# Welcome!
> This page is a guide for new users to learn about git, HTML, and GitHub pages

> ⚠️ This is **not** an advanced guide, please see [Extra Resources]() below if you're looking for those.

This guide isn't meant to be completed all in one go, although it's entirely possible to. Feel free to take a break and pick this up later if you need to.

If you have any questions or have feedback on how I can improve this guide, feel free to message my instagram [`@raymond-exe`](https://www.instagram.com/raymond.exe).

Have fun!

<br><br>

# Table of Contents

> - [**Getting Started**](#getting-started)
>   - [*What is Git?*](#what-is-gits)
>   - [*What is GitHub & GitHub Pages?*](#what-is-github--github-pages)
>   - [*What is HTML?*](#what-is-html)
> - [**Part 1: Setting Up**](#part-1-setting-up)
>   - [*GitHub Basics & Naming your Site*](#github-basics--naming-your-site)
>   - [*Webpage Setup*](#webpage-setup)
>   - [*Setting up your IDE*](#setting-up-your-ide)
> - [**Part 2: Content & Coding**](#part-2-content--coding)
> - [**Part 3: Extra Resources**](#part-3-extra-resources)
<br>

---

<br><br>

# Getting Started

(You don't *need* to read this, but it's helpful if you get confused later on while reading this).

<br>

## What is Git?
Git is formally known as a "Version Control System". It allows us to track which changes have been made to a codebase, when they were made, by who, and even work collaboratively with other programmers on the same project.

In git, programming projects are organized as "repositories". Each repository consists of "branches", which are copies of the codebase separated by feature or additions, later re-combined with the main/"master" branch once the feature is complete. Code is added/updated piecewise through "commits", which are authored by programmers and titled to represent the changes that were made.

This page you're reading is actually an example of a Git repository, hosted by GitHub.

This is the current branch:

![](https://media.discordapp.net/attachments/742768690889490464/1111207995607633950/image.png)


And [here](https://github.com/Raymond-exe/new-page/commit/b05ee63bc7460fd9457113fb2800a589cab2f5ec) is an example of a Git commit.

For the purposes of this project, we'll be sticking to only using the master branch, however you may see other GitHub Pages websites separate their master branch and their "live" branch, or the version of the website publicly seen.

<br>

## What is GitHub & GitHub Pages?
GitHub is a company/website that allows users to store their Git repositories on their servers. GitHub Pages is a service run by GitHub which hosts websites from user repositories.

<br>

## What is HTML?
HTML is a language used to visually organize text (and images) on a page. It doesn't handle button logic nor is it super pretty, but it stores the primary content to be displayed on a page, before other languages such as CSS and JavaScript handle the prettiness and logic of the page, respectively.

While not super complex, I would recommend going through W3 school's HTML tutorial available [here](https://www.w3schools.com/html/).

A full list of HTML elements are also available [here](https://www.w3schools.com/tags/default.asp).


<br>

---

<br><br>

# Part 1: Setting Up

<br>

## GitHub Basics & Naming your Site

To start, make sure you have a [GitHub](https://github.com/login) account. GitHub will help store all files related to our website, and host the website itself as a [GitHub Pages](https://pages.github.com) site.

Next, fork ***this*** repository (using the `Fork` button or clicking [here](https://github.com/Raymond-exe/new-page/fork)) and follow the naming convention below:

<details>
<summary>GitHub Pages naming convention</summary>

- If you name it `<USERNAME>.github.io`, your website will appear under the URL `<USERNAME>.github.io`
- If you name it `<ANYTHING>`, your website will appear under the url `<USERNAME>.github.io/<ANYTHING>`

As examples:
- [raymond-exe](https://github.com/raymond-exe)'s repository named **"raymond-exe.github.io"** will have the URL `https://raymond-exe.github.io`.
- The same user's repository named **"blackjack"** will have the URL `https://raymond-exe.github.io/blackjack`.
</details>

We'll be using the [GitHub Desktop](https://desktop.github.com) application to skip needing to learn Git commands, but if you already have it or have the Git CLI set up you can skip this step. You can download GitHub Desktop [here](https://desktop.github.com).

Lastly, you'll need to copy **your** repository's files onto your computer using GitHub Desktop. Follow the short tutorial below if it's is your first time doing this:

[![](https://markdown-videos.deta.dev/youtube/PoZNIbs_wx8)](https://youtu.be/PoZNIbs_wx8)

<br>

## Webpage Setup

To set up your GitHub repository with GitHub pages, you'll want to navigate to the `Settings` tab of the repository.

![](https://media.discordapp.net/attachments/774125506210693121/1111218070397136976/image.png)

Next, click on `Pages` located at the bottom of the`Code and automation` section on the left.

![](https://media.discordapp.net/attachments/774125506210693121/1111218070623625257/image.png)

Now select the `master` branch, or the branch containing the version of the site you would like to display publicly, and click `Save` to confirm your selection.

![](https://media.discordapp.net/attachments/774125506210693121/1111218070871093258/image.png)

Any updates to the `index.html` file in this repository should now be reflected on a live GitHub Pages site!


<br>

## Setting up your IDE

An IDE / "Integrated Development Environment" is where you'll write all your code for the website.

I recommend using [Visual Studio Code](https://code.visualstudio.com) to write code thanks to its [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) plugin that allows us to preview the website as we code it, although any code editor should be able to work just fine.

If you're using VS Code, here's a tutorial on how to set up the Live Server plugin:

[![](https://markdown-videos.deta.dev/youtube/I2PlgSGT2Ls)](https://youtu.be/I2PlgSGT2Ls)

<br>

---

<br><br>

# Part 2: Content & Coding

Now that everything *else* is ready, we can begin writing code!

Go ahead and open this repository in your editor and open `index.html`. If this is your first time working with HTML, you can reference the [What is HTML?]() section above for help with HTML elements.

<br>

At this point you should be all set to create the website however you'd like, so everything below this line is mostly optional. If you won't be reading beyond this, you can delete both `example.html` and `images/crown.jpg`, but using these files we'll be making an example project portfolio website.

<br>

## Part 3.1: Making a (small) Portfolio!


<br>

---

<br>

# Part 3: Extra Resources
- [W3 Schools - HTML Tutorial](https://www.w3schools.com/html/)
- [W3 Schools - HTML Elements List](https://www.w3schools.com/tags/default.asp)
- [W3 Schools - CSS Tutorial](https://www.w3schools.com/css/)