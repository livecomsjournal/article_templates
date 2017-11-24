# Preparing LaTex articles using GitHub for the Living Journal of Computational Molecular Sciences ([LiveCoMS](http://www.livecomsjournal.org/))

## LaTeX and GitHub

LaTeX is a powerful typesetting program that is very commonly used in the mathematics and physics community, and increasingly in the computational sciences. We have provided a LaTeX template for use with LiveCoMS articles in order to make it easy to have a pleasing, consistent visual style.

We request that articles developed for LiveCoMS do so by creating a GitHub repository for the paper.  GitHub was created to be able to easily manage code versioning, merging, and branching for software development. We feel that for collaborative documents like the ones in LiveCoMS, which encourage feedback from the community, and not just for authors, this software model is a very good fit. See a more on-depth discussion of this in [brief explanation of "paper writing as code development"](http://https://github.com/livecomsjournal/journal_information/blob/master/editorial_material/PAPER_CODE.md) for this model we are using for LiveCoMS.

### Setting up and Managing a GitHub repository

GitHub has a substantial set of online tutorials and answered questions.  [It is very easy to set up a repository in GitHub](https://help.github.com/articles/create-a-repo/).

Some particular recommendations we have when you set up your GitHub repository.
- Use the issue tracker.  The [issue tracker model](https://guides.github.com/features/issues/) is a powerful way to manage contributions from a number of different authors and contributors.
- [Protect the master branch](https://help.github.com/articles/about-protected-branches/); if people are changing the master branch directly, it will be much harder to track revisions and make sure changes are edited before being incorporated. 
- We recommend adding changes to the repository [through pull requests](https://help.github.com/articles/proposing-changes-to-your-work-with-pull-requests/). In this way, other people can easily see what changes are being requested.

### Some LaTeX formatting tips

- Keep your paper in one sentence per line.  This makes it easy to see which sentences have changed when you look at the diff between one version and the next.  The GitHub diff tools operate on a per-line basis. If there are no line breaks between sentences, then other authors will see only that something somewhere in the paragraph has changed.
