---
title: Interview with Scott Hanselman from YOW 2013
date: '2014-01-28 09:25:54'
tags:
- yow2013
---

At the Yow 2013 conference we had a chance to interview Scott Hanselman who did the Evening Keynote on Day of YOW 2013.

<!-- more -->

<iframe style="border: none" src="//html5-player.libsyn.com/embed/episode/id/2652159/height/75/width/640/theme/standard/direction/no/autoplay/no/autonext/no/thumbnail/yes/preload/no/no_addthis/no/" height="75" width="640" scrolling="no"  allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Transcription:

Darren:           Joining us today on Hack &amp; Heckle is Scott Hanselman who’ll give the keynote speech on day one of the YOW Conference. All right, Scott, would you like to introduce yourself for the listeners who don’t know who you are?

Scott:              My name is Scott Hanselman and I work at Microsoft, been there for the last five or six years. I’ve got a website hanselman.com and I’ve got three podcasts. I do one called Hanselminutes, which is an interview show. I do one called This Developer’s Life, which is more long form storytelling. Most recently I’ve been doing one called Ratchet and The Geek, which is kind of like a chat. Just car talk, we have a show in the States called Car Talk. It’s just two guys talking about cars; it’s kind of like that.

Darren:           I listened to Hanselminutes. I’ve been listening to This Developer’s Life which is your homage to This American Life.

Scott:              Absolutely, I wouldn’t even say it’s a homage. I would say it’s a complete rip off. Yes, it’s actually such a big rip off that their lawyers called us and said, “Stop calling it that.”

Darren:           Really?

Scott:              Yeah, they daaid.  But then they said it was okay because they heard the show and they realized what we were trying to do. We’re allowed to use it until one day when they call and say we have to stop.

Darren:           Could they really stop you?

Scott:              Yeah, they could. You don’t want to be threatened or anything, we’ll just change it to Dev Life or something like that.

Darren:           Rather than This Developer’s Life?

Scott:              It’s clearly a rip off of This American Life.

Darren:           But then the Tshirts wouldn’t work, as well.

Scott:              That is true, we would have to get on the t-shirts but it’s not like we make any money on the thing.

Darren:           How did you find your keynote? I thought it was hilarious. Do you think it went well?

Scott:              I thought it was hilarious too. What could I possibly say? I don’t know. It’s fun; I’m kind of getting a reputation as being the silly guy in the technical speaking crowd. It’s kind of tough because there is some pretty heavy hitters in this particular conference. People I am really intimidated to be speaking in front of.

Leigh:     Yeah, one of the things I really loved about your talk is because it was the last one of the day and everyone had already had a few drinks, I think it was sort of a perfect way to end it, we couldn’t really have one of those hardcore technical talks that … it wouldn’t have been a good way to end it, I think.

Scott:              Yeah, it would be really hard to internals of monads or whatever at 5:30 at night.

Leigh:     Yeah, one of the other things I loved is that, you seem to weave in very well and did the self-deprecating humor very well being from Microsoft and this sort of conference is quite focused on open source a lot and I loved how you waved in Azure and Visual Studio into your talk, it was really cleverly done and it certainly taught me a lot about Azure. I didn’t really know too much about Azure. I’ve used Amazon web services before but, yeah, it was clever and it was a really good way to introduce someone like me to it. Well done, that was great.

Scott:              No one wants to sit through a bit commercial. It would be lame if … I was invited which was step one, which his good. There are conferences where either Microsoft or Google paid to get a spot, where they will give X thousand dollars to become a platinum sponsor and then some random guy or girl is going to give the keynote, it’s clearly a giant infomercial about their products.

I like Visual Studio legitimately and I like Azure, I didn’t originally. I used to think Azure sucked, and I didn’t talk about it probably just because it was a lousy thing, this was like two, three years ago. But now that it’s all like an HTML5 portal and it’s all web services and it’s all open source we’re feeling really great about it. I am talking about it because I am jazzed.

Te idea for the talk was, I have these thoughts about the philosophy of how a software should be built and how these things should be woven together, I work on Azure and Visual Studio and I like them and I have all these cool stories that I want to share so I try to build those three things together into one kind of edutainment event.

Darren:           I like it. I like it.

Scott:              Did you think it was okay?

