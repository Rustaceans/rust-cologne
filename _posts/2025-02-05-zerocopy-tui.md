---
title: "Rust in February: Terminal UIs and zerocopy parsing"
date: 2025-02-05 19:15:00 MEZ
categories: meetup cologne
links:
    "Meetup.com": "https://www.meetup.com/rustcologne/events/305878437"
    "Planning discussion on Github": "https://github.com/Rustaceans/rust-cologne/issues/126"
location: c4
talks:
- title: "Ratatui"
  speaker:
    name: "dawe"
    github: dawedawe
  abstract: |
    Ratatui is a Rust crate to create terminal user interfaces (TUIs).
    From layouts over styles to architecture options: This talk will give a beginner friendly overview of the key concepts of ratatui and TUIs in general.
- title: "Parsing binary formats with zerocopy"
  speaker:
    name: "Florian Zeitz"
    github: florob
  abstract: |
    There are many options to parse binary formats. While many of them copy the parsed data over into a new struct, it can be very efficent to keep the data in place.
    This talk introduces the zerocopy crate as an option for doing so and discusses how it provides a safer way to this approach than C code.
  slides: "https://babelmonkeys.de/~florob/talks/RC-2025-02-05-zerocopy-parsing.pdf"
---
_(The meetup will likely be held in German but we'll switch to English if needed.)_

Dear Rustacean,

our next Meetup will be on **Wednesday 2025-02-05, 19:15 CET**.

You're new to Rust, tried it out with some private projects or are already working professionally with it for years? You're in good company! Whether you want to speed up your python code, write a web service, need interop with your C++-codebase, cross-compile for a microcontroller, write an emulator, … we've got you covered!

We commonly open up with a brief summary of noteworthy changes in the Rust ecosystem. Be it updates to the language itself, public events, its impact on other projects and languages, …

Following that this month we will have two interesting talks for you. Dawe will introduce us to creating terminal user interfaces with the "ratatui" crate. Florob will tell us about zerocopy parsing
of binary formats.

Always wanted to know why Rust is harder to learn than other popular languages or why it lacks a certain feature? When is it appropriate to rewrite a project in Rust? Is the compiler really that slow and are the binaries really that big? Do all those safety guarantees have an impact on the performance? Fetch a drink and let's find it out.

**[You can register here](https://www.meetup.com/rustcologne/events/305878437)**.

See you soon!

Yours,
Florian and Kai
- - -
If you have a topic you'd like to talk about, please [let us know in advance](https://github.com/Rustaceans/rust-cologne/issues/126). This way we can make sure there's a time-slot for you and maybe announce it officially. Thank you.
