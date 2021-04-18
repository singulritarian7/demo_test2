# demo_test2
Add file to Repository in GitHub
Objective for Exercise

To add file to repository on GitHub
To add file to repository on GitHub through command line
Note: These instructions works on BASH terminal on Windows & Mac terminals.

Click 'Add file' to add a file

image

Provide the file name and add a description to that file. To commit the changes in the repository, click ‘Commit New File’

image

image

Adding a file remotely will not be there in the local directory. Check the files using dir

image

As per the screenshot above, there is 1 file in the repository.

To pull the file that is added in remote repository to local repository, we use PULL command git pull

image

After pull, if I check the local repository using dir, there are 2 files as shown:

image

To add a branch in master branch git branch branchname (occurs localy not remotly)

Switch the branch git checkout branchname

Adding a file in branch echo "content">> filename.txt

Then add the file and push the file. To create the branch remotely we have to use git push --set-upstream origin branchname

image

Switch the branch again to the master using git checkout master

Merge command to merge the branches git merge mybranch ((occurs localy not remotly)

As the merge command is used the new create branch will be merged to the master branch and the file will be inserted to it. Previously, we have 2 file in the master, now there are 3 files. This merge ocurrs locally, not remotly, so make sure to push the files using git push image

Now, the file which is in the branch, is now in the master branch image

Author(s)
Malika Singla
Other Contributor(s)
Lavanya

Changelog
Date	Version	Changed by	Change Description
2020-08-25	2.0	Lavanya	Migrated Lab to Markdown and added to course repo in GitLab
© IBM Corporation 2020. All rights reserved.
