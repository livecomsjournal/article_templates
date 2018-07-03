# Guidelines for Generating the Bibliography

## BibTeX

- It is highly recommended that LiveCoMS authors use BibTeX to create the bibliography; for general information see http://www.bibtex.org
- Use of BibTeX requires an input BibTeX bibliography file; see http://www.bibtex.org/Format
- Authors are responsible for:
  * correctly formatting the bibliography file
  * correctly compiling their manuscript against the bibliography file; see http://www.bibtex.org/Using
- BibTeX is invoked in the main TeX document via: \bibliography{livecoms-sample}
- LiveCoMS uses a bibliography style derived from the "Vancouver" style that is distributed by eLife. The "vancouver-livecoms.bst" file must be included in the same directory as the LiveCoMS TeX file to successfully compile the bibliography.  

## Bibliography File

A sample bibliography file is provided in the LiveCoMS Article Template repository: "livecoms-sample.bib"

## Electronic Resources

- LiveCoMS requests that an electronic link be included for each reference if possible. This can include an "digital object identifier" (DOI), a URL provided by the publisher, or some alternate identifier (e.g., PubMed). All recent publications, including books, are likely to have an assigned DOI.
- A reference must contain no more than one electronic link. The order of preference for the link is:
  * DOI
  * Publisher URL
  * some other ID
- The vancouver-livecoms.bst style will prefer to include the DOI, and suppress a separate URL, if the DOI is supplied, so that only one electronic link is included in the citation.
- Electronic links in the BibTeX file are formatted as follows:
  * DOI: doi = {10.1093/nar/gkr1030}
  * Publisher URL: url = {http://nar.oxfordjournals.org/content/40/D1/D706.abstract}
  * An alternate ID can be provided via the "note" tag, such as: note = {PubMed: https://www.ncbi.nlm.nih.gov/pubmed/20454547}
- Do not include the "http://" or "https://" prefix in DOI tags

## Acknowledgments
We are particularly grateful to eLife for providing the excellent LaTeX template (under the CC-BY license) which provided the starting point for LiveCoMS' templates, and to [LianTze Lim](https://github.com/liantze) ([http://liantze.penguinattack.org](http://liantze.penguinattack.org)) who provided support in adapting the class file and template from eLife v 1.4.
