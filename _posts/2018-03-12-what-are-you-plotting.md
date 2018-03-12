---
title: "Is that a spectrum, or memory access timings?"
date: 2018-03-12 19:15:00 MEZ
categories: meetup cologne
links:
    "Meetup.com": "https://www.meetup.com/RustCologne/events/vnwndpyxfbkb/"
    "Planning discussion on Github": "https://github.com/Rustaceans/rust-cologne/issues/48"
location: c4
talks:
- title: "Rust Audio analysis"
  speaker:
    name: "Matthias Endler"
    twitter: matthiasendler
    github: mre
  abstract: |
    Rust can be used in many ways. One area is for working with audio data.
    I always wanted a real-time tool to analyze the sound spectrum in front of my apartment door.
    In particular, I'm interested in the number of car honks throughout the day and its distribution.
    So I read an audio stream, split it into small chunks, and run a Fourier analysis on it.
    My assumption is that you can see a higher amplitude in a certain band of frequencies when a car honk occurs. Let's see how it turns out.
- title: "Caches and You"
  speaker:
    name: "Florian Zeitz"
    twitter: florob
    github: florob
  slides: "http://babelmonkeys.de/%7Eflorob/talks/RC-2018-03-12-caches-and-you.pdf"
  abstract: |
    One of the great things about Rust is that it gives you a lot of control if you need it.
    Amongst other things it gives you control over memory.
    How big is your data structure really, and where should it be allocated.
    This talk will look at caching in modern CPUs in conjunction with Rust data types and data structures.
    We will see how efficient code can be written to best utilize the cache. 
---
We'll have two short talks for you, followed by the usual open discussion and mingling. We are looking forward to seeing you. :-)

Please note that this meetup on the second **Monday** in March!

The meetup will likely be held in German, we will however reevaluate this at the beginning of the evening and may switch to English if needed.
