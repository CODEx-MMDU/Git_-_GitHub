# GitHub Workshop README

Welcome to our GitHub Workshop! This README will serve as your guide to understanding the basics of Git and GitHub, including how to install Git on your machine, and an overview of important Git commands you'll be using throughout this workshop. Let's dive in!

## What are Git and GitHub?

**Git** is a distributed version control system that allows you to track changes in your files and coordinate work on those files among multiple people. It's a fundamental tool for developers, allowing for efficient collaboration and version control of projects.

**GitHub** is a cloud-based hosting service that lets you manage Git repositories. It provides a web-based graphical interface and includes features such as bug tracking, feature requests, task management, and wikis for every project. GitHub makes collaboration on code projects easier, offering tools for reviewing code, managing projects, and hosting documentation.

## Installing Git

### Windows

1. Download the latest Git for Windows installer from the [Git website](https://git-scm.com/download/win).
2. Run the installer and follow the steps provided by the setup wizard. Leave all the default settings unless you have a specific need to change them.
3. To check if Git was installed successfully, open the Command Prompt or Git Bash and type `git --version`.

### macOS

1. The easiest way to install Git on a Mac is through the stand-alone installer:
   - Download the latest macOS Git installer from the [Git website](https://git-scm.com/download/mac).
   - Follow the prompts to install Git.
2. Alternatively, you can use Homebrew by running `brew install git` in the terminal.
3. Verify the installation by opening the Terminal and typing `git --version`.

### Linux

1. Open a terminal window.
2. Update your package list with `sudo apt-get update` (Debian/Ubuntu) or `sudo yum update` (Fedora).
3. Install Git using `sudo apt-get install git` (Debian/Ubuntu) or `sudo yum install git` (Fedora).
4. Confirm the installation by typing `git --version`.

## Configuring Git

Before starting to use Git, you'll need to configure your user name and email address. Run the following commands, replacing the name and email with your own:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

## Important Git Commands

- **`git init`**: Initialize a new Git repository in your current directory.
- **`git clone [URL]`**: Clone (copy) a repository from GitHub (or another location) to your local machine.
- **`git add [file]`**: Add a file(s) to the staging area, marking it for inclusion in the next commit.
- **`git commit -m "[commit message]"`**: Commit your staged changes to the repository along with a descriptive message.
- **`git push`**: Push your local commits to the remote repository on GitHub.
- **`git pull`**: Update your local repository with the newest commits from the remote repository.
- **`git branch`**: List, create, or delete branches.
- **`git checkout [branch-name]`**: Switch to another branch and check it out into your working directory.
- **`git merge [branch]`**: Merge the specified branch’s history into the current branch.

## Additional Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Pro Git Book](https://git-scm.com/book/en/v2)

## Conclusion

This README provides a foundational overview to get you started with Git and GitHub. As you explore more, you'll discover the vast potential of these tools in managing, sharing, and collaborating on code projects. Happy coding!
