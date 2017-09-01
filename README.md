# Preparing LaTex articles using GitHub for the Living Journal of Computational Molecular Sciences ([LiveCoMS](http://www.livecomsjournal.org/))

## LaTeX and GitHub

LaTeX is a powerful typesetting program that is very commonly used in the mathematics and physics community, and increasingly in the computational sciences. We have a provide a LaTeX template for LiveCoMS in order to make it easy to have a pleasing, consistent visual style. 

We request that articles developed for LiveCoMS do so by creating a GitHub repository for the paper.  GitHub was created to be able to easily manage code versioning, merging, and branching for software developemt. We feel that for collaborative documents like the ones in LiveCoMS, which encourage feedback from the community, and not just for authors, this software model is a very good fit. See a more on-depth discussion of this in [brief explanation of "paper writing as code development"](http://https://github.com/livecomsjournal/journal_information/blob/master/editorial_material/PAPER_CODE.md) for this model we are using for LiveCoMS.

### Setting up and Managing a GitHub repository

GitHub has a substantial set of online tutorials and answered questions.  [It is very easy to set up a repository in GitHub](https://help.github.com/articles/create-a-repo/). 

Some particular recommendations we have when you set up your GitHub repository. 
- Use the issue tracker.  The [issue tracker model](https://guides.github.com/features/issues/) is a powerful way to manage
- [Protect the master branch](https://help.github.com/articles/about-protected-branches/) 
- We recommend adding changes to the repository [through pull requests](https://help.github.com/articles/proposing-changes-to-your-work-with-pull-requests/). In this way, other people can easily see what changes are being requested.

### Creating document versions

### Some LaTeX formating tips

- Keep your paper in one sentence per line.  This makes it easy to see which sentences have changed when you look at the diff between one version and the next.  The GitHub diff tools operate on a per-line basis. If there are no line breaks between sentences, then other authors will see only that something somewhere in the paragraph has changed.

## What's here in this repository

Here we provide:
- Our LaTeX template
- An example article using the template, with links to others
- LaTeX formatting tips for using our template well in combination with GitHub

## LaTeX templates

This repository provides LaTeX templates to prepare articles for LiveCoMS. Our templates are adapted from the eLife Overleaf templates (v1.4; obtained 8/10/2017). 
Our templates (adoped from eLife's) are available under the [CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/).

Our template files, including a LaTeX template (which itself provides an example, including text and figures), a bibliography style file, and a class, are available in the `templates` directory. 

**To get started with our template, clone this repository or click the "clone or download button" and download a zip file. Then navigate to the `templates` directory, copy the files to where you will be working, and get started!**
 
