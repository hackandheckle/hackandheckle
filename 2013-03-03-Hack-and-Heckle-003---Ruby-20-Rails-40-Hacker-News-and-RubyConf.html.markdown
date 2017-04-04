---
title: Hack and Heckle 003 - Ruby 2.0, Rails 4.0, Hacker News and RubyConf
date: '2013-03-03 00:36:58'
tags: []
---

<strong>Hack and Heckle 003 - Ruby 2.0, Rails 4.0, Hacker News and RubyConf</strong>

<a href="https://drive.google.com/open?id=0B3KFoVQ01nUJYlRib3pKd2lINFE">Show Audio File</a>

<strong>Show Notes:</strong>

News:

<a href="http://www.ruby-lang.org/en/news/2013/02/24/ruby-2-0-0-p0-is-released/">http://www.ruby-lang.org/en/news/2013/02/24/ruby-2-0-0-p0-is-released/</a>Â - Ruby 2.0 released

<a href="http://www.kickstarter.com/projects/1225193080/the-ruby-20-walkthrough/comments">http://www.kickstarter.com/projects/1225193080/the-ruby-20-walkthrough/comments</a>Â - Ruby 2.0 walkthrough

<a href="http://weblog.rubyonrails.org/2013/2/25/Rails-4-0-beta1/">http://weblog.rubyonrails.org/2013/2/25/Rails-4-0-beta1/</a>Â - Rails 4.0 beta 1

<a href="https://www.djangoproject.com/weblog/2013/feb/26/15/">https://www.djangoproject.com/weblog/2013/feb/26/15/</a>Â - Django 1.5

&nbsp;

Hacker News:

<a href="http://news.ycombinator.com/item?id=5283160">http://news.ycombinator.com/item?id=5283160</a>Â - Why a one-room West Virginia library runs a $20,000 Cisco router

<a href="https://speakerdeck.com/garrettdimon/bootstrapping-a-software-product">https://speakerdeck.com/garrettdimon/bootstrapping-a-software-product</a>Â - Bootstrapping a product

<a href="https://medium.com/life-of-learning/39ba4ff482e1">https://medium.com/life-of-learning/39ba4ff482e1</a>Â - How to start working on a side project

<a href="http://www.marco.org/2013/02/25/adn-freemium">http://www.marco.org/2013/02/25/adn-freemium</a>Â - App.net new direction (free accounts)

<a href="http://thenextweb.com/mobile/2013/02/25/sony-jumps-on-the-mozilla-bandwagon-will-bring-launch-firefox-os/">http://thenextweb.com/mobile/2013/02/25/sony-jumps-on-the-mozilla-bandwagon-will-bring-launch-firefox-os/</a>Â - Sony to Release Mozilla Firefox OS Platform

<a href="http://www.google.com/glass/start/">http://www.google.com/glass/start/</a>Â - google glass

<a href="http://www.thestreet.com/story/11850432/1/watch-out-for-google-glasses.html">http://www.thestreet.com/story/11850432/1/watch-out-for-google-glasses.html</a>Â - Watch out for Google Glass

&nbsp;

RubyConf:

<a href="http://www.rubyconf.org.au/">http://www.rubyconf.org.au/</a>

<a href="http://lanyrd.com/2013/rubyconf-australia/schedule/">http://lanyrd.com/2013/rubyconf-australia/schedule/</a>

<a href="http://jruby.org/">http://jruby.org/</a>Â - JRuby

Picks:

DR :

Omnigraffle (Mac Visio) -Â <a href="http://www.omnigroup.com/products/omnigraffle/">http://www.omnigroup.com/products/omnigraffle/</a>

Audible (audio book service) -Â <a href="http://www.audible.com/">http://www.audible.com/</a>

The Launch Pad - Y Combinator storiesÂ Â - Randall StrossÂ (Book / Audio book)

&nbsp;

MM:

<a href="http://torquebox.org/">http://torquebox.org/</a>Â - TorqueBox (JRuby Application Server)

<a href="http://rubygems.org/gems/coal-mine-canary">http://rubygems.org/gems/coal-mine-canary</a>Â -Â coal-mine-canary - Ben Smith - checks got bad gem behaviour.

Show Notes:

Darren: Hello and welcome to the show. Itâ€™s been a few weeks since weâ€™ve been on air, but weâ€™ve had a few unexpected hiccups. Weâ€™ve had some large hail storms in Queensland, some power outages. I myself, well my wife, weâ€™ve had a new baby. And weâ€™ve also had some visitors come over from the UK. Everything is now back to normal and the show has returned. We will endeavor to have a weekly show from now on so please bear with us. So, Mike, whatâ€™s happened this week in the news?

Mike: Well, this week, big announcement. Ruby 2.0 came out, Ruby 2.0.0. I think it was 20 years to the day when Ruby was first released. I think it's been a very long time in the making. I canâ€™t remember how many years. So very exciting. Ruby 2.0, as I said it's been a long time coming. It doesn't offer a massive amount of new features and stuff but it's a lot of bug fixes and it's certainly a great way to go forward. 

Darren: Yes, there are some enumerables or something thatâ€™s some new stuff, and some VM optimizations and stuff like that, isn't there?

Mike: Yes, and what else have you got. You've got the refinements. I think the refinements was a big one.

Darren: Yes, but refinements, I thought refinements â€“ itâ€™s in the language but it's in prototype mode or something.

Mike: Yes, it's in but it's not quite made it to release if you like. It's all about monkey patching and how to do monkey patching in a safe way if you like.

Darren: Did you listen to the Ruby Rogues where theyâ€™re actually talking about how â€“ was it the last one â€“ one guy was saying about his talk on the conferences and how he wants to change how stuff gets into Ruby and how itâ€™s all down to one guy if you know what I mean.

Mike: Yes, itâ€™s all down to Max at the moment, isnâ€™t it? He controls it. I think the Ruby community is quite happy to let Max do it until it becomes an obstacle. He ultimately has the final decision pretty much in the same way as David Heinemeier Hansson as with Rails. 

Darren: I think it helps with some cohesion, but I do understand because Iâ€™m from a Java background with the JCEs, the JCP, the Java Community Process, how having more of a community that makes a group decision feels more inclusive if you know what I mean. Iâ€™m not saying heâ€™s done a bad job. I think heâ€™s done quite a good job, but it is difficult when itâ€™s pinned on one person. 

Mike: But, I think at the moment it probably works well. The Ruby community, I think theyâ€™re â€“ whatâ€™s the word â€“ theyâ€™re all in awe of Max. Itâ€™s working at the moment.

Darren: I think it definitely is. I just wonder how long, oh no, Iâ€™m sorry. I was going to say thereâ€™s a new version of Ruby out.

Mike: I think I just said that, Darren.

