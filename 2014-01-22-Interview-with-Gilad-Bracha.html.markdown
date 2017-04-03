---
title: Interview with Gilad Bracha
date: '2014-01-22 08:15:05'
tags:
- yow2013
---

At the Yow 2013 conference we had a chance to interview Gilad Bracha who works on the Dart language at Google.
<iframe style="border: none;" src="//html5-player.libsyn.com/embed/episode/id/2643002/height/75/width/640/theme/standard/direction/no/autoplay/no/autonext/no/thumbnail/yes/preload/no/no_addthis/no/" height="75" width="640" allowfullscreen="" scrolling="no"></iframe>
<!--more-->

Darren Rogan: Hello and welcome to Hack and Heckle. Today we have an interview with Gilad Bracha who works at Google on the Dart language.
Joining me today is Gilad Bracha, is that correct?
Gilad: Close enough. Usually Gilad Bracha is what English speakers should say because they gag otherwise.
Darren Rogan: How do you pronounce it?
Gilad: Gilad Bracha.
Darren Rogan: Okay, I've got no chance.
Gilad: Yeah, I don't ... That's okay.
Darren Rogan: So we're doing a talk here called Expiration in Next Generation Web Languages, and you were just saying before we started that it's more about languages themselves that are related to webs. Do you want to just give a quick synopsis of [crosstalk 00:36]?
Gilad: Sure. Two languages, one is Dart. Dart is the language we're working on at Google for web programming. It's designed to make it easier to develop large-scale web apps, especially for people who might be uncomfortable with JavaScript, people from a more traditional software engineering background, Java, C Sharp, whatever. But generally it's more structured. The larger your apps get, the more you need kind of some sort of standard structure. We have classes, we have a form of type-checking, which is interesting, type-checking. We have standard library, we have all kinds of things that you don't get in JavaScript, which is proving to be very useful at Google, and it's open-source and we're putting out [crosstalk 01:24]
Darren Rogan: Is there a dependency-management framework in it, or ...
Gilad: There's, I'm not sure what you mean here, there is a package manager that ...

