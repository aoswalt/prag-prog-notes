# Notes from Pragmatic Programmer 20th Anniv Ed

## Preface to the Second Edition

To save time with new clients, we started jotting down notes. And those notes became The Pragmatic Programmer

20 years has had no impact whatsoever on common sense. Technology may have changed, but people haven't. Practices and approaches that were a good idea then remain a good idea now

### How the Book Is Organized

This book is written as a collection of short topics. Each topic is self-contained, and addresses a particular theme. You'll find numerous cross references, which help put each topic in context. Feel free to read the topics in any order—this isn't a book you need to read front-to-back

### What's in a Name?

Sometimes, there are perfectly good jargon words for concepts, words that we've decided to ignore

### From the Preface to the First Edition

Programming is a craft. At its simplest, it comes down to getting a computer to do what you want it to do (or what your user wants it to do). As a programmer, you are part listener, part advisor, part interpreter, and part dictator. You try to capture elusive requirements and find a way of expressing them so that a mere machine can do them justice. You try to document your work so that others can understand it, and you try to engineer your work so that others can build on it. What's more, you try to do all this against the relentless ticking of the project clock. You work small miracles every day

There is no best solution, be it a tool, a language, or an operating system. There can only be systems that are more appropriate in a particular set of circumstances

This is where pragmatism comes in. You shouldn't be wedded to any particular technology, but have a broad enough background and experience base to allow you to choose good solutions in particular situations

### What Makes a Pragmatic Programmer?

Each developer is unique, with individual strengths and weaknesses, preferences and dislikes

You try to understand the underlying nature of each problem you face

think about what you're doing while you're doing it

it's an ongoing critical appraisal of every decision you make, every day, and on every project

Never run on auto-pilot. Constantly be thinking, critiquing your work in real time

This is going to take up some of your valuable time—time that is probably already under tremendous pressure

Over the long term, your time investment will be repaid as you and your team become more efficient, write code that's easier to maintain, and spend less time in meetings

### Individual Pragmatists, Large Teams

There should be engineering in software construction. However, this doesn't preclude individual craftsmanship

craftspeople, interpreting the engineering requirements to produce a whole that transcended the purely mechanical side of the construction

### It's a Continuous Process

Great lawns need small amounts of daily care, and so do great programmers

Every day, work to refine the skills you have and to add new tools to your repertoire

## Chapter 1: A Pragmatic Philosophy

This book is about you

Pragmatic programming stems from a philosophy of pragmatic thinking. This chapter sets the basis for that philosophy

### Topic 1: It's Your Life

"you can change your organization or change your organization." (privilege)

### Topic 2: The Cat Ate My Source Code

We can be proud of our abilities, but we must own up to our shortcomings—our ignorance and our mistakes

#### Team Trust

Above all, your team needs to be able to trust and rely on you—and you need to be comfortable relying on each of them as well

#### Take Responsibility

Don't blame all the problems on a vendor, a programming language, management, or your coworkers. Any and all of these may play a role, but it is up to you to provide solutions, not excuses

Telling your boss "the cat ate my source code'' just won't cut it

Instead of excuses, provide options. Don't say it can't be done; explain what can be done to salvage the situation

#### Challenges

When you find yourself saying, "I don't know," be sure to follow it up with "—but I'll find out." (including a reasonable guess is good)

### Topic 3: Software Entropy

When disorder increases in software, we call it "software rot."

Some folks might call it by the more optimistic term, "technical debt," with the implied notion that they'll pay it back someday. They probably won't (tech investments)

Whatever the name, though, both debt and rot can spread uncontrollably

The most important one seems to be the psychology, or culture, at work on a project

One broken window, left unrepaired for any substantial length of time, instills in the inhabitants of the building a sense of abandonment—a sense that the powers that be don't care about the building

hopelessness can be contagious

Ignoring a clearly broken situation reinforces the ideas that perhaps nothing can be fixed, that no one cares, all is doomed

Don't leave "broken windows'' (bad designs, wrong decisions, or poor code) unrepaired. Fix each one as soon as it is discovered

Take some action to prevent further damage

neglect accelerates the rot faster than any other factor

thinking that no one has the time to go around cleaning up all the broken glass of a project. If so, then you'd better plan on getting a dumpster

#### First, Do No Harm

roll out a mat between the front door and the source of the fire. They didn't want to mess up the carpet

don't cause collateral damage just because there's a crisis of some sort. One broken window is one too many

where the code is pristinely beautiful—cleanly written, well designed, and elegant—you will likely take extra special care not to mess it up

Just tell yourself, "No broken windows."

### Topic 4: Stone Soup and Boiled Frogs

the soldiers act as a catalyst, bringing the village together so they can jointly produce something that they couldn't have done by themselves

Work out what you can reasonably ask for. Develop it well. Once you've got it, show people

People find it easier to join an ongoing success

#### The Villagers' Side

Keep an eye on the big picture. Constantly review what's happening around you, not just what you personally are doing

#### Challenges

Can you determine whether you're making stone soup or frog soup when you try to catalyze change?

### Topic 5: Good-Enough Software

the real world just won't let us produce much that's truly perfect, particularly not bug-free software. Time, technology, and temperament all conspire against us

you can discipline yourself to write software that's good enough—good enough for your users, for future maintainers, for your own peace of mind

