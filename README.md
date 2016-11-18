# Introduction to version control systems with Git and GitHub

At the beginning of any software project, you will be faced with the question:
"How do we share our code?". While you might get started with something like
Dropbox, the tool used across the software industry is a Version Control
System (VCS). See Wikipedia (https://en.wikipedia.org/wiki/Version_control)
for a longer introduction.

In this session, three full time developers from e-conomic, will give an
introduction and workshop on a VCS called Git, and how it is used together
with GitHub.com. You will learn how Git is used in a larger software setup,
and why it is an indispensable tool for building software in teams. We will
introduce you to some Git basics, and follow up with a workshop where you will
apply your newly learned skills.

Bring your laptop.

### Prerequisites:
* A GitHub account: https://github.com/
* Git command line installed.
    * Windows: https://git-for-windows.github.io/
    * Mac/Linux: open "Terminal" and type "git" - it is probably already installed.


# Session overview

### Introduction
* Presentation of us, our background, where we work, why we are here.
* Presentation of you - by raising hands 
   * How far in education?
   * How many have used git?
   * How have you shared code so far?
* Why Git?
    * Why not email/Dropbox/googledocs.
    * Git is for plain text - not a Dropbox replacement
    * How does Git solve it?
    * Highlevel view of Git across multiple machines.
    * Git in a bigger setup - many devs, production machines, tests
    * GitHub

### Demo

We will demo git using GitHub and two developer machines. One developer machine on the mac,
and another on Windows running in a VM.

* Create a repository on Github with a Readme file
* Switch to the terminal
* Navigate to desired folder
* Clone the created repository on Computer 1
* Add an empty file on Computer 1 and push
* Clone the created Repository on Computer 2
* Add a Java class with two empty methods to the file on Computer 2 and push
   * Permission to repo denied - Add Computer 2 user as collaborator from Computer 1 on GitHub
* Notice that the file is not automatically updated on Computer 1
* Pull changes on Computer 1
* Add some code in the first method on Computer 1 and push
* Add some code in the second method on Computer 2 and push
  * Cannot push - pull before push and see that changes has been merged
* Pull changes on Computer 1
* Change something in the first method on Computer 1 and push
* Change something in the first method on Computer 2 and push
  * Cannot push - pull before push and see merge conflict
* Resolve merge conflict


### Workshop
* 2x2 reproduce what was done in the demo

### Next steps.
* Branching and merging.
* Pull Requests on github.


# Links
* https://guides.github.com/ (Learn how to use git and GitHub)
* https://git-scm.com/about/ (Why and How git was build)
* https://education.github.com/pack (Github offers and education pack, that includes private repos - otherwise your projects will be visable to everybody
