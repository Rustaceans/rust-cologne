---
title: "Fast? Safe? Both?"
date: 2019-08-07 19:15:00 MESZ
categories: meetup cologne
links:
    "Meetup.com": "https://www.meetup.com/RustCologne/events/tnrnbryzlbkb/"
    "Planning discussion on Github": "https://github.com/Rustaceans/rust-cologne/issues/82"
location: c4
talks:
- title: "WebAssembly"
  speaker:
    name: "Matthias Endler"
    twitter: matthiasendler
    github: mre
  slides: "https://github.com/mre/wasm/"
  abstract: |
    WebAssembly has the potential to change the way we write and deploy software in the future
    and Rust is in a great position to become the best language to target WebAssembly.
    Let me show you why I think both of these statements are true and why you should care.
    Featuring simple examples!
- title: "How defined is Rust?"
  speaker:
    name: "Florian Zeitz"
    twitter: florob
    github: florob
  slides: "https://babelmonkeys.de/~florob/talks/RC-2019-08-07-rust-defined.pdf"
  abstract: |
    C is notorious for its undefined behavior. It is relatively easy to void all program behavior
    by making a small error. Rust has no undefined behavior in its safe subset. Yet it has to deal
    with the same situations C makes undefined somehow, ideally without sacrificing performance.
    Also Rust's unsafe subset has its own set of undefined behavior.
    This talk will investigate how Rust deals with issues like oversized shift amounts, type punning,
    and integer overflow.
---
Dear Rustaceans,

we're happy to announce that our next meetup will be on **Wednesday, August 7th, 2019** at **19:15**!

This time we'll have two talks:
Matthias Endler will talk to us about using Rust to build applications with WebAssembly.
Florian Zeitz will contrast the C programing language with Rust in terms of their safety
guarantees and resulting performance.

Afterwards there will be time for socializing and open discussion over some drinks.

We are looking forward to seeing you. :-)

Yours,
Florian

- - -

The meetup will likely be held in English, we will however reevaluate this at the beginning of the evening and may switch to German if desired.
