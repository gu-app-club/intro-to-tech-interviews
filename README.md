# Intro to Tech Interviews

This document is a rough overview for a potential class for tech interviews, written by senior GU undergrads. 

## What are technical interviews?
If you want to really experience what students are going through, before you read any further, go [take this](https://leetcode.com/problems/longest-substring-without-repeating-characters/description/) challenge. (Set a timer for 20 minutes and complete it before it goes off)


When a student applys to an internship or post-grad job, nearly every company will give them a "technical interview" on top of a behavioral interview. Unlike a behavioral interview, a technical interview focuses around solving 1 or more code challenges. These will often ask the student to solve a problem with a certain algorithm or data structure. Or they might give a problem statement and have the student figure out what algorithm and data structure is required. 

A simple interview question might be:

``` 
Reverse a binary tree.
```

A more complicated interview question might be:

```
Given a 2 dimensional array of 1's and 0's such as:

[
    [00001110],
    [00001110],
    [00000000],
    [01100000],
]

Let's say that the 1's are "land" and the 0's are "ocean". 
Write a program that counts the number of land masses where a land mass 
is defined as a piece of land surrounded on all sides by water. You can assume 
that the edges of the array are water.
```

### Structure of the interview

#### Automated
Many companies use services like [Hackerrank](https://www.hackerrank.com/) to test their candiates remotely without any person. The student will recieve the test in their email and then be able to take it at any time they would like. However, once you start the test, you often need to complete it within a certain time limit. (Generally within an hour or 30 minutes.) Often times, this is a race against the clock.

#### Phone interviews
Some companies will call the student and have them do a code challenge with an engineer on google docs or a code sharing website. Often times this code doesn't actually have to run and the student can ask the interviewer questions.

#### White board interviewers
If the company is local or flys the student out to their location, the student will likely do their coding on a whiteboard. These are similar to the phone interview, but often times there can be several other engineers watching. 

## Goals of this class
* Inform students about the concept of technical interviews (both in person and automated)
* Provide a venue for students to practice code challeneges both in person and on their own
* Calm student fears and guide them away from unhealthy panic
    * Avoid [/r/cscareerquestions](http://reddit.com/r/cscareerquestions)
    * Apply to many places to avoid getting caught up in a single job offer
    * Practice to avoid test anxiety

## What is expected from a professor and class
In general, the class should briefly cover subjects and provide interview questions that relate to them. Data structures and algorithms implementation details can be glossed over (as other classes go into those in more depth).

### Briefly review previously covered data structures and algorithms
* Brief section on Big O
* Hashsets and Hashtables (Usage and efficiency, NOT implementation)
* Queues and Stacks (Usage and efficiency, NOT implementation)
* Simple trees (Usage and efficiency, NOT implementation)
    * Avoid balanced trees such as red/black, they very very infrequently come up in interviews

### Brief Overview of subjects that are NOT normally covered
* Breadth first and Depth first search
* Dykstras and A* Search
* Tries
* Dynamic Programming

## What is not expected from a professor or class
We don't expect professors to have signifigant experience interviewing for industry jobs. Nor do we expect them to know anything about resumes, applications, companies, or anything else. The career center is quite good at handling these things and so we should let them do it.

This class should not require any serious grading. Asking students to do coding challenges is fine, but in general, let the students be self driven. The professor should act as proctor and share their knowledge of core computer science topics. 

## Previously created guides and resources

GUMAD and other groups have been working hard to help create resources for students.

### Websites
* [GUMAD's Lets-Learn-Jobs Comprehensive Guide](https://gu-app-club.github.io/lets-learn-jobs/)
* [GUMAD's introduction to Trie's](http://trie.now.sh/)

### Books
* [Cracking the Coding Interview (AKA: The bible)](http://www.crackingthecodinginterview.com/)

### Places to practice coding challenges
* [Leetcode](https://leetcode.com/)
* [HackerRank](https://www.hackerrank.com/)

## Potential class structure

### Each Day
* Cover a topic 
* Bring a student up to the front of the class to do an interview question
* Have other students do it while they're doing it

### Homework for each day
Do one coding challenge on Hackerrank / Leetcode (Time yourself preferably).

### 15 week Schedule
* Week 1 - Introduction to what code challenges are
    * HW: Do Strings / Arrays problems [Examples](https://leetcode.com/tag/string/)
* Week 2 - Brief overview of Big O
    * HW: Do Strings / Arrays problems, but write down your Big O for the question
* Week 3 - Hashsets and Hashtables (Things with O(1) lookup)
    * HW: Do problems involving sets or hashtables. [Examples](https://leetcode.com/tag/hash-table/)
        * Example problem: Find first repeated item in the list
* Week 4 - Queues and Stacks
    * HW: Do problems involving Queues and Stacks [Examples](https://leetcode.com/tag/stack/)
* Week 5 - Trees
    * HW: Do problems involving Trees [Examples](https://leetcode.com/tag/tree/)
* Week 6 - Tries / Prefix trees
    * HW: Do problems invovling Tries [Examples](https://leetcode.com/tag/trie/)
* Week 7 - Breadth first and depth first search
    * HW: Do problems involving graph theory and searching [Examples](https://www.hackerrank.com/domains/algorithms/graph-theory)
* Week 8 - Do Dykstras and A* Search
    * HW: Do problems involving Dykstras and A* Search 
* Week 9 - Dynamic programming
    * HW: Do problems involving dynamic programming [Examples](https://www.hackerrank.com/domains/algorithms/dynamic-programming)
* Week 10 - Generic Practice 
* Week 11 - Generic Practice
* Week 12 - Generic Practice
* Week 13 - Generic Practice
* Week 14 - Generic Practice
* Week 15 - Generic Practice

## On Prerequisites
There should be none. This really should be a course that students take because they feel like they're ready. Whether you're applying for a job as a freshman, sophmore, junior or senior you will often be asked similar questions.

While it would be incredibly helpful to have had data structures and advanced data structures, it's not always necessary and many students will have to learn quickly if they would like an internship early on. 

In other words, it should probably be aimed at seniors and juinors and allow sophmores and freshmen to join if they would like. 
