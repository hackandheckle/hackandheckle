---
title: Interview with Joe Albahari at Yow 2013
date: '2014-01-08 08:38:39'
tags:
- yow2013
---

At the Yow 2013 Conference in Brisbane we had chance to catch up with Joe Albahari the author of linqpad

Transcript is available over the page

<a href="https://drive.google.com/open?id=0B3KFoVQ01nUJQVIxQkd1UnJ2Yzg">Show audio file</a>

<!--more-->

Ben:	Hello, welcome to Hack and Heckle. Joining us now is Joe Albahari, who’ll be discussing his presentation at the 2013 YOW Conference about solving the hard problem of concurrency. 
Darren:	Now, I’ve got an interview with Joe Albahari. He’s doing a talk on the concurrency trend for solving hard problems with concurrency. Would you like to introduce yourself to some people listening?
Joe: 	Sure. I’m the author of C# 5.0 in a Nutshell which is a nutshell of over a thousand pages and more of a coconut …
Darren:	Yeah, a bit of a coconut, yeah.
Joe:	… than a nut and also LINQPad the code scratch pad for .NET languages and SQL.
Darren:	Thanks very much. So, you talked today. We haven’t seen your talk yet, so I know that you’re interested in concurrency through non-immutable [states 00:00:52] Is that correct? Would you say that’s correct?
Joe:	That’s half of the story. Avoiding immutable state is one way to avoid all the problems that concurrency and shared right at the state. But that’s only one way to do it. The other way is to avoid the concurrency. A technical an answer, but …
Ben: 	Is that by non-blocking or is that more just not needing to be concurrent or what state?
Joe:	Yes. It’s about non-blocking in that a lot of the times that we use concurrency, particularly, in rich client applications which have some of the worst thread-safety challenges. A lot of the time when we are using concurrency what we actually need is temporal, time-based code. We don’t necessarily need concurrent code. We need temporal code, asynchronous code. What we can do is if we explicitly imbue our code with temporal logic, time-travel logic, [await asic 00:01:50] we can then voluntarily take on some of those simple time-based concerns and then avoid all the difficult part concurrency concerns by doing that.
Darren: 	Okay, so I should call you the C# Doctor?
Joe: 	The Time Lord.
Darren:	The Time Lord, yeah. That’s quite apt. So, for some people who haven’t really looked at this, would you be able to explain a bit different from the imperative short state they’re used to with their MVC razor view .NET web apps, if you know what I mean?
Joe:	Well, this approach is compatible with imperative programming, so it doesn’t require that you go functional and you get rid of state. Now, going functional is good wherever you can. If you can avoid the state, that’s another great way to solve it. That’s one of the first things you look for. In the case of a rich client, you cannot really avoid state. You’ve got controls and text bots and so on. You can’t turn that whole thing into a big link query, you still need that state.
	Now, you’re talking about MVC and running on a server. That is a slightly different problem. You’re running on a server. You’re not so much concerned about thread safety because there don’t tend to be a lot of shared states anyway. So, you’ve got a number of requests that can be in parallel coming on web server. They don’t tend to interfere with each other generally. 
	So, your concern is not so much about thread safety. It’s more about thread efficiency, particularly if you’re writing a server which needs to talk to other servers. For instance, if it’s running on a cloud, if it’s running as a cloud service, then it needs to talk to other cloud servers. In those kinds of cases, if it’s making a lot of concurrent requests of the servers and those servers may be in different data centers then that can represent, potentially, a lot of locking quests that can be running, consuming a lot of threads. Those threads can actually get quite expensive. 	
	The idea of them going for a time-based rather than a concurrency-based model, so instead of blocking, you then do, if that, and waiting, you do literally time travel, literally time. Rather than coalescing all your operations onto a single VR thread, just like a thread station, you’re coalescing them onto this small pool of all threads. It’s very efficient and fast and minimizes the resource consumption. That can make a big difference, particularly, on any cloud servers 
	On cloud servers, we know exactly how much it costs per megabyte of RAM because we pay for it. The size of the instance is quite important to the cost of running it. So, if you only need a medium instead of an extra large and they need 100 extra large, instead of 500 extra large, it’s a huge saving. This is a really, really easy way to get that saving because it really means you’re adding, using a few extra [kiloids 00:04:40] into the language, voluntarily taking on temporal time-based concerns. So, you avoid blocking and you avoid difficult concurrency considerations. 
