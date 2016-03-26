{%mode mode="cli" %}
# Tell git to pay attention to the file's changes


{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** `git status`, `git add ___`

{%endmode %}


# Commit your new file

Git has your new recipe file ready to be packaged up into a **commit**. A commit wraps up any changes that have been added and saves them together with a short message. 

The short message is called the commit message. It describes the changes that are being packaged together. This is not only important but necessary.




{%mode mode="cli" %}

### Review: Commands to tell git about changes

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git add hello.txt` | **git**, **add hello.txt** to your "stage" | tells git to keep an eye on the `hello.txt` file |
| `git commit -m "a message"` | **git**, **commit** these changes as described by this **m**essage | tells git to track the changes of the staged files and to remember the changes with the commit message |

{%endmode %}

