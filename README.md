## git config

**Use**: To set your user name and email in the main
configuration file.

**How to**: To check your name and email type in `git config --global user.name` and `git config --global user.email`. And to set your new email or name `git config --global user.name = “Pedro Sanchez”` and `git config --global user.email =
“pedrosanchez@moncloa.com”`

## git init

**Use**: To initialise a git repository for a new or
existing project.

**How to**: `git init` in the root of your project directory.

## git clone

**Use**: To copy a git repository from remote source,
also sets the remote to original source so that you can pull again.

**How to**: `git clone <:clone git url:>`

## git status

**Use**: To check the status of files you’ve changed in
your working directory, i.e, what all has changed
since your last commit.

**How to**: `git status` in your working directory lists
out all the files that have been changed.

## git add

**Use**: adds changes to stage/index in your working directory.

**How to**: `git add <:list-of-files:>` or to add all the files inside the current folder where you are git
add .

## git commit

**Use**: commits your changes and sets it to new commit object for your remote.

**How to**: `git commit -m”sweet little commit message”`

## git push/git pull

**Use**: Push or Pull your changes to remote. If you
have added and committed your changes and you
want to push them. Or if your remote has updated
and you want those latest changes.

**How to**: `git pull <:remote:> <:branch:>` and `git
push <:remote:> <:branch:>`

## git remote

**Use**: To check what remote/source you have or
add a new remote.

**How to**: `git remote -v` to check and list. And `git
remote add origin <:remote_url:>`

Instead of origin you can choose another name .

# How to …. Labs (pair , daily)

## Fork (github) Always

Always remember to fork before cloning! This
allows you to have a “copy” of the original on your
repositories that you can push changes to but that it
´s still connected to the main repository!

“I can’t push changes , it says that I don’t have the
proper access/rights”

**If this happens , you have cloned directly without
forking and you are trying to push your changes to the master brunch**

### Clone

Double check that you are in fact in your
repositories , meaning , you have actually FORKED
the repo

Right after forking (NEVER FORGET STEP 1), its
time to `git clone` inside the desired folder.

### Do the exercise

This is where the magic happens!

### Add , commit , push

It's always good practice to repeat this process every so often while doing the exercise.

### Pull request

Now you are done with the exercise, please remember to create a new pull with the proper title indicated by your TAs so they are able to find you.