The phrase "good enough'' does not imply sloppy or poorly produced code

users be given an opportunity to participate in the process of deciding when what you've produced is good enough for their needs

#### Involve Your Users in the Trade-Off

Often you'll remember to find out what they want.[8] But do you ever ask them how good they want their software to be?

The scope and quality of the system you produce should be discussed as part of that system's requirements

many users would rather use software with some rough edges today than wait a year for the shiny, bells-and-whistles version

Great software today is often preferable to the fantasy of perfect software tomorrow

If you give your users something to play with early, their feedback will often lead you to a better eventual solution (part of the idea of standalone live branches)

#### Know When to Stop

If you add layer upon layer, detail over detail, the painting becomes lost in the paint.

Don't spoil a perfectly good program by over-embellishment and over-refinement. Move on, and let your code stand in its own right for a while. It may not be perfect

### Topic 6: Your Knowledge Portfolio

Your knowledge and experience are your most important day-to-day professional assets. Unfortunately, they're expiring assets

Your ability to learn new things is your most important strategic asset

#### Your Knowledge Portfolio

We like to think of all the facts programmers know about computing, the application domains they work in, and all their experience as their _knowledge portfolios_

make yourself do it initially and form a habit. Develop a routine which you follow until your brain internalizes it

#### Building Your Portfolio

* Invest Regularly

  you must invest in your knowledge portfolio regularly, even if it's just a small amount

* Diversify

  The more different things you know, the more valuable you are

  The more technologies you are comfortable with, the better you will be able to adjust to change. And don't forget all the other skills you need, including those in non-technical areas

* Manage Risk

  Technology exists along a spectrum

  Don't put all your technical eggs in one basket

* Buy Low, Sell High

  Learning an emerging technology before it becomes popular can be just as hard as finding an undervalued stock, but the payoff can be just as rewarding

* Review and Rebalance

  This is a very dynamic industry

#### Goals

* Learn at least one new language every year

  Different languages solve the same problems in different ways. By learning several different approaches, you can help broaden your thinking and avoid getting stuck in a rut

* Read a technical book each month

  for deep understanding you need long-form books

* Read nontechnical books, too

  computers are used by people

  Don't forget the human side of the equation, as that requires an entirely different skill set

* Participate in local user groups and meetups

  Isolation can be deadly to your career

* Experiment with different environments

  Linux vs Windows, IDE vs simple editor

* Stay current

  Read news and posts online on technology different from that of your current project

It doesn't matter whether you ever use any of these technologies on a project, or even whether you put them on your resume. The process of learning will expand your thinking, opening you to new possibilities and new ways of doing things

Even if your project doesn't use that technology, perhaps you can borrow some ideas

#### Opportunities for Learning

Take it as a personal challenge to find the answer

Always have something to read in an otherwise dead moment (Pocket is good for this)

#### Critical Thinking
_think critically_ about what you read and hear. You need to ensure that the knowledge in your portfolio is accurate and unswayed by either vendor or media hype

Critical thinking is an entire discipline unto itself

* Ask the "Five Whys"

  A favorite consulting trick: ask "why?" at least five times

  You might be able to get closer to a root cause this way

* Who does this benefit?

  follow the money can be a very helpful path to analyze

* What's the context?

  Everything occurs in its own context, which is why "one size fits all" solutions often don't

  "best practice." Good questions to consider are "best for who?"

* When or Where would this work?

  Don't stop with first-order thinking (what will happen next), but use second-order thinking: what will happen after that?

* Why is this a problem?

  Is there an underlying model?

### Topic 7: Communicate!

Having the best ideas, the finest code, or the most pragmatic thinking is ultimately sterile unless you can communicate with other people

A good idea is an orphan without effective communication

We write code, which communicates our intentions to a machine and documents our thinking for future generations of developers

Treat English (or whatever your native tongue may be) as just another programming language. Write natural language as you would write code: honor the DRY principle, ETC, automation, and so on

#### Know Your Audience

You're communicating only if you're conveying what you mean to convey—just talking isn't enough

You can present this update in many different ways, depending on your audience

By making the appropriate pitch to each group, you'll get them all excited about your project

As with all forms of communication, the trick here is to gather feedback

Don't just wait for questions: ask for them. Look at body language, and facial expressions

#### Know What You Want to Say

Plan what you want to say

"Does this communicate what I want to express to my audience in a way that works for them?" Refine it until it does.

#### Choose the Moment

As part of understanding what your audience needs to hear, you need to work out what their priorities are

Make what you're saying relevant in time, as well as in content

#### Choose a Style

Adjust the style of your delivery to suit your audience

If in doubt, ask

you are half of the communication transaction. If someone says they need a paragraph describing something and you can't see any way of doing it in less than several pages, tell them so

#### Involve Your Audience

the documents we produce end up being less important than the process we go through to produce them

#### Be a Listener

one technique that you must use if you want people to listen to you: listen to them

Encourage people to talk by asking questions, or ask them to restate the discussion in their own words

#### Get Back to People

Keeping people informed makes them far more forgiving of the occasional slip, and makes them feel that you haven't forgotten them

#### Documentation

documentation as an integral part of the overall development process

restrict your non-API commenting to discussing why something is done, its purpose and its goal

document those elusive bits of a project that can't be documented anywhere else: engineering trade-offs, why decisions were made, what other alternatives were discarded, and so on
