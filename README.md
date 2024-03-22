# ML Project 1 README

Welcome to our ML Project! This guide is designed to help you get started with Git and GitHub, enabling you to contribute to our project effectively.

## Setting Up

Before you can work on the project, you need to have Git installed on your computer and be able to access our GitHub repository.

### 1. Installing Git

If you haven't already, download and install Git from [https://git-scm.com/downloads](https://git-scm.com/downloads). Follow the installation instructions for your operating system.

### 2. Cloning the Repository

To work on the project, you'll need to have a local copy of our code on your machine. This process is called "cloning" the repository.

1. Open your terminal or command prompt.
2. Navigate to the folder where you want to store the project.
3. Run the following command:

```sh
git clone https://github.com/SamNicklez/ml-project-1.git
```

4. Enter your GitHub credentials if prompted.

You now have a local copy of the project! Navigate into the project folder with `cd ml-project-1` to start working.

## Making Changes

After you've made changes to the project (like adding a new feature or fixing a bug), you'll want to save these changes and share them with the team. Here's how:

### 1. Pulling Latest Changes

Before making any changes, it's a good practice to pull the latest changes from GitHub to ensure your local copy is up-to-date.

```sh
git pull origin main
```

### 2. Creating a New Branch

It's recommended to create a new branch for your changes. This keeps the project organized and makes it easier to review and merge contributions.

```sh
git checkout -b <your-branch-name>
```

Replace `<your-branch-name>` with a descriptive name for your branch (e.g., `lanes-branch`).

### 3. Committing Changes

After you've made changes, you need to "commit" them. This saves a snapshot of your changes.

1. Add the files you've changed to the commit:

```sh
git add .
```

The `.` adds all changed files. If you want to add specific files, replace `.` with the file names.

2. Commit the changes with a message describing what you've done:

```sh
git commit -m "Your descriptive commit message here"
```

### 4. Pushing Changes

To share your changes with the team, you need to "push" your branch to GitHub.

```sh
git push origin <your-branch-name>
```

Replace `<your-branch-name>` with the name of your branch.

## Contributing

After pushing your changes, go to the [GitHub repository](https://github.com/SamNicklez/ml-project-1) and create a pull request from your branch. This will notify team members to review your changes to the code. After a review, your changes can be merged into the main project.

## Need Help?

If you're stuck or have questions, feel free to ask me (Sam). Happy coding!
