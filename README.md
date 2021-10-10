[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)
#

# First-contributions-practice
This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below to practise making a Pull Request(PR).

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

Questions can be asked by raising a `Discussion` with a `Q&A` tag.

Issues arising from using this repository's code can be outlined under the `Issues` tab

**Just add your name to the alphabetical list in [Contributors.md](./Contributors.md) and optionally, a link to your GitHub account**

# How to contribute

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone forked repository and make changes locally
<img align="right" width="300" src="https://res.cloudinary.com/dkfj0v8ow/image/upload/v1633874531/Screenshot_2021-10-10_at_17.01.52_sdbuzh.png" alt="clone this repository" />

Click on the clone button (green in colour). This gives you a copy of the project. Its now yours to play around with

Open a terminal and run the following git command:

```
  git clone https://github.com/yourGithubUsername/First-contribution-practice.git
```
This will download the forked copy of this repo to your computer


## Create a branch 

Switch to the cloned folder. This can be done with Gitbash or the integrated terminal in the VSCode editor

Open the file `README.md` in your text editor such as VS Code

```
  cd First-contribution-practice  
```
Now create a branch using the `git checkout` command:

Your name would make a good branch because it's unique

```
  git checkout -b <name of new branch>
```

For example:

```
git checkout -b add-jerry-abraham
```
(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.
If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

Celebrate your contribution and share it with your friends and followers

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](https://firstcontributions.github.io/#project-list).


---

## <ins> What if I have a Conflict? </ins>

#### A GitHub conflict is when people make changes to the same area or line in a file. This must be fixed before it is merged in order to prevent collision in the main branch.

- #### To read more about this, go to [Github Docs - About Merge Conflicts](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)
- #### To find out about how to fix a Git Conflict, go to [Github Docs - Resolve Merge Conflict](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)

---
