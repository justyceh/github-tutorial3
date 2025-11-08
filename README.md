# Github tutorial 3

In this tutorial we are focusing on git branching and how it works



# Github branching


Master Branch

Commit 1 --- Commit 2 --- Commit 3


But we could create anoter branch if we want to like so

Here Commit 1 - 4 represents master branch, below it where a new commit 1 --- commit 2 appears is the feature branch
Commit 1 --- Commit 2 --- Commit 3 --- Commit 4 
                                \
                                  \
                                    Commit 1 --- Commit 2

Any changes we make on this feature branch, or different branch will not be reflected onto the master branch

Any commits made onto the master branch will not be reflected on to the feature branch unless we make the feature branch come from that last commit from the master branch

We can then eventually Merge our feature or hot fix branches back together 

This is useful for debugging and handling potential app breaking bugs, by creating a new branch from the master branch we can test various solutions and if they work we can merge them back to the master branch

Remember:
If you have two branches, one master, one hot fix
Anything commited to the hot fix will not be commited to the master, anything commited to the master (after the hot fix branch has been already created) will not be reflected in the hot fix branch


- We can check our branches by running git branch, any name with a asterik next to it, is the branch you are currently on

- We can use git checkout -b to create a new branch, or switch between sticks
- We can use git checkout -b to create a new branch, or switch between trees