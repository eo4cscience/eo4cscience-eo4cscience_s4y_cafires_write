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

# 4.1 Account management

<span style="font-size:12;font-weight:bold;font-style:italic;">the publication sub-title tutorial</style> 

Because we want the content of the pages to be dynamic we need to build up the "Python environment" for the executable code-cells in the page. While the namespace of the code-cells is the running kernel I prefer to keep the chapter files self-contained. This means that  each page will start with a code-cell that imports the Python libraries that are required for that page.

```{tip}
The purpose of this chapter is to guide the reader through the entire process of reproducing the results on which the article was based. Unlike "THE PUBLICATION" segment there is a lot of content in this chapter and we will need many markdown files to setup and rund the Python code. This means that there will be sub-pages for THE SCIENCE segment of the publication.
```

```{code-cell}
import matplotlib.pyplot as plt        # this provides a shortcut alias for the plotting functions
import matplotlib                      # this makes graphing and plotting features available to the chapter code
from myst_nb import glue               # this is used to support references between markdown and code

import numpy   as np                   # this makes the numpy library available to the chapter code
import sklearn as scp                  # this makes the scipy library available to the chapter code
import sympy   as smp                  # this makes the sympy library available to the chapter code
```
