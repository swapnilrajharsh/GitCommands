# GitCommands
Take a Sneak Peak to Git Commands for quick reference


## How to remove files that are listed in the .gitignore but still on the repository?

``git rm --cached `git ls-files -i -c --exclude-from=.gitignore` ``

[Answer to the same ](https://stackoverflow.com/a/13541721)
