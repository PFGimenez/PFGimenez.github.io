---
title: "System programming on Linux and Windows"
collection: teaching
type: "M1"
permalink: /teaching/cs-sysprog
venue: "CentraleSupélec"
date: 2020-01-01
location: "Rennes, France"
---

I am in charge of this module since 2020.

The C language is still one of the most widely used languages to program low-level software applications in operating systems or application layers closeby. In particular, it is widely used for background services in GNU/Linux and Microsoft Windows systems (web servers, database servers, e-mail servers, file servers, and so on). Although designed a long time ago (in the 1970s) this state of things is due to the unchallenged performance of C programs, thanks to the continuous progress of available compiler toolchains. The drawbacks of writing in such a concrete language are therefore (partially) balanced by near-optimal performance, at the cost of a substantial effort for program design.
This course is therefore oriented towards students willing to strengthen their programming skills through experience with the C language, by writing applications close to the OS using standard UNIX interfaces (POSIX standard, I/O management, inter-process communication, multiprocess / multithread programming, system signal handling, debugging and application design and implementation) and their Microsoft Windows cousins with the Win32/Win64 APIs.
This course will also be the opportunity to realise the intrinsic difficulties of programming in C (especially the explicit memory management and the consequences of arguable design decisions in the implementations of arrays and strings) and the safety and security problems they incur.
We will use this experience to introduce a new programming language (Rust), which allows to guarantee both more security and safety (by language design, especially thanks to its rich type system) and achieves high performance just like C programs. To the best of our knowledge, this is the first language in programming languages history that reconciles security/safety with performance (previous attempts always sacrificed either security or performance). The Rust language is already currently used by Mozilla developers for the web browser Firefox.

The course is evaluated with a project on a freely chosen subject. Some examples:
  - Linux shell
  - Windows malware
  - Simplified git
  - VPN client
