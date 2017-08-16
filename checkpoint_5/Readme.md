
If you're not already, please go into the checkpoint_5 directory.

 - `cd checkpoint_5`

Show me the lines in foo.txt that have "ERROR" in them.

 - `grep ERROR foo.txt`
    
Show me the lines in foo.txt that have "Synergistic" in them.

 - `grep Synergistic foo.txt`

What does the -i option to grep accomplish?

 - case-insensitive matching

What option to ls tells it to output file size in human readable form?

 - `ls -lh`

What does the -r and -f options to rm do exactly?

 -r: Attempt to remove the file hierarchy rooted in each file argument.
 -f: Attempt to remove the files without prompting for confirmation, regardless of the 
     file's permissions.

What does the ifconfig command do?

 - configure network interface parameters

What is your shell set to?

 - /bin/bash: `env | grep SHELL`

What directory are you in (don't use pwd this time)?

 - `env | grep PWD`

What is your home directory set to?

 - /Users/david: `env | grep HOME`

Can you set your environment to have DEBUG set to true?

 - `export DEBUG=true`

Explain how you would change your PATH on your computer

 - `export PATH=<new path addition>:$PATH`

Can you remove the debug environment variable?

 - `unset DEBUG`
    
Why is it dangerous to run "rm -rf /". DO NOT RUN THIS COMMAND. Simply explain why it's a very bad idea.

 - it will attempt to delete everything on your drive.

Can you put "This class is fun" into bar.txt?

 - `echo "This class is fun" > bar.txt`

Can you put "Oh so much fun" into foo.txt?

 - `echo "Oh so much fun" >> foo.txt` to append or `echo "Oh so much fun" > foo.txt` to 
   overwrite.

Run find in the class directory, pipe the output to pbcopy and create a gist with the content.  Paste the Gist URL below.

 - `find ~/workspace/davinci_coders_t3_2016 | pbcopy`

    Gist URL:  https://gist.github.com/daktest/975ad374b2ba13a7e4908d71f30ced71

Please logout.

 - `exit`


