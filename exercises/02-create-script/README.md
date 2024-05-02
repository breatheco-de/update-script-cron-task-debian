# `02` Create the script

In GNU/Linux environments a script is a simple text file, which is intended to be executed by the terminal. In other words, each of the lines of the script will be executed in the terminal as if someone transcribed them one by one.

For this we can use nano in the terminal or the text editor that we have in the applications menu, the important thing is to create the file with the instructions that we want to be executed.

Before testing your script you must specify that the file has execution permissions and this is a task for the root user.

## 📝 Instructions:

1. Create a script that updates the list of available packages and does an update of all of them.

2. Like many others, this task may usually require confirmation from the user. To automate the update you should skip the confirmation.

3. You must run the script with root privileges.

## 💡 Hint:

> - Try executing each command separately before merging everything into the script
>
> - Almost all commands have a built-in manual, just type 'man' before the command and see the documentation. Example 'man ls'