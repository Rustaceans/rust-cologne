---
title: "Bring your code! (and a brief introduction to serde)"
date: 2023-05-10 19:15:00 MESZ
categories: meetup cologne
links:
    "Meetup.com": "https://www.meetup.com/rustcologne/events/293321630/"
    "Planning discussion on Github": "https://github.com/Rustaceans/rust-cologne/issues/105"
location: c4
talks:
- title: "Serde"
  speaker:
    name: "Florian Zeitz"
    twitter: florob
    github: florob
  abstract: |
    This talk will give a short overview over using serde, the most popular serialization and deserialization framework for Rust.
  slides: "http://babelmonkeys.de/~florob/talks/RC-2023-05-10-serde.pdf"
---
Dear Rustaceans,

our next Meetup will be on **Wednesday 2023-05-10, 19:15 CEST**.

The first part will give you a short overview of the [`serde`](https://crates.io/crates/serde) crate. Serde is a framework for **serializing and deserializing Rust data structures** efficiently and generically.

For the second part we invite you to solve the attached task and **bring your home-grown code**. It doesn't matter whether your Rust-level is `println!("Hello World!")` or "async webserver on `no_std`". Just give it a try and show your result. You failed on this task? Great! Something to learn for everyone!

**Description of the task**: Write a function that takes the first `n` numbers (`0..n`) and outputs them in the order, they would appear in a dictionary (lexicographic order).

The input `10` would result in the sequence `8, 5, 4, 9, 1, 7, 6, 3, 2, 0` because they would be spelled "eight, five, four, nine, one, seven, six, three, two, zero".

Feel free to fill gaps in this specification with whatever you feel comfortable with. Here are some suggestions:

- print your results to `stdout`, collect them in a `Vec` or return an `Iterator`
- `123405` might become "one hundred twenty-three thousand four hundred five"
- see [Names of large numbers](https://en.wikipedia.org/wiki/Names_of_large_numbers) for even bigger numbers

Depending on how much time is left, we could add some tests, benchmarks, compare memory-footprints, make your solution more generic, …

**[You can register here](https://www.meetup.com/rustcologne/events/293321630/)**.

We are looking forward to seeing you. :-)

Yours,
Florian and Kai
- - -
The meetup will likely be held in German, we will however reevaluate this at the beginning of the evening and may switch to English if needed.
- - -
COVID-19 measures: We have restricted the maximum number of participants to ensure social distancing is possible.
Accordingly we need to know how many people will attend the meetup.
Please make sure to register and, in case you are no longer able to attend, cancel your registration.
Feel free to privately send us a message if you think that more safety measures are required.
