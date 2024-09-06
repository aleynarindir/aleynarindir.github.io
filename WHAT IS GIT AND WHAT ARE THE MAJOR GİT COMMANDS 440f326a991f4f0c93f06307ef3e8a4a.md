# WHAT IS GIT AND WHAT ARE THE MAJOR GİT COMMANDS?

September 2,2024

### What is Git?

Git is a version control system. It was developed by Linus Torvalds in 2005 and widely used, especially in large software projects. Git is a tool that allows person-based changes to be made in projects where one or more people work. These changes are saved by Git and the project is kept up to date.

![image.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/image.png)

Working Directory:  This is the area where changes are made for the project.

Staging Area: It is where changes made to the working area are collected before they are permanently added to a transaction.

Local Repository: It was a storage that is kept locally on the computer and can only be accessed by the person working in folder.

Remote Repository: It is a repository that is usually hosted on a platform such as Github, Gitlab, Bitbucket and accessible to team members.

### Let’s illustrate with a simple example 🍎

We have a project and let's think of this project like an apple. 5 people will do the project. Therefore, first of all, let's divide the apple into 4 and send it by truck to 4 people to make changes. Let each person perform operations such as git add, git commit and keep the apple slice in their local repository. Finally, have them truck those apple slices via git push to the remote warehouse for other people to see. The 5th person should add the bought apple slices to her own repositoy using git pull and work on them again.

### Major git commands

1. **Git Config:**  It comes from the word configuration It is the process of introducing the names and e-mails of the people participating in the project.

        **git config    —global     user.name    “aleynanarin”**

        **git config    —global      user.email     “aleyna.narin.1@gmail.com”**

If we want to see our settings configured with git config, we use the following command.

        **git config     —list**

If we want to see only the user name or user email

        **git config     —global    user.name/user.email**

**PWD:**  It shows which file we are in.   

![image.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/image%201.png)

**CD:** It is used to enter the file.

        **cd    [folder name]**

- **cd  ..** : Used to go back to a folder.

![image.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/image%202.png)

**LS:** It shows the files and directories of the current folder.

- **ls  —l:** Shows the file contents one under the other.
- **ls  —a:** Hidden files are also accessed

![Ekran Resmi 2024-09-02 12.01.46.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-02_12.01.46.png)

![Ekran Resmi 2024-09-02 12.04.03.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-02_12.04.03.png)

**MKDIR:** Used to create a new folder.

        **mkdir   [folder name]**

 **TOUCH:** It is used to create files in the folder.

        **touch   [file name]**

![image.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/image%203.png)

![Ekran Resmi 2024-09-02 12.02.57.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-02_12.02.57.png)

**VI / VIM:** If you want to write something to the file, vi or vim command is used.

        **vi /vim    [file name]**

To write, we must first press the "i" key.

To exit, you need to press “esc : w q “keys respectively.

[data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAQAAAAngNWGAAABDUlEQVR4AYXRgUZDYRjH4TegFTKgpEqiFJgoWAoMEQGBgBboChaaAKxLKAhAhQqAdAmpBIQolkCFqp2nITvNKXuA7+/Hhzey5OWjE4Nq3rzY1f9/NGHPB549492+8Ww060iCS2XdctZdI3GsECmb+HJoIX6x6EgDm+lURTH+YB7V9nAqE5WNme4YKuOiY6iMe6PaQxUUIuTbswgFVNJwA8sO3Bn6yR6bWZMSNtJwDtuWfHpQxaPx9C9zadil7jrCigbq6UXceNIVKTWUIqypm2ytJdTiNyNeXclF6GttOVfeDEc7qzjR23r3OMFqZKng1kw0mXGLrfibHTScOZWgGv9TdC6ROFeMTgwYiIxvJzMRWQbeGZUAAAAASUVORK5CYII=](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAQAAAAngNWGAAABDUlEQVR4AYXRgUZDYRjH4TegFTKgpEqiFJgoWAoMEQGBgBboChaaAKxLKAhAhQqAdAmpBIQolkCFqp2nITvNKXuA7+/Hhzey5OWjE4Nq3rzY1f9/NGHPB549492+8Ww060iCS2XdctZdI3GsECmb+HJoIX6x6EgDm+lURTH+YB7V9nAqE5WNme4YKuOiY6iMe6PaQxUUIuTbswgFVNJwA8sO3Bn6yR6bWZMSNtJwDtuWfHpQxaPx9C9zadil7jrCigbq6UXceNIVKTWUIqypm2ytJdTiNyNeXclF6GttOVfeDEc7qzjR23r3OMFqZKng1kw0mXGLrfibHTScOZWgGv9TdC6ROFeMTgwYiIxvJzMRWQbeGZUAAAAASUVORK5CYII=)

