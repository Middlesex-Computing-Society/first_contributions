
# How to Contribute to the Members List Project

Welcome to our Members List Project! We're excited that you want to contribute. Whether you're new to open source or an experienced developer, we appreciate you for contributing to this project.

This guide will walk you through adding your name and GitHub Username to our repository's `MEMBERS_LIST.md` file using a pull request (PR). Please follow these steps:

## Step 1: Fork the Repository

- Click the "Fork" button in the upper right-hand corner of this repository. This will create a copy of the repository in your GitHub account.

## Step 2: Clone Your Fork

- Open your forked repository on GitHub.
- Click the "Code" button and copy the URL to your clipboard.
- Open your terminal and run the following command, replacing `<your-username>` with your GitHub username:
  ```sh
  git clone https://github.com/<your-username>/members_list.git
  ```

## Step 3: Create a New Branch

- Navigate to the repository directory using the `cd` command.
  ```sh
  cd members_list
  ```
- Create a new branch for your changes using a descriptive name:
  ```sh
  git checkout -b add-your-name
  ```

## Step 4: Add Your Name and MISIS Number

- Open the `MEMBERS_LIST.md` file using your preferred text editor.
- Add your full name, Course of study and Github Username in the following format:
  ```
  - Your Full Name (Your-course) - <github-username> e.g Harith Onigemo (Computer Systems Engineering) - @harithmetic1
  ```

## Step 5: Commit Your Changes

- Save the `MEMBERS_LIST.md` file.
- Stage and commit your changes with a descriptive commit message:
  ```sh
  git add MEMBERS_LIST.md
  git commit -m "Harith: Added my details to MEMBERS_LIST.md file."
  ```

## Step 6: Push Your Changes

- Push your branch to your fork on GitHub:
  ```sh
  git push origin add-your-name
  ```

## Step 7: Create a Pull Request (PR)

- Go to the main repository on GitHub.
- Click the "New Pull Request" button.
- Set the base branch to the main branch of the main repository and the compare branch to your fork's branch (e.g., `add-your-name`).
- Review your changes, add a meaningful PR title and description, and click "Create Pull Request."

## Step 8: Wait for Review

- The project maintainers will now review Your PR. Please make any changes you asked for if necessary.

## Step 9: PR Approval and Merge

- Once your PR is approved, one of the maintainers will merge it into the main branch.
- Congratulations, you've successfully contributed to our project!

Thank you for your contribution, and welcome to the open-source community!
```