Darren: Sorry? No I mean a new point release. So, should I jump in now or should I wait for the next point release which is then going to bring some of those features up. 

Mike: Oh, I see. I think with the eminent release of Rails 4.0 then that fully supports Ruby 2.0. 

Darren: Actually before we get to that.

Mike: Go on sir. 

Darren: Talking about Rails, Iâ€™m sure youâ€™re a backer like myself of the Ruby 2.0 walk through by Peter Cooper, the Kickstarter Project. I have my email. It is done. I havenâ€™t actually listened to the video yet or watched the video yet. He did say something about having a tongue ulcer, so hopefully heâ€™s articulate enough. But he generally was. His 1.9 one was really, really good. So Iâ€™m looking forward to this 2.0 one. 

Mike: Like yourself, Iâ€™ve actually downloaded it but I just havenâ€™t had a chance to look at it. I think heâ€™s released most of the [INAUDIBLE 4:55]. Is it in six parts or eight parts?

Darren: Seven parts I think.

Mike: Sever parts? I think heâ€™s still to release the final two I think is my understanding. I havenâ€™t had a chance to look at it either. 

Darren: Heâ€™s had a young baby as well. It sort of throws your timelines and your scheduling out a bit. As you can tell, there has been no podcast for a couple of weeks. So it can get a bit hard to get time. 

Mike: I can understand. And I think he was quite ill as well as you said. 

Darren: Yes, but Iâ€™m looking forward to that. You were saying, Rails 4.0.

Mike: Yes, Rails 4.0 has just been released right off the back of Ruby 2.0. Beta one is officially out. Likewise, I havenâ€™t had a chance to play with it. Itâ€™s only been like three days. Looking forward to downloading that and installing that and starting to play with that. Lots of new changes. Do you want to go through them all?

Darren: No, we donâ€™t have to go through them all. I see that Basecamp Breeze is out and thatâ€™s running Rails 4.0 on Ruby 2.0. 

Mike: Okay. Iâ€™m just looking at that now.

Darren: Just for some other ones, itâ€™s got turbo links which is the new JavaScript linking, well it turns it into a single page. But it did break a few stuff and some gems didnâ€™t work with it. I wonder if thatâ€™s all been resolved yet.

Mike: Yes, so the turbo links is basically, Iâ€™m trying to remember, what was it called, PScript or something? No, it wasnâ€™t PScript, but itâ€™s basically where part of the page gets refreshed dynamically by Java Scripts so it doesnâ€™t have to do a full page refresh.

Darren: Yes.

Mike: Yes. It did go by another name before but I canâ€™t remember what it was called. 

Darren: Did, what do you call him off Ruby Rogues, he wrote it, didnâ€™t he? The turbo links library?

Mike: Which one? What Josh?

Darren: No, the one in the wheelchair. Whatâ€™s his name? Iâ€™m terrible with names. 

Mike: James Edward Gray.

Darren: Yes, I think thatâ€™s James Edward Grayâ€™s project, the turbo links. Iâ€™m pretty certain it is. 

Mike: I think it stemmed from PJax. I think thatâ€™s the one it came from. I actually thought that it was David Heinemeier Hansson that wrote that. 

Darren: Was that?

Mike: I could be wrong.

Darren: I donâ€™t think so. I see now that theyâ€™ve got strong parameters by default which I think is very important to guard against the parameter injection stuff. 

Mike: Absolutely, yes. 

Darren: There still seems to be lots of issues with YAML, so I donâ€™t know how long weâ€™ll have beta one before weâ€™ve got some security fixes. 

Mike: Iâ€™m not sure if youâ€™ve heard about that YAML, but, Darren, Iâ€™ll speak about the Ruby conference shortly, but that YAML problem or the problems that came out of it, it was pretty touch and go for a second, bringing down, for example, all the Ruby Gem servers. It was real serious stuff. There was almost a catastrophe of the internet that was thankfully stopped by all the guys that pulled the stops out to fix it. 

Darren: Yes, it was pretty close. 

Mike: It was very, very serious.

Darren: I heard it was down, down to the line. 

Mike: Yes.

Darren: Yes, because the gem server got corrupted and anyone who was taking from that would have corrupted and I think Heroku pulled the plug on gems and deployments. If they hadnâ€™t acted as quickly as they did then it would have been completely gone. But for anyone listening who is a Ruby developer, you must, absolutely must update your Rails bundle to one of the new security fixes. The security vulnerability has been added to Metasploit so itâ€™s a one button click for script jockey to just take over your server basically. They can inject and they can take over and they can do whatever they want. Once theyâ€™re in, itâ€™s extremely hard to do anything because itâ€™s all boundary security. So once they get past that boundary, itâ€™s basically open slather. So I strongly recommend anyone who hasnâ€™t to go do it now. Before we get on to the conference, one other release this week which weâ€™ll talk about which is Django 1.5 has been released. Django is like Rails but for Python. I might actually just leave it at that for now because I havenâ€™t really used it too much. But Iâ€™m going to have a new guest joining us next week, a new host. Heâ€™s going to join us going forward and he has been playing around with Django. So when he comes on next week, we might ask him a bit more about it, what it is, what this 1.5 release means, etc., and maybe how can he describe it.

Mike: So do we know if this is a major release?

Darren: Yes, itâ€™s a major release. 

Mike: So this is the Python back end, the Python Rails framework, isnâ€™t it?

Darren: Yes. I was asking Lee about it. He really likes it. I havenâ€™t played with it myself, but they seem to be sort of copying the best ideas from each other.

Mike: Yes, I think. 

Darren: But yes, Lee [INAUDIBLE 10:36] will be joining us next week. Unfortunately he couldnâ€™t make it this week. He was planning on coming this week, but hopefully weâ€™ll have him next week. Then we can actually ask him a bit more about the Django stuff. 

Mike: Sounds good.

Darren: A section we havenâ€™t done before which is going to be included which is Hacker News. So weâ€™re going to pick some stories this week of Hacker News that have taken our fancy. Then weâ€™re going to have a brief discussion about some of those. We may have a bit more next week but this week with Mike being down to RubyConf, which weâ€™ll talk about a bit later, Iâ€™m just going to do a couple of picks, Iâ€™ll have a bit of a discussion, and then weâ€™ll move on. But we might have a shorter show. The first one which I came across which I really liked, which Iâ€™ll put in the show notes, was actually Bootstrapping a Software Product. Which is an old slide deck. I was actually released in September 2011, but I only seen it on Hacker News this week. And what it is is this guy called Gareth Diamond whoâ€™s created a hosted bug and issue tracking system called Sifter, heâ€™s talking about how he started his product, so the lessons learned from being a solo finder and releasing his app. Itâ€™s a Rails app, but heâ€™s talking about how much it costs, what he thinks he did right, what he thinks he did wrong, what it really was like. He goes through some of the periods of his life when things happened. Iâ€™ll put the link in the show notes but I think itâ€™s good for anyone whoâ€™s interested in doing a software product, because I thought it was pretty good. 

