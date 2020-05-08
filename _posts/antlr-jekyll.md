---
title:  "About ANTLR and its Setup"
date:   2019-03-12
tags: jekyll
---

## Check About ANTLR Setup in Windows

<strong>Another Language Tool for Language Recoginition</strong>(ANTLR) is a parser generator which is used in various operations in binary files or structured text.

It uses **LL parser** which parses input from left to right.

ANTLR takes a grammar as input and generates output source code for a recognizer of that language. The grammar files taken as input are of the type **.g4** an extension which is provided in [this](https://github.com/antlr/grammars-v4).

It supports all type of languages such as Java, C++, Python, Haskell etc. By using these grammar files it generates a parser which can build and parse trees.

**Command**
**antlr4 python.g4** This generates the combined lexer and parser files for python grammar file in python language itself.

Similarly, for specific programming language the lexer and parser files are generated in that same language. Moreover, if you want to create your own language you can make your own grammar version and get your hands dirty.
To build your own grammar versions please check [this link](https://github.com/antlr/antlr4/blob/master/doc/lexicon.md).

**Applications**
1. Twitter uses ANTLR for parsing query everyday.
2. Systems like Hive and Pig uses it.
3. In IDEs like Netbeans which uses ANTLR to parse C++.
4. One can build JSON parsers too with it.

For setting up ANTLR here is the [link to work on](https://github.com/Dhiraj240/ANTLR).
