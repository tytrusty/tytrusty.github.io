---
layout: post
title: Week of 3 Apr - 9 Apr
---

### What did you do this past week?
Last week I mostly spent my time finishing up the Darwin project for OOP. I'm glad my partner and I spent a lot of time planning the design as it made implementation extremely easy. As a result, things went smoothly and I had a decent amount of time to review my project before the deadline. Although, one thing I had difficulty with was the UML, so there's a chance I will lose points for that portion. 

This weekend I had a ton of fun working on a new project. Miraculously, the stars aligned and I had a (mostly) free weekend, so I wanted to work on something moderately big. For last week's blog, I posted an article about the programming language pipeline, which got me interested in making my own language. My plan was to make a language that was extremely unintuitive, difficult to code, and difficult to read. I therefore decided to work on a language where all expressions looked like ASCII emoticons. 

So, I started off looking at all the tools like Flex, Bison, and LLVM, but there was way too much information to digest. I figured it would be easier to do the tokenization and parsing myself (and it was). My language ([github link](https://github.com/tytrusty/emoticon-language)) pipeline was lexing (read tokens), parsing (build Abstract syntax tree), then transpiling (convert my language to c code). Given I've only worked on it for two days now, not much is implemented. However, I implemented basic integer initialization and comments. 

Here's an example of what I have working: 
```
(#_#)              this is a comment
(#_#)--*           this is a multi-line comment *--(#_#) 
o \(^-^)/ 5  (#_#) this is assignment
```
The above code produces the c code: `int o = 5;`

### What's in your way?
Right now the quizzes are the main thing in my way since I've been making some stupid mistakes on them lately. On last Monday's quiz, for example, I missed a question asking for the signature of one of vector's constructors, which should be a freebie. It's approaching the end of the quizzes so I'm starting to slack. For this week, I'm going to make sure I'm much more prepared. 

### What will you do next week?
I'm looking forward to working on the next project in OOP. Starting on the Darwin project early gave me plenty of time to relax and enjoy the project, so I plan to do this for the Life project too. Outside of OOP, I also need to do a programming assignment for Intro to Computer Security. 

### What's my experience of the class?
Besides my recent hiccups in the quizzes, class has been great. I've really enjoyed learning about the Vector class implementation. I hope we get the chance to learn about abstract classes and the virtual keyword because when I was working on my personal project, I was struggling with these concepts.

### What's my pick-of-the-week or tip-of-the-week?
My pick of this stackoverflow [http://stackoverflow.com/questions/38060436/what-are-the-new-features-in-c17](http://stackoverflow.com/questions/38060436/what-are-the-new-features-in-c17) explaining the new features in C++17.
