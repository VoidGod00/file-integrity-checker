# file-integrity-checker
file intergrity checker is build using bash scripting

To loop through directories and sub-directories a for loop is used to hit all files and an if statement is used to check if that file is a directory or not. If yes, the function calls itself and starts over in the new directory and continues on from there

Checking is done by reading a previously taken baseline and a newly taken temp file line by line, and field by field checking for changes.

These changes are flagged and the flags can be used to generate an easy to read report displaying high priority changes first and low priority changes last.

Each bullet is its own script that are all used in the main.sh script to make it more readable and easy to understand
