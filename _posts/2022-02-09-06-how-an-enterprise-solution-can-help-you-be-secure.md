---
title: 06 - How an enterprise solution can help you be secure
layout: post
type: main
description: In our first episode in English, we talked with a Solutions Architect from one of the biggest security companies in the world, Veracode. We discussed about how an enterprise tool can help developers to build secure software.
file: https://api.spreaker.com/v2/episodes/48624907/download.mp3
length: 47:27
videoid: udVCFp8L2tY
cover: "../assets/img/306.png"
---

In our first episode in English, we talked with a Solutions Architect from one of the biggest security companies in the world, Veracode. We discussed about how an enterprise tool can help developers to build secure software.

Raw Transcription

00:21.25
cassiodeveloper
Hello everyone how are you doing? It's a pleasure to start presenting our first episode in english because today you have an international guest. Actually it's our second international guest because we had in the past someone from Peru which was carolinaalina. Ah, carol. Actually we talked about container security if you could remember but today we have our first english guest. So that's why our episodes going to be in english sorry if you don't understand english it's a good opportunity to start learning but today it's the episode number 6 of devs se cops podcast which is on our um nine february and caspeator.

01:04.30
Marcos Santos
I I'm Mark sense.

01:06.50
Balbino
And I Hadri Bobbino and.

01:08.13
cassiodeveloper
All some awesome accent. Also awesome accent of rouddrigo. Perfect Perfect hadrig today. You're going to talk about an ni Enterprise solution special for helping developers to develop more.

01:11.53
Balbino
I.

01:27.70
cassiodeveloper
Ah, secure code. Let's see or develop securely if I can see if I can talk like that and for that we have um how how can I classify this guest. He is an amazing guy which is has some understanding of Portuguese I know he know how to say Kypiina for example and he.

01:42.41
Jonathan Davis
In your following pocal homebocal. Ah.

01:46.32
cassiodeveloper
Yeah, you see you see you see and he will introduce himself now guys. Welcome Junaam thank you for your time. Thank you for how to say be able to join us and to discuss a bit to help our listeners who understand about an enterprise two enterprise solution also to understand the importance of. Having secure tools during the development during the the pipeline and everything. So again, welcome and thank you please introduce yourself a bit.

02:10.91
Jonathan Davis
Yeah, yeah, absolutely thanks. Cassio. Um, yeah, so I'm Jonathan Davis and I'm a solutions architect at vera code and so really I help um a lot of the salespeople but on the technical side so I help give demos of the solution answer questions about the solution. And I also help ah in the poc process and things like that. Um, so definitely really excited to talk with cassio and the team here about how developers can use these tools to write more secure code.

02:41.80
cassiodeveloper
This very good Marcus as you can see. He's doing the same job as you are at novi 8 doing pocs performing demos and of course as we have. Some stupid questions or some customers or ah, something like how can I run my cli or how how is the best moment to ah how to say implement the enterprise tool from open overop open source tool or something like this.

02:55.85
Marcos Santos
I Oh my gods.

03:12.13
cassiodeveloper
How you feel having a good partner today here with us Marcus I'm talking to you.

03:16.10
Marcos Santos
I no no okay, okay um when moving them music. Okay further I'm pretty good in working with fee you and no digging off 8 and then the job is a good. I like the the customers have so many questions stupid and ah should yesterday the customer make me a question. Ah and well what which is better.

03:46.00
cassiodeveloper
H.

03:53.00
Marcos Santos
Ah, sash or dust No no, but it is is a different tools. Ah not show the better one for other is that complimentos. Yeah, okay.

03:53.87
cassiodeveloper
Good question, Good question to restart.

04:03.21
Jonathan Davis
Yeah, it yeah I think that's a good question so it's not that um one tool is better or 1 type of testing is better. It's that you have different types of testing for different use cases.

04:04.70
cassiodeveloper
Um, there are different levels.

04:18.20
Jonathan Davis
Um, so one of the things we do at vera code is we offer a lot of different testing types. So we have sast or static analysis to analyze like your first -party code we have se to analyze any third party libraries you're pulling in because especially today in modern software. Ah, big portion of the application is going to be using these third party libraries and we want to make sure that's secure. We also have dynamic analysis testing and so dynamic analysis testing will help us find vulnerabilities in running web applications and so if you're just looking at the code you might not find certain issues that show up. Um, at runtime things like server configuration issues and so we can find those with dynamic analysis and then we also have manual penetration testing and so manual penetration testing is we'll actually have human beings test this application and kind of act like a ah red team. Um, to find vulnerabilities that no automated tool can find things like business logic issues. For example.

05:20.56
cassiodeveloper
Um, um Jonathan this manual testing. Can we call it as pen test. It's something like this good. We I worked with faira code in 2011 or 12 something like this.

05:25.52
Jonathan Davis
Yeah, yeah, absolutely yeah, a mainop penetration testing.

05:37.60
cassiodeveloper
In a company in Brazil called sarazaper really nice group. Really big group and really nice company to work in and back then they were using this 3 options as you mentioned sast for analyzing our search code bat as dynamic testing and also this menual testing. When we called some architecture or some some guy. Let's say some cons consumering to help those with this manual test and I have a question in addition, what Marcos mentioned. Um, how can how do how you approach customers to explain Dane. Okay guys you don't need. It's not about being better or asked or dust.

05:59.40
Jonathan Davis
Ah.

06:13.57
Jonathan Davis
Yeah.

06:15.68
cassiodeveloper
You have you have to have you need to have these levels of protection how you approach them how you approach the customers.

06:18.44
Jonathan Davis
Right? right? Well one of the things we have is we have some helpful information on our website that we can share with customers and so one of the things that we share is the different types of flaws in which type of testing uncovers which flaw.

