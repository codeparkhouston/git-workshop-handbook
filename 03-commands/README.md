{%mode mode="s" %}

# Get in command

Congratulations! You're getting the hang of it.

Now, to unlock the full power of Git, we need to become comfortable using the **command-line**. Don't worry! The best way to learn is to jump in and do it. We'll take you through the basics now.
{%endmode %}

{%mode mode="mentor" %}
> **Info** Help your team find and open their Terminal or Git Bash.
>
> Briefly introduce the command-line. Let them know that while it may seem weird and annoying to have to type things to work with the computer, you get faster with more practice, and there are a lot of things we can do from here.
{%endmode %}
{%mode mode="s" %}

## The session

When you open your command-line, you enter a new session.
{%endmode %}

{%mode mode="mentor" %}
> **Info** Discuss with your team the concept of a session.  You could say that it's like a new conversation that you're having with your computer.
{%endmode %}

{%mode mode="s" %}
> You'll hear the words console, terminal, and command-line used interchangeably. What you need to remember is these are synonymous with having one of these sessions open.

## The prompt

When you open a new session, you'll have a *mostly* empty screen. The session is waiting for you to type something. The place where you start typing is the **prompt**. This will look like

`>`

or

`$`

on most machines, "prompting" you to say something.
{%endmode %}

{%mode mode="mentor" %}
> **Info** Show your team how you run a couple of commands.  Show how you wait for the prompt, type in a command -- `pwd` for example-- and press <kbd>Enter</kbd> to run.
>
> Also, be sure to show how they can press the up arrow to bring back previous commands for running.
{%endmode %}

{%mode mode="s" %}

## Where are we?

Ok, let's start typing something. Type `pwd` at the prompt and press <kbd>Enter</kbd>.  What happened? 

>You need to press <kbd>Enter</kbd> to submit a command on the command-line. From now on I won't tell you to press <kbd>Enter</kbd>, but you'll need to press it after each command before it will run.

It replies with something like `/Users/neeraj/`. `pwd` is short for "**p**resent **w**orking **d**irectory". What's a directory? It's a folder. Folders and directories are the same thing. When we typed `pwd` and <kbd>Enter</kbd>, we asked the computer to tell us what folder we are in.

## Make a folder

Let's try a new command. Type `mkdir gitworkshop/test`. `mkdir` means "**m**a**k**e a **dir**ectory". We told the computer to make a folder called gitworkshop and then make a folder named test inside that folder! If you wanted to make a folder with a folder inside without the commandline, this would take a few steps. Here we did it in one step. There are a lot of shortcuts like this that show the power of the command-line.

We're seeing something else here too. We're seeing that both when we did `pwd` and `mkdir`, we saw folder names separated by slashes - `/` or `\`. What we're seeing are *paths*. These are exactly what they sound like, they're paths to a folder or file. 

## Path

The **path** is an essential concept. Fortunately, it's something you're familiar with even if you didn't know it. When you go to your file browser and click through folders, what you're doing is navigating the path. There's nothing else to it. 

We will us `cd` and `ls` to move between folders on the command-line and check whether we've found our file or not. `cd` means "**c**hange **d**irectory" and it's exactly like clicking through to the next folder. Try `cd ghworkshop`. Now, let's try `ls`. ls means "**l**i**s**t". So, we changed folders to the `ghworkshop` folder, then asked the computer to list its contents. It will list the "test" folder we created earlier.
{%endmode %}

{%mode mode="mentor" %}
> **Info** As your team moves into practice, showing them relative paths -- `../`, `./` -- and absolute paths -- `/__/__/` -- may be helpful.
{%endmode %}

{%mode mode="s" %}

## Practice

Try finding a file in your file browser, then find it on your command-line by using . Do this a few times. Practice makes perfect!

You now know enough to move forward with unlocking the full potential of Git. If the idea of the command-line still feels iffy to you, stick with it. The remainder of this workshop will provide a little more practice.

## Review

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `pwd` | **p**resent **w**orking **d**irectory | Tells us where we are |
| `mkdir _____` | **m**a**k**e a **dir**ectory | make a new directory in we are |
| `cd ____`  | **c**hange **d**irectory | Move into the ____ directory |
| `ls` | **l**i**s**t | List the things that are in this directory |

{%endmode %}