Mike: I sounds interesting. You need to send me that link. 

Darren: Yes, Iâ€™ll send you the link. Because it was a pretty straightforward product. And he does talk about when he looked at it at a micro level that he didnâ€™t feel like he was getting anywhere, but when he looked at it over a longer term then it was much better. And he was saying how he started it up on the side, kept his job going. He didnâ€™t make enough revenue to quit his day job as it was. But then once he got it up to a certain point where he was able to get a better revenue, that he was then able to pay his mortgage and bills, at that point he then quit his day job. And he did take a significant pay cut, but at least he was able to pay his bills, and then he was able to focus on his app. And at that point he was tried and tested because he was getting a revenue stream. I think these days with startups, weâ€™ve heavily focused on getting investments from angels. Itâ€™s not free money. They want the money back. So it either works, I wouldnâ€™t say that angel money is bad, but I think people underestimate bootstrapping your own business.

Mike: Yes. I think a lot of people are out to make a fast buck, get a big company interested in them and then possibly try and sell it off again.

Darren: Just flip the company.

Mike: Yes. 

Darren: See thatâ€™s okay if youâ€™re living in Silicon Valley. But if youâ€™re living somewhere else, the eco system of building up a small company to a medium sized company, and then it to be purchased, it just isnâ€™t as big. So I think bootstrapping and making a profitable product from the start is something really worth doing. 

Mike: I guess it all depends on who you are, what you want. Some people do it just so they can get bought. 

Darren: Yes. 

Mike: And other people, like Evernote, I think they are long time planners to be around for years. They donâ€™t want to be bought by anybody. Similarly like Dropbox, Apple came and made them an offer and they turned around and said no. Could easily have made the founders very rich.

Darren: Yes, it just depends on what you want to do. Iâ€™m a software developer just like yourself. So always in the back of my mind is that Iâ€™ll do my own product. I just havenâ€™t thought of it yet [Laughter].

Mike: Yes, you and me both, Darren [Laughter]. Itâ€™s coming to me though, itâ€™s coming to me very soon. I can feel it. 

Darren: Yes. I do really like this slide pack as it does through it in an open and honest approach. It is really probably him over three years, and he does show a bit of a timeline about him getting married and having kids, worst period of his life and stuff. But anyone whoâ€™s thinking about doing a product on bootstrapping, I think itâ€™s definitely worth a read. 

Mike: Sounds good.

Darren: So on that, another one which is sort of similar is there was another posting which I came across which was â€œHow to Start Working on a Side Projectâ€�. It was written by a guy called Gordon Koo on the 24th of February. And heâ€™s talking about itâ€™s good to keep your skills updated, that life can get in the way but itâ€™s good to just have some side projects and to do something interesting and only do it when you want to do it. And try to set yourself some goals and stuff like that. But I think itâ€™s very good. As you were saying in the pre-show discussion, Iâ€™m quite active if you know what I mean. With having a young child Iâ€™m still doing the podcast and learning new stuff, as well as doing a normal 9 to 5 job.

Mike: 9 to 5 job and being a father.

Darren: Yes, and the father of a nearly 3-year-old and nearly 3-week-old, and my lovely wife whoâ€™s definitely never going to listen to this [Laughs]. Sheâ€™s just had a baby so her hormones arenâ€™t exactly the pre-baby level, and I will just leave it at that. 

Mike: Yes, itâ€™s probably best to.

Darren: But it talks about working slots into your regular schedule. Like one of the things I was doing before I was driving into work, I was getting a bus. I actually spent that, which was probably an hour to an hour in a half each day, doing some stuff. I have a MacBook Air, so I was actually doing a bit of Ruby Motion stuff or Iâ€™d be reading. Iâ€™ve got some audio books and Iâ€™ve recently just got my Kickstarter I Draw Comics book. So Iâ€™m actually just doing my comics, brushing up on my artwork again. And I just find that makes it useful because Iâ€™m trying to maximize the time that I have. So yes, this posting I think is quite relevant for me at the minute and for other people too. So itâ€™s definitely worth the read. 

Mike: Yep, send me links.

Darren: Will do. I donâ€™t know if you saw this but I was on Marco.org, I think I came across it from Hacker News as well, which is talking about â€“ well App.net has launched free accounts. You and I are the only two people that I know that are on App.net, like personally now. But yes, theyâ€™ve released some free accounts. 

Mike: There must be some limits on there, are there?

Darren: Free clients can only have 40 people. So you can only follow 40 people. And App.net has also released a new file API. 

Mike: Yes, I read about that. Yes. That link is really interesting. 

Darren: It does, but the free one, theyâ€™ve got a limited storage. My only issue with that â€“ I know theyâ€™re trying to differentiate themselves from Twitter but do I want to pay to have my files stored on there? Because I've already got drop box. I already have Google Drive, and I've got 100 gigs a month for $5 bucks. Do I want another service on App.net? I'm not sure.

Mike: I haven't actually played with it myself. I read about it. It must have been a couple of weeks old now isnâ€™t it?

Darren: Yes. 

Mike: The file service.

Darren: The file service is a couple of weeks old.

Mike: It sounded quite cool, and offers up a lot more opportunities for development type â€“ different applications that you can now plug into App.net.

Darren: App.net has gotten quite quiet as well. I donâ€™t know if it's going to last like I want it to last, but I don't know if it's got enough traction.

Mike: Well, if they're now offering free accounts then they must be doing something right. I haven't looked at their use accounts recently but the last time I looked it was last year and it was kicking on 30,000. So if theyâ€™re offering free accounts they must be way above that.

Darren: I think they're worried that they're going to have a mass exodus at the end of the first paid period, if you know what I mean, where the people who paid won't pay again. Because I've got a developer account which is like 100 bucks, and another personal account which is like 50 bucks, so I give them $150 and I barely use it to be honest. I check it from time to time but I check Twitter much more than I check App.net

Mike: Likewise, although I do try to keep up with it. But Twitter and is the go to application for that.

Darren: It is, it is. Some of the people I follow just aren't there. Marco is one of the people who I do follow, the Instapaper creator, and he was the podcast on that 5by5 show which is no longer on. I just thought it was interesting theyâ€™re now launching free accounts.

Mike: Yes, I didnâ€™t know that.

Darren: All right. So also on Hacker News, I saw a story in which I thought was quite interesting on Ars Technica which is â€œWhy a one-room Virginia library runs a $20,000 Cisco router,â€� and that West Virginia has wasted five million dollars on enterprise-class gear from Cisco.

