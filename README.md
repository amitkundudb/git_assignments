## Assignments
**Question 1** **<br />**

Step 1: Created a new Git repository.<br />

Step 2: Created a file and committed changes.<br />

Step 3: Viewed the commit history of the repository.<br />

Step 4: Opened the file created earlier and made some changes to it. <br />

Step 5: Checked the file modified is now marked as "modified" and unstaged. Hint (git status)<br />

Step 6: Staged the changes made to the file and committed the changes to the repository.<br />

Step 7: Cloned the repository created in GitHub.<br />

Step 8: Fetched the changes, navigated into the cloned repository using the command line, and used the command git fetch to fetch any changes that had been made to the original repository since it was cloned.<br />

Step 9: Pulled changes, merged the changes fetched into the local copy of the repository, and used the command git pull. <br />

**Question 2** 

Step 1: Cloned the repository created in GitHub. 

Step 2: Created a new branch using the command. 

Step 3: Switched to the new branch. 

Step 4: Made some changes to the code in the local copy of the repository. 

Step 5: Committed changes to the new branch. 

Step 6: Switched back to the original branch 

Step 7: Merged the new branch. 

Step 8: Pushed changes to the original branch 

 

 

**Question 3** 

Step 1: Created a feature branch. 

Step 2: Switched to the new branch. 

Step 3: Opened the file and made some changes to it. 

Step 4: Added and committed the changes to the new branch. 

Step 5: Pushed the changes to the new feature branch. 

Step 6: Created a pull request. 

Step 6: As another user in the master branch made some changes to the same file. 

Step 7: Added and committed the changes to the master branch. 

Step 8: Pushed the changes to the master branch. 

Note : There was a conflict in the pull request, and it was resolved using git rebase. 

 

**Question 4** 

Step 1: Created a feature branch. 

 

Step 2: Switched to the new branch. 

Opened the file and made some changes to it. 

Added and committed the changes to the new branch. 

Opened the same file and made some changes to it. 

Added and committed the changes to the new branch. 

Opened the same file and made some changes to it. 

Added and committed the changes to the new branch. 

Step 3: Identified the commit or commits that were wanted to "cherry-pick"(Noted the hash of the commit or commits that were wanted to "cherry-pick") 

Step 4: Used the "git checkout" command to switch to the branch where the changes were wanted to be applied. 

Step 5: Used the "git cherry-pick" command followed by the commit hash(es) that were wanted to be applied. 

 

**Question 5** 

Step 1: Created a feature branch. 

Step 2: Switched to the new branch. 

Opened the file and made some changes to it. 

Added and committed the changes to the new branch. 

Opened the same file and made some changes to it. 

Added and committed the changes to the new branch. 

Opened the same file and made some changes to it. 

Added and committed the changes to the new branch. 

Step 3: Used the "git log" command to view the commit history and identified the commit to which was wanted to reset. 

Step 4: Used the "git reset" command followed by the desired reset type and the commit hash 

Step 5: Verified that the reset was successful by using the "git log" command again.  

Step 6: Used the "git log" command to view the commit history and identified the commit that was wanted to reverse. 

Step 7: Used the "git revert" command followed by the commit hash or reference to which was wanted to revert. (Hint: git revert <commit hash>) 

Step 8: Verified that the revert was successful by using the "git log" command again. 

Note: Identified the difference between git log after git reset and git revert.