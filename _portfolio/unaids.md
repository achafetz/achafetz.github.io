---
title: "UNAIDS Data Accessibility"
excerpt: "Creating a package to munge and host UNAIDS HIV Estimates"
header:
  #image: /assets/images/work/mtg_epi-plot.png
  teaser: /assets/images/work/mtg_epi-plot.png
sidebar:
  - title: "Role"
    image: /assets/images/work/mtg_hex.png
    image_alt: "mindthegap Package Logo"
    text: "Designer, Developer, Owner"
  - title: "Timeline"
    text: "2019-2025"
  - title: "Custom R Package"
    text: "[mindthegap](https://usaid-oha-si.github.io/mindthegap/)"
  - title: "Tools"
    text: "R, Git"
gallery:
  - url: /assets/images/work/mtg_untidy.png
    image_path: /assets/images/work/mtg_untidy.png
    alt: "UNAIDS HIV estimates untidy spreadhsheet"
  - url: /assets/images/work/mtg_datastructure.png
    image_path: /assets/images/work/mtg_datastructure.png
    alt: "Tidied data structure"
  - url: /assets/images/work/mtg_epi-plot.png
    image_path: /assets/images/work/mtg_epi-plot.png
    alt: "Kenya Epi Trends plot (1990-2024)"
  - url: /assets/images/work/mtg_gh-releases.png
    image_path: /assets/images/work/mtg_gh-releases.png
    alt: "Various Releases of the data hosted on GitHub"
---

## Project Purpose
 Process, clean, and host tidy UNAIDS' annual HIV Country Estimates data for analyts' ease of access and use.

## Overview

  - Munged the messy spreadsheet UNAIDS posted on [their site](https://aidsinfo.unaids.org/) to tidy it into an analytic and viz ready dataset
  - Added functions for standard graphical views 
  - Created a way for public data to be easy hosted and accessed

## Outcomes
  - Standardize output of an untidy dataset
  - Added features to the dataset (e.g. PEPFAR affliation, goal reach, etc) to minimize analysts reinventing the wheel
  - Allowed for easy access of data through an R package


## Lessons Learned
  - Leveraged GitHub Releases to host the dataset
  - Designed unit tests
  - Worked with stakeholder to understand data needs and explain limitations
  - Learned the importance of hiding developer only functions from end users
  - Optimized data storage/access as well as function parameters
  - Improved naming conventions for functions
  - Collaborated with UNAIDS to gain access to their database to establish a query


{% include gallery caption="" %}