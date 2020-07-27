---
title: Homework Grading
linktitle: Homework Grading
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  cosc2430:
    weight: 4

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

- **How to submit your homework**
  - 1\. Create a folder named exactly the same as hw1, hw2, hw3...
  - 2\. There should not be any folders inside the homework folder hw1, hw2, hw3...
  - 3\. It's mandatory to upload your .cpp and .h files to the homework folder.
  - 4\. You can create practice folders on Linux server with any name except for hw0~hw5\.

  
- **How to test your programe**

**./grade.sh**

- **How to check your grade** There are two methods.
  - **cd hw1-archive**
  - **cat GRADE**
  - **cat COMPILE.err** #display the compile error if GRADE is 0, otherwise the file COMPILE.err will not exist.
  - **cat 1.out** # display your program output of test case 1
  - **cat 1.ans** # display the standard answer of test case 1
  - **cat 1.diff** # display the difference between the 1.stdout and 1.ans
  - Or you can use the following commands to check the grading (This way is easier)
  - **cp -r hw1-archive hw1-check** # you do not have write access to the archive folders, that's why you need to copy.
  - **cd hw1-check**
  - **./grade.sh**



*   **How we grade your homework**

*   1\. We first copy your homework and the grading test cases to a folder name like "hw1-archive", then we grade your homework in the archive folder. The grading test cases are unknown for you.
*   2\. We use `g++ -std=c++11 *.cpp -o programe_name` to compile your homework, where the programe_name is specified in the homework
*   3\. We use `diff -iEBwu 1.stdout 1.ans` to determine whether you pass the test case 1 or not, where 1.stdout is your output, 1.ans is the standard output. The command will ignore the spaces and blank lines. Generally, you will get 10 points for each test case, 90 in total
*   4\. If your code can compile, then you get 10 points, otherwise you will get 0 for the homework.


- **programming rules**

- Do always follow the homework specification. Do not use any cheating skills. For example your bubble sort and selection sort are the same. Once detected, the grade of the homework will be zero.
- Do not use int main() or void main(). Do use int main(int argc, char\* argv[]).
- Do not use hard coding. For example, file.open("1.txt");
- Do not halt or wait user's interaction. For example, system("pause");
- Do not submit your homework in the blackboard.
- Do test your program in the Linux server before you submit the homework.
- Do design and test testcases as many as possible. Your program may pass easy testcases but fail passing hard testcases.
- Do not share and copy code. If you use some code from the internet or book, disclose it in your code, otherwise this is considered as cheating! Once detected, the grade of the homework will be F.