06:35.11
cassiodeveloper
Um, he.

06:37.80
Jonathan Davis
And so when you're looking at that list. You can see that there are flaws that you can only find with static analysis and then there are flaws that you can only find with dynamic and so it makes sense to use multiple types of testing to make sure that you're uncovering everything.

06:48.84
cassiodeveloper
Okay, perfect hodrigo question for you to let's let's start using this perfect English a.

06:54.74
Balbino
My anger First it all, it's I warning my english ah working brox and I I like to compare it to with Cassia's face is that terrible. So sorry about this.

07:00.13
Marcos Santos
And the put particular English is.

07:07.75
cassiodeveloper
Um, yes, it's a term but it's working progress as I know I have a question I have a question for you just just a question just just a moment how you approach the customers because Junita said okay, it's nice to have this.

07:11.57
Jonathan Davis
So.

07:12.53
Balbino
And it's so working progress and ah okay, okay.

07:27.71
cassiodeveloper
With a tool. You can find some flaws with another two. You can find different type of flows. Ah you use the same speech for customers in Brazil or you have some addition or some another information like guys you don't need these or that you need both of them.

07:40.55
Balbino
Yeah I like to to say about Mara about the process I want to understand how how the process the the user and cu stay usually and I i. See how the gaps in in this process and after all I see how the gapy a not just suggesting how to to and have to use. yeah yeah now I

08:00.11
cassiodeveloper
Okay.

08:08.32
cassiodeveloper
Few these gaps. Okay, okay, perfect. Perfect now you can make our question I feel for yeah, awesome.

08:09.74
Jonathan Davis
No, that makes sense.

08:17.13
Balbino
I Forget that but I remember I remember but what are the biggest challenges selling security for for. Yeah.

08:20.14
Marcos Santos
I.

08:25.94
Jonathan Davis
Ah, the biggest the biggest challenge I think it's just um education in general you know talking to people about the different testing types and why they need them because a lot of times you know we're working with customers who are just getting started in their security program and so we want to help educate them. Um, and make sure that they understand all the different options available to them so that they can identify which gaps and and which ones are most needed.

08:53.55
cassiodeveloper
It's a good question because for example from security perspective and I am ah this really security guy. Let's say so when customers ask me what kind of testing I need to have in my pipeline I say all the kinds all kinds of testing that as you can pay or as you can implement. Because we have open source enterprise and everything. But of course it's hard to to have this approach because it's Sas dust sas das a ca I asked sometimes ah manuual pin testing I iac see infrastructure as code for example, containers server. So it's a lot.

09:26.93
Jonathan Davis
It is a lot.

09:28.32
cassiodeveloper
Of ah different tests and different tools and sometimes it's hard to customers decide what to do? So my how to say my speech for them is at least you need to have se and sast because with both of them. You're going to be how to say 100 % covert on testing your code. So everything you produce as as software which is your code. Basically it's rub be covered as you mentioned ah jonathanam a lot of modern softwares. They are using a lot of third -part softwares. Ah which is libraries and everything and we have some numbers against this is seventh.

09:47.39
Jonathan Davis
The.

09:58.43
Jonathan Davis
Er.

10:05.20
cassiodeveloper
Almost 70% of a software is composed by 30 power libraries. So only only 30% is your own code. Let's see let's say with this this 2 combination sast an se. It's a good approach to start.

10:08.24
Jonathan Davis
Oh.

10:20.69
cassiodeveloper
Ah, doing appsac. Let's say application secret. Do you agree or have another opinion.

10:21.29
Jonathan Davis
Yeah, yeah I know I agree with that. Um, like you said it's good to just start testing kind of your code, especially if you're thinking about it from a developer and then you can kind of progress to some of the other types of testing. So I think that makes sense another thing that we do. Ah, to help Developers is we allow them to integrate this product and so they can integrate it for example into ides that they're using and so if developers are using ides like visual Studio Visual Studio code Inteja while um while they're writing code. They can also be performing a security scan.

10:44.96
cassiodeveloper
Um.

10:56.74
cassiodeveloper
On 1

10:58.34
Jonathan Davis
Of that code and so that makes a lot easier for the developers because they don't have to necessarily log into our platform to kick off these scans and see the results they can do it right? as they're working and it's also going to make their life better because they're going to be finding these issues as they code. Instead of waiting until the end of a release right? because you don't want to be at the end of release on a Friday and then you find out you have you know 15 high severity issues that you need to fix right? and so it's better if you can find these things as you go.

11:23.66
cassiodeveloper
Um, yeah I think I think this kind of integrations is the I don't know this word in English but it's a start of state of art in pushing left because it's oh.

11:35.69
Jonathan Davis
Yeah, absolutely.

11:40.20
cassiodeveloper
Ah, all foodability in softwareer is about coding So the let's say the vulnerability is boring on the time and you already performed this kind of Scan and you already blocking this vulnerability into born even to Rise and let's say I think it's the best approach of pushing life. You know.

11:55.90
Jonathan Davis
Yeah, absolutely and you know pushing left can be a gradual process too. So a lot of customers get intimidated right because they're like okay you have this product and you have all these different integrations and so we're going to have to set up everything at once but you can take a gradual approach. And so sometimes customers will start and when they start they're only doing scans in the verico platform and then maybe after that they'll shift to the kind of the cicd and every time a build happens like in Jenkins. For example, you're performing scans as well and then you can do things like fail a job.

12:28.81
cassiodeveloper
Moha.

12:33.39
Jonathan Davis
If you find high severity issues and then after that you can shift left even further like you said ah to kind of the the um furthest left you can go and actually do those scans in the ide itself that developers are catching those issues and so you know one thing that we talk to customers about.

12:33.42
cassiodeveloper
Um, ah.

