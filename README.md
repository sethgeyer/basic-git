Basic Git, GitHub, and Students
=========

Git, GitHub, and Students is how we collaborate together during class. Exercises, such as this one, are how we submit work for the rest of class.

In this exercise we'll re-inforce several `git` concepts and learn how to submit work. Work individually on this. If you finish, help other students.

When you make a commit, please make a good commit message describing what you did.

## Tech skills learned

* Git
* GitHub

## Resources

* [Git Documentation](http://git-scm.com/documentation)
* [Pro Git](http://git-scm.com/book)

## Tasks

* Have _only_ one user fork this repository. 
* Clone the forked repository to the person's machine that forked the repo into the `~/gSchoolWork/exercises` folder.
* Create a file called `hello.txt`.
* Make a commit with this file.
* Check `git status` to make sure you actually commited the file.
* Push this change to GitHub.
* Add the text "hello world" to line 1 in the file `hello.txt`.
* Make a commit with this change.
* Push this change to GitHub.
* Ask for an instructor to review your work.
* Redirect the output from `git log` into a file called `git-log.txt`. NO TEXT EDITORS!.
* Commit this file with the contents.
* Push this change to GitHub.
* Ask for an instructor to review your work.
* Log into students and create a submission for this exercise. When asked for a repo name, type in `basic-git`.
* Clone the forked repository onto the other person's computer
* On the original computer add "I hope this makes it!" on line 2 to the `hello.txt`.
* On the new computer add "Oh no! What's going to happen?" on line 2 to the `hello.txt`.
* Make a commit on the first computer. Use `git add -p` to stage the change.
* Make a commit on the second computer.  Use `git add -p` to stage the change.
* Merge these two changes together so they both end up on GitHub, on lines 1 and 2, respectively.
`hello.txt` looks like this after the merge:
```
hello world
I hope this makes it!
Oh no! What's going to happen?
```

* On one of the computers, over-write the old `git-log.txt` with the new output from `git log`.
* Ask for an instructor to review your work
* Fork the forked repository to the other person's account.
* Log into students with the other user and submit this code.
* Ask for an instructor to review your work

When you're finished, you should BOTH have a repository on GitHub that has two files in, `hello.txt` and `git-log.txt`.
`git-log.txt` contains the most recent output from `git log` and `hello.txt` with the correct lines.

Now that you've finished this, get some paper and show what you just did visually:

* Draw the git tree
* Draw the interactions between each pair's computer and github
* Ask for an instructor to review your work

