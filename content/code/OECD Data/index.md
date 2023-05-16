---
title: OECD Data
subtitle: A real-time macroeconomic database for 14 countries

# Summary for listings and search engines
summary: The new real-time database used in our [paper](https://larsspreng.github.io/publication/fx_hmsu/) in the Journal of Applied Econometrics.
# Link this post with a project
projects: []

# Date published
date: "2023-05-16"

# Date updated
lastmod: "2022"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
#image:
#  caption: ''
#  focal_point: ""
#  placement: 2
#  preview_only: false

authors:
- admin

tags:
- Code
- Data

categories:
- Code
- Data
---

## Summary
For our [paper](https://larsspreng.github.io/publication/fx_hmsu/) in the Journal of Applied Econometrics, we collated a new real-time database for 14 countries. At the time of writing the paper, the datbase consisted of 272 vinatage datasets. Each dataset starts in 1990:02 and ends one month prior to its release. I refer to Section 4.2 in our [paper](https://larsspreng.github.io/publication/fx_hmsu/) for a detailed description.

## Data
We made the data used in our paper publicly available on [GitHub](https://larsspreng.github.io/publication/fx_hmsu/).  

## Code
We wroe Python code that automatically sources the data from the OECD archives. The code is available on [GitHub](https://github.com/larsspreng/OECD_Data/tree/main) and can be used to:
- update the database,
- download other data from the OECD through Python.