---
title: Regrading Homework
linktitle: Regrading Homework
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  cosc1430:
    weight: 5

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 4
---

- **Late Submission/Regrading the homework:**
It is an opportunity for the students to enhance their homework submission: 
For example, assume the homework4 deadline is **3/11/20xx**
- **Scenario 1:**
- The code is uploaded under hw4 folder on time, after grading your hw4 grade is 100. No need for regrading
- **Scenario 2:**
- The code is uploaded under hw4 folder **on time**, after grading your hw4 grade is 50 (first grading), - and you want to resubmit
- a.	Modify your code and reupload under the same folder in this case hw4
- b.	Wait for the regrading time
  - 1.\	Two days after the deadline (**3/13**) at the same time (second grading) out of 80%
  - 2.\	Four days after the deadline (**3/15**) at the same time (third grading) out of 50%

   - Using 1. your final grade on hw4 will be: firstgrading +(secondgrading-firstgrading)*80 %
   - If your second grading is 80                                    50 + (80-50) *80/100   = 74

    - Using 1. And 2.:firstgrading +(secondgrading-firstgrading)*80 %  +(thirdgrading-second grading)*50%
    - If your third grading is 100                     50 + (80-50) *80/100  +(100-80)*50/100 = 84 

- **Final regrading at the end of the semester:**
- This is an opportunity to enhance one homework, you can try to enhance all the homework by updating - - all the codes submitted in their respective folders, however only the best regrade will be considered.
- Example Scenario:
- Grades before the final regrade
- Hw1:50     Hw2:70    Hw3:30      Hw4:90
- After regrade 
- Hw1:40     Hw2:80    Hw3:50      Hw4:100
- **Final Grades** 
- Hw1:50     Hw2:70   **Hw3:50**      Hw4:90   **Hw3 has the best regrade** (Only this grade will be uploaded)

 
  










- **cp 1.txt 2.txt** to copy a file 1.txt to 2.txt
- **mv 1.txt folder** to move a filename 1.txt to folder
- **cat 1.txt** to display the content of 1.txt
- **ls** to list all files and folders in the current directory
- **cd hw1** to change directory to folder hw1
- **cd ..** to change directory to the parent folder
- **cd ~** to change directory to the home directory
- **nano main.cpp** to edit the file main.cpp
- **chmod +rx grade.sh** to make grade.sh readable and executable

- **programming rules**

- Do always follow the homework specification. Do not using some cheating skills. For example your bubble sort and selection sort are the same. Once detected, 0 for the homework.
- Do not use int main() or void main(). Do use int main(int argc, char\* argv[]).
- Do not use hard coding. For example, file.open("1.txt");
- Do not halt or wait user's interaction. For example, system("pause");
- Do not submit your homework in the blackboard
- Do test your program in the Linux server before you submit the homework
- Do design and test testcases as many as possible. Your program may pass easy testcases but fail for hard testcases
- Your code will probably reuse in the next homework.
- Do not share and copy code. If you use some code in the internet or book, disclose it in your code, otherwise you are cheating! Once detected, F for the course grade, at least.
