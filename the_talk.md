The Talk v2
===========

# INTRO

* Joe Wright. TL. Confess.... Confess to my sins. Avoid my transgressions.
* Have you ever? Deploy. Arch Understanding. 10 coders opinions


## PATTERNS

* I haz dev patterns: Test, CI, App down
* Don't have these lead paths. Stackoverflow failed me. I don't have the pattern to pull off the shelf.


## QUOTE (Alfred)

* My Goal is this quote.
* Situations with no pattern. What I did, What I learnt
* Please grab me and help me afterwards

>> but first, same page


## TECH LEAD WHAT IS?

* Write down 3 things.

>> pat kua, colleague


## TECH LEAD VENN

* Leadership, Developer, Architect
* Dev: Hands on. Emphasis. How much?
* Lead: Feedback. Motivate. Build relationships. Resolve conflict.
* Arch: Hands on. Deployment. CFRs. Start an Evolve.


## TECH LEAD CODA

* Distill
* Need dev principles & practices (TDD, Refactoring). Not the best coder -> Understand value.
* Everyone on the same page. Make decisions
* CFRs: deployment context, customer context, organisation context

>> That said, #1 source of my problems, BRAIN "this hasn't happened before, what to do?"


## PEOPLE

* All problems are people problems. True. Dev a lot are tech problems.
* Never had an opinion on.
* No patterns.
* Exposure to this world. Sympathy for old tech leads.


## QUOTE (Pratchet)

* Summarising how it feels in hindsight

>> Onwards. With Sit #1


## Sitatuon #1 TO CODE OR NOT TO CODE

SIT: All code -> problem with stakeholder (deploy world changed).
     Hands off -> No Code. Cannot resolve conflicts, or ensure vision.

* Lose respect or fail stakeholders.
* 30%
* Respect is the currency. How easy you are.
* Lose respect by hoarding the interesting work.

>> One key skill for 30%


## DELEGATION

* Share out the responsibility. People are eager to pick up interesting bits of work.
* How to start? Diary. LB fix issue. Writing stories with BAs
* Feature Leads: Share your vision. Care about hard to change decisions, like external API.
* Bring a dev to meetings
* Focus on principles, not the impl


## Situation #2 I MUST CHOOSE ONE STYLE OF LEADERSHIP

SIT: Self organising team (support, coach). Works for some people, some of the time. But others felt left out or overly watching.

* Different people need different things
* People are seeds. How can you create the env?
* Some people need to be told exactly what to do


## SITUATIONAL LEADERSHIP MODEL

* 4 styles applied to context
* Figure out the task and skills of the person
* Direct: Junior members. Very enthusiastic, lack skills -> DIRECT
* Got skill, but uncomfortable -> COACH
* Competant, but need motivation to do it (talking to unsavoury folk) -> SUPPORT
* High skill & motivation -> DELEGATE

>> Cavet

## QUOTE (Box)

* Does is help? Assume not unniversal


## Situation #3 THE STANDUP CONFRONTATION

SIT: 3 days to document CI. Stare. I wonder if we can get the value another way. Ambigious. They spent a day doing it anyway.
     Day later I sat down and went through their issues.

>> Key learning points


## QUOTE (Berkun)

* They were feeling like they weren't contributing enough. Want to understand everything.
* Improvement idea. Encourage.


## Situation #4 THE BLIND PAIR

SIT: 2 devs, 3 days -> 4 days. Complex. Concerened. Kept changing the complex, not considering options. Gave up, take a break.

* Don't use statements, ask questions. CI is wrong, concerened about knowing if it works. 
* Socratic method: What are our options? How will this impact on X? What happens if we encounter Y?

SIT: 2 hours later. Complete change. Asked same questions.

* Failure. Learning experience which saved us. We could see into the future.


## QUOTE (Rob)

* Learn off code. Don't be afraid to say no.


## Situation #5 THE SHINY THING

SIT: Rewrite perf test in a Scala framework. Perf tests well established.

* Tension: Improvement vs Consistency. Suitable amount helps prod, too much kills innovation.


