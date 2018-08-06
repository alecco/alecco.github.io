# Required Reading for Optimization - part 2

Software optimization is hard and getting more complex.
It's quite common to see programmers obsessing about some deep optimization
when their code is missing a much bigger opportunity somewhere else.

So, before you get into thinking about performance and optimization
there is a basic background you need to have a thorough understanding of the basics.

## The right tool for the right job

We programmers tend to marvel and wonder on new software techniques.
This is great for learning and exploring
but it steers us away from pragmatism.

Many times in my career I've seen teams waste months on complex in-house systems
based on low level lanugage implementations
or using hard parallelization frameworks.
Many times those jobs could be replaced by sensible solutions
using simple unix command line tools or
minimal SQLite databases with proper indexing.


## Latency scales

You should get a very good understanding of
[ltency numbers and scales](https://people.eecs.berkeley.edu/~rcs/research/interactive_latency.html).

For example, there is often no significant gain in using
an optimized low-level programming language
if the task at hand is memory or network bound.
Sometimes a script is good enough.

## Language

There is a trade-off of high level languages vs. low level languages.
High level gives you quick time to delivery, simple abstractions,
flexibility.
Low level gives you performance and sometimes safety.

https://benchmarksgame-team.pages.debian.net/benchmarksgame/faster/gcc-python3.html


## SQL and indexing

A great resource to learn the essential concepts in SQL is
Marcus Winand's [Use the Index Luke](https://use-the-index-luke.com/).


## Agner Fog's optimization manuals

Agner wrote some great resources on [optimizing programs](https://www.agner.org/optimize/).

[Intel manuals](https://software.intel.com/en-us/articles/intel-sdm).


