# About
Git Cheat Sheet allows you to get acquainted with Git, which is one of the source control and versioning tools, as well as some questions that may be asked for you and any other programmer to use this source versioning and control tool. It will be answered.

## Why use version control tools like Git?
* We can use it for source management and have a place to maintain and version our system, and one of the most widely used source control system is Git. Also, we need it to implement the DevOps process.

## What is a repository? What important files does a good repository have?
* There is a place or repository that contains all the commits, branches, tags, references and releases.
* A good repository has 3 important files: README.md, .gitignore, LICENSE.

## What are the parts of a good document?
* A good document of three parts: \
1- What is this project doing and what is it supposed to do? \
2- How should we use it? \
3- If someone wanted to help improve the performance of the program, how can he do it?

## What does the ```git clone``` command do?
* This command creates a copy of the source in the remote repository on the our local system.

## What command should be executed if we want to update the local repository with the remote repository?
* ```git fetch```

## What is the difference between checkout, reset, revert?
* ```checkout``` returns to the desired branch without creating a commit.
* ```revert``` returns to the desired branch but also creates a new commit.
* ```reset``` returns to the desired brunch but deletes the commit.

## What is the difference between merge and rebase?
* In merge, it creates a new commit, but in rebase, if there are changes in the reference, we can merge the changes according to the order.

## What command is used to view the history of commits?
* ```git log```

## What command do we use if we want to see the changes of a file?
* ``` git diff ```

## What is a tag for? How to create a tag?
* Tags are ref's that point to specific points in Git history. Tagging is generally used to capture a point in history that is used for a marked version release (i.e. v1.0.1).
* To create a tag, ``` git tag <tagname> ```

## What is the process to participate in a project managed with git?
* We need to be able to clone of the repository on our system using git clone, make the necessary changes, stage the changes, be able to see history, revert, checkout, pull, and also merge, push.

## What are the branches used for and how can they be integrated?
* When we want to create a new feature or make changes to the source, we create a new branch. By doing this, we can encapsulate our source with the created changes.
* To combine the branches, we can use ```git merge``` or ```git rebase```


[@dwsclass](https://github.com/dwsclass) dws-dev-004-git