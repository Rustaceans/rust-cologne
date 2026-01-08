---
title: "Rust in January: async atrocities - futurelock and cancelability"
date: 2026-01-14 19:15:00 MEZ
categories: meetup cologne
links:
    "Meetup.com": "https://www.meetup.com/rustcologne/events/312789818/"
    "Planning discussion on Github": "https://github.com/Rustaceans/rust-cologne/issues/137"
location: c4
---

Rust Cologne is a monthly meetup dealing with everything Rust.
This Meetup we'll talk about common and lesser known pitfalls when writing async Code.

_(The meetup will likely be held in German but we'll switch to English if needed.)_

Dear Rustacean,

you are hereby warmly invited to join the next Rust Cologne meetup. Whether you want to speed up your python code, write a web service, need interop with your C++-codebase, cross-compile for a microcontroller, write an emulator, … we've got you covered!

We commonly open up with a brief summary of noteworthy changes in the Rust ecosystem. Be it updates to the language itself, public events, its impact on other projects and languages, …

"If it compiles, it works" is a common feeling when writing Rust code. A strict type-system, proper linting and helpful compiler messages prevent lots of problems common in other languages. "The thrill has gone …" is a common feeling when writing `async` Rust code.

As more and more crates evolved around that language feature, so did the challenges: surprising deadlocks, lost results, increased complexity, lifetime-issues, data loss, …

In this meetup we talk about how `async` is _different_ from ordinary Rust and how to tackle at least some of the challenges it brought to the language.

As usual, the remaining time is about whatever _you_ want to talk about!

Always wanted to know why Rust is harder to learn than other popular languages or why it lacks a certain feature? When is it appropriate to rewrite a project in Rust? Is the compiler really that slow and are the binaries really that big? Do all those safety guarantees have an impact on the performance? Fetch a drink and let's find out.

**[You can register here](https://www.meetup.com/rustcologne/events/312789818/)**.

See you soon!

Yours,
Florian and Kai
- - -
If you have a topic you'd like to talk about, please [let us know in advance](https://github.com/Rustaceans/rust-cologne/issues/137). This way we can make sure there's a time-slot for you and maybe announce it officially. Thank you.
