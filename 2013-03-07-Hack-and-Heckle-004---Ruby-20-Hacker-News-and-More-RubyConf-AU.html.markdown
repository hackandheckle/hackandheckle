---
title: Hack and Heckle 004 - Ruby 2.0, Hacker News and More RubyConf AU
date: '2013-03-07 22:09:11'
tags: []
---

<iframe style="border: none" src="http://html5-player.libsyn.com/embed/episode/id/2242502/height/360/width/640/theme/legacy/direction/no/autoplay/no/autonext/no/thumbnail/yes/preload/no/no_addthis/no/" height="360" width="640" scrolling="no"></iframe>

Welcome Feedback:

Voice feedback: direct on the website (speakpipe on website) leave a message ( <60 secs)
Email feedback: feedback@hackandheckle.com

Website: hackandheckle.com

Show Notes:

DR:
http://news.ycombinator.com/item?id=5310911 - Tesla Motors master plan
-Electric Cars
http://news.ycombinator.com/item?id=5311668 - Why Five Days in the Office is Too Many
-Remote Working / Yahoo stopping it

http://news.ycombinator.com/item?id=5309866 - Evernote hacked
http://news.ycombinator.com/item?id=5311010 - Evernote doesn't care about security
-evernote 

http://boingboing.net/2013/02/21/graphene-supercapacitors-could.html - Graphene battery

http://news.ycombinator.com/item?id=5310244 - Open source events burned by paypal
-paypal can they be trusted?


MM:
http://statico.github.com/vim.html - VIM after 20 years
http://news.ycombinator.com/item?id=5321603 - FLAT UI bootstrap
https://cooperpress.com/ - Ruby 2.0 Walkthrough soon to be released
http://www.rubyconf.org.au/ - Ruby Conf AU
http://lanyrd.com/2013/rubyconf-australia/ Videos and Slides from Ruby Conf