Darren:	When you say is that like perceiving premise of the future so I then attach the future icon code lock to the asynchronous callout Is that correct?
Joe:	Absolutely. See, a task is a future. That is what you will wait on. That is your unit of time travel is the future. You don’t horde into when that future completes with a value.
Darren:	I haven’t done any futures coding myself. Have you done a little bit of it?
Ben:	Yeah, I’ve been doing a little bit. I’ve been doing a reactive programming course I’ve done some in the past as well. Just very basically, it promised a future state. So, is that, a little bit DUI-based application you would say? How do you get those contacts you use? That’s a good [inaudible 00:05:26] basic code that I’m reasonably sure this is going to complete, but it never comes back and uses that [inaudible 00:05:32] How do you … ?
Joe:	Okay. There’s a couple of points there. The question about what if something never completes? Then what you need to do is introduce a timeout. That would be the norm, no matter what your architecture is. So the question is, how do you do that elegantly with futures? Normally, you would hope that the methods you’re calling, the asynchronous methods that return futures, have the option to specify the timeout, but if they don’t then you can write your own [combinater 00:06:01] to take M future in which there is another future that times it out. 
	So, another one of the benefits of using futures is we get composability. So, if you have a method that doesn’t have a timeout and you just want to apply timeout, you can write a function now that takes a task in, eight times that, your timeout returns another task out. It’s another possibility. You can program with them and you can use them as building blocks and put them together nicely.
Ben:	That also allows you to cancell tasks as well. Well it’s a slightly separate problem probably.
Joe:	It’s related, but the principle of cancellation is similar.
Darren:	What about the interaction back with the user? How does the future interact back with the primary thread normally? Do you recommend?
Joe:	The way that the await keyword works. The way that this time travel works, you jump into the [tarvass 00:06:51] and then if you jump into the tarvass on the UI thread, you’ll come back. When you come out of the tarvass, you’ll come back onto the UI thread at that point. That’s a function of the runtime, the way it works in the wait.  It picks up the current synchronization context, this. It’s a rich client synchronization context. So, it posts a continuation to that context. 
	So, it will automatically, by default, always come back onto the UI thread if you went in only one thread. When it comes back, it will re-throw any exceptions. So, if that task faulted, it will then have re-throw your exceptions back to the quarter. So, simply by doing nothing, you fall into a bit of success when it comes to exception handling.
Ben: 	So when you say, “Rich client,” are you thinking of HTML website or are you thinking of installed application 
Joe:	It’s installed applications. So, you’re looking at any of the Windows, Windows forms, WV app, or any of the, if you’re using Zamarin and you want to target a native app on IOS or Android, then that’s the model you would use.
Ben:	Well the problem with http is you don’t get to reply backYou can still have futures within that HT thread, but once I would send a response back to the browser that’s it you can’t come back to me again in the future saying wait I’ve finished now
Darren:	It’s a bit harder? You’ve been saying that you can do stuff like web sockets or something to stay in those locations as an individual client.
Joe:	Are you talking about javascript and scenario?
Darren:	You certainly [inaudible 08:08:27] on MVC and the fact that the UI thread, it disconnected from the server thread which you may push the future onto. So, at which point am I able to come back to tell the UI to update?
Joe:	If you’re in a MVC app, then it won’t come back on the same thread and you don’t want it to come back on the same. There’s no advantage in that scenario. You don’t have a thread-safety problem. You have more a scalability issue and the benefit you get in that scenario.
Ben:	In the other talks, that you’ve seen in the conference that you think are exciting, are there any highlights have you seen there?
Joe:	Well, there’s a talk coming up on reactive extensions which I plan to see.  That’s another part of what I’m talking about myself. Also, the workshop I’m giving is reactive extensions. That’s the other kind of latency problem. Futures address latency problem. Observables address another kind of latency problem and something I’m also covering in the workshop and in the talk and tell them how those two play together. 
Darren:	Okay. All right. Thanks very much.
Ben:	Thank you.
Joe:	Thank you.


