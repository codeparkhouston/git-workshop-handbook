# Adding to your project

First, let's check what branch we are in

```bash
git branch
```

Git tells us we are working with the master branch.  Open this directory in your text editor, add a file, and save.  Now, you can ask git about the status of things with

```bash
git status
```

Git will respond and even provide some helpful hints for us.

{%mode mode="mentor" %}
> **Info** Discuss the status and explain why we'll need to "add" next.
{%endmode %}

Now, let's go ahead and tell git to track our file:

```bash
git add <filename>
```

As before, we will "commit" this change with a message:

```bash
git commit -m "message about the change"
```

{%mode mode="mentor" %}
> **Info** Discuss add vs. commit.
{%endmode %}

{%mode mode="s" %}
Try running `git status`.  Notice that git knows what's up.  Git now remembers the changes you made.  Run `git log` to see a history of commits.
{%endmode %}

## Review

### Asking `git` for information

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git status`  | **git**, what's your **status**?  | tells us which files have changed since our last commit |
| `git log` | **git**, give us a **log** | shows us a history of our commits |

### Commands to tell `git` about changes

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git add hello.txt` | **git**, **add hello.txt** to your "stage" | tells git to keep an eye on the `hello.txt` file |
| `git commit -m "a message"` | **git**, **commit** these changes as described by this **m**essage | tells git to track the changes of the staged files and to remember the changes with the commit message |
