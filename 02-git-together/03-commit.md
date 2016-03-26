{%mode mode="cli" %}
# Add file

Your mentor will show you how we can ask git what's going on.  Git will respond and provide some helpful hints for us.

{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** Show your team `git status` and `git add ___`

{%endmode %}


# Commit your new file

Git has your new recipe file ready to be packaged up into a **commit**. A commit wraps up any changes that have been added and saves them together with a short message. 

The short message is called the commit message. It describes the changes that are being packaged together.

{%mode mode="mentor" %}
> **Info** Discuss why commit messages are helpful.
>
> Point out the commit boxes at the bottom and tell them to go with the default option of committing to their branch.
>
> Once they've committed, you can show them how switching through branches online now shows the same initial "README.md" file, along with new and different recipe files.

{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** Show how to do a `git commit -m "_____"`.
>
> Discuss why commit messages are helpful.
>
> Once they've committed, show the team how they can switch back to the orignal branch with `git checkout master` and point out how the project files in their text editors have changed.  Switch back to their working branches.

{%endmode %}

{%mode mode="cli" %}

Try running `git status`.  Notice that git knows what's up.  Git now remembers the changes you made.  Run `git log` to see a history of commits.

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

### Switch copies

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git checkout ____` | **git**, **checkout** an existing branch called _____ | Switches us to the ____ copy |

{%endmode %}