[data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAQAAAAngNWGAAABDUlEQVR4AYXRgUZDYRjH4TegFTKgpEqiFJgoWAoMEQGBgBboChaaAKxLKAhAhQqAdAmpBIQolkCFqp2nITvNKXuA7+/Hhzey5OWjE4Nq3rzY1f9/NGHPB549492+8Ww060iCS2XdctZdI3GsECmb+HJoIX6x6EgDm+lURTH+YB7V9nAqE5WNme4YKuOiY6iMe6PaQxUUIuTbswgFVNJwA8sO3Bn6yR6bWZMSNtJwDtuWfHpQxaPx9C9zadil7jrCigbq6UXceNIVKTWUIqypm2ytJdTiNyNeXclF6GttOVfeDEc7qzjR23r3OMFqZKng1kw0mXGLrfibHTScOZWgGv9TdC6ROFeMTgwYiIxvJzMRWQbeGZUAAAAASUVORK5CYII=](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAQAAAAngNWGAAABDUlEQVR4AYXRgUZDYRjH4TegFTKgpEqiFJgoWAoMEQGBgBboChaaAKxLKAhAhQqAdAmpBIQolkCFqp2nITvNKXuA7+/Hhzey5OWjE4Nq3rzY1f9/NGHPB549492+8Ww060iCS2XdctZdI3GsECmb+HJoIX6x6EgDm+lURTH+YB7V9nAqE5WNme4YKuOiY6iMe6PaQxUUIuTbswgFVNJwA8sO3Bn6yR6bWZMSNtJwDtuWfHpQxaPx9C9zadil7jrCigbq6UXceNIVKTWUIqypm2ytJdTiNyNeXclF6GttOVfeDEc7qzjR23r3OMFqZKng1kw0mXGLrfibHTScOZWgGv9TdC6ROFeMTgwYiIxvJzMRWQbeGZUAAAAASUVORK5CYII=)

![Ekran Resmi 2024-09-02 13.02.39.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-02_13.02.39.png)

**CAT:**  It allows us to view the file content.

        **cat    [file name]**

![Ekran Resmi 2024-09-02 15.26.35.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-02_15.26.35.png)

**RM:** Used to delete files. 

        **rm    [file name]**

If we want to delete both the folder and the files in it, we use the following command.

        **rm   -r    [name of folder]**   

1. **Git Init:** With the git init command, a hidden repository with the ".git" extension is created in the current folder. In this way, all git-related features become available.We can also call it the start command.

![Ekran Resmi 2024-09-02 13.25.21.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-02_13.25.21.png)

1. **Git Status:** This command shows which files have been modified, which have the staging area added (i.e. made ready to commit), and which are untracked (untracked). So it is a monitoring command.

![Ekran Resmi 2024-09-02 14.09.03.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-02_14.09.03.png)

1. **Git Add:**  The git add command is used to make the files ready for commit in the staging area.

        **git    add    [file name]**

If we want to add a folder and the files in it to the repository, the following command is used.

        **git add .** 

![image.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/image%204.png)

If we want to retrieve the file sent to the staging area from the storage area, the following command is used.

        **git  rm   —cached   [file name]**

![Ekran Resmi 2024-09-02 14.47.15.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-02_14.47.15.png)

1. **Git Commit:** With the commit command, we save the changes made in the project in the local repository.

        **git   commit   -m   “first commit /initial commit”**

If we want to see the commit history, we use the following command.

        **git     log** 

![Ekran Resmi 2024-09-03 13.43.47.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-03_13.43.47.png)

If we want to get briefer information about the commits made, we can use the following command.

        **git   log     —oneline** 

![Ekran Resmi 2024-09-03 13.53.03.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-03_13.53.03.png)

1. **Git Reset:** It is a powerful command used to undo changes made.

If we want to revert to the desired version and definitively delete subsequent versions, we use the following command.

        **git    reset     [commit id]    —hard**

If you want to delete the transaction from the commit but want to process it in the staging area and make it ready for committing later, you can use the command below.

        **git    reset    [commit id]     —soft**

1. **Git Amend:**  If we want to change the message of the last commit made, we use this command.Additionally, changes can be made in the same commit with this command.

        **git     commit     —amend      -m      “The commit message”**

The following command is used to see the content of the latest commit and change its message if we want.

        **git      commit    amend**

![Ekran Resmi 2024-09-03 16.42.32.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-03_16.42.32.png)

1. **Git Revert:** This command undoes the selected commit, but creates a new commit in doing so. Reverses the changes made by the reverted commit and saves those changes as a new commit.

        **git      revert      [id of the commit to be reverted]**

💡   For example, I am doing a project.

