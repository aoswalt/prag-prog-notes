# Notes from Pragmatic Programmer 20th Anniv Ed

## Preface to the Second Edition

To save time with new clients, we started jotting down notes. And those notes became The Pragmatic Programmer

20 years has had no impact whatsoever on common sense. Technology may have changed, but people haven't. Practices and approaches that were a good idea then remain a good idea now

### How the Book Is Organized

This book is written as a collection of short topics. Each topic is self-contained, and addresses a particular theme. You'll find numerous cross references, which help put each topic in context. Feel free to read the topics in any order - this isn't a book you need to read front-to-back

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

This is going to take up some of your valuable time - time that is probably already under tremendous pressure

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

We can be proud of our abilities, but we must own up to our shortcomings - our ignorance and our mistakes

#### Team Trust

Above all, your team needs to be able to trust and rely on you - and you need to be comfortable relying on each of them as well

#### Take Responsibility

Don't blame all the problems on a vendor, a programming language, management, or your coworkers. Any and all of these may play a role, but it is up to you to provide solutions, not excuses

Telling your boss "the cat ate my source code'' just won't cut it

Instead of excuses, provide options. Don't say it can't be done; explain what can be done to salvage the situation

#### Challenges

When you find yourself saying, "I don't know," be sure to follow it up with " - but I'll find out." (including a reasonable guess is good)

### Topic 3: Software Entropy

When disorder increases in software, we call it "software rot."

Some folks might call it by the more optimistic term, "technical debt," with the implied notion that they'll pay it back someday. They probably won't (tech investments)

Whatever the name, though, both debt and rot can spread uncontrollably

The most important one seems to be the psychology, or culture, at work on a project

One broken window, left unrepaired for any substantial length of time, instills in the inhabitants of the building a sense of abandonment - a sense that the powers that be don't care about the building

hopelessness can be contagious

Ignoring a clearly broken situation reinforces the ideas that perhaps nothing can be fixed, that no one cares, all is doomed

Don't leave "broken windows'' (bad designs, wrong decisions, or poor code) unrepaired. Fix each one as soon as it is discovered

Take some action to prevent further damage

neglect accelerates the rot faster than any other factor

thinking that no one has the time to go around cleaning up all the broken glass of a project. If so, then you'd better plan on getting a dumpster

#### First, Do No Harm

roll out a mat between the front door and the source of the fire. They didn't want to mess up the carpet

don't cause collateral damage just because there's a crisis of some sort. One broken window is one too many

where the code is pristinely beautiful - cleanly written, well designed, and elegant - you will likely take extra special care not to mess it up

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

you can discipline yourself to write software that's good enough - good enough for your users, for future maintainers, for your own peace of mind

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

You're communicating only if you're conveying what you mean to convey - just talking isn't enough

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

## Chapter 2: A Pragmatic Approach

certain tips and tricks that apply at all levels of software development, processes that are virtually universal, and ideas that are almost axiomatic

### Topic 8: The Essence of Good Design

Good Design Is Easier to Change Than Bad Design

A thing is well designed if it adapts to the people who use it. For code, that means it must adapt by changing

ETC principle: Easier to Change

#### ETC Is a Value, Not a Rule

Deliberately ask yourself "did the thing I just did make the overall system easier or harder to change?"

Much of the time, common sense will be correct, and you can make an educated guess

You can always fall back on the ultimate "easy to change" path: try to make what you write replaceable

It's what you should be doing all the time, anyway. It's really just thinking about keeping code decoupled and cohesive

Note the situation in your engineering day book: the choices you have, and some guesses about change. Leave a tag in the source. Then, later, when this code has to change, you'll be able to look back and give yourself feedback

### Topic 9: DRY - The Evils of Duplication

maintenance is not a discrete activity, but a routine part of the entire development process

the DRY principle: Every piece of knowledge must have a single, unambiguous, authoritative representation within a system

It isn't a question of whether you'll remember: it's a question of when you'll forget

#### DRY Is More Than Code

"don't copy-and-paste lines of source." That is part of DRY, but it's a tiny and fairly trivial part

DRY is about the duplication of knowledge, of intent. It's about expressing the same thing in two different places, possibly in two totally different ways

##### Not All Code Duplication Is Knowledge Duplication

The code is the same, but the knowledge they represent is different. The two functions validate two separate things that just happen to have the same rules. That's a coincidence, not a duplication

##### Duplication In Documentation

The intent of this function is given twice: once in the comment and again in the code

Ask yourself what the comment adds to the code. From our point of view, it simply compensates for some bad naming and layout

