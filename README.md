# Github_Shree_Assignment
Git &amp; Github Assignments

#Assignment1

## Steps

### Step 1: Check Repository Status
`git status`

Checks tracked and untracked files.

### Step 2: Stage Files
`git add .`

Adds all changes to the staging area.

### Step 3: Commit Changes
`git commit -m "new feature added"`

Saves changes with a commit message.

### Step 4: Push to GitHub
`git push`

Uploads local commits to the remote repository.
git status

git add .


<img width="1180" height="801" alt="image" src="https://github.com/user-attachments/assets/139c1397-91dc-4a9d-a6ec-e00dbad4fdcd" />

## Step 5: Add Remote Repository
`git remote add origin https://github.com/Sandhyashree1812/Github_Shree_Assignment.git`

Links the local project to the GitHub repository.

---

## Step 6: Verify Remote Connection
`git remote -v`

Displays the connected remote repository URLs.

---

## Step 7: Push Branch to GitHub
`git push -u origin main`

Pushes the `main` branch to GitHub and sets it as the default upstream branch.

---

<img width="1195" height="297" alt="image" src="https://github.com/user-attachments/assets/1ec315ec-0719-42b0-ba79-7fb65d901170" />

<img width="1875" height="492" alt="image" src="https://github.com/user-attachments/assets/4cbfea94-73ef-4896-8774-ada6ebcc846c" />

<img width="1642" height="521" alt="image" src="https://github.com/user-attachments/assets/20770985-23aa-49c8-a69a-f4a65aa5fdd4" />

========================== 


#Assignment 2

## Step 1: Modify `app.py`
Make changes or add new functionality inside `app.py`.


<img width="1590" height="228" alt="Screenshot 2026-05-10 074725" src="https://github.com/user-attachments/assets/a4a14353-e235-4602-b9f0-50eb237cd306" />

-------

## Step 2: Check Changes Before Staging
`git status`

Shows modified files before staging.

<img width="762" height="260" alt="image" src="https://github.com/user-attachments/assets/9fab891c-8b76-49e5-8a6e-6b816b4c7705" />

------

## Step 3: View File Differences
`git diff`

Displays the changes made in the file.

---

## Step 4: Stage Specific Changes
`git add -p`

---------

## Step 5: Commit Changes
`git commit -m "Added 3 new features"`

Creates a new commit with a descriptive commit message.

<img width="1200" height="765" alt="Screenshot 2026-05-10 075418" src="https://github.com/user-attachments/assets/960e089d-6149-468d-8eca-8b3b368040f5" />

================== 


## Step 6: Make Another Change
Edit `app.py` again with additional updates.

<img width="1595" height="393" alt="Screenshot 2026-05-10 080852" src="https://github.com/user-attachments/assets/a3339ac4-6ae2-4b45-8307-97387a90cef9" />

<img width="850" height="342" alt="Screenshot 2026-05-10 081221" src="https://github.com/user-attachments/assets/c855fcd5-adfd-41a1-8f47-1108835e0315" />

---------

## Step 7: Stage All Changes
`git add .`

Stages all modified files.

<img width="582" height="265" alt="Screenshot 2026-05-10 081434" src="https://github.com/user-attachments/assets/c90e0074-fe22-402f-b8fc-7abaa4d90c12" />


------


## Step 8: Commit Again
`git commit -m "two new Functions added"`

Saves the latest updates.

<img width="962" height="72" alt="Screenshot 2026-05-10 082101" src="https://github.com/user-attachments/assets/d32bd89f-f562-4b99-bbc4-37f0727d6688" />

-----------

## Step 9: View Full Commit History
`git log`

Displays detailed commit history.

<img width="973" height="701" alt="Screenshot 2026-05-10 082255" src="https://github.com/user-attachments/assets/1513975e-5689-40b3-97b3-8b54528061d6" />

---------


## Step 10: View Compact Commit History
`git log --oneline`

