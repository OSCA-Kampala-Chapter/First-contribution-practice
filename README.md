[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)

# First-contributions-practice

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below to practise making a [Pull Request(PR)](https://github.com/OSCA-Kampala-Chapter/First-contribution-practice/compare).

Questions can be asked by raising a [Discussion](https://github.com/OSCA-Kampala-Chapter/First-contribution-practice/discussions) with a `Q&A` Category tag. Click [New Discussion](https://github.com/OSCA-Kampala-Chapter/First-contribution-practice/discussions/new)

Issues arising from using this repository's code can be outlined under the [Issues](https://github.com/OSCA-Kampala-Chapter/First-contribution-practice/discussions) tab

**Just add your name to the alphabetical list in [Contributors.md](./Contributors.md) and optionally, a link to your GitHub account**

# How to contribute

<img align="right" width="300" src="https://res.cloudinary.com/dkfj0v8ow/image/upload/v1633880626/C1F78D9F-38A5-4DD2-80C8-A94E231CD50C_1_201_a_k7hvbu.jpg" alt="fork this repository" />

### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/)

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone forked repository and make changes locally

<img align="right" width="300" src="https://res.cloudinary.com/dkfj0v8ow/image/upload/v1633881160/7D97B9EF-F94A-470D-A74A-C477149FD821_1_201_a_kddjso.jpg" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon. Its now yours to play around with

Open a terminal and run the following git command:

```
  git clone https://github.com/yourGithubUsername/First-contribution-practice.git
```

This will download the forked copy of this repo to your computer
<img align="right" width="300" src="https://res.cloudinary.com/dkfj0v8ow/image/upload/v1633880626/7BE1DC86-08E8-4B40-8EA2-28460EE992A6_1_201_a_hukryp.jpg" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Switch to the cloned folder. This can be done with Gitbash or the integrated terminal in the VSCode editor

Open the file `README.md` in your text editor such as VS Code

```bash
  cd First-contribution-practice
```

Now create a branch using the `git checkout` command:

Your name would make a good branch because it's unique

```bash
  git checkout -b <name of new branch>
```

For example:

```bash
git checkout -b add-jerry-abraham
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://res.cloudinary.com/dkfj0v8ow/image/upload/v1633881795/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f6769742d7374617475732e706e67_rnqkxw.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```bash
git add Contributors.md
```

You can also add all the changes, by using the command below:

```bash
git add .
```

Now commit those changes using the `git commit` command:

```bash
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```bash
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://res.cloudinary.com/dkfj0v8ow/image/upload/v1633882933/F36B5B3F-A5EB-40F0-87D9-E0CA9F4DDCEC_1_201_a_to6ttr.jpg" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://res.cloudinary.com/dkfj0v8ow/image/upload/v1633882952/Screenshot_2021-10-10_at_19.19.07_vecyri.png" alt="submit pull request" />

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
