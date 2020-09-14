---
layout: project
title: Functional Programming for Systems Software
date: 14 September 2020
image:
    path: /assets/img/projects/honors-thesis.png
caption: Implementing Baremetal Programs in Habit
description:
links:
    - title: Paper
      url: https://pdxscholar.library.pdx.edu/honorstheses/
    - title: C Implementation
      url: https://github.com/dvaneson/paging
    - title: LC Implementation
      url: https://github.com/dvaneson/paging-lc
featured: false
---

## Summary

This thesis presents a case study of Habit, a functional language with built-in
functionality for low level programming. Habit was designed at Portland State
University by the High Assurance Systems Programming team, aiming to bridge the
gap between a high-level language that minimizes potential errors and the low
level capabilities and efficiency of a language like C. To test how well Habit
meets this goal I implemented a page table in both C and a prototype of Habit,
LC, to compare and contrast the implementations. I found Habit to be an
interesting and potentially powerful language, but also unfortunately encounterd
a bug in the compiler that prevented me from finishing the page table. There
were also some feature gaps I felt should be addressed, that I discuss in the
paper. My hope is to see the continued development of Habit so that it becomes a
more reliable and fleshed out language.
