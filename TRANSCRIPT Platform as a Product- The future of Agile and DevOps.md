
... Back to [[index]] ...

[[Platform as a Product- The future of Agile and DevOps]]

```
Speaker 1   00:05
Got to pack my wash charger so you'll see me look at my watch about a million times. So, if I pull up my phone, I'm checking the time. Thank you for joining me and your morning. It's not the first one. Thankfully, hopefully you've had some caffeine. I know, I haven't. And uh, today we're going to talk about this concept called platforms as a product, it will be relatively high level from a technical standpoint. It's more level process in

Speaker 2   00:33
The act. It's like that in your organization.

Speaker 1   00:37
Before we get into that, My name is Brad Nelson. That is a somewhat decent drawing of me. I do art in my free time. I don't have much of that these days but, um, Every once in a while, I'll draw this last year 2024. So last year, I started podcast the edge of fragile's podcast. Uh, upcoming episodes are going to happen. Like John burn, James Brennney Esther Durky. You know, any of those names.

Speaker 2   01:07
Okay, for

Speaker 1   01:08
Them. Love it to turn this out. I currently work for Ford Motor Company their credit area. I'm in their platform engineering department. However, I do not represent Ford asterisk legal anything. I say it's not based on Ford. So on and so forth. Before that I was a consultant. Uh, for about five years. As a manager of product management and Agile coaching basically, so I help organizations with their Transformations. I've been an agile coach scrum, Master product manager, front-end developer tester done, just about all of it, except back, end DBA, Tech stuff, and that's magic to me. So if you, uh, you work in the back ends props to you, Cool. So that's enough about me. So let's get into it. Why are your agile teams slowing down? And the big one is contact switching. Now, this is assuming you're already kind of working in agile teams, but we'll cover a little bit of the alignment, competitans, but the biggest thing is content switching. A context switching is incredibly impactful on your performance and your time. And the other reason is cognitive load. Humans are limited to holding three to five items in their mind at once. And so if you are trying to hold something in your mind that's complex, especially if you're a developer, you have to remember like coding. Schema. You have to remember, you know, what other things integrate with this? What was the thing that I changed last? Oh look, someone else changed something in the same area. And I didn't know. That you're digging into all this stuff and then hope time for my daily Let me just pause my thoughts and help address the team. All right, I'm back into it. Oh, someone needs something for me. Now, I'm on a completely, a different task. But I know I'm going to come back, I'm going to try as best I can and keep that in the back burner. All that information, while I'm digging into a new thing, Oh, the effect popped up. Gotta switch again. Now, I'm going to try to keep that second thing on the back burner. And work on this third thing and truly dig into it and truly try to understand all the systems and everything that goes into it. And when I grown a year ago in this, Or when someone wrote before I enjoyed the company, And so your brain fills up. And then next thing, you know, you're not performing as well. It takes you longer to complete stuff. You're more likely to make mistakes and this isn't your your fault. This is the human condition. Sound familiar to anyone. Yeah, I think most of them. So, one of the things that I didn't think to ask for were tables, So I have some activities that require pen and paper, I have the pen in the paper. We're just going to try it. Uh, on lamps and if it doesn't work, or if you have your laptop to write on, Um, then shame with me but it's an experiment. Inspirit.

Speaker 2   04:33
There are a bunch

Speaker 1   04:36
Of these fancy big pants. That's got nobody's name on them. So if you need a pen, hopefully help yourself. Anyone

Speaker 3   04:47
Need a pen here?

Speaker 1   04:59
Like a bunch of this really fancy. Uh, he's got one sporting right there. So, I'm gonna take one and pass. I mean

Speaker 2   05:30
I I need a billion pages. We're going to. And yeah three Congressman, right? Come on

Speaker 1   05:57
Hickeys,

Speaker 2   05:58
Proving a point about context switching. Maybe I'm not actually gonna drop. We're just passing over here. Thank you. Thank If there are any managers in here, I

Speaker 1   06:18
Want you to see I drew the sun, everyone last minute. And look how naturally helpful everyone is. Out there, right? It's not because our developers are white.

Speaker 2   06:31
How do I get my clicker? So.

Speaker 1   06:33
All right, this is an exercise I stole from Dave Crenshaw. Um, in fact, you talk about various different types of multitasking. We'll get to that in a minute here. But the first step I'm going to ask you to do is to just draw two lines across your page. All right, and then don't start yet. But when I say go, I want you to write out switch. Tasking is a d. And then underneath that 1 through 20. Or 1 through 21, I'm gonna time you Uh, this fancy mostly accurate stopwatch here. Uh, we'll go, you can look up when you're dying. You can see how long it took you. All right, everyone ready?

Speaker 2   07:19
All right,

Speaker 1   07:20
And go.

Speaker 2   07:46
We

Speaker 1   07:46
Call it guys. That's not much is not going.

Speaker 2   07:49
There we go. There's

Speaker 1   07:53
There's my first message talking about it. Uh, I programmed a timer for the next exercise.

Speaker 4   07:59
So is everyone done them?

Speaker 1   08:01
So that's her 30 seconds. Ish. All right, so for this next one, I'm going to have you write an S and then a one letter W, then a two and a high and a

Speaker 2   08:14
Three, all the way across the board. All

Speaker 1   08:17
Right. Ready. Go.

Speaker 2   09:14
Ears. All right, if you're not done to spend 60

Speaker 1   09:21
Seconds, And work that time with William the engineer. Uh, yeah, when I did it, if you didn't finish, it took me about 57 seconds a second. And so the the point is it's a lot harder, right?

Speaker 2   09:36
When you're

Speaker 1   09:37
Able to streamline a thought, first, you're really doing the same thing you're writing. All right, the same stop. If your contact switch between the words and the numbers, it's a lot harder. So that's a nice little exercise to show the impact of contents contact switching. There's even something as simple as that took. You twice as long. All right. And that's because there's two types of multitasking. There's something called back tasking, which is when you're baking, you put something in the oven you walk away, you know, it's there, but you're able to pretty much fully dedicate your attention to something else. Or hey we cured off

Speaker 2   10:17
Um like

Speaker 1   10:18
The the test Suite. I know it's raining. I am talking, I cared off something that's running. I know it's there, but I can come back and check on it. Open a

Speaker 2   10:26
Support

Speaker 1   10:26
Ticket or someone else. Right. I can go focus on something else. But anything that requires your attention? Well, that's actually called a switch passing. And that's what most people want. Multitasking is because we really can multitask in the way that every math description in the world thinks you can't

Speaker 2   10:46
Right? And

Speaker 1   10:48
So really what we're doing is we're switching back and forth which would pass really fast. So now I'm going to ask you to put your paper open. This is the last exercise.

Speaker 2   11:08
All right, so what I'm going

Speaker 1   11:09
To do is I'm going to give you three seconds to memorize the next letters, and slides and then write them back. All right. Ready.

Speaker 2   11:30
Oh, I

Speaker 5   11:31
Stopped fucking

Speaker 2   11:43
All right. So we're

Speaker 1   11:49
Gonna try it again.

Speaker 2   11:51
All right,

Speaker 1   11:52
Just one more time and then so I'll show you again for three seconds. And then you write it down.

Speaker 2   12:24
You're better than Texas.

Speaker 1   12:28
Same. Same letters. And that's something called information, chunking. Exact same letters but because like something freeze and there were letters you were familiar with. It was easier for you to memorize them. And once again, this is a small scale and that exercise is actually from education teaching people because

Speaker 2   12:50
It's the

Speaker 1   12:50
Same thing. But when we're working and we think about multitasking, you know, we're able to die. Really, really good in a subject area. We just sent information as chunks.

Speaker 2   13:02
But it

Speaker 1   13:03
Should grow in a different system, a different task, a different area. That's a new chunk. And so, The money really has an intern there.

Speaker 2   13:14
I can only

Speaker 1   13:14
Think on one thing at once. We only focus on one thing in a while. If we try to do more, well, we're going back and forth. There aren't exceptions. Always, and most of us we want to do one thing once. This trunking allows us to dive deeper as I mentioned, We can hold a handful of chunks, the previous slide is at three to five. Some people say the magic seven and there's some discrepancies out there in the scientific world, but it's around a handful of things at once that you could hold. There's limits based on that. It's a lot harder for us to hold numbers than words for example and there's so that's also why the amount of chunks that we get pulled at a time vary because it's based on the information they're trying to remember. And when we don't take these things into consideration and our teams in our organizations, All right, all of these things start to happen. Many of us here have probably experienced some of these things or seen some of these things and maybe we don't fully understand why. But I guarantee this is a large part of that.

Speaker 2   14:31
All right. So how did

Speaker 1   14:32
We get here? Oh first. Let's put that evil on me, right? So I'm not trying to curse you all. I'm going to share how we got here and then a way that we can move forward So, a lot of organizations Have different teams across these different areas.

Speaker 2   14:51
And

Speaker 1   14:51
It seems like the natural inclination is the based off of discipline so teams are out like this. Yeah, you're in for team middleware. Now, you have your data team or yay, to hear some sort of middle layer team. Maybe they actually write apis, Maybe Services near us like web methods, but some sort of in-between connector team and then you have your front end teams Those guys are the worst I've never. I was brand a developer. And so,

Speaker 4   15:22
When we get into agile, we teach

Speaker 1   15:25
That we want to be able to deliver something for an ideation to Production. And with his little handouts as possible. And so we introduce these things called stream teams. And so string teams. Uh, our lines are value string. Ideally, I bet most organizations miss that memo. But, uh, your product team, your stream team is really what it is. And so this helps some because now as uh, DBA or as a front end or whatever developer I'm no longer working at multiple products at once. So this allows me to focus a little bit more and get a little bit more familiar with the domain, and this is great. Uh, but then as your organization scales, right? We're like, oh, wellber's gonna buy more games where I start having more more teams working the same thing or you're gonna be supporting more stuff. More tooling is introduced each team has their own tooling and our spendings going out. Team one is licensing for this competitor team, two's licensing from this competitor. So next thing you know we're not getting the best deal on software. We can't really help each other or we have to learn multiple tools to do the same thing. And uh, we start to recreate the wheel across all of our teams. And there's a lot of things that happen there when we start to scale and we're not deliberate with it. Uh but the biggest thing is that next thing, you know, we're spending more time maintaining the tooling To be able to reduce value. Then we are spending time. Delivering, that delivering what the business wants for us. And then, you know, our t-shaped team that has one DBA, is now trying to manage, right? The database for all the teams, Is now spending a lot of time at Tech Deck or reorganizing or you know, if Uh, you've been in any organizations I've been in. Apparently, nobody knows how to structure a table appropriately. So,

Speaker 2   17:31
It seems like they're

Speaker 1   17:32
Always an afterthought. And so, all this stuff impacts. And so the solution is something called a platform team. All right. And so the idea is we take, One of these areas that the teams are spending up that are all working on. And you can't get out of that team. You reduce cognitive load. Now from that team. All right, and then this team can just focus on that thing. And so, we talk about a platform it's software Hardware, with, reusable capabilities on which other Technologies can be

Speaker 2   18:09
Developed on.

Speaker 1   18:11
I think the one that most people tend to think about, at first, is hosting At like, if you have a data center, In your organization or most of us now come to the cloud or have a multi-cloud solution and that's an easy one to end up. As a platform, that is something that someone else manages a lot of times another company on behalf of our team. We have to know how to interact with it, but we don't have to know everything that goes into keeping that right. Now, this might sound a lot like a component team, right? Well, it's not we're not going backwards to the component thing. At the side door right now. It's

Speaker 2   18:53
All

Speaker 1   18:53
Right. Well, I'll explain why. The first thing I want to ask you is what percentage of apps on your phone. Do you actually use? 10. 15 8. Yeah, we all have a lot installed, some of them because they come up the phone. Um, but I've definitely installed many apps that I've never went back to or I used it once. Or I tried to use once didn't have what I wanted, and it just sits there, collecting digital complex, And and that's because 80 percent of features in the average software is rarely or never used. 80 of the things that we are programming that we are spending 40 plus hours a week on are not being used. And this is something that most of people. Have found in their research. The most recent one that I'm aware of is Pendo. The 2019. And so usually when people say like oh I need to hire more developers, I'm like, well, do

Speaker 2   20:00
You

Speaker 1   20:02
Why do we need to focus on things that people

Speaker 2   20:05
Actually use?

Speaker 1   20:07
And so that's when we introduce What's called the product mindset. And so, the product mindset is focusing on delivering value for customers, based on the learnings and feedback. All right. So this is the opposite of completion driven approach, that project, delivery tends to focus on, What I mean by completion driven is our goal is to get the work done.

Speaker 2   20:29
All right,

Speaker 1   20:29
Whatever our tasks are whatever our cards are whatever. Our project roadmap is. Our goal is to get that done. Doesn't matter if it delivers value.

Speaker 2   20:40
Right. And then we're like oh,

Speaker 1   20:42
I just delivered a million dollar project. All right, so the next. Well, did you make my handles a million dollars? Did we get it back? At least we are not. Thanks for Pakistan, including the task. And so the product mindset is really, I would call the agile mindset, address become very ambiguous. And so, I feel like I have to specify, but the very first principle,

Speaker 2   21:08
Of

Speaker 1   21:09
The actual Manifesto says our number one priority is our highest priority, but don't choose messenger, so can't hold it, right. Is delivering value to our customers. Now, there's like an iterative incremental. Or vertage in there. That people tend to focus on. They forget that and everyone's saying we're supposed to be doing is delivering value for customers.

Speaker 2   21:34
Okay, and so

Speaker 1   21:35
It's not about building the right thing. Or it's not sorry, it's not about building the thing, right? I can't read my inside anyway. Right? That we all naturally think of solutions, we all naturally. Go there. I think it's a human trait. As soon as we hear a problem, we're like, how can I solve this? Let's all this way. Let's solve it. This way. It's all it this way before. But what we really need to do is understand the problems and start. Doc, our documentation with what is the problem we're trying to solve? What is the value? It brings for our organization. We need to work more on delivering the right thing. That I've taught this a lot, uh, to a lot of Which are product managers. And it's called the code of uncertainty.

Speaker 2   22:25
And so

Speaker 1   22:25
When we very first have this idea, there's a moment, this thing we're trying to solve, we have the most possible uncertainty We don't really know what it is. We need to build to solve that problem. Our goal is to be a close certainty.

Speaker 2   22:42
Every

Speaker 1   22:43
Team is gonna be a little different, it's a little bit of an art as much as a science. But what

Speaker 2   22:48
You want

Speaker 1   22:49
To do is you want to kind of figure out your process. And draw your own lines.

Speaker 2   22:55
So, when

Speaker 1   22:55
I finished planning, I still am not very servant that the thing I'm building for today, but I'm more certain When I started development, I don't know. What I learned more through development.

Speaker 2   23:08
And

Speaker 1   23:08
Actually, when I released the production, I still don't know. And that's why we need to validate. What we're putting in production, see if it has the effects, neither

Speaker 2   23:19
One.

Speaker 1   23:19
And so agile is all about planning. It's all about refinement and pushing to production is part of our refinement process.

Speaker 2   23:28
It's

Speaker 1   23:29
Part of how we reduce the uncertainty. And so when we go back to a platform and when we think about it as a component team, the difference is that we need to apply that same product and mindset to our platform team. And that's why this talk to small platform as a product. Okay, your customers are your internal. Developers Engineers teams whoever your platform is serving.

Speaker 2   23:59
Let's

Speaker 1   23:59
Go back to the cloud example, all right? Like AWS, they're a completely different company. That's how you

Speaker 2   24:05
Want

Speaker 1   24:05
To function, even though you're within your company, people should be able to self-service from your team. If you have to put in a ticket, you're not a platform

Speaker 2   24:15
Team.

Speaker 1   24:16
Right? If you are an impediment, you're you're not doing this in an effective way. You're going back to employment teams, And so the platform team builds and maintains right building blocks across the company. And this allows us as we talked and we saw reduces times of load allows us to increase our Mastery. I've had a lot of developers complain going to cross-functional teams. I don't want a program in that area.

Speaker 2   24:44
All right. I think they

Speaker 1   24:45
Didn't agreed yet. I didn't spend years in this field to program. This other thing,

Speaker 2   24:51
So it's

Speaker 1   24:51
Going to help them with that. It's going to allow our product teams and our stream teams to focus on, delivering the solutions. Instead of maintaining, whatever it is, the platform team is taking off them. It's also going to ensure that that thing is being looked at appropriately. Security is being considered. It's getting all the the updates it needs, it's getting the care and loving and needs to take care of it. Because the person that are cross-functional team either just got forced to pick up, you know, Jenkins or whatever it is because nobody else wanted it or they're the junior. And they don't really know what they're doing, they just know enough to get it running.

Speaker 2   25:33
Or,

Speaker 1   25:35
You know, the CMS tool. Someone on the team, get stuck as the CMS expert because they did one ticket in it and now nobody else wants to touch it. They can all be like, oh well,

Speaker 2   25:47
You did it before.

Speaker 1   25:50
It also bleeds into finaps. Um where you can reduce your cost of your organization by combining licenses. You can get better deals if you're buying more and more. So on and so forth. It also holds up security and all that. So platform as a component. Because they're kind of it, it requires you to get a roadmap requires you to open support. Where I can actually make a change on the server. I have to open a ticket. Oh, that is an impediment. If those same teams learned to treat you as the customer and not as an inconvenience, And created tools that help you to self-service. Then you're becoming a platform.

Speaker 2   26:43
Then you

Speaker 1   26:43
Are becoming enabler.

Speaker 2   26:45
And now

Speaker 1   26:46
That's not to say that you're going to know everything that they need up front. You still need to work with them like a product team does, I don't know what all my customers are going to. Um, I don't know what all my customers need to solve. Immediately, right? I listen to them. I talk to them. I observe them. And then, You're going to do the same thing as a platform. You're going to see what your developers are doing, what their challenges are. You can see what their roadmap is. Oh, they're doing this thing three months out. Hopefully, they're planning quite that far. But

Speaker 2   27:23
Uh,

Speaker 1   27:23
They have this thing up coming, where I'm gonna need to update my platform. Let me work it into my model before they

Speaker 2   27:30
Need it. Now, this concept

Speaker 1   27:36
Was first introduced by thoughtworks 2017 but in 2019, the 14 topologies talked about it quite a bit. So this isn't necessarily new at this point. Wow. I mean, we know organizations take time to die things and we're written 2001, right? And we're still Organizations are adult. A lot of those houses are even older.

Speaker 2   28:03
And in the book we've touched on some of

Speaker 1   28:05
These themes, there's basically four teams that they talk about, so they're streamlined teams. They're going to capture

Speaker 2   28:10
Subsystems, all right?

Speaker 1   28:18
Right? And so we touched on streamline. All right, so streamlines on your product teams, they should be aligned to value stream platform themes. Enable them, right? These other teams you maybe they have like, enabling team. That's where you have specific Specialists.

Speaker 2   28:37
Um,

Speaker 1   28:37
Any of complicated substances. You don't see those a lot. Some of them would be like, an agile coaching team given as a person team in your organization, they wouldn't be experiencing Or if you Enterprise artifacts and they're not a stream team, they're in a11 in a complicated subsystem teams like data scientists. In data scientist routine. Usually

Speaker 2   29:00
They

Speaker 1   29:01
Only do data science part

Speaker 2   29:03
At a

Speaker 1   29:04
Very deep in that area. But uh, I highly encourage you to read this book where I was first introduced to the idea as well. And this is the year old engine now but

Speaker 2   29:18
You know, Gartner predicting that this is for

Speaker 1   29:21
The future, right? So you can see it and see the arrow incoming technology. And this is the way that organizations are going to be going. This is the way that we're going to stay competitive. So it's definitely something to wrap your mind around. And we'll try to open their organization and

Speaker 2   29:42
Go in this direction. All right, story

Speaker 1   29:50
Time.

Speaker 4   29:52
So I've seen this go well.

Speaker 1   29:55
Uh, and that's all. And I've done this at organization before, I even do this concept was I have a name for it and so some of you may have experienced that as well. Uh, so I spent a few years at a little grocer called Meyer. In their marketing and loyalty department. And, I work on the mobile apps. Don't blame me for any new things. I've been there about

Speaker 2   30:19
Eight years,

Speaker 1   30:19
But I was there when created it. And I spent a few years working on it and it was tied to their power systems and they went through a safe transformations. And then they force these teams. And it worked well first. Uh, but the way that the engineering was structured, at the time, or for the technology at the time, is if you, you know, native mobile apps, I was an Android or technically their own, they're

Speaker 2   30:49
Working really different,

Speaker 1   30:50
They put podium, electric users. Platform, we did not. I think he had services that we actually have things that kind of goal for rent. First, Backpack to the website. And those also tie back to our logic application, that enables sales, and coupons, and that sort of stuff which then picked up in the stores. It's all connected, but it's all these different products and areas. And on a mobile app teams, they took these service people who worked on the logic layer. And they stuck them on the jeans. Well, they have very little work to ever do for the lab. It's kind of a dummy, why it's taking this other stuff and they spend all of their time. Supporting the actual logic change that it has And working with one Excel and all that stuff. And so what we found was naturally they had created their own team. And they were on two teams, they were showing up every day for the mobile app daily and then they were having their own kind of sock.

Speaker 2   31:57
Because

Speaker 1   31:58
That's who their real team wants, that's who they're really working. And so I actually uh got asked at the time by them like hey can you help us build a business case? The pitch says Um, and it happen. And to be honest, it was a very hard pitch at the time. Uh, leadership there was like I need you to guarantee and they're going to get more done. I was like, what if they get the same amount done, but they're happier. Not good

Speaker 2   32:22
Now. All right. Uh, I promise you they'll

Speaker 1   32:26
Get more done. And we did see an improvement. Because they were no longer in as many meetings. In advance. And they weren't. Uh, they were switching past as much. They still had to interact with those teams because we still needed stuff from time to time but it was a huge Improvement and so a platform can be something except with that. And the mobile app. Can't go ready. We're kind of stealing from it so they already can move that home right to self-service and so when you say self-service it doesn't have to be a fancy control panel. It can just be an API that's available that people can can leverage

Speaker 2   33:10
Um, let's see here, uh, I am

Speaker 1   33:13
That's another type of platform that a lot of organizations kind of I think Grant access to, you can use your laptop or to get a certain area. Some organizations have built-in cell service websites. I just started at. Four or five months ago. There are a lot of websites. You go to. I need access to this. You put the box. Doesn't always work as well as I'd like, but So so those are some examples of platform teams. But then I've worked with web methods team. Where they had their own roadmap. So all these teams had to come to them and say, hey, I need this And usually things are like, I need it tomorrow. We're going back to a good point. That's where. That really kind of gets the difference. Is this A New Concept or just kind of thinking about it a different way? So

Speaker 6   34:27
You it's great that you mentioned. I am because I was gonna use that as an example. When a medium or larger company talks about having in platform team, how wide of a scope is it does it become one big platform team with individual components inside of or does every individual team just Rebrand themselves as a platform team? Because that's my platform. I mean, I'm thinking of things, like, you know, you've got IAM. You've got a sales force. You've got your Cloud enablement team that, that's what I'm part of, right. Um, and everybody wants to call themselves a platform team, right? But there has to be a breadth. To me where you know, that platform is no longer, there's always going to be components outside, right? So

Speaker 1   35:19
You can have multiple platform teams in your company. Uh, and if you're at a smart company, you should Um think of it the same way as like, how did you align our products use In these value stream acting hopefully, Odds, are someone just said that's productive? But we need to align around about, so I wouldn't expect right Salesforce team to also be dealing with gcp. For example, like those are different enough. Where it would be their own platform teams. You want to apply the same product linking?

Speaker 2   35:54
To

Speaker 1   35:55
Both girls. And ideally you would even have a project manager. More technical. But they're the ones that are going out and they're looking and trying to see what is it that the organization needs from this tool going forward.

Speaker 6   36:09
As an aside. Can a platform team. Include the tooling that they want the other teams to interact with them as part of their platform. So if I'm part of the cloud team and I declare you're going, everyone's going to use terraform as their standard tooling to deploy stuff to my cloud. Does that

Speaker 2   36:28
Become part

Speaker 6   36:29
Of my platform or is that Is is declaring that even something the platform team should do, should they say you do what you want? You just tell us what you want, we'll make it happen.

Speaker 2   36:40
I would say

Speaker 4   36:40
Independency, you know, I do think it's up to you if you're in the position to know what's

Speaker 1   36:49
Best, you're like hey it's best forever, you care for and that's something that I can take on as a part of my team, but yeah if you're terraform needs increased kind of load to the point where you're focusing on that. Much. You need to talk about that, okay? And so, when we think about organizations, Organizations are too. Okay and we're just not aligning ourselves. Effectively. So instead of having five teams that are all managing UCB or Salesforce or perform which is then that often so it's on the team to take that walk away. When I was at Amway, I was in that RO department. For iot devices. So any of their iot devices that connect through that I was in that area. And we had a platform that just maintained like the mobile app itself. So every mobile app was really based on the same platform and then we would customize it, but they handled all

Speaker 2   37:56
Of

Speaker 1   37:56
Like the networking Logistics of the app. They handle logging in to Amway's site. They handled all of that. And then we just had teams sit on top of that, that would then constantly see the particular IOP device. But then we would have a really different team that really managed like account modifications. Answer your question.

Speaker 2   38:22
Yeah, yeah. So you

Speaker 1   38:23
Might have a lot of platform teams and you're in a small company when I'm not

Speaker 2   38:28
It

Speaker 1   38:29
Doesn't make sense to introduce a platform team, if it doesn't make sense. But I think a lot of us something like this either work for a large company or consultants not working. Great question. A little earlier, you talked about Buildings were great things, right? And part of that, he said that should be

Speaker 2   38:51
And

Speaker 1   38:52
Agile talks about bringing customers about it, but that's really easy to say.

Speaker 2   38:59
Right,

Speaker 1   38:59
That's super easy to say. Anybody can say that it sounds kind of insightful, but the problem is a lot of both of those things are very subjective. So Who's right to think of you. Check figure out. In fact, my story, I gave a talk at this very conference called the velocity trap, where I explain exactly how to do that. But, When you think about how most our teams operate and I mentioned like we focus on completing past a lot of agile teams are the same. We're like what's our philosophy.

Speaker 2   39:31
Right. And that's

Speaker 1   39:32
All we care about becomes are great. If you are presenting your philosophy to anyone outside of your team, stop. And you're teaching them the wrong thing. We need to figure out what is it that our customers need and it is a bit of And so, when we go back to the point of uncertainty, That's where I say. The living reproduction is part of our refinement so we need to deliver something to production and say did that have not wash our hand but it was there and then we keep changing that. Most companies are not there, but we need to start aligning our work to the sponsor solving not like check boxes. There's audit managers, it's there to do that. There's an entire bill called user

Speaker 2   40:20
Experience. Okay. And

Speaker 1   40:23
Do the research. They look into it. So there's people that specialize in it that are underrepresented in a lot of companies. Um, so ultimately, I don't want to say, it's not the developer's jobs. It's kind of those jobs deliver value but there are other roles in other trainings that are much more equipped to answer that question. But most companies struggle with that because it is hard, you're right. It's very hard. Very hard to figure out what is the value. It's easier to say this done check check check. Of water because you know, you posted the 80 percent of features are never rarely used, right? And I think of like accessibility Those are never rarely used and but they're super important, right? So when we, when we kind of quantify it in that manner, It really pushes out a lot of the things that are important to a small. But the rarely are never used. So, is that bringing value to the customer? I think, right?

Speaker 2   41:22
But the

Speaker 1   41:23
Question is, is it a numbers game? Are we trying to get to 50 of our features are used 100 of our features are always used, I don't know. And I think that's a I I think that You know, quantifying it like that. You know, takes away from those rarely and never used features which offer a lot of value. Uh

Speaker 2   41:44
And

Speaker 1   41:45
Say yeah, anything like that. But I think uh Microsoft Word How many teachers are in Microsoft Word? How many actually use?

Speaker 2   41:53
Oh I actually

Speaker 1   41:54
You're a small percentage but the point is is that they're one of those features are there because some are just I don't know. Microsoft knows. I was working with the top partner, took interaction with some, but I don't think most comfortable smell and that's part of the problem. So, really I'm saying is find out. Maybe, you're the exception, right?

Speaker 2   42:18
And when it comes to

Speaker 1   42:19
Accessibility things, Unfortunately, a lot of companies don't do the right thing, just for the right thing and the amount of time. That's going to be up to your company inside. Do I want to be the company that, you

Speaker 2   42:31
Know,

Speaker 1   42:32
Gets read it about because my banks aren't accessible. Like graduation and Brands have their own intensive

Speaker 2   42:40
Values.

Speaker 1   42:46
That's something that the people who are paying for development. Really, got the name of the side. I remember like an easy answer for that. I'll remember, just it's gonna balance again.

Speaker 2   42:57
So when

Speaker 7   42:58
It comes to a platform team is the customer the other team within the company. Yes.

Speaker 2   43:05
And

Speaker 7   43:05
Then do you find that? It's easier to assess whether you're delivering value to those customers.

Speaker 2   43:11
Yes.

Speaker 1   43:12
Okay. Yeah. Two simple questions. Yeah. Yeah. I've had some readers be like well you have to make sure that whatever those teams value Target is that they're doing what is their kpi and their cape guy needs to go off. There's too many factors in Miracles. Yeah, it's a little platforms. If really, you're measuring your income?

Speaker 3   43:35
And I'm some question and I'm afraid if the answer is, yeah, that's another talk. Um,

Speaker 1   43:41
So you worked for Ford now

Speaker 3   43:42
Companies D with lean for now two decades. And and customer value there has to be someone outside of forward. So I'm a platform team. I deliver value to you, that's not valued from the lean standpoint. Unless you used to ship a product to somebody outside of the fort and

Speaker 2   43:59
Thinking

Speaker 3   44:00
About that. How does a platform team an annual review? Make sure, for example, there are people are recognized for the value, they're really contributed to the net business effect. When they are one level removed from the genuine value delivered outside the organization.

Speaker 2   44:15
Correct.

Speaker 1   44:16
That was an example where I think Wing doesn't necessarily translate the software cleanly and

Speaker 2   44:21
Where I

Speaker 1   44:22
Think you give yourself in trouble by overthinking it but I also want to correct you most of the principles the main board created.

Speaker 2   44:29
Oh yeah

Speaker 3   44:29
No. I'm

Speaker 2   44:30
They've been leaning forever, right?

Speaker 1   44:32
Not necessarily activities from whatever. But um but yeah so I mean ultimately someone high up needs to be looking to say like hey our platform Community. But at the more micro level, if you're a platform humor, I would just focus on And so, it's just being about, Um, okay. That is something that

Speaker 5   45:03
I think I think one of the ways you can measure that which do they come to you, when they need

Speaker 2   45:08
Something or do they kind of work around you? Yeah. Do

Speaker 3   45:11
They choose you like a competitive scenario? Yeah.

Speaker 5   45:16
Sometimes people drive that around that because they know how long it's going to take for

Speaker 2   45:20
The form that maybe or they're not going to work. Yeah. And

Speaker 1   45:29
You will see an uptake but I don't like saying the platform team is responsible for that because as like an actual consultant parent usually wasn't

Speaker 2   45:39
Whether or not.

Speaker 1   45:47
That's a great question integrate that Any other questions thoughts? Can I see your product slide? Yes. This way, we could stream it alone. Yeah. Do those kind of there's a stream aligning team kind of walked into a Blackboard team, or is it a collection of you have many shrinkle 18s producing, all these value products and then you can build a platform out of that. How you know, is there a relationship there or are they really truly different types of A platform should alignment as well. It's just the value ends at about as we want. So really think of like a student line team is being a problem, a lot more. Seem like we have multiple streamlined teams, the one platform, I really like that. Uh, where instead of five teams to maintain the U.S, ideally we're reminded They're trying to scale. And the way that they're going about scaling really, what we need to do is we need to do value strains and realign our products and our teams and split them off your focus. That way instead of just trying to throw more people like a problem and then that introduces the folio management which is something more. Any company that's big enough problems. Your framework I would say. A solution. So the platform team plays down whatever the tool is at what point is it no longer the responsibility to throw abstraction. It sits at what point is it? Another deep responsibility to build that fraction to getting the platform. For some platforms money, that's complicated, but often get into at the top. Um, If your customers can't use your products, that's your problems. So when you see the platform team is both responsible for running it and then like providing home charts or something on that line. Or in any kind of pool like that. Or do you think that there should potentially be sister platforms? He's one is managing Hardware one's managing accessibility Um, I would say. You're responsible for all of it, but I'm going to throw like an asterisk and it depends and on the organization. Um, but ideally, you're responsible for all of it, you're responsible for maintaining tool and then being able to access it. Where I draw the line is once it starts going into feature development, That's the streamline team.

Speaker 2   49:05
So,

Speaker 1   49:06
You're not necessarily managing their data or their possibilities or their codes. They

Speaker 2   49:13
Need to figure

Speaker 1   49:13
That out their own. Ideally you have some sort of Wiki or swag or something that enables them to use it and answers questions, I think whatever it is. That is your platform to each responsibility. Any other questions? It's great. Great conversation. I appreciate it. And purposely. Made it a little bit shorter to enable that. That's what I have. Thank you.

Speaker 2   50:05
You want the slide

Speaker 8   50:06
Work over here, you can download apply or go here and it's Excel zones. Great data Delta login. You want to add your new things or code on.

Speaker 9   50:21
And it doesn't like that. Nope.

Speaker 6   50:52
Because then they get really pissed off that dad has Snapchat. Dad has Snapchat, of course. So

Speaker 2   51:00
Here's

Speaker 6   51:00
The thing with my niece and nephews mommy doesn't have Snapchat, but Aunt stuff does. You should have you should have heard it when I said I gotta get on my Discord, oh, my kids were thrown for a loop, really? You have Discord buddy,

Speaker 10   51:15
We created Discord.

Speaker 6   51:16
This court is dead, love it. Just add it. I've been on my phone just for that. Yeah. So well, I will say I'm out of here. All right. Well, have a great trip home. Yeah, nice to meet you. It's been awesome. I mean, where the hell can I find me on the internet? I sent you a link demo. You did, did I accept it? Yeah, yeah. Okay. Cool. Because I

Speaker 2   51:38
Mean,

Speaker 6   51:39
I don't, you know, I don't keep a whole lot of bullshit out there, but I have a LinkedIn profile and I'd be post comments. I don't either but also like I post comments on there and run my mouth occasionally, right, I could at least remember to connect because one day I might be there. That's what vice versa and that works. I've um, my last three jobs. Have come because of old connections, exactly. It really has. And a buddy of mine, the guy was actually I got a guy, give me a second and then the guy was sending a snack with, he's a voice engineer. That he works on Cisco is I think it's Cisco is not going to allow CDW to sell it anymore. They're taking it back and they're saying we're selling this ourselves. Right? Right. So he's going to be either losing his job or finding something else. Yeah, he sent me a message from this company. He sent me his screen capture from a company. I used to work for that has voice engineer job. I sent his send a recommendation for him over to the guy and he's already got an interview tomorrow. I mean this happened this week he sent me the message. Night and I think his res his interviews tomorrow. So, you know, I try to keep up with people like that, right? I'm not, you know, it works out great. Um, and if you ever say anything like Great American or something just holler, yeah, we had an awesome platform team with Cloud Foundry. Um, Moving to kubernetes, probably. Yeah, but I'll tell you, I have my, my date already carved. I've heard the headstone for cloud found, I don't know. I don't know if they do remote, it was all on site, okay? But the large parts of Great America do have a remote like the data teams and stuff, they're all over the place.

Speaker 2   53:27
Um

Speaker 6   53:27
Our platform team, I have been more than impressed with their skills. Um He's younger than me. Okay, people don't leave because it's been a fabulous place to work. Okay. Um and our platform. Team stand. Good. In the meetings, I've been in with them, I'm I'm shocked at their skills. Which is funny. Steve was probably

Speaker 2   53:59
Yeah, I think that really commonly with

Speaker 6   54:03
Class drinks. Oh, anything. He can do it all. Oh yeah. So you know, if you ever see something there, if you're interested, please, please holler? Yeah. Um, for sure. And I mean, they're great people. And I, you know, it is Insurance. I think you fit in pretty damn. Well, they aren't um, they're a lot more like when it was a Humana, that was a different scene. Wait,

Speaker 10   54:42
She works for home now.

Speaker 1   54:44
Yeah.

Speaker 6   54:46
No, no five days a week, she's in the office. Um and they do the mentor shirts and ties the women have to dress up. Until recently, the men even had beards and he couldn't have your hair ball. If you can't have your parents. Such a collar then came down here is very, very much like that. Um, I mean, I guess if they changing, you know, I'll dress however you want, they don't they don't have a pension plan though. Because who else does this? All right. They're like only Fortune 500 company. One of the only that still has pension plans. Real fancy. They they do and they do it on fire. They are always on. They're really backward on technology. They don't they never laid anybody off anyway. So, I've got connections to both of those. Yeah.

Speaker 2   55:32
And like,

Speaker 6   55:34
I probably would never work for Western 7 because that just doesn't fit my Persona Great. American is not that person, even though it's the same basic company, right down the street, Um, because I mean, similar stuff, but right down the street, um, you know, hey, just let me know. Yeah, anyway, we'll be in touch.

Speaker 2   56:12
That

Speaker 6   56:14
Interface. It's like really your product. Yeah. The guy asked about performance be terraform is if you give them a structured interface of how they're going to use that air form and how they're going. Yeah, so they actually have a team, how do we use all the other components and they can put them all in and they should check boxes for that. Nice use it. I guess it made sense to them. I, I don't know. The reasons they started before I was there but but it's really impressive. It's the most impressive thing I've seen and it's probably Like honestly, it's true. That's cool. Yeah, I mean, I know like Netflix has had platform teams for a while. I don't know about the other organization today. Google's more about embedding people into. Yeah, this one pushes the website like sections And in order to deploy it and just type down like what is my repository name? Like is this public facing? What security I knew. Do I want to test? Do I want to use tools what part of like the cicing pipeline? It's all check boxes. Nice. We built a multi-team using less platform team. Um it was starting to get going great. You're like we're going to reorder and we're going to send everyone out and put them in in the stream teams and I'm like,

Speaker 1   57:43
Yeah

Speaker 6   57:45
It's funny something out of that but I do feel like companies where you are too fast to know if the first yard even had. Yeah. In fact it takes so long but most people exciting as we are Yeah, I mean, and they were growing something else every year, they're doubling in size, but yeah, I agree. I was just getting this going. You guys. I got much to say other members, wonderful. And um,

```