Ben:     Yeah, I really enjoyed it. The thing that impressed me was the Visual Studio editing of the HTML touch straight into the browser with that plug-in control that was amazing. I never even thought of that as an idea and then to see it I was sort of, not just probably develop the tools and just sort of be able to see it that’s something, to be able to actually get in there and change it and see it applying it to your idea that was pretty impressive.

Scott:              Yeah, that’s called Browser Link and that’s plugged into Visual Studio Web Essentials and the code for how we did that is on Mad Christensen’s  GitHub. It’s wide open and ultimately the thing about that talk was that we have the right lego pieces now, the JavaScript is mature enough and web service is mature enough that we can do these kind of things, and that was really just a two week prototype.

Because browser link is the underlayment, it’s the foundational thing, there is a road. We have yet to decide what cars and vehicles we want to put on that road, that idea for the design, that was just one, and that is actually done as a plug-in. You don’t get that with Visual Studio, you get browser Link. You install these to your Web Essentials and then those things light up so then the question is, what are you guys going to be built?

Leigh:           Yeah, absolutely. You’re saying it’s kind of a platform that you guys can extend on and build more stuff into it.

Scott:              And there’s no reason that Sublime or Webstorm or some other ID couldn’t do the same thing.

Leigh:           That’s great.

Scott:              We’re not trying to be the only IDE that does that.

Leigh:           Yeah. Scott, I would love to hear about sort of what your day to day activities are at Microsoft. You’ve become kind of an evangelist, what they call an evangelist these days, but are you still coding day to day? Are you cut and code and putting releases out or are you mostly just evangelizing?

Scott:              I’m not an evangelist. I don’t work for what’s called DPE, Developer Platform Evangelist. I’m not a developer. There’s program managers, developers and testers, I am a program manager. I wouldn’t say I am cutting production code, but at the same time our group has changed, where we do stuff on GetNow. I do, do pool requests, like I did a pool request for Cuda Debug Console recently and I switched it over to Bootstrap just because I was like, “That’s kind of ugly, I am going to make it prettier.”

Just like any community member I did that and it will be run through the same process as anything else. I don’t have any responsibilities to produce code but I do, do three or four pool requests a week on different things that bother me.

Leigh:           Is your team kind of a guerilla sort of installment within Microsoft or is it sort of changing in the organization?

Scott:              No, we’re a proper organization. I work for Scott Hunter and ultimately that rolls up to Scott Guthrie, you have to be named Scott to be involved in any way.

Leigh:           I see. I see.

Scott:              Guthrie owns Azure. Hunter owns ASP.NET and Web Tools so that Web Tools means like to file new project dialogue, all those dialogues and publishing and anything that involves a tool that plugs into Visual Studio and he ultimately owns like the open source thing and the management of ASP.NET proper.

I think of myself kind of as the PM of miscellaneous. That might mean that you, Leigh are the PM of the find new project dialogue and Darren is in charge of publishing and Ben is in charge of the editor, but you three may not all talk to each other, and you might find a decision you made in the find new project dialogue, messes Darren’s publishing up, or something and the editor isn’t right after a certain founder, those interactions it’s kind of my job to go and say, “The story arch that is creating and ultimately publishing a piece of software doesn’t quite work.” So I try to get all the teams to think about the big picture. That’s my day to day job.

Leigh:           Absolutely.

Scott:              In the evangelism stuff, again I hate that word.

Darren:           I think everyone does.

Scott:              Evangelism sounds, when I think of evangelism, with all due respect I think about the crusades, I think about trying to convert people to a particular religion. I’m not really interested in whether you guys, the set of people who are not me care about my religion or not, and that’s why Azure lets you run anything you want to. I would like you to be informed and then make the best decision. I think of myself more as a teacher. I am really excited about this XYZ and you should at least know it’s there and if you want to use it, great, if not that’s fine, I don’t care. I don’t get paid anymore if you use my products.

Darren:           Yeah. Open source in Microsoft and the use of Git, is that sort of a recent thing? Open source has been there for a while but it kind of …

Scott:              Git has been about two years now. I think that it was the realization by Brian Harry’s team, Brian Harry is in charge of TFS, is that when you say TFS people think about the source control provider, but TFS is way bigger than that. There is TFS the team foundation, server manager, the ALM system, the issues and tracking and burned down charts and all those things around life cycle management of which a small part is centralized source control. TFVC, we’ll call it, it’s the source control server.

