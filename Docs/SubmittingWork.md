# Submitting work
## Build a branch
Branches are breakaways from the main body (trunk) that allow you to do work in a protected area that can be deleted in case of critical error, or if many projects are on the go, switched between. 

Branches hold commits (saves) and are later merged into the main body (trunk).

### Process
- Right clicking on the repo folder you cloned will bring up a list of git actions. 
- In Tortoise you will see `Switch/Checkout`

<img src="https://github.com/user-attachments/assets/a56ffadc-dae5-42af-9b7b-4d3dc8d729fa" width="500px"> 

- Select `Create New Branch` and give it a meaningful name based on what work you are doing
- On creation you will be switched to that branch,
- Alternatively in the *full menu* you can select `Create branch`
  
<img src="https://github.com/user-attachments/assets/245e1d52-f913-4673-a1c2-d183f7d5de14" width="500px"> 

> Note: In windows 11 you will have to click `Show more actions`, to get the old style windows right click menu to get he full menu of git actions

## Commit to the branch
Commits are saved changes with a bit of text noting what the save it about.

When you are ready to save your changes. 
- Go to TortoiseGit and click `Commit`
- Ensure you are committing to your branch
- Edited files will show up automatically
- If you have new files you will need to click `show unversioned files` and select them
- Click `ok`

You can commit as many times as you like. Good standards are to commit once per feature or sub feature and only with the files that are touched for that change. As all files in the commit are marked with the text you use on github and small commits are much easier to review. “Fixed file spelling” on one file is more meaningful than “made various fixes” over a pile of unreated files.

## Push the branch to github
Once you are satisfied with your work and it has all been committed, or at any time you want to put your saved changes into the cloud for safe keeping, you `Push`.

## Make a pull request
After pushing, visiting github will prompt you to make a [pull request](https://github.com/Citizen-Group/SteelRain/pulls). A `Pull Request` is just a formal way of submitting files to the repo. We use it to ensure you get credit and to automate some of the digital paperwork.

Create either manually or via the prompt. A pull request for your branch and write something meaningful as to what was done. For assets this can be fairly simple, for code, it should reflect the work done and files touched.

## Get the pull request approved
The pull request will be shortly after approved. Nothing else you need to do, unless there is a problem found. You may be asked to make changes if something is found in the review.

## Switch your branch to main
You can switch your branch back to main at any time, or wait for the approval.

## Pull down to make sure you have the latest
Once the pull request is approved, use `pull` to grab the latest and update your main with all the changes.

## Repeat when ready for next task
After grabbing your next project, create a branch and the cycle starts anew.



