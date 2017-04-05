---
title: Final Interview Dave Thomas from YOW 2013
date: '2014-02-04 04:45:25'
tags:
- yow2013
---

Our final interview from YOW 2103 with Dave Thomas the man behind the YOW conference.

<!--more -->

<a href="https://drive.google.com/open?id=0B3KFoVQ01nUJUV9FNmNsNF9pU00">Show audio file</a>

Show Notes:

Darren :<b>          </b>Today on Hack and Heckle, we’ve got Dave Thomas with us for an interview. Most people would already know who he is, but for those who don’t, could you introduce yourself for us please?

Dave:<b>              </b>Sure. I’m the organizer of the YOW! Australia Conferences and Workshops, and in my previous life I was responsible for everything bad associated with the IBM Java virtual machines and Eclipse IDE and tools. I do a lot of work in programming languages. I was also a founding director of the Agile Alliance, for which I also apologize. Today, I’m doing interactive analytics for large data sets.

Ben:<b>                </b>What's been your highlight of the conference so far? You’ve been obviously very busy so what’s been the …

Dave:<b>              </b>I am fortunate in that A: I’m involved globally with something called the GoTo Conferences. We run a lot of these in Europe. We also run a conference in Chicago. Some of the speakers I know very, very well. Some are in our speaker network for quite a few years. I think I’m always excited by the local speakers as well, so I think having the great mobile talk by Stewart from Melbourne. I think that’s really good and then of course, we’ve had a fantastic reaction to Andrew Sorensen’s live coding.

Darren:           I didn’t see that one.

Dave:              You want to see the video; you really do want to see it when it comes out.

Darren:<b>           </b>Is it physically sort of moving his hands around as well?

Dave:<b>              </b>No. Basically, they make music. It's a performance, but they do the music by live coding. They actually change the program on the fly and it controls all the musical instruments. Actually, they also control physical stuff over at the new QUT building so they actually control the display walls and everything like that and the physics playroom and so on doing live. He has an environment that lets you basically write essentially a dialect of Lisp extempore, and it’s fantastic. If you haven’t seen it, you want to watch the video.

Darren:           I'll be checking out the video.

Dave:              There is actually a TED video, TED Australia video …

Darren:           Okay, yeah.

Dave:              That has him in it. But I think that was one big highlight. Having Mike Dixon here, who’s doing a new thing called Google Earth Engine.

Mike worked on Google News for quite a few years, but this is taking all the data that comes from various satellites and so I input it together so you’ve seen this sort of Amazon …

Darren:           Rainforest, yeah.

Dave:              … rainforest and things like that. That's work that Mike has done at Google.com. It’s really exciting to have him because I actually taught him as a student back in Canada. I haven’t seen him for many, many years, and we’re very pleased, but really, really interesting talk.

For me it’s having those talks that are off in a different area but show computing being used in new and interesting ways. I organized the conference so I have a conflict of interest. I think we’ve had a lot of great speakers, and most people told me that they were stuck between at least two sessions.

Darren:           I've been stuck through a few, yeah.       What do you think about the rise of the functional programming languages and do you see an increase in the talks and interests?

Dave:<b>              </b>Well, we’ve been actually been part of that conspiracy for quite some time. Someone who’s here fairly frequently, Eric Meyer, and I are good friends. We basically think that it’s important that people understand there's different ways to view programming. It’s not that functional is right or that objects are wrong, SQL is right or no SQL.

It’s really the notion of what’s the right thing for the right job and what’s the level of programmer? I think one of the challenges is predictably when vendors get wrapped around it, they reinforce whatever religious enthusiasm there is, and you get this X kills Y kind of culture as opposed to saying, “Hey, this is really good here, but not over here,” but definitely functional programming.

Right now, in North America you’re hard pressed to find or hire Scala developers and Clojure developers. Basically, I would say that not being unfair but the Alpha Geek community has moved already, and certainly if you look at [inaudible 00:04:45] here in Australia, they had a very, very strong team, both here and in Sydney doing a lot of work with large Australian firms, Atlassian. That’s moved pretty heavily in the Scala. Thought Works has been doing a lot of work in Clojure and a lot of other people. I think it’s sort of already happened.

