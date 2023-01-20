To revert the changes of a merge you need to use the following command:

git revert [commit] -m 1

This reverts all the merged in changes. 

An important point:

The changes are still in the Git History, so if you later need the changes from the previously merged branch you need to revert the revert.