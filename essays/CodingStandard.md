---
layout: essay
type: essay
title: "Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2024-09-25
published: true
labels:
  - Coding
  - ESLint
  - Standards
---

## Introduction

While many coding languages are fairly similar to learn and implement, the main differences lie in minuscule things such as spacing, brackets, and just formatting in general. This can be thought of as “Coding Standards”. While I understand why people don’t really care for the nitty-gritty of the formatting for the programming language, at times I definitely don’t; I can understand the benefits that come along with implementing “Coding Standards”. These past couple of assignments I got first-hand experience with executing the correct coding standards through the use of VSCode and ESLint.

## Initial Impression
	
After getting through all the issues with setting up VSCode as an environment and redownloading npm like 10 times, I was able to get practice in the full process of using git, VSCode, and ESLint. When completing assignments and WODs on TypescriptPlayground, I was under the impression that Typescript was a very relaxed programming language when it comes to formatting. I felt like I could get away with not putting types for functions, spacing, no semi-colons, etc., and my program would run perfectly fine on Typescript Playground. However, since using VSCode and ESLint, I see that I was completely wrong. Within the first few lines, I was getting a bunch of red squiggles for things that I thought were completely okay. At first, I was getting frustrated with thinking I was doing something completely wrong with the code but just found out the errors were pertaining to small errors like having to add a trailing return, adding spaces before the brackets, etc. However, the more I used it, I saw how it was able to make sure my code was sound with things like ensuring code types from functions.

## Experience and My Perspective


While I did find some of the standards pretty tedious and almost just over the top, I felt that there are some useful ones in there to help me to better my code and good for my practice. For example, I believe on the E27 assignment one of the functions, “zipList”, we were tasked to alternate taking values from two different lists (one numbers and the other string) and essentially “zipping” them into one. At first, I tried not to define a type for the input arrays so that it would allow any type of array as input. However, ESLint said that it needs to be defined. After some searching I found you can use “any[]” in Typescript, but unfortunately our version was not allowing it. The solution I found was I can do “number | string []” so it allows for either a number array or a string array. Though it wasn’t a solution for all types of arrays to be inputted, it helped me to get a better understanding of what is allowed and what isn’t in formatting. For me I think I view ESLint as a way to make sure that my code is sound and use it to almost double check that my functions are operating/returning what they are supposed to.

ESLint and maintaining the coding standard can be a little tedious and irritating to correct since it alerts at every little coding standard; however, I think it is good for helping students learning the new language. It helps get repetitions as to what the code is supposed to be formatted like and ensuring that functions are returning correctly. If working in a group and sharing parts of code, coding standards ensure that all code is up to a proper standard for everyone to follow which will help to mitigate error and confusion.