## QUOTE (Tzu)

* Two sides of the same coin. Innovation destroys the previous way of working
* How to decide? Does it improve the rest of the org.
* Improvment backlog: Lean thinking.
* RabbitMQ. Replaced batching with eventing.


## Situation #6 THE GRAD DECISION

SIT: Consultancy, 6m-1y, swap normal. 2 weeks in.

* Tension: Experience vs Diversity
* Take the best?
* Delay, spend time pairing. Enthusiasm, energy & desire to learn.
* Wasn't just that, it was the cultural impact. Pessimistic left.
* Crystal ball: I wonder. Client impact, grad->dev

>> Should you take a grad?


## Quote (depends)

* Stength of your team.
* Every change is a new team.
* It's about Culture.


## Situation #7 FORGETTING ABOUT YOURSELF

SIT: You spend all your time with others. No time to think to yourself.

* Reflect on what is going on
* Inundated with calls. Leaves you reactionary, as you cannot deal with everything.
* Set aside time: block calendar, book a room, WFH
* Think about smells you are seeing. The CFRs no one else is thinking about.
* Diary -> Where this talk came from


## FINAL

* Good decisions
* Use different leadership depending on the context
* Look after yourself. Keep a diary and reach out.

THANKS!






















The Talk v1
===========

# INTRO

 Have you ever worked on a project where....
 No one thought about how you were going to deploy it until a week before go live?
 There was no shared understanding of the architecture of an application?
 Where all the devs had conflicting opinions, all expresssed in the same code base?

Me too. Over the last year I've been looking to improve these situations. 

As a developer we have a catalogue of practices and patterns we can use when we encounter the majoriity of problems we see in our industry.

When I started being a TW tech lead last year I quickly realsied that I didn't have a set of patterns I could use for all these new situations that I was expected to resolve. I was left thinking on my feet. But I was determined to learn and improve on this.

Learn all you can from the mistakes of others. You won't have time to make them all yourself. ~Alfred Sheinwold

During this talk I'll tell you about the problems I faced without knowing what to do next. You can decide what you might do in the same situation, and please grab me afterwards and let me know. But for the next 35 minute I'll let you know with heinsight what I would do now.

>>>> But first. Let's make sure we are on the same page with regard to what a tech lead is.

## Tech lead background: 
 * If we wrote down the top 3 things they cover, not one of us would have the same answers
 * We've all seen different approaches to tech leadership. I agree with Pat Kua that an effective tech lead needs to concentrate on three core areas:
 * Pat Kua - circles of responsibility
 * A developer, A leader and an Archtect
 * Dev: You have to get hands on to earn respect. I'd expect a tech lead to have a really good grasp of practices and also still be keeping their hands in the code
 * Leader: Must be able to give feedback (to help develop and become more effective), not just tech: motivational, relationship building, delegating, influencing. Resolve conflict (healthy, but cannot stay in that state). 
 * Arch: TL is a hands on architect. Tech leads need to "Build systems - not software". CFRs. Deployment, how long it will last and evolve.

Engender the tech vision. Champion cross functional attributes.  Build systems - not software. Focus on principles not impl.

>>>>  So now we're all in agreement. Let me tell you the number one cause of situations where I was left flat footed

## People (Problems)

* Things you never had an opinion on you now have to
* I do not have a pattern to solve these problems
* Compassion for the folk that had to lead me in the past

>>> So, no more fan fare, here's the problems that I was put in, I'll let you know what I did and what I'll probably do next time

“Wisdom comes from experience. Experience is often a result of lack of wisdom.” ― Terry Pratchett

# Situations 




## To code, or not to code?

The Situation: Just made tech lead, did the same + meetings. Things started going off. Went off code entirely. Lost respect of the team.

* No code? Too much Code? (lose respect - a manager, fail at your job)
* Respect is the currency of the tech realm
* Code at least 30% of the time

# Delegate

