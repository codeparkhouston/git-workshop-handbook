# "Pushing" your project online

We have our new project on our computer, but now, we want to get it online.  In order to do that, we would first use GitHub to make a place for it.

{%mode mode="mentor" %}
> **Info** Show your team how to create a new repository online, and then use the second set of commands to push up their repo.
>
> Discuss the idea of git remotes.  Show how you can run `git remote -v` to see the saved remote.
>
> Discuss how pushing tells git to send your latest commits out to the specified remote.
{%endmode %}

{%mode mode="mentor-cli" %}
> **Info** Show your team how to create a new repository online, and then use the second set of commands to push up their repo.
>
> Discuss the idea of git remotes.  Show how you can run `git remote -v` to see the saved remote.
>
> Discuss how pushing tells git to send your latest commits out to the specified remote.
{%endmode %}

Once we have a matching empty repo online, your mentor will show you how to get the online version synced with the latest changes you've made on your computer's version.

## Review

### Putting our code online

| Command     | What it means | What it does |
| ----------- | ------------- | ------------ |
| `git remote add origin ______.git` | **git**, **add** this ____.git address as a **remote origin** | saves a reference to an online home named `origin` |
| `git push -u origin master` | **git**, **push** what you have tracked up as the master for `origin` | updates our `origin` online with the later tracked code on `mater` |
