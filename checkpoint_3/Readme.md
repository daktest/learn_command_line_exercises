
If you're not already, please go into the checkpoint_3 directory.

`cd ~/workspace/davinci_coders_t3_2016/homework/learn_command_line_exercises/checkpoint_3`

Can you rename foo/bar/file1.txt to foo/blah.txt?

`mv foo/bar/file1.txt foo/blah.txt`
    
Let's make a copy of foo/blah.txt and put it in the foo/bar/baz directory.

`cp foo/blah.txt foo/bar/baz/`

What happens if you touch an existing file. (Hint:  The answer is not nothing...)

The date of the file is updated.

Can you copy the foo/blah.txt file to slash temp?

No, there is no /temp dir.

Can you copy .bash_profile in your home directory to the current directory? (Do not use cd here...)

`cp ~/.bash_profile .`

What's in foo/blah.txt?

`cat foo/blah.txt` or `less foo/blah.txt` or `more foo/blah.txt`
    
Can you show me what's in foo/blah.txt one page at a time?

See last two options above.
