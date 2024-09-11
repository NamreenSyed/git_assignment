# Git Assignment - NamreenSyed

a. What is an _issue_?
In Git, issues are a way of tracking bugs, new features, and other tasks related with a repo.

b. What is a _pull request_?
A pull request is a way of submiting a unit of work for review by your peers on a shared project, so that mistakes can be caught and changes can be made before commiting those changes to the main branch. It is also a way of documenting changes as you go in a PR description.

c. Describe the steps to open a _pull request_?
First, you pull the latest changes from the main branch, then you branch off into a feature branch (e.g. new-feature). After making changes locally to new-feature, you commit and push those changes to the origin. Then once you are ready to commit those changes to main, you open a Pull Request and (upon review) you merge in the changes. The PR should have a detailed description.

d. Describe the steps to add a collaborator to a repository (share write permissions)
In the project settings, you can add a collaborator by going to "Settings", "Collaborators", then "Add People". You may need to enter your password. Then search for the user by username or email, then add them to the project. To assign them write permissions, they need the "write" role assigned to them.

e. What is the difference between `git` and `GitHub`?
`git` is the underlying software for managing distributed versions of files across teams. GitHub is a service that hosts projects in a centralized way and allows developers to manage their software using git.

f. What does `git diff` do?
Git diff is a way of seeing the differences between the file on origin and the file stored locally. Any changes you make to the file will appear in green or red depending on whether you added or removed or changed content.
