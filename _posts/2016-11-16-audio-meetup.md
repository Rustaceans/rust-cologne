---
title: "Open Source Audio Meetup"
date: 2016-11-16 19:00:00 MEZ
categories: meetup cologne
links:
    "Meetup.com": "http://www.meetup.com/RustCologne/events/234651810/"
    "Rust user forum": "https://users.rust-lang.org/t/7904"
    "German Rust forum": "https://forum.rustplatz.de/t/184"
    "Planning discussion on Github": "https://github.com/Rustaceans/rust-cologne/issues/10"
location: c4
talks:
- title: "Requirements of Real-Time Audio Programming"
  speaker:
    name: "Daniel Appelt"
    github: danielappelt
  slides: "https://danielappelt.github.io/talk-real-time-audio-programming"
  abstract: |
    This talk will focus on the requirements of real-time audio programming. On a high-level, I would like to explain why rust seems to be a better choice for that subject than many other new generation languages.
- title: "Low Latency Audio Transfer with AES-67 and Rust"
  speaker:
    name: "Marc Schettke"
    github: masche842
    twitter: marcschettke
  slides: http://schettke.com/files/rs67_rust-cologne_20161115.pdf
  abstract: |
    For quite some time professional audio systems use standard ethernet to transport audio data reliable and with very low latency (real-time). However, as proprietary technology has been used, interoperability was an issue. To resolve this, the Audio Engineering Society (AES) defined a minimal set of requirements in an open standard named AES-67. Since its publication in 2013 it has been implemented by many manufacturers but still lacks an open source implementation.
    
    Rust on the other hand is a modern system language and seems to be an ideal candidate for this, because it is safe, fast and can be used to develop for many targets from small microcontrollers to full-fledged high performance architectures.
    
    In this talk I will give a short introduction into real-time networks for professional audio applications and the AES-67 standard. I will then walk through my ideas for an open source implementation called "rs-sixty-seven" and what challenges I see. Finally I like to collect your thoughts and suggestions.

---

At the October meetup, we decided to _not_ do a meetup on the first Wednesday of November, but instead join forces with the [Open Source Audio Meetup](http://cologne.linuxaudio.org/doku.php) which is at the _third_ Wednesday (also at the c4).

After the talks we'll have an open discussion about music, audio software and programming with Rust. As always, you can enjoy some drinks, meet nice people and discuss about Rust and Open Source Audio. Be prepared for an interesting mix of topics from both worlds!

**Important note:** This meetup will be held **in German** - not English - due to joining with the Open Source Audio meetup.
