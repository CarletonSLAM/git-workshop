# Git Workshop

---

# Agenda

1. [Why use Git](#why-use-git)
1. [What is Git](#what-is-git)
1. [How does Git Work](#how-git-works)
1. [Recap](#recap)
1. [Installing Git](#installing-git)

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

1. Visit https://git-scm.com/downloads and select the proper installation link based on your operating system (Windows, Mac Os, Linux)

![alt text](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/git-site.png)

---

# Installing Git

3. Install the software.
    * macOS 
      1. Install [brew](https://brew.sh/)
      1. `brew install git`

    * Windows

        ![alt text](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/git-install.png)

    * Linux Debain based
    ```
    apt-get install git
    ```    

---

# Installing Git

4. Once the installation is complete, you can check that git installed by running ```git --version``` on your terminal

    * On Windows, the Git Bash terminal is also installed with git so you can use this to run most of your commands from now on.

    * The result should look similar to the one below.
    ```
    $ git --version
    git version 2.12.0.windows.1
    ```

---

# Creating an account on Github

1. Visit https://github.com/ and click on the "Sign up for Github" Button.

![alt text](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/github-signup.png)

2. Tell us the email you signed up as so that we can add you to the repository where we have an activity.

---

#Git Activity

Adding your own contributions to our workshop webpage

---

# Git Activity
### View Repository

1. Visit https://github.com/CarletonSLAM/git-workshop

2. Click on the "Clone or download" button and copy the HTTPS URL in the text box.

![alt text](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/github-download.png)

---

# Git Activity
### Clone Repository

3. Open your terminal or (or Git Bash if you're on Windows) and navigate to a folder you want to download our repository
    * ```cd path/to/directory```

4. Run ```git clone  https://github.com/CarletonSLAM/git-workshop``` on your terminal.

5. Run ```cd git-workshop``` and ```git checkout -b YOUR_NAME ``` commands one after the other with YOUR_NAME replaced by your own name.

---

# Git Activity
### Modify file

6. Naviagte to the docs folder and open index.html in a text editor.

7. Add your own name and program in a h3 tag in the middle of the body tag i.e. ```<h3>Jacky - Software Engineering </h3>```

8. Save the file.

---

# Git Activity
## Commit

---

# Git Activity
## Push

---

# Git Activity
## Pull Request

# Recap

![recap](https://raw.github.com/CarletonSLAM/git-workshop/master/.github/recap_git_diagram.png)