* Delegate by Diary (like performance problems, it ain't where you think it is))
* Feature leeds.
* Ask people to come to the team rather than email. Use a concierge.
* Bring a team member to all meetings, so you can delegate in the future
* Work out which issues will have the most impact, and so which would provide the most value by being resolved.

* Focus on principles not implementations




## I should choose an approach and treat everyone the same.

The situation: Let's treat everyone the same. Encourage a self-organising team, just get involved when things veer off course. This ends up with devs stuggling for 5 days. Or 

* Every dev is like a seed, you need to figure out how to create the right environment for them to flourish
* Is it ok to tell people what to do? Yes Sometimes.

## Situational Management Theory

* You need to know the task and the skills of hte person
* Grads are enthusiastic. Need direction
* Folk with a skill, not comfortable. COACH
* Competenace, need to know why it is importnat: SUPPORT
* high competenace, high commitement: DELETGATE








## The standup confrontation

The situation: You are running your standup, you ask for an update on an item. Dev demands 3 days off to document the CI process. All eyes set on you. What do you do?

* Diffuse, don't feel presurred to make decisions and argue in groups unexpectedly
* Understand what the need is.

* Document all the things? Document the edges. Document at different levels.
* Many alternatives to documentation.
* Documents are like bannas, they go off.

"The realization that everyone is different when you talk to them alone is a secret to success in life. … The mystery for why some people you know succeed or fail in life is how courageous they are in pulling people aside and how effective they are in those private conversations we never see." - Scott Berkun





## The emotionally blinded pair and the architect
 
The situation: You've given two of your devs 4 days to prove out how to solve an icky problem. The solution is overly complex but works. Evertyhing in you says you are concerned. But they refuse to discuss the negatives and concenrtrate on variations of the same problem. Bonus, your lead architect likes the direction too.

* Mel advice. Don't make statements, ask questions.
* Socratic method: What are our options? How will this impact on X? What happens if we encounter Y?
* Take a break. Emotions come quick, and go quick.
* "Avoiding giant holes in the ground is better than climbing up mountains" - Rob Lally
* Priase the original idea
* Visible relief

* Make a list. It's less stressful when it's written down and prioritized
* The people above are emotional too. Give them just enough info.





## The Shiny thing

The situation: The new dev wants to rewrite your test suite in another tool which other teams aren't using.

* Innovation vs Consistency
* A suitable amount of standardisation helps productivity. Too much standardisation kills innovation.
* "We allow innovation on teams, provided it is onnovation that is possible to be reused on other teams" - Stuart Skinner
* Cretion and Destruction are two sides of the same coin.
* We should eliminate useless traditions and introduce new valuable ones. An org where nothing eever changes is not a wirkplace byt a living museum
* Priotization: Lean thinking. This has value, but is it more valuable then the next improvment option?





## The Grad decision 

The situation: Headline. You've just bedded in a grab. You can get a better person.

* Experience vs Diversity
* The team was acting quite conservative about practices and it's outlook
* I want the best I can get to make it easier for me.
* Asked my supriors who didn't quite give a clear answer.
* Team delivering. What would you do?
* Spent a day pairing. Some concerns, but seemed to have the right mindset.
* Take the best person you can get factoring in skill, experience, energy & ability to learn quickly.
*  Hire young for enthusiam, energy and desire to learn.
* Depends on the stength of the team. Not sharing is a liability.





## Look after yourself

The Situation: You spend all your time on everyone else, that you start neglecting your own issues.

* Easy to become reactionary
* Make time for youself. You can feel inudated.
* You cannot deal with everything. You need to spend time thinking.
* What smells am I seing. What can I do?
* Set aside planning time. Sit in a room on your own.
* Book out a room. Block out a calendar section. WFH.
* What are the things that no one else is thinking about?
* Lonely. No feedback at the same level.




# WRAPUP

3 bits of advice?

* Keep an experiences diary. Reach out to your network.
* Leadership changes in every context and with each person in that context. Treat each situation as unique.
* Look after yourself, no one else is going to think about the big picture items

Thank you.



http://www.quotegarden.com/wisdom.html