##### DRY Violations in Data

whenever a module exposes a data structure, you're coupling all the code that uses that structure to the implementation of that module

#### Representational Duplication

some kind of DRY violation: your code has to have knowledge that is also present in the external thing

##### Duplication Across Internal APIs

For internal APIs, look for tools that let you specify the API in some kind of neutral format

##### Duplication Across External APIs

public APIs are documented formally using something like OpenAPI

##### Duplication with Data Sources

There's another option, and one we often prefer. Rather than writing code that represents external data in a fixed structure (an instance of a struct or class, for example), just stick it into a key/value data structure (your language might call it a map, hash, dictionary, or even object). On its own this is risky: you lose a lot of the security of knowing just what data you're working with. So we recommend adding a second layer to this solution: a simple table-driven validation suite that verifies that the map you've created contains at least the data you need, in the format you need it. Your API documentation tool might be able to generate this

What you're trying to do is foster an environment where it's easier to find and reuse existing stuff than to write it yourself

#### Interdeveloper Duplication

If it isn't easy, people won't do it

### Topic 10: Orthogonality

#### What Is Orthogonality?

Two or more things are orthogonal if changes in one do not affect any of the others

#### Benefits of Orthogonality

When components of any system are highly interdependent, there is no such thing as a local fix

We want to design components that are self-contained: independent, and with a single, well-defined purpose

As long as you don't change that component's external interfaces, you can be confident that you won't cause problems that ripple through the entire system

You get two major benefits if you write orthogonal systems: increased productivity and reduced risk

##### Gain Productivity

there is no need to keep changing existing code as you add new code

If components have specific, well-defined responsibilities, they can be combined with new components in ways that were not envisioned by their original implementors. The more loosely coupled your systems, the easier they are to reconfigure and reengineer

You get more functionality per unit effort by combining orthogonal components

##### Reduce Risk

If a module is sick, it is less likely to spread the symptoms around the rest of the system

Make small changes and fixes to a particular area, and any problems you generate will be restricted to that area

easier to design and run tests on its components

interfaces to these third-party components will be isolated to smaller parts of the overall development

#### Design

Systems should be composed of a set of cooperating modules, each of which implements functionality independent of the others

If I dramatically change the requirements behind a particular function, how many modules are affected? In an orthogonal system, the answer should be "one.''

Don't rely on the properties of things you can't control.

#### Toolkits and Libraries

When you bring in a toolkit (or even a library from other members of your team), ask yourself whether it imposes changes on your code that shouldn't be there

#### Coding

Unless you constantly monitor not just what you are doing but also the larger context of the application, you might unintentionally duplicate functionality in some other module, or express existing knowledge twice

* Keep your code decoupled

  modules that don't reveal anything unnecessary to other modules and that don't rely on other modules' implementations

* Avoid global data

  In general, your code is easier to understand and maintain if you explicitly pass any required context into your modules

  Be careful with singletons - they can also lead to unnecessary linkage

* Avoid similar functions

  Duplicate code is a symptom of structural problems

Get into the habit of being constantly critical of your code

#### Testing

An orthogonally designed and implemented system is easier to test. Because the interactions between the system's components are formalized and limited, more of the system testing can be performed at the individual module level

Writing unit tests is itself an interesting test of orthogonality

Bug fixing is also a good time to assess the orthogonality of the system as a whole. When you come across a problem, assess how localized the fix is

tag bug fixes when you check the code back in after testing. You can then run monthly reports analyzing trends in the number of source files affected by each bug fix

#### Documentation

orthogonality also applies to documentation. The axes are content and presentation

a markup system such as Markdown: when writing we focus only on the content, and leave the presentation to whichever tool we use to render it

#### Living with Orthogonality

With DRY, you're looking to minimize duplication within a system, whereas with orthogonality you reduce the interdependency among the system's components

### Topic 11: Reversibility

if you rely heavily on some fact, you can almost guarantee that it will change

There is always more than one way to implement something, and there is usually more than one vendor available to provide a third-party product

With every critical decision, the project team commits to a smaller target - a narrower version of reality that has fewer options

The problem is that critical decisions aren't easily reversible

#### Reversibility

we don't always make the best decisions the first time around

The mistake lies in assuming that any decision is cast in stone - and in not preparing for the contingencies that might arise

Instead of carving decisions in stone, think of them more as being written in the sand at the beach. A big wave can come along and wipe them out at any time

#### Flexible Architecture

