---
{"dg-publish":true,"permalink":"/programming-logic/"}
---


To begin to understand programming logic you need to understand how programming a computer actually works. How do we give a computer instructions? How does the computer process those instructions?

## Binary

We communicate with computers using a binary number system consisting of 0 and 1, with a **bit** being each individual binary digit. Computers are made up of billions of transistors that can be switched on and off, manipulating the flow of electricity. A bit is represented by turning a particular switch on or off to represent a 0 or 1. Different types of information is conveyed using patterns of 1s and 0s.

## Algorithms

The next step in understanding programming is understanding the **algorithm,** the step by step instructions that we, as programmers, feed to the computer allowing it to solve a problem ([[Programmers Solve Problems\|Programmers Solve Problems]]) (transforming input to output). It’s funny that I had always heard so much about the algorithm and it was always made to seem like such an illusive thing. Probably because no one ever knows how google’s seo algorithm works. But, though the practice is hard, it’s really such a simple concept.

An algorithm can be written in any programming language, expressed using a flow chart, or with pseudocode.

## Pseudocode

If you had to be completely fluent in one language and one language only, it should be **pseudocode**. Okay, that’s kind of a trick answer since pseudocode isn’t really a language at all. It consists of writing out the algorithm, the steps that the computer must perform, in your own written/spoken language.

The example below from CS50 covers the important elements common to all programming languages. It’s best to write your pseudocode with the terms used in most languages such as if, else if, else as well as the proper indents.

-   Actions / verbs — pick up, open, look — are referred to as **functions**.
-   Branches that lead to different paths — if, else if, else — are called **conditionals**.
-   Questions that decide where we go, true/false statements — is earlier, is on, is later — are **expressions**.
-   Words that make us repeat parts of the program — go back to — are **loops**.

Pick up phone book
Open to middle of phone book
Look at page
	If person is on page
		Call person
	Else if person is earlier in book
		Open to middle of left half of book
		Go back to line 3
	Else if person is later in book
		Open to middle of right half of book
		Go back to line 3
	Else
		Quit

**Planted:** 1/18/23  
**Last Tended:** 1/18/23  
**Status:** 🌿 #growing