Commit A:I create a file: file.txt and write "Hello World" in it.
Commit B: I update the file.txt and write "Hello Git"
Commit C: I update the file.txt file again and write "Hello Git Revert".
In this case, my commit history would be like this:

Commit C: "Hello Git Revert" (Final version)
Commit B: "Hello Git"
Commit A: "Hello World"

If I run git revert B it will reverse the changes that Git Commit B made. So, Commit B had added "Hello Git" to the file; git revert undoes this and removes the "Hello Git" part from the file, so the file content becomes "Hello World" as in Commit A.

However, this change is added as a new commit:

Commit D (Revert B): "Hello World" (This commit reverses the effect of Commit B).

1. **Git Branch:** We need branches when we want to make developments independently of the main project. After checking whether the operations we performed are useful or not, if we do not encounter any errors, we merge the branch we used with the master branch. Each person working on the project has their own branch they work on.

💡 The branch can be created from the master branch or from any branch.

💡 Files that are not created on the master branch do not appear on the master branch.

If we want to see the branch in the folder we are in, we use the following command.

        **git branch**

![Ekran Resmi 2024-09-03 21.43.56.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-03_21.43.56.png)

If we want to create a branch, we use the following command.

        **git    branch     [the name of the branch we want to create]**

![Ekran Resmi 2024-09-03 21.52.56.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-03_21.52.56.png)

If we want to switch from one branch to another, we use the following command.

        **git      checkout        [the name of the branch we want to switch to]**

![Ekran Resmi 2024-09-03 22.04.47.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-03_22.04.47.png)

If we want to both create a branch and switch to that branch, we use the following command.

        **git       checkout         -b**          **[the name of the branch we want to create]**

![Ekran Resmi 2024-09-04 06.18.45.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_06.18.45.png)

If we want to list the created branches, we use the following commands.

        **git        branch        -a**

        **git        branch        —all**

![Ekran Resmi 2024-09-04 06.14.05.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_06.14.05.png)

If we want to delete the branch, we use the following command.

        **git      branch       -D.         [the name of the branch we want to delete]**

![Ekran Resmi 2024-09-04 06.26.03.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_06.26.03.png)

If we want to call the branch we want to merge, we use the following command. First of all, we need to be in the branch on which we will merge.

        **git       merge      [name of the branch to be added]** 

![Ekran Resmi 2024-09-04 06.31.12.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_06.31.12.png)

1. **Git Diff:** If we want to list a change made to a file on the terminal, we use this command

![Ekran Resmi 2024-09-04 07.06.02.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_07.06.02.png)

If we want to undo the changes we made to our existing file, we use the following command.

        **git    checkout     —  [file name]**

![Ekran Resmi 2024-09-04 07.32.27.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_07.32.27.png)

1. **Git Move:** 

If we want to change the name of this command file, we use the following command.

        **git    mv     [the file we want to change]         [new name of the file]**

![Ekran Resmi 2024-09-04 09.01.07.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_09.01.07.png)

If we want to move the file, we use the following command.

        **git       mv        [the name of the file we want to moved]             [the name of the folder that will contain the file]/**       

![Ekran Resmi 2024-09-04 09.10.08.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_09.10.08.png)

If we want to change the name of the file while moving it, we use the following command.

**git        mv          [name of the file to be moved and renamed]**          **[the name of the folder that will contain the        file]/[new name of the file].extension**

![Ekran Resmi 2024-09-04 09.22.01.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_09.22.01.png)

1. **Git Stash:** While working on a project, when we need to leave our current job and do another job, we save all the changes we made by sending them to another area with this command.

        **git       stash       save     “A descriptive message, such as a commit message”**

![Ekran Resmi 2024-09-04 09.53.29.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_09.53.29.png)

If we want to sort our current stash, we use the following command.

        **git      stash      list**

![Ekran Resmi 2024-09-04 09.56.32.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_09.56.32.png)

If we want to see the change in the stash we want, we use the following command.The last stash id is 0, the id value increases from the end to the beginning as 1 2 3..

        **git        stash       show     -p    [stash id]** 

![Ekran Resmi 2024-09-04 10.05.16.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_10.05.16.png)

If we want to clear the last stash with id 0, we use the following command.

        **git      stash     drop** 

![Ekran Resmi 2024-09-04 10.11.53.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_10.11.53.png)

If we want to clear any stash, we use the following command.

        **git      stash     drop   [stash id]**

![Ekran Resmi 2024-09-04 10.15.59.png](WHAT%20IS%20GIT%20AND%20WHAT%20ARE%20THE%20MAJOR%20GI%CC%87T%20COMMANDS%20440f326a991f4f0c93f06307ef3e8a4a/Ekran_Resmi_2024-09-04_10.15.59.png)

If we want to restore deleted stash, we use the following command.

        **git      stash     pop**