12:51.39
Jonathan Davis
Is that it it doesn't have to be something that you do immediately overnight. It can be a process of of ah implementing security.

12:55.75
cassiodeveloper
Yeah, perfect perfect hodri. We were inside to say something.

12:57.30
Balbino
Know when yeah when you use this did use this approach in shipshi left he you turn on the lights and the the head of dev about the security and he he see it but 10 with. I don't know how how do this but and was it a Legalga Louis do dos da pray Saint Proof Cap son win ziov we made to maybe.

13:19.70
cassiodeveloper
Satan portuguese.

13:21.55
Jonathan Davis
Um, favorite of agy.

13:25.30
cassiodeveloper
Now you give you let's say you give ah you give a hint for a dev to start ah thinking about security at first let's say cool cool.

13:31.24
Balbino
Yeah, yeah.

13:33.20
Jonathan Davis
Yeah, absolutely absolutely I completely agree in the developers they're they're going to be happiest. Um, you know when they can see the results in the ide but you might not get to that state immediately.

13:45.42
cassiodeveloper
Perfect. It's perfect. Ah Marcos you haven't any question in your hands to to rise up or not perfect. Marco's just ah, he just wake up. He still need to know get.

13:52.52
Marcos Santos
In this moment now I think no no is not a brother who.

13:55.69
Balbino
Up. And the brisk.

14:01.76
Jonathan Davis
Yeah, and you know another thing too since we're talking about how to help developers up to this point we've talked about the different types of testing you can do right? We talked about Sas se das but then the other side of the equation is like how can we help educate developers.

14:04.40
cassiodeveloper
That sign.

14:09.30
Marcos Santos
You.

14:19.86
Jonathan Davis
So they're writing more secure code because that's going to make your life easier because if all you're doing is testing for flaws and then fixing them. You're kind of playing a game of whack-a-mole I don't know if if yeah, okay, so yeah, um, you you want to make sure that you're actually introducing less flaws to begin with. And so that's where secure code training comes into play and one of the the neat things about what we do for secure code trading at um vera code is that what we don't just rely on videos and so you know a lot of vendors will just show the developer video and then give them a quiz at the end. But that's not really helping the knowledge stick and so we actually have interactive training and so like let's say you're learning about sql injection. For example, we have these security labs which are hands-on and so you can go into a course on Sql injection will actually spin up a web application for you. Ah, that has sql injection flaws and so then you would get experience. Um, first of all practicing hacking those flaws so you'd actually be able to um, hack a live web app and then we actually give you the the code for that web application. So you can go in and rewrite those sql queries. So that it's no longer vulnerable to sql injection and so the developers get hands-on experience. Um exploiting and fixing these things and so that that's definitely also helps companies to integrate security because as the developers become more knowledgeable about secure code. It's going to be a lot easier for you to um. To fix flaws in the future and you're gonna have less flaws to fix.

15:53.75
cassiodeveloper
I think I think this is okay, okay going gone. Oh my God I think this is the how to say main pointing all software security because.

15:55.53
Marcos Santos
What's good good Another No no go I ask ask after.

16:12.75
cassiodeveloper
When you talk about this testing and Saas and dust and penetration testing all kind of security tests is about to find problems and that's I'd say that's a step on your process that you must have you need to find for problems all the time but you need to stop creating problems.

16:12.92
Jonathan Davis
But.

16:19.22
Jonathan Davis
Um, exactly.

16:28.80
Jonathan Davis
Exactly.

16:30.74
cassiodeveloper
You stop? You need to stop creating bugs and vulnerabilities and that's as you said this kind of 2 comes up because um, if you don't come to the developer. Okay, guy. Okay, my dev guy here's a se injection or carite descripting or whatever hipy inspection or whatever and. You need to fix this way. Okay, he will fix but tomorrow he will produce New Vulnerability If You don't if he don't understand how to stop building code like that as I as I call as defensive programming. It's kind of like like this you need to stop creating vulnerabilities and for this.

16:49.73
Jonathan Davis
Um, exactly.

17:07.90
cassiodeveloper
This kind of tools as security labs as Jonita mentioned it's the best approach to help the developer of your course. Of course you have another tools and another approach ah to help other kind of people in this process as system analysis or actetss or even devops guys or even business guys. Yeah, end the end users.

17:21.20
Jonathan Davis
Oma the.

17:27.88
cassiodeveloper
But for the developer I think is the best ah way to educate you know? Okay, guys here is how you stop coding shit as hodrigo was doing the past keyword.

17:31.30
Jonathan Davis
Yeah.

17:36.66
Balbino
Yeah, we talk about this in never episode and this this creature is gay old just keep that keyword keyword. Yeah.

17:36.82
Marcos Santos
To Ziga. Ah.

17:37.74
Jonathan Davis
Ah.

17:44.40
Jonathan Davis
Yeah, exactly yeah and another thing too is that um you know when we talk about helping the developer. We also have services in place and so you know one of the questions that some developers might have is well. Why should I even go with a tool like Vera code.

17:47.32
Marcos Santos
Not any.

18:02.67
Jonathan Davis
If there are free tools available and there are a lot of reasons but 1 of the benefits is all the services and support that you get so we actually have a team of people they're called the application security consultants and they were developers in the past. So they have a lot of development knowledge and experience. But they also have a lot of security knowledge. And um, ah, developers and security team members can actually book a call with one of these appset consultants. Ah to ask them questions about the vulnerabilities that they found and how to fix them so you can actually ask your questions to a live expert who can help resolve any doubts that you're having. And help guide you in the best ways to fix these issues and so you do get a lot of services and support in addition to ah, the tools that we're giving you.

18:48.49
cassiodeveloper
I This is this was supposed to be my next question and it will still be but no, this does talk a comment on this when when it comes to saast solution. For example, when you talk about new companies startups and new business. They have a lot of different language.

