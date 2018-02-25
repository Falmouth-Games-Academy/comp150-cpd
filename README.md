# COMP150 - Reflective Journal to Accompany My CPD Report
*You should reflect across the first 13 weeks of the course. This is the period from induction week to the Winter vacation. In your reflections, you should try to identify at least one challenge that you experienced and/or obstacle that you encountered that week. Consider which skills and/or characteristics that challenge/obstacle relates to.*  

*This will prove to be a considerable aid when you need to identify the most important areas of personal development in your report. Do try to keep up by completing an entry in the journal every week.*

# Notes
### Dispositional domain:
Time management, motivation, self-discipline  

### Affective domain:  
Capacity to be aware of, control and express emotions, and how to handle situations in a judicous and empathetic way.  

### Interpersonal domain:
Communication, listening, negotiation, problem-solving, decision-making and assertiveness  
Not everyone has perfect interpersonal skills. The vital skill is managing all people including these kind.  

### Cognitive domain:
Assessing the strengths and weaknesses of your approach to learning.  

As I noticed in the study, one of these things is reflecting on progress. This is mildly ironic. And generally speaking, if there is any case of irony wherein I am the one to call it ironic, it is ironic.  

### Procedural domain:
Identifying the skills you have, and what you need to improve. There is a GDC talk called How to Succeed, Fail and Learn worth watching.

# Arising Problem Areas
## Communication blocks
There are times when I know I need to know something, but don't ask. Things like 'why hasn't x updated the Trello board, and when will they?'.  

The cause is probably that deep childhood etc etc. If I talked too much, people tuned me out. However, I know this stuff is important. Chances are, they do too. So the important thing is to focus on their perspective: expose what they already knew. I could do this by, upon not seeing the Trello boards updated in the first thirty minutes, **asking them what they're currently doing**. When they answer, I'll acknowledge, say my thoughts, and then say **can you add that to the Trello board and stick your name on it?**.  

I probably need to read up on basic psychology to get it just right.  

## Lack of work/underachievement
I need to step back and look at the things that have slowed me down these past few weeks:  

**1. Dialogue system overscoping:** The dialogue system I was making had too many features. We really **need something on the screen**. Now that we're knee-deep into Unreal, I'll make sure I'm making something **presentable to the team** from now on.  
**2. Separate projects:** Oh man. Just **don't do them**. Keep it to one project next time.

# Achievements
## SVN
I've played a role in making sure everyone knows how SVN works. I made a channel in Slack, however I noticed **not many people read it**. There were many who **asked me how SVN works** despite all the information being there. I believe this is fine, perhaps just a lack of self-motivation on their part. Question is, **could I do more to encourage the team to read my tutorial(s)**?

## Hanging out
We really need to hang out more--I ntoice that we get to know each other best in **scenarios where we're not working**. And I feel it'd be great benefit to know each other, there's more motivation in pleasing people you know well than those you don't--not everyone is as **motivated by work as I am**, and furthermore that motivation very very much excludes Unreal.

# Journal
## Week 1 (29th Jan 2017)
This week summarised: I tried to finish developing my dialogue system, and had a headache trying to transfer it into Unreal. Learning Unreal is very slow--still don't know how to handle it. Noticing team attendance is wobbly. Trying to learn to become a scrum master and missing many vital elements.

## Week 2 (5th Feb 2017)
This week summarised: Managing tasks. Communicating more. Unreal headaches, and perhaps not communicating my own progress enough. Noting a lack of content showing--we need to showcase more.

Later on in this week I realised a scrum master is supposed to, or at least could keep more specific times that people came in. I was always wondering this, but was concerned it was too pedantic--apparently not, this is a working environment after all and stating whether someone was present at no particular time isn't specific enough!  

Started nagging people to update the Trello board a little more. It's still shaky, but I've noticed that a few members are updating me more often about their progress, which is fantastic.  

I'm still bowing under the pressure of Unreal. This week I was trying to merge the projects together into one but couldn't do so without errors from every direction. Even simply renaming a project is enough to make the system cry 'irreparable error'.  

Focus could be the problem, but honestly, maybe I should be seeking more help from the tutors. From a programming perspective, we're not being taught much useful about Unreal. We're not learning Unreal code or Blueprints so far. Even I'm not self-motivated enough to sit through those compile times and hours of headaches over doing simple tasks which I've literally made my own engine to handle in the past. Yet we need self-motivation to learn what we're doing. Props to Tomas for showing the most of it, and to the others for trying--while only some results have cropped up so far, I can see the thousand-yard stare of Unreal terror in their eyes.  

In the meantime, started to work on Arduino project on the weekend. It's fun! And perhaps taking too much of my time. But I love having the freedom to try exactly what I want.  

My personal life is alright. I want to get out more and meet people. On that topic, I note after the lecture today that it'd be a good idea to hang out with the team for more fun stuff as well. We benefit a ton from knowing each other more. I went out with Chris and Dary Saturday--it was great fun--and I think it's good to relax, enjoy ourselves and realise we're not stalking each other's trello activity 24/7.

## Week 3
Another week, another plethora of Unreal errors. On the bright side, I implemented and demonstrated the dialogue system (before it broke again). Meanwhile, I've been working on my Arduino project, building its engine and everything. This is on top of trying to be a better Scrum msater. To my credit, I've been nagging everyone about the Trello boards. However, I have room to improve when it comes to communicating stand-up times, and managing them.  

For the second sprint, I made a new meetings register. I noted a register mentioned on Slack that had a lot more detail, e.g. time in and time out, than the one I was doing previously. I've been largely keeping good track, though there have been occasions where I've forgotten to note down someone's leaving time and do it in retrospect.  

## Week 4
This week I implemented shield deflection into Demiurge. By showing this tangible gameplay I definitely **helped inspire** some of the team. While it's a small step, every bit of motivation counts. I hope to continue this trend of showing and inspiring.  

On Friday I made a small pong game. This was an online multiplayer game. While implementing network synchronisation, I decided to create a ControllerMessage type, which specified inputs from players. However, I quickly realised that since the logic was client-side, I was starting to **include state data with input data**. Also, I was **assigning** each element to the objects' variables when they sent and received them. This slowed production significantly.  

Next time in a game jam, I'll create 'state data' for online synchronisation. Each synchronised object will own an instance of this state data, which will inherit from a network message. Thus instead of needing to convert and copy everything when an update is received, a simple memory copy will do the trick. While suboptimal for the final online version, this is appropriate in the LAN-only 'skateboard' version of the product.  