Mike: That's shocking.

Darren: They've got a picture of it on the article. You have to check this out. It will be in the show notes. It's just Marmet Public Library and the router that's in there as like a $15,000 to $20,000 dollar router made for midsize to large-size deployments. It's only like one building, they've got one internet connection. â€œExtremely small facility with only one Internet connectionâ€� and a $20,000 router. 

Mike: Dear God.

Darren: Just crazy. Actually, while weâ€™re talking about routers, I was listening to Security Now, which is a podcast on Twit, and they have uncovered a security vulnerability in most routers. There are 81 million routers on the Internet with this security issue and it has to do with the UPNP which is a lot of stuff to auto connect and work out its own rights.

Mike: Universal plug and play.

Darren: Universal plug and play. I'll put it in the show notes, but Steve Gibson has got a web site called GRC. He's one of the hosts of Security Now, and in that he was talking about he's created a thing called Shields Up which is a scanner. You can go to his website and go to Shields Up and he will port scan your router to determine if you've got a security issue. I did, so I was very surprised. I went in and I turned UPNP off in my router. What that did allow people to do was take over your Internet. So they can take your local network and they could get in if they wanted. So there's a guy who scanned the entire Internet, and there are 81 million active devices with this vulnerability. It's not fully live as in it's not in Metasploit yet, but they are now updating their ROMs because it's just consumer routers.
Mike: That's scary.

Darren: You should go now to Shields Up. So if you just Google search Shields Up you'll get there.

Mike: Shields?

Darren: Shields as in protection shield, yes, just my Irish accent.

Mike: ShieldsUp.com.

Darren: I just do Shields Up in Google. It's not ShieldsUp.com, it's GRC.com. Steve Gibson Research Corporation, I think that's what itâ€™s called. Steve Gibson. And while you're doing that. Just have a look and see if your router is actuallyâ€¦

Mike: I'm clicking on proceed as we speak.

Darren: It doesn't take long at all to actually check. But it does mean that if it comes back saying that you are vulnerable, it does mean that somebody could take over your machine.

Mike: Yes. Did not respond to UPNP prompts.

Darren: That's great.

Mike: I have a green light.

Darren: I didn't. 

Mike: I have nothing turned on in my router then.

Darren: I didn't even realize I had it turned on. I think I was doing some Xbox Live stuff and I had to turn it on for Xbox Live to work. But the thing is I'll just log in and turn it on if I want to get on Xbox Live and then turned back off again when I'm done. 

Mike: Very interesting.

Darren: My router is not a $20,000 router.

Mike: [Laughing] So how many people did you say were infected, 80 million?

Darren: The guy who scanned the Internet said there something like 81 million devices.

Mike: Somebody could have fun with that.

Darren: They just have a complete port scanner and once it's put in to a scanning database, they just pick them up. They just scan your computer every so often for any vulnerabilities and then come along, check out what's inside your network and then it's not so much what you have, it's more about the fact that when they get in your network they use you as a bot net, as a platform to then do an attack. So then you're trying to explain to the Federal police it was me.

Mike: It was me sir, honest.

Darren: You know what happened to the guy who ran that Tor network in Austria. Remember that Tor network which is a private network? I could explain how it works another day but there's a guy who was running an exit node and he's been arrested and he's been charged for the websites and what people were doing when they were coming over that network. So you could be in the same position. Anyway, let's move on. Let's move to mobile. So on Hacker News, Iâ€™ve come across that Sony has jumped on the Mozilla bandwagon and will launch a Firefox OS device in 2014.

Mike: I've read about this, yes. Very interesting.

Darren: Well LG and Huawei, is that how you pronounce it? They've also committed to run a Firefox phone, and it's all HTML5 stuff. I don't know if we need another phone, but I do like Firefox. I always have, even though I've moved over to Chrome. I'd like to see what's there, what they're going to do.

Mike: Likewise, I'm a Chrome user now who used to be Firefox.

Darren: Yes. The mobile space is all getting a bit of a shakeup at the minute with Ubuntu phone coming out. I've watched the keynotes of those. They look really nice. Apparently they can run android apps as well. And also the new Blackberry, I checked out a bit of screencast with the new Blackberry phones. They look pretty nice.

Mike: Itâ€™s the Blackberry 10 or something, isn't it?

Darren: I canâ€™t remember the name of it, but apparently they can also run androids. So thereâ€™s a lot of android stuff.

Mike: I think itâ€™s android or â€“ well, I like Microsoft and Nokia, I don't know what's happening with them either.

Darren: I think Nokia got screwed over by Windows 7 phones not being compatible with Windows 8. But Nokia I think have put up their hand to say that they are doing Firefox I think it is. Let me just check. The Nokia Symbian platform. It doesn't say about them. Anyway, while we're talking about mobile, Google Glass has released a competition in the US for normal people to get their hands on some Google glasses.

Mike: [Laughter] So, you want to explain what Google Glass is?

Darren: Google Glass is basically a wearable android device with a screen which is placed in front of your eye and is a heads up display. So it's got a little bit of glass on that. It is transparent, but within that glass, it can actually display stuff. If you go to a Google Glass, it's actually got a really good video and it shows off some of the stuff that they're working on. It's got a built and video recorder as well. I really, really want one.

Mike: [Laughter] Now there's a surprise.

Darren: Yes, very big surprise. I wear glasses always anyway.

Mike: Is there anything available at the moment?

Darren: Not for us in Australia. I contacted them and theyâ€™ve said we will hope to sometime be releasing outside of America. So I got shot down. The only way I know to do it is basically to go to the Google IO conference. That's it. If you go to Google IO you can get your hands on them. From what Iâ€™ve heard, that was the only way to get them. But even saying that, it seems to be only people within the US that can get them which is really, really annoying.

Mike: Yes. They look quite cool actually.

Darren: They do. I think the form factor of the classes themselves is going to update and change. I wouldn't mind writing an app for it and seeing what I can do with it.

Mike: Yes, I think itâ€™s very clever.

Darren: I think it will be. I think it will be great. Turn by turn directions when you're driving in the car, I think that would be perfect. Anyway, on the back of that, on Hacker News I came across an article called â€œWatch out for Google glasses.â€�  Google glasses are supposed to come out this year, like generally on the market at the end of the year. So then they started talking about what impact that will have. So it's on TheStraight.com. Itâ€™s is a very good article that talks about what's going to happen and how people are going to get creepy and how people get freaked out when people are being filmed if you know what I mean. So what are they going to do when you're wearing the glasses, because they won't know you're recording because it's already on your head, it on your face. So you're going to have policies that say you canâ€™t wear Google classes here and you canâ€™t wear them there.

Mike: So we have video, and we have sound recording and we have all that kind of funny stuff.

