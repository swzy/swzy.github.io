---
title: "Back to Basics"
layout: post
date: 2020-8-9 21:12
headerImage: false
category: blog
author: Sam Yi
description: JavaScript
---

Finally got to the section on JavaScript - where I left off last year. Felt like it was a great refresher into programming in general and even some basic Computer Science concepts:

* Basic JavaScript syntax and basic ways to debug
* JS as a _synchronous_, single-threaded language that may be executed _asynchronously_ due to the V8 JavaScript runtime and the APIs that are provided by the browser itself.
* How the event loop, task queue, and call stack work together to determine how asynchronous execution is determined and, even if it can cause alot of headache, is necessary for seamless UI experiences.

Then I got into a little bit of a rabbit hole re-learning about compilers and interpreters and was able to suss out a layman's explanation to get me through:

* **Compilers** will convert high-level, "plain English" source code into binary machine code that the underlying hardware can execute while **interpreters** execute the high-level code or script line-by-line. There is a more nuanced discussion about how just-in-time (JIT) compilation and bytecode interpreters, even in the case of JavaScript, start to blur some of those lines but I think I will go further down that rabbit-hole (and wonder more about the true value of my CS degree) another day.

Finally, started to round off my day with wrapping my head around callback functions, which I have some experience with by using Promises in a web app project, but I didn't get to a comfortable place and will likely keep working on that.

Not bad and good stuff!