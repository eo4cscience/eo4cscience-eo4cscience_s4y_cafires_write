# EO4CSCIENCE eSee4Yourself Article Template

The preferred way to start a new eSee4Yourself article is using the eo4cscience `_eo4cscience_es4y`-template which will generate the whole repository for the new publication. Once this is created we can simply do a git clone into the ebooks directory and we're set. The benefit of using the template is that the naming of the repository will all be taken care of and the environment files etc come with the template.

The git clone happens from the eo4cscience account and the authentication is:

username:       eo4cscience
access_key:     `<local only>`

We can then move into the new clone of the book repository. The naming convention for the "See for Yourself" series follows the same patterns as the eBooks but with a small extra `_s4y_`:

```
  eo4cscience_s4y_<slug>_write
```

This is merely done to group all the series' articles together in the directory.

The eSee4Yourself articles have a standard outline that guides the reader through the process of reproducing the results presented in the article. The S4Y articles are part of the curriculum publication strategy to engage with the general public about the performed research. (typically there will also be either an eBook or a ePublication article).

The S4Y articles follow the following feature publication method. The article needs to capture the reader from the title onwards. This means that it should be placed in location, time and present immediate relevance to the reader audience. Furthermore the progression through the content gets ever more technical flowing frome general background through the discussion of the findings.

The main outline for the S4Y template consists of two sections:

1. the publication section
1. the reproducable research section

The online outline of the publication will enable the reader to jump straigh to either one of these entrypoints depending on whether the reader want to do "reading-first" or whether the reader wants to do "science-first".

The template consists of the following files:

README.md
: this file is the repository summary file and explains how the template has to be used for authors of the template repository -- a write's guide of you will.

index.md
: this is the introduction page to the publication and is reached by clicking on the EO4CSC logo of the publication. It provides a small summary of the content of the document and instruction for the reader on how to reference the publication. It is the point where the publication title is presented and the reference to author and institution is written.

introduction.md
: this is the introduction to the content of the publication and is where the reader is presented with the overview of the publication. It sets the general introduction and stages the "three-components" of the publication. The main purpose of the introduction page is to grab the reader with the relevance on why to proceed with reading or working with the document. This content is independent of the "reader-first" or "science-first" separation.

publication.md
: these are the standard "reader-first" components of the publication and provide the journalistic content and meta-data for the publication. There will be sub-pages under this table of content entry for sub topics and headers.

science.md
: these are the standard "science-first" components of the publication and provide the hands-on guidance to reproducing the science findings on which the articles journalistinc content was based. Again there will be sub-pages from this page as structured through the `_toc.yml` hierarchy. 

---




A short example showing how to create a new eBook for the EO4SCience Curriculum Framework using Jupyter Book 2.0.

```
Quick setup — if you’ve done this kind of thing before

git clone https://github.com/eo4cscience/_eo4cscience_ebook.git

# 

https://github.com/eo4cscience/_eo4cscience_ebook.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

# create a new repository on the command line

echo "# _eo4cscience_ebook" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/eo4cscience/_eo4cscience_ebook.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/eo4cscience/_eo4cscience_ebook.git
git branch -M main
git push -u origin main
```