18:52.12
Jonathan Davis
Da.

19:05.58
Jonathan Davis
The.

19:07.26
cassiodeveloper
I have customers that they have go c sharp java javascript python and some kind. Yeah, some guys is even using cloure. Okay, so it's 7 six seven different language and when we talk you about 1 specific language maybe open source will help you. But.

19:10.14
Jonathan Davis
The. A a.

19:24.86
cassiodeveloper
On these enterprise companies. They have a lot of different language and that's why you need enterprise solution to have this kind of support otherwise you're going to have 6 different tools just for doing sust for each language your code so doesn't make sense. But ah maybe it's a trick question janita I'm sorry.

19:24.89
Jonathan Davis
Maha.

19:29.70
Jonathan Davis
Go ahead.

19:34.60
Jonathan Davis
Exactly.

19:41.64
Jonathan Davis
Ah, ah.

19:43.51
cassiodeveloper
Ah, but when when it comes to ca and I know enterprise solutions I know also opense solutions. What is exactly the difference between open and enterprise because ca you just go to Cv database and get if there is there. You know something like this.

19:50.32
Jonathan Davis
Yeah.

19:58.14
Jonathan Davis
I'm I'm glad you asked me this question. Okay, so actually we have a different approach to se so we do use the national vulnerability database as a starting point. But the the limitation of using just a national vulnerability database is that it's a claims based organization. And so what that means is that somebody you know like a software developer has to actually submit a flaw or a vulnerability ah to the national vulnerability database then it goes into their backlog and then they'll eventually publish it. But what we do is first of all, we do a lot of our own research. And so we're using like machine learning in ai um to monitor popular third -party repos on places like github in order to find issues as they're raised before they're even reported to the national vulnerability database and then we also have a team of researchers who can dig deeper as well. Um, and in kind of a manual way. So we have a lot of our own research that we've done and as a result kind of the total ah surface area of vulnerabilities that we can find in se is going to be about two and a half times the size of a vendor that is just relying on the national vulnerability database.

21:08.73
cassiodeveloper
You have perfect now makes sense why you pay why you pay for a ca if you have free solutions which can do something like the same but not for example in case of last last biggest case was log for a J problem.

21:11.38
Jonathan Davis
Um, yeah.

21:17.15
Jonathan Davis
Exactly.

21:22.98
Jonathan Davis
A.

21:24.98
cassiodeveloper
And maybe these enterprise solutions on the same day they were already aware of this and publish and doing scans and maybe some open source could take one day more let's say if it one day more or even more and this from the security perspective is being vulnerable being exposed one day 1 hour more can.

21:35.65
Jonathan Davis
E.

21:44.70
cassiodeveloper
Cost your company's life. Let's say it's big risk big risk to take right.

21:44.45
Jonathan Davis
Yeah, yeah, exactly yeah and in fact, there was um, another issue too and it wasn't as big as the law for j issue but there was an issue with I think the ua parser javascript library which is a really popular library that a lot of big companies are using. Ah, and so what happened was actually um, an attacker compromised the count of the npm account of the developer who develops this library which is downloaded millions of times and this attacker was but able to inject malicious code so that every time you download it. You're downloading. Um, this malicious code issue. Um, and so um, almost as soon as that issue was raised. We were able to update our database and notify all of our customers about this problem and so that's one of the benefits that you're getting as you mentioned is just the speed of updates that we can provide about ah vulnerable Third party libraries.

22:38.76
cassiodeveloper
Perfect perfect Marcos you are shy today. What's the problem because of the english.

22:43.15
Marcos Santos
No no, oh no, no, it's not a problem but I have a question but you cut me some minutes ago. No no. But I have a new question. Um.

22:52.22
cassiodeveloper
Okay, I'm so I'm sorry I'm sorry I'm I'm excited. Okay.

22:59.39
Marcos Santos
What the biggest challenger you find the in the customers Jonathan and is an implementmate Ccd is integrations education was the biggest challenge.

23:03.33
Jonathan Davis
Yeah I think that.

23:09.84
Jonathan Davis
yeah yeah I think that it's a couple things education as you mentioned making sure that they know about all the different testing types available to them and why they should use different testing types. Um, and then the implementation can also be a challenge. And so that's why we recommend doing the implementation in phases and so one of the things we really like to emphasize the customers is you don't have to do everything at once you can take um, a crawl walk and run approach and so in the beginning you know, maybe all you do is you just upload your code into the veraco platform. You know once every week and you scan it and then after that maybe you move over to Jenkins and so that every time a jenkins build happens. You're scanning code there. But maybe you don't even fail that build immediately if you find issues because then the developers are going to get and get angry right? because you're blocking their code from going. Cassia understands. He was a developer and so then ah so and so so maybe you wait until the developers get used to having these code scans before you'll fail a bill if you find any high severity issues and then after that maybe you shift into the ide. So that developers can see these issues as they're coding.

24:05.55
cassiodeveloper
Yes, yes.

24:06.52
Marcos Santos
I.

24:24.40
Jonathan Davis
Um, but it's it's a gradual process.

24:25.51
Balbino
Use the drug geno approach enough. Yeah.

24:26.74
Marcos Santos
I Yeah a gay my god.

24:29.50
Jonathan Davis
Ah, but but we saw we're selling good things though. Ah.

24:34.21
cassiodeveloper
Ah, perfect, perfect comment hadri drug dealer. You give a b to be then you start rising this truth perfect perfect okay question answered Marcucos Are you happy now. Good good.

24:39.34
Jonathan Davis
Ah.

24:45.68
Marcos Santos
Ah, good. Yeah as I'm happy ah have good.

24:48.75
Jonathan Davis
Awesome.

