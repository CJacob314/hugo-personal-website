+++
date = '2024-10-31T08:40:40-05:00'
draft = false
title = 'RSA'
+++
{{< alert "lightbulb" >}}
This entire project was inspired by [Dr. Looper](https://sites.google.com/view/nicole-looper) at [UIC](https://www.uic.edu/), who taught my amazing Math 215 course!
{{< /alert >}}
{{< lead >}}
A big step for my self-confidence
{{< /lead >}}

Even before I started my undergraduate degree, I was fascinated by the idea of an asymmetric cryptosystem. It just seemed like *magic* to me.

So I would occasionally visit the [Wikipedia page for RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)#Operation), only to get discouraged quickly by how out-of-reach this knowledge seemed.
Once that discouragement had worn off and something again piqued my curiosity, I'd revisit the page, and the cycle would continue.

Eventually, while learning about modular arithmetic in Math 215 at UIC, Dr. Looper made an offhand comment about how this math is the backbone of RSA. My curiosity again spiked, this time higher than ever before. Maybe I could *actually understand* it this time!

With the frequent help of Dr. Looper both in class and during office hours, I built an intuitive understanding of the cryptosystem and [started](https://github.com/CJacob314/RSA-Implementation/commit/82b564490a60e4bb655aadc5c5016e3543fe421b) a C++ implementation (using [boost::multiprecision](https://github.com/boostorg/multiprecision) for the large integers) in the Fall of 2023.

I put hours and hours into the project, developing a [Rust CLI frontend](https://github.com/CJacob314/RSA-Implementation/tree/rust-cli-wrapper) (if I were starting the project today, I would have written it entirely in Rust with [num_bigint](https://crates.io/crates/num-bigint)) and a [WASM-compiled version](https://rsa.jacobcohen.dev/) you can try in your browser right now!
{{< alert >}}
Seriously, [go try it out now](https://rsa.jacobcohen.dev/) and come back later!
{{< /alert >}}

Realizing that I had gained an implementation-worthy understanding of something I'd once written off as only for "genius mathematicians" changed the way I saw myself.

I gained a new confidence. After learning RSA in class, it took me more than half a year to get RSA working, but **I got it working**. I learned that I'm not innately too stupid to understand most things, no matter how impossibly difficult they seem. If I put my mind (and *lots* of time) to it, I can understand *almost* anything.
