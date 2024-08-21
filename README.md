# Objective

- [ ] Create a GitHub account and login via CLI or the Desktop application
- [ ] Understand how to create a new repository, then commit and push files to it
- [ ] Practice accepting and completing an assignment with GitHub Classroom

# How to Get Started

1. Complete **Step 1: Creating a GitHub Account**
2. For **Step 2**, choose either **Survival Mode** to set up GitHub in the browser and the Desktop client or **Hardcore** mode to set up GitHub CLI
3. Complete **Step 3: GitHub Classroom and Deliverables** and mark this assignment as complete on Google Classroom
4. Review the **Rubric** at the bottom of the page

# Vocabulary

| Vocabulary                                | Definition                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Clone**                                 | When you clone a **remote repository**, you create a local copy of it on your own machine.                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Commit**                                | Committing staged files saves your changes in **Git** locally. Generally you commit every time you make functional progress on a project. You can look through your previous commits and revert your files back to those previous versions as well. This is why writing descriptive commit messages is so helpful!                                                                                                                                                                                                                                 |
| **Git**                                   | A **version control** software to track versions of files that is often used by programmers who are collaboratively creating software. We will use Git to track and manage **local repositories**.                                                                                                                                                                                                                                                                                                                                                 |
| **GitHub**                                | A website that hosts **remote repositories**. GitHub interfaces well with **Git** and allows users to access and update repositories anywhere making it the default for creating code collaboratively and publicly hosting open-source projects.                                                                                                                                                                                                                                                                                                   |
| **Push**                                  | When you push to a **repository**, you send all of your **committed** changes to that repository. In our case, this will send all of your local commits to your **remote repository** on GitHub.                                                                                                                                                                                                                                                                                                                                                   |
| **Repository** often abbreviated **repo** | A data structure which holds all the files and directory structure for your project. You can think of a repository as one large. A **local repository** is stored on your computer. Think of this like opening your file explorer and creating a folder. Your files are only stored on one device. A **remote repository** is stored on the cloud by a third-party service, in this case **GitHub**. Think of this like creating a folder in Google Drive. You can share viewing/editing rights with others and access your files from any device. |
| **Version Control**                       | A software engineering practice to manage versions of files.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |


# Step 1: Creating a GitHub Account

