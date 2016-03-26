# Fixing some issues

It's been called to our attention, so let's fix the typo. The process should now begin to become familiar to you. You'll need to:

{%mode mode="s" %}
* Create a new **branch**
* Make your edits
* **Commit** your changes
* Make a **pull request**
{%endmode %}

{%mode mode="cli" %}
* `git checkout -b <branch name>`
* Make your edits
* `git add ___`
* `git commit -m _____` your changes
* `git push origin <branch name>`
* Make a **pull request**
{%endmode %}

{%mode mode="mentor" %}
> **Info** 
> Make your own branch and PR for one of the issues that another member is working on.  This will be for you to merge in last to demonstrate a merge conflict.
>
> This time, when you merge the pull request, put `closes #___` -- where __ is the issue number -- in the "Confirm Merge" message.  Show your team how the issue is now closed.
>
> When it comes to merging your PR, GitHub will have a message about how it can't merge since there's a conflict with master.  Explain to your team about how sometimes, we'll confuse git.  Resolve the conflict locally, and show your team how it's really just about helping git know what the file should actually look like.
{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** 
> Make your own branch and PR for one of the issues that another member is working on.  This will be for you to merge in last to demonstrate a merge conflict.
>
> This time, when you merge the pull request, put `closes #___` -- where __ is the issue number -- in the "Confirm Merge" message.  Show your team how the issue is now closed.
>
> When it comes to merging your PR, GitHub will have a message about how it can't merge since there's a conflict with master.  Explain to your team about how sometimes, we'll confuse git.  Resolve the conflict locally, and show your team how it's really just about helping git know what the file should actually look like.
{%endmode %}

Browse around on the repo online and see how the recipes book is turning out!

{%mode mode="mentor" %}
> **Info** Lead your team in a show-and-tell of different libraries that are on GitHub.  Ask first what they've heard of or used, and pull up their repos online.  [Bootstrap](https://github.com/twbs/bootstrap) might be a a great candidate for this.  Or, for members more familiar with data analysis, [ggplot2](https://github.com/hadley/ggplot2), [jupyter/iPython notebook](https://github.com/jupyter/notebook).  Show how contributions have been made to these projects using similar workflows to what we just did.
>
> Congratulate team members on their shiny green contribution box on their profiles.
{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** Lead your team in a show-and-tell of different libraries that are on GitHub.  Ask first what they've heard of or used, and pull up their repos online.  [Bootstrap](https://github.com/twbs/bootstrap) might be a a great candidate for this.  Or, for members more familiar with data analysis, [ggplot2](https://github.com/hadley/ggplot2), [jupyter/iPython notebook](https://github.com/jupyter/notebook).  Show how contributions have been made to these projects using similar workflows to what we just did.
>
> Congratulate team members on their shiny green contribution box on their profiles.
{%endmode %}

> **Comment** 
> Revel in the glory of your team's first git collaboration!  Celebrate, discuss, review, ask questions, and take a break.
