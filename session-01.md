# Session 01

## `git`

`git` is the underlying software we will use to manage changes to our code and track the history of those changes. You can use `git` directly (via the command-line) or indirectly through another application like Visual Studio Code or GitHub Desktop. No matter how you use it, it works the same, so there are some foundational ideas to become familiar with.


## Terminology

### Repository

A project. To you, it will *look like* the collection of files and folders that make up the project. In reality, it is a complete internal database tracking the entire history of the project. This term is often shortened to `repo`.


### Local and Remote

A *local* repository is a copy of the repository on the machine you're working on. A *remote* repository is a copy of the repository *anywhere* else - whether it's on someone else's computer, another one of your computers, or hosted somewhere like GitHub. `git` is distributed, meaning that as long as locals and remotes are kept in sync with one another, you can recover the complete history of the repository from a single copy anywhere.

In many cases, you will designate a specific remote (usually the one on GitHub) as the original and source of truth, but this doesn't always have to be the case.


### `origin`

By convention, `origin` is a special name we give to the remote repository that will serve as our source of truth and as the original copy. For us, that means that the remote repository kept in GitHub is our `origin` for a local repository.


### Branch

A repository may have one or more branches, which act as alternate concurrent versions of the repository. The `main` branch is usually considered the current version of repository, but you can create many more branches that are works-in-progress that include changes to what is currently in the `main` branch, all while leaving the `main` branch in a stable state until your work is complete. When you save changes, it is usually done to the branch you are currently working on until you are ready for those changes to be added to another branch, like `main`.


### Working Directory

This is the area where you are actively working. When you make changes to a file, create a new file, or delete a file, those changes are all placed into your working tree once you save. This area is *untracked*. You are able to view the differences you've made up until this point, but they are not being saved by `git`, so you can easily abandon them if you change your mind, but you can easily lose them if you aren't careful.


### Staging Area

This is where changes can move after the working directory. After you make a change to a file and save it to the working directory, you can use `git` to promote it to the staging area. This is when `git` starts actively tracking the changes you're making. If you make changes to a file after you add it to the staging area, the old changes will appear in the staging area, but the new changes will only appear in the working directory until you add them to the staging area as well. At this point, your changes are still not part of the history, but you have bundled them together to get them ready.


### Commit

A commit is the way `git` adds changes to the history. When you make a commit, you are taking everything in the staging area and creating a bundle for `git` to add to the history. When the files in the staging area are turned into a commit, they are added to the history of the branch you're working on and removed from the staging area. You can include as few as one file in a commit or you can include changes to every file in your repository in a commit while also adding new files.

There is no strict rule for what should go in a commit, but a guideline I try to follow that commits should be complete thoughts. Maybe there are 10 things I need to accomplish as part of the changes I'm working on. If so, I would probably make each of those 10 a separate commit. If the first change requires edits to three files, I would make those changes, add them to the staging area, and commit them before moving to the second change.

It's also not necessary that everything *work* with each commit, but I would also recommend that as a good habit when possible. If making the first change makes it so that the code no longer builds, then maybe you should consider getting it into a working state before doing a commit. These guidelines are all competing priorities, and it's not always possible to achieve all of them at once, so find a flow or pattern that works for you.


### Merge

### Pull Request