Displays commit history in one-line format.

<img width="610" height="147" alt="Screenshot 2026-05-10 082430" src="https://github.com/user-attachments/assets/2731d374-25c2-4e74-844e-5277c450f206" />

---------

======================================================================================================================================================

#Assignment 3

## Step 1: Create a New Branch
`git branch feature-update`

Creates a new branch named `feature-update`.

---

## Step 2: Switch to the New Branch
 `git checkout -b feature-update`
 Creates and switches to the branch in one step.

---

## Step 3: Modify `app.py`
Update `app.py` with new feature logic.

---

## Step 4: Stage Changes
`git add .`

Stages all modified files.

---

## Step 5: Commit Changes
`git commit -m "two new Logics added"`

Creates a commit with the latest changes.

<img width="812" height="571" alt="Screenshot 2026-05-10 083947" src="https://github.com/user-attachments/assets/50510367-d8e4-40a7-b06f-11f6c671fb8c" />

<img width="1056" height="331" alt="Screenshot 2026-05-10 084342" src="https://github.com/user-attachments/assets/b51f3759-064a-4f8a-9233-b0f831f2b97f" />

----- 

## Step 6: Switch Back to the Main Branch
`git checkout main`

Switches from the feature branch to the `main` branch.

<img width="795" height="246" alt="Screenshot 2026-05-10 084730" src="https://github.com/user-attachments/assets/78f961fe-f12a-44df-a3f9-e9101d51f089" />

Note: We see the app.py in main doesnt have the logics added in app.py of feature-update

<img width="843" height="456" alt="Screenshot 2026-05-10 084751" src="https://github.com/user-attachments/assets/7af6e8ad-eb52-4d65-ad0a-6f44449195eb" />



---

## Step 7: Merge the Feature Branch into Main
`git merge feature-update`

Merges the changes from the `feature-update` branch into `main`.

<img width="706" height="153" alt="Screenshot 2026-05-10 090641" src="https://github.com/user-attachments/assets/a76a9784-5b38-4bc3-96d1-5a2fbb2e0d45" />



---

## Step 8: Verify Merged Changes
`git log --oneline`

Displays commit history to confirm the feature branch changes were merged successfully.


<img width="752" height="252" alt="Screenshot 2026-05-10 090818" src="https://github.com/user-attachments/assets/7ea74cf4-6793-4b67-8c84-31810964db1b" />



<img width="688" height="391" alt="Screenshot 2026-05-10 090939" src="https://github.com/user-attachments/assets/3221f32f-4ce7-470c-90b3-8bfa97b423c3" />



<img width="725" height="295" alt="Screenshot 2026-05-10 091008" src="https://github.com/user-attachments/assets/7d2242b7-c656-4801-8c35-4f2d5bb143df" />



<img width="636" height="188" alt="Screenshot 2026-05-10 155615" src="https://github.com/user-attachments/assets/92f2bd55-9857-4bbf-8adf-8807bfc24550" />



---
Delete the branch safely

Try force deleting a branch (create a dummy branch for this)
## Step 9: Delete the Branch Safely
`git branch -d feature-update`

Deletes the `feature-update` branch after it has been merged.

<img width="687" height="381" alt="Screenshot 2026-05-10 160811" src="https://github.com/user-attachments/assets/70871e44-01ed-431b-94a7-3ac07c9640b1" />



---

## Step 10: Create a Dummy Branch
`git branch dummy-branch`

Creates a temporary branch for testing force deletion.

---

## Step 11: Force Delete the Dummy Branch
`git branch -D dummy-branch`

Force deletes the `dummy-branch` even if it is not merged.

<img width="1050" height="267" alt="Screenshot 2026-05-10 161318" src="https://github.com/user-attachments/assets/4e160766-49c4-4516-9c80-bc9fd96d8287" />


---

================================================================================================================ 

#Assignment 4

## Step 1: Modify `app.py`
Make changes in `app.py` without committing them.

