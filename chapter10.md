# Learn the command-line

Congratulations! You're getting the hang of it.

Now, to unlock the full power of Git, we need to become comfortable using the **command-line**. Don't worry! The best way to learn is to jump in and do it. We'll take you through the basics now.

**The session** - When you open your command-line, you enter a new session. You'll hear the words console, terminal, and command-line used interchangeably. What you need to remember is these are synonymous with having one of these sessions open.

**The prompt** - When you open a new session, you'll have a *mostly* empty screen. The session is waiting for you to type something. The place where you start typing is the **prompt**. This will look like `>` or `$` on most machines.

`pwd` - Ok, let's start typing something. Type `pwd` at the prompt and press Enter.  What happened? 

>You need to press Enter to submit a command on the command-line. From now on I won't tell you to press Enter, but you'll need to press it after each command before it will run.

It printed something like `/Users/neeraj/`. pwd is short for "present working directory". What's a directory? It's a folder. Folders and directories are the same thing. When we typed `pwd` and Enter, we asked the computer to tell us what folder we were presently in. 

`mkdir` - Let's try a new command. Type `mkdir gitworkshop/test`. mkdir means "make directory". We told the computer to make a folder called gitworkshop and then make a folder names test inside that folder! If you wanted to make a folder, and a folder inside that folder without the commandline, this would take a few steps. Here we did it in one step. Hopefully you're starting to see the power of the command-line.

You're seeing something else here too. You're seeing that both when we did `pwd` and `mkdir`, we saw folder names separated by slashes - `/` or `\`. What we're seeing are *paths*. These are exactly what they sound like, they're paths to a folder or file. 

The **path** is an essential concept. Fortunately, it's something you're familiar with even if you didn't know it. When you go to your file browser and click through folders, what you're doing is navigating the path. There's nothing else to it. 

Before you can move between folders on the command-line or know whether you've found your file or not, you'll need to learn `cd` and `ls`, respectively. cd means "change directory" and it's exactly like clicking through to the next folder. Try `cd ghworkshop`. Now try `ls`. ls means "list". So, we changed folders to the `ghworkshop` folder, then asked the computer to list its contents. It will list the "test" folder we created earlier.

Try finding a file in your file browser, then finding it on your command-line. Do this a few times. Practice makes perfect!

You now know enough to move forward with unlocking the full potential of Git. If the idea of the command-line still feels iffy to you, stick with it. The remainder of this workshop will provide a little more practice.

## Review

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `pwd` | **p**rint **w**orking **d**irectory | Tells us where we are |
| `ls` | **l**i**s**t | List the things that are in this directory |
| `mkdir` | **m**a**k**e a **dir**ectory | make a new directory in we are |
| `cd hello`  | **c**hange **d**irectory | Move into the hello directory |
| `ls -a`     | **l**i**s**t  **a**ll | List all things that are in this directory |
