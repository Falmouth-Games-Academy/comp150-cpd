# COMP150 - Reflective Journal to Accompany My CPD Report
*You should reflect across the first 13 weeks of the course. This is the period from induction week to the Winter vacation. In your reflections, you should try to identify at least one challenge that you experienced and/or obstacle that you encountered that week. Consider which skills and/or characteristics that challenge/obstacle relates to.*  

*This will prove to be a considerable aid when you need to identify the most important areas of personal development in your report. Do try to keep up by completing an entry in the journal every week.*

## Notes
# Derp domain:
Time management, motivation, self-discipline  

# Affective domain:  
Capacity to be aware of, control and express emotions, and how to handle situations in a judicous and empathetic way.  

# Interpersonal domain:
Communication, listening, negotiation, problem-solving, decision-making and assertiveness  
Not everyone has perfect interpersonal skills. The vital skill is managing all people including these kind.  

# Cognitive domain:
Assessing the strengths and weaknesses of your approach to learning.  

As I noticed in the study, one of these things is reflecting on progress. This is mildly ironic. And generally speaking, if there is any case of irony wherein I am the one to call it ironic, it is ironic.  

# Procedural domain:
Identifying the skills you have, and what you need to improve. There is a GDC talk called How to Succeed, Fail and Learn worth watching.  

## Week 0 (September 18th 2017)
This week I participated in the Robot Olympiad. It was tough.

The first problem was a lack of task setting. At first, no one knew what to do, as one member took the robot and began independently piecing it together. This initiated an ongoing **lack of concurrent productivity as others wondered what to do.**  

The second problem was team communication. Many creative, technical, and practical suggestions made to him were shot down or debated hotly. **I lost motivation and felt useless.** He had predetermined what would work and what wouldn’t, and deflected all input.

I wanted to experiment and contribute. But **my interests weren’t of value to the team**. However, **the product still was.**

To counter this problem in the future, I will speak more confidently with a more product-focused approach. Teammates who don’t know each other have a common interest: the product. Next time I’m faced with a lack of contribution opportunity, I’ll **ask, ‘what do you want from this robot,’** followed by **‘then I’ll help with [x task]’**, where x is a useful non-blocking task and justifiable as I have no other assigned jobs. This direct form of communication should revive motivation and improve the product.

## Week 1 (September 25th 2017)
This week I worked in a team to produce a game concept. It was another disaster in team communication.

Following an initial conceptualisation session, which was bumpy as **we had no method to manage conflicting ideas**, the team parted ways **without sharing contact details.** This created a multitude of problems. When in a new team, **I will ensure contact is arranged before we part ways next time.**

I managed to recover the team by **creating a Discord server and creating shoutouts on Slack**. This and contact links between other members **slowly brought the team online.** After Nathan and Adrian first arrived, we arranged a studio meeting to solidify the designs, with success.

But during work period, **work wasn’t being done**, and when it was, **it wasn’t communicated**. There was **no workflow**, so in the weekend **I arranged a scrum workflow, but it was too late**, and **some members weren't aware**--they weren’t online. By Sunday I’d not only expended a lot of personal energy working on the specifications, but **was criticised for taking too much of the work.**

Much of this could have been avoided with better contact. Next time **contact details will be shared** and **an initial meeting arranged.**

## Week 2 (October 2nd 2017)
This week I worked solo to produce a game concept. I worked hard and was confident in the idea, but sadly it was unpopular across the board.

Let’s start off with the bad. **My time management was off point.** I spent too many hours trying to pass the SpaceChem assignment to a ‘professional’ level, hating every moment of it, falling short by one symbol. From now I will try to **prioritise work**, to favour **more productive or highly-marked assignments by doing those first.**

I had time to work all weekend on the concept. I went to the library to select a concept, develop the game in a quiet environment, and produce a decent amount of inspired work. **Moving to a new environment helped me stay focused** as I spewed my ideas onto calcium-carbonate-coated sheets of pure tree.

I can’t easily fix having outlandish and unpopular ideas, but I could try and **condense them more.** Unfortunately my feedback stated that a similar game already existed. Understandable, pure genius is usually fashionably late. However my pitch went overtime, which I could mitigate by **rehearsing**, which I could do by **not spending hours aggressively mashing SpaceChem particles**, so I have more time left.

## Week 3 (October 9th 2017)
This week I worked with Tomas on pair programming. It’s going fine, but internally it's rough due to my extensive experience. It tests my patience--I must always slow down.

