# Starting our own projects

Now, we will start our own repos and be the ones managing it as we practice what we learned earlier on each other's projects.

{% mode mode="s" %}
Previously, we worked off of branches of the project online.  This time, we will be starting the project on our computers, and then putting it online.

{%endmode %}

First, **m**a**k**e a **dir**ectory for our project, and **c**hange **d**irectory into it.

Then, in our brand new project directory, **l**i**s**t **a**ll files with `ls -a`.  This command is just like `ls`, but will show us system files as well.

It's an empty folder, as expected.  Now run,

```bash
git init
```
{% mode mode="s" %}
From now on, anytime we are asking git to do something for us, our command will start with `git`.
{%endmode %}

{% mode mode="mentor" %}

> **Info** Explain how git is a program that's exposed in the command-line, and what we put in after git are the commands we want git to run.
>
> Point out that git replies back to us to let us know it succeeded.
{%endmode %}

Now, **l**i**s**t **a**ll files with `ls -a` again.  You'll notice there's a new subdirectory now, called ".git".  This is where git keeps track of our commits, branches, etc.

## Review

### Making a new repo on your computer

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git init`  | **git init**ialize | Start git tracking |

### List all 

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `ls -a`     | **l**i**s**t  **a**ll | List all things that are in this directory |