you also need to think about maintaining flexibility in the areas of architecture, deployment, and vendor integration

### Topic 12: Tracer Bullets

We use the term tracer bullet development to visually illustrate the need for immediate feedback under actual conditions with a moving goal

#### Code That Glows in the Dark

Look for the important requirements, the ones that define the system. Look for the areas where you have doubts, and where you see the biggest risks. Then prioritize your development so that these are the first areas you code

Tracer code is not disposable: you write it for keeps. It contains all the error checking, structuring, documentation, and self-checking that any piece of production code has

Tracer development is consistent with the idea that a project is never finished: there will always be changes required and functions to add

* Users get to see something working early

  They also get to contribute as the project progresses

* Developers build a structure to work in

  worked out all the end-to-end interactions

* You have an integration platform

  you have an environment to which you can add new pieces of code once they have been unit-tested

The impact of each new change is more apparent, and the interactions are more limited

* You have something to demonstrate

  you'll always have something to show them

* You have a better feel for progress

  developers tackle use cases one by one

Because each individual development is smaller, you avoid creating those monolithic blocks of code that are reported as 95% complete week after week

#### Tracer Bullets Don't Always Hit Their Target

a small body of code has low inertia - it is easy and quick to change. You'll be able to gather feedback on your application and generate a new, more accurate version quickly and cheaply

#### Tracer Code versus Prototyping

There is a difference

With a true prototype, you will throw away whatever you lashed together when trying out the concept, and recode it properly using the lessons you've learned

You could prototype a user interface for your end users in a UI tool

you might want to prototype a number of algorithms that perform the actual packing

once you'd made your decision, you'd start again and code the algorithms in their final environment, interfacing to the real world. This is prototyping, and it is very useful

Once you have all the components in the application plumbed together, you have a framework to show your users and your developers. Over time, you add to this framework with new functionality, completing stubbed routines. But the framework stays intact, and you know the system will continue to behave the way it did when your first tracer code was completed

Prototyping generates disposable code. Tracer code is lean but complete, and forms part of the skeleton of the final system

### Topic 13: Prototypes and Post-it Notes

Like the car makers, we can target a prototype to test one or more specific aspects of a project

prototypes as code-based, but they don't always have to be

Post-it notes are great for prototyping dynamic things such as workflow and application logic. A user interface can be prototyped as a drawing on a whiteboard, as a nonfunctional mock-up drawn with a paint program, or with an interface builder

Prototypes are designed to answer just a few questions

you find yourself in an environment where you cannot give up the details, then you need to ask yourself if you are really building a prototype at all

#### Things to Prototype

What sorts of things might you choose to investigate with a prototype? Anything that carries risk

Prototyping is a learning experience. Its value lies not in the code produced, but in the lessons learned

#### How to Use Prototypes

* Correctness
* Completeness
* Robustness
* Style

Prototypes gloss over details, and focus in on specific aspects of the system being considered, so you may want to implement them using a high-level scripting language

#### Prototyping Architecture

As opposed to tracer bullets, none of the individual modules in the prototype system need to be particularly functional

you may not even need to code in order to prototype architecture - you can prototype on a whiteboard, with Post-it notes or index cards

some specific areas you may want to look for in the architectural prototype: Are the responsibilities of the major areas well defined and appropriate? Are the collaborations between major components well defined? Is coupling minimized? Can you identify potential sources of duplication? Are interface definitions and constraints acceptable? Does every module have an access path to the data it needs during execution? Does it have that access when it needs it?

#### How _Not_ to Use Prototypes

make sure that everyone understands that you are writing disposable code

### Topic 14: Domain Languages

macros - all of which may suggest or obscure certain solutions

the language of the problem domain may also suggest a programming solution

try to write code using the vocabulary of the application domain

Your business users will have a vague idea of what they want to achieve, but they neither know nor care about the details

#### Characteristics of Domain Languages

RSpec and the router code are embedded into the code you run: they are true extensions to your code's vocabulary. Cucumber and Ansible are read by code and converted into some form the code can use. We call RSpec and the router examples of internal domain languages, while Cucumber and Ansible use external languages

##### Trade-Offs Between Internal and External  Languages

an internal domain language can take advantage of the features of its host language

internal domain languages is that you're bound by the syntax and semantics of that language

External languages have no such restrictions. As long as you can write a parser for the language

writing a good parser is not a trivial job

don't spend more effort than you save

##### An Internal Domain Language on the Cheap

Don't do a bunch of metaprogramming. Instead, just write functions to do the work

### Topic 15: Estimating