Darren:<b>           </b>Did you have a favorite in regards to the FT languages?

Dave:<b>              </b>I think it depends what you’re doing. Scala for me is really too hard and complicated. It’s a brilliant piece of engineering. What Martin Odersky and his team have done is absolutely … To take Haskell and put it in a blender with Java and spin it and have it come out so you can actually drink it and feel good, it’s really amazing.

Personally, I think of the languages, I think Clojure is much more approachable for people who want to move to the JVM. I really see a big move in the US and actually all in Europe basically from non JVM languages to JVM languages. Frequently we see Ruby developers moving towards Clojure and Java application developers, but really heavy duty developers with strong CS background probably moving to Scala.

Darren:<b>           </b>Both of us have recently done their Scala courses. I personally think that Scala has got an advantage in regards that is the super language, that it can eat Java from the inside out. You can almost write it in Java and have a growth curve. I don’t know if that’s necessarily the best way to bring people across into FP but what do you think about that?

Dave:<b>              </b>F-sharp and Scala are both are dessert topping and a floor wax. And the real issue is do people really understand functional programming. I always recommend to people who are doing that, that they actually learn Haskell or Clojure first, which is certainly the way that Tony and the Brisbane functional programming mafia, you will learn it the right way.

Darren:           You will do it properly, yeah.

Dave:              I think if you come that way you’re in much better strait.

I think the real problem is what do the normal people do to help them maintain the stuff that you come across later. How do you separate the line between when you’re doing functional stuff or when you’re using the libraries underneath? I really prefer the fact that when you’re writing in a language that’s good for the task, that you are actually using that language and that you can use libraries in other languages, which is what I like about Clojure in particular. I think also the Scala stack has become quite a bit more complicated.

Darren:<b>           </b>The other person who does the podcast, Leigh, he’s done some Scala and some Clojure, and he has a strong preference towards Clojure, finds Scala to be quite complicated, but then it doesn’t offer that supermix of Java as well as far as I was aware.

Dave:<b>              </b>No, it doesn’t. I think that’s the feature. They’re both fine, but I certainly would feel it’s a lot easier to teach people Clojure, and it does keep them honest. We did have previous languages that were called Ada and PL1 that you could do everything in.

Darren:           A bit before my time

Ben:                We have to re invent everything?

Dave:              No, no, that wasn’t my comment. I’m just saying that the challenge with super language is that you add more and more features and so then you have people who say, “Which things should I be using? Generics or no? Now Java has Clojure so now using Clojure or will Scala do it?” It’s good that it’s all in one language, but it means the complexity of the whole system it’s a lot.

Darren:<b>           </b>There’s a lot of time and efforts spent in the decision making process that you wouldn’t necessarily have to do if you didn’t have those options?

Dave:<b>              </b>Sometimes it’s nicer to have one way to do things. It’s kind of like if you look at a lot of object frameworks, one of the big problems with them is they spend a lot of time figuring all the possible ways you can do it so you have a really large surface area of API, in practice, where you’d like to say, “Look, it’s just a collection. Why should I have to worry about,” when I’m thinking I should be able to start with a collection and later on say, “Please make my collection a faster collection or an index collection, or a key collection,” or something like that as opposed to having to know that it’s really the chartreuse blue green collection that I need. Oh that’s the wrong one.

Darren:           It sort of falls into a type discussion, strong and dynamic typing. What do you say on that?

Dave:              I have a long track record of being both a stateful sinner and someone who favors dynamic … I actually think that through a combined group of people that care about it probably, I think you’re seeing things. I don’t know whether you saw the Facebook talk on Hack, that’s a brilliant piece of engineering. Incremental type inference is essential for anyone to use typed programming languages to the extent they’re both Dart and TypeScript. These things respect the fact that you don't always know what the type is.

I think if you're working on new applications, you frequently, when you do a quick spreadsheet you don’t really worry about whether this is … Really, I liked the approach that actually Manuel Chakravarty from UNSW did a keynote at Lambda Jam last May. In the keynote he basically says it's nice to think types really talk about constraints on the program or properties of the program. JSLint is really a type system of some sort. If you actually think all of these things, and Gilad Bracha is speaking here of this notion of what he calls pluggable type system. The notion is that, when you're thinking, even in Haskell it's hard to think because you can't even run the program at all until it's perfect. Although now, Haskell has an option to actually let it run.

