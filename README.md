# A Quick Tour of Haskell

**Functional Tools That You Can Take Home!**

*An ACM Talk by Bailey Parker on 2018-03-30*

## The Abstract

> Most students first learn imperatives languages (like C++, Java, or Python)
> and never look back. Some may be exposed to functional languages for a
> course, but never find other uses for them. Functional programming, though,
> can teach useful skills that transfer over to your day-to-day programming in
> school, internships, and jobs. Join us for a brief survey of the basics of
> Haskell spanning recursion, composition, immutability, and laziness and
> concluding by delving into the magic of monads. Along the way you'll pick up
> some tips for writing clearer, more concise, and less buggy code placed in
> real world contexts such a ML and CDNs.

*NB:* The mention of ML and CDNs is a little clickbaity! I provide some much
simplified examples of how you could use functional to reason about them
better, but this definitely isn't a detailed talk about either.

## About the Talk

This talk is part of a larger vision I have to create a series of talks about
practical design patterns used in the real world to great effect. Many CS
curriculums focus more on computer science as a science and not an art. And
while there is undeniably a science to solving problems by composing algorithms
and using prior art and research to understand a problem, I contend that you
should also focus on the art of CS. Treat the code you write like an essay; it
should be well organized, clear, and free of grammatical errors. Code that is
simple and conveys its intent clearly is a treat for the reader. And this
directly translates to less friction when changes are necessary in the future.
Too many programs train students to be *Get It Done™* machines without giving
much pause to consider the next person to read the code. Just like a writer
wouldn't publish scribbled notes from a journal, you shouldn't publish code that
you wouldn't want others to read. Your product should be a labor of love, a
manuscript with attention to all of the details.

Metaphors aside, this manifests itself in software design patterns. I've found
course offerings and academic stress to be lacking in this area. And this is
only to the students' detriment. If/when they enter the commercial workforce,
they'll be expected to jump into large code bases and contribute code that may
still be relied on for years to come. Without experience in properly applying
design patterns, they're forced to pick up this critical skill on the job while
adjusting to the new environment. I content that software design should be
taught as early in the process as possible to preclude this.

Students who are frustrated with CS aren't "bad" at it, they just haven't been
show best practices that will make it easier to focus on learning (instead of
keeping track of lots of mental state or permuting code with abandon until it
"just works"). Good practices like writing simple, testable, decoupled,
testable code go a long way to easing the learning process.

Patterns aren't just pedantry. They arise out of the fact that code is written
by humans. And, humans aren't prefect. Design patterns allow our limited
biological computing power to focus solely on the important things so that we
can more easily write bug-free, beautiful code.

## Instructions

You should be able to view `index.html` in any recent web browser. The most
recent version is also available on
[GitHub pages](https://baileyparker.github.io/haskell-talk/).

## Typos?

I fixed a few before uploading, but if you find any, please file an issue or
submit a PR. Thanks!
