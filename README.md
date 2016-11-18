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

## Prerequisites:
1. [Create a GitHub account](https://github.com/join)
2. Download and install

   * [Download Windows package](https://git-for-windows.github.io)
   * [Download OSX package](https://git-scm.com)
   
3. On your computer open the program 

    * Windows: Git Bash
    * OSX: Terminal
    
4. Tell Git your name so your commits will be properly labeled

        git config --global user.name "YOUR NAME"

5. Tell Git the email address that will be associated with your Git commits

        git config --global user.email "YOUR EMAIL ADDRESS"

## Session overview

### Introduction
* Presentation of us, our background, where we work, why we are here
* Presentation of you - by raising hands 
   * How far in education?
   * How many have used git?
   * How have you shared code so far?
* Why Git?
    * Why not email/Dropbox/googledocs
    * Git is for plain text - not a Dropbox replacement
    * How does Git solve it?
    * Highlevel view of Git across multiple machines
    * Git in a bigger setup - many devs, production machines, tests
    * GitHub

### Workshop

The workshop consists of three parts. We will introduce some concepts, that you will then have to replicate on your own and in teams of two. We will demo git using GitHub and two developer machines. One developer machine on the mac,
and another on Windows running in a VM. 

#### Part 1 - Getting started
* Create a repository on Github with a Readme file
* Switch to the terminal
   * `pwd`, `ls`, `cd`, `clear`
* Navigate to desired folder
* Clone the created repository on Computer 1
* Add an empty file on Computer 1 and push
   * Here, you might have to put in your GitHub username and password
   
#### Part 2 - Working together
* Clone the created Repository on Computer 2
* Add a Java class with two empty methods to the file on Computer 2 and push
   * Permission to repo denied - Add Computer 2 user as collaborator from Computer 1 on GitHub
* Notice that the file is not automatically updated on Computer 1
* Pull changes on Computer 1
* Add some code in the first method on Computer 1 and push
* Add some code in the second method on Computer 2 and push
  * Cannot push - pull before push and see that changes has been merged
* Pull changes on Computer 1

#### Part 3 - Resolving merge conflicts
* Change something in the first method on Computer 1 and push
* Change something in the first method on Computer 2 and push
  * Cannot push - pull before push and see merge conflict
* Resolve merge conflict

### Next steps.
* Branching and merging.
* Pull Requests on github


# Links
* https://guides.github.com/ (Learn how to use git and GitHub)
* https://git-scm.com/about/ (Why and How git was build)
* https://education.github.com/pack (Github offers and education pack, that includes private repos - otherwise your projects will be visable to everybody