---

## Step 2: Stash the Changes (Including Untracked Files)
`git stash -u`

Temporarily saves tracked and untracked changes.



---

## Step 3: Check the Stash List
`git stash list`

Displays all saved stashes.

<img width="782" height="132" alt="Screenshot 2026-05-10 162704" src="https://github.com/user-attachments/assets/758c856d-601b-4442-8b12-466e302013f8" />



---

## Step 4: Apply the Stashed Changes Back
`git stash apply`

Restores the most recent stashed changes.

<img width="696" height="353" alt="Screenshot 2026-05-10 164033" src="https://github.com/user-attachments/assets/f7895ab1-0d18-4360-aa35-8a5b806c5e7e" />

<img width="622" height="327" alt="Screenshot 2026-05-10 164650" src="https://github.com/user-attachments/assets/7c96ad1c-46c7-4bd3-8018-e726707fe214" />



---

## Step 5: Commit the Changes
```bash
git add .
git commit -m "Restored and committed stashed changes"
```

Stages and commits the restored changes.

<img width="956" height="187" alt="Screenshot 2026-05-10 165210" src="https://github.com/user-attachments/assets/77d5e225-a8aa-4a76-aa28-86c647ca1ff8" />


---

## Step 6: Make Another Commit with Incorrect Code
```bash
git add .
git commit -m "Added incorrect code"
```

Creates a commit containing incorrect changes.

<img width="516" height="382" alt="image" src="https://github.com/user-attachments/assets/471f684f-9af1-4406-aab9-d7a526c517ad" />



---

## Step 7: Undo the Last Commit Using Reset soft
`git reset --soft HEAD~1`

Removes the last commit while keeping the changes in the staging area.

<img width="756" height="201" alt="image" src="https://github.com/user-attachments/assets/a1fb5432-0282-49b1-95fa-422771186369" />

<img width="522" height="387" alt="image" src="https://github.com/user-attachments/assets/b8937980-2d23-4a3a-8aaf-a4f41cef418d" />



## Step 8:Undo the Last Commit Using Reset hard
`git reset --hard HEAD~1`
Completely removes the last commit and its changes.

<img width="925" height="120" alt="image" src="https://github.com/user-attachments/assets/03c3e5d2-425f-48e1-9725-d23aa3834471" />

<img width="467" height="267" alt="image" src="https://github.com/user-attachments/assets/0197763c-3569-44d1-b7ce-5eee0795e32e" />



---

## Step 9: Make Another Commit
```bash
git add .
git commit -m "Added 2 lines of corrected code"
```

Creates a new commit with corrected changes.

<img width="460" height="287" alt="image" src="https://github.com/user-attachments/assets/cd4b8c64-0f10-44b0-9f99-504730af542d" />

<img width="861" height="177" alt="image" src="https://github.com/user-attachments/assets/1d1bb4e6-5382-43c7-92e0-a6e7f788cf1c" />

---

## Step 10: Undo a Commit Using Revert
`git revert HEAD`

Creates a new commit that reverses the latest commit changes.

<img width="636" height="192" alt="image" src="https://github.com/user-attachments/assets/153b15b9-6dff-4efc-b454-68a0b64cb789" />

Previous:
<img width="460" height="287" alt="Screenshot 2026-05-10 201213" src="https://github.com/user-attachments/assets/ca57dab1-c306-4ea6-9e53-3df6347c8341" />

After Revert:
<img width="417" height="317" alt="image" src="https://github.com/user-attachments/assets/4257ef96-529c-4e25-a2e2-d7ce3501a9a9" />

NoteL we enter a editor here , to quit press esc key and enter or :wq and enter

---

## Step 11: Verifying the Commit History
`git log --oneline`

Displays the updated commit history in compact format.

<img width="807" height="302" alt="image" src="https://github.com/user-attachments/assets/f9362d79-95cd-432d-993f-164bcf075bda" />


---

========================================== 