When he decided that, hey, this is okay. That it’s okay to have choice and we’ll have a deferrer for a great centralized source control system which is valid for some enterprises, TFS source control, and then for others it’s Git, and now you can choose. If you go to Visual Studio you make a new project, the first question is, “Which system do you want?”

Git’s clearly won on the DVCS world, like Mercurial is still out there and those other things, we’ve also got things like SPN and even CVS is still out there but ultimately give is FTP for code. It’s out of the box, 2013 supports it. It’s all about choice.

Speaker 1:     Lots of people internally use TFS?

Scott:              We use TFS for issue tracking and stuff but other people use the good stuff, so it doesn’t really matter.  Again, you have to manage your project somehow, better to have choice than not. You can actually see us committing to our Git repository read, even if it’s on CodePlex. In the old days we used to commit to TFS and then we throw a zip file over the wall, and we just thought that was silly, now we read this command to Git and you can see it proper. Is it a new thing? No. Two years maybe right now, newish.

Darren:           Newish, yeah.

Darren:           That’s still pretty new for an enterprise that size especially with your own product within source control.

Scott:              Remember we’re 90,000 people but that doesn’t mean that we are all doing the same thing. I think ASP.NET is like 120 people or something like that, 115, but our team of PMs is like 9 or 10, so it’s really like 1,000 companies of 90 people each if that makes sense, and we run ours like a start-up. Everyone is very excited and we want to have lots of different ideas and it’s very, for distribution we do Scrums and regular releases and something like.

Darren:           With Agile you would do Scrum management would be the other one, maybe you tried Kanban or any of the other Agile …?

Scott:              Every team is a little bit different. Some of our teams use Trello and have like a Kanban board and Trello. There’s a new Kanban board in Scrum inside of TFS, TFS Online is good. If you go to visualstudio.com, you can sign up to TFS and I think it’s teams of five.

Darren:           For free.

Scott:              For free.

Darren:           Cool.

Scott:              We get all the stuff, burned down charts and Scrum and all that stuff.

Darren:           I’m still using 2010 at this point

Scott:              Switch to the online one, it’s really brilliant. Software and services is where it’s at I’m telling you. There is just no reason to run any of the stuff you want. I used to hate SharePoint, because I have to manage the thing. It’s like a puppy and there’s still actually one SharePoint server left in my life that’s under some guy’s desk, you know what I mean? And it’s like 2007. But once you throw that up in the cloud, I don’t care if it’s SharePoint or if it’s Google Drive or Trello or whatever, it’s handled and it’s versions itself.

SharePoint managed in the cloud like Office 365, dude it works awesome. Here, you can’t see this because we’re doing podcasts. I’m pulling out my phone here and take a look at this, I go here and I click on Microsoft and what do you see? You see nine really fully featured apps. I got OneNote, Outlook, Office Mobile, SkyDrive, Linked, Remote Desktop. I click on Office Mobile, take a look at this, this is actually going to connect now to SharePoint and now look, I’ve got Word, PowerPoint and here’s a tiny Excel all on my iPhone, and that’s what the cloud says to me, that’s why I get excited about that. We use all tools, we use Trello, we use SharePoint, we use Google Docs, we use whatever the thing is the team wants to do.

Darren:     Do you have everyone co-located or you do remote work?

Scott:              I’m kind of the only remote guy on our particular team but we do have a development group in Vancouver BC, if there’s immigration stuff I see sometimes people would show up there. Steve Sanderson is in London. Three of these are mobile people. I’m kind of the most remote, the most visibly remote person.

Darren:           Do you use any remote tools?

Scott:              Yeah, I keep a Skype call running as often as I can. We have no bandwidth problems, I can just keep it on high def all day long and they can just peek into my office and say, “Hey, how’s it going?” It’s like a portal, like portal two. And then we use Linked a lot. Linked is like corporate chat. Some people use Kip chat or Jabber, Linked is our corporate chat and I think they are going to integrate the two somehow.

What’s nice about Linked is that, again, I got it on my iPhone and I can actually be in a café, do screen sharing and chat people and then also it’s like Google, what’s the phone thing that Google has, Google Voice?

Darren:           Google Voice, yeah.

Scott:              I’ve got VOIP, as well.  I can make phone calls from my … this is the phone call app that I am holding up on my iPhone so I can make a call and it would show up from my pretend VOIP phone in Washington State where I do not live. Does that make sense?

