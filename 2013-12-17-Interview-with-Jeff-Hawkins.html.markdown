---
title: Interview with Jeff Hawkins
date: '2013-12-17 09:23:17'
tags:
- interview
- yow2013
---

At the recent 2013 yow conference in Brisbane we interviewed Jeff Hawkins on computing like the brain.

The transcript of the interview is available over the jump

<a href="https://drive.google.com/open?id=0B3KFoVQ01nUJM0QtY2J4Y2kybm8">Show audio file</a>

<!--more-->

Benjamin:         Hello, and welcome to Hack and Heckle. Today we've got an interview with Jeff Hawkins who was the keynote at the recent Yale conference on "Computing Like The Brain: The Path to Machine Intelligence."

Leigh:                 Leigh. Hi everyone. We're here with Jeff who just did a talk on computing like the brain, machine intelligence and all that good stuff. I guess we've just got a few follow-up questions which I know I'm keen to hear your thoughts on. One of the things that I was thinking about during your talk was emotion and what role it plays in all of this, and the decisions that are made by humans are largely guided a lot by emotion, and how that fits into the research you guys are doing.

Jeff:                     Yeah, so what I talked about was the neocortex which is 80% of the bottom of your brain, and that builds a model of the world, but the neocortex itself is not the center of emotional content in the brain. There's the subcortical.

Leigh:                 Yeah.

Jeff:                     And so you can understand how the system builds a model of the world, but if you wanted to build a human, or something that had intent or desires, you'd have to build an emotional component. Today, our models are very, very simple. We basically say we want to be learning now, or we don't want to be learning now. That's the extent of our emotions.

Leigh:                 Yes.

Jeff:                     Turn on learning, turn off learning. But in a human, emotions are much more complex, they relate to a lot of things being a biological entity, and recreation, and hunger, and all that stuff. We're not trying to do any of that stuff. What it basically falls down to in modeling the neocortex is, when do you decide to learn something, when do you decide not to learn something, and how can you assign-- and we have an ability to turn the rate of learning up or down. And that would depend on the application area. In our case, when we talk about using our technology in Grok model server data, we're just constantly learning. There's never an emotional component to it. It's just constant learning, constantly trying to model something. In other situations, you might want to have a variable learning rate, but we're really not even trying to capture that emotional component.

Leigh:                 Okay. Is it something you're thinking about at all, or talked about?

Jeff:                     We've talked about it a lot to the extent that I just mentioned. But again, it's in my talk, there's no goal here to build human-like things.

Leigh:                 A   human, yeah.

Jeff:                     There's no intention whatsoever. We're not talking about machines that you can have a conversation with and talk about the latest sports or weather. There's none of that.

Leigh:                 That's right. You mentioned it was like a tool for humans to use.

Jeff:                     It's a tool. Even though we are- If you think about a human, we have the same brain that a reptile has. But we have this huge thing on top, which is the neocortex, which adds a very deep model of the world. But we're still very emotional animals, just like other types of animals, non-mammals. But we're not trying to do any of that. We're just trying to capture the ability to learn the structure of the world, or a structure of some particular part of the world, and use the lay as a technology, and not building animal-like, human-like, reproductive anything.

Leigh:                 Absolutely. One of the other thoughts I had as well, during your talk, was that, given the model that you guys have with the special data and how it's represented, if you're able to give certain types of input sensory inputs that humans don't have, have you guys thought about the fact that we might not even be capable of understanding the questions that we're able to ask this machine?

Jeff:                     Well, I certainly think that, as humans, we spend a lot of time trying to understand problems where we don't have a good sensory input for it. You think about people who study protein solving, or biochemistry, or people who study astrophysics, or cosmology. They're trying to understand things we cannot sense directly. So we spend a lot of time coming up with tools to make things that we can now sense as humans. So I think that gets to the point of your question. We go through a lot of steps to make it so we can think about these problems. You could build machines that generically think about these problems, that are interfaced directly to them, that work at different speeds, different scales and time, different types of sensory inputs, and those machines will still work like a cortex. I'm not sure if you're going in this direction, but I don't think we're going to get to a point where these machines understand things we can't understand.

