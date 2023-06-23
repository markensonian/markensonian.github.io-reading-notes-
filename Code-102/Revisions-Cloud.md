# Revisions and the Cloud

## Welcome to More Git FAQs with Version Control. 

### Q: What is Version Control?

A: Snapshot of your work that can be reverted back to. It's a way to undo work or branch off and experiment when writing code or whatever. You can do this to a Word doc if you want. You can check your status through the terminal by following each step with `git status` to see the state of changes or staging (added files).*

### Q: What is cloning in Git?

A: Copy of a project and allows you to send it to your local computer to work on it outside of GitHub.

### Q: What is the command to track and stage files?q

A: `git add <fileName>` or `git add .` e.g. for tracking all files `$ git add *` and to unstage, use `git reset HEAD ...`. It does this to all files in the folder. The dot stands for all. You can also try $ git clone https://github.com/test mydirectory.

### Q: What is the command to take a snapshot of your changed files?

A: `git commit -m` will commit your changes so it sends it to GitHub as a snapshot. -m means message so you can include why you made changes set within `"<your words here>"`
Saving a changed version of your project — called commit — makes Git take a snapshot of the file and stores a reference to it.

### Q: What is the command to send your changed files to Github?

A: `git push` (e.g. $ git push origin master) will send your committed changes (or snapshot) to GitHub. Once this is done, your branch should be up-to-date and identical in both locations - local (your computer) as well as remote (GitHub). A-C-P
