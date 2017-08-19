# Paper writing as code development

Modern code development can be highly collaborative, with authors taking advantage of feedback from peers or experts in their area as their code is reviewed.
This can be especially true in open source code development, such as on GitHub, where development work on software of broad interest might draw constructive criticism and even contributions from many individuals all over the world, greatly improving the final product in a collaborative way and allowing the authors to benefit from the wisdom of the crowds.
It is not unusual for contributions even to come from experts previously unknown to the authors.

*We believe this same model will improve our science writing* in LiveCoMS' area -- reviews, best practices documents, tutorials, and other living documents. 
Authors can make the text of their documents available online as if it were code, and the interested community can provide feedback, make suggestions, and bring new information (additional references, an alternate perspective, confirmatory data, etc.) to the table and to the paper.
Some particularly helpful individuals may even provide new text that the authors may wish to incorporate into their papers, just as outside workers might contribute to a software project. 

## Incentives

Some resources are so valuable to the community that the community develops an interest in maintaining them and ensuring they continue.
Wikipedia provides an example, as do many successful open source software projects. 
But why not scientific paper-writing? 
There are certain foundational documents everyone needs which require constant updating to reflect the latest advances; for example, a document describing the basics of molecular simulations needs updating as new algorithms become available, etc. 

Open source software development already demonstrates that community resources can provide adequate incentive for widespread contributions. 
But with updateable, living papers we can provide an additional incentive: Authorship. 
Especially significant contributors to an article can be recognized by adding them as formal authors. 
More minor contributors can be acknowledged.
If these documents become valuable enough to the community, these incentives will further drive participation. 

## Tools for paper writing/code development

Code developers and authors have many of the same requirements when we receive feedback on our work, or when others propose changes to it. 
We want a way to track people's detailed comments and feedback, and keep a record of which issues we have dealt with and which we haven't, and who raised those concerns.
And when people propose changes, we want their changes "tracked" so we can see exactly what they proposed changing and why, and make sure we agree with the changes. 
Version control is also important, providing the ability to backtrack changes when needed or seee when a particular change was introduced.
All of these tools are available via GitHub and git, so commonly used to make modern software development run smoothly. 
Code developers also have a variety of tricks which carry over directly to making collaborative paper-writing run more smoothly.

Relating to incentives, it is worth noting that GitHub automatically tracks contributions from those who actually make changes (accepted by the authors) to the material, providing a way for contributors to get credit even without formal acknowledgment or authorship.

## How it works in practice

In practice, authors simply make their paper's source material (LaTeX source, image files, tables, etc., along with as much of the raw material as possible) in a public GitHub repository and link to this in their preprint, encouraging community participation via the issue tracker (for discussion/reports of problems) or via pull requests (proposed edits of the material)..
If the article draws an interested community, the authors can expect contributions in both forms. 
Some readers will certainly catch typos or recommend other references or additional discussion via the issue tracker; others may be interested in actually helping to contribute by proposing modifications such as via pull requests.
The authors then review issues and proposed changes, dealing with them appropriately.

Perhaps this may seem idealistic, but a recent example proves this model can work. 
David Mobley and Michael Gilson wrote a recent review paper on benchmarking binding free energy calculations, [Predicting binding free energies: Frontiers and benchmarks](https://github.com/mobleylab/benchmarksets) which uses precisely this model. 
A variety of community contributions have already come in, with some contributions extensive enough that one new author has already been added and another is being added (as of this writing).
The paper is substantially longer new, covers more of the field, and includes a variety of new developments which occurred since its original publication. 

We will also make available some practical, detailed instructions on using GitHub in this manner, though authors using this model will need to gain some basic familiarity with using git and GitHub, or have a co-author who handles this aspect.
 
