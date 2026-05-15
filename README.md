# ENVS 193DD Intermediate Elective 2

# General information
This repository contains data and code to visualize relative native vs. non-native vegetation cover at North Campus Open Space. It also contains (edited) code from Ijeamaka Anyene’s [“Historically Black Colleges and Universities”](https://github.com/Ijeamakaanyene/tidytuesday) visualization, which was used as inspiration for the vegetation visualization.

To work with the code in this repository, you will need the following packages:

```
library(tidyverse)
library(here)
library(ggtext)
library(showtext)
```

# Data and file information

```
├── README.md
├── code                                          
│   ├── 2021_04_hbcu.Rmd                          # Anyene’s hbcu viz (personal edits made)
│   ├── 2021_04_hbcu.html
|   ├── vo-henderson_intermediate-elective-02.qmd # Vegetation viz
|   └── vo-henderson_intermediate-elective-02.pdf
├── data
│   ├── veg.csv                                   # vegetation data
│   └── vp_veg_metadata.csv                       # vegetation metadata
├── images
│   └── intermediate-sketch.png
├── outputs
│   ├── 2021_04_hbcus.png                         # output of Anyene's viz
│   └── 2026_05_ncos.png                          # output of vegetation viz
└── week-05_spring-2026_aquatic-inverts.Rproj
```

# Rendered output

The rendered output can be found [here](https://github.com/hendersonvo/intermediate-elective/blob/main/code/vo-henderson_intermediate-elective-02.pdf)