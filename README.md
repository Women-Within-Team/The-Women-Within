# The Women Within

![The Women Within](https://github.com/yaseminmenan/The-Women-Within/blob/main/Assets/Docs/women_within_banner.png)

## Overview ##

"A woman wakes up in a strange manor with no prior memories. Doors lead to a one-way path, but she must goback. Are these rooms real? Are these women real? I don’t know anymore..."

## Project structure ##

![Project structure](https://github.com/yaseminmenan/The-Women-Within/assets/38699919/96033099-fa61-4f62-86db-fdfc59f48a89)

## Getting Started ##

### Prerequisites ###

Ensure you have the following prerequisites installed:

- [Unity] (Version 2022.3.10.f1)
- [TODO: define additional dependencies]

### Installation ###

It is required that you have [git LFS](https://git-lfs.github.com) installed.

```bash
git clone https://github.com/yaseminmenan/The-Women-Within.git
cd The-Women-Within
git submodule update --init --recursive
```

## Development Workflow ##

### Branching ###

Follow a branching model to organize development efforts:

- `main`: Main development branch
- `feature/{feature-name}`: Feature branches (that you will develop on)

### Coding Standards ###

Adhere to the coding standards defined in [code-contributing](https://github.com/Women-Within-Team/The-Women-Within/blob/main/PROGRAMMING_GUIDE.md).  

### Start Developing ###

**Always** pull before creating a new branch to get the latest changes on your local repository.

```bash
git checkout main
git pull
``` 

Create your own branch, chose a name descriptive for your work.

```bash
git checkout -b <insert_branch_name>
``` 

Don't forget to commit and push your changes. When you are finished, create a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request#creating-the-pull-request) and add reviewers.

```bash
git add <files to add>
git status # double check everything is fine
git commit -a -m "<your_message_here>"
git push origin <insert_branch_name>
```

Also see best practices for [commits](https://gist.github.com/luismts/495d982e8c5b1a0ced4a57cf3d93cf60) and [pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/best-practices-for-pull-requests).
