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
