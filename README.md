# Godhuli-Vyas-Learning-Git

1. Installation of Git, GitHub, and VS Code:
To get started with version control and code collaboration, it's essential to have Git, GitHub, and a code editor like VS Code installed on your system. Here's how you can install them:

Git Installation:
1. Visit the [Git website](https://git-scm.com/).
2. Download the installer for your operating system (Windows, macOS, or Linux).
3. Run the installer and follow the on-screen instructions.
4. Once installed, open a terminal or command prompt and verify the installation by typing `git --version`.

GitHub:
1. Navigate to [GitHub](https://github.com/) in your web browser.
2. Sign up for an account if you don't have one already.
3. GitHub offers various plans, including a free plan for individual developers.
4. After creating an account, you're ready to start using GitHub for hosting your repositories and collaborating with others.

VS Code Installation:
1. Visit the [Visual Studio Code website](https://code.visualstudio.com/).
2. Download the installer for your operating system.
3. Run the installer and follow the on-screen instructions.
4. Once installed, you'll have access to a powerful and customizable code editor that integrates seamlessly with Git and GitHub.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/50e50c57-564f-4410-9f0b-ce27d1c80557)



2. Setting Up Git
After installing Git, you need to configure it with your identity and email address. This information is used to identify your commits. Here's how you can set it up:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Replace `"Your Name"` with your actual name and `"your.email@example.com"` with your email address. This information will be associated with your commits.

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/6a96c12d-37f4-4a65-9cfd-74b6ee8f731b)



3. Cloning a Repository from GitHub
Cloning a repository allows you to create a local copy of a remote repository on your machine. Let's clone the "Godhuli-Vyas-Learning-Git" repository, which contains a website named "Dice Duel."

git clone https://github.com/Godhuli-Vyas-Learning-Git/Dice-Duel.git


This command will create a directory named "Dice-Duel" in your current location and download all the files from the remote repository.
 
![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/9851709c-b22f-4c6a-9d5b-bc0251903de1)



4. Modified File Not Added or Committed
After making changes to files in your repository, you need to stage them for commit using `git add` and then commit them to the repository using `git commit`. If you make changes but forget to add or commit them, Git will show these files as modified but not staged for commit.

git status

This command will show you the status of your working directory, including any modified files. To stage changes for commit, use `git add <file>` or `git add .` to add all modified files.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/834dab95-f1df-48f6-bb69-017f577215d8)




5. Changes Added
If you've made changes but forgot to add them using `git add`, you won't be able to commit them. To add changes to the staging area, use:


git add .


This command stages all changes in your working directory for the next commit. After staging changes, you can commit them using `git commit`.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/039826c2-59b9-4087-86c0-4a249c724be1)




6. Checking the Status of the Current Code
To check the status of your repository and see which files have been modified, added, or deleted, you can use the `git status` command.

git status

This command will display information about the current state of your repository, including any changes that have been made since the last commit.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/62d6ec7f-62a0-4804-975f-4f7314e82a5e)



7. Pushing Changed Code
Once you've committed your changes locally, you can push them to a remote repository on GitHub using the `git push` command.


git push origin main


This command will push the committed changes from your local `main` branch to the remote repository on GitHub.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/7dc393a2-d5fb-4698-9dec-381e24a2fb97)




8. Feature Branch Addition
Creating a feature branch allows you to work on new features or fixes without affecting the main codebase. Here's how you can create a new feature branch:


git checkout -b feature-branch


This command creates a new branch named `feature-branch` and switches to it. You can now work on your new feature without affecting the main branch.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/627c52ef-5b79-46c9-8703-5a207f24eddf)



9. Collaborator Branch Addition
When collaborating with others, conflicts may arise when multiple people make changes to the same file. Here's how you can create a new branch and make conflicting changes:


git checkout -b collaborator-branch


This command creates a new branch named `collaborator-branch`, where you can make conflicting changes to the same file as another collaborator.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/3e5a36a1-792a-441b-bacb-32eef96ab7d6)





