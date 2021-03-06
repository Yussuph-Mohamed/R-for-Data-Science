---
title: Materials for D-Lab's R for Data Science
author: Dillon Niederhut
---

This repository contains the instructor materials for the D-Lab's R intensive.

## If you are a student:

You can download the contents of this repository with:

```
git clone https://github.com/dlab-berkeley/r-for-data-science.git
```

or, by clicking the "Download Zip" button and then extracting the `.zip` file.

The instructor of this workshop series will lead you through the activities for each day.

## If you are a D-Lab instructor

You'll see accumulated teaching notes and examples for each day's topics in the instructor folder. For your convenience, these are available as .Rmd, commented .R files, PDF documents, and HTML slides. The meta-document for this workshop series, which explains the logic behind the structure and topics, can be viewed [at the D-Lab guides repository](https://github.com/dlab-berkeley/guides/blob/master/r.pdf)

For information on contributing to this repository, see `CONTRIBUTING.md`

## If you are a D-Lab facilitator

The standard Drupal workshop descriptions and facetweet postings for this workshop series are in `PUBLICITY.md`

## Description

* `data/` : data necessary for interactive coding examples
* `examples/` 
    * `save_console_output.R` : R code for saving console output to pdf
* `instructor/` : teaching notes
* `scripts/`
    * `feedback_cleaner.R` : used to clean data for use in Day 3
    * `regenrate_files.R` : for regenerating `.R` and `.pdf` files from `.Rmd`

## Topics:

This workshop series covers:

1. Interacting with R
2. Datatypes
3. Data structures
4. Reading data
5. Sanitizing data
6. Missing data
7. Reshaping data
8. Summary statistics
9. Plotting
10. Linear models
11. Non-parametric models
12. Functions
13. Loops
14. Parallelization
15. Packages

## Libraries

This workshop uses the following packages:

* Amelia
* devtools
* dplyr
* foreign
* ggplot2
* parallelMap
* RCurl
* roxygen2
* stringr
* tidyr
* XML

---
_D-Lab == Data Intensive Social Science, For All!_
