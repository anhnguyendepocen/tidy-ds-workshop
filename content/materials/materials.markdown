---
title: Download Materials
author: ''
date: "2019-05-30"
slug: download
categories: []
tags: []
linktitle: "Download Materials"
menu:
  materials:
    name: "Download Materials"
    weight: 2
toc: yes
type: docs
---



## How can I access the workshop materials?

Individual slide decks, exercise files, and solutions can be downloaded for each day under the "Schedule" section.

To download all of the course materials, use any of these methods:

* View, clone, or fork the GitHub repository for the workshop [here](https://github.com/wjakethompson/tidyds-2019).
* Click the "Download Workshop Files" button on [home page](/#hero).
* Use the **usethis** package to download the course materials with:

    
    ```r
    install.packages("usethis", repos = "https://cran.rstudio.com/")
    usethis::use_course("bit.ly/tidyds19")
    ```

Once the materials have been downloaded, open the `tidyds-2019.Rproj` file. This should open RStudio, with the work directory set to the directory where the project is located. Once RStudio is open, you can use the file view (in the lower right quadrant of RStudio) to open any of the files.