Darren:           Oh does it? I didn’t know that.

Dave:              Yeah. I think, to me, and we do it explore like this, live coding, with the music, I defy you to figure out how you would do that, to do the coding on the fly. For exploratory programming, and a lot of people are doing that, then once you figure out what it is, then you say, “Oh yeah, now I know what it is, so, A, I'm going to toss this code away and now I'm going to start over, I know what this thing looks like." Now, if you're working on something you already know, you've done the program 10 times before, then you already know what the type patterns look like. It makes sense.

To me, the ideal is to have a system that lets you turn off these type systems. For instance there’s a type actually is called Phil Walder that’s working on session types, which we use our approximate types, where basically for instance if you want to describe a file interface. Something is a file if the pattern of method implications is it open, rewrite star, close. You can describe that with a regular … But that's not something that most type systems today can talk about. You can say that any interface that allows this pattern looks like a file. It's a more sophisticated form of duck typing.

I think as long as we keep reaching beyond … the nice thing is to be able to mix and match these type systems that, okay, I really want to turn the knobs down. This is going into a mission critical system. We need to have the full power that they improve or I need caulk here. [crosstalk 00:13:10] Or the other one, look, I’m trying to think, I have to be able to change this very quickly.

Darren:           I’m from a JAVA background, so I’ve known dealing with refactoring bad decisions in modeling and typing before, and then I’ve also been doing Ruby which is dynamically typed and then Scala, but I still don’t know where to seat. There’s some very strong opinions on them.

Dave:              I think one of the problems is languages are something where people have a lot of strong opinions. Also, with editors, I'm sure you used Emax or IDE, and I think that the reality is …

Darren:           They’re both valid.

Dave:              They’re both, yeah. And if you're an accomplished musician, and you play the piano, and someone comes along and gives you a beautiful saxophone, worth maybe 10 times what your piano is, you just say, “Oh thank you.” You really don’t know what to with it. Because the things are all sub-cognitive, which are like where the keys are, and can I control these. All those things are suddenly gone, so now you have to think about them.

I think that's one of the real issues, the same with programming languages, often the libraries. You’ve invested so much in figuring out how all these badly designed libraries work, that changing, there’s a big stress associated with doing that. I always think of them as instruments, and people should not be. If it works for them … [crosstalk 00:14:41]. If it’s working, then it must be the right thing. I know people who do very old things called "data flow," “structured analysis,” which was a technique in the 70's that people did, and that was the badge of honor then. And now, no person would be seen doing that, because they’ll already be doing object or whatever. I know people that build that software.

Darren:           You’ve been around for a long time. Do you think that we all have turned into a bit of a fashion industry and sometimes we throw out past learnings so we can jump on the newest bandwagon?

Dave:              I think the Internet allows us to move quickly in our minds. I'm not sure it allows us in reality to get there. But on the other hand, there's so many positive things. I think the last thing anyone that’s old should say is that the new guys are doing it the wrong way, because that’s absolutely not true. Whatever is the best way is the best way. I think the really important thing is, you get wisdom from your grandparents, you get discipline from your parents, and you get the excitement of new ideas and innovation from your children or whatever it is. So, I think it's kind of this healthy respect.

One of the things I have noticed a lot more of this year, thanks to people like Nolan and others is basically the notion of … and I think the rich and key tradition very much is, "Hey, it's actually a good idea to actually read the background papers, as well as the blog posts." Sometimes you actually just have to really read it and think about it. Taking it away. Reading code is a probably a good way to pair without … In Lean the principle is collective ownership. So anyway two of you can share what's going on whether that’s by drawing it on the wall or coding together. It's the bigger idea. I think that's really exciting and the ways and things you’re doing.

I think it's important to know that if you're actually using this in a situation where a customer is depending on it, then you have to look at, “Okay, what’s it like it?” Bringing a DSL in, great idea, if it really solves the problem, really pretty crisp, but the company needs to dedicate two people to maintain that DSL.

Darren:           That they need to be aware of it.

