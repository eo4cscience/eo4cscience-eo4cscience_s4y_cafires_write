---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.14.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# 2. THE PUBLICATION TITLE

<span style="font-size:12;font-weight:bold;font-style:italic;">the publication sub-title</style> 

Because we want the content of the pages to be dynamically connected with the results from the THE_SCIENCE segment we need to build up the "Python environment" for the executable code-cells in the page. While the namespace of the code-cells is the running kernel I prefer to keep the chapter files self-contained. This means that  each page will start with a code-cell that imports the Python libraries that are required for that page. 

> Note 1 - "THE PUBLICATION" segment only make references to figures and graphs and should not contain any computed content other than glue-references. This import code-cell is removed from the generated output using the tag-specification `:tags: [remove-cell]`. Remove this entire note from your deliverable but leave the following code-cell.

```{code-cell}
:tags: [remove-cell]
from myst_nb import glue               # this is used to support references between markdown and code
```

> Note 2: The publication's journalistic content will be written as a single markdown page with the subsections as level 2 headers that show up on the righthand side of the page. This way the whole article can be downloaded as a `pdf-file` if the reader so desires.

## Summary

This is the same summary that was presented on the 110_page. The main purpose of the summary is to fill in the catch components of the publication's title.


## Elaborate on the catch-components

This section should use the 5-stage feature-writing outline as discussed in the book: expose..build..climax..fall..denouement 
