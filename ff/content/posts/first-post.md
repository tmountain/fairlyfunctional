---
title: "Why Bother?"
date: 2018-12-16T11:39:50-05:00
tags:
 - purescript
 - clojure
 - haskell
 - longform
---

## Statement of Rationale

Welcome to fairlyfunctional.io. Before we embark on this journey together, I feel
that it might be worthwhile to present some of the reasons I'm doing this, and in turn,
express why you might find the content I'll be exploring here to be of interest.

Like most people, I place a high premium on my free time, and long gone are
the days of my youth when I had the capacity to spend late nights and marathon
weekends chasing after a deeper understanding of some esoteric piece of the technology puzzle.

For something to capture my attention nowadays, it has to represent a means to an end. That is,
it has to serve as a medium for which I can reach some tangible goal in a way that
is superior to the previous solution, and hopefully, save time in the future (avoiding debt or otherwise).

From this vantage point, starting yet [another](http://dailyvim.blogspot.com/)
 tech [blog](http://travis-whitton.blogspot.com/) might seem like
it's off target; however, after some extensive thinking on the topic,
I have concluded the efforts I'll be applying here are indeed a means
to an end, and they map to a very specific goal, which I can summarize as follows:

_To document and describe a methodology for building modern applications
given two guiding principles:_

_1) Using the existing body of 50+ years of computer science research and
study for the purpose of delivering hyper reliable applications.
(AKA -- Standing on the shoulders of giants for great good)._

_2) Leveraging the extremely robust technology ecosystems which already exist to
avoid duplicating effort. (AKA -- Squeezing the juice out of the JavaScript orange)._

Individually, neither objective is terribly interesting, as it's easy to write
"correct" code in a vacuum (a world free of side-effects), and it's also
easy to cherry-pick components out of a package manager and drop them into an app.
However, the intersection of these objectives turns out to be a very interesting
place indeed, as there are [only](https://github.com/ghcjs/ghcjs)
a [few](https://elm-lang.org/) [options](http://www.purescript.org/) that meet
my admittedly [opinionated criteria](https://www.reddit.com/r/purescript/comments/6g6brx/why_purescript/dinwty2/)
regarding the appropriate characteristics to deliver on these principles.

As a backdrop regarding how I arrived here, as of 2018, I've been writing code professionally
for twenty years, and I've been on a knowledge quest since the beginning. In the early
days of my career, I obsessed over Linux distributions, Perl, and trying to understand every possible
nuance of the command-line. Munging text and writing small utilities was the order
of the day, and working at a rapidly growing ISP was the perfect opportunity to hone
that craft.

From there, I spent quite a bit of time working on what most folks would think of as
traditional web applications (monolithic MVC apps) written in dynamic scripting languages
(PHP, Python, and Ruby). For the more "designed" applications I worked on during this
time period, I'd regularly try to wedge my models or controllers into awkward inheritance
hierarchies and never fully understood why everything had to be an object when all I was really
doing was passing data around.

In tuning systems where performance mattered, I moved into thinking about state and
concurrency almost obsessively. Initially, this came about via a desire to master
the idiosyncrasies of database transactions and their respective isolation levels.
Later the same set of concerns came to the forefront when working on a large
JVM based mobile application for a streaming music service that was popular at the
time (Grooveshark).

After a nightmarish stint (and many deadlocks) trying to reason about concurrency on
the JVM using traditional means (lock-based synchronization and pouring over [JCIP](http://jcip.net/)),
I came to the conclusion that _there had to be a better way_.

This was 2008, and Clojure was just starting to garner mainstream attention. Embarking on
what I believed would be a quick survey of a language that could solve my concurrency
crisis, I found myself very quickly falling down the rabbit's hole into the world
of functional programming, and Clojure became both a fundamental part of my toolbox
and the door to an amazing community.

Since then, I have spent thousands of hours learning about how to write better code
under the umbrella of FP, and through that journey, questions have continued to arise.
Most notably, I have found myself asking, "What tools are available to provide guarantees
about the shape and consistency of the data in my projects?" and more generally,
"How can I write code that is both safe, abstract, and easy to maintain as my
projects grow?"

After much deliberation, I landed in the world of statically typed ML based languages.
I've spent much of my free time over the last few years working on understanding Haskell
and its value proposition, and like so many others, I went on the Monad pilgrimage --
*and while we're on that topic, allow me to preemptively apologize, as I'll be bringing
yet another monad tutorial to the world as a featured article on this blog because
I have some ideas on how to intuitively explain this infamously murky
topic (under the umbrella of avoiding the monad fallacy).*

Through all of this, the world has continued to change around me, and I now find myself
in a place where the front-end has become the driving force behind the modern web.
JavaScript is undeniably the ubiquitous technology powering the experiences we've all come to
expect; thus, yet again, the desire sets in to continue on the knowledge quest.

This new chapter of my technology life is one in which I'm hoping to take all my existing
education in functional programming and apply it to building front-end applications that
are uncompromising regarding safety, consistency, and pragmatism regarding
an open door to the outside world.

I'll be using this blog to work through the topics like
working with PureScript and its
[FFI facilities](https://github.com/purescript/documentation/blob/master/language/FFI.md)
to seamlessly blend type-safe code with third-party React components while
managing state in a way that is [easy to reason about](https://guide.elm-lang.org/architecture/).

I recognize that the barrier to entry on these technologies can be steep,
and one of my key goals is to demystify topics like monads, typeclasses,
and applicative functors and present them in a way in which their practical
applications become clear.

I'll be doing this under the umbrella of building an application of my own to help folks
master verb conjugation in foreign languages (notably Spanish and Russian),
as this is another passion of mine.

Just as the Haskell motto is "avoid success at all costs", I will not be producing any of this
content in hopes of reaching an audience of any particular size; rather, I'm here
for the explicit purpose of preserving information and creating a historical tome
which I can refer to as I go. I'm also not committing to any specific pace whatsoever, as
I also view this as an opportunity to practice "slow thinking", so the content will
likely come in fits and spurts.

Once more unto the breach. ¡Que se abra el telón!
