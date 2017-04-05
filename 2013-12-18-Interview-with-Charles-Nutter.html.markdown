---
title: Interview with Charles Nutter
date: '2013-12-18 10:55:40'
tags:
- yow2013
---

At the Yow 2013 Conference in Brisbane we had chance to catch up with Charles Nutter who works on the JRuby Project.

Transcript is available over the page

<a href="https://drive.google.com/open?id=0B3KFoVQ01nUJazJDUmdGSzd6Y2c">Show audio file</a>

<!--more-->

Ben:                    Hello, welcome to Hack and Heckle. Joining us this time is Charles Nutter, who will be discussing his presentation at the 2013 Yale Conference.

Darren:              We're from podcast Hack and Heckle, here in Brisbane, we're a multi-language podcast. I do Java and Ruby so I know you well. First of all, I would like to say I enjoy your Blog. I think it's very informative and I like the detail that you go to. It would be much more detailed than I would ever go to and I think that's quite good. I attended your talk on the JVM. But do you want to give yourself a quick intro for anyone who hasn't heard of Charles Nutter?

Charles:             Sure. Charles Nutter. People just call me Charlie mostly. I've been working on JRuby full-time for about the past seven years now. First at Sun then Engine Yard then Red Hat, but over time as we've solved the problems of making JRuby fast, of making it work well, finding a lot of edge cases in the JVM to fix and work on. That's kind of what I was talking about here today.

Darren:              So do you think that people here using Rivers should be moving over to the JVM or do you think the forking issue is so major?

Charles:             Well, we've never really tried to convince people that they should just move to JRuby because, obviously we think it's better for a lot of reasons, but until you hit the point where standard C Ruby, MRI is not good enough for your application, we just say continue doing it. I mean there are good reasons to use MRI, good reasons to use JRuby. We've always figured that as applications grew up, needed more resources, needed better use of hardware, then people would start to come to JRuby and that's what we're starting to see now.

Darren:              Yeah, still think it's a bit strange where a lot of people who have moved to Ruby have come from Java, so then they really don't want to go back to the JVM as they see it as a step back irrespective of the possible performance benefits. Would you agree with that?

Charles:             Yeah. We often joke that our least favorite part of JRuby is the fact that the 'J' is in the name. If the original folks who had started the JRuby project ten, twelve years ago, if they had had the foresight to call it awesome Ruby or fast Ruby we'd probably have a lot more adoption, because people wouldn't see that 'J' and run screaming away from it.

Darren:              Yeah, I thought was so funny. So coming back to your talk, do you want to just go through some of the frame works that you mentioned, the extensions to the JVM that you're looking for some contributors to join?

Charles:             Sure, so I approached the talk just trying to figure out what are the things that make people not choose the JVM. One of the big ones for us has been startup time, so I covered a library called Drip that basically preloads the JVM in the background, gets it ready for you so that your next command that you run is much faster and seeing easily the order of magnitude faster JRuby startup using Drip. I'm trying to get more folks aware of that. The next one that we hear about a lot is being able to call native libraries do [inaudible 00:02:53] like things, use native memory and for that we talked about the J&amp;R library that we've been promoting and improving over time. It allows you to write just plain Java code and call into native code at any time and do all the stuff you couldn't do on Java before.

Then I talked about some more VM level stuff and both dynamics being the way we're working on better performance for JRuby and other dynamic languages and then the Truffle and Graal project coming out of Oracle that are kind of looking beyond what JVM byte code can do for us, finding new ways to implement and optimize languages on JVM. There's a lot of really cool stuff and pretty much all of the things people complained about or said that, kept them away from JVM are being solved by someone.

Darren:              So I think first of all it needs to solved and second of all it needs to be marketed back to those developers because they might not be fully aware of those benefits that are, problems that are now being resolved or?

Charles:             Right.

Darren:              At least partially resolved.

Charles:             Right exactly.  And both dynamics people may know about it from just a marketing perspective because it was one of the big bullets for Java 7's release, but overall most of these projects are still unknown to people and they really do provide some interesting solutions that nobody thought were solved at this point.

Darren:              But from the implementation perspective does Java 8 the upcoming release of Java 8 actually simplify things for you guys with Lambdas embedded in the language or does that have no bearing?

Charles:             Not really. The Lambda support that is available for Java 8 it's largely Java language [inaudible 00:04:25] so other languages, there's not a whole lot to be gained from that. What they have done though is taken a new look at how, some of the collections libraries and other libraries in the JDK can better fit Lambdas and so for those of us who have closures or blocks like Ruby, can start taking advantage of those modifications to the collections libraries. Deeper than that because Lambda in Java 8 is implemented in terms of invoke dynamic it uses that for some of its dispatch and bootstrapping. It means the JDM guys are going to have to make invoke dynamic even faster, solve some of the performance issues that have taken a while to get to. So we are benefiting, but not in a direct way.

Darren:              So you'd say most of the problems apart from the fork issue, the fork in the JVM, are on the road to being solved?