1. Create a [GitHub Account](https://github.com/join) using your personal email address. GitHub is a platform that programmers often use as a digital portfolio. That being said if you want to pursue computer science, employers will be looking for you on this platform. You want all of your publicly available information to be professional.
	1. It doesn't have to be right now, but it is a good idea to update your profile with your current information and a professional photo.
	2. Also, if you create a repository called `your_username` with a file `README.md` it will be automatically displayed on your profile. This is a great way to introduce yourself and highlight your resume. I recommend looking at (and stealing from) [these examples](https://github.com/abhisheknaiidu/awesome-github-profile-readme?tab=readme-ov-file#gifs-) or using [these templates](https://github.com/durgeshsamariya/awesome-github-profile-readme-templates) .
	3. You can also create a repository called `your_username.github.io`. This will automatically create and host a website for you accessible at `your_username.github.io` if you would rather use HTML to build your portfolio. 


---
![image001-1](https://github.com/user-attachments/assets/30825f92-e652-49c8-bbef-57e4b4d8302d)

# Step 2 (Survival Mode)

## Git and GitHub Browser Setup

1. There is not much to set up in the browser, except to log in to [GitHub](https://github.com/). Then follow the steps below to create a repository. You can try creating your first repository, then come back to the GitHub Desktop setup below.

## Creating your first repository

1. Now that you are logged into GitHub, click on your profile photo in the top right corner and navigate to your profile. 
2. Then, move from the 'Overview' tab to the 'Repositories' tab.
3. Click the green 'New' button in the upper right.
4. Give it a name `Hello_World` and make it private. Click the checkbox to add a `README`, but you can skip the `.gitignore` and license options.
5. You should now see your `README.md` file listed in your repository and it displayed below with the name of your repository. Click on the pencil icon on the top right of the `README` or click on `README.md` in the list to open it and click the pencil in the upper right.
6. Make a change by typing in the box. You can toggle between the 'Edit' tab to see the raw Markdown with all of the special characters and the 'Preview' view in the top left to see how it will be displayed.
7. Once you are done editing, click the green 'Commit changes...' button in the top right. 
8. It will then list the files you changed, in this case `README.md`, and ask you to include a message. The default message is fine, but the more descriptive you are the easier it will be to go back through and revert to a previous state if you want to undo your changes. Then hit the green 'Commit changes' button. This both **commits** and **pushes** your changes. 
	1. As you will notice, the contents of your `README.md` file automatically display on your repository page, but other files do not. This is why we have been learning Markdown! Writing a Markdown file called `README` to explain your project and how to use it is standard practice in software development, so GitHub will automatically display it for you. 
9. To upload a file from your computer, click the 'Add file' button then 'Upload files' under the homepage or 'Code' tab of your repository. Then, either drag in a new file or use the browse button to find it. Once you are done, add a commit message and complete your upload with 'Commit changes'.

## Git and GitHub Desktop Setup

1. To set up GitHub Desktop, find and open the program on your computer.
2. When you open the program, if it doesn't automatically prompt you to login to GitHub, click the 'File' tab in the top left, then 'Options'. Under 'Accounts', click on the button that says 'Sign into GitHub.com' then 'Continue with browser'. 
3. Once it opens in the browser, login(if you haven't already) and click 'Continue' to authorize the GitHub Desktop App.
4. Once you have logged in, it should show you a list of your repositories on the left and give you some quick access buttons on the left. 
5. Create a new empty directory on your computer for your repository. Then in GitHub Desktop, select your `Hello_World` repository from the list on the left and hit 'Clone `your_username/Hello_World`' at the bottom.
6. Either using the auto-filled URL or selecting the repository from the GitHub tab, hit the button that says 'Choose' and navigate to your empty directory we made in the last step. Then hit the blue 'Clone' button.
7. Now if you use File Explorer to navigate to that directory, you should see the `README.md` file you made.
8. Edit and save the `README.md`
9. Your GitHub Desktop application should show that you changed that file. Keeping your `README` checked in the list, add a commit message in the text box next to your profile photo in the bottom right. Then hit the blue 'Commit to master' button. 
	1. **You must** include a message with your commit. 
	2. Every file in your directory that you checked on the left has now been committed. When you push to GitHub, all of the commits you made are applied to your local repository. 
11. Now your GitHub Desktop application should update and say 'No local changes' at the top. If you hit the blue 'Push origin' button, your commits will be pushed to GitHub. 
12. Look back at your repository from the browser. You should see your changes reflected.
13. To clone a different repository, hit 'File' then 'Clone repository' then repeat the steps above. 
# OR

![image009-1](https://github.com/user-attachments/assets/d65435eb-9cc1-4209-913d-564874ca4733)
# Step 2 (Hardcore Mode)

## Git and GitHub CLI Setup

1. Login to Git from the terminal with the two commands:
	1. `git config --global user.name "your_username"` . Use your actual GitHub username here; don't literally type `"your_username"`...
	2. `git config --global user.email "your_email_address@example.com"`. Use your email address that you used to make a GitHub account.
3. [Install GitHub's command line interface](https://github.com/cli/cli/blob/trunk/docs/install_linux.md) **GitHub CLI** or `gh` for Ubuntu by following the instructions. *You will administrator privileges for this step.*
4. Use `gh auth login` and follow the prompts. Select `HTTPS` as your preferred protocol for Git operations and answer `yes` if it asks you if you want to authenticate Git with your GitHub credentials.
	1. If this doesn't work, you may need to use SSH keys. Here are two links to help you set it up: [StackOverflow](https://stackoverflow.com/questions/34731832/log-in-to-github-from-the-command-line-with-multiple-accounts)  and [GitHub Docs](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

Now if you use a command like `gh auth status` you should get this response:

```shell
github.com
  ✓ Logged in to github.com account [your_username)here] (keyring)
  - Active account: true
  - Git operations protocol: https
  - Token: gho_************************************
  - Token scopes: 'gist', 'read:org', 'repo', 'workflow'
```

## Creating your first repository

1. Open GitHub in your browser, and create a new private repository called `Hello_World`. Skip adding a `README`, a `.gitignore`, or a license.
2. Create a new directory called `Hello_World` on your computer.
3. `cd` into the directory and create a file called `README.md`.
4. Initialize a local Git repository with `git init`.  If you list all files in the directory, you should see a folder called `.git`. 
5. Connect your remote GitHub repository with your local Git repository with `git remote add origin your_link_here`. Don't literally type `your_link_here`; Get the link by copying it from the blue **Quick setup** box. 
	1. If there was already something in your repository and you just wanted to clone it to a specific location, you would click on the green **Code** button and go over to GitHub CLI and copy the command `gh repo clone your_username/repo`.
6. Switch your main branch with `git branch -M main`. 
	1. If you wanted to use multiple branches, you can use `git branch branch_name` to switch between them, but for our purposes we are going to stick with the `main` branch.

### Stage, Commit, and Push Files

*Every time you update files the in your repository and you want to push those changes to GitHub, you will repeat these steps.*

7. Stage your `README.md` file to include it in your next commit with either of the following:
	1. `git add README.md` - stages `README.md` in your local repository.
	2. `git add .` - stages *all* files  in your current directory in your local repository. As you get in the habit of using Git, you will likely want to use this to stage multiple files at once.

Now if you use `git status` , you should see that `README.md` is ready to be committed:

```shell
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
```

8. Commit your staged files with `git commit -m "commit message"`. **You must** include a message with your commit. Your changes will not be committed without a message, so to avoid problems **always** include `-m` and a message.

Now if you check `git status`, you should see that your changes have been committed and there is nothing staged left:

```shell
On branch main
nothing to commit, working tree clean
```

You can commit as many times as you want before uploading your changes with push.

9. Once you have committed all of your changes, push them to GitHub with `git push -u origin main`. 
	1. This pushes your commits to the branch `main`.

Your `README.md` file should appear in the remote repository on GitHub. As you will notice, the contents of your `README.md` file automatically display on your repository page, but other files do not. This is why we have been learning Markdown! Writing a Markdown file called `README` to explain your project and how to use it is standard practice in software development, so GitHub will automatically display it for you. 

10. Update the contents of `README.md` on your local machine and repeat steps 7, 8, and 9. You should see your changes reflected in your remote repository.

---

# Step 3: GitHub Classroom and Deliverables

When you accept an assignment, GitHub Classroom automatically creates a new repository for you, using my template. You are not the owner of this repository, so it won't show up on your personal GitHub profile. However, you will be able to access it by searching [EPIC-Campus-LPS repositories](https://github.com/orgs/EPIC-Campus-LPS/repositories). All of your repositories will have your username in the title, which should make it easy to find if you lose the link. 

For all the labs we will use GitHub for, I will provide you with a link to accept the assignment and create your repository via Google Classroom. Each of these repositories will have a copy of the instructions and any additional starter code or materials you need. You will submit your work by **#1** uploading your work to your repository and **#2** marking the assignment 'Complete' on Google Classroom. 

If I update the assignment *after you have created your repository*, you should see the a message like 'This branch is 1 commits behind `really_long_repository_name`' appear at the top of the main page of your repository on GitHub. To sync my updates to your repository, hit the 'Sync Fork' button.  

When you are working on a project, you are encouraged to back up your work by uploading it to GitHub at least once every class.

1. To practice this, accept [this assignment if you are in the EVEN AM Class](https://classroom.github.com/a/OjVGkCC9) and [this assignment if you are in the EVEN PM class](https://classroom.github.com/a/x9i-W56Z). Update the `README.md` file to check the box. Then mark as complete on Google Classroom

---

# Rubric

*Course Content*

- 3 points - All required items are present. 
	- Assignment was submitted on Google Classroom and `README` was updated on GitHub Classroom Assignment.
- 1.5 points - Did not attempt or student should reattempt. 

*Workforce Readiness*

- 2 points - Exemplified  WFR standards
	- Assignment is complete as described.
- 1 points - Developing WFR standards
	- Did not attempt or student should reattempt. 




---

# Optional: Creative Mode 

1. Help me update this tutorial by adding photos, rewording confusing text, adding troubleshooting sections, etc.
2. Create a poster to display relevant GitHub CLI commands. We have access to a poster printer so I can actually hang it up in our classroom.