This introduced the first issue - **stressing him out.** I correct mistakes very quickly. Repeatedly correcting him, though constructively and with rationale, **probably affected his confidence.** He sometimes seemed tired, uncomfortable or quiet. Meanwhile **I’m conscious of hindering his hands-on learning** when giving the answers, or being patronising and unhelpful when allowing him his own time to work something out. I get stressed out too.

But **we get along well.** He explained he beats himself up over things like that. Working under the critical eyes of someone more experienced must be hard, unless they’re a teacher. On the bright side, I’m **learning more about expressing critique** and he is **learning more about code**. Recently he is **correcting me on my mistakes** more than before, which means he’s getting experience, and that I’m approachable to him, which makes me more comfortable.

How to improve: take **more regular breaks** during studio practice. Evidently, we can work together, but **stress is sometimes too high.** Take a 10-min break per 45-mins, go outside, chat, coffee.

## Week 4 (October 16th 2017)
This week we kicked off some actual development. **The team’s good.** I'm confident. We gonna make sum gamez!

**Timekeeping has been good.** We all know when we’re meeting up and the meetings have happened on time with no absences. Stand-ups ensure we all play a part.

Negotiating with Beren however is a challenge--we have differences in opinions with the code. Vitally he **sometimes changes my and Tomas’ code without a review.** Granted, he has taken the responsibility of bringing the code modules together, but I'm precious about code, and while his rationale is often strong--and I’ve adapted accordingly--**some of the modifications were undue,** possibly unnecessary. My rationale isn’t always smart, but that's for the team to decide during review. I expect **this’ll also result in merge conflicts.** I raised my concerns on the spot but haven’t convinced him. As I continue working to avoid wasting time, **I’m failing to convey my viewpoint to the team.**

I plan to **discuss this at the next contractor meeting.** My goal is to **clarify and ensure we have a proper review strategy** in place that favours a team consensus on coding choices. I'll also emphasise my **discomfort in my code being changed without permission.**

## Week 5 (October 23rd 2017)
This week I worked with my team to develop Frontier. It went well! Too well! Development was on time, and the sprint goal of having a cohesive central app structure was achieved in one day.  

So since I communicated well and managed my time successfully(!?) this week, let's look at my programming skills! While I'm learning several things about Python, one of the things I've noticed is that **Python class variables of class types don't work as I expect**. Specifically, creating a collision parameter class in the variable definitions makes one that is **shared across all instances**! I fixed this by **updating Object.__init__ to instantiate one**.  

However, this introduces a new concern. **New object types require this instantiation.** I **haven't informed the team** yet; this will cause crash bugs if they try to implement new classes and forget about the params (which even I do!). I have considered remedying this by **providing a shared default value**, but that could be **accidentally changed**. Therefore **a crash is actually preferred behaviour**, as it informs programmers of their mistake. Instead I will add a reminder into the skeleton.py file immediately and ensure the team knows of it in the next standup.

## Week 6 (October 30th 2017)
What began as a game week soon turned into an essay week. What went well was that I did **self-motivated work in the studio** every weekday. After the team efforts started to slow down, I used the time to work on my agile essay. According to my research self-motivated work, especially in a group, is usually the most beneficial to learning. Score!  

Something that gave me a massive headache **sprite rotation in pygame**. The nature of its sprite rotation is extremely weird; create a 32x32 image, put a dot in a corner, rotate it and watch the crazy path that dot takes in what should intuitively be a simple circle. I **spent hours** on that, including one which probably left Tomas with nothing to do. I feel bad for that, and **shouldn't have focused so much on it**.  

I know I need to **reduce my focus** on things to leave room for others. I wrote this entry retrospectively after Week 7 where it was also a concern. I can't think of a smart goal for it--this is probably one of my autistic traits and nobody's cured autism just yet--but I raise my full awareness.  

## Week 7 (November 6th 2017)
This week was essay week: the sequel. It's so hard to tell what went right; from that I already know what went wrong. Perhaps what went right was the **attempted application of tasksetting** while working in the library on the essays. I used Trello to set up reviews and updates for the agile essay; this process was helpful in revision.  

What went wrong: **focus**. I'm **too focused** on the essays before review, revising every paragraph several times while asking myself why I'm doing it. The marks will be useful, but are nothing more than critique. Furthermore, I could be working on the group game, programming the Lego robot, or preparing my 3D modeller for release. I'm racing towards a constantly moving qualitative finish line never knowing if I'm passing enough checkpoints.  

To improve, I shall **continue panicking** helplessly. I'll see if my heavy focus on my research question impacts the agile essay and if the structure of my computing essay is considered harmful--til then, they are qualities that are good in my eyes. I **will adjust accordingly** for my next essays depending on the feedback I get, **as soon as I get it**.  

