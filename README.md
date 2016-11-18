# Introduction to version control systems with Git and GitHub

At the beginning of any software project, you will be faced with the question:
"How do we share our code?". While you might get started with something like
Dropbox, the tool used across the software industry is a Version Control
System (VCS). See Wikipedia (https://en.wikipedia.org/wiki/Version_control)
for a longer introduction.

In this session, three full time developers from e-conomic, will give an
introduction and workshop on a VCS called Git, and how it is used together
with GitHub.com. You will learn how Git is used in a larger software setup,
and why it indispensable tool for building software in teams. We will
introduce you to some Git basics, and follow up with a workshop where you will
apply your newly learned skills.

Bring your laptop.

### Prerequisits:
* A GitHub account: https://github.com/
* Git command line installed.
    * Windows: https://git-for-windows.github.io/
    * Mac/Linux: open "Terminal" and type "git" - it is probably already installed.


### Notes for demo and workshop:

* Presentation of us, our background, where we work, why we are here.
* Overview of the session
    * Why Git? Why not email/Dropbox/googledocs.
    * How does Git solve it?
    * Highlevel view of Git across multiple machines.
    * Git in a bigger setup - many devs, production machines, tests
    * GitHub

* Demo
We will demo git using GitHub and two developer machines. One developer machine on the mac,
and another on Windows running in a VM.
    * Creating a repository on Github
    * The terminal - navigating the file system
    * Git from GUIs vs the command line
    * Cloning a repository
    * Adding files and pushing them to GitHub
        * `status`, `add`, `commit`, `push`
    * Getting the file on another computer
    * Adding code changes (e.g. class with two methods)
        * Git is for plain text - it is not your Dropbox replacement
    * Other computer does not have those changes yet, GitHub does
    * Make change on Windows, push
    * Make change on OSX push -> fail -> pull -> push
    * Make conflicting change and push it
    * Make Windows conflicting change pull - resolve merge conflict and push

### Workshop
* 2x2 reproduce what was done in the demo

### Next steps.
* Branching and merging.
* Pull Requests on github.


# Thoughts and links (brunsgaard)
* I think we should encourage CLI, there are alot of git desktop tools
* https://guides.github.com/
* Github offers and education pack, that includes private repos (Otherwise your projects will be visable to everybody)
* https://help.github.com/articles/set-up-git/
* https://guides.github.com/activities/hello-world/
* https://git-scm.com/about/ (Why and How git was build)
* binarydata vs plaintext (bad for word documents)
* Git blame, git logs, force push
* File size limtes
