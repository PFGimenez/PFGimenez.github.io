---
title: "Towards programming languages free of injection-based vulnerabilities by design"
collection: talks
type: "Talk"
venue: "Séminaire PIRAT"
date: 2024-10-24
location: "Rennes, France"
---

Many systems are controlled via commands built upon user inputs. For systems that deal with structured commands, such as SQL queries, XML documents, or network messages, such commands are generally constructed in a “fill-in-the-blank” fashion: the user input is concatenated with a fixed part written by the developer (the template). However, the user input can be crafted to modify the command’s semantics intended by the developer and lead to the system’s malicious usages. Such an attack, called an injection-based attack, is considered one of the most severe threat to web applications. Solutions to prevent such vulnerabilities exist but are generally ad hoc and rely on the developer’s expertise and diligence. Our approach addresses these vulnerabilities from the formal language theory's point of view. We formally define two new security properties. The first one, “intent-equivalence”, guarantees that a developer’s template cannot lead to malicious injections. The second one, “intent-security”, guarantees that every possible template is intent-equivalent, and therefore that the programming language itself is secure. From these definitions, we propose new techniques to create programming language that are secure by design, and present two secure, simplified versions of widespread languages.