Leigh:                 Yeah, that is kind of where I was going.

Jeff:                     I don't think so. I mean-

Leigh:                 Because we're limited to the context and sensory input we have, if you give a machine another sense that we have no concept of, how that would react with our context-

Jeff:                     Take my talk as an example. I've spent pretty much a lifetime trying to understand how brains work, and I now have a pretty good model for a lot of it. It's very clear to me, simple for me to understand now. But I realize when I talk to an audience like this that's never been exposed to it before, there's a huge learning curve. There's a huge amount of things that I understand that they don't understand yet, but they can understand. If I spent more time at it, we could expose it to multiple times [crosstalk 0:04:45]

Leigh:                 It comes as a learning thing, we're capable of realizing things that we don't currently realize, through our learning.

Jeff:                     We haven't found anything yet, any kind of knowledge, even weird, obtuse, abstract knowledge, that a human can't learn, given the proper tool.

Leigh:                 Yeah.

Jeff:                     We are able to learn very odd things that we wouldn't normally learn in our life. [crosstalk 0:05:05]

Leigh:                 I guess the funny thing, what I was thinking, is that the famous, "What is the meaning of life? It's forty-two," to the computer, was a perfectly reasonable answer that we humans, without the same sensory inputs, weren't able to understand that answer.

Jeff:                     What's going on in brains, it's very, very difficult to know what's going on inside of a brain, extremely difficult to even probe it. People understand how hard neuroscience is. But when we do this in software and hardware, it'll be completely transparent, it's very obvious. We can go in, de-bug our systems, look at what's going on, and try to understand the representations they form. We do that. When our models don't work correctly, or even when they do work correctly, we sometimes want to dig in and figure out, "How did it get to that answer? What did it learn?" It's not easy, but you can do it. It's not like these systems are going to be off in some mysterious land, thinking things we'll never understand. (laughs)

Leigh:                 (laughs) Yeah, we're there along the way. Every step of the way.

Jeff:                     That's right, it's just technology. It's really cool technology, and it's kind of a big impact, but you have to talk a while to stop thinking like humans. (laughs)

Leigh:                 Yeah, absolutely. All right, bringing it back to Grok, your product, which is your Amazon server, it's just that some of the people listening won't actually have heard of it, so, do you want to just-

Jeff:                     Yeah, it's really cool, we basically have a way of monitoring metric data coming off of Amazon instances or services, in a very automated way. By the way, Grok is in private beta now, so you can join if you want, just come and tell us. But eventually it'll be available on the Amazon store, probably the beginning of the year in the Amazon Marketplace. Essentially, you create an instance, a low-cost instance, and you send data from your applications to it, and Grok models the data. It can detect- What Grok does is it learns what's typical behavior for your environment, your instances, your applications, and it can detect when that changes, when the underlying patterns in the data change. It's very good at this. It can say, "Given the last month of activity, the last two weeks of activity, the thing that's happening now is unusual. Now, how unusual is it? Well, it a 1% likelihood that it's in the state, or 0.1% likelihood, or 0.01% likelihood." We can tell that. So what it can do is come back and give you an ordered list of, say, all the things you're monitoring, and these are the ones that are most unusual right now. Right at eleven o'clock today, this thing became a little bit wonky, and why did that happen. The cool thing about this is, I think this is a really great application, it's very valuable, but the way we're doing it is really cool too. We're building these brain models essentially for all these metrics. Of course, as a user of Grok you don't need to know any of that. It's plug-and-go.

Leigh:                 Plug-and-play, that's the best way to do it.

Jeff:                     (laughs) Yeah, plug-and-play. [crosstalk 0:07:59]

Leigh:                 You're in private beta now, have you got an idea of when you're going to be launching at all?

Jeff:                     It's a little too early to know when we're going to come out of private beta. I mean, we literally started the private beta two weeks ago.

Leigh:                 Okay, so it's recent.

