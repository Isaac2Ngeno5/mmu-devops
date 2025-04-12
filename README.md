# Multi-Media University Devops Event

This guide outlines the steps to contribute your name to the GitHub Collaboration Tutorial project using only the `git clone` command, assuming you have direct write access to the repository (this is less common for open-source projects but possible in collaborative environments).

**Important:** This method assumes you have been granted direct write access to the main repository. If you haven't, you will likely need to follow the forking workflow instead.

## Steps to Contribute:

1.  **Clone the Repository:**
    * Go to the GitHub repository of the Collaboration Tutorial.
    * Click the **"Code"** button (it's usually green).
    * Copy the HTTPS or SSH URL provided.
    * Open your terminal or Git Bash on your local machine.
    * Navigate to the directory where you want to clone the repository.
    * Run the following command, replacing `<repository-url>` with the URL you copied:
        ```bash
        git clone <repository-url>
        ```

2.  **Navigate to the Repository Directory:**
    * Once the cloning is complete, navigate into the newly created repository directory:
        ```bash
        cd <repository-name>
        ```
        (Replace `<repository-name>` with the actual name of the repository).

3.  **Create a New Branch:**
    * Before making any changes, it's good practice to create a new branch. This isolates your changes.
    * Run the following command to create and switch to a new branch named `add-your-name`:
        ```bash
        git checkout -b add-your-name
        ```

4.  **Add Your Name:**
    * Open the file where names are being collected (e.g., `CONTRIBUTORS.md`, `names.txt`, or a similar file - refer to the tutorial's instructions).
    * Add your name to the end of the list on a new line.
    * Save the changes to the file.

5.  **Stage Your Changes:**
    * Tell Git which changes you want to include in your commit:
        ```bash
        git add <file-name>
        ```
        (Replace `<file-name>` with the name of the file you modified).
    * To stage all changes, you can use:
        ```bash
        git add .
        ```

6.  **Commit Your Changes:**
    * Create a commit with a descriptive message explaining your changes:
        ```bash
        git commit -m "Add my name to the list of contributors"
        ```

7.  **Push Your Changes Directly:**
    * Upload your local branch directly to the main repository on GitHub:
        ```bash
        git push origin add-your-name
        ```

8.  **Create a Pull Request (Optional but Recommended):**
    * Even with direct write access, creating a pull request is often a good practice for review and discussion.
    * Go to the GitHub repository.
    * You should see a notification prompting you to "Compare & pull request" for your newly pushed branch. Click this button.
    * Alternatively, navigate to the "Pull requests" tab and click the "New pull request" button.
    * Ensure that the **base repository** and **base branch** are the main repository's defaults (e.g., `main` or `master`) and the **compare branch** is your `add-your-name` branch.
    * Add a title and a brief description to your pull request explaining that you are adding your name as part of the tutorial.
    * Click the **"Create pull request"** button.

9.  **Wait for Review (If you created a Pull Request):**
    * If you created a pull request, the maintainers may review your changes.

10. **Congratulations!**
    * Once your changes are merged (either directly or via a pull request), your name will be part of the contributors list in the Collaboration Tutorial repository.

This simplified process is applicable when you have direct write access. In most collaborative scenarios, the forking workflow provides a safer and more organized way to contribute.