24:51.87
cassiodeveloper
Butrigo any questions to arise I have a lot you know, okay, 1 1 more question Jonathan ah when you when you were talking about ah saas for sorry saas stat analysis.

24:52.22
Balbino
Ah, no, no, no I don't have.

24:55.37
Marcos Santos
Um, the the.

25:02.69
Jonathan Davis
Ah, ah.

25:07.37
cassiodeveloper
Ah, how Vera code approach. It's ah ah, software as a service solution or its On-premise solution If it's both what what customers prefer it's size Cloud or how it is.

25:11.19
Jonathan Davis
Yeah. Yeah, yeah, I'm glad you asked this question so we're um, a hundred percent um cloud solution so a hundred percent saas and that gives us some benefits and so one benefit is that you don't have to worry about scalability and so if you're using an on-premise solution. And you have a lot of applications that you want to scan you have to make sure that you have enough virtual machines and and resources and infrastructure to support all the scans that you want to do um but because we're a cloud solution built on top of Aws you don't have to worry about these kinds of issues and will scale with you as you're scanning more applications. Um, another benefit that we get by being a saas solution is we have all of this knowledge. Um, you know which customers have shared with us by using the platform for over fifteen years now and so whenever customers fix an issue or whenever they market you know as a false positive that's data. And our team is able to use to make the tools smarter and so over time you know our tools have gotten smarter. We've really cut down the number of false positives we have ah that false positive rate is only around 1% now across all the different applications that we're scanning. In in so there there are definitely a lot of benefits to being ah ah a cloud provider.

26:32.40
cassiodeveloper
So this is a good ah good point. Good topic because I've tested some other solutions in the past and then the percentage of false positives in CPlus plus for example was 30% but of course other language like Java or c sharp was 1% and two percent which is.

26:34.61
Marcos Santos
And.

26:43.52
Jonathan Davis
Okay, 5

26:45.46
Marcos Santos
This is a w high.

26:51.89
cassiodeveloper
Really good. But anyway for c and c plus plus 30% it's really much and if you start let's say we get a company to start security and they start doing scans and they started having 30% of their scans has fucking ah false positives.

27:03.40
Jonathan Davis
Right? right? right? exactly.

27:09.43
cassiodeveloper
The developers. Okay, you give me problem to fix but it's not a problem. You're given another problem's not a problem then this is even worse for as Roudderrigo was mentioned before to focus on process and gaps and this is even worse because developers they are and untouchable. Don't touch me let me program.

27:22.78
Jonathan Davis
Yeah, yeah, yeah, ah.

27:26.89
cassiodeveloper
They are this this these superhero guys and they are not actually because they are building the view, not Abilities developers if you are listen to me, you are building the view abilities. It's your fault. Okay, it's not ours for anyway, it's this approach is not good for the process or for the future mindset. But how to say as you said it need to be.

27:30.60
Balbino
Um.

27:36.53
Marcos Santos
Oh.

27:45.76
Jonathan Davis
Yeah, exactly yeah and like you said it's so important to have that trust with the development team because you know security and development need to be able to work together and so yeah, that's one of the things that we want to do is we want to break down that barrier.

27:46.46
cassiodeveloper
Step by step first step first to to have this future implemented. Yeah.

28:03.33
Jonathan Davis
And one of the ways you you break that barrier is as you mentioned having a low false positive rate right? So so developers realize oh when the security guys give me an issue. It's a real issue right? I actually need to. It's actually something I need to fix and they're not just going to send me on um, kind of ah a wild goose chase.

28:06.80
cassiodeveloper
Um, no. Yeah.

28:17.97
cassiodeveloper
Yeah, and ah, in addition, guys talking to about this I'm trying to get a new guest here for next episodes to talk about a dynamic solution which use. Ai andfient intelligence and everything to rise and new vulnerabilities with 0 false positives. Let's see if you can have this talk of these guys from Israel. Let's see if they are coming up or not if not that's fine if yes, that's fine, the same nothing in changing our lives. Let's move on Rodrigo has. Something new to talk or something.

28:51.56
Balbino
Now I'm using head percent my brain to understand the conversation. So I don't have time I don't have time to think about the question.

28:52.47
Marcos Santos
Never that ah that but ah I have a question but I have a question to make in about the.

28:56.86
Jonathan Davis
Ah, you know you know? um, um, ah yeah.

28:57.51
cassiodeveloper
To Understand english. Ah, awesome.

29:12.40
Marcos Santos
Um, the solution is is Onpremise Ceo O Se Um, ah yeah, is there any difference and in the solution on Premisecy on the Cloud services in.

29:16.13
Jonathan Davis
E.

29:26.61
Jonathan Davis
Oh.

29:29.95
Marcos Santos
Ah, in in terms of functionalities. You have yeah you have more false perceive 1 on other we have him functions in so in clouds you don't have onpremise you have been. Yeah.

29:32.15
cassiodeveloper
Um, functionalities. Okay.

29:36.81
Jonathan Davis
Yeah, yeah.

29:44.24
Jonathan Davis
Yeah, so so we're we're a hundred percent cloud and so every every scan um that a customer does with us. Ah, they'll be doing within vera codes cloud.

29:48.90
Marcos Santos
Okay.

29:57.90
cassiodeveloper
You So there is no difference because you don't have on-prems. Yeah, that's it. Okay, okay, um I have.

29:58.65
Marcos Santos
So yeah.

30:03.23
Balbino
Um, if if you if you haven't listened the the gas if you don't have this this slide on it. But.

30:08.73
cassiodeveloper
Ah, don't make this question and it it's fine. It's fine because our listeners is gonna need is gonna um, start to proving English start to listen also in English when your talk and the most important guys.

30:10.82
Marcos Santos
Oh my. Glad.

