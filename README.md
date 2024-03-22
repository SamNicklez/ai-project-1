# ML Project 1 README

Welcome to our ML Project! This guide is designed to help you get started with Git and GitHub, enabling you to contribute to our project effectively.

Link to our dataset [here](https://www.kaggle.com/datasets/jacksondivakarr/student-classification-dataset?select=student.csv)
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

Certainly! Expanding the README to include setup instructions for Python and Visual Studio Code (VSCode) will make it easier for your team to get started. Below, I've added sections on setting up Python and VSCode to the README.

---

### Installing Python

Our project requires Python. Here's how you can install it:

1. **Download Python:** Go to the official Python website at [https://www.python.org/downloads/](https://www.python.org/downloads/) and download the latest version of Python for your operating system.

2. **Install Python:** Open the downloaded file and follow the installation instructions. Make sure to check the box that says "Add Python to PATH" during installation.

3. **Verify Installation:** Open your terminal or command prompt and type `python --version`. You should see the Python version number if the installation was successful.

### Setting Up Visual Studio Code (VSCode)

VSCode is a popular, lightweight code editor that supports Python development and many other programming languages.

1. **Download VSCode:** Visit the official Visual Studio Code website at [https://code.visualstudio.com/](https://code.visualstudio.com/) and download the version for your operating system.

2. **Install VSCode:** Open the downloaded file and follow the installation instructions.

3. **Install Python Extension for VSCode:** Launch VSCode, go to the Extensions view by clicking on the square icon on the sidebar or pressing `Ctrl+Shift+X`. Search for "Python" and install the extension by Microsoft.

4. **Open the Project in VSCode:** Open VSCode, go to File > Open Folder, and select the folder where you cloned the GitHub repository.

### Configuring Python in VSCode

To ensure VSCode uses the correct Python interpreter:

1. Open the command palette with `Ctrl+Shift+P` or `Cmd+Shift+P` on macOS.
2. Type "Python: Select Interpreter" and select it.
3. Choose the Python interpreter you installed earlier. If you have multiple versions of Python installed, select the one you plan to use for this project.

### Installing Required Python Packages

Our project may require additional Python packages. You can install them using `pip`, Python's package installer.

1. Open your terminal or command prompt.
2. Navigate to the project folder (make sure you are in /src in the terminal).
3. Run the following command to install all required packages:

```sh
pip install -r requirements.txt
```

The `requirements.txt` file contains a list of all packages needed for the project. If you add a new package, make sure to update this file.

## Need Help?

If you're stuck or have questions, feel free to ask me (Sam). Happy coding!
