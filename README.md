# Interactive Content Repository

This is a unified authoring platform that makes it easy (for reasonably computer-savvy users) to make academic content in all its forms available on the web in a coherent and easily maintained way, increasing both presence and reach of the work going on in an AI research group or CDT.

To contribute create a .md file in the content folder following the template. 

```
# <TITLE> #

## Tldr 
<TLDR>

## Author 
<AUTHOR>

## Image  

![hero-image](<LINK-TO-THE-IMAGE>)

## Paper-authors
- <AUTHORS>

## Venue
- [<VENUE-NAME>-<VENUE-YEAR>](<VENUE-LINK>)

## Video   
<LINK-TO-THE-VIDEO>

## Slides
<LINK-TO-THE-SLIDES>

## Code
<LINK-TO-THE-CODE>

## Theme
<THEME>

## Tags

![Generic badge](https://img.shields.io/badge/<TAG-NAME>-blue.svg)
![Generic badge](https://img.shields.io/badge/<TAG-NAME>-blue.svg)

## More Resources

[![PDF](https://img.shields.io/badge/read-PDF-green.svg)](<LINK-FOR-PDF>)

[![Generic badge](https://img.shields.io/badge/View-Poster-green.svg)](<LINK-FOR-POSTER>)

[![Generic badge](https://img.shields.io/badge/Read-Supplement-green.svg)](<LINK-FOR-SUPPLEMENT>)

[![Generic badge](https://img.shields.io/badge/Read-Scholar-green.svg)](<LINK-FOR-SCHOLAR>)
```

After that, edit the _toc.yml file as follows

```
# Table of contents
# Learn more at https://jupyterbook.org/customize/toc.html
format: jb-book
root: intro
chapters:
- file: content/Precision-Recall-Gain Curves
  title: Precision-Recall-Gain Curves - PR Analysis Done Right
- file: content/post2
  title: A Second Post
- file: path/to/your/new/file
  title: title-for-your-post
```

Then add your changes to commit. To do so use the commands


```
git status
```
The output show the modified/deleted/new files

```
git add <files-names>
```

or alternatively 

```
git add .
```

Adds all files to commit.

Commit your code.
```
git commit -m '<message-related-to-the-modifications>'
```

Push your updates to the repo.

```
git push
```
