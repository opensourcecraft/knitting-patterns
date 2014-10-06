How to contribute
=======================
OpenSourceCraft patterns and materials are licensed under a *[Creative Commons Attribution-ShareAlike 4.0](http://creativecommons.org/licenses/by-sa/4.0/)* license. 

*These guidelines are based on the Django Girls tutorial [https://github.com/DjangoGirls/tutorial](https://github.com/DjangoGirls/tutorial)*

# Editing basics
The Github [Fork & Pull workflow](https://help.github.com/articles/using-pull-requests) is used to accept and review changes.

Patterns should be written in [Markdown mark up language](https://help.github.com/articles/markdown-basics) to allow for review of changes on Github.


# Getting started and prerequisites

For contributing to OpenSourceCraft knitting patterns you need the following:

* a [Github account](https://github.com)
* in the case of complex edits familiarity with [Git command line basics](https://help.github.com/articles/set-up-git) or familiarity with an app ([Windows](https://windows.github.com/), [Mac](https://mac.github.com/)) to push your edits made on your computer to Github.

## Fork the repository

First fork the [opensourcecraft/knitting-patterns](https://github.com/opensourcecraft/knitting-patterns) repository to your personal Github account.


## Simple changes to existing patterns

For simple changes like typo corrections you can use the Github online editor:

* Open your local fork page on Github,
* go to the pattern you with to edit,
* press the *Edit* icon (pen)

and you can edit directly on github.com.

Markdown syntax is used to edit the individual pages of the tutorial.

Save your changes and create a pull request as explained below.

## New patterns/documents

For adding new patterns, writing larger amounts of text or adding images, you need to get a copy on your local computer.

Either use the Github app for your operating system (mentioned above) or the `git` command line to get the repository locally. You get the repository address from the front page of your own Github repository fork:

    git clone git@github.com:yourgithubusername/knitting-patterns.git

Use the the [Gitbook Editor](http://help.gitbook.io/editor/README.html) app or other software such as [Mou](http://25.io/mou/) to edit/create your markdown documents.

If you are adding a new pattern, create a folder for it in the relevant sub-folder under 'knitting-patterns'.

Then commit the changes using `git` and push the changes to your remote Github repository.

Example:

    $ git status
    On branch mymaster
    Untracked files:
      (use "git add <file>..." to include in what will be committed)

        toys/teddy.md

    $ git add toys/teddy.md

    $ git commit -m "Added teddy pattern"
    [mymaster fe36152] Added teddy pattern
     1 file changed, 0 insertions(+), 0 deletions(-)
     create mode 100644 toys/teddy.md
     
    $ git push
    Counting objects: 11, done.
    Delta compression using up to 8 threads.
    Compressing objects: 100% (5/5), done.
    Writing objects: 100% (5/5), 266.37 KiB | 0 bytes/s, done.
    Total 5 (delta 1), reused 0 (delta 0)
    To git@github.com:yourgithubusername/knitting-patterns.git
       b37ca59..fe36152  mymaster -> mymaster

# Making a pull request

After you have finished your changes you need to create a [pull request](https://help.github.com/articles/using-pull-requests)  on Github. The OpenSourceCraft team will be notified about the pull request, review your changes, comment if necessary, and then *merge* your changes to the master version.

In your own repository on Github press *Compare & pull request*

Comment on *why* this change is being made, then press *Create pull request*.

Github emails will notify you for the follow up process.

# Further information and help

For any questions please contact [@rebkwok](http://github.com/rebkwok)
