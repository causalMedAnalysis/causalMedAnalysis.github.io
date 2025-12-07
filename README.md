This website contains statistical software and replication materials for the book [Causal Mediation Analysis](https://www.cambridge.org/us/universitypress/subjects/social-science-research-methods/quantitative-methods/causal-mediation-analysis) (Wodtke and Zhou 2026, Cambridge University Press).

*Causal Mediation Analysis* is a comprehensive guide to understanding why an exposure affects an outcome. It explains how to decompose causal effects into the pathways through which they operate, starting from simple, intuitive applications and building up to more complex designs. Drawing on applications from sociology, psychology, political science, and economics, the book shows how to bring cutting-edge methods into empirical research on mediation.

---

## Software & Resources

Below are the online resources that accompany the book.

### 1. The cmed Stata Module
`cmed` is a Stata module for conducting causal mediation analysis using the methods described in the book. It can estimate natural, controlled, interventional, and path-specific effects using a variety of different approaches, including regression, weighting, simulation, multiply robust, and de-biased machine learning methods.

**Stata module repository:** <https://github.com/causalMedAnalysis/cmed>

**Installation (within Stata):**
```
net install cmed, from("https://raw.github.com/causalMedAnalysis/cmed/master/") replace
```

### 2. The cmedR R Package
`cmedR` is an R package for conducting causal mediation analysis using the methods described in the book. It can estimate natural, controlled, interventional, and path-specific effects using a variety of different approaches, including regression, weighting, simulation, multiply robust, and de-biased machine learning methods. It essentially duplicates the functionality of the `cmed` Stata module while additionally including several other features, like support for more flexible model specification and super learners for de-biased machine learning. 

**R package repository:** <https://github.com/causalMedAnalysis/cmedR>

**Installation (within R):**
```
library(devtools)
install_github("causalMedAnalysis/cmedR")
```

### 3. Replication Files
Data and code for reproducing the analyses in the book, using the Stata module (`cmed`) and R package (`cmedR`) introduced above.

**Replication repository:** <https://github.com/causalMedAnalysis/repFiles>

[**Click Here to Download All Replication Files**](https://github.com/causalMedAnalysis/repFiles/archive/refs/heads/main.zip)

---

## How to Use This Material

1. Start with the book to understand methods for analyzing causal mediation.
2. Install the Stata module or R package following the instructions above.
3. Use the replication files to run the scripts and implement the workflow from the book.
4. Adapt the code to your own data and applications.

---

## How to Cite This Material

When using `cmed` or `cmedR`, please include the following citation:

Wodtke, Geoffrey T. and Xiang Zhou. 2026. *Causal Mediation Analysis*. Cambridge University Press.

Or use the following bibtex entry:
```
@book{wodtke_zhou_2026_causalmed,
  author    = {Wodtke, Geoffrey T and Zhou, Xiang},
  title     = {Causal Mediation Analysis},
  year      = {2026},
  publisher = {Cambridge University Press}
}
```

---

Maintained by [Geoff Wodtke](https://stonecenter.uchicago.edu/people/geoff-wodtke/) and [Xiang Zhou](https://xzhou.scholars.harvard.edu/).  
To report issues, please email causalmed (at) gmail (dot) com.
