# LiveCoMS LaTeX templates

## What's here in this repository

- LiveCoMS's LaTeX templates for all the different article types
- An example article using the template
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

* Navigate to the `templates` directory, pick your article type `.tex` file, rename this file to match the name your want, and delete the other `.tex` files.  Rename the `templates` directory to a name of your choice.

* Edit `your.README.md` to be suitable for your document, move it to `README.md`.

* Follow the directions to [create a new repository on your own GitHub account](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) with your new files.

* Check out the [Information for Authors](information_for_authors.md) for more tips and tricks for getting started with [LaTeX](https://www.latex-project.org/) and [GitHub](https://github.com).

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
