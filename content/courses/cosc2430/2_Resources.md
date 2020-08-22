---
title: Resources
linktitle: Resources
toc: true
type: docs
date: 2019-05-05T00:00:00+01:00
weight: "1"
menu:
  cosc2430:
    weight: 2
---

*   [Connect to linux server](https://drive.google.com/file/d/1uWypN3bpi-HEskHhK7GHrlUjyKKudap2/view?usp=sharing)
*   [The first Lab hour video.](https://drive.google.com/open?id=1p4zqRJVi2-kSEpFQ8jO-F0z6TvZg78iz)
*   [waht is the Argument Manager?](https://drive.google.com/drive/folders/1PcZvy1P72nArqj_gmKSX8ELw8jTpe8_N?usp=sharing)
*   Don't know how to install and use SSH on Windows? Follow the instructions [here](http://www.ohlone.edu/org/webcenter/sftptutorial/windowssftp-downloadinstall.html).  
    A video tutorial can be found on [YouTube](https://www.youtube.com/watch?v=mncUlFUiHNM&feature=youtu.be). (Credits to our student **Christopher Holley**, thank you Chris!)
*   A tutorial for SSH on Linux can be found [here](http://support.suso.com/supki/SSH_Tutorial_for_Linux).
*   If you barely used Linux before, you can get a simple hands-on tutorial [here](http://www.howtogeek.com/140679/beginner-geek-how-to-start-using-the-linux-terminal/).
*   You can also take a look at the command-line argument and script file [parser](FAQ/parsers.zip) if you don't know how to do it.


*   **Frequently used linux commands**

*   **ssh username@code.cs.uh.edu** to login. The initial password contains 9 digits, PSID + Captital Initial Last name + Capital Initial First name. It's recommended to use **passwd** to modify the initial passwd. You must remember the password. If you forget the password, you have to go to PGH527 to ask the adminisrtator to reset it. Again, please remember your password.
*   **scp -r file_or_folder username@code.cs.uh.edu:~/hw1/** to upload a file or a folder to hw1 folder on the server
*   **cp 1.txt 2.txt** to copy a file 1.txt to 2.txt
*   **mv 1.txt folder** to move a filename 1.txt to folder
*   **cat 1.txt** to display the content of 1.txt
*   **ls** to list all files and folders in the current directory
*   **cd hw1** to change directory to folder hw1
*   **cd ..** to change directory to the parent folder
*   **cd ~** to change directory to the home directory
*   **nano main.cpp** to edit the file main.cpp
*   **chmod +rx grade.sh** to make grade.sh readable and executable