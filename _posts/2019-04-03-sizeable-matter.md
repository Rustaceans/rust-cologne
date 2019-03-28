---
title: "A Sizeable Matter"
date: 2019-09-03 19:15:00 MESZ
categories: meetup cologne
links:
    "Meetup.com": "https://www.meetup.com/de-DE/RustCologne/events/vnwndpyzgbfb/"
    "Planning discussion on Github": "https://github.com/Rustaceans/rust-cologne/issues/77"
location: c4
talks:
- title: "Implementing `wc` in Rust"
  speaker:
    name: "Matthias Endler"
    twitter: matthiasendler
    github: mre
  abstract: |
    The simple programs are sometimes the trickiest.
    Take `wc` for example, which prints the number of words, lines, characters,
    and bytes of its input. It's surprisingly hard to write a correct version of that program.
    Let me show you why and how Rusts prevents most of the bugs by design.
    This interactive coding session is targeted towards beginners and intermediate Rust programmers.
- title: "Dynamically Sized Types"
  speaker:
    name: "Florian Zeitz"
    twitter: florob
    github: florob
  abstract: |
    Everything has a memory footprint. And for most types it is known at compile time.
    But how large is a slice (`[T]`) or a trait object (`dyn Trait`)?
    In this talk we'll explore those types that only have a known size at runtime,
    bringing some clairty into terms like "dynamically sized", "unsized" or "existential" types.
---
Dear Rustaceans,

we're happy to announce that our next meetup will be on **Wednesday, April 5, 2019** at **19:15**!

We have two talks dealing with the size of things in very different ways.
First we'll have a talk by Matthias Endler showing how to size up a file, by reimplementing a simple
`wc` clone in Rust.
Second Florian Zeitz is going to tell us about the size of types in Rust, particularly those only
known at runtime.

Afterwards there will be time for socializing and open discussion over some drinks.

**[You can register here](https://www.meetup.com/de-DE/RustCologne/events/vnwndpyzgbfb/)**.

We are looking forward to seeing you. :-)

Yours,
Florian

- - -

The meetup will likely be held in English, we will however reevaluate this at the beginning of the evening and may switch to German if desired.
