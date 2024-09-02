# PREPARATION GIT
This is a repository for teaching material of git basic for collaboration and contribution to the open-source
## Learning outcome :
* Understand how to start collaboration in the open-source repository
* Understand basic step-by-step collaboration in the open-source repository

## Check your requirements!
* Already installed git. Check this link [download git](https://git-scm.com/downloads)
* Already set username and email of git. Check this link [git configuration](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)

## What should you do ?
* Fork this repository, you will see on top of page
* Clone the repository to your device, you can use git bash `git clone <repo_url>`
* Create a new branch, then checkout to the new branch that has been created. Use `git checkout -b <branch_name>` or `git branch <branch_name>` then follow by `git switch <branch_name>`. 
* Start making a folder and some files in the repository. Example :
  
  ![image](https://github.com/srikresna/preparation-git/assets/28501206/59358a72-4994-4065-a1e6-100195b773a7)

  You can use windows file explorer directly to create a folder or use linux commands like `mkdir` and `echo`.

* Then, commit the file1 and file2 in the first commit, then commit file3 in the second commit. First of all, move the file into the staging area using `git add <file_name>`, after that you can commit the change using `git commit -m "commit message"`. (Best practice: use conventional commit message to improve readability)
* So in the end we will have 2 commits, 1 commit for file1 and file2, 1 commit for file3.
* Push the commit into your branch using `git push -u origin <branch_name>`.
* Check the repository in the github, then choose compare pull & request. If you encounter a compare and pull request button doesn't appear. Ask the mentor immediately.
* Fill the some details in the pull & request section then finish it!

## End of section
If you find another problem with your git, feel free to ask the mentor.

## Another resource to learn git individually
* [learn git with visualization](https://learngitbranching.js.org/)
* [learn git with youtube](https://youtube.com/playlist?list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&si=weyUH7Qqk8392-6y)
* [conventional commits message](https://www.conventionalcommits.org/en/v1.0.0/)

