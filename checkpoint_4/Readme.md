
If you're not already, please go into the checkpoint_4 directory.

 - `cd checkpoint_4`

Remove everything in the foo directory using one command

 - `rm -R foo/*`

The following questions are about the file color_preferences.txt.

How many lines are there?

 - 1000: `grep -c . color_preferences.txt`

How many teenagers are there?

 - 320: `egrep -c '13|14|15|16|17|18|19' color_preferences.txt`
    
Copy the lines from color_preferences.txt to a file called teens.txt, but only include the lines where their age is 13-19.
    
 - `egrep '13|14|15|16|17|18|19' color_preferences.txt > teens.txt`
        
How many teenagers like the color purple?

 - 14: `grep -i -c purple teens.txt`
    
