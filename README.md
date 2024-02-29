# GIT & GITHUB BASICS

Basic introduction to the Git and GitHub workflow, emphasizing repository creation, local setup, making changes, committing, and pushing to GitHub.

1. **Initialize a new Git repository**

    ```bash
    git init
    ```

2. **Add a remote repository named 'origin' with the specified URL**

    ```bash
    git remote add origin https://github.com/Karume-lab/PLPBasicGitAssignment.git
    ```

3. **Create a README file with the given content**

    ```bash
    echo "# GIT & GITHUB BASICS" > README.md
    ```

4. **Stage and commit the README file**

    ```bash
    git add README.md
    git commit -m "add readme"
    ```

5. **Create a text file named 'me.txt' with a personal introduction**

    ```bash
    echo "My name is Karume and this is \"Introduction to GIT & GITHUB!\"" > me.txt
    ```

6. **Stage and commit the 'me.txt' file**

    ```bash
    git add me.txt
    git commit -m "me file"
    ```

7. **Push the committed changes to the 'main' branch of the remote repository**

    ```bash
    git push -u origin main
    ```
