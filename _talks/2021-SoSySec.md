---
title: "A formal study of injection-based vulnerabilities and some tools it will enable"
collection: talks
type: "Talk"
venue: "SoSySec seminars at IRISA"
date: 2021-02-19
location: "Rennes, France"
---

Many systems work by receiving instructions and processing them: e.g., a browser receives and then displays an HTML page and executes Javascript scripts, a database receives a query and then applies it to its data, an embedded system controlled through a protocol receives and then processes a message. When such instructions depend on user input, one generally constructs them with concatenation or insertion. It can lead to injection-based attacks: when the user input modifies the query's intended semantics and leads to a security breach. Protections do exist but are not sufficient as they never tackle the origin of the problem: the language itself. We propose a new formal approach based on formal languages to assess risk, enhance static analysis, and enable new tools. This approach is general and can be applied to query, programming, and domain-specific languages as well as network protocols. We are setting up an ANR project to go into this subject in more depth. The presentation, in French, is available on [Youtube](https://youtu.be/YCjWmmeyIAw). [Slides](https://pfgimenez.github.io/files/sosysec.pdf)
