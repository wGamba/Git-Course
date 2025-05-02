# SCESI Git Course

In this project, I'll learn Git using the repository as class notes (I'll do it in English for my comfort).

 ## Author 

 ***wGamba***

 ## First class: Git Introduction 

 ### Version Control System

 #### What is a Version Control System?

 A version control system (VCS) is a tool that helps you keep track of changes to files over time. It allows you to revert to previous versions, collaborate with others, and manage different versions of your code.

#### Why is Version Control System important?

* **Performance** : Only the requiered data is saved.
* **Security** : Saves every action.
* **Flexibility**: Linear development is not required.

### History
* **1990**: Early VCS tools like RCS and CVS emerged.

* **2005**: Linus Torvalds created Git for Linux kernel development.

* **2008**: GitHub launched, boosting Git's adoption. It was initially created using Ruby.

* **2018**: Microsoft acquired GitHub, further expanding its reach.

* **2025**: GitHub leads the market with AI-driven features and advanced collaboration tools.


### What is Git?

Git stores a full repository copy locally, enabling offline work, and syncs with remote repositories for collaboration and backups.

![Repo Sync](assets/Repo_sync.png)

### What is a repository?

A repository, often referred to as a "repo," is a storage location where your project's files and their revision history are managed. It can be local (on your computer) or remote (hosted on platforms like GitHub). Repositories enable collaboration, version tracking, and centralized management of your codebase.

### Git Commands 

#### Git help

**`git --help`** displays a list of available Git commands and their descriptions. Use it to get quick help or details about specific commands.

#### Git init

**`git init`** initializes a new Git repository in your project directory. It creates a hidden `.git` folder to track changes and manage version control. Use it to start versioning your project.

**`<directory Project> git init`** It is possible to create a Git repository in an already existing directory by using the command `<directory Project> git init`. This initializes Git in the specified directory without affecting its current files. 

## Second class: States and Commits

### The three states of Git

In Git, a state refers to the status of your files in the version control process. 

* **Modified** : The file has been created, changed or delted but not yet staged for commit. 
* **Staged** : The file is marked to be included in the next commit.
* **Commited** : The changes are saved to the local repository.

![Git States](assets/Git_states.png)