    <----- GIT TUTORIAL ----->

# hello-world
Hello World repository for Git tutorial
This is an example repository for the Git tutoial on https://www.w3schools.com

This repository is built step by step in the tutorial.

The shorthand command for 'git add --all' is 'git add -A'

When we -commit-, we should always include a message:
By adding clear messages to each commit, it is easy for yourself and others to see what changed and when.

Short status flags are:
    ?? - Untracked files
    A  - Files added to stage
    M  - Modified files
    D  - Deleted files

* Files in your Git repository folder can be in one of 2 states:
1- Tracked - files that Git know about and are added to the repository.
2- Untracked - files that are in your working directory, but not added to the repository.

* Staged files are files that are ready to be commited to the repository.

* Adding commits keep track of our progress and changes as we work. Git considers each commit change point or 'save point'.
It is a point in the project you can go back to if you find a bug, or want to make a change. 
When we commit, we always should include a message. It will make it easy for us and others to see what has changed.

*In Git, a branch is a new/seperate version of the main repository. 
Branches allow you to work on different parts of a projecct without impacting the main branch.
When the work is complete, a branch can be merged with the main project.

*We can change our file on GitHub.

*When working as a team on a project, it is important that everyone stays up to date.anytime you start working on a project, 
you should get the most recent changes to your local copy. With Git, you can do that with 'pull'.
pull is a combination fof 2 different command: fetch and merge.
- fetch gets all the change history of a tracked branch/repo. So, on your local Git, fetch updates to see what has changed on GitHub.
- merge combines the current branch, with a specified branch.
- pull is a combination of fetch and merge. It is used to pull all changes from a remote repository into the branch you are working on.

*We can use -push- to push our code to GitHub.


    GIT Commands:

-> -- version                                                   To check if git is properly installed. If its installed you should be able to see st like "git version X.Y"
-> git config --global user.name "your-username"                Use this 2 to let Git know who ypu are.
-> git config -- global user.email "your-email-address"         Use this 2 to let Git know who ypu are.
-> mkdir myproject                                              Makes a new directory.
-> cd myproject                                                 Changes the current working directory.
-> git init                                                     You created a Git repository.
-> ls                                                           It will list the fils in the directory.
-> git status                                                   Now Git is aware of the file, but has not added to our repository.
-> git add file_name                                            We added our file to the Staging Environment.
-> git add --all   (Shoth hand command: git add -A)             We added all our files to to Staging Environment at once.
-> git commit -m "Your message"                                 Adds a message to our commit.
-> git commit -a -m "Your message"                              It will automatically stage what changed and commit with a message.
-> git log                                                      It will show us the history of commits for our repository.
-> git command -help  or   git help --all                       You can use this command if you are having trouble remembering commands.
-> git branch new-branch-name                                   We created a new branch.
-> git checkout branch-name                                     Checkout is the command used to check out a branch. Move us from current one to specified one.
** Using the -b option on checkout will create a new branch, and move to it, if it does not exist.
-> git branch -d branch-name                                    Deletes the branch.
-> git remote add origin URL                                    Specifies that you are adding a remote repository, with the specified URL, as an origin to your local Git repo.
-> git fetch origin                                             Get all the change history of the origin for this branch.
-> git merge origin/master                                      Merges the current branch with the branch master, on origin.
-> git pull origin                                              Updates the current branch from its origin using a single command.
-> git push origin                                              We push our changes to our remote origin.