Picks:
Loader.io - Load testing (Beta loader.io) web page and restful services
App Sumo (appsumo.com) - Techie Deals site (Groupon for Devs)
LastPass (lastpass.com) - Password Manager
Dolphin - Android Browser (http://dolphin-browser.com/)
Sublime 2 (http://www.sublimetext.com/2) - And it does have split screen...
Boxen -  https://github.com/boxen (setting up local machine - mac)
Divvy (http://mizage.com/divvy/) - Screen layout tool
Tree House (paid screencast on development topics) http://teamtreehouse.com/
Little Snitch (Mac firewall) http://www.obdev.at/products/littlesnitch/index.html


Transcription:
Hack and Heckle

Darren: Today some news, some hacker news, a bit more of discussion on Ruby 2.0 and RubyConf.  So Mike…

Mike: Hello Darren.

Darren: How are you keeping?

Mike: Not too bad.  I could do without all the rain.

Darren: Yes. Have you had a chance yet to investigate the Ruby 2.0 release?

Mike: Yes.  I finally had a chance to go through Peter Cooper's videos.  To be honest, the changes in Ruby 2.0 are not as significant as the changes that happened in Ruby 1.9.3.  The video is very good. It's certainly not as long as the last one which I think was about 3 hours.

Darren: Yes, I noticed he split it down into was it seven or eight?

Mike: He split it into seven or eight.  I think we're still missing the final two and I think the Best Bits video which is probably about 20 minutes, 15 minutes, probably sums up most of the bits for the whole of the remaining videos if you'd like.  The main changes – the lazy enumerators.  I don’t know if you've had a chance to look at this or not.

Darren: I haven't had a chance to look at the video.  I watched the intro today but I haven’t had a chance to go through that Overview video you were talking about.

Mike: Yes, so lazy array is very cool. Sorry, lazy enumerator is very cool for stuff like map and select in Ruby. So as an example, if you're going to do a range from – I don't know – one to infinity for example, with map and select that would never finish because it just continues right through the end.  It doesn't do a lazy select.  Now you have the lazy method, so you can lick through and do some fancy stuff as you go and desire to finish it whenever you want.  Very cool.  I'm not quite sure how I’m going to use it yet, but a very nice method.

Darren: So is there anything else in the Ruby 2.0 Overview video?

Mike: Yes, a couple things, keyword arguments.  You're probably aware previously when you're passing arguments, passing a hash as an example to a method, you can define defaults, and you would have to use things like defaults, merge, etc., etc. to either take the defaults or merge in the new parameters that came in.  With Ruby 2.0, you can now just specify that as the signature on the method and take the defaults or the defaults get overwritten by whatever is passing.  It's very cool.  Much nicer implementation.

Darren: Yes, I can't wait to have a play with it.

Mike: There are a couple of others – module prepend and trustpoint. I'm not going to get into trustpoint because I haven’t a really spent a lot of time on that one. But module prepend now gives you the option, instead of including a module into a class you can now prepend it, which basically means any methods that are defined in that module would be the first of lookup in the ancestry tree if you'd like.  Whereas before you would do an include, so the class specs would be looked up first, then the included module would be looked up afterwards. Does that make sense?

Darren: Yes. I think so.

Mike: So basically, you now have a way to include modules at the start of the ancestry tree before the actual class that you're using.  I'm hoping that makes sense.  Watch the video.

Darren: I’ll watch the video.  I haven't seen it yet to be able to jump in.

Mike: And the other one I think we mentioned last week was the refinements, but they're not quite in there yet.  So we won’t talk about them again.

Darren: Yes, we'll wait until they’re actually in the next point release and we’ll go into them in a bit more detail.

Mike: But it's a very good set of videos.  I think there are still another couple to come.  One, two, three, four, five, six, seven, yes, probably another two to come.  Well worth watching, but like I said, the Ruby 2.0 release is not as significant as the 1.9.3 release was.

Darren: Yes, I've seen that.  I like the way it was Ruby 2.0 on the 20th anniversary like it was all done on purpose.  I did enjoy that.

Mike: It was to the very day I think, wasn’t it?  Yes, that's very nice.  We like it.

Darren: Yes, we do.

Mike: Anyway, you should start using it.  It's P.0.0.0. It’s very stable.  No doubt there will be fixes coming soon.

Darren: It's backwards compatible with 1.9 as well, isn’t it?

Mike: It’s backwards compatible with 1.9, yes.

Darren: All gems should be working fine?

Mike: Yes, and on that subject, I think there's a Rails release candidate for 3.2.13 which offers full support for Ruby 2.0 as well. 

Darren: For anyone who's listening who would like to give us some feedback, it's feedback@hackandheckle.com.  For anyone else, you can also check out the website HackandHeckle.com. The show notes and transcriptions of the show are on there. Also you can leave a direct voice feedback via SpeakPipe which is a bit of a plugin directly in the website. So if you have got a question for us or a bit of feedback, you can just jump on the website and leave us a message under 60 seconds, and we will try to bring it up in the show. My first pick on Hacker News is the story about Yahoo stopping remote working.

Mike: Yes, I read that.  Very funny.

Darren: And then this article by Prerna Gupta, which is Why Five Days in the Office Is Too Many.  And he talks about peak productivity and how working from home gives you some time for unstructured thought, and that he feels he's more productive during that time, where Marissa Mayer has been saying that she wants everyone to come into the office so that they can start working and having impromptu meetings. I understand what that's like a bit because when I'm in the office I hear stuff going on next to me and regularly jump in and help.  But in saying that, I do work remotely myself.  I worked from home today and I find that I am more productive when I work from home than when I'm actually working in the office.  I get to the office and I'm a bit stressed from the commute and I need a cup of coffee or something.  When I’m at home, that just isn't there.

Mike: Yes, well here in Brisbane I need to dry out by the time I get to the office.  It's not very good with all the rain. Sorry, just for the listeners, I ride a motor bike to work.  Brisbane is now in their rainy wet season and I seem to be getting hit every day these days.

Darren: Yes, the weather's been awful.

Mike: Yes, but going back to that Yahoo one, the point was they were stopping everybody from working from home, yes?  

Darren: Yes.

Mike: But wasn’t it also to find out – I probably read this about a week ago so maybe I’m not up to date on this – but wasn’t it also to find out about who was actually doing what because there seemed to be a lot of people and they didn’t actually know what they were doing.

Darren: That's correct.  The story last week was when Marissa Mayer – a week before, she actually banned the employees.  This pick, this article is defending working from home.

Mike: Oh I see, okay. Sorry, I beg your pardon.

Darren: So it's sort of a follow on.  I did actually have another pick for last week which I cut which was about proven productivity gains working from home.  I think it doesn't work for everyone. I have an office from home.  So I've got a room, I've got computers, everything is setup, I’m in it right now. So you need that work/home separation. So when I'm in here I'm doing work, and when I'm not in here I'm not doing any work.

Mike: I guess it also depends on your personality.  Some people don't mind working from home, working by themselves with no interaction.  Some people prefer having people around them, etc.

Darren: To be honest, a lot of places I'm working, most of the dads are sitting in with headphones on anyway and they talk to you on bloody messenger rather than turning around and you may be sitting behind them. 

Mike: Yes, I’ve seen that where I am as well.

Darren: So sitting beside them or sitting an hour away doesn’t really make a big difference.  And I'm working remotely with people in Sydney, so even if I'm in the office which is in Brisbane, the company I’m working for at the minute, most of the people I'm working with aren’t even in that office.  So in that respect, it really doesn't benefit me or the task at hand for me to travel into the office.  I more go in some people see that I'm around and help other people.

Mike: Yes. I agree, yes.

Darren: So I might do another pick if you don't mind.  

Mike: Yes, go for it.

Darren: I have two picks about Evernote.  The first one which I read was that Evernote doesn’t care about security.

Mike: Yes, I read that one.

Darren: Did you read that one by Mark Percival?  I thought it was quite interesting, saying that they still don't have two factor authentication, and they're talking about SSL, about the encryption SSL is not enforced.  I thought it was quite interesting because I like to have a secure service but I love Evernote.  I’ve been using it for a long time now.  And then as I read that article, what happened the next day?

Mike: They got hacked.

Darren: Evernote got hacked.  So I got an email, which is also the next posting from Hacker News, which is the security notice from Evernote that says that they were hacked and that they think that their passwords, because they’re salted and hashed, they think they’re okay.

Mike: Yes, I had the same. Now everybody has to change their passcodes.

Darren: Yep.

Mike: But all my notebooks look fine.  I'm happy.

Darren: Yes, I don't think that there's anything really in our notebooks that anybody's going to be that interested in.

Mike: As long as you're not storing your bank account details in there.

Darren: As long as you have different passwords for every service.

Mike: Yes, that's what LastPass is for isn't it, to give that little plug.

Darren: Yes, that should definitely go in the picks.  I'm a pro member of LastPass. It's only like $12 a year or $20 a year.  But I pay because I want to make sure that service stays around.

Mike: I think it was you who introduced me to LastPass.

Darren: I think it was. 

Mike: And I just love it. You can go anywhere, pick up Google, login, and all of your LastPass stuff comes with you as well.  It's just fantastic. It's fantastic if you're moving around.

Darren: It is and I move around a bit.  The other thing which I find is quite good is on the android operating system, there's a browser called Dolphin, and it actually integrates into Dolphin. It won't integrate into Safari on iOS, they just won't let it.  But you can get it as an app, but then you copy a password and then you jump back in through another app. It's a little bit annoying.  So I'm actually using Dolphin on android. So on my phone I still have the goodness of LastPass, so it remembers all my passwords so I can get it to auto login.

Mike: This is good for web browsing, is it?  

Darren: It's purely for web browsing.  Is just the fact that it's embedded into the browser, the way it is for Chrome.

Mike: Yes, I must say I don't too much because it's too difficult on the iOS iPhone.  I guess there must be plugins for it.

Darren: I don’t think there is. 

Mike: I tend not to browse.

Darren: I don't believe there is a plugin first of all. I think they've actually locked it down that there are no plugins.  

Mike: Okay.

Darren: So Evernote hack – Do you want to do a pick?

Mike: Okay, I’ll do a pick.  Because I'm a big fan of Vim, I was just reading Ian Langworth’s story, he calls it “Vim After 11 Years.” He’s been a developer for a long time.  The link is in the show notes. I don't know how many of you out there are using Vim but he talks about how customizable Vim is. There are a squillion plugins to do all sorts of things from stuff like syntax highlighting, file manipulation and editing, and file management and that kind of stuff. Completely re-customizable. What else has it got, it's got things like registers. So everything you do, if you cut and paste something it will go into a register and it’s always there. You can shift back and forwards. It's a very nice article. As I said, I'm quite a Vim fan. He goes through it in details. But all the stuff, I've forgotten actually.

Darren: I'm currently using Sublime 2.0. I quite like Sublime 2.0. And I also have nothing against Emacs, but I'm not a par user of Emacs or Vim. I do like my fatter client, if you know what I mean.  

Mike: Can you do split screen in Sublime?

Darren: I don't know actually. I've never tried to do split screen yet. 

Mike: That's one of the things that I quite like with Vim, especially if I'm writing Rails stuff. I can split the screen, have my test, and run that in one, and have it cooled down and waiting in the other. It's very nice.

Darren: Yes, when I'm doing that I’m generally using Guard, so I've got the test running in a separate terminal window.

Mike: Yes, I have been there as well. But check it out. If you're interested in Vim – like I said, I'm a bit of a geek on it – terminal buffer, registers – he talks about it all, and all the plugins that are available as well. So it's well worth the read if it gets you going. Yes, next.

Darren: Next, I'll do the next one, “Tesla Motors Master Plan.” 

Mike: Whoa, what's that?

Darren: You know Tesla Motors, the electric car company. There's a posting by Elon Musk, which is the Co-Founder and CEO, and he basically just explains what his master plan for Tesla Motors is and was.  Basically he talks about the car that he was trying to build and how it stacks up to other ones. But the short of it is that his master plan is to build a sports car, use that money to build an affordable car, use that money to build an even more affordable car, and all at the same time trying to drive down emissions and increase electric car generation.  

Mike: So where's he at for the moment then?

Darren: Well, he has got Tesla Roadster out, and the Model S. So they've done the sports car, and they’re still delivering them.  There was a story last week, or the week before, about a journalist in New York who had taken the car for a drive and actually had run out of fuel.  And then there was a bit of a spark between them because they had the full GPS readings of the car and they were saying that he was going around and around in circles and stuff.  And then he was saying that he got lost and couldn't find the refueling station.  So he had to drive around and around looking for it.  They were like are you trying to sabotage the release?  According to some resources, some preorders got canceled.  There was another journalist that did the CM car journey and they say it worked absolutely fine.  But I think realistically if I'm going to be driving across country, I'm going to find out where the recharging statin is before I leave and not halfway down the road.

Mike: Yes, I think you should.  It's far too new.

Darren: Yes. I really like Elon Musk. I think what he's trying to do – he also owns SpaceX, you know that private space company that is now launching satellites in space.  It was the first commercial rocket that docked with the International Space Station.  

Mike: Okay.

Darren: So I just think that one person is having such an impact trying to actually create a commercial space company as well as creating an electric car company.  

Mike: Very cool, yes.

Darren: And he's also invested in another company called SolarCity which then make [INAUDIBLE 18:33].  Some other articles I was reading that he'd written in the past that he's trying to create free charging stations in the future.  So if it takes off he wants to make it free and he wants the cars and stuff to be able to use these batteries.  He's got some grand plans.  It's a very hard thing to do.  But he does do some comparisons to the other cars that are there, the Honda CNG, the Honda FCX, and the Toyota Prius, and it talks about their CO2 emissions, and you can see that the Testla Roadster is  considerably less and the efficiencies considerably more.

Mike: How much do these things cost?

Darren: At this point, beyond our pay grade. 

Mike: [Laughter]

Darren: Well let me have a look. How much is a muffler? Financing, service plans. I think there's a long wait for Tesla as well. It's taking a lot longer than they expect. 

Mike: I can't see any pictures either. I'm looking for a nice picture of it. 

Darren: Well, the Model S is $52,000.

Mike: Dollars? 

Darren: Yes.

Mike: US dollars?

Darren: US Dollars.  

Mike: Okay.

Darren: The other ones are coming a bit later.  They've got the Model S, and they're doing a Model S Signature which looks like more of a saloon, and then they're doing I think the Model X, which I think is a bit more of a family car. It's not so much for the people who own companies, but the people who work in companies. I really like what they're doing. I truly believe that electric cars are the way of the future.

Mike: Yes.  When I was back in the UK in November, there are all these recharging points coming up, like popping up everywhere now.  So at the service stations or the motorways and stuff, you can just plug your car in.

Darren: I’ve seen, I can’t remember the name of it now, an electric motor bike?

Mike: Yes, I have seen electric – it was a couple of years ago I think the last time I linked to one of those. 

Darren: He was hooning around on it for a couple of hours and it cost like $2 in electric. Unrelated, there’s a thing on graphene, which is like a type of carbon. I don’t actually have the post on me but some scientist has come up with a new way of using graphite, well graphene as a flexible battery. They’re trying to get stuff through the patent office so everything is very hush, hush. They’re saying that hopefully in the next 10 years it’s going to revolutionize batteries. 

Mike: They’ve been saying that for a while though.

Darren: I know. I know.  

Mike: All right. Let’s move on. Okay, so I just saw one here from Design Modal, it’s a GitHub account. But it’s really for all you web designers out there if there are any listening. They’re offering a free web user interface kit called Flat UI. Most of the stuff they offer is chargeable, but this is free for the moment. So go grab it while you can. A whole bunch of buttons, menus, inputs, progress bars and sliders, navigations, all the normal stuff. It looks very nice. It’s built with the back of Bootstrap.

Darren: Twitter Bootstrap.

Mike: But they’ve got vectors and fonts and glyphs and all sorts of – 

Darren: It looks very good actually.

Mike: Very nice things in there, yes, and it’s free. And the link to the ones they offered free previously, they’re normally now about $39. So download it while you can. 

Darren: Yes, I might have to do that myself. I just bought a similar looking one last week.

Mike: Yes, I think there was one on here, on the news a couple of weeks ago. But as I said that’s now $39. So go grab it quick.  

Darren: I’m hitting the download button as we speak. 

Mike: You might never use it but – 

Darren: I’d prefer to have it and not use it. 

Mike: Absolutely, yes.  Keep it in your little tool box.

Darren: All right, so I’ll do one more pick for Hacker News and it is “Open Source Events Burned by PayPal.” 

Mike: What’s all that about.

Darren: It’s about a Python conference, Django/Python conference which was in Europe, that had its PayPal account frozen. And then they basically keep all the assets, and then they were trying to get the money back. So a lot of people have already paid. What was this one, “Just confirmed, conferences having issues with PayPal. It’s a combined total of over one-hundred thousand dollars of all these open source conferences that have problems with getting money out of PayPal.”

Mike: Wow, that’s a lot of money.

Darren: That’s a lot of money. And they’re saying that a lot of conferences keep quiet about it because they are afraid that making a fuss will annoy the anti-fraud people at PayPal. So they try to keep quiet and see if they can get the money.

Mike: So what was the big issue then? It was a Python conference. What were they trying to get out of PayPal? So people who went there bought their tickets through PayPal?

Darren: Yes, PayPal was a payment method, and they bought the tickets through PayPal and then PayPal froze the accounts and said that they considered it may be fraud, at which point they said you need to go through the fraud process, and would not pay the money. What happens for the conference is that they still have to pay the outgoings for rent, etc., and then try to reclaim that money later.  So they’re having a lot of issues. And they’re saying that a legal recourse against PayPal is just a folly. And they say they’ve got an army of lawyers. It isn’t a bank. And by agreeing to the PayPal terms of service you are prevented from joining a class action lawsuit against them.  

Mike: That’s not good.

Darren: Which basically means you can’t really sue them. 

Mike: Yes.

Darren: So people are recommending that they move over to Stripe or someone else.

Mike: I was about to say Stripe. 

Darren: Yes, well I’d probably try to go to Braintree Payments because Stripe’s not available here.  It basically says that PayPal is the big boy on the market and they’re just locking stuff up.  

Mike: It doesn’t look well.

Darren: They’ve got PayPal evangelists that seem to be working against the anti-fraud people. I’ve had a few problems with PayPal in the past myself. But I just thought it was interesting that they’re talking about the fact that they get locked out and in the meantime they have to try to get money out and then they have to go through the anti-fraud.

Mike: So did they actually get the money back then?

Darren: It doesn’t say if they got the money back. It just talks about them burning conferences year after year. 

Mike: That’s not good, not good at all.

Darren: No. That was just for people to think about who they’re going to use. 

Mike: Yes. It’s interesting.

Darren: Okay, Mike.  Well do you want to talk a bit more about RubyConf?

Mike: Okay, yes. So it wasn’t last week, it was the week before.

Darren: Yes, but we didn’t get to talk too much about it last week due to time constraints. We did go a bit over. The show is aimed for less than 45 minutes and I think we went over an hour for the last one.  So hopefully we can get this one in a bit shorter. So do you want to just pick one of the sessions and we’ll start going through it?

Mike: Okay. So am I on mute?

Darren: You’re on mute now.

Mike: Can you hear me now?

Darren: Yes. I can hear you.

Mike: Okay. Which one to go to, which one? I ran through the sessions last week. Do you want me to just quickly go through them again or not?

Darren: I don’t think you need to go through them again. Just pick one.

Mike: Okay, let me talk about Will Farrington. Will Farrington is a GitHubber. His talk was on “Managing an Army of Laptops with Puppet.” There were quite a few GitHubbers at the conference as a habit. I don’t know where they all live but they were all American. So there seems to be have been a lot of them coming across the [INAUDIBLE 02:10]. I probably mentioned this last time, this guy spoke so fast it was unbelievable. Big ginger beard, very nice guy, but he spoke a hundred miles an hour. And the initial impression was he was going to run out of speed after 5 minutes. But he carried on for the full 45. Actually, I can’t remember what his job title was, but GitHub faced some challenges with all the new starters that were coming on, dozens of these projects. It was just a real nightmare for them to get their developers all setup. So they created a project called Boxen, it’s on GitHub.com-Boxen. He basically talked in depth about this project and what it gave for the developers basically to provision a working desktop within a couple of minutes.  At the moment it only works on Mac iOS, but there are plans to spin it off to Linux and such like as well. It was very interesting the way he talked about it. I’ve gone blank, Darren.

Darren: That’s all right. I was actually checking out Lanyard.com. I’ve seen that they’ve got some of the videos on. They’ve got the “Sinatra in Six Lines: How to do crazy stuff with Ruby,” that’s now on Lanyard. 

Mike: So the “Sinatra in SIX lines” is probably one of the funniest things I’ve ever seen in my life. You really need to watch it. I only went there because I couldn’t get into I think it was the Rails live streaming one because it was all packed out. So it was basically sit on the floor or nothing.  

Darren: Just for the other people, the slides that are currently available are: the “Speaker Deck: Share Presentations without the Mess,” the “Schemas for a Real World,” “RubyConf Australia High Availability,” “Uptime at Braintree,” and “Hacking with Gems.”

Mike: “Hacking with Gems” is also definitely one that I would recommend. That was something that we’ve all thought about. I can’t remember his name, what’s his name, “Hacking with Gems” was Benjamin Smith, wasn’t it?

Darren: Yes.

Mike: So Benjamin Smith, he works for Pivotal Labs, and he walked through about 5 or 6 gems that he’s written, all very easy, very simple, simple Ruby code that you would basically gem install and he’s got control of your machine, he’s got control of your GitHub environment. So any gems that you own, etc., etc. So if that slide is up there you should definitely watch it.

Darren: Yes, I’ll have a watch of that. I’m just actually looking through the photos as we speak. 

Mike: Am I in the audience?

Darren: I don’t think so. Most of them are pretty close-up photos. I think they’ve just been pulled off Twitter because there was one of a new born baby. We’ve got five slides, one video. They’ve also got “Using Ruby for Building iOS” slides.

Mike: Unfortunately, I didn’t manage to go to that one. Actually that was a bit of a shame. The special documentary, that was quite interesting. I think I mentioned it last week. 

Darren: Yes, you did mention it last week.

Mike: They showed about a 20-minute documentary that’s still a work in progress. A guy from the US was flown in, Kevin Triplett, and he’s making a documentary about “Why the Lucky Stiff.” That went down very well, which was then followed on by Aaron Patterson’s finishing keynote speech for that day. I don’t know if that talk is up yet, is it?

Darren: No, it’s not up yet. 

Mike: It’s not up yet. It was funny. I think you had to be there. It was one of those interactive sort of keynotes. It was just very funny. Lots of questions to Aaron about how the choices are made about what gets into Rails, etc., etc. and he seems to be of the opinion that everything that he mentions then gets declined by DHH. 

Darren: I did remember him being on Ruby Rogues and saying how he added mini tests into Rails, and then DHH came and took it out afterwards.

Mike: It was basically because he was showing mini tests. You could sort of mangle it so it looked exactly like our spec.  DHH has got a fabricated of our speck. So it was in there and then it came out which was a real shame. If the video comes out, definitely watch it because he’s highly entertaining. You all seem to have this thing with cats, though. Him and Corey Haines. 

Darren: Yes, a lot of people on the internet have things with cats and I just don’t get it. 

Mike: I have a cats but I just don’t talk about them.  So what else?  The “Hacking with Gems,” you’ve got to watch that when it comes out. It’s extremely funny, and opened your eyes up to what you could do with Ruby gems and how you could use and abuse it. 

Darren: You did that, then last week your pick was the Canary gem. 

Mike: It was the Canary gem, yes. My pick for later on is something else that he also recommended as well. What else have we got?  “State of Ruby,” by Ben Hoskings. He was basically talking through MRI, JRuby, Rubinius and all the other JRuby implementations. There was no real conclusion at the end of it. I think JRuby and Rubinius seem to have a lot of attraction at the moment being [INAUDIBLE 8:57], but JRuby seems to be the big grand scale implementation of Ruby.

Darren: So this is the point in the show where we try to make some recommendations on some software or something techie and something non techie. I will start and I will do a techie pick. I got an email from SandGrid.

Mike: Who is SandGrid?

Darren: SandGrid is a transactional email service. I wasn’t actually picking them at this point. But like Mandril, remember using Mandril? It’s the same thing. They came out before Mandril because Mandril is the Mail Chimp equivalent, SandGrid was the first real – I think they’re a YC company, and they’ve come out with transactional emails. And they’ve gone guns at it. They now have a new bit of software which is in beta, and I got an email about it and I signed up for it, called loader.io. And it’s a stress testing tool. It looks pretty well featured. It’s the sort of tool that you would be paying a bit of money for. There’s no mention about the actual pricing once it moves out of beta but for anyone who’s listening, it might be worth going and checking out. 

Mike: So it has Ruby APIs, Java APIs?

Darren: It’s more for stress testing websites. So just jump on the website and have a look.

Mike: Do you want me to do one or not?

Darren: Yes, you can do one.

Mike: This is sort of a non-techie one, or is it’s a techie one. I’ve got an iMac 27 inch. And obviously that’s rather large. So I’ve been looking for a Windows management tool to manage the workspace. In the last couple of days, I’ve been playing around with this software called Divvy. I’ve just got the free trial download. I guess you need to have a big screen to make this work but it’s very handy. You can click on the Divvy icon, you get a little grid, and you can pop all your windows into one, two, three, four, five, six, seven, eight, 8 by 6 boxes if you’d like. So you can fit all your screen into little boxes and it minimizes them all for you. It’s very nice.

Darren: Sounds good.

Mike: For big screens.

Darren: I can understand what it does. I just wish I had a screen big enough. 
Just while I was talking about that loader.io, it does have web pages and restful services. So it’s not language specific so it will hit either URL or restful services. It will support anything that’s doing rest. So Java, C-sharp, Ruby, whatever you want. It’s definitely worth the look while it’s free as well. 

Mike: Actually I’ll load it up now. 

Darren: My other still sort of techie pick is AppSumo, it’s like a daily deals site for software developers and techie people. I’ve bought quite a few stuff off of there. They send me an email once a week with some offers that they have. 

Mike: So what kind of things have you bought off of there?

Darren: I’ve bought image packs, icon vector packs. I bought access to the Treehouse which is an online code teaching website. I think it was $100 bucks. It was normally like $300 bucks and it was $100 for a years’ subscription to their videos, well to their site. They’ve actually got a bunch of stuff in there.  There’s a lot of stuff in their video back catalogue, and I just downloaded them and I’m watching some of the stuff on PHP and Django and stuff that I haven’t read. There’s other ones on jQuery, color, there are ones on more genericky stuff around financing and business related stuff. There’s Ruby and Rails and android and iOS.

Mike: I’m guessing there are a few free ones as well.

Darren: I don’t know. I don’t think there are any free ones. I think it’s basically you pay to get in and then you have access, and it’s like a subscription service generally.  I haven’t actually watched any of the videos yet but I just bought that one. I bought Square UI which looks a little bit like that free UI, but more of a squarey sort of Windows 8 approach. And then that’s the whole UI system. I like to pick those up from time to time. I’ve got little projects that I’ll probably use those on in the future. 

Mike: Very cool.

Darren: So that would be my other pick for today.

Mike: So my other pick is going to be on the back of the “Hacking Ruby Gems” conference, one that you recommended. It’s called Little Snitch. I’m not sure if it runs in Windows. It’s definitely a Mac iOS. But basically it’s a firewall. It’s a very nice firewall. So if you’re using iTerm and such like that, and you’re installing gems and the gem is trying to do something weird, then Little Snitch will pop up a nice little graphical interface telling you what’s going on. You should definitely try it. Download it. It’s got like a silent mode. There are profiles for whether you’re going into home or office or internet café. You can set incoming connections, what’s live, what’s not, that kind of stuff, all the normal firewall utility stuff that goes on. 

Darren: I don’t actually have a firewall on my MacBook. I might actually have a look at that. 

Mike: As I say, having sat in that session about “Hacking Ruby Gems,” it’s made me think “Oh my goodness.”

Darren: It’s not too expensive. What’s this? Little Snitch.

Mike: It’s $14 – $14 is it?

Darren: No, it’s an upgrade, $16.95. I just jumped on the site. Single license is $35.

Mike: Oh, sorry, for Little Snitch. Yes. The Divvy screen management is $14. You should try it. Especially as it brings up nice little boxes within iTerm, because it fits in quite nicely with that. 

Darren: Yes, I’m going to download it as we speak.

Mike: Because everybody’s using iTerm.

Darren: Yes, I use iTerm2. 

Mike: Yes, iTerm2, yes.  It’s very cool. Give it a try. 

Darren: I used to use Terminator on the Linux machine. Terminator, that was pretty good. But I like iTerm. Depending on what I do. I sometimes still have a terminal window up, especially if I’m going to have something running in the background for a long time because I have a habit of closing the tabs on iTerm a bit too much and killing background processes that take a while to startup.

Mike: I see, yes. You should use screen. Type in screen. 

Darren: Screen?

Mike: Yes. 

Darren: I’ll have a look at that.

Mike: Type in screen, start your Rails up and disconnect out of it. I think it’s Control AD.

Darren: So what does it do?

Mike: It opens up a separate process so you can flip back to it. Basically you run a Rails app or whatever, run some process in there. You can see it creates a separate process tree. 

Darren: It basically disowns the process from that screen, from the terminal?

Mike: Yes. So you’re still in the same terminal. You can flip it back and forward. So if you hit Control AD, you’ll see it detaches and you can go back in again. It’s very cool.

Darren: I do that a lot of times when I’m starting up servers, I would detach that from the back end. 

Mike: Yes so start your Rails up or your Java or whatever, your Tomcat server or your Web logic server, hit Control AD and out you come. And it sits there running in the background. And you can go get it whenever you want. 

Darren: Unfortunately I’m doing a bit of Java work at the minute, so it’s Eclipse which is a big beast.

Mike: Yes, very big beast.

Darren: It does the job. I actually use STS, which is their spring source one. It does what it needs to do for what I’m doing. It’s fine.  I installed Little Snitch.

Mike: Installed LittIe Snitch? I think you have to reboot your machine after you install it. 

Darren: Fair enough. I’m installing it as we speak. Here we go. Restart now. 

Mike: Don’t do that, Darren, because you’ll disappear. 

Darren: The podcast is still going [Laughs].

Mike: So are we done?

Darren: I think we’re done for the day. 

Mike: Okay. So do we promise to have Lee there for next week?

Darren: Well, if Telstra will come around and fix this internet. Yes, Leigh Appel was supposed to join us today but as our run of luck continues, his internet crapped out with TPG and now he has to wait for someone from Telstra to come around and fix his internet connection. He’s booked in for Tuesday so hopefully he’ll be online next week. 

