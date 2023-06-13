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

# 5. SUGGESTIONS FOR FURTHER STUDY

```{tip}
The purpose of this chapter to continue the journey of modeling of glacial advance and retreat using diferential equation models. This chapter includes the stochastic aspect of variability of the climate in the models.
```

```{code-cell}
import matplotlib.pyplot as plt        # this provides a shortcut alias for the plotting functions
import matplotlib                      # this makes graphing and plotting features available to the chapter code
from myst_nb import glue               # this is used to support references between markdown and code

import numpy   as np                   # this makes the numpy library available to the chapter code
import sklearn as scp                  # this makes the scipy library available to the chapter code
import sympy   as smp                  # this makes the sympy library available to the chapter code
```

In the previous chapter we started our modeling with the creation of a deterministic model. The underlying model for the glacier dynamics was purely driven by the mass balance and the geometry of the glacier. This meant that we were dealing with a one-input-one-output scenario. This is not the best approach if we want to do a forecasting of possible behavior of the glacier dynamics in the future. Ehat we would be looking for in  forecasting scenarios is to get a range of possible scenarios.

There are a few different ways to generate such probability scenarios. One is to run the model multiple times with slightly different start parameters and analyze the variability of the output. This will give us a range of possibilies for the future. This is called an ensemble approach where we derive distribution paramters from the set of outcomes from all the different scenarios. The probability distributions will then give us an idea about the expected mean and variance of the possible future scenarios.


## References

This is a collection of articles that were consulted for this chapter.

____________________________________________


https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2011GL047913

This is the conclusion
