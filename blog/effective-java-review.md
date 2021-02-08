---
published: false
cover: /post-images/effective-java-review.jpg
date: 2021-02-08T20:42:56.834Z
title: Effective Java Review
canonical_url: ''
category: Tech
tags:
  - java
  - coding
  - best practices
---
# Preface

Learning a new program language is similar to learning a new language, you need to know the language structure or grammar, how to name things or vocab, and how to say them properly or usage. Programming requires to know the core of the language, like is it Object oriented or functional, it's data structures and operations provided in its standard libaries, and how to use them by structuring your code.

"The Java programming language, for example, is object-oriented with single inheritance and supports an imperative (statement-oriented) coding style within each method. The libraries address graphic display support, networking, distributed computing, and security..."

Additionally, programs change over time, so we must be able to easily modify the code by structuring it properly.

You can read: "The Java™ Language Specification by Gosling, Joy, yours truly, and Bracha." for the first two parts of learning the language, this book is for #3.

"I naturally think in terms of exported APIs (Application Programming Interfaces), and I encourage you to do likewise. Even if you aren’t developing reusable components, thinking in these terms tends to improve the quality of the software you write. Furthermore, it’s not uncommon to write a reusable component without knowing it: You write something useful, share it with your buddy across the hall, and before long you have half a dozen users."

He notes tihs is different then what's stated in something like _Extreme Programming_ since it would require flexible design for something not created yet.

## Introduction

### Standards
1. Clarity and simplicity are paramount
1. Components should be as small as possible but no smaller
1. Code should be re-used rather than copied
1. Errors should be detected as soon as possible after they are made

"Learning the art of programming, like most other disciplines, consists of first learning the rules and then learning when to break them."


### How things are referenced

"Class instances and arrays are objects; primitive values are not. A class’s members consist of its fields, methods, member classes, and member interfaces. A method’s signature consists of its name and the types of its formal parameters; the signature does not include the method’s return type."


#### Expanded Examples

https://github.com/jbloch/effective-java-3e-source-code