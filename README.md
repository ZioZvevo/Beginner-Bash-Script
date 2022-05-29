# Beginner-Bash-Script
Hello! This is my first Repository on GitHub, but its also just my first bash script. Its very simple, but a beginner can identify the for loops, if statements, and variable use, as well as basic bash commands such as echo. This simple bash script is used to learn the very basics of bash.

Please note that the text "delete all files" does not trigger the deletion of files. 
The real command to delete the files which can be found at the bottom of the code is: rm -rf /storage/emulated/0

NOTE: In order to not have any accidental deletions of user data, i commented this rm -rf command and added a "1" in the middle.
This way, we are all sure that the files will not be deleted.

Other than that, this script is intended to:

Showcase For loops

Showcase echo command to display and print text

Use if statements and variables to structure the script

Using basic bash commands such as sleep.

Notes:
sleep command is added in order to have a delay in the script. For example,
"sleep 5" pauses the script for 5 seconds. This is useful if wanted to pause the script when there is something to read.

variablename=variablevalue is the format of variables. As you can see, enter=0 at the start of the program, but turns into enter=1 when the script reads that the user presses ENTER.

The read enter command is used with read -p.

In order to space certain parts of the script out so it didn't look like a mess, I added for loops with "echo" followed by a space.
Using for loops, i was able to space the text out by 2 spaces, as I did for i in 1 .. 2 command.

Note that the 2 in this example can be any specificed number you give it.

I am not sure if there are better ways to space out the script, but there probably are.

Enjoy bash scripting!

 