30:12.37
Jonathan Davis
Um, no, no, it's fine. It's fine I understand.

30:21.69
Jonathan Davis
Ah, yeah.

30:27.18
cassiodeveloper
It's not about to be native or have 100% clear English It's about communication we can communicate we can understand each other even the guys who can't speak good but they can understand and that's is all about anyway when you talk about even security or developing or anything and it's big approaching braue that. People need to start learning English They you are already programming in English There is no Portuguese program language you are already using English you are already using every day you already play video games. So Why not talk? Why not listen why not to improve or even produce content and everything. So. We want also to encourage people our listeners our community to Pursue English because it's not that hard. You know we have contact with English since we were born on video games and everything. So. It's not that hard. Okay, yeah.

31:15.10
Jonathan Davis
Yeah, absolutely and I'll keep improving my portuguese and maybe in six months we can. We can do this again in portuguese.

31:21.54
Marcos Santos
No any and and using just moment and can you have and some com communication problems with the Brazilian guys because our English sub terrible end up particular the english.

31:22.90
cassiodeveloper
Yeah I'm um.

31:36.33
Jonathan Davis
No, no, no I've been able to I think get all my points across and understand everybody here as well. So.

31:41.40
Marcos Santos
And ah ah was good.

31:43.91
cassiodeveloper
Yes, and and for this episode we're gonna test this first transcription. So maybe we're gonna have all these lyrics how to say transcripted in english so you can copy and paste and translate in Google so you understand anyway.

31:49.50
Marcos Santos
Um, will yeah.

31:54.30
Jonathan Davis
Ah, but.

32:01.46
cassiodeveloper
It's not a reason to not listen to this episode. But anyway you have how many 70 episodes on first and second season so you have a lot of episodes in Portuguese with Marcos Jokes and everything so you can come back there and listen to all of them hadri you were moving. You want to say something.

32:06.61
Marcos Santos
Well yeah, but.

32:17.33
Balbino
No I'm just listening I'm just listening I for not yeah, don't.

32:21.29
cassiodeveloper
Um, you like music my brain to translate so don't bother me. Ah no I have I have a new question for Jonathan ah, do you have some how to say ah conflict not you I mean in process.

32:21.40
Marcos Santos
Um, yeah, yeah, let's go do yeah.

32:24.90
Jonathan Davis
Ah. Yeah, fully.

32:39.87
cassiodeveloper
Some conflicts between developers and security when you rise some vulnerability for them and they are no. It's false positive. Oh it's not a problem. Oh this is actually easy. It is a vulnerability but I have phyro I have web Application fighter I have something in something and some to protect me but because they don't want to fix this.

32:51.34
Jonathan Davis
Ah, ah, ah yeah.

32:57.67
cassiodeveloper
They want to avoid more job. That's the thing we have this problem with impressive you a lot of guys does this and we say okay guys you need to fix this because if a hacker comes over your web application fire comes over your network over you all all over your other controls.

33:12.40
Jonathan Davis
Per her.

33:14.00
cassiodeveloper
U Two will come to your application so you need to fix this Anyway, you have this kind of conflict.

33:17.81
Jonathan Davis
Yeah, you know, um, we do and we have a couple different ways to kind of help customers and so one of the things that we do is that we give the customers a choice and so when we report flaws in the platform. Ah you know we expect you to fix the code but you have the option. Um, to market as mitigated in the platform and so for exactly the reasons you mentioned I could market it as mitigated because I have a firewall or because of some other control that I have in place. Um, which I believe would prevent that from being exploited and somebody on the team has ah who has a mitigation Approver role. Ah, can then accept or reject that request and so you know as as a security person. Maybe as a developer I can potentially go in I can market as mitigated I can leave a note explaining why I don't think we should have to fix it and then the person who's in charge of that program could choose to accept that. Ah, and so that's that's one solution and then the other thing ah kind of goes back to the app set consultants and so the good thing is that you have these services people like the application security consultants who can speak the same language as the developers and so if the developers um are Doubting. You know the security people. Can bring in an app set consultant who can explain in a lot more technical detail. Why this flaw is truly going to be exploitable Why it's an issue they should fix in code and and so you have some options you can fix things in a platform or you can. Um, consult with experts If if you want to go deeper with the developer.

34:50.21
cassiodeveloper
Good, very good. This is very good actually okay Marcos give us some message you can do it in Portuguese because you didn't record it yet. So that's fine hey.

34:52.65
Marcos Santos
Me.

35:01.63
Marcos Santos
Okay, okay oh this all but life foral teation but the Ferma geology proof of work on Comemi gear says then ba education with ah Gm na aul to oji lakes. Ok go get you ven to.

35:07.51
cassiodeveloper
Have it.

35:21.79
Marcos Santos
Comar li and buttojilaka a per da paa misaid ta me come again. Well I know so scoge while I log to sco will chi inu cananala da seoso kesh in Tele Mu Canodo cast offaor it. It. The seji vgani forma is being withist. Ita Sameco can even 1 by say pisar you doesn't taste the cheese and o any quack from Aiey Vera you have been portent by and they grab bating stomachmiing us. Ah.

35:50.29
cassiodeveloper
Ah, you see do not understand everything in portuguese. But if if someone is listeners and don't understand Portuguese that's fine. We are asking for likes and money so you can send us money as our donation because we we need to rise this podcast over the world. So.

35:50.74
Jonathan Davis
Exacta Menchi ah

35:58.90
Marcos Santos
Yeah, yeah, rags.

36:00.86
Jonathan Davis
Ah.

36:00.97
Balbino
Ah. Like Sheri money.

36:08.74
cassiodeveloper
Can help us anyway like sharing money that's actually it's followers I learned that in life. It's all about followers I want followers. That's it follow me guys. Follow me and I will be happy.

36:15.82
Jonathan Davis
Yeah, get your harvest right? because that follower that followers a repeat viewer right.

36:17.32
Marcos Santos
Yeah, follow follow classes or is a run that a developer. Yeah.

36:22.75
cassiodeveloper
Yes, because do you remember then I don't know if you watched black mirror but there is this episode of they don't have money. It's just about stars 5 stars 3 stars or something. Yeah, it's it's all about this so I need to be 5 stars and that's it guys like and share and everything.

36:23.46
Balbino
Matt.

36:32.21
Jonathan Davis
Yeah I did see that yeah yo yep Ah ah ah.

36:37.31
Balbino
1

36:39.56
Marcos Santos
Earth. Must.

36:41.78
cassiodeveloper
And do be fine Jonathan do you have any? How actually how can you talk about more of integrations. It's just about a cicd as said id or you have some other kind of Apis or jira to help with vulnerability management. How is this.

36:48.31
Jonathan Davis
Yeah.

36:59.40
Jonathan Davis
Yeah, yeah, um, a great question. So ah, like you mentioned we do have an Api and so in addition to um, the integrations that we have with cicd tools and ides you can call our api directly also as you mentioned we have um, an integration with ticketing systems like Jira.

37:00.37
cassiodeveloper
Integrations.

37:17.86
Jonathan Davis
Um, as well as um, azure devops ah azure devops issues and so you can for example with our Jira plugin you can pull in issues from vera code ah into your Jira and then you can assign those issues to different developers and and team members there. Um, and so we do try to have a lot of integrations so that this tool will fit with a lot of the other things that you already have as part of your process.

37:44.37
cassiodeveloper
I that's great. Ah I think yesterday yesterday. No last Friday I raised a video on Youtube talking about next gen security and I was talking about something about okay imagine you could automate your mitigations like.

37:45.28
Marcos Santos
Great.

38:00.53
Jonathan Davis
Yeah, yeah.

38:02.75
cassiodeveloper
You run a sastscan and you found okay Sql injections. But you're going to take one month to fix this but you need to release tomorrow into production. So imagine if you could take these vulnerabilities and automatically rise some rule in your web application fire. Ah, fireroll or even rise any rule on your api gateway. You know some kind of automation mitigations based on this vulnerability its findings from saas from sa whatever in order to anticipate this fixing because it can take longer time but I was talking about kind of.

38:22.86
Jonathan Davis
The.

38:34.45
Jonathan Davis
Ah.

38:40.16
cassiodeveloper
Nextxiani security as I called but it's all about Apis if some tools don't offer Apis You won't be able to do this or you're gonna have to run hodrigo' is gonna remember this because we worker together in a company we were using how to eat remember this fucking robot.

38:42.29
Jonathan Davis
The.

38:56.60
Balbino
Yeah.

38:57.30
cassiodeveloper
Out to it. It was clicking you clicking on your screen and everything it it was there. It can do everything but it's terrible to program on this and if you have Apis is much easier doing python or something right.

39:02.85
Jonathan Davis
Oh.

39:07.20
Balbino
Um, yeah, includes this this this robot saving about 10000000 of of year for that. Ah yeah, yeah.

39:15.98
cassiodeveloper
A year of this company. Yeah because because ah just to clarify this robots was it was open in spreadsheet and take some values and go to some websites to input these values and clicking a button because this website didn't provide Apis.

39:16.98
Jonathan Davis
Oh interesting.

39:24.48
Jonathan Davis
Ah, ah.

39:35.14
cassiodeveloper
So this this process was you ref foundund. It was a refund process. All this spreadsheet was refund for the company. So only these robots as hodrigo mentioned was saving for the actually was getting back for the company 10000000 reis annually so

39:35.19
Jonathan Davis
Huh. E.

39:51.84
cassiodeveloper
Just to have an idea how automation has power in our life today and when you talk about automation and everything it's the key to have an Api and why I'm talking about this deeply because a lot actually most of the open source tools. They don't have Apis They do they can do good jobs.

39:54.69
Jonathan Davis
Yeah, fully.

40:10.96
cassiodeveloper
They can do good scans and everything as I am oasp has a lot of really good projects and and so on but some don't offer apis. So maybe you have a mature level of security that you need to do something extra and without Apis you We were not able to do this.

40:23.30
Jonathan Davis
Exactly yeah, a hundred percent degree automation as you mentioned is really important and help save time and money and so that that's also one of the reasons why we have so many different ways to automate the tool.

40:37.48
cassiodeveloper
Yeah, awesome. Go Rodrigo you are muty and amuty.

40:42.17
Balbino
And had talk. Ah okay, talk about the the material level. Do you have and some some approach you follow your customer to and to increase the the material level in Inapp sense. Yeah.

40:56.97
Jonathan Davis
Yeah, so so yeah, absolutely so another thing that we have um is we have analytics and we have a lot of different analytics to help the customer understand you know, kind of where they are in application security right? It's it's like any other goal you'd set right? like so if you set a goal. Um, that you know this year um you want to become you know more fit right? Well then you're going to record what you're eating. You're going to record. Um you know how many calories you know how many miles you're walking or running and it's important to record these things and and also your progress and fitness right. So that you can make sure that you're actually moving towards the goal and it's the same thing with application security you want to have a lot of analytics in place so that you can make sure that you're actually making progress and so we give you ability to see the big picture. Of course we give you reports for the apps that you scan right? So if you scan an application. We'll tell you. Application has vulnerabilities but we'll also give you the bigger picture so you can see for example out of all the applications I've scanned 70% of them are in compliance and 30% are out of compliance with the policies that I've set and over the whole history of our application security program. This is how many issues of you know that we have which are not fixed. This is how many we fixed. This is how many days it takes us to fix an issue and here's how all of that data is changing over time and so as you mentioned Rodrigo we want to make sure that we give all of that ah information and all those analytics to the customer. Ah, so that they can see how their program is maturing.