in the process of producing an estimate, you'll come to understand more about the world your programs inhabit

#### How Accurate Is Accurate Enough?

Do they need high accuracy, or are they looking for a ballpark figure?

the units you use make a difference in the interpretation of the result

#### Where Do Estimates Come From?

All estimates are based on models of the problem

basic estimating trick that always gives good answers: ask someone who's already done it

##### Understand What's Being Asked

##### Build a Model of the System

Often, the process of building the model leads to discoveries of underlying patterns and processes that weren't apparent on the surface

##### Break the Model into Components

Sometimes a component contributes a single value that is added into the result. Some components may supply multiplying factors, while others may be more complicated

##### Give Each Parameter a Value

The trick is to work out which parameters have the most impact on the result, and concentrate on getting them about right

You should have a justifiable way of calculating these critical parameters

you'll often find yourself basing an estimate on other subestimates. This is where your largest errors will creep in

##### Calculate the Answers

Only in the simplest of cases will an estimate have a single answer

During the calculation phase, you get answers that seem strange. Don't be too quick to dismiss them. If your arithmetic is correct, your understanding of the problem or your model is probably wrong

##### Keep Track of Your Estimating Prowess

it's a great idea to record your estimates so you can see how close you were

take some time to uncover what happened

#### Estimating Project Schedules

Program Evaluation Review Technique, or PERT

Every PERT task has an optimistic, a most likely, and a pessimistic estimate

Using a range of values like this is a great way to avoid one of the most common causes of estimation error: padding a number because you're unsure

the only way to determine the timetable for a project is by gaining experience on that same project

Iterate the Schedule with the Code

the team, their productivity, and the environment will determine the schedule. By formalizing this, and refining the schedule as part of each iteration, you'll be giving them the most accurate scheduling estimates you can

#### What to Say When Asked for an Estimate

You say "I'll get back to you."

You almost always get better results if you slow the process down and spend some time going through the steps

## Chapter 3: The Basic Tools

Tools amplify your talent

Always be on the lookout for better ways of doing things

### Topic 16: The Power of Plain Text

our base material isn't wood or iron, it's knowledge

the best format for storing knowledge persistently is plain text

The problem with most binary formats is that the context necessary to understand the data is separate from the data itself

#### What Is Plain Text?

Plain text is made up of printable characters in a form that conveys information

publisher, who wanted us to use a word processor (part of why prag prog publishing came to be)

The information part is important

**Keep Knowledge in Plain Text**

#### The Power of Text

Plain text doesn't mean that the text is unstructured

Insurance Against Obsolescence

##### Insurance Against Obsolescence

Human-readable forms of data, and self-describing data, will outlive all other forms of data and the applications that created them

You may not have recognized the significance of the numbers quite as easily. This is the difference between human readable and human understandable

##### Leverage

Unix is famous for being designed around the philosophy of small, sharp tools, each intended to do one thing well

a common underlying format - the line-oriented, plain-text file

Plain text is also easier to search

File comparison tools such as diff and fc allow you to see at a glance what changes have been made, while sum allows you to generate a checksum to monitor the file for accidental (or malicious) modification

##### Easier Testing

simple matter to add, update, or modify the test data without having to create any special tools to do so

plain-text output from regression tests can be trivially analyzed with shell commands or a simple script

#### Lowest Common Denominator

You need to ensure that all parties can communicate using a common standard. Plain text is that standard

### Topic 17: Shell Games

A benefit of GUIs is WYSIWYG - what you see is what you get. The disadvantage is WYSIAYG - what you see is all you get

Pragmatic Programmers don't just cut code, or develop object models, or write documentation, or automate the build process - we do all of these things

The scope of any one tool is usually limited to the tasks that the tool is expected to perform

Gain familiarity with the shell, and you'll find your productivity soaring

### Topic 18: Power Editing

text is the basic raw material of programming

**Achieve Editor Fluency**

the major gain is that by becoming fluent, you no longer have to think about the mechanics of editing

#### What Does "Fluent" Mean?

When editing code, move by various syntactic units (matching delimiters, functions, modules, ...)

Split the editor window into multiple panels, and navigate between them

Display compilation errors in the current project

#### Moving Toward Fluency

Run the current project's tests

learn the commands that make your life easier

Every time you find yourself doing something repetitive, get into the habit of thinking "there must be a better way."

#### Challenges

turn off autorepeat, and instead learn the key sequences to move, select, and delete by characters, words, lines, and blocks

Lose the mouse/trackpad. For one whole week, edit using just the keyboard
