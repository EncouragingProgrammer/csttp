# Assignment: Git, GitHub, and VS Code Workflow

## Objective
By the end of this assignment, students should be able to:
- Install and configure Git, GitHub, and VS Code.
- Set up a GitHub repository and push code to it.
- Create and manage branches in Git.
- Use GitHub Projects to create and complete a task.
- Submit a pull request for review and merge changes.

---

## Step 1: Install and Configure Git, GitHub, and VS Code

### Install the necessary tools
1. **Git:** Download and install Git from [git-scm.com](https://git-scm.com/downloads).
2. **GitHub:** Create an account at [GitHub](https://github.com) if you don’t already have one.
3. **VS Code:** Download and install [Visual Studio Code](https://code.visualstudio.com/).

### Verify Git installation
Open a terminal (Command Prompt, Git Bash, or Terminal - including VS Code Terminal) and run:

```
git --version
```

You should see the installed version of Git.

---

## Step 2: Configure Git with Your Credentials

Set up your username and email for Git:

```
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Verify the setup:

```
git config --list
```

📌 **Reference:** [Configuring Git](https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git)

---

## Step 3: Create a New Repository on GitHub
1. Go to [GitHub](https://github.com/) and log in. If you don't yet have an account, please create one.
2. Click on **New Repository** (or navigate to [Create Repository](https://github.com/new)).
3. Give the repository a name (e.g., `git-intro-assignment`).
4. Select **Public** (Alternatively, if you select **private** you will need to add me as your collaborator)
5. Check **Add a README file**.
6. Click **Create Repository**.

📌 **Reference:** [Creating a Repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)

---

## Step 4: Clone the Repository to Your Local Machine
In VS Code or Terminal, navigate to a directory where you want to clone the repo:

```
git clone https://github.com/your-username/your-repo-name.git
```

Move into the project folder:

```
cd your-repo-name
```

📌 **Reference:** [Cloning a Repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

---

## Step 5: Create a Hello World Program and Commit It

1. Open the repository in **VS Code**.
2. Create a new file (e.g., `hello.py` for Python or `hello.js` for JavaScript - choose 1).
3. Add the following code:

   **Python (`hello.py`):**
   ```
   print("Hello, World!")
   ```

   **JavaScript (`hello.js`):**
   ```
   console.log("Hello, World!");
   ```

4. Save the file.
5. Open a terminal in VS Code and run:

   ```
   git add .
   git commit -m "Added Hello World program"
   git push origin main
   ```

📌 **Reference:** [Committing Changes](https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository)

---

## Step 6: Create a GitHub Project and Task
1. Go to your repository on GitHub.
2. Click on **Projects** → **New Project**.
3. Select **Board** and name it **Git Learning**.
4. Click **+ Add Item**, name it **Complete Git Workflow**, and **assign it to yourself**.

📌 **Reference:** [GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects)

---

## Step 7: Create a New Branch and Make Changes
Using either the github UI, the VS Code UI, or your local VS CODE terminal, complete the following:
1. Create a new branch. Terminal example:

   ```
   git checkout -b feature-update
   ```

2. Open or Create `README.md` in the new branch, using VS Code, and add a new line:


3. Save and commit your changes:

```
git add README.md
git commit -m "Updated README with project description"
git push origin feature-update
```

📌 **Reference:** [Creating and Deleting Branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository)

---

## Step 8: Create a Pull Request and Assign Me as a Reviewer
1. Go to your repository on GitHub.
2. Click **Pull Requests** → **New Pull Request**.
3. Select `feature-update` as the source branch and `main` as the target.
4. Click **Create Pull Request**.
5. Assign **EncouragingProgrammer** (Ryan, your instructor) as the **Reviewer**.
6. Click **Create Pull Request**.

📌 **Reference:** [Creating a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

---

## Step 9: Merge the Pull Request
1. Wait for approval.
2. Click **Merge Pull Request** → **Confirm Merge**.
3. Delete the `feature-update` branch after merging.

📌 **Reference:** [Merging a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)

---

## Step 10: Update and Close the GitHub Project Task
1. Go back to **GitHub Projects**.
2. Drag **Complete Git Workflow** to **Done**.
3. Add a comment summarizing what you learned.

📌 **Reference:** [Managing Project Boards](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-your-project/adding-your-project-to-a-repository)

---

## Submission Instructions
Once you've completed all steps:
- Check with your instructor to see if your pull request has been received, reviewed, and merged.
- Check if there is any of your fellow students that are struggling and politely ask if they would like any assistance in support or completing this "Assignment".

---

## Additional Resources
- [What is git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
- [Github - Hello World](https://docs.github.com/en/get-started/start-your-journey/hello-world)
- [About repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)
- [About Branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)
- [Pushing commits to a remote repository](https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository)
- [Merging a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)
- [About merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)

---
