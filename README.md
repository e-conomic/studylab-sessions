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

### Prerequisites:
* A GitHub account: https://github.com/
* Git command line installed.
    * Windows: https://git-for-windows.github.io/
    * Mac/Linux: open "Terminal" and type "git" - it is probably already installed.


### Notes for demo and workshop:
* Presentation of us, our background, where we work, why we are here.
* Overview of the session
    * Why Git? Why not email/Dropbox/googledocs. (Made for the Linux kernel project)
    * How does Git solve it.
    * Highlevel view of Git across multiple machines.
    * Git in a bigger setup - many devs, production machines, tests
    * GitHub

* Demo
    * Create repository on Github
    * The terminal - navigate the file system
    * Git from GUIs can be done, but command line often easier to understand, and most people do this
    * Clone repository
    * Add file, commit push to github
    * Get the file on another computer.
    * Make code change to the file (e.g. class with two methods)
    * Status add commit push
    * Other computer does not have those changes - show this on some diagram
    *   Show this on other computer? Ie in virtual machine? Git bash for Windows..
    * Make change on Windows, push
    * Make change on OSX push -> fail -> pull -> push
    * Make OSX conflicting change push
    * Make Windows conflicting change pull - resolve merge conflict

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
