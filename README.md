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


---
Delete the branch safely

Try force deleting a branch (create a dummy branch for this)
## Step 9: Delete the Branch Safely
`git branch -d feature-update`

Deletes the `feature-update` branch after it has been merged.

---

## Step 10: Create a Dummy Branch
`git branch dummy-branch`

Creates a temporary branch for testing force deletion.

---

## Step 11: Force Delete the Dummy Branch
`git branch -D dummy-branch`

Force deletes the `dummy-branch` even if it is not merged.

---









