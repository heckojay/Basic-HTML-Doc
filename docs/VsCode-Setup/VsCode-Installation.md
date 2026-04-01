## Overview

Before you can write HTML, you need a place to write it. This task walks you through installing **Visual Studio Code (VS Code)** — a free code editor — and connecting it to **GitHub**, a platform that stores and backs up your code online.

---

## Download and Install VS Code

VS Code is the editor you will use to write all of your HTML code.

### Steps

1. Open your web browser and enter/click the following link: [https://code.visualstudio.com](https://code.visualstudio.com).
   ![Brower](Images/step1.png)

2. Click the large **Download** button. The website automatically detects your operating system and suggests the correct version, in our case it is Windows operating system.
   ![VSCode page](Images/step2.png)

3. Once the file downloads, open the `.exe` installer file from your Downloads folder.
   ![Brower](Images/step3.png)

4. Follow the installer steps:
   1. Accept the licence agreement and click **Next**.
   2. Leave the install location as default and click **Next**.
   3. On the _Select Additional Tasks_ screen, check the box labelled **Add to PATH** (recommended).
   4. Click **Next**, then **Install**.
   5. Click **Finish** to launch VS Code.

   > ⚠️ **Caution**
   > Do not uncheck "Add to PATH." This option allows you to use VS Code from the terminal later.

VS Code will open. You will see a Welcome tab with quick-start options.

![VS Code application open for the first time, showing the Welcome tab with options like New File and Open Folder.](images/vscode-welcome.png)
_Figure 2: VS Code on first launch. The Welcome tab gives you quick access to common starting actions._

---

## Part 3: Sign In to GitHub Inside VS Code

VS Code has built-in Git and GitHub tools. Signing in connects your editor directly to your GitHub account so you can save your work online.

### Steps

1. In VS Code, click the **Accounts** icon at the bottom of the left sidebar. It looks like a person silhouette.

   ![VS Code left sidebar with the Accounts icon highlighted at the bottom, shaped like a person outline.](images/vscode-accounts-icon.png)
   _Figure 3: The Accounts icon in the VS Code sidebar._

2. In the menu that appears, click **Sign in with GitHub**.

3. Your browser will open and ask you to authorise VS Code to access GitHub. Click **Authorize Visual-Studio-Code**.

   > 🛑 **Warning**
   > Only click **Authorize** if you initiated this action yourself. If a browser window opens asking you to authorise GitHub unexpectedly, close it immediately.

4. Your browser may ask: _"Allow this page to open Visual Studio Code?"_ — click **Open** (or **Allow**).

5. Switch back to VS Code. Your GitHub username should now appear in the bottom-left corner of the window, next to the Accounts icon.

   > 📝 **Note**
   > If nothing happens after step 4, return to VS Code manually. The sign-in may have completed in the background.

---

## Part 4: Create Your First GitHub Repository

A _repository_ (often shortened to _repo_) is a folder where GitHub stores all the files for a project, along with a full history of every change you make.

### Steps

1. Return to [https://github.com](https://github.com) in your browser and sign in if needed.

2. Click the **+** icon in the top-right corner of the page, then click **New repository**.

   ![GitHub top navigation bar with the plus icon highlighted in the top-right corner.](images/github-new-repo.png)
   _Figure 4: Click the + icon to create a new repository on GitHub._

3. Fill in the repository details:
   - **Repository name:** Type `html-practice` (no spaces).
   - **Description:** Optionally type a short description, e.g., `My first HTML project`.
   - **Visibility:** Select **Public** (so your instructor can view it).

   > 💡 **Tip**
   > A Public repository is visible to anyone on the internet. Do not upload passwords, personal information, or private files to a public repository.

4. Check the box labelled **Add a README file**. This creates a starter file in your repository.

5. Leave all other settings as default and click **Create repository**.

Your repository is now live on GitHub.

---

## Part 5: Clone the Repository to Your Computer

_Cloning_ downloads a copy of your GitHub repository to your computer so you can open and edit files in VS Code. Changes you make locally can then be sent back ("pushed") to GitHub.

### Steps

1. On your new repository page on GitHub, click the green **Code** button.

2. Make sure the **HTTPS** tab is selected, then click the **copy** icon next to the URL to copy it.

   ![GitHub repository page showing the green Code button expanded, with the HTTPS URL and copy icon highlighted.](images/github-clone-url.png)
   _Figure 5: Copy the HTTPS URL from the Code dropdown to clone your repository._

3. Switch to VS Code. Press the following keyboard shortcut to open the **Command Palette**:
   - **Windows:** `Ctrl + Shift + P`
   - **Mac:** `Cmd + Shift + P`

4. In the Command Palette, type `Git: Clone` and select it from the dropdown list.

5. Paste the URL you copied from GitHub and press `Enter`.

6. A file browser window will open. Choose a folder on your computer where you want to save the project (e.g., your Desktop or Documents folder), then click **Select as Repository Destination**.

7. VS Code will ask: _"Would you like to open the cloned repository?"_ — click **Open**.

Your repository folder is now open in VS Code and connected to GitHub.

![VS Code showing the cloned repository open in the Explorer panel on the left, with README.md visible.](images/vscode-cloned-repo.png)
_Figure 6: Your cloned repository open in VS Code. The README.md file created on GitHub is visible in the Explorer panel._

---

## Conclusion

You have successfully set up your coding environment. At this point you have:

- Created a free GitHub account
- Installed and launched Visual Studio Code
- Connected VS Code to your GitHub account
- Created a GitHub repository
- Cloned the repository to your computer

You are now ready to begin writing HTML. Continue to **Task 2: Creating and Structuring an HTML File** to write your first webpage.

---