42:33.12
Balbino
O.

42:33.17
cassiodeveloper
Now I'm sure now I'm sure I'm Steve Jobs of application security because 2 because 2 or 3 episodes back. We talked about application security keypis and comes Jonathan with this information. So I'm Steve Jobs of application security I'm now I'm sure.

42:33.63
Marcos Santos
I mean 1 Okay, well you will.

42:37.80
Jonathan Davis
Ah.

42:46.58
Marcos Santos
Yeah.

42:46.99
Jonathan Davis
Ah.

42:48.17
Balbino
Yeah, fair.

42:51.77
Marcos Santos
So I have um, an important question so to make so Jonathan and I know no I god bye bye joha but no.

42:52.60
Jonathan Davis
Ah, ah.

42:52.67
cassiodeveloper
I'm going to be rich of this.. Ah. Yes, he's married. Yeah, he's married Mars I.

43:01.92
Balbino
Um.

43:10.82
Marcos Santos
Ah, what's the biggest ah geencing in yus such in Brazil and Thea with the ma reach level when Rodrigo says is more is is bashing Usa is.

43:21.49
Jonathan Davis
Yeah.

43:27.58
Marcos Santos
Is ah higher than Brazil Brazil was the g phrase.

43:29.89
Jonathan Davis
Yeah, um, so I can't ah speak too much to like how different regions are using. Um, you know these different tools. You know probably somebody on our on our um, our channel team could better answer that question but I would say kind of back to Cassio's earlier point. Um, that I think it's important to have Sas and se in place because ah casio I think you gave that statistic 70% of an application is um, open source right? or we're pulling our third party libraries and so if you're just scanning. Ah your first party code then you know you're leaving 70% of your application unscanned and and so I think it's really important to use both. We make it easy for you to use both and so when you do a static scan we're automatically going to do an se scan if you provide us with your dependency manager file. So for example, if you're using node js. If you provide us that package lock Json file along with um, you know the node Js code you want us to scan will do static analysis and se at the same time for you.

44:34.12
cassiodeveloper
We and in addition to this question of marcu's actually trying to give some answer here in Europe we are more proactive you know Bra Z is still reactive so we still wait for vulnerability is still wait for something to happen to make investments and everything.

44:38.20
Marcos Santos
And.

44:47.11
Jonathan Davis
Other.

44:53.58
cassiodeveloper
I think it's in the us is kind of like Europe kind of proactive and companies they have more regular um regulations more something about this. So maybe they are pushed to do something not to wait to the problems but to approach the process before they happen. Ah okay guys we are on the time.

45:07.77
Jonathan Davis
Oh.

45:12.80
Marcos Santos
Oh.

45:13.40
cassiodeveloper
So I want to say thank you to Jonathan to for joining us before saying goodbye Marcus I need to ask you for permission because houdri guci today has a joke for us on our episode he was he was working one month on this english joke.

45:14.38
Jonathan Davis
Thank you very much. Ah.

45:19.75
Marcos Santos
Um, oh kids.

45:21.50
Balbino
Are. Come bar. Nothing. Yeah.

45:27.88
Jonathan Davis
Okay, ah.

45:29.90
cassiodeveloper
So let's let's see what come ups every episode Janita we have a joke you know, come kind of joke to see if you understand but let's see let's see what hodrigos bring us today. Okay.

45:30.30
Marcos Santos
Um, okay, yeah, okay, another I and so ah.

45:35.70
Balbino
This joke is for for John okay, what it does a baby computer car call you fatherder.

45:39.84
Jonathan Davis
Okay. Oh what.

45:47.34
cassiodeveloper
Um, how and.

45:48.69
Balbino
Um, data are this and then Joke is markles.

45:50.35
Jonathan Davis
Now pretty good. It's actually pretty good. Ah.

45:50.87
Marcos Santos
Um, ah my God Ah clean.

46:02.50
Marcos Santos
Um, the dare freedom.

46:06.40
cassiodeveloper
I Have to say every day this this podcast is growing and growing Now we are We have even international jokes you see and the the guest laugh on this so it worked so perfect. That's perfect.

46:07.11
Balbino
And.

46:07.82
Jonathan Davis
I like it.

46:14.10
Jonathan Davis
So that's funny.

46:17.16
Balbino
Yet.

46:21.60
cassiodeveloper
Okay, guys Jonathan thank you again. Thank you for our time. Thank you for joining us. Thank you bringing knowledge. Thank you about talking about veracou I know a lot of companies in Bra brazil they are using and we are I'm a enterprise guy how to say so ah i.

46:22.71
Jonathan Davis
Yeah, thank you so much.

46:35.98
cassiodeveloper
Push companies to come to this enterprise approach not on not only open source I think open source is first level and we need to go to second level and third level and automation everything. So thank you for coming up with all ideas and all clarifying. Okay.

46:45.84
Jonathan Davis
Yeah, yeah, thank you guys and um Rodrigo Marcos so motu perra air what do what are there.

46:52.50
cassiodeveloper
Ah, perfect, perfect. So this is the episode number 6 of third season and I'm cassip perator and.

46:52.22
Balbino
But I went to present.

46:52.98
Marcos Santos
Ah, with the present.

47:03.32
Balbino
Um, Hodrigo Barbino and yeah

47:03.70
Marcos Santos
Hi'm Mark circles. But.

47:06.70
Jonathan Davis
Jonathan Jonathan Davis

47:07.68
Marcos Santos
Ah, no, where I.

47:09.90
cassiodeveloper
Perfect guys. So see you next week on next episode Bye bye.
