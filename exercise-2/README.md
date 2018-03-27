# Exercise 2
In this exercise you'll practice making a simple shell script.

To complete the exercise, follow the below instructions:

1. Create a new file called `count.sh` in using your favorite editor (e.g., VS Code). Save it to your Desktop. 
 
2. Add a _shebang_ (`#!/usr/bin/env bash`) to the top of the `count.sh` script. 

3. Add commands to the script (each on their own line to perform the following actions):

    1. Navigate to the Desktop (use an _absolute_ path based on the user's home directory `~`).
    2. _Append_ the text `"script executed"` to the end of a file on the Desktop called `counter.txt`
    3.  Use the `wc` (**w**ord **c**ount) command to display the number of lines in the `counter.txt` file.

4. Make the `count.sh` script executable (`chmod +x note.sh`)

5. Execute the `count.sh` scrtip (`./count.sh`)
