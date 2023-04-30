# Version control
Version control, also known as source control, is the practice of tracking and managing changes to software code.  

## Goal of learning
By completing this tutorial, you will be able to:
- Understand the concept of version control (What is VC? Common toolings? Common conventions?)
- Understand common Git operations (init, add, commit, push, pull, merge, rebase, etc.)
- Use Git with GitHub
- Understand and able to write GitHub-flavored markdown

## Learning materials
### What is version control?
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.  

Excellent video explaining what is VC and how it works:  
[![What is Version Control?](https://img.youtube.com/vi/xQujH0ElTUg/0.jpg)](https://www.youtube.com/watch?v=xQujH0ElTUg)

### Common Git operations
> If you need help installing Git on your machine, go to: [Install Git
](https://www.atlassian.com/git/tutorials/install-git)

Read and learn below Git operations:

#### Basic operations
- [git init](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-init)
- [git add](https://www.atlassian.com/git/tutorials/saving-changes)
- [git commit](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)
- [git stash](https://www.atlassian.com/git/tutorials/saving-changes/git-stash)
- [git status](https://www.atlassian.com/git/tutorials/inspecting-a-repository)
- [.gitignore](https://www.atlassian.com/git/tutorials/saving-changes/gitignore)

#### Syncing
- [git remote](https://www.atlassian.com/git/tutorials/syncing)
- [git fetch](https://www.atlassian.com/git/tutorials/syncing/git-fetch)
- [git push](https://www.atlassian.com/git/tutorials/syncing/git-push)
- [git pull](https://www.atlassian.com/git/tutorials/syncing/git-pull)

#### Branching
- [git branch](https://www.atlassian.com/git/tutorials/using-branches)
- [git checkout](https://www.atlassian.com/git/tutorials/using-branches/git-checkout)
- [git merge](https://www.atlassian.com/git/tutorials/using-branches/git-merge)
- [Merge conflicts](https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts)

#### Advanced git operations
- [Pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
- [git rebase](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)

#### GitHub flavored markdown
- [About writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## Exercises

### Exercise 1: Fork, branch and rebase
1. Fork this repo
2. Branch off from the default branch, name it `your-name`. Example: `michael-jackson`
3. Go to your branch
4. Add your name to the line below:
> Make sure to make this change on your branch. Your name goes here: Anna Zhao	
5. Go back to the default branch, add your name to the line below:
> Make sure to make this change on the default branch. Your name goes here: Anna Zhao
6. Go back to your branch, rebase default branch
7. Push your branch to remote
8. Push the default branch to remote
9. Share your repo with your manager for review