Dave:              That’s right. If they go to Scala or Clojure, they'll have to have a couple of people that really know that and then be prepared to work with that, like Jed who’s speaking here from Atlassian. He’s kind of rolling around Atlassian to support people as they’re challenged with … If you're not prepared to make that investment, then you really have to think, "Is it really time for us to move there, or should we wait until there's more available people?"

Darren:           You have a lot of very good speakers this year. There were some that I was quite impressed by, Douglas Crockford, and then you’ve got, what’s the other Crockfort? The Netflix Architecture …

Dave:              Adrian.

Darren:           Adrian, as well as the FP guys as well, and Philip Wadler, which I really liked his keynote, Super Lambda. I thought that was quite entertaining. Yeah, I think you've got a good mix of experienced people that we’d look up to and known about for quite some time, as well as some of the younger guys. Is that something intentional, that you try to get?

Dave:              Yeah, we do. We have an independent international program committee, and basically we take all the suggestions we get from people, and we have a big database and we code them by. Some people say, "I want to hear someone talk about music," “someone to talk about visualization,” or I want exactly so and so to talk, and basically, we have … the program committee is pretty simple. We have to have two people advocate for the topic or the person, and no one be to it, because we really want to have a variety.

Basically Yow’s point is trying and go from now out to three to five years. That one, we’re trying to slide along that curve and compliment the fantastic user groups and podcasts and so on the local community does. Basically our goal is to try and bring several international people, plus mixing it. And it’s got …

Darren:           And the Yow! Nights.

Dave:              The Yow! Nights as well and now have the Lambda Jam conference which we do in Brisbane, and we’re doing a …

Darren:           What date is that again?

Dave:              That’s I think it’s the 8<sup>th</sup> and 9<sup>th</sup> or the 9<sup>th</sup> and 10<sup>th</sup>, I can’t remember exactly in May.

Ben:                So that’s next year again?

Dave:              Yeah, that’d be next year. We were going to do … which is now we're doing a mobile event in Melbourne in September with a group called SWIPE that have been doing the SWIPE, but we're doing a swipe Android and Internet thing.

Darren:           That Swipe, the Swipe keyboard people?

Dave:              No, Swipe is the iOS. I know actually the iOS conference, didn’t run it this year, but a great conference that run two years previous. We’re teaming with them to be able to do that. We like to try and bring things that complement so people will have ideas.

Darren:           You also said you might be expanding your operations a bit further things?

Dave:              Well, we do conferences other places in the world, but we have a bunch of people from WA, and that other part of Australia, New Zealand. (laughter). I’ll be taking a beating for that remark justifiably. But who are interested. We’ve actually done, we did …

Darren:           When you get to New Zealand then you just keep on the American, is that how you like it?

Dave:              We’ve actually have Dan North doing Yow! Nights there and David Evans was out there already.

Darren:           So I should keep an eye on the website for?

Dave:              Yes they are, and we’ll be doing that in the area that’ll probably hear …

Darren:           A bit more about it.

Dave:              A bit more about it, yeah. I think we’re trying and we’ll keep doing more, as long as we pretty much we pull out pretty much everything we get back in.

Darren:           Do you want to give special thanks to any of the sponsors or anything?

Dave:              The special thanks, all the sponsors are really important. We're here in Brisbane, really, and in Australia, first and foremost, due to Sun Corporation. We would never been able to do it, never been able to do it in Brisbane without Sun Corporation. But, right behind them is TechOne, they've been with us from the outset, and we have some more smaller companies jumping in, and we’re welcoming to have more. TNS and Wotif are both in there. I hope I haven't left someone out. I probably have. All safety …

Darren:           Safety first.

Dave:              Safety first for all of you that are going to move north to those opportunities.

Darren:           Yeah, well, I was going talk to them to find out I was in time.

Ben:                So that was some corporate they’ve sponsored?

Dave:              Yes.

Ben:                Yes.

Dave:              Thanks very much guys. We really appreciate having you here and being able to speak to people in Australian, so that will be a lot of understanding.

Darren:           I may not be the best presenter though.

Dave:              I was going to say that.

Darren:           Thank you very much for coming to the show.

Dave:              Thanks a lot.

&nbsp;
