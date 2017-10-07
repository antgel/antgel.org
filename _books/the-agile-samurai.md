---
layout: page
title: The Agile Samurai
toc: true
---

## Intro

In 2001, several of the great names in software development got together
and came up with the [Agile Manifesto](https://agilemanifesto.org),
which became the basis for a revolution in software development, the
influence of which is still felt today.

[The Agile Samurai](FIXME) by [Jonathan Rasmusson](FIXME), published by
the wonderful [Pragmatic Bookshelf](), is a light-hearted look at Agile
practices, in a practical context. At the time of writing (2017), the
book is seven years old, which is a lifetime in software terms, yet it
remains relevant.

As with anything worthwhile that looks likely to become popular, the
commercial / enterprise software behemoths jumped on the bandwagon and
tried to make Agile their own. This has been a cause of some distress
for the early pioneers. One doesn't *do* Agile.  One might behave
according to  *Agile principles*, one might do *Scrum* or *Kanban*, but
one doesn't do *Agile*.

This page is a distillation of some of my main takeaways from the book.
I hope it will provide a useful reference for fellow readers, and
I hope that those of you want to get into Agile, will buy it.

> Throughout, Agile principles will appear like this.

Agile has many flavours - I have attempted to stick to Scrum
terminology.

## Part 1 - Introducing Agile

### Chapter 1 - Agile in a Nutshell

What would it take to deliver something of value each and every week?

#### Deliver something of value every week

Put yourself in the customer's shoes. What would give you confidence
that the development team was delivering? Documents and notes? Or
working software?

When doing this, good things happen. You:

1. Break big problems down into smaller ones (make things
   manageable).
1. Focus on the really important stuff and forget everything else
   (get lean).
1. Make sure that what you're delivering works (testing).
1. Go looking for feedback (stay on the right path).
1. Change course when necessary (roll with the changes).
1. Become accountable (made the commitment, own it).

> Our highest priority is to satisfy the customer through early and
> continuous delivery of working software.

#### How does Agile planning work?

* The *product backlog* is the "to-do" list. It contains all the *user
stories* (high-level features) that the product owner wants to see.
* *Sprint* is the 1-2 week period where the most important stories
  are transformed into working software.
* *Velocity* is how much work the team can take on in the iteration.
* Being *flexible on scope* is how the team handles situations where
  there is too much to do.
* When reality kicks in and things change, we use *adaptive planning* to
  change the plan.

There is no point being unrealistic. "Management by miracle" is doomed
from the start. Working transparently with the customer is preferable.

#### Done means done

*Done* means doing everything necessary to produce shippable code. This
includes:
* Analysis
* Design
* Coding
* Testing
* UX

*If it can't be shipped, it's not done.*

> Working software is the primary measure of success.

#### Three simple truths

1. It is impossible to gather all the requirements at the beginning of
   the project.
1. Whatever requirements are gathered are guaranteed to change.
1. There will always be more to do than time and money will allow.

This means we don't:
1. Wait for everything to be defined, before moving forward.
1. Worry about change, it's inevitable.
1. Stress about having too much to do, it's the normal state.

### Chapter 2 - Meet Your Agile Team

No pre-defined roles, anyone can do anything. Yet high-performing Agile
teams produce quality software.

#### How are agile projects different?

1. Roles blur, like working in a mini-startup, yet people have core
competencies.
1. Analysis, coding, design, and testing are *continuous*,
not isolated. People need to be joined at the hip, daily.
1. Quality is a team responsibility.

#### What makes an Agile team tick?

##### Co-location

* Faster feedback.
* Problems fixed on the spot.
* Less friction
* Trust built quicker.

##### Engaged customers

Core team members, full-on partners, who will:

* Show up to demos.
* Answer questions.
* Give feedback.
* Provide guidance and insight.

> Business people and developers must work together daily throughout the
> project.

If customer is *not* engaged, build trust.

##### Self-organization

* Team should be given a goal and everyone should stand back as team
  decides how to get there.
* Egos put to the side.
* Let the role fit the person, rather than "letting" the person fit the
  role.

How to do this?

* Let team create plan, estimates, and take ownership.
* Don't worry about titles and roles. "Worry" about continuous delivery
  of working, tested, software.
* Look for people who take initative, who don't wait to be
  micro-managed.

> The best architectures, requirements, and designs emerge from
> self-organizing teams.

##### Accountability and empowerment

A good team *wants* to be agile. They know customers count on them and
relish the responsibility.

> Build projects around motivated individuals. Give them the environment
> and support they need, and trust them to get the job done.

If there's an issue with accountability, ask the team to demo the
software. The team will see that real people count on them to deliver. A
bad demo can raise the interest level in making sure that everything
works.

##### Cross-functionality

Serve the customer end-to-end. Have the expertise to take any feature
and deliver it fully.

Recruit generalists who are comfortable walking the full stack. No need
to wait for permission or negotiate for resources.

#### Roles we typically see

There is little formality with Agile.

* Customer: decides what to build.
* Dev team: decides how to build it.

##### The Agile Customer

* "Source of truth" from whom requirements flow.
* Subject matter expert, familiar with the business, committed to
  guidance and feedback.
* Sets priorities in a collaborative process with dev team. 
* Decides on what to leave out when deadlines loom and resources are
  tight.

##### The development team

Cross-functional group who can take any development requirement and turn
it into production-ready, working software. Taking a traditional team
and telling them to self-organize is unlikely to work well. Need to
present Agile in understood terms:

The Agile analyst:
* Gets in there, figures out how features will work.
* Asks the right questions, works closely with customer.
* Help write user stories.
* Does deep-dive on analysis.
* Helps create mock-ups and prototypes.

The Agile programmer:
* Pros because they take quality and testing seriously.
* Write lots of tests, even using them to help drive design.
* Continuously designing and improving architecture as they go.
* Make sure codebase always production-ready, deployment is a non-event.

The Agile tester:
* Understands that building it doesn't mean it works.
* Gets involved early on, defining test cases for user stories.
* Works with customer defining tests for success.
* Works with developers building automation and looking for holes.
* Keeps big testing picture in mind.

The Agile project manager:
* Removes roadblocks in the team's way.
* Continuously planning, adjusting course when necessary.
* Sets expectations with stakeholders, builds relationships with rest of
  company, shields the team when necessary.
* Doesn't micro-manage the team - builds the environment where they know
  what to do.

The Agile UX designer:
* Passionate about making experience useful, usable, desirable.
* Many UX practices are similar to Agile, e.g. incremental, iterative
  approach, don't build everything up-front.

Other roles in the development team are treated just like anyone else on
the project. It's natural and expected that people will wear multiple
hats.

#### Tips for forming your Agile team

* Look for generalists. Agile requires people to follow through and own
  things end-to-end.
* Comfortable with ambiguity. Not everything is neat and tidy,
  requirements will be missing and change, and the team needs to adapt.
  Need people who don't panic, can take a hit, and deal with change.
* Team players who leave egos at the door. Roles are blurred, no need to
  "protect their turf". Want people who are comfortable, and enjoy
  sharing, learning, and growing with others.

## Part 2 - Agile Project Inception

`FIXME: Come back to this, it's relatively rare compared to planning.`

## Part 3 - Agile Project Planning


