---
title: Causal Mediation Analysis
description: Resources, software, and replication files for the book *Causal Mediation Analysis*.
---

# *Causal Mediation Analysis*

*Causal Mediation Analysis* is a comprehensive guide to understanding **why** an exposure affects an outcome. It explains how to decompose causal effects into the pathways and mechanisms through which they operate, starting from simple, intuitive applications and building up to more complex designs. Drawing on applications from sociology, psychology, political science, and economics, the book shows how to bring cutting-edge mediation methods into real empirical research.

## Software & Resources

Below are the main online resources that accompany the book.

### 1. The cmed stata module
`cmed` is a Stata module for conducting causal mediation analysis using the methods described in the book.

**Stata module repo:**
https://github.com/causalMedAnalysis/cmed

**Installation:**
```
net install github, from("https://haghish.github.io/github/")
github install causalMedAnalysis/cmed
```

---

### 2. The cmedR R Package
`cmedR` is a R package for conducting causal mediation analysis using the methods described in the book. It duplicates the functionality of the `cmed` Stata module and additionally includes several other features, like support for parallel processing. 

**R package repo:**  
https://github.com/causalMedAnalysis/cmedR

**Installation:**
```
library(devtools)
install_github("causalMedAnalysis/cmedR")
```

---

### 3. Replication Files (Stata & R)
Data and code in both Stata and R for reproducing the analyses in the book, using the Stata module (`cmed`) and R package (`cmedR`) outlined above.

**Replication repository:**  
https://github.com/causalMedAnalysis/repFiles

---

## How to Use This Material

1. **Start with the book** to understand methods for analyzing causal mediation.
2. **Install the Stata module or R package** using the instructions above.
3. **Use the replication repo** to run the scripts and follow the full workflow in the book.
4. Adapt the code to your own data and applications.

---

*Maintained by the authors of* **Causal Mediation Analysis**.  
For questions or to report issues, please email causalmed@gmail.com.
