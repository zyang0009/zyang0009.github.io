# Portfolio Building Demo


- [Portfolio Building Demo](#portfolio-building-demo)
  - [What is a GitHub page?](#what-is-a-github-page)
    - [Change a repository to GitHub page.](#change-a-repository-to-github-page)
  - [Directory structures](#directory-structures)
  - [Add your own materials](#add-your-own-materials)
    - [Branch-merge workflow](#branch-merge-workflow)
  - [Additional note:](#additional-note)

This is an example reposiotry that demos how to build a portfolio using GitHub Pages. The original material is from this [repo](https://github.com/aboualnaser/aboualnaser.github.io) and then modified for tutorial purpose.

## What is a GitHub page?

A [GitHub page](https://pages.github.com/) is a static site building service. It enables you to turn a repository into a website. For more details. Please refer to the official GitHub page.


The typical usage of GitHub page includes

  1. Project page like [Electronjs](https://github.com/electron/electronjs.org).
  2. Personal blog, (a lot of examples).
  3. Personal portfolio, like this one.

Usually there are two ways to maintain a static website. 
   1. Modify the html, js and css files directly.
   2. Use a static site generator like [Jekyll](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll). 

If the website is simple enough like this one, you `can` modify the html file directly, as I am doing, but it is almost always encouraged to learn a static website generator. For more information, please refer to the [official tutorial](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll) using Jekyll with GitHub page.


### Change a repository to GitHub page.

To turn a normal repository into a GitHub Page repository, go to the `Settings` tab of the repository and enable the GitHub page option. Do make sure that the repository has a `index.md` or `index.html` to show something on the main page of the site. For details, please refer to this [tutorial](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site).

If the repository's name is the same as your username, then it can be accessed at [https://username.github.io](https://username.github.io). Otherwise he site can be accessed at [https://username.github.io/reponame](https://username.github.io/reponame). For example, this page can be accessed at [https://rongpenl.github.io/ZacharyCV/](https://rongpenl.github.io/ZacharyCV/). The former is usually used to create personal portfolio so if your GitHub username looks unprofessional or unrelated to yourself, **change it now** since it is globally unique and someone else may also want it.


## Directory structures




## Add your own materials

For simplicity, there are only the `index.html` file and `images` directory that you need to modify. Follow the comments in the [index.html](./index.html) file to modify it and monitor the content and look of it in your browser to proceed.

### Branch-merge workflow


## Additional note:

Thanks to [Zach](https://www.linkedin.com/in/zachary-p-villarreal/) for allowing me to use his portfolio as example to build this website.