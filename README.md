the-first-tutorial
==================

A quick introduction to various CS concepts.  Before we explain how this is going to work, please make sure you have the following things set up and configured.

Software
------------------


  * To start, you'll need to install git on your machine.  Github has an [excellent guide to this process](https://help.github.com/articles/set-up-git).  For some platforms there is an option to skip the guide and install a native app instead - don't install github's native app.  Just follow the guide, because we may end up using some more advanced git features.
  * Once git is installed, make sure that you have python2 configured on your machine.  You can check this by opening up a terminal and running `python`.  If not, python can be installed from [the python downloads page](https://www.python.org/downloads/).
  * You will need some sort of text editor with syntax highlighting.  If you don't have one already installed, [sublime text 3](http://www.sublimetext.com/3) might be a good cross platform choice.


Accounts
------------------

 * You will need to create a github account to follow along and perform various actions related to this tutorial.
 * Please create a free account on [ideone.com](http://ideone.com/) - this is an online compiler program that will allow us to all run our code on the same platform for comparison.


Following the Tutorial
==================
The tutorial is broken up into lessons, and each lesson is broken up into problems.  We're going to do the lessons in order, and the problems in order.  This process is designed to take between ten and twenty minutes per problem, although the first problem in a lesson may take longer since they tend to require some setup.

Getting Started
------------------
Fork this repository on github using the "Fork" button at the top of this page.  Navigate to your forked repository using the github interface, and clone it into a directory on your local machine.  Then, open up that folder using your text editor of choice, and navigate to the folder containing the first lesson.  A description of the problem will be written in a file titled `README.md` in that folder.  You will also see a number of input files, each titled `problem[0-9]+.txt` (yeah, we're starting at zero).  You will also see a number of solution files, named `solution[0-9]+.txt`. Read the lesson/problem description, and then start working on a solution that you will save in the same folder.  Name the file containing your solution program similarly to the associated input file - for instance if working on a python solution, name the solution to problem0 `problem0.py`.  Your programs should read the input files from stdin, and produce identical output to the numbered `solution[0-9]+.txt` files.

In order to verify that your solutions are correct and run them against the provided input files, you will have to use the input redirection and diff tools provided by your terminal shell.  On linux or Mac OS X, checking a solution should involve something like this, if run from the root directory of this project:

    python lesson0/problem0.py < lesson0/problem0.txt | diff -s lesson0/solution0.txt -
    
A solution on windows will essentially the same once git has been installed.
    
A correct solution should output `Files lesson0/solution0.txt and - are identical`.  If diff reports mismatches on seemingly identical lines, you probably checked out the solution files with the wrong line ending encoding for your platform - see [this article](https://help.github.com/articles/dealing-with-line-endings) for steps to resolve the issue.

Once you have solved the problem, paste your solution into the ideone.com editor, and expand the stdin section and paste in the apporpriate `problem.txt` file.  Run your soultion in 'private' mode, and submit the link to the moderator.

Procedures
---------
Please feel free to help out other competitors with problems!  This is intended to be a collaborative and educational exercise, and we don't want anyone getting stuck or bogged down in small details and losing interest.  We only ask that you:

  1.  Don't actually type anything for someone else - offer direction, but don't take over the process.
  2.  Don't just give away any solutions.  You can rephrase the problem, or call attention to specific issues with their solution, but try not to explicitly state how to fix them - although feel free to hint strongly towards the right solution if the problem is algorithmic in nature.  It may be that not everyone actually solves all problems in the alotted time, but our hope is that they would at least be capable of working through them alone at a later date.