## Week 8 (November 13th 2017)
Essay submission week! So fun!!!

And now for something entirely different: **peer review skills!** Turns out I write thorough feedback to help the writer improve. The problem is **I don't have enough time** to go through the whole rubric. It's expected that if I can't review 10 1000-word essays to 9 criteria of 6 competency levels each whilst giving constructive feedback in three hours, I'm not doing them fast enough. I'm a slow reader and interpreter, so **this is stressful**. I could be less thorough, but feel this would not be conducive to helping a peer develop.  

On the bright side, **I identified several flaws** in my work with others' feedback, and rewrote large portions.  

I have no SMART goal, but propose a SHART one (h is for 'heuristic'): to peer review my own work regularly with the rubric and Notepad. I will do this for each section of an assignment or report once it's drafted, and rinse and repeat after revising. This should help me identify more strategies for speeding up the peer review process whilst improving the work itself. I don't have a specific time goal--I only want to provide the most useful feedback.  

## Week 9 (November 20th 2017)
This week we finalised the game project and pitch. 

Overall, active progress on the game was good. I made sure to be available in the mornings to work on the combat system where I successfully implemented **a baseline collision system**. I took a **less precise approach** with regards to time, which I feel is a good thing as it **resulted in a tangible game feature** rather than the building blocks.  

However, the pitch fell behind. Planning of the pitch was poor--we never **established a team workflow for it**. Ryan and Scott offered to do it, but this was insufficient; we need to know what each of us will cover, and create the slides accordingly. As time started running out, Mango and I got online to continue Scott's work, with some more work left for the others the next day. This was successful overall, but not to a high standard.  

Should a pitch project arise again, I will **ensure we have a team workflow and deadlines for the pitch** by asking everyone what part they wish to do, until a proper decisive discussion is sparked. I will play the passive role of raising awareness of the impending team process.

## Week 10 (November 27th 2017)
This week, Mango and I finished our Tinkering Audio project. It was pretty great! We didn't quite reach the stretch goals we wanted to, mostly due to lack of time, but we submitted a functional program. Sadly, we never got around to adding an interface showing *why* we used colours to represent sound transformations. We were shooting for creative flair with that one, but without context, the joke may lead to confusion for the user.

A blend of time management and interpersonal skills were the issue there. To achieve the vision we had near the end of the project, we needed to dedicate more time to it. However, who else is so fussed as me? While I would've liked to over-dedicate to the project, I didn't force that on Mango. We struck a good balance with good communication, but could perhaps improve by finishing the project further in advance of the deadline. That way we could add the funnier parts in a whole day.

Next time: I'll get us to try to finish the assignment a week in advance by telling my partner 'Hey, wanna finish the assignment next week instead of the week after?'

## Week 11 (December 4th 2017)
This week, my team and I began conceptualising. Meanwhile, I started Unreal. Unreal is slow as heck. But I’m finally **grasping the concepts** of a professional game engine in my favourite language, C++: I’m finally gaining some kind of industry-standard knowledge. I hate templates though. They’re fantastic, but the compile times are insane.  

Reintroducing the interpersonal domain: so **ideas aren’t flying**. The first team meeting was alright, but I strongly felt there was **a lack of cohesion**. We don’t really know each other or our strengths and tastes. This is normal, but we don’t need to settle for normal. I know I could play a stronger role in this: while I contributed ideas in a fair share, there’s so little inspiration. I feel this is a flaw for the team that won’t resolve automatically. Overall they seem just ‘alright’ with the project.  

As an aspiring team leader, I have a goal to inspire creativity. We won’t get creative until we’re more comfortable with each other. I’ll try making a poll.
\[TO FINISH\]

## Week 12
This week, my team and I presented the game pitch. Oh boy. Straighten your ties, team! Oops, we don’t have the ties. Oops, we don’t have the team!!  

I reflect on Week 9, as once again we tried to finish off the presentation hours before the pitch. Thankfully, we **did establish a workflow**. While many team members didn’t show up ‘til later in the day, the pitching experience was more successful than our last. We BScs and Maria, eventually followed by James, Louis and the others, pulled together the pitch taking as many pages as needed. Among the challenges was **knowing who was going to say what**. This was a fairly familiar workflow issue. I think it could have been avoided if we **started it sooner** although aligning everyone to the same schedule is a **noteworthy challenge**.  

But the pitch was successful: we somehow **coordinated speaking parts for all of us**. Thinking retrospectively, that is a really good sign. If only we could coordinate our creativity a little more.
