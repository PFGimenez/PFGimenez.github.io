---
title: "A theory of injection-based vulnerabilities in formal grammars"
collection: talks
type: "Talk"
venue: "2023 Annual Meeting of the WG \"Formal Methods for Security\""
date: 2023-03-29
location: "Roscoff, France"
---

Many systems work by receiving instructions and processing them: e.g., a browser receives and then displays an HTML page and executes Javascript scripts, a database receives a query and then applies it to its data, an embedded system controlled through a protocol receives and then processes a message. When such instructions depend on user input, one generally constructs them with concatenation or insertion. It can lead to injection-based attacks: when the user input modifies the query's intended semantics and leads to a security breach. Protections do exist but are not sufficient as they never tackle the origin of the problem: the language itself. We propose a new formal approach based on formal languages to assess risk, enhance static analysis, and enable new tools. This approach is general and can be applied to query, programming, and domain-specific languages as well as network protocols. [Slides](https://pfgimenez.fr/files/gtmfs.pdf)
