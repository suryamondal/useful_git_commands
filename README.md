# Some useful git commands and the use of those
*Here I listed some of the git commands and how to use them efficiently. You no need to be a professional to use it. Git supposed to be for all. This tutorial is only for the people who does not want to be a professional.*

The concept of `git` is simplicity. The main point of git is that one does need to create new file or folder to keep track of the evolution (or changes) of a project.

The main byproduct of this notions is that; `git` also can track the evulution of a project with multiple contributors.

For me, I use `git` along with `github`  also for coping the codes between two or more terminals. It is really quicker and efficient than use `rsync` for these small ASCII files.

## Local Repository
A git `repository` is synonymus to a `folder` or `directory`, but actualy not. A git repository resides inside a folder, and that is the end of the similarity. We do not want to create multiple copy of the same objects when moving to a new versions.

So, we create a folder/directory named `useful_git_commands`. The we go inside it. We then execute the following command.
```
git init
```
This creates a directory named `.git` inside `useful_git_commands` and fills it with all the necessary objects. **We, amatures, must never cause any harm to this one.**