Darren: So they're saying it's going to be very difficult to tell people if the thingâ€™s off. Will you start getting kicked out of premises? What's going to happen the first time some kid or some dick head â€“ Iâ€™m going to beep that out [Laughing] â€“ some personâ€¦

Mike: You should leave it in.

Darren: No, keep family friendly reading â€“ some person does something bad with them â€“ that goes into a public place and record something that they shouldn't just like they can with a mobile phone. This article was talking about the social interactions. So what's going to happen? It's a nice article. It makes you think about it. They're saying it's going to cost a grand and a half. But in a couple of years it might drop down to like 500 bucks. Once they get down to 500 bucks or so, then you may find them become more and more used, and more and more people having them. One thing they have mentioned which I think is important for most people to know is that theyâ€™re going to use Bluetooth to connect to your phone, or Wi-Fi with Bluetooth so they can share your internet. So there are discussions about them locking it down to only pair with an android device so you donâ€™t have a second radio request, you donâ€™t have yet another reason to get over paid connection from your mobile provider. So apparently theyâ€™re going to use Bluetooth to connect over and download over that, which is good to know. But itâ€™s probably going to be next year before we get our hands on them. Theyâ€™re going to be open to the public. Everyoneâ€™s going to get one, and Iâ€™m going to have to buy one and get it shipped over from America.

Mike: $1,500?

Darren: $1,500. I know, very expensive. But I want to build something on it. You know I like to learn new stuff and I like to do some techie stuff. So I would like to build an app for Google glasses. I do think that it is the future, that headâ€™s up display. And I would really, really like â€“ I can convince my wife that Iâ€™m going to buy one. 

Mike: Well Iâ€™m sure that Apple or somebody else will be working on something similar as well. 

Darren: I think at this minute itâ€™s dubbed the iWatch.

Mike: The iWatch, yes. Iâ€™ve seen that, because that was on the back of the Pebble watch thatâ€™s just come out. Itâ€™s a kickstarter project.

Darren: I think the term that theyâ€™re using is iWatch, which is the Apple Glass. I heard that Apple had been working on it before Google, but being Apple, theyâ€™re not saying anything. So everyoneâ€™s going with Google Glass. When the Apple comes out, theyâ€™ll try to call it something else. Theyâ€™re the two main operating systems so it will be an iOS device, and it will be an android device. So if you know iOS and you donâ€™t know android, you might want to wait until thereâ€™s an Apple one coming out. But if youâ€™re a Java developer or android, then Google Glass might be the way to go. I just think Google might be better in this instance because of the services â€“ the GPS and all that sort of stuff. If you look at the disaster that was Apple Maps, if you donâ€™t live in California then you donâ€™t want to use Apple Maps. 

Mike: Certainly, not in Australia. No.

Darren: Hell no. You can get lost in Victoria, three hours in the wrong direction.

Mike: The police had warnings up. [Laughing] Donâ€™t follow your Apple Maps because itâ€™s definitely going to go wrong here. Youâ€™ll get lost. 

Darren: Itâ€™s a bit silly.

Mike: Itâ€™s hilarious.

Darren: I know. So thatâ€™s it.

Mike: So thatâ€™s all fixed now.

Darren: Yes. Is it? The Apple Mapâ€™s all good now?

Mike: Well, I think a lot of those problems have been ironed out now, yes. Is it 6.02 or 6.03 is out now?

Darren: I donâ€™t know. As you know, I have done some iOS development stuff and we a newest iPhone in the house but my wife has it. I have got my trusty Galaxy III. Iâ€™m still an android phone â€“ MacBooker with an android phone. So thatâ€™s it for Hacker News.

Mike: You want to talk about RubyConf?

Darren: Yes, please. Tell me all about RubyConf?

Mike: Okay, so RubyConf was last week, Wednesday the 20th through to Friday the 22nd. The RubyConf itself was on Thursday and Friday, thatâ€™s where the sessions were. Wednesday was workshops if youâ€™d signed up for them. There must have been about 5 or 6 workshops, I canâ€™t remember. 

Darren: Whatâ€™s this, it says Rails Girls, Advanced Rails, Code Retreat, JRuby, Rails 4 iOS. Whatâ€™s Rails 4 iOS?

Mike: Rails development.

Darren: Itâ€™s actually saying let Rails be out backend. Which makes sense, thatâ€™s what Iâ€™ve been doing. 

Mike: Yes, absolutely. The Rails Girls, very nice. So weâ€™re keeping this family arenâ€™t we? I went to the JRuby workshop. Charles Nutter, one of the core contributors for JRuby and another guy called Hiro Asari, they both work for Red Hat and paid for by Red Hat. So the conference was all day. There was about 20 of us in the room, something like that.

Darren: So how long was this workshop? Was that an all day workshop?

Mike: It was 8 hours, yes.

Darren: So you basically had to pick one of those and that was the entire day?

Mike: Yes. For the day I think it was $95 and you could choose anyone you want obviously, apart from Ruby Girls [Laughing].

Darren: Well, to be honest, you know I would have been there except for we just had our newborn. So, Iâ€™ve got a bit of envy.

Mike: It was a very nice conference. Iâ€™ll tell you all about it. Charles Nutter, being the god on JRuby, he talked through installation of Ruby, Java and Ruby integration, how you call the Java libraries from Ruby, etc., etc. It was very much a hands-on one, Darren. Everybody had their laptops. Nobody came prepared apart from me. So the first hour was spent trying to install Java and trying to get everything up and running. Problems we had, there were no internet connections. 

Darren: Thatâ€™s always the same. 

Mike: It was really bad. Hiroâ€™s talk was all about the Red Hatâ€™s open sourced, what do you call it, OpenShift? 

Darren: OpenShift, yes.

Mike: Have you heard of OpenShift yet?

Darren: Yes.

Mike: We unfortunately didnâ€™t get to hear that talk because there was hands-on demo about how you create OpenShift application and deploy it up to the web, which was very disappointing. But the whole thing was very good fun. Lots of people asking questions.

Darren: Iâ€™m just going to put my neck out here, I truly think that Ruby will move on the JVM, because theyâ€™re sorting the threading. Rails is sorting the threading. And the JVM is the beesâ€™ knees in regards to performance. 

Mike: Yes, absolutely. Some of the performance stats that Charles had done for the end of it, it was comparing Ruby 1.8.7, 1.9.3, even the new Ruby 2.0 based on whatever it was.

Darren: On the JVM and the RMI?

Mike: Yes, mixing MRI, Rubinius. The very last one was JRuby with Java extensions. So weâ€™re going from like maybe 5 seconds all the way down to 0.1 with JRuby and Java extensions, like blindingly fast. And granted, that was on JDK 8 or Open JDK 8 because all the new stuff is in there which has not been released in Java 7.

