{%mode mode="cli" %}
# Getting the repo

To work on the project, we'll start by getting a copy of the repo on your computer.  We can do this by using git to **clone** the repo to your own computer.
{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** Show your team how to `git clone` the recipe project.  Point out the messages git returns to be helpful.
{%endmode %}

{%mode mode="cli" %}
Once you have the project on your computer, you're ready to rock and roll.
{%endmode %}

# Branching

First thing we'll do is create a **branch** of our own to work on. A branch is a full copy of your project files. 


> **Comment** Why would you want to make a copy before you start making edits?


![branch](https://www.atlassian.com/wac/landing/git/tutorial/git-branches/pageSections/0/contentColumnTwo/0/imageBinary/git-tutorial_branching-merging.png)


{%mode mode="mentor" %}
> **Info** After the discussion, show your team how to make a branch on GitHub by clicking on the branch selector, typing in a new branch name, and pressing enter.
>
> Show them how the branch button says their branch name when they are looking at their copy.
{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** After the discussion, show your team how to `git checkout -b ` a new local branch.
>
> Also, show how `git branch` now lists two branches -- the one we just made, and one called "master".
{%endmode %}

{%mode mode="cli" %}

## Review

### Commands to tell git to make copies

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git clone ____` | **git**, **clone** the repo at the online address of ____ | Makes a copy from ____ to our computer |
| `git checkout -b ____` | **git**, **checkout** a new branch called _____ | Makes a copy of our project and remembers it by the name ____, and switches us to this copy |

### Asking `git` about branches

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git branch` | **git**, list us **branch**es | show us all the branches we've made and highlights the one we are in |

{%endmode %}