Darren Rogan: Yeah, package manager.
Gilad: Yeah, yeah sure. Lots of the usual paraphernalia that you really want to have standardized is that bit of an issue in JavaScript. There's a lot to choose from there, but you have to make the choices, then other people have made other choices and they don't inter-operate, so it's a big problem. There are lots of other issues, but just to give you an idea of what Dart is about.
The other language, Newspeak, is a language that I developed a few years ago that is much more, I guess, radical. Dart is aimed at more mainstream adoption, where at 1.0 it's something Google's putting out and using in its products.
Darren Rogan: I have heard of it but I haven't actually spent any time looking at it, although Newspeak, I haven't actually heard of that one.
Gilad: Yeah, I'm not terribly surprised, right, if you're not reading the programming language research literature or are hardcore, you probably haven't because it doesn't have ... it's a small kind of labor-of-love kind of thing, it doesn't have a lot of backing. I had some funding before the crash in 2008, and after that it's been more a volunteer, open-source thing.
Darren Rogan: What would be the difference between it and Dart?
Gilad: Newspeak is really trying to push the envelope in a lot of ways, so it has very powerful modularity properties, probably more powerful than any language you've seen. The sort of simplistic way of putting it is dependency-injection built into the language. I don't particularly like that, but it's something that maybe people can relate to without my giving a half-hour explanation. It's also comes with its own, it has an ID written in itself, it's very flexible, with a lot of ... I don't know if you've heard of Smalltalk, but it's in the tradition of Smalltalk and Self, but with a bit more, mainly modularity and security brought in mind.
Darren Rogan: Okay. Language construction, something that I would imagine it's a quite difficult field to get into, quite small. I remember when I was at Uni studying compilers I thought "this would be lots of fun but I'd never get a job."
Gilad: It is, getting a job in this is not something you can really reliably plan for. Mostly it's, most people who do this in academia, there are very few of us who manage to get paid full-time in industry to work on this. You really have to be very specialized, right? That's certainly true. It's not just compilers. Compilers is comparatively easy to get a job. There are loads of, relatively speaking, from my perspective, loads of people work on implementation, but actually language design and so forth, there are very, very few and we all know each other, right? Microsoft, Google, used to be at Sun. I spent a lot of time working on Java as well and other things. Yeah, it's a very specialized [fun work 04:27]
Darren Rogan: It seems it would be quite enjoyable as well. It's one of those jobs like a referee. No one's going to, any time they had a problem, they always blame the referee at the end of the day. Thankless job, you know what I mean?
Gilad: Well, I know exactly what you mean, but it's nice work if you can get it. If you really, people care about programming languages in a quite irrational way, right, because it's in your face all the time. It's what you're actually ...
Darren Rogan: [inaudible 00:04:54] Crawford. You've seen the discussion that Pascal guy wanted a knife fight over disregarding a type system?
Gilad: Ooh, I missed that. I've been in those fights all the time and I've played both sides of the street actually on that. Sure, it's almost like religion, right. It gets very passionate, very emotional, and it's really important to people the language they work on. There's a lot of discussion of the pro's and con's and technical reasons, but in the end there's something more going on here.
Darren Rogan: Emotional decisions.
Gilad: Yeah, yeah.
Darren Rogan: So would you say that Dart is going, hopefully, to be a successor to JavaScript? Is that what ...
Gilad: That's not really what we're after. That is the one-line characterization that a lot of people have put out.
Darren Rogan: Yeah, I've heard that myself. I haven't really looked at it.
Gilad: Yeah, it's not necessarily very helpful. We're trying to give people a meaningful alternative. We think that competition is good, choice is good. Having people confirm a fact that the only language you can use on a web browser realistically is JavaScript is, that's not going to last. The world doesn't work that way.
Darren Rogan: It's also depressing as well, a little bit.
Gilad: Yes, but, I don't want to get into that particular war. Lots of people are going to compile to JavaScript. The difficulty is that, unless you have a lot of resources and expertise, you're going to lose performance in that transition, or else your language is so close to JavaScript it really didn't matter in the first place. It's easy to make some sort of easy ...
Darren Rogan: Yeah, DSL basically on top of JavaScript.
Gilad: Yeah, but unless it changes something important, it's not that interesting. If it changes something important, you'll find that it is not easy to compile to and you need resources to fly all these kind of things to make compilers really work. Dart basically, the JavaScript that you get out of Dart runs about as fast as the JavaScript you run by hand. Oddly enough, we couldn't believe it at first, but it turns out in some cases even faster, because the compiler sometimes does some optimizations that a reasonable person wouldn't do. We're in that ballpark, so you're not really losing any performance by going to Dart. Basically there isn't, in our view, there isn't a downside, but that has taken a lot of clever Google engineers a fair amount of work, and many language projects will not have those resources to do that.
Darren Rogan: Would you say there's much of an uptick towards Dart?
Gilad: There's an uptick. First of all, Google had multiple goals with this one. The most important one is to make Google more efficient, right? So we invest no small amount in web programming. We've written probably more JavaScript code than anybody else. A lot of people came to the conclusion that it would be productive to have something different. Beyond that, outside we just launched 1.0 in mid-November, so we're in it for the long haul. There's people using it, there's people, even before we had 1.0, there's people doing startups with it, which is rather brave of them given that we were changing things under their feet all the time. Definitely we expect to see considerable update. The language has been designed to be kind of comfortable for people. It's very familiar, if you come from the curly-brace tradition, then you should be able to get the basic idea without any surprises.
Darren Rogan: Will there be any other support within Chrome, or is it always going to be built into a JavaScript?
Gilad: Okay, so there's actually a virtual machine as well. The virtual machine, I don't know what our official stance is, but it's going to find its way into Chrome at some point. The bar for getting to Chrome is incredibly high, for all kinds of both engineering reasons and security and [inaudible 00:08:50] footprint and all kinds of things, right? But we expect it, we're quite sure it'll get into Chrome at one point, right? At that point you'll have the Dart being natively supported inside Chrome, which is no small thing because a very large proportion of the world's desktops and an even larger proportion, probably, in terms of the world's mobile.
I don't know when it'll become ubiquitous, but it has an advantage. Right now, first of all you can run it on the server with better performance. The other advantage, which might be slightly surprising, is, a big problem with the tools that compile into JavaScript is the development cycle. They introduce a delay of these compilations, which can be quite slow at times and so forth. Our development environment basically uses a build of Chrome, of Chromium basically, that already has Dart in it, we call it Dartium. You get instantaneous response, just like with a dynamic language, like any other dynamic language like Ruby or JavaScript or something, so your development cycle is really quick.
Darren Rogan: I'm Java background, did a lot of Ruby lately. It's hard to go back to that long build cycle.
Gilad: Basically, a lot of us are old Smalltalkers at heart, and we had the short build cycle decades ago and the rest of the world looked strangely on us. Slowly these ideas are getting into the mainstream.
Darren Rogan: Were you involved in the name, because I think Dart's a fantastic name?
Gilad: Well, I wasn't really involved in the name. There was a lot of discussion. There were a lot of names thrown about.
Darren Rogan: Really? What sort of alternative names were thrown about?
Gilad: Let's see, there was Dash. I think it was originally, the code name was Dash. I think that's public knowledge. Dash had some, once you actually want a name you have to go through legal and whatnot.
Darren Rogan: And trademark infringements and ...
Gilad: Yeah, all kinds of things. So finding something that worked for everyone, that had that same flavor of being something light and fast and whatever took awhile. I can't say that I was much involved in the name but I was there as the discussions went back and forth.
Darren Rogan: Okay, cool. I always like a good name. I like the stories where they come from. I just think it's a bit strange with the train system being called Dart in the Bay Area as well, which ...
Gilad: It's called Bart actually.
Darren Rogan: Bart, sorry.
Gilad: So that's a different matter. That's Bay Area Rapid Transit.
Darren Rogan: Bay Area, yeah. I kept thinking it was Dart.
Gilad: Yeah. That might be Dublin, in Ireland.
Darren Rogan: Yes, it could be. I think it's the Dart in Dublin. I get them confused [inaudible 00:11:27]
Is there any other talks that you're interested in attending or that you've already seen?
Gilad: I've, there's a couple of talks on language NVMs so ... The Facebook guys have this interesting take on this language hack which is basically PHP slightly cleaned up and with a type system. I don't want to say anything good about PHP, but they've done very good work in terms of ... there's some commonality along, this is a trend that we're starting to see really take off of type systems for what were otherwise dynamic-type programming languages. They're doing that in PHP. We have such a system for Dart. This has been a hobbyhorse of mine for 20 years. We built one for Smalltalk many years ago and so forth, so again, it takes that long. When you do something in research or whatever, it takes 20, 30, whatever years until you see it in the mainstream, so you don't get too many opportunities. The Microsoft guys have TypeScript, which is basically a ...
Darren Rogan: A typing system for JavaScript.
Gilad: A typing system for JavaScript, and there's all kinds of technical differences between these things, but they're actually all kind of in the same flavor in a lot of ways.
Darren Rogan: Might bring it to an end. Thank you very much.
Gilad: You're very welcome.
Darren Rogan: And I hope you enjoy your time here.
Gilad: Thank you.