Darren:           Yeah, I’ve got some friend in the US who do a similar thing.

Scott:              Yeah. I am location transparent and location ...

Leigh:           Scott, let me ask you, I’m really interested in this. I don’t know why but what is Microsoft doing with yammer? I haven’t really kept up with it. Do you know much about it?

Scott:              I only know that it’s integrated with Office 365 and then it’s like Facebook for corporations.

Leigh:           And I wonder does Microsoft use it internal?

Scott:              Oh yeah, big time. I’ve actually got the YAMA app on my iPhone and basically it’s like Facebook but with corporate gossip.

Leigh:           That’s the impression I get as well, I was just interested to know if they use it internally.

Scott:              Oh yeah big time, they use it a lot, and it’s integrated now, so when I log into outlook.com, I can actually see YAMA appear as one of the tabs, and it’s all integrated. There’s YAMA, this is Microsoft. I’ve got my feed; let me see what people are asking about. People, they’ll say, “I saw this ad and I liked it or I didn’t like it”, and they’ll have very frank conversations about Microsoft specific issues and they can do it in a secure way and don’t feel like they are going to get in trouble.

Leigh:           That’s nice, that’s good. Cool. All right, Scott, we’ve been going for 15 minutes, have you got any more time to kick off?

Scott:              I’ll keep talking, you guys are nice. When you become not nice I will run away.

Leigh:           Yeah, that makes sense. That makes sense. How are you enjoying Australia? Is this your first time or?

Scott:              No, no. I’ve been here before, it’s lovely and it very warm and I wonder if you guys realize how nice you have it down here.

Leigh:           I don’t know

Scott:              It’s pretty fantastic, it’s almost like being in a future science fiction movie where it’s like 2050 and there’s like segues and people floating and hovercrafts and stuff and there’s like public catarands that just go across the bay. It’s ridiculous, it’s really lovely.

Ben:     Since you’re here for the conference, what’s been your highlight of the conference so far? Have there been any talks or anything you’ve been really excited about?

Scott:              For me it has been meeting some of these famous people that really matter. I appreciate the compliments about the keynote stuff but it’s hard to give a talk like that when Douglas Crawford is standing six feet from you and Adrian Cockcroft, chief architect in Netflix is sitting next to him. You know what I mean? Then like the father of Pearl or someone with a PhD or three and I am up there making jokes and showing animated gifts of cats, it’s just a weird feeling, because you can enjoy both kinds of talks, but I think my talks are a little bit more show business. I feel like I am, even though I’ve got the keynote to this particular yell I feel like I’m the opening act. Does that make sense? I am here to warm people up

Darren:           Get people jazzed.

Scott:              Then we’ll go learn about monads or whatever.

Darren:           Yeah, yeah. That’s right.

Scott:              It’s a little intimidating to give these talks in front of people especially when you’re telling silly jokes. I just can’t watch a dry talk anymore that’s why I am silly.

Darren:           You’ve done Melbourne so far I believe, and now Brisbane and then Sydney’s the final one, are you planning on spending any extra time in Australia or go straight home?

Scott:              That’s a touchy point. With all due respect, I love everyone’s country, when they ask me if I am in their country, “How do you find our country?” “It’s lovely. I am sure it’s great and that’s why you live here.

Darren:           Yeah, it’s a pretty tricky question. How could you possibly say, “No, I’m not enjoying it?”

Scott:              This hell hole of your country, no. The example I always give was I was in Egypt for a week and I got there on a Tuesday and I finished my job, it was on Friday and they said, “Hey, you should stay over and you should see the sphinx and the pyramids and we’ll take you on a camel and it will be great.” They were really trying to show me their wonderful country, and I would love to see the world, I really would, but I have got 4-year old and a 6-year old and they are going to be 4 and 6 for one year, and there is 52 weekends in a year, and one of those weekends is 2% of their year.

I am pretty sure the pyramids have been there for a while, and I am pretty sure that they will be there later, and I have seen Indiana Jones. I just said, “With all due respect, I am going to leave.” While I am hugely, hugely digging Brisbane in particular, I think the water frontier is amazing and what you guys have accomplished, there is a perfect little island Utopia, it’s pretty amazing with a 4% tax rate, and I think it’s great. I would even think about maybe living here for a year or two, but the sooner that I get out of here the better because my 4-year old, now 6-year old rather Skyped me earlier today and said, “Daddy, I have forgotten what your beard feels like.

