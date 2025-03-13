[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18474967&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
Version control is about tracking changes made to a code, creating branches, collaborating simultaneously on a single project without conflict, merging branches, and keeping the history of changes for easy rollback in case of system failure.<br>

why GitHub is a popular tool for managing versions of code.<br>
Github enables software engineers to host GIT-based repositories on the cloud for easy access and collaboration.
Version control maintains the integrity of the project by enabling roll back from modification in case of errors.

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?
1.	Log in to your Github account.
2.	Click the “+” on the right menu.
3.	Click on the “new repository” link on the drop-down menu.
4.	Fill in the required fields. Example: the repository name.
5.	Choose a license and click on Create repository.<br>

Important decisions<br>
1.	Select visibility. “Public - Anyone on the internet can see this repository. You choose who can commit.” or “private - You choose who can see and commit to this repository.” 
2.	When selecting visibility, make sure there is no sensitive data.
3.	.gitignore – choosing files not to track.

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
README file contains information about the project. It offers comprehensive documentation of the project to enable easy collaboration. <br>

A well-written README should include: <br>
1.	Project title
2.	Project description
3.	Procedures and instructions to use the project
4.	If it is a group work, include team members' details like name and github profiles.
5.	The problem the project is trying to solve.
6.	Languages, framework, and database.<br>

How does it contribute to effective collaboration?<br>
README file provides information about the project needed for collaborators to start their collaboration. This comprehensive information enables collaborators to keep on referring to it whenever they encounter an error.

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?
Comparison
1.	A public repository is open and can be seen by anyone on the internet, while a private repository is only visible to invited collaborators.
2.	Anyone can contribute by pulling requests from the public repository, while contributions in the private repository are only made by the invited collaborators.
3.	A public repository is free to create, while a public repository is obtained through a paid plan.<br>

Similarities<br>
1.	Both repositories use Git version control.
2.	Both allow the addition of collaborators with different permission levels.
3.	Both allow two-way authentication.<br>

Public Repositories<br>
Advantages<br>
1.	Anyone can collaborate, contribute to ideas, and discover and report bugs.
2.	It allows contributors to gain recognition for their contributions.
3.	It allows direct feedback from users. This feedback can be used to improve the project.
4.	It contains detailed documentation about the project.<br>

Disadvantages<br>
1.	A public repository exposes the codebase to everyone, posing risks of vulnerability exploitation.
2.	It exposes confidential or sensitive information to the public.
3.	It is hard to coordinate when more collaborators join.
4.	Team reputation can be ruined when the repository is not properly maintained.<br>

Private Repositories<br>
Advantages<br>
1.	It is only accessed by invitation; therefore, it protects the codebase and sensitive information.
2.	It is easy to manage and coordinate a team of collaborators.
3.	Hides innovations until it is ready for the market.
4.	Easy decision-making due to fewer stakeholders.<br>

Disadvantages<br>
1.	Poor documentation practices.
2.	Less pressure from the public to maintain high-quality code.
3.	Projects lack scrutiny from the broader community.

## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
Steps involved in making first commit to a GitHub repository<br>
1.	Install Git
2.	Create a repository in Github
3.	Initialize Git~git init
4.	Configure Git;
o	~git config - -global user.name “your name”
o	~git config - -global user.email “your email”
5.	Create a file on the repository 
6.	Add the file.  ~git add “filename” 
7.	Commit changes. ~git commit -am “my first commit”
8.	Push to GitHub using the git push command.<br>

Commits<br>
Commits are changes recorded to a repository<br>

How do commits help in tracking changes and managing different versions of your project?<br>
Commits help to track changes by creating a history of a project in a chronological order.
It also saves the author, date of commit, and commit description.
Each commit has a unique identity (SHA-1 hash). This identity ensures its integrity and uniqueness.

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
Branching creates a stem from the original codebase to allow development time to work on different features without interference. Collaborators can pull changes from their branches and merge them into the main branch. 
Branching enables collaborators to work on different features which are reviewed before merging to the project. This is important for code review and makes it easier to track and revert changes.<br>

The process of creating, using, and merging branches in a typical workflow<br>
1.	Create an isolated branch for a new feature or bug fix if it does not exist and switch to it using Git checkout -b
2.	Verify that the branch exists using the Git branch command.
3.	Edit, stage, and commit changes on the branch.
4.	Push the branch to Github when working with other collaborators.
5.	Create a pull request in Github and add a description explaining the changes.
6.	Request reviews from members.
7.	Modify the  code according to feedback and push the updates.
8.	Merge the pull request to the main branch.

## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
A pull request is a request to merge changes from one branch into another branch in a Git repository. A pull request allows the team to review and discuss the proposed changes before they are merged into the main branch.<br>
1.	Code Review: Pull request facilitates code review by allowing team members to review code, propose changes, and identify bugs before merging the code to the main codebase.
2.	Collaboration: Pull requests enable developers to come together and discuss and agree on changes and give feedback.<br>

How do Pull Requests Work?<br>
1.	Developers working on separate features create a new branch.
2.	Changes are made and committed to the branch.
3.	The branch is pushed to the remote host like GitHub.
4.	A pull request is created to merge the feature branches into the target branch.
5.	The team discusses the changes and agrees, changes are made, and the pull request is updated.
6.	The pull request is merged with the targeted branch.

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
Forking is creating a copy of a repository from another user’s repositories to your account. This copies all the data, including files, commit history, and branches. Cloning is copying a repository from your remote host, like GitHub, to your local computer to work on it offline. Forking is used when you want to make changes without altering an existing repository.
## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
Issues help in tracking bug reports, feedback, ideas, and new features.
Project boards are useful in managing projects. It helps to organize and prioritize work using Scrum.
When bugs are discovered, issues are created with clear descriptions on how to reproduce and what is expected. They are categorized by type and fix priority and assigned to members. The project board is used to track bugs, whether it is a new bug, confirmed, in progress, fixed, or resolved. Big features are broken down into small tasks. The project board helps to manage bugs and features by organizing projects in sprints.<br>

how these tools can enhance collaborative efforts<br>
1.	The current status of tasks and priorities are seen by the members.
2.	Information is centred, hence easily accessible.
3.	The ability to break the task into smaller tasks facilitates collaboration.
4.	Visual representation of workloads on scrum enhances planning.

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
Challenges
1.	Merging conflicts can occur when multiple developers modify the same code. Github fails to automatically determine which changes to keep.
2.	Failure to pull latest branches lead to outdated branches. Merging these outdated branches can introduce unexpected issues. 
3.	Data loss due to force pushing, which overwrites remote commits or deleting branch before merging.
4.	GitHub has limited storage, large files and multiple commits can lower performance.
5.	Pull requests waiting for Code review causes slow development.<br>

best practices<br>
1.	Use Git workflows and separate branching for bugs, features, and release.
2.	Use Git rebase for more organized project history and regularly pull changes from the main branch.
3.	Writing descriptive, clear and concise commits.
4.	Use Git large file storage extension for large files and delete branches after merging to create space.
5.	Code owners should automatically assign reviewers.<br>

common pitfalls new users<br>
1.	Difficulty in understanding Git basics and the project.
2.	Committing large and unnecessary files.
3.	Making changes directly to the main branch causing merge conflicts.
4.	Merging conflicts makes them to force push therefore overwriting important changes.<br>

Strategies to overcome<br>
1.	Proper documentation for onboarding new users. New user should learn Git fundamentals and practice with a local repository before collaboration.
2.	Use Git LFS for large file and .gitignore for unnecessary files.
3.	Create a feature branch and Git push for review.
4.	Communicate with collaborators to co-ordinate changes and pull latest changes.