Jeff:                     Yeah, but the goal-

Leigh:                 Are you getting a lot of good feedback?

Jeff:                     Yeah, we are! There's a lot of interest in it. We were at the Amazon re:Invent conference in Las Vegas like three or four weeks ago, and tremendous amount of interest in it. First of all, there's a lot of interest in an anomaly detector. I mean, it's unbelievable. People who spend a lot of time monitoring servers, they get sick and tired of getting alerts and pages in the middle of the night, and they don't know what's going on. It's just an area that needs help. People have applications that span thousands and thousands of servers, and they have monitoring tools, they have all kinds of stuff, but not really happy with what what they've got. So, that reaction was great. We're just starting out, and we'll see how it goes. We think we'll be on the Marketplace probably somewhere in January. We'll still be in a beta program, but when you're on the Marketplace you can't be in a private beta program. So you can contact us now, we'd be happy to-

Leigh:                 What's the plans for Grok? Are you going to stay within the IT in the Amazon ecosystem, or...?

Jeff:                     We don't know yet. Amazon's a great place to start, it's the gorilla of, you know, 800-pound gorilla. There's a lot of places we can go within there, we could also go to other com providers, whether it's a company like Rackspace, or Microsoft reserve. We have people who want to do custom applications within any one of these environments, so they want to focus on a particular type of application that might be running on a cloud. We have people who want to do non-com applications, they want to do this behind- on-premise solutions, we can do that. So these are all areas we're interested in going to. And then there's the opportunity to go outside of IT.

Leigh:                 Yeah.

Jeff:                     We actually started using Grok looking at energy, and looking at machinery. We looked for anomalies in wind mills and blast harnesses and all that, and energy metering data. We could do all this stuff. The reason we chose IT and Amazon is because it was an environment where you could literally just plug-and-play, click-and-go. Where all these other spaces were complex in terms of getting the data, you need-

Leigh:                 Yes. Do you also have a lot of machinery required to fit the sensors in some of the pieces.

Jeff:                     Yeah. They often have the sensors already, but they don't have an easy way to get the data, believe it or not. You'd be surprised. You say, "I want to stream the data from this machine every five minutes to this server." Often, that's nearly impossible.

Leigh:                 I did a lot of integration work, and I've come across a lot of FTP jobs and CSE files [crosstalk 0:10:51]. I'm not surprised.

Jeff:                     Exactly. And you know how the format's changed, and they screw it up, and people decide to leave this data because they didn't think it was useful. All that stuff gets in the way. We're going to make our engine available and our source code for our mobile app available, and we think people are going to approach them with interest, and take the Grok technology and apply it to these custom areas. But they're going to have to have a lot of domain expertise, and we're going to have to learn how to sell into that space. But all that'll happen. I really believe that we entering a world that- the Internet of things, if you want to call it that. Zillions of billions of sensors. How are you going to take advantage of these sensors? You have to have automated modeling. There's no way in the world you can take advantage of sensors that are collecting data every second, every minute, without automated modeling, and you have to have these properties I talked about. They have to be continuously learning, they have to be looking at temporal, spatial patterns. The world has to go in this direction. You can't hire a bunch of data scientists to look at ten million-

Darren 4:           That makes a lot of sense. There was a Darren last year who was talking about how they store their data, and basically to get anything you want you have to remodel, because they're not sure what they want at the point of collection.

Jeff:                     I know, it was in the [Kinsey 0:12:02] report that came out that says we need six hundred thousand new data scientists next year. That's not gonna happen! (laughs) And when you have high-velocity data, as I mentioned in my talk, you don't really have a lot of time. Literally, the data we're looking at coming off of computer servers, it doesn't matter what happened a month ago. Who cares? It's what happened yesterday and the day before. You're looking at financial markets. You're looking at any kind of high-velocity stuff. You have to be constantly learning, constantly updating to what's happening now.

Leigh:                 Have you done anything with actions that you were talking about, the analysis and prediction? [crosstalk 0:12:40]

