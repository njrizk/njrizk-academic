---
title: Resources
linktitle: Resources
toc: true
type: docs
date: 2019-05-05T00:00:00+01:00
weight: "1"

---
*   [The first Lab hour video.](https://drive.google.com/open?id=1p4zqRJVi2-kSEpFQ8jO-F0z6TvZg78iz)
*   Don't know how to install and use SSH on Windows? Follow the instructions [here](http://www.ohlone.edu/org/webcenter/sftptutorial/windowssftp-downloadinstall.html).  
    A video tutorial can be found on [YouTube](https://www.youtube.com/watch?v=mncUlFUiHNM&feature=youtu.be). (Credits to our student **Christopher Holley**, thank you Chris!)
*   A tutorial for SSH on Linux can be found [here](http://support.suso.com/supki/SSH_Tutorial_for_Linux).
*   If you barely used Linux before, you can get a simple hands-on tutorial [here](http://www.howtogeek.com/140679/beginner-geek-how-to-start-using-the-linux-terminal/).
*   You can also take a look at the command-line argument and script file [parser](FAQ/parsers.zip) if you don't know how to do it.


*   **How we grade your homework**

*   1\. We first copy your homework and the grading test cases to a folder name like "hw1-archive", then we grade your homework in the archive folder. The grading test cases are unknown for you.
*   2\. We use `g++ -std=c++11 *.cpp -o programe_name` to compile your homework, where the programe_name is specified in the homework
*   3\. We use `diff -iEBwu 1.stdout 1.ans` to determine whether you pass the test case 1 or not, where 1.stdout is your output, 1.ans is the standard output. The command will ignore the spaces and blank lines. Generally, you will get 10 points for each test case, 90 in total
*   4\. If your code can compile, then you get 10 points, otherwise you will get 0 for the homework.