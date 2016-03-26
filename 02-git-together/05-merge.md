{%mode mode="cli" %}
# Push your changes back into GitHub

Now that we've made some substantial changes, we want to share our recipes with the world! Or at least with our team.

The recipes are on your computer, in your copy/branch of the project.  For us to get it merged back in with everyone's changes, we have to get your branch online, onto GitHub.  Your mentor will show you how we can do this.
{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** Show how to `git push origin ___` and introduce/explain the concept of git remotes.
>
> Your team will likely have to login on the command line.  This may be confusing since there's no feedback of the password being typed in.
{%endmode %}


# Merging your branch back in

{%mode mode="s" %}
Now that we've made some substantial changes, we want to share our recipes with the world! Or at least with our team. Let's see how we can merge our personal branch back in with the main branch, the *Master* branch.
{%endmode %}

{%mode mode="cli" %}
Now that our branches are online, let's see how we can merge them back in with the main branch, the *Master* branch.
{%endmode %}

{%mode mode="mentor" %}
> **Info** There may be questions about what it means for a branch to be the "master" branch.  Discuss.
{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** There may be questions about what it means for a branch to be the "master" branch.  Discuss.
{%endmode %}

On GitHub, the mechanism for doing this is a **pull request**, or PR for short. A pull request tells the owner of the repo that you're ready for them to merge your changes back in. This is when someone responsible for the project will approve your changes and **merge** them into the main branch.

> Merging branches is a feature built into Git, but pull requests are a feature of GitHub.

Go ahead and submit a pull request with your mentor. Ask questions about the process, and make sure to see how the pull requests get merged.


{%mode mode="mentor" %}
> **Info** Review the pull requests.  Point out the log of commits and file diffs on the GitHub PR page.
>
> Show off the merged repo on GitHub.
{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** Review the pull requests.  Point out the log of commits and file diffs on the GitHub PR page.
>
> Show off the merged repo on GitHub.
{%endmode %}

# Sync your local copy with what's online.

Right now, locally, we are still on the copy with only your changes.  To be able to see the current master version with everyone's recipes, we'll need to first go back to our master branch, and then "pull" in the updates from the origin's master branch.

{%mode mode="mentor-cli" %}
> **Info** Show your team how to `git checkout master` and then `git pull origin master`.
>
> Point out how we've done `git checkout` before, with the `-b` option to make our new branch, and how running it without the `-b` allows us to switch to an existing branch.
{%endmode %}

Look at your local copy of the project.  You should now have a complete copy with everyone's recipes!

{%mode mode="cli" %}

## Review

### Commands to sync remotes

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git push origin ____` | **git**, **push** what you have tracked up as the ___ branch for `origin` | syncs our `origin` branch of ___ online |
| `git pull origin ____` | **git**, **pull** from `origin` the ___ branch | syncs our ___ branch with what's in `origin` |

{%endmode %}
