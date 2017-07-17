# Template CyVerse Science Informatician Deliverable Reporting

You should [import](https://help.github.com/articles/importing-a-repository-with-github-importer/) this repo to build a CyVerse Science Informatician Reporting Repository that will allow you to organize and publicly report activities for members of the Science Informatician Team. 

## How CyVerse Learning Center documentation is built

Each CyVerse Tutorial, Guide, or Quickstart has its own [ReadtheDocs](https://readthedocs.org/) page which in turn is built from its own repo (See the template repos at [https://github.com/CyVerse-learning-materials](https://github.com/CyVerse-learning-materials)). Starting from a [ResStructured text file](http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html) (index.rst) The documentation is built using [Sphinx](http://www.sphinx-doc.org/en/1.4.8/), and hosted on a repo configured with GitHub [Webhooks/Services](http://docs.readthedocs.io/en/latest/webhooks.html). Finally, the site is added to ReadtheDocs. Directions for completing this workflow are below **(See Building a Tutorial from Scratch)**.


## What this repo contains

|Item|Description|Notes|
|----|-----------|-----|
|index.rst|Edit this template to include your deliverables|documents written in markdown will need to be converted to restructured text|
|step1.rst|If documentation has more than one page, use this for the second through second-to-last page; copy as needed|copy as needed for additional pages 1..(n-1)|
|finalpage.rst|If documentation has more than one page, this should always be the **last** page||
|/img (folder)|Place images for your tutorials here|CyVerse logos and other useful images are already here|
|/slides (folder)|Place slides associated with your tutorial here|version controlled files preferred, PPT acceptable|
|/misc (folder)|miscellaneous needed for building documentation| |
|License.md|License|this license file applies to all materials created by CyVerse for this documentation|
|Contributors_maintainers.md|Contact information and recognition||


## Fixing and/or improving documentation via GitHub

1. [Fork](https://help.github.com/articles/fork-a-repo/) this repo to your GitHub account
2. Make edits directly to the **index.rst** file. Edits may be made to the fork the web interface to your GitHub account or [clone](https://help.github.com/articles/cloning-a-repository/) the repo to work on your local computer. For very significant changes (we suggest [making a new branch](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/)). 
3. Commit change; if working from a local copy, push those changes to your fork in Github. 
4. Submit a pull request back to the master repository; you may need to act on feedback before your request is merged. 


### Documentation Style Guide

*General Principles*

- Write instructions in short numbered steps. 
- Where possible limit step to one action; small final actions such as 'press submit' should be separated by a semicolon
- Limit the use of screenshots; where they are needed, use ReStructured text directives for [substitution of images](http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#substitution-definitions) and label them in numbered order in the text (e.g. |image1|)
- Example data associated with documentation should be anonymously available on CyVerse Data Commons (Tutorials@cyverse.org can help you with this)
- Discovery Environment applications should be directly linked to documentation (clicking the 'info' button on any application will give you the 'App URL')
- Atmosphere images should be directly linked to documentation (e.g. "atmo.cyverse.org/application/images/####". 

*Specific examples*

|Instruction|Example|
|-----------|-------|
|Steps generally begin with a verb or preposition|<ul><li>Click on the button<li>Under the "Result" menu</ul>|
|Locations of files are given in absolute paths|<ul><li>/dir1/dir2/file.extension</ul>|
|Top-level menus in Discovery Environment Apps in double quotes|<ul><li>Under "Input" select...</ul>|
|Subheadings/steps in Discovery Environment Apps in single quotes|<ul><li>For 'sensitivity' enter...</ul>|
|Buttons and keywords in bold|<ul><li>Click on **Apps**<li>Select **Arabidopsis**<li>Set 'sensitivity' to **Medium**</ul>|



 
