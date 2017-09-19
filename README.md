# Git Workshop

---

# Agenda

1. [Why use Git](#why-use-git)
1. [What is Git](#what-is-git)
1. [How does Git Work](#how-git-works)
1. [Recap](#recap)
1. [Installing Git](#installing-git)
1. [Git Activity](#git-activity)

---

# Why use Git

Imagine yourself as a software developer in company.
You're working in a team of 5 people.
Everyone needs to make changes to files

To avoid disaster, we need a way of:
- Tracking the version of the files
- Distribute the files to each member
- Using changes from other people

---

# What is Git

> Git

Git is a version control system. There are many version control systems, but `git` is a very popular one. Git provides a set of commands that allow you to interact with it.

> Version Control System

It's a system that allows you to record edits to files over time. Hence the name.
Version control systems allow groups of people to edit the same files and have a clean way of controlling the version and order of changes.

---

# How Git Works
![git_diagram](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/git_diagram.png)

---

# How Git Works cont
* Download the project from your online codebase

    **Git terms: Clone the repository**

* You now have your own copy of the project

    **Git terms: You now have a working directory**

* After editing your file

    **Git terms: You have unstaged changes**

* Tell git which files you changed

    **Git terms: Stage your changes to your local repository**

* Upload your changes to your online codebase

    **Git terms: Push your changes to your remote repository**

* When someone else uploads changes you can grab them

    **Git terms: Pull the changes**

--- 

# Recap

![recap](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/recap_git_diagram_cut.png)

---

# Installing Git
- macOS 
  ```bash
  # install brew
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  # install git
  brew install git
  ```

- Linux (Debian based)
```bash
apt-get install git
```    

---

# Installing Git

- Windows

  1. Visit https://git-scm.com/downloads 

  ![alt text](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/git-site.png)

  1. Install the software

  ![alt text](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/git-install.png)

---

# Installing Git

- Open the terminal (macOS, Linux) or git bash application (Windows)
```bash
# Check if git is installed
git
```
- Should see a list of possible commands

---

# Creating an account on Github

1. Visit https://github.com/ and click on the "Sign up for Github" Button.

![alt text](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/github-signup.png)

---

# Git Activity

Adding your own contributions to our workshop webpage

---

# Git Activity
### View Repository

1. Visit https://github.com/CarletonSLAM/git-workshop
1. Click on the "Clone or download" button and copy the HTTPS URL in the text box.

![alt text](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/github-download.png)

---

# Git Activity
### Clone Repository

3. Open your terminal or (or Git Bash if you're on Windows) and navigate to a folder you want to clone to

    cd path/to/directory

4. Clone the repository

    git clone  https://github.com/CarletonSLAM/git-workshop

5. Navigate to you the repoository

    cd git-workshop

6. Create your own branch

    git branch YOUR_BRANCH_NAME 

7. Checkout to your branch

    git checkout YOUR_BRANCH_NAME

---

# Git Activity
### Modify file

8. Navigate to the docs folder and open index.html in a text editor.

9. Add your own name and program in a h3 tag in the middle of the body tag i.e. 

    <h3>Jacky - Software Engineering </h3>

10. Save the file.

---

# Git Activity
## Add and Commit

We now want to stage our changes and commit them.

    git add index.html
    git commit -m "Description of your changes"

---

# Git Activity
## Push
```bash
# Check the status
git status

# Push to your branch if everything looks good
git push origin YOUR_BRANCH_NAME
```

---

# Git Activity
## Pull Request

Go to the repository website and you'll be prompted to make a pull request

---

# Recap

![recap](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/recap_git_diagram.png)