10. Undoing Features
If you need to undo changes made by merging a feature branch with the main branch, you can use the `git reset` command.


git reset HEAD~1


This command resets the HEAD pointer to the previous commit, effectively undoing the merge. You can also use the commit hash to reset to a specific commit.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/ca746870-770c-41ab-a8dd-c91e559468b8)




11. New Feature Added in Feature Branch
After creating a feature branch, developers gain a dedicated workspace to innovate and refine their contributions without directly altering the main codebase. This isolated environment encourages experimentation and iteration, fostering a more organized and collaborative development process. Within this context, developers can enhance UI elements, introduce new features, optimize performance, address bugs and errors, integrate third-party APIs, and ensure accessibility and compliance. By leveraging the feature branch, developers can prototype, refine, and test their enhancements thoroughly before integrating them into the main project, ensuring a smoother development workflow and delivering high-quality features to users.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/69224ffe-7b72-47e1-94ef-430a5ef43857)





12. New Features Pushed to Feature Branch on GitHub
After making changes in your feature branch, you can use the `git push` command to push these changes to the remote repository on GitHub. This command ensures that the modifications made locally are reflected in the remote repository, allowing for seamless collaboration and version control. By pushing changes to GitHub, developers can share their progress with team members and contribute to the project's development in a collaborative manner.

git push origin feature-branch


This command pushes the changes from your local feature branch to the remote repository on GitHub.
 
![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/448ab65f-479d-4b80-9e1a-9f39b4110480)



13. Checking Differences Between Branches
To compare the differences between two branches, the `git diff` command is invaluable. By utilizing this command, developers can quickly identify variations in code between different branches, aiding in code review, debugging, and ensuring consistency across the project. Whether it's comparing changes in feature branches or assessing modifications between the main and development branches, `git diff` provides a comprehensive overview of the code disparities, facilitating efficient collaboration and decision-making in the development process.
git diff main feature-branch

This command will show you the differences between the `main` and `feature-branch` branches.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/d5bb8d5b-dab5-466a-ad6c-e575a1691543)





14. Merged Feature with Main
To integrate a feature branch with the main branch, developers can initiate a pull request on GitHub. This process facilitates the review and discussion of proposed changes before merging them into the main codebase. By creating a pull request, developers invite feedback from team members, ensuring the integrity and quality of the code changes. Once approved, the changes can be merged seamlessly, maintaining project continuity and fostering collaboration among contributors.
 
 ![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/a69a9191-0ad7-4268-85c0-6cc62ac221b7)
![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/0a2b091b-002c-4cbd-b800-c685092d787a)



15. Reset Hard
If there's a need to revert changes made in a feature branch, the `git reset --hard` command followed by the commit hash can effectively accomplish this task. By specifying the commit hash, developers can reset the branch to a specific point in its commit history, discarding any subsequent changes. This command provides a robust mechanism for undoing modifications and restoring the feature branch to a previous state, ensuring code integrity and facilitating efficient development workflows.

git reset --hard <commit-hash>

This command resets your working directory to the specified commit, discarding any changes made after that commit.
 

![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/2ee69503-47a4-4b9d-9dc9-c083a8b06b39)



16. Creating a Pull Request from Collaborator Branch
After making modifications in the collaborator branch, developers can initiate a pull request on GitHub to propose their changes for review and eventual integration into the main branch. By creating a pull request, collaborators invite feedback, scrutiny, and discussion from team members or project maintainers. This process facilitates transparent communication and ensures that proposed changes align with project objectives and coding standards. Once the pull request undergoes review and approval, the changes can be merged into the main branch, promoting collaboration and maintaining code quality throughout the development lifecycle.
 
![image](https://github.com/GodhuliVyas/Godhuli-Vyas-Learning-Git/assets/126496013/ffc2bc42-8f51-4b29-8e17-e61831254708)


