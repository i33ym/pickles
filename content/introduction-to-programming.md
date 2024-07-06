+++
title = "Introduction to Programming"
date = 2024-07-01
weight = 2

[taxonomies]
categories = ["Software"]
tags = ["introduction to programming", "racket", "beginner"]

[extra]
author = "Isroil Muhitdinov"
+++

Programming is the math of the 21-century. Anyone equipped with grounded understanding of it definitely has an extra advantage in any competetive endavor of science and logic.
<!-- more -->

In this course of Introduction to Programming students are taught to be able to formulate, communicate their thoughts and ideas through computer code. In this course, we use a beginner-friendly yet at the same time extremely practical programming language called [Racket](https://racket-lang.org). The course is designed to be completed in 6 months. Successful completion of the course means that students have strong understanding and usage of the fundamentals of programming and they are ready to embark on the journey of becoming industry-ready software developers.

```racket
(define out (open-output-file "./taswiya/introduction-to-programming.txt"))
(display "Please enter your name: ")
(define name (read))
(display (format "Welcome to the \"Introduction to Programming\" course, ~a.\nWe're glad to have you on board!", name))
(close-output-port out)
```
