---
title: "Towards programming languages free of injection-based vulnerabilities by design"
collection: publications
excerpt: "Many systems are controlled via commands built upon user inputs. For systems that deal with structured commands, such as SQL queries, XML documents, or network messages, such commands are generally constructed in a “fill-in-the-blank” fashion: the user input is concatenated with a fixed part written by the developer (the template). However, the user input can be crafted to modify the command’s semantics intended by the developer and lead to the system’s malicious usages. Such an attack, called an injection-based attack, is considered one of the most severe threat to web applications. Solutions to prevent such vulnerabilities exist but are generally ad hoc and rely on the developer’s expertise and diligence. Our approach addresses these vulnerabilities from the formal language theory's point of view. We formally define two new security properties. The first one, “intent-equivalence”, guarantees that a developer’s template cannot lead to malicious injections. The second one, “intent-security”, guarantees that every possible template is intent-equivalent, and therefore that the programming language itself is secure. From these definitions, we show that new design patterns can help create programming languages that are secure by design."
date: 2025-05-15
venue: 'The 11th Workshop on Language-theoretic Security and Applications (LangSec25)'
paperurl: ''
citation: 'Alata, E. & Gimenez, P. F., (2025 May). Towards programming languages free of injection-based vulnerabilities by design. In the 11th Workshop on Language-theoretic Security and Applications (LangSec25).'
---
