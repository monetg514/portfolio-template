# Getting Started


Portfolio template for CSC and DSP 310

_this is designed to be used by accepting an assignment on github classroom(the url is like: `https://github.com/rhodyprog4ds/portfolio-username`), if you are viewing the source repository(the name url is `https://github.com/rhodyprog4ds/portfolio`), you should go to your repository instead or fork it if you are not enrolled_

**If you are enrolled in the class, using the template from the source repository, not a github classroom link will not create an assignment that can be graded.  **

##  Publishing


#### On GitHub

GitHub Actions are setup for publishing your Jupyter book on GitHub, you can view the rendered website by:
  - Change to the `gh-pages` branch above and view `portfolio.pdf` to see your contents as a pdf, that you can download
  - Offline: switch to the `gh-pages` branch with `git checkout gh-pages` and pull that branch after you push to main.

_In December, if you wish you will be able to transfer ownership of your portfolio to your GitHub account to move it from `rhodyprog4ds.github.io/portfolio-username` to `username.github.io/whatever-you-want`._


#### You can build locally by
*optional*
You can run Jupyter book offline to view the compiled version of your portfolio, but you do not need to. There are some parts of this that are experimental and may be hard to get working on Windows or even Mac, but work on the Linux systems that GitHub hosts.
  - follow the [Jupyter Book Setup Instructions](https://jupyterbook.org/start/overview.html) in order to build offline
  - follow the [Jupyter Book PDF Instructions](https://jupyterbook.org/advanced/pdf.html) in order to build to pdf offline



## Make it yours

**do this for assignment 1** 

- edit `_config.yml` to set your name as author
- fill in the template in  `about.md` to be about yourself
- edit the KWL section of the first 3 `submission_x_intro.md` files
- change the logo if you wish

## Using your Jupyter Book Portfolio

You can use it by adding files, either markdown files or jupyter notebooks to the folder and pushing to the repository.

Optionally, there's a lot of other features. For information on how to use special formatting, see the [Jupyter Book Documentation](https://jupyterbook.org/intro.html) and the example files in the `template_files/` folder of this repository.


## Preparing for Portfolio Checks
_(not assignment 1, only portfolio checks)_

- add files with your contents to the repository, commit all changes directly to the `main` branch
- edit the appropriate `submission_x_intro.md`
- edit `_toc.yml` as follows to include each file you've added following the example below, but with your own file names.
```
- file: submission_1_intro
  sections:
    - file: check1/notesonx
    - file: check1/reflectionb
```
- when you're ready to submit, [create a pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) with `feedback` as the base branch and `main` as the head branch (labeled "compare")
