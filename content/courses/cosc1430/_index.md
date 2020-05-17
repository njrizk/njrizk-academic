---
# Course title, summary, and position.
linktitle: COSC 1430 - Introduction to Programming 
summary: Learn how to Program in C++
weight: 1

# Page metadata.
title: Overview
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

menu:
  cosc1430:
    name: Overview
    weight: 1
---

Put your overview info here.

*   **How we grade your homework**

*   1\. We first copy your homework and the grading test cases to a folder name like "hw1-archive", then we grade your homework in the archive folder. The grading test cases are unknown for you.
*   2\. We use `g++ -std=c++11 *.cpp -o programe_name` to compile your homework, where the programe_name is specified in the homework
*   3\. We use `diff -iEBwu 1.stdout 1.ans` to determine whether you pass the test case 1 or not, where 1.stdout is your output, 1.ans is the standard output. The command will ignore the spaces and blank lines. Generally, you will get 10 points for each test case, 90 in total
*   4\. If your code can compile, then you get 10 points, otherwise you will get 0 for the homework.


