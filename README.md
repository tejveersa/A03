# A03
Web Development Class

GITHUB: Github is an open source version control system created by Linus Torvalds, the creator of Linux. This version control system allows for users to commit edits, clone duplicates, branch off to create iterative changes, merge multiple interations together, and more on repositories (a collection of documents or sourcecode). 


GIT: You can also install GIT on your cli as a remote to push changes, pull repos, and fetch repos.


REPOSITORY: Usually there is a single repository per project. Each repository contains files, folders, and a README page (a file that provides an overview/description of the project). 
Create a REPOSITORY by:
1. Clicking the "+" in the top right of the screen.
2. Name your repo.
3. Write a short description.
4. Then initialize the repo with a README page.
5. Lastly, press the green "Create repository" button.


BRANCH: Branching is a unique feature that allows you to create an object-oriented alias of the original repo (called the MASTER). This is useful to test changes before committing them to the original MASTER repo.
Create a BRANCH by:
1. Going to your repository.
2. Clicking the branch dropdown menu that says "branch: Master"
3. Type the branch name.
4. Click the blue "Create branch" button or hit “Enter” on the keyboard.


CLONE: When you're working with a repository on GitHub, you might want to have it on your local machine to make it easier to work with.
CLONE repo by:
1. Going to the main page of the repository.
2. Click Clone or download.
3. Enter location of the download and complete.


COMMIT: On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done & why.
COMMIT change by:
1. Going to file you want to edit.
2. Press the "pencil button" in the upper right.
3. Make changes in the editor.
4. Write a description of your change addition.
5. Press the "Commit changes" button.


PUSH: Make changes via cli and push the commit or whole repo to Github.
Make PUSH using Git CLI:
1. Your changes are now in the HEAD of your local working copy. To send those changes to your remote repository, execute
"git push origin master"
2. Change master to whatever branch you want to push your changes to.


PULL: When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.
Make PULL Request by:
1. Clicking the  Pull Request tab, then from the Pull Request page, click the green New pull request button.
2. In the Example Comparisons box, select the branch you made, readme-edits, to compare with master (the original).
3. Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit.
4. When you’re satisfied that these are the changes you want to submit, click the big green Create Pull Request button.
5. Give your pull request a title and write a brief description of your changes.
6. Click Create pull request button.


MERGE: Bring your changes together
How to MERGE:
1. Click the green Merge pull request button to merge the changes into master.
2. Click Confirm merge.
3. Go ahead and delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.


Merge Conflict: Occurs when there are competing line changes when you make different changes to the same line of the same file on different branches in your Git repository.
Resolving Merge Conflict by:
1. Under your repository name, click  Pull requests.
2. In the "Pull Requests" list, click the pull request with a merge conflict that you'd like to resolve.
3. Near the bottom of your pull request, click Resolve conflicts.
4. Decide if you want to keep only your branch's changes, keep only the other branch's changes, or make a brand new change, which may incorporate changes from both branches.
5. If you have more than one merge conflict in your file, scroll down to the next set of conflict markers and repeat steps four and five to resolve your merge conflict.
6. Once you've resolved all the conflicts in the file, click Mark as resolved.
7. If you have more than one file with a conflict, select the next file you want to edit on the left side of the page under "conflicting files" and repeat steps four through seven until you've resolved all of your pull request's merge conflicts.
8. Once you've resolved all your merge conflicts, click Commit merge. This merges the entire base branch into your head branch.
9. To merge your pull request, click Merge pull request. For more information about other pull request merge options, see "Merging a pull request."


FETCH: Retrieve new work done by other people. Fetching from a repository grabs all the new remote-tracking branches and tags without merging those changes into your own branches.
Using Git Cli:
1. If you already have a local repositorywith a remote URLset up for the desired project, you can grab all the new information by usinggit fetch *remotename* in the terminal
2. Use command: "git fetch remotename"


REMOTE: 
Establish REMOTE using Git CLI:
1. If you have not cloned an existing repository and want to connect your repository to a remote server, you need to add it with
"git remote add origin <server>"
2. Now you are able to push your changes to the selected remote server


RESOURCES:
https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository
https://guides.github.com/activities/hello-world/
https://rogerdudler.github.io/git-guide/
https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-on-github

