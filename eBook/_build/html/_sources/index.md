# EO4S4Y - A Starter Template for public communications in the "See 4 Yourself" series 

<div style="font-style:italic;font-size:10pt;color:teal;margin-top:25px;margin-bottom:50px">
    <div style="margin-left:100px">
    Raynier A. van Egmond<br>
    Earth Observation for Citizen Science program<br>
    Number xxx / Volume xxx in the "The See 4 Yourself" - series<br>
    Vashon Island (WA) USA.<br>
    </div>
</div>



The eSee4Yourself articles have a standard outline that guides the reader through the process of reproducing the results presented in the article. The S4Y articles are part of the curriculum publication strategy to engage with the general public about the performed research. (Typically there will also be either an eBook or a ePublication article).

The S4Y articles follow the following feature publication method. The article needs to capture the reader from the title onwards. This means that it should be placed in location, time and present immediate relevance to the reader audience. Furthermore the progression through the content gets ever more technical flowing frome general background through the discussion of the findings.

The main outline for the S4Y template consists of two sections:

1. the publication section
1. the reproducable research section

The online outline of the publication will enable the reader to jump straigh to either one of these entrypoints depending on whether the reader want to do "reading-first" or whether the reader wants to do "science-first".

The template consists of the following files:

README.md
: this file is the repository summary file and explains how the template has to be used for authors of the template repository -- a write's guide of you will. This is **NOT PART** of the online publication itself but a component of the repository.

index.md
: this is the introduction page to the publication and is reached by clicking on the EO4CSC logo of the publication [__this page__]. It provides a small summary of the content of the document and instruction for the reader on how to reference the publication. It is the point where the publication title is presented and the reference to author and institution is written.

introduction.md
: this is the introduction to the content of the publication and is where the reader is presented with the overview of the publication. It sets the general introduction and stages the "three-components" of the publication. The main purpose of the introduction page is to grab the reader with the relevance on why to proceed with reading or working with the document. This content is independent of the "reader-first" or "science-first" separation.

publication.md
: these are the standard "reader-first" components of the publication and provide the journalistic content and meta-data for the publication. There will be sub-pages under this table of content entry for sub topics and headers.

science.md
: these are the standard "science-first" components of the publication and provide the hands-on guidance to reproducing the science findings on which the articles journalistinc content was based. Again there will be sub-pages from this page as structured through the `_toc.yml` hierarchy. 

metadata.md
: this page provides all the metadata abround the software, datasources and satellites that were used to produce the scientific results. This will aid those that want to reproduce the material to verify that they are working on the same basis as the article. Once we open up comments for the publications we can receive pull-requests and bug fixes for these repositories.  

------

<div style="font-size:14pt; font-weight:bolder">Summary</div>

<div style="font-size:smaller; color: teal; font-style:italic;margin-left:50px;">
This eBook provides .. do the regular summary for the book with respect to content, results and next steps or whatever makes sense here. 
</div>


<div style="font-size:14pt; font-weight:bolder;margin-top:2rem;">Bibliography</div>

Please cite the material in this eBook as: {cite:p}`vanEgmond_2023_s4y000`

```
van Egmond, R. A. (2023) A Starter Template for public communications in the "See 4 Yourself" series. Self published by EO4CSC.
```

<span style="font-size:14pt; font-weight:bolder;margin-top:40px">Bibtex-entry</span>

```
@book{vanEgmond_2023_s4y001,
  author    = {van Egmond, R. A.},
  title     = {{A Starter Template for public communications in the "See 4 Yourself" series}},
  year      = {2023},
  number    = {1},
  volume    = {1},
  series    = {{"The See 4 Yourself" - series}},
  publisher = {"Earth Observation for Citizen Science" program},
  url       = {http://www.eo4csc.org/eo4csc/_eo4cscience_es4y/index.htm},
  urldate   = {2023-07-01}
}
```

While the book aims to provide a self-contained body of content it does link to other publications in the EO4CSC publications series. Specific mention is made of the book <a href="http://github.com/eo4cscience" target='_blank'>"Introduction to ..."</a> where the href of the anchor to the left points to the eBook content of the published content.

To get some introduction into the larger picture of the EO4CSC Curriculum and how to use this template please refer to the method description on page... in the eBook <a href="http://github.com/eo4cscience" target='_blank'> Introducing the EO4CScience Methodology: a self-guiding curriculum for robust citizen-science Earth observation projects</a> and for the use of the writing format please refer to chapter [How to write Jupyter eBook Content](../docs/how_to_write_ebook_content).

```{note}
These lectures were built using the new Sphinx-based [Jupyter Book 2.0](https://beta.jupyterbook.org/intro.html) tool set, as part of the [ExecutableBookProject](https://ebp.jupyterbook.org/en/latest/).  They are intended mainly as a demonstration of these tools. Instructions for how to build them from source can be found in the Jupyter Book documentation.
```