Darren:           Oh really?

Scott:              Seriously, come on. You know what I mean? Do you want me to go on a canoe trip? No, I’m going to go home. So yeah, I would like to go home right away.

Darren:           Yeah, yeah. Absolutely.

Scott:              I don’t know if that is a long-winded answer. Like you have a lovely country, get me out of this country, if my kids were here though, if they came on the trip, which was the original plan.

Darren:           Yeah, have you thought about that? Do you do that often?

Scott:              But they’ll come along. I’ve never done a 2-week trip like this without the kids. They were supposed to come, some stuff came up, they couldn’t make it but that is usually the intent. Otherwise, I get in and out. I’m going to Denmark in January and I am going to leave on a Tuesday and be back on Friday night, just in and out.

Darren:           Do you find with your position at Microsoft you actually have to do a lot of travel?

Scott:              No, I don’t technically have to do any of the travel. Again this “evangelist” thing is kind of a side deal, for example the blog is mine, it’s owned by me, it’s paid for by me. The little bit of advertising money I get from Google ads is mine. It was an agreement I made that I am going to blog about whatever I want to and whatever makes me happy. The speaking is kind of half Microsoft, half not.

If I go to my boss and I say, “Hey, I want to go to Australia.” He’s going to say, “What are we going to get out of this?”I can say, “We just released Visual Studio 2013 and Australia is a big market and they are very nice people”, but it would be silly for me to come here and just give three talks and stay for two weeks, because I’m going to reach what? 500 people times 3? This is more of a ‘me’ thing than it is a Microsoft thing but I can’t waste time.

I’ve actually got 15 talks while I am here, three at YAO. I’ve got customer visits, I talk to car sales, I talk to different companies and they each brought 100 people and more. I talked to user groups, I gave user group, I came here to hang out with you guys after going to a user group that we had maybe 120 people. When I go there I have a flight in a couple of hours to Sydney and there will be a couple of hundred people there. My point is just be as visible as I can, talk to as many people and be excited about what I am doing. I don’t want to have any wasted days.

Then I stop by my boss, I’m like, “I’m going to talk to like 5,000, 6,000 people.” Then he’s like, “Okay, I could see you doing that. We’ll give you a little budget to do that kind of stuff.” It’s a bit of a dance, because I literally got a text from my boss an hour ago and he was like, “Are you back yet?” He didn’t say it in that tone but that’s the tone that I read it in. It was like, “Are you back yet? Are you in the country? I’m like, “Not really.” It’s tough sometimes because I don’t want him to think that this is a vacation, because it’s not.

If my kids were here I would take the extra week and we’d hang out. But this is kind of a working thing and I still have to do the hard work of a program manager while I am here which is, delete email. After we’re done here I need to go and delete some email.

Darren:           Just coming back to the actual talk. Was there a person who was a microprocessor or was that just something you used to weave the story through your talk?

Scott:              Oh, you mean the story of the gentleman. That was a real guy.

Darren:           Was it?

Scott:              Yeah. That’s an interesting question. The Meta question underneath that you’re asking is, how many of the stories do we tell when we tell stories in the business of show as we say, are real stories? Yes, there was an actual older guy at Intel who wanted to learn web programming and he was old and rich and famous and he wanted to become a web guy that is all true. Yes, I met [Ty Rick Nielsen 00:22:48] who invented HTP and I find him intimidating, that is true. The actual quotes or whatever may not be 100% true because it’s just like when you tell any story …

Darren:           A little bit embellishment.

Scott:              It gets bigger and bigger and bigger, you know what I mean? I told the story about the kids at the New York Times that used Amazon web services, I’ve been telling that story for months about how it cost them $300, and I just learned from when I told it in Melbourne to the guys that I know those kids, it actually cost them $150 twice because they had to run it a second time because he made a mistake. I then incorporated that into the original talk.

Are they lies? I wouldn’t say that they are lies. But that said, I heard this really great interview on a radio station in the US, the show is called Fresh Air and it was Billy Crystal. You know the actor Billy Crystal?

Darren:           Yeah, Billy Crystal, yeah.

