---
title: "OHA R Packages"
excerpt: "Custom R packaged to improve analytic and viz workflows"
header:
  #image: /assets/images/work/packages_main.png
  teaser: /assets/images/work/packages_main.png
sidebar:
  - title: "Role"
    image: /assets/images/work/packages_si.png
    text: "Designer, Developer, Maintainer, Owner"
  - title: "Timeline"
    text: "2019-2025"
  - title: "Custom R Packages"
    text: "[rOpenSci](https://usaid-oha-si.r-universe.dev/packages)"
  - title: "Tools"
    text: "R, Git"
gallery:
  - url: /assets/images/work/packages_main.png
    image_path: /assets/images/work/packages_main.png
    alt: "Main R packages"
  - url: /assets/images/work/packages_other.png
    image_path: /assets/images/work/packages_other.png
    alt: "Other R packages"
  - url: /assets/images/work/package_infrastructure.png
    image_path: /assets/images/work/package_infrastructure.png
    alt: "OHA R package Infrastructure"
---

## Project Purpose
Create a common infratructure for data scientists and data analysts within USAID's HIV program to use to improve efficiency, collaboration, version control, and reproducibility.

## Overview
  - [**gagglr**](https://usaid-oha-si.github.io/gagglr/) - provides a check to users to ensure they are using the latest versions of the core OHA utility packages since they are not updated on regular intervals
  - [**glamr**](https://usaid-oha-si.github.io/glamr/) - focuses on workflow improvements and authentication that is used in other packages
  - [**gophr**](https://usaid-oha-si.github.io/gophr/) - provides utility functions for importing and working with PEPFAR structured datasets (PSDs)
  - [**glitr**](https://usaid-oha-si.github.io/glitr/) - builds upon the ggplot2 framework, providing structured themes and colors for consistency across our visual products
  - [**grabr**](https://usaid-oha-si.github.io/grabr/) - extend the utility functions in glamr, focusing primarily on API utility functions
  - [**mindthegap**](https://usaid-oha-si.github.io/mindtheap/) - munges and provides an access point to tidy UNAIDS estimates and common visualizations
  - [**tameDP**](https://usaid-oha-si.github.io/tameDP/) - converts the PEPFAR Target Setting Tool (TST) into a common structure to mimic other PEPFAR structured datasets for usability
  - [**themask**](https://usaid-oha-si.github.io/themask/) - creates and makes available a dummy, masked dataset that mirrors PEPFAR structured datasets 
  - [**wavelength**](https://usaid-oha-si.github.io/wavelength/) - handles High Frequency Reporting ETL


## Outcomes
  - Created and maintained a variety of open source, R packages to improve process workflows, automation, credential management, and data visualization


## Lessons Learned
  - Design efficient R packages
  - Leverage unit test
  - Leverage continuous integration via GitHub Actions
  - Setup a R universe on rOpenSci
  - Create package sites with full documentation and vignettes
  - Reliance of GitHub Issues for tracking





{% include gallery caption="" %}