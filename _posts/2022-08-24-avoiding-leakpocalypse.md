---
title: "Avoiding the Leakpocalypse"
date: 2022-08-24 19:15:00 MESZ
categories: meetup cologne
links:
    "Meetup.com": "https://www.meetup.com/de-DE/rustcologne/events/287924732"
    "Planning discussion on Github": "https://github.com/Rustaceans/rust-cologne/issues/97"
location: c4
talks:
- title: "Rust’s Ownership Model"
  speaker:
    name: "Florian Zeitz"
    twitter: florob
    github: florob
  slides: "https://babelmonkeys.de/~florob/talks/RC-2022-08-24-rust-ownership.pdf"
---
Dear Rustaceans,

our next Meetup will be on **Wednesday 2022-08-24 19:15 CEST**.

Rust's ownership and borrowing system is what gives it its "super powers". It enables guaranteed
memory safety and freedom from data races.
At this meetup we want to look at this system, devoting one half to a beginner level introduction
and the other to its relation to threading. The later will also provide an introduction to scoped
threads introduced in Rust 1.63 (released August 11th).

Throwback to early 2015. The Rust 1.0 release is around the corner and most of the Rust talks are
talking about this revolutionary feature: scoped threads.
Threads that can only run as long as the scope they are created in exists.
They can access local variables without any locks, mutexes, reference counting, *and* fear of
use-after-free. It's amazing.

However, a bit later it turns out that leaking memory breaks this API. Leaking a thread will make
it run longer than its defining scope. Leaking is memory safe. Wasteful but safe.
So the API is reconsidered and ultimately dropped from Rust's 1.0 release.
Some dub it the "leakpocalypse". Sadness.

Fast forward to today. Rust 1.63 has been released and scoped threads are finally back and kicking
in the standard library with a revised API. At the meetup we'll look at this new API and how it
makes fork-join style parallelism a lot easier.

Any remaining time will be used as **open space**: Imagine a bazaar, where you can suggest topics and spontaneously join any discussion you find interesting. It all depends on your interests. You can enjoy some drinks, meet nice people and discuss about Rust.

**[You can register here](https://www.meetup.com/de-DE/rustcologne/events/287924732)**.

We are looking forward to seeing you. :-)

Yours,
Kai and Florian
- - -
The meetup will likely be held in German, we will however reevaluate this at the beginning of the evening and may switch to English if needed.
- - -
Due to COVID-19 still being around, bringing a face mask will be necessary. For the same reason we need to know how many people will attend the meetup. Please make sure to register and, in case you are no longer able to attend, cancel your registration. Thank you.