Charles:             Yeah, I think largely they are in one way or another. And you know the forking question came up, it's a popular way to do process management in the Ruby world, but I think we can find other solutions that are just as good. Ideally get people to wrap that process management behind an API and use something like Drip or a multitenant JDM or and other options so I don't think it's a serious limitation as far as  JRuby goes.

Darren:              What do you think, it's more to do with they need to start looking at thread management rather than using forks?

Charles:             Right and that's where a lot of folks exactly end up getting stuck on fork verses using threads. On MRI you don't actually have real concurrent threads so the only way you can do that is by spinning up another process that leads to forking libraries to get concurrency and then that doesn't work on JRuby where threads would have just worked fine. So as more people know the right way to do concurrency as we have more community leaders come up with concurrency libraries that can mask that all away then maybe use fork, maybe use threads because you're never going to know. It's more at the level of the library at this point.

Darren:              Okay.

Ben:                    Now once someone’s actually implemented that, implemented using fork that, that creates a big barrier to the adoption of JRuby. Is that …?

Charles:             It definitely does, it definitely does. What we've seen over time though is that folks directly calling fork from their own code is becoming more and more rare. Usually if you're doing it for concurrency you'll call into a concurrency library that may happen to use fork. Or if you're doing it for process management you'll call into a process management library and in every case there's an alternative way that's non-forking, using threads for concurrency, doing some pre-launching of additional processes that aren't forks. It's just improving over time and we still get reports from people that really wish they could fork the JVM, but more and more they're using a library that hides all that stuff.

Ben:                    Do you see much library support moving towards the threading model or is not known [inaudible 00:07:04]

Charles:             A lot of folks are moving to a threading model and the adopting curve over the last year has been two or three times as many folks as the year prior are using JRuby now. It seems like a lot of that is concurrency driven. We have been hearing from people that they just can't scale their application without massive [EC2 00:07:23] costs or hosting costs, they make a move to JRuby and drop their costs by a half or down to a quarter of what it was before, simply because they can have a single process do all the concurrency rather than a massive amount of memory from many processors. So that's where we're getting a lot of our adoption curve now. We're also seeing as we work out the last performance bumps in JRuby, more and more folks are moving over just to get straight-line performance well. So it's looking pretty good as far as adoption these days.

Darren:              Yeah, I was quite impressed with the metrics that were showing.  I haven't heard of drip, it looks like something I'll definitely have a look at.

Charles:             Yeah, the drip stuff we're doing a preloading startup of JRuby. That could be the holy grail for us. Whenever we've asked why Rubyists haven't moved to JRuby, nine out of ten responses are due to startup time. So if we can find a way to make drip fit nicely into a typical Ruby development process we may have solved the last mile as far as adoption goes.

Darren:              Yeah, yeah. Like when I'm doing stuff on the command line even if I was intending to maybe use JRuby on the server I'd probably still use an MRI just because of the straight command line integration, but if drip is able to come up with, and sometimes better performance than yeah I think that's something I definitely will be having a bit more of a look at.

Charles:             Yup, exactly.  We do have some folks who use MRI as their development environment, but obviously if drip makes it possible for you to have the same development environment as test and production then that's the ideal way to go.

Darren:              Yeah and then I wouldn't really be arguing about things that are different on the server from the local machine, any of those issues can be flushed out on the [inaudible 00:08:54] machine?

Charles:             Right, right, exactly.

Darren:              So that makes a lot of sense. Yeah although I spend a lot of time still in Java land. I assume you would spend most of your time in Java rather than in Ruby coding?

Charles:             Yeah unfortunately since JRuby is still implemented mostly in Java that's where I spend a lot of my time. Of course I'm also working from Tyler performance optimization and stuff, but over time as we add Ruby 2.0, Ruby 2.1 features, more and more often we're just writing those features in Ruby code and so the Ruby part of JRuby is growing over time and if there's a missing feature we're happy to accept the first version of it in Ruby and then maybe only port it to Java performance wise if we need to.

Darren:              Okay, yeah that makes a lot of sense.

Charles:             Yeah. It feels pretty good these days.

Darren:              So are you having a nice conference is there any speakers in particular you want to go see?

Charles:             There's a talk later today on a the disruptor concurrency frameworks.  I want to see that one and ...

Darren:              It's Michael Baker, Michael Barker?

Charles:             Yeah Michael Barker that's right.  I had some talks with him, he's also in the native space a little bit and understands some of the concerns that we are trying to address with J and R.  I caught a couple of the other good talks. I very much liked [inaudible 00:10:07] talk on dark verses new speak and kind of tradeoffs and features and constraints. Daniel Spiewak talk on functional and object and how they're kind of evolving together.  I'm very much on kind of a either language side or low level VM optimization stuff, so those are the talks I'm catching.

Darren:              Oh, I see.  Well thanks very much and I hope you enjoy your time here in Australia.

Charles:             Yeah, thanks very much.

&nbsp;
