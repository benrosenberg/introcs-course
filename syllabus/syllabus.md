---
title: "Intro CS Syllabus: 7-week course"
author: Ben Rosenberg
date: \today
geometry: margin=1.0in
toc: true
---

[[PDF version]](syllabus.pdf)

# Welcome!

Welcome to CS XXXX! The way this class is graded is designed to help you. Please read the syllabus in its entirety so that you have a good idea of what will be covered throughout the class.

# Logistics

## Lectures, discussions, office hours

Lectures will be delivered in-person in [insert room name here], on [insert days of the week here] at [insert time here]. Discussion sections will be held in [insert room name here] at [insert time here] on [insert days of week here].

Office hours will be held in-person in [insert room name here] on [insert days of week here] from [begin time] to [end time].

## Course materials

All course materials can be found on the course website (NOT on Canvas or Blackboard or Aspen or Classroom or what have you). They are as follows:

 - This syllabus
 - Lecture notes
 - Exam practice
 - Assignment files and due dates
 - Course calendar

There are more materials than just those listed above on the website if you want to look around.

## Prerequisites

Since this is an introductory CS course, no previous knowledge of computer science is required or assumed. All that we ask is that you are familiar with at least calculus (you should have a MATH 1110-level knowledge of mathematics).

## Extensions and drops

There is a zero-tolerance policy for lateness. Extensions will only be honored if there is a letter from SDS that can be provided to back up your case. 

You get 2 assignment drops in this course. Since there are only 5 assignments in the course overall, these are not typical drops: they can only be used if you actually tried to do the assignment, and thus you can only use a drop if you got a 70 or more on a given assignment. Any score below a 70 will be counted as-is, and not dropped. 

## Class discussion forum

This class will use Ed Discussions as its forum. The link will be posted on the website.

# Topics covered and exams

Time/exam | Coverage
-|---
Week 1 | Variables: Types, Assignment
Week 1  | Strings and lists
Week 2  | Conditionals
Week 3  | Loops: For loops, While loops, Break and continue
EXAM 1 | Weeks 1-3
Week 4  | Functions
Week 5  | Generators
Weeks 6, 7  | Functional tools: Lambdas, Map, List comprehension, Filter, Reduce
EXAM 2 | Weeks 1-7

# Grading rubric

## Participation

Participation includes lecture questions (both answered and asked) and (helpful and constructive) Ed Discussions activity. It will be worth 5% of the course grade.

## Assignments 

There will be one assignment every week, except for those weeks on which there are exams. Since this is a 7-week course, that means there will be 5 assignments. Assignments will be available on the course website two weeks before they are due, with the exception of the first assignment. Generally, the first week after the assignment is made available, the relevant material will be taught in lecture, while in the second week, the assignment should be worked on and handed in. Material on assignments may show up on exams, so doing them will be helpful in increasing your exam grades.

Your final assignment grade $a$ will be calculated using the following equation, given sorted (ascending) list of undropped assignment numbers $u$:

$$a = \begin{cases}
    0.17 \cdot u_0 + 0.33 \cdot u_1 + 0.50 \cdot u_2 & 5 - |u| = 2 \\ 
    0.10 \cdot u_0 + 0.20 \cdot u_1 + 0.30 \cdot u_2 + 0.40 \cdot u_3 & 5 - |u| = 1 \\
    0.06 \cdot u_0 + 0.13 \cdot u_1 + 0.20 \cdot u_2 + 0.27 \cdot u_3 + 0.34 \cdot u_4 & 5 - |u| = 0
\end{cases}$$

Note that the when the assignments are being sorted, they are being sorted not by your grade on them but rather the indices of the assignments themselves; e.g., if you drop assignments 2 and 4, and you receive grades of 80, 88, and 85 on assignments 1, 3, and 5 respectively, your grade will be $a = 0.17 \cdot 80 + 0.33 \cdot 88 + 0.50 \cdot 85 = 85.14$, and **not** $0.17 \cdot 80 + 0.33 \cdot 85 + 0.50 \cdot 88 = 85.65$.

## Exams

There are two exams: one which covers the first three weeks of class, and a cumulative final exam. Practice exam material will be released one week in advance of each exam. There will be a lecture exclusively on reviewing material for the exam before each exam, during which questions can be asked. If you require special accomodations for exams, please send an email or make a private Ed post far in advance of the first exam (at least 2 weeks before) so that we can prepare the accomodations.

## Final grade calculation

Your final grade will be calculated using the following expression:
$$0.05 \cdot p + 0.45 \cdot a + 0.20 \cdot \min(e_1, e_2) + 0.35 \cdot \max(e_1, e_2)$$

In the above equation, $p$, $a$, $e_1$, and $e_2$ are your grades out of 100 for participation, assignments, the first exam, and the final exam, respectively. This class is curved as follows:

points | letter grade
-|-
100 | A+
96 | A
92 | A-
88 | B+
84 | B
80 | B-
76 | C+
72 | C
68 | C-
64 | F

Read the above table in the following manner: it is guaranteed that, given that the expression above evaluates (when your grades are plugged in) to at least the point value on the left, you will receive at least the grade on the right. Note that it is possible to get over an 100 in this course, as $0.05 + 0.45 + 0.20 + 0.35 = 1.05 > 1$, so it is indeed possible to get an A+ provided that you do exceptional work.

We reserve the right to deviate from this grading scale when we deem it necessary given certain circumstances, but given the exceedingly clear nature of this grading scale, we will not be answering questions about letter grades (or honoring requests for grade "round-ups").

# Academic integrity

If we find that academic integrity is being violated in any way, the following occur as a consequence:

AI violated on | AI consequence
-|---
in-class questions | no consequence. collaboration is encouraged!
assignments | negative 100% on the assignment and note on transcript. assignments on which AI was violated will (obviously, as a result of the drop floor) not be dropped and will thus cause you to lose a significant amount of points on your final grade.
exam | failure of the course.

Note that the sharing of course materials (anything that can be found on the website, or exams) without proper attribution or with perceived AI-violating intent will be considered an AI violation as well, the consequences for which will be considered on a case-by-case basis.