Scott:              One of his first jobs was opening for Sammy Davis Jr. Sammy Davis Jr. was at a time arguably like the Michael Jackson of the night club scene, and he was like one of the most famous people on the planet. And Billy Crystal opened for Sammy Davis Jr., and they worked together in Vegas for …. Was it Vegas or Atlantic City? For a year, Billy goes on. He’s the young comedian, he does his bit and then Sammy would come out afterwards because he is the main act, and he would say, “This cat, he’s just a great kid, he’s a fantastic kid. He was just at the hospital earlier visiting some sick kids.” Each show Sammy Davis Jr. would tell something about Billy Crystal not true, not even remotely true.

They never did anything other than work together, you know what I mean? Then each show, like Tuesday, “What a fantastic kid. I had him over at the house and the wife and we had some biscuits and we had a lovely Sunday dinner.” Billy Crystal was like sitting on the wings going like none of this ever happened. But the audience eats it up because they are imagining a world where Billy Crystal is hanging out with Sammy Davis Jr. And say, “Is he lying or did you pay to see his show?” I don’t like to that point, but I do add animated gifts to make it more impactful, let’s just say.

Darren:           How long did it take you to actually get your full speech up? Because it did seem quite polished or is it just the fact that you have been doing it for so long that you’re able to get one of those talks done?

Scott:              That talk probably took a week, two weeks to do but at the same time I’ve maybe done it three or four times. The other thing is you got to take into consideration the energy of the crowd, if they are in a good mood and they like you.

The first five minutes I was uncomfortable but then once I realized there is a crowd on my side or not then I feel better.  If you’re against me then it’s going to be a more antagonistic relationship and more heckling, and if you guys are with me then let’s have fun together, let’s go on this journey. I also did a lot of High School Theater. I think that the basics of timing are important and I encourage people who are giving speeches to do toastmasters. Do you have toastmasters down here? Public speaking classes are really, really important.

Ben:     On the issue of timing, those guys yesterday I think you entire, I think there was one period that I thought might have slipped his tongue and so people came at just the right moment I thought that was quite impressive.

Scott:              One of the things I was telling some of the YAO interns and conference organizers, someone said that she thought one of the jokes had really good timing, and I said the timing is so important, because you don’t want to tell a joke and then have a pause, because it’s very uncomfortable. Because you’re basically subconsciously asking the audience to laugh, so you’ll say something like, “Yeah, just moved in from Melbourne and boy, are my arms tired.” And it’s like pause, and then what happens is someone’s got to give, either the audience’s got to laugh and you taken a risk there because you just threw a grenade out and you’re waiting for the grenade to explode. Or, you kind of go, and make some sad pathetic laugh on your part.

What you do is you’ve got to punch through the wall. You don’t punch and you aim at the wall, you punch through the wall. You say something like, “That’s a stupid joke,” but I’m giving an example here. “Yeah, I just flew in from Melbourne and boy, are my arms are tired. Let me tell you …” You just keep walking, keep going. If they happen to laugh …

Darren:           Then you pause.

Scott:              At least they are laughing through another sentence, but you are going, “Let me tell you. These kids, kids here in Australia are racky.” You use just filler words. But it shows that you weren’t intending to wait for them to laugh. Does that make sense?

Darren:           Yeah, it does make sense.

Scott:              An old comedy teacher of mine once said, you know the most important thing about comedy. Timing. Thanks for noticing that though, I’ve done some stand up. I just can’t watch damn dry talk. You know what I mean? That was a professor doing; it was at a state school teaching C-Sharp. Who wants to sit for five classes a week and listen to this pressure man drawn on? So it’s got to be light and fun.

Darren:           Yeah. You mentioned that you had done some standup, is that something that you do on the side at all or is it …?

Scott:              I am doing it on the side right now, aren’t I?

Darren:           Oh yeah, I guess.

Scott:              No, I don’t do proper standup, I am kind of crippled without PowerPoint and code anymore. If I did standup I would at least need a notepad or some projector.

Darren:           You’ve got those gifts to act as a crutch for you.

Scott:              Yeah, the gifts are a crutch. I probably could do it but it could take me longer than a week to put together a type 15 minutes. That was a type hour, but I’ve got some demos. If I could do standup with a few demos, we’ll see.

Darren:           All right, Scott, thank you very much for coming on the show with us. We really appreciate your time. I hope you’ve enjoyed your stay in Australia. I hope you do well in Sydney.

Scott:              Thank you very much. I appreciate it.

&nbsp;
