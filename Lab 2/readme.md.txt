# Lab 02 – Git & GitHub Operations

**Name:** Rafia Fiaz  
**Reg No:** 2023-BSE-051  
**Class & Section:** BSE 5-B  
**Submitted To:** Sir Shoaib  

---

## 🧩 Task 1  
**Objective:** Set up the lab environment and prepare for Git operations.  

No screenshots required for this setup step.  

---

## 🔑 Task 2 – Generate and Add SSH Key  

1. Generate a new SSH key using PowerShell.  
2. Add your SSH public key to GitHub under **Settings → SSH and GPG keys**.  
3. Clone your Lab 2 repository using SSH.

### 📸 Screenshots for Task 2
![SSH Key Generation](../Lab2/Screenshots/ssh_keygen.png)  
*Generating new SSH key using PowerShell.*

![GitHub SSH Key Added](../Lab2/Screenshots/github_sshkey.png)  
*SSH key successfully added on GitHub.*

![Repository Cloned via SSH](../Lab2/Screenshots/ssh_clone.png)  
*Cloning Lab 2 repository using SSH.*

---

## 🧠 Task 3 – Configure Git Identity  

1. Set up your Git username and email.  
2. Verify configuration with `git config --list`.

### 📸 Screenshots for Task 3
![Git Identity Setup](../Lab2/Screenshots/git_identity.png)  
*Setting Git username and email.*

![Git Config List](../Lab2/Screenshots/git_config_list.png)  
*Verifying Git configuration.*

---

## 🗂 Task 4 – Explore the .git Folder  

View the internal structure of the `.git` directory to understand repository metadata.

### 📸 Screenshots for Task 4
![Git Folder](../Lab2/Screenshots/git_folder.png)  
*Contents of the .git folder.*

---

## 🧹 Task 5 – Re-initialize Repository  

1. Delete existing `.git` folder.  
2. Re-initialize using `git init`.  
3. Add and commit a new `README.md`.  
4. Connect to GitHub and push.

### 📸 Screenshots for Task 5
![Deleting Old Git Folder](../Lab2/Screenshots/delete_git.png..png)  
*Removing the old .git folder.*

![Git Init](../Lab2/Screenshots/git_init.png)  
*Re-initializing the repository.*

![First Commit](../Lab2/Screenshots/first_commit.png)  
*Initial commit after re-init.*

![First Push](../Lab2/Screenshots/first_push.png)  
*Pushing committed files to GitHub.*

---

## 📝 Task 6 – Work with Notes File  

1. Create `notes.txt` and write content.  
2. Check status, stage, and commit.  
3. Edit again and repeat commit steps.

### 📸 Screenshots for Task 6
![Status Check](../Lab2/Screenshots/status1.png)  
*Checking Git status after file creation.*

![Commit Notes](../Lab2/Screenshots/commit_notes.png)  
*Committing initial notes file.*

![Update Commit](../Lab2/Screenshots/commit_update.png)  
*Committing updates after editing.*

---

## 🌿 Task 7 – Create Bugfix Branch on GitHub  

1. Create branch `bugfix/user-auth-error` on GitHub.  
2. Pull the branch locally.

### 📸 Screenshots for Task 7
![Bugfix Branch GUI](../Lab2/Screenshots/bugfix_branch_gui.png)  
*Bugfix branch created on GitHub.*

![Bugfix Branch Local](../Lab2/Screenshots/bugfix_branch_local.png)  
*Pulled branch locally.*

---

## ⚙️ Task 8 – Create Feature Branch (DB Connection)  

1. Create branch `feature/db-connection` via Git Bash.  
2. Push it to the remote repository.

### 📸 Screenshots for Task 8
![Feature DB Branch](../Lab2/Screenshots/feature_db_branch.png)  
*Creating new feature branch.*

![Feature Commit](../Lab2/Screenshots/feature_commit.png)  
*Committing and pushing feature branch.*

---

## 🔀 Task 9 – Branch Switching and Merge  

1. Create & switch to a new branch.  
2. Modify `main.py`.  
3. Switch back to main and merge.  
4. Push all branches.

### 📸 Screenshots for Task 9
![Branch Create](../Lab2/Screenshots/branch_create.png)  
*New branch created.*

![Merge Branch](../Lab2/Screenshots/merge.png)  
*Branch merged back into main.*

![Push Branches](../Lab2/Screenshots/push_branches.png)  
*Pushing all branches to remote.*

---

## 🔃 Task 10 – Create Pull Request (PR)  

1. On GitHub, create PR from `feature/db-connection` to `master`.  
2. Review and merge via GUI.  
3. Delete the feature branch after merge.

### 📸 Screenshots for Task 10
![PR Creation](../Lab2/Screenshots/pr_creation.png)  
*Opening pull request on GitHub.*

![PR Details](../Lab2/Screenshots/pr_create_details.png)  
*Pull request details view.*

![PR Merge](../Lab2/Screenshots/pr_merge.png)  
*Merging the pull request.*

![PR Merge Confirm](../Lab2/Screenshots/pr_merge_confirm.png)  
*Merge confirmed on GitHub.*

![Branch Delete](../Lab2/Screenshots/branch_delete.png)  
*Feature branch deleted after merge.*

---

## 🧭 Task 11 – Professional Branching Strategy  

1. Create branches: `develop`, `staging`, `feature/*`, and `bugfix/*`.  
2. Demonstrate merges into `develop`, then `staging`, and finally `main`.  
3. Document with screenshots.

### 📸 Screenshots for Task 11
![Branch Strategy](../Lab2/Screenshots/branch_strategy.png)  
*Professional branching workflow.*

![Branch Merges](../Lab2/Screenshots/branch_merges.png)  
*Merging feature/bugfix branches into develop/staging.*

![Final Merge](../Lab2/Screenshots/final_merge.png)  
*Final merge into main (production).*

---

## 🤝 Bonus Task – Collaboration  

1. Create branch `collab`.  
2. Add a collaborator on GitHub.  
3. Both users pull, edit `notes.txt`, commit, and push.  
4. Merge `collab` into main.

### 📸 Screenshots for Bonus Task
![Collab Commit](../Lab2/Screenshots/collab_commit.png)  
*Collaborators committing to the collab branch.*

![Collab Merge](../Lab2/Screenshots/collab_merge.png)  
*Merging collab branch into main.*

---

## 🧹 Task 12 – Pull Request / Merge Request Review  

1. Create PR or MR and assign a reviewer.  
2. Reviewer approves or requests changes.  
3. Author updates and merges.

### 📸 Screenshots for Task 12
![PR Assigned Reviewer](../Lab2/Screenshots/pr_assigned_reviewer.png)  
*Assigning reviewer for PR.*

![PR Request Changes](../Lab2/Screenshots/pr_request_changes.png)  
*Reviewer requesting changes.*

![PR Approved](../Lab2/Screenshots/pr_approved.png)  
*PR approved after review.*

![PR Updated Commits](../Lab2/Screenshots/pr_updated_with_commits.png)  
*Author updated PR with new commits.*

---

## 🧯 Task 13 – Delete Remote Branch After Merge  

1. Delete remote branch after merge.  
2. Update local repository.

### 📸 Screenshots for Task 13
![Remote Branch Delete Command](../Lab2/Screenshots/remote_branch_delete_cmd.png)  
*Deleting remote branch using Git Bash.*

![Remote Branch Deleted](../Lab2/Screenshots/remote_branch_deleted.png)  
*Verification of deleted remote branch.*

![Local Branch Deleted](../Lab2/Screenshots/local_branch_deleted.png)  
*Local cleanup after remote deletion.*