Darren: Yes, I canâ€™t wait for JDK 8 myself. I still do a lot of Java work. 

Mike: The whole thing was very interesting. Both of them are really smart guys. One of the things Iâ€™ve been playing with is TorqueBox. He was talking about the new web servers basically for multi-threading front ends. So TorqueBox, Puma, Trinidad, and services like that for the Ruby. Like in MRI world, you have WebReg and Unicorn and such like that. TorqueBox is the new one and I think itâ€™s being supported by Red Hat now. So you can run a fully functional JBoss application.

Darren: It sits on top of JBoss. Yes, I was actually looking at that probably three weeks ago. 

Mike: Itâ€™s very nice. It comes with all the messaging and all the funky stuff youâ€™d expect from a J2E server â€“ the messaging, the transactions. And Red Hat are now supporting that with JRuby Rails application type thing so you can buy a fully featured support model from them. 

Darren: Thatâ€™s great. 

Mike: On the cloud. 

Darren: Thatâ€™s what I want to do, fill time as I want to do JRuby and Java and android and Ruby Motion. Thatâ€™s what I want to do. Iâ€™d be happy doing those technologies. Iâ€™ll do Objective-C, but Ruby Motion is just so much nicer. But the JVM, I know the JVM. I know it well. And RMI is good, donâ€™t get me wrong, but thereâ€™s something to be said for the JVM, and if I can move on to JRuby and everything works. The problem is, Iâ€™m not sure if the gems are all thread safe yet.

Mike: Probably not, but itâ€™s coming. 

Darren: I think maybe this time next year Iâ€™d say, every gem thatâ€™s in use will probably be thread safe and everythingâ€™s good to go. 

Mike: I think thereâ€™s a big push for thread safe. It seemed to be the talk of the conference â€“ being thread safe. 

Darren: Itâ€™s actually quite interesting that I heard a lot of people talking about Java. Itâ€™s very strange that Ruby people are actually talking about good things in Java. Itâ€™s normally most people leaving Java because itâ€™s so verbose and going to Ruby and Rails. 

Mike: Well, weâ€™re talking about the JVM, not Java. 

Darren: Yes, but theyâ€™re talking about the threading model, theyâ€™re talking about the JVM, theyâ€™re talking about stuff from Java, not that theyâ€™re moving to Java. They want to incorporate those bits into Ruby.

Mike: They were saying most of the upgrades or the updates to Java 7 were for the lacks of languages such as JRuby, and likewise in 8 as well. 

Darren: Yes, well the JVM is full of new languages now. Itâ€™s not Java Groovy. On a lot of the JDK and JVM stuff are to support those dynamic libraries and dynamic programming languages and stuff. Iâ€™m sorry to say that Java still does not have Lambdas. [Laughing]

Mike: Really? And thatâ€™s not going to be released the end of this year now is it?

Darren: No, itâ€™s not. Itâ€™s a bit annoying. At least the new JT double â€œEâ€� is going to be released in another month, and Iâ€™ll talk about it when it does. So the workshop was good.

Mike: The workshop was good. As I said, we couldnâ€™t do the presentation on OpenShift but he did mention the others that were coming into this. So like edging out, Heroku. Heroku now supporting JRuby. CloudBees, have you ever heard of?

Darren: Iâ€™ve heard of CloudBees, yes.

Mike: Jelastic and Amazon Elastic Beanstalk.

Darren: CloudBees used to just be a CI server they used to do, like a Jenkins. And then they moved into hosting applications as well. 

Mike: Yes. The big thing with OpenShift is Red Hat are now offering commercial support. 

Darren: Thatâ€™s good. I think I have an OpenShift book that I got from the Rails mailing list. 

Mike: Okay, some time ago. I looked at OpenShift a long time ago because it was so embryonic. I sort of left it and I thought Iâ€™d come back to it another time. But they certainly seem to be making good inroads now. Thereâ€™s a lot happening. 

Darren: Just take a break right now. Iâ€™m probably going to have to jump offline in about 10 to 15 minutes because itâ€™s getting story time for my daughter for bedtime. So if we could do this in about 10 minutes that would be great. 

Mike: I will run through it then. 

Darren: I donâ€™t mean to push you for time. 

Mike: Iâ€™ve got lots to talk about though. 

Darren: We donâ€™t have to do it all today. Lee wanted to know about the conference too. So if youâ€™ve got some really interesting stories or some that you wanted to talk about, you might say Iâ€™m just going to do the overview today and next week I might talk about a few bits more. As long as you right it down, because if itâ€™s fresh in your mind you might need to say it now. 

Mike: Well, no, because I had written everything down last night. I went through everything and wrote notes for everything. 

Darren: Perfect. 

Mike: So why donâ€™t we just go through the ones I attended. Because honestly, it was like one every 45 minutes mate. 

Darren: Okay.

Mike: Nonstop for a few days. So let me go through the ones I attended and letâ€™s say weâ€™ll talk about it next week because Iâ€™ve actually written it all up.

Darren: If you just say what they were, and then we might go into them in a little bit more detail next week. Sorry for having to run on you. I can just here Orla running around. 

Mike: No, youâ€™re fine. Donâ€™t worry.

Darren: So how was the actual conference part of it?

Mike: The conference was great. The venue, we were at a hotel north of Melbourne. The Jasper Hotel. There were 380 people that attended. 2 conference rooms so they had parallel sessions going on at any one time. To be honest, there wasnâ€™t enough room. The popular sessions you had to sit on the floor sometimes. It was a bit annoying. And the seats were not very comfortable. There was no Wi Fi and the power was appalling. 

Darren: Why was there no Wi Fi? You canâ€™t have a developer conference without decent Wi Fi. 

Mike: There was no Wi Fi, and also while you were in the conference rooms you were pretty lucky to get 3G. Depending on where you sat, you would be very lucky. So you couldnâ€™t get anything, like Twitter was out of the question in half the ones I was on, which was very annoying because itâ€™s sort of in the center of Melbourne. 

Darren: You would expect a bit better.

Mike: Youâ€™d expect a bit better yes. So Darren, in the interest of time because weâ€™ve been on for quite a while now, what I might do is just tell you the sessions I attended and then maybe next week we can talk about the in detail.

Darren: Yes, that sounds a bit better. If you just want to go through at a very high level, we might then pick one or two and then do it over the next couple just to see how much you have to say basically and how many questions I have. Because I really wanted to go and wasnâ€™t able to go so Iâ€™m interested, very interested.

Mike: Well it was my first one.

Darren: It was the first one in Australia. 

