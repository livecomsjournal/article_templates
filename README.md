# LiveCoMS LaTeX templates

## What's here in this repository

- LiveCoMS's LaTeX templates for all the different article types, in the [`templates`](templates) directory
- A sample article using the template
- Files for starting your own LiveCoMS paper's repo so that you can just clone this repo and get started (see [Getting started](#getting-started))
- [LaTeX formatting tips for using our template well in combination with GitHub](information_for_authors.md)
- [CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/) under which these templates are released

## Description of files.
This repository provides LaTeX templates to prepare articles for LiveCoMS.
Our templates are adapted from the eLife Overleaf templates (v1.4).

The `templates` directory provides our template files, including a LaTeX template `.tex` (which itself provides an example, including text and figures) for each article type, a bibliography style file (`livecoms-vancouver.bst`), and a class file (`livecoms.cls`).

## Using LiveCoMS templates for your own living document

### Getting started.

* To get started with our template, clone [this repository](https://github.com/livecomsjournal/article_templates) or click the "clone or download button" and download and unzip the a `.zip file`.

* Make a new directory somewhere which will contain the contents of the new GitHub repository you are about to create; for now let's call this `mydirectory`.

* In the copy of this repository you just obtained by downloading or cloning (`article_templates`), copy the files you need to your new directory `mydirectory`. Specifically, navigate to the `templates` directory, pick your article type `.tex` file, rename this file to match the name your want, and copy it to `mydirectory` along with the `.cls` and `.bst` there. Also copy `LICENSE`, `your.README.md`, and `information_for_authors.md`.

* Navigate to `mydirectory` and edit `your.README.md` to be suitable for your document, renaming it to `README.md`.

* If you wish to choose a different license for your work, replace `LICENSE` (a CC-BY license, which we recommend) with a license of your choosing, though we recommend reading [this analysis](http://openaccess.ox.ac.uk/2013/06/13/cc-by-what-does-it-mean-for-scholarly-articles-3/) if you are reluctant about CC-BY; our perspective is that to reach the broadest possible audience while getting maximal credit for your work, you want a license very similar to CC-BY if at all possible.

* Follow the directions to [create a new repository on your own GitHub account](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) with your new files in `mydirectory`.

* Check out the [Information for Authors](information_for_authors.md) for more tips and tricks for getting started with [LaTeX](https://www.latex-project.org/) and [GitHub](https://github.com); ideally you would preserve and update this to be suitable for your work along with your GitHub repo, but this is up to you.

* Start writing and invite collaborators!

### LaTeX Requirements

Our templates require a relatively recent LaTeX installation and have been tested with these versions and others:
- MacTex 2017
- XeLaTeX
- LuaLaTeX
- TeXLive2016/2017

There are known compatibility issues with TeXLive 2015.

## Acknowledgments
We are particularly grateful to eLife for providing the excellent LaTeX template (under the CC-BY license) which provided the starting point for LiveCoMS' templates, and to [LianTze Lim](https://github.com/liantze) ([http://liantze.penguinattack.org](http://liantze.penguinattack.org)) who provided support in adapting the class file and template from eLife v 1.4.
