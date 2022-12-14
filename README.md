# Github
Git command

Using Third-Party Library
Consider you are working on a project that creates a man from a boy. Instead of writing the code from scratch, you found a third-party library, called mustache repo, which can add the required feature to your project.

The possible challenges are:

How will you add the third-party library in your repo?
How will you get further updates (of the third-party library) in the future?
This is where git submodule comes into the picture!
Git submodule will allow you to add a vendor library to your project and get their future updates instantly.

To add a Git submodule use:

Syntax: git submodule add <URL of vendor library>

Example: git submodule add https://github.com/doctrine/some-library.git

  Git Submodule - Cheat Sheet
git submodule add <URL>: Adds a submodule to the project.
git submodule status: View status (working, staging, or indexed files) of all the submodules.
git submodule update: Updates submodules after switching branches.
git submodule update --init: After cloning a new repo, if you need to add submodules to it from .gitmodules file, use this command.
git submodule update --init --recursive: If the submodules inside a newly cloned repo are nested, then use this.
git submodule update --remote: Pulls all changes in the submodules.
  
$ git reflog
fc3d0e7 (HEAD -> branchA) HEAD@{0}: commit: Deleted
d01d36d (HEAD -> branchA, master) HEAD@{0}: checkout: moving from master to branchA
d01d36d (HEAD -> branchA, master) HEAD@{1}: commit: File Created
8c2419a HEAD@{2}: reset: moving to HEAD