Mike: Yes, the first Ruby Conference in Australia. So it basically opened with keynotes and they closed with keynotes as well. Corey Haines, big Rubyist in the world. He just loved training and development and that kind of stuff. He opened it, very good. He went on for about an hour. The actual sessions I went to: Refactoring from Good to Great â€“ thereâ€™s no slides on this because this was actually a live coding sort of refactoring session. A guy called â€“ it was very clever, it must be said â€“ Ben Orenstein. Heâ€™d obviously practiced this many times before. 

Darren: Iâ€™d say so.

Mike: Some of the stuff that he was doing like click of the fingers and everything changed type stuff. The next one I went to was Sinatra in SIX Lines, Konstantin Haase from Munich. The only reason I went to this one was because the Conference Room B was all filled out so I wasnâ€™t going to sit on the floor. 

Darren: What was the other one you were going to go to?

Mike: I think it was Rails Real Time, which I really would have liked to see. But as it happens, Konstantinâ€™s talk was absolutely hilarious. So heâ€™s the author of lots of gems, but the ones he talks about â€“ it was all about how to do crazy stuff with Ruby. He re-wrote Sinatra in SIX Lines, called it Almost Sinatra. So it was a very funny talk and he just sort of went on and on. So it was Almost Sinatra, now he needed a bit Rack, so he wrote another gem called Almost Rack. Thereâ€™s another gem called Almost Rack Protection. And theyâ€™re all on GitHub so you can go check the out. Iâ€™ll put them in the show notes, but that was quite good. Then Millions of Apps. What Have We Learned â€“ a guy Richard Schneeman, he worked for Heroku â€“ Iâ€™ll tell you more about him later. The C word from Pat Allen. Pat Allen is a Rubyist down in Australia, very big in the community, very focused on the community.

Darren: You know something, you see that Millions of Apps?

Mike: Yes.

Darren: I think that was the same talk that was done at the YOW! Conference, the Heroku one. 

Mike: Possibly.

Darren: Anyway, sorry for interrupting. 

Mike: No thatâ€™s alright. But the conference got interrupted itself because of stuff that was going on with Heroku, so Iâ€™m limited. I canâ€™t actually remember what it was now. It escapes me. 

Darren: What was the next one you said? The C word?

Mike: The C word from Pat Allen, yes. 

Darren: I can only think of one C word and Iâ€™m trying to keep a family friendly rating. So what was that one?

Mike: Patâ€™s talk was really about his personal journey in the Ruby world and how nice people are and how weâ€™re nice in the Ruby world and how Max is nice so we are nice, that kind of stuff. It was just little stories that he told. 

Darren: So what was the C word?

Mike: I donâ€™t actually know.

Darren: That was just a tag line to get people in through the door?

Mike: The C word. I donâ€™t know actually, I canâ€™t remember. Anyway, letâ€™s move it on because I know youâ€™re strapped for time here. The next one, very, very clever one. The Setup â€“ it was Managing an Army of Laptops with Puppet. I donâ€™t know if youâ€™ve got that one in front of you. A guy called Will Farrington, heâ€™s a GitHuber â€“ there were a lot of GitHubers there by the way â€“ he was from the US, big orange beard. He spoke like a hundred miles an hour and Iâ€™m think thereâ€™s no way this guy can go on for 45 minutes but he did. And he was talking about the new product that GitHub released called Boxen. So itâ€™s GitHub.com/Boxen/Boxen. 

Darren: Whatâ€™s that?

Mike: Iâ€™ll tell you about it next week. 

Darren: Okay, fair enough. Iâ€™ll have a look at it then.

Mike: Boxen is very cool. Itâ€™s only for Mac but theyâ€™ve only just started doing it. Basically it delivers a desktop environment for the new GitHubers to join. Being developed. Okay, moving on because Iâ€™ve got quite a few. Lessons from the Masters from Geoffrey Grosenbach. I donâ€™t know if you follow PeepCode?

Darren: I know of it. I know what PeepCode is. I donâ€™t think Iâ€™ve bought anything off PeepCode.

Mike: Over the last year or something, he did some sessions, I think they called them play by play so people like Yehuda Katz and Gary Bernhardt, Zed Shaw, Jim Weirich, Aaron Patterson. Basically itâ€™s clips of the funny bits of the videos heâ€™s taken while heâ€™s been recording his shows. Itâ€™s very cool. 

Darren: I hope he puts that up. I wouldnâ€™t mind seeing that. 

Mike: Well the Gary Bernhardt one, because I donâ€™t know if youâ€™ve seen this trial software. Itâ€™s Vim stuff, itâ€™s unbelievable. 

Darren: I cancelled it. I was a paying member of Destroy All Software but I just wasnâ€™t getting to them. I think the fact I had to go to the website, I know it sounds really bad but I had to go to the website and download them. They were coming through like Ruby Tapas or Rails cast or anything, they were just coming through in an RSS feed. It makes such a big difference. 

Mike: I do actually empathize with you there because itâ€™s very annoying. And then there was a special documentary, they had flown a movie director in from the states, a guy called Kevin Triplett, who had basically done a video about Why the Lucky Stiff. You know why?

Darren: No, I donâ€™t know that. 

Mike: You donâ€™t know? Okay why, he was a very prolific Rubyist. He was a cartoonist, an artist, a programmer, and he pushed Ruby in a completely different way. He was completely infamous around the Ruby world. Disappeared off the planet in 2009, like his name, Why the Lucky Stiff. He was famous for the book I think it was Wise Poignant Guide to Ruby. 

Darren: Okay, well what about him?

Mike: So basically, Why was famous and he disappeared. So itâ€™s all about who he was and why he disappeared and that kind of stuff. Very touching. So Iâ€™ll talk more about it later. Thursday's keynote was done by Aaron Patterson. We'll go into that later. Aaron is one of the few Ruby committers and Rails committers and he talked about upcoming Rails and stuff, and the YAML thatâ€™s been in the news recently.

Darren: Did anything happen afterwards? Did you go out for beers?

Mike: On the Wednesday, because I was catching up with other folks in Melbourne because I used to work there, not really no. On Thursday I did. Thursday there was drinks after the conference.

Darren: Because I actually met with Gary Bernhardt when I went to the YOW! Conference and had a really good chat with him. I assumed with Ruby being a good community thing that there was a lot of people who went to the pub afterwards. 

Mike: Most of the people were staying in the same hotel where the conference was, and Ninefold were sponsoring drinks again so the drinks were free. 

Darren: Nice.

Mike: It was a good evening, yes.

Darren: Thatâ€™s good. So then Friday?

Mike: Friday started off with a keynote, Mike Lindsaar, heâ€™s famous for doing the very first email gem. I think it still works now. He also worked on Action Mailer. I think he is the only Australian member of the Rails committer team, I believe so. Then it was The High Performance Ruby, so that was Charles Nutter again. Basically, I probably heard most of the stuff that he presented in the workshop on Wednesday so nothing new there. Then there was the State of Ruby.

Darren: You probably should have gone to Ruby Motion on that one, isnâ€™t Ruby Motion on at the same time it looks like?

Mike: Yes it was and I was going to go there but I couldnâ€™t get a seat. To sit on the floor for 45 minutes, I was like no. I donâ€™t think so. Seriously, these conference rooms were small. So 380 people in between two of them, it was obviously the popular ones. By Friday, I was like I need a seat.

Darren: Yes, I know what you mean. You get a bit burnt out and youâ€™re just like oh screw it, Iâ€™ll go to the other one. 

Mike: Well you only have, itâ€™s not even 5 minutes between the sessions. So youâ€™re going from 9 until a quarter to 6.

Darren: So if youâ€™ve got one that goes over slightly, youâ€™ve got less chance of getting in.

Mike: Youâ€™ve got no chance of getting up to it, yes. So State of Ruby, Bob Hoskings, he was talking about MRI, Rubinius, JRuby, etc., etc., There was a lot of overlap with stuff that Charles Nutter had talked about because itâ€™s the same sort of thing. I also went to the Braintree one. I canâ€™t remember much about that because I think I sat on the floor. It was the Money High Availability at Braintree.

Darren: I remember we were talking about them in the last podcast about them finally coming to Australia.

Mike: I think they were more concentrating on why theyâ€™re keeping their service up. It was all high availability and how do they go about doing that. Adam Hawkins, he was the afternoon, Dear God What Am I Doing? Concurrency and Parallel Processing. This was a live presentation. It was his first venture into threads and fibers and processing and faulking and all that kind of stuff â€“ that was faulking by the way. He basically walked through his experience.

Darren: I do some parallelism and concurrency, and I did some super computer programming when I was at UNE with the multicourse, and itâ€™s complicated stuff. 

Mike: Itâ€™s complicated, yes. His talk was just a very high level, and it was what he did and his thought process as he went through it all. He talks about cellulite as well. He touched on that. Iâ€™ve got one more to go. Hacking with Gems, possibly the funniest one Iâ€™ve ever seen or been too in my life

Darren: Well that's the first one you mentioned to me.

Mike: Benjamin Smith, he's from Pivotal Labs. Do not try this at home.

Darren: I seen at the Ruby Meetup, that's the one they discussed.

Mike: That was it? Of course, that's the one. Yes.

Darren: I couldn't make it on Monday because I ended up getting late into work, so I had to go pick my daughter up from day care. I couldnâ€™t make it. But that was the topic. They were going over that talk

Mike: Honestly it was actually scarily simple how they did things how he hijacked gems. But he also showed you how to detect for malicious gems and stuff like that. I could talk about it again. I can show you all my notes. I couldnâ€™t actually stay for the end keynote because I had to catch a plane. 

Darren: Get a flight home. Yes, I know what you mean. It takes a while to get to the airport.

Mike: Well as it happened, I could've stayed because the plane was late for like 2 hours. 

Darren: [Laughing] Yes but if you have of stayed, you would have missed the plane. Thatâ€™s the way it goes. 

Mike: Friday night rush hour in Melbourne wasnâ€™t good. 

Darren: I used to travel in and out of Melbourne all the time, that and Sydney. I used to spend my Friday afternoons waiting for the delayed planes that always happened. 

Mike: So the conference was great. Aaron Patterson's talk he was very funny with his little digs about DHH. I can talk about it all later. 

Darren: We'll go into a bit more depth in the next one. We might just pick a couple and talk about them. 

Mike: Well pick Benjamin Smithâ€™s one because he was hilarious. Hacking with Gems was a laugh a minute. 

Darren: Thatâ€™s good. I'm glad it was good. I'll be booking myself in for next yearâ€™s, not 2014 but I will be there. 

Mike: I'm definitely going to go next year, yes. 

Darren: Sounds good. Maybe next year we might even do a podcast from down there. Weâ€™ll have to wait and see.

Mike: Well not if it's in Melbourne in the same hotel. 

Darren: [Laughing] We might be able to record it.

Mike: Yes, possibly yes.

Darren: So we can just sit in the hotel room with a couple of beers and just have a chat about the conference and just record it. But I don't think weâ€™ll be able to release it. All right, so we want to move on to picks. My picks for this show are firstly, I'm going to pick OmniGraffle. Itâ€™s a bit of software for the Mac which is the Visio equivalent. If you don't know what Visio is, then you don't need on the OminGraffle. I use it quite a lot for doing diagrams. It just looks much nicer than Visio. There are some limitations to it, importing and exporting. But I just think it's great. That's my techie pick. And my non-techie pick is Audible.com. That's the audio books site owned by Amazon. I don't have a lot of time to actually sit and read a book these days. I'm driving from work and stuff. I've started to purchase audio books. So there are a few that I have, startup books that were there, Y Combinator, Getting Stuff Done with Techstars book. In regards to start up stuff, the Launch Pad, the Y Combinator Stories by Randall Ross I've just listened to on audible. I think it was pretty good. I also listen to fiction books and stuff as well. That's my non-techie pick is audible books. I don't know if it's reading. Is it reading? Iâ€™m listening to it. 

Mike: Itâ€™s listening, yes.

Darren: And if Audible wants to sponsor us just let me know. [Laughter]  
Mike: Okay, my techie pick is TorqueBox. Iâ€™ve only played with it while I was at the conference, the JRuby. But itâ€™s very nice. I intend to spend a lot of time on that in the next week I think. 

Darren: Cool.

Mike: Other techie picks â€“ I'm going to go with Benjamin Smith's one which is the Cold-Mind-Canary gem. I hope youâ€™ve got that. Iâ€™ll put a link in the show notes.

Darren: Yes. I got it. Cold-Mind-Canary. So how does it die? That was the thing, the canary used to die from gas poisoning. 

Mike: After all the hacky gems that he had written and posted in Ruby gems apparently this is the one gem thatâ€™s is actually kosher and you can install this, and it will actually check for any weirdness going on in your gems files. So it's like a little antivirus. 

Darren: That's a good idea. 

Mike: That's quite good, yes. But we'll talk about that later. Other picks â€“ I wish I could find a roofer that would actually come around to my house. I have buckets in four rooms.

Darren: Thatâ€™s annoying.

Mike: Iâ€™m being dripped on. 

Darren: It's been a bit wet and wild in Queensland. I've discovered four lakes on my back deck. My daughter was shouting at me the other day because I put her little tricycle, itâ€™s got a little tray on the back, and one of the buckets I put it under the water. And she was going no daddy no. 

Mike: Yes, speaking of buckets, my wife is at her wits end now. It's getting fixed. 

Darren: Well, we might call that a wrap for today. 

Mike: Sounds good. 