Jeff:                     What I mentioned was, brains are essentially building a motor model of the world, right? They're constantly interacting with the world. What we've created so far is like a brain with an ear, but it has no ability to move. So it's very useful, but that's the analogy of where we are right now. This is an area where I'm actively working in, I actually have made some progress, really significant progress, on my plane ride over from the States to Australia.

Leigh:                 I bet. You had plenty of time of that plane ride. (laughs)

Jeff:                     I did have a lot of time. I was reading a bunch of papers, and then I was working on this problem, and there's a lot of people in our online community, the NuPIC community, which your listeners should check out, it's at numenta.org-

Leigh:                 Yeah, I think we've mentioned it before.

Jeff:                     There's a lot of people there interested in robotics. At our last Hackathon, we had three teams that did motor-related stuff. Very early, one guy was using the CLA flood copter, another guy was doing some [crosstalk 0:13:34] But I think that it's an area that needs a lot of work and exploration. I gave a talk at Hackathon about what we know about the solution to it. We know a lot. It's just a matter of focusing time.

Leigh:                 Has anyone come to you in financial services? What you're talking about, pattern matching, prediction, falls heavily into what I would consider to be interesting to day trading and [crosstalk 0:13:57]

Jeff:                     Here's what I believe about it. First of all, I don't think it's possible to use Grok or a brain of any sort to predict the price of Apple computer [inaudible 0:14:04]. You have to find structure in the data. The brain in our models finds structure in the data. Typically when you have a thousand different competing algorithms, you can't find the structure. However, there are things we can do. We found that we were pretty good at, very good actually, at predicting volume of trades. We had a lot of interest in people wanting to model individual traders. You remember the London whale, these rogue traders getting into trouble? This is a big problem for financial services companies. They want to be able to detect individuals. Now, if you monitor the trades from an individual from a group, you would be able to find a lot of patterns in there. Then we could detect when they do something unusual.

Leigh:                 An anomaly.

Jeff:                     Yes, anomalies. So while I think there are applications in the financial services sector, they're not predicting the stock price.

Leigh:                 (laughs) There are other ones, just taking that day trading that actually completely ignored the stock price and looking at volume of trades so that they're behind the ball, consistently behind the ball with that? [crosstalk 0:15:00]

Jeff:                     Again, the way I think about it is you want to find something where- The ideal actual use of this is just trying to monitor lots and lots of things, because you can build lots and lots of models, and the models- There are only a few causal things in the world that are making the data change. Again, I don't think anything that you're trying to do trying to predict the stock price is just going to be crazy. But we can predict volume. That, we're pretty good at. We showed that. I want to try to move away from people saying "I'm going to make a lot of money off of this," as opposed to, "Hey, I can do something really interesting."

Leigh:                 "I could do a really interesting thing," yeah.

Darren 4:           I would agree with that. I was just thinking that finance normally drives innovation, because you've got the cash to do something.

Jeff:                     Yeah. We also found that in a lot of these financial firms they hire lots of mathematicians and machinery. And they actually don't want to use outside tools, they don't want to use anybody's thing. [crosstalk 0:15:58] Yes, trade secrets. So, it was a complex space. Look, our source code is open source. I wouldn't be surprised if some of those guys take it and do something with it, but they won't tell us about it.

Leigh:                 They're very secretive.

Jeff:                     (laughs) They're very secretive about it.

Leigh:                 Well, Jeff, thank you very much for giving us your precious time for this, and we hope you enjoy your time in Australia.

Jeff:                     I'm having a great time here. This is a great country. My first time, I'm enjoying it tremendously, so-

Leigh:                 Great, great!

Jeff:                     Thanks for talking to me, and hope you tell your listeners again, numenta.org, you can look at groksolutions.com, and join the email list at the open source community at numenta.org, and you can ask questions, all the questions they want. I'm active on that email list too, so-

Leigh:                 Great! That's good to see.

Jeff:                     I'm not active this week. (laughs) I'm not keeping up with it this week.

Leigh:                 Brilliant. Thanks Jeff.

Darren:              Thanks very much.

&nbsp;
