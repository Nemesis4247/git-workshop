Git & GitHub Workshop
=====================

Welcome to the workshop. Feel free to use this guide as reference.

Setup User Configuration
------------------------

First thing to do is to setup your identity.

    $ git config --global user.name "Your Name"
    $ git config --global user.email your.email@example.com
    
Initialize your Repository!
--------------------------

Go to your project folder and initailize a git repo using init.

    $ git init

Moving your changes to Staging Area
-----------------------------------

After you are done with your changes, you can add those changes to Staging Area.

    $ git add "filename"
    
For adding all the files in the current directory

    $ git add .
    
Committing
----------

You are now ready to commit. The `-m` flag allows you to enter a message
to go with the commit at the same time.

    $ git commit -m "I am adding two new files"
    
Log
---

We should now have a new commit. To see all the commits so far, use
`git log`

    $ git log
