# csc3320-system-level-programming-lab-assignment-3-post-lab-solved
**TO GET THIS SOLUTION VISIT:** [CSC3320 System Level Programming Lab Assignment 3 (Post-Lab) Solved](https://www.ankitcodinghub.com/product/csc3320-system-level-programming-lab-assignment-3-post-lab-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114261&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC3320 System Level Programming Lab Assignment 3 (Post-Lab) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
th

Purpose: Learn how to set permissions for the files and directories. Practices on editing a file via the vi editor.

Note: Please follow the instructions below step by step, and then write a report by

answering the questions and upload the report (named as

Lab3_FirstNameLastName.pdf or Lab3_FirstNameLastName.doc) to Google Classroom, under the rubric Lab 3 Out-of-lab Assignment.

Please add the lab assignment NUMBER and your NAME at the top of your file sheet. Part 1: VI Editing – Small file

Open your terminal and connect to snowball server. Change your directory to your home directory (cd ~ ), and then create a new directory named as “Lab3” (mkdir Lab3). After that, go to directory Lab3 (cd Lab3) and please download the file “Try.c” (content shown in table below) by the following command (internet access required):

cp /home/bbello1/Public/Try.c Try.c

Be sure it succeeds using “ls” to see the file name “Try.c” listed.

Try the following steps by issuing some commands in your vi editor 1) Open “Try.c” with vi editor

$vi Try.c

2) Move cursor to the beginning of “Error!” use UP DOWN LEFT RIGHT arrow to control cursor

3) Insert “xxx”.

i

type “xxx” (hit x three times)

4) Append a blank line after the current line.

Hit Esc to command mode o (lowercase

o)

5) Delete “xxx”.

Hit Esc to command mode.

Move cursor to the beginning of “xxx”, press x three times or press 3s to delete “xxx”

6) Copy the first 2 lines, move cursor to the beginning of file, and then paste it after current line

:1,2y

:0 p

7) Delete the first 2 lines

:1,2d

8) Save it

:w

9) Replace all “fptr” with “FPTR”

:1,$s/fptr/FPTR/g

10) Save and exit.

:wq

Part 2: VI Editing – Large file

1) Go into your Lab3 directory.

$cd ~/Lab3

again.

$cp /home/bbello1/Public/RealEstate.csv .

Please write the commands you will issue to complete the following tasks and answering corresponding questions step by step in your report. 3) Use vi to open “RealEstate.csv”.

4) Move the cursor to the last line (without knowing the number of last line).

5) Display line number.

6) Search for the transaction for the estate located at “111 EAST”

Which line is this string located? (Please just write down the line number) Delete this line.

7) Move the cursor to the line 50.

8) Substitute all comma “,” with colon “:” from line 50 to line 54.

9) Copy line 50 to line 54 to the end of file.

10)Remove line 50 to line 54.

11) Describe how to enter the text mode and insert a new line “Recorded inyear 2008” between line 1 and line 2.

12) Switch back to command mode.

13) Save the file and quit vi.

Part 3: Permissions for files

Follow the instructions step by step and finish the questions as required. 1) Go into your Lab3 directory.

$cd ~/Lab3

2) Check the file permissions for file “Try.c” in your own Lab3 directory. $ls -l Try.c

The leftmost 3 characters rw- tells us that the user (owner of the file) can only read and write the file.

The middle 3 characters rw- tells us the other users in the same group as the owner can only read and write the file.

The last 3 characters r– tells us the other users in the other groups different from owner can only read the file.

Note: once you copy a file from other directory or download a file from other resources, you are the owner of the new copied or downloaded file.

4) Remove the read permission for the owner (yourself). $chmod u-r Try.c

5) Check the file permissions for file “Try.c” again.

$ ls -l Try.c

So -w- in the leftmost 3 characters tells us that the user (owner of the file ) only has the permission to write something into the file.

7) Try the vi editor again to modify the file. $vi Try.c

9) Quit vi editor.

:q

10) Try read “Try.c” again using cat.

$cat Try.c

Attach a screenshot of the output.

11) Use chmod with an octal number to let all the users only have readpermission for “Try.c”.

$chmod 444 Try.c

Note: The permission string to be set should be r–r–r–. Convert each group of three characters into decimal to form an octal number, which should be 444.

12) Check the file permissions for file “Try.c” again. And explain themeaning of each character in the file permission string.

13) Try the vi editor again to modify the file. Then remove one line bypressing dd

$vi Try.c

Move your cursor to some line and press dd

14) Try to save the file in the vi editor.

:w

15) Can you find some error message at the bottom of the screen? Ifyes, what is it and how to quit the vi editor without saving the modification.

Write answer in your answer sheet.

16) Use chmod to add write the permission to all the users for”Try.c”.

Write answer in your answer sheet.

17) Check the file permissions for file “Try.c” again. And explain themeaning of each character in the file permission string.

Write answer in your answer sheet.

Part 4: Permissions for directories

Let us learn the permissions for directories by only changing different permissions to the owner of the file.

1) Go to your home directory and then check the permissions fordirectory Lab3. $cd ~

$ls -ld ~/Lab3

Note: -d option will let you check the detailed information for the directory instead of its contents.

3) Use chmod with octal number to forbid all permissions to allusers. $chmod 000 ~/Lab3

5) Finishing the following tasks and fill out the blanks in the row forowner’s permission “—” in the table below. If the task or command can be executed successfully, mark Y in the table, otherwise, mark N in the table. Please mark N/A if the task or command is not executed.

A. Check the contents in directory Lab3.

$ls ~/Lab3

B. Create a directory named as “test” in Lab3.

$mkdir ~/Lab3/test

C. Create a file named as “test.txt” in Lab3.

$cat&gt;~/Lab3/test.txt

A test

^D

D. If (B) succeeds, remove the created directory “test” of Lab3. $rm -r ~/Lab3/test

E. If (C) succeeds, copy “test.txt” from your Lab3 into your home

directory. $cp ~/Lab3/test.txt .

F. Go into directory Lab3.

$cd ~/Lab3

The blanks in row “—” have been filled out in the table. Please compare it to your answers.

For example, since owner’s permissions is –x at next row, we should first set the file permission by issuing the command chmod 100 ~/Lab3. And then fill out the blanks in the row for permissions –x by repeating 5).

Appendix:

Table: The mapping of permissions of three characters to octal/decimal
