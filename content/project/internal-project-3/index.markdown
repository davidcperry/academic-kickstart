---
title: Internal Project
summary: An example of using the in-built project page.
tags:
- Deep Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

```r
cars <- c(1, 3, 6, 1, 1, 1, 2, 3, 4, 5)

# Graph the cars vector with all defaults
plot(cars)

library(bupaR)
```

```
## 
## Attaching package: 'bupaR'
```

```
## The following object is masked from 'package:stats':
## 
##     filter
```

```
## The following object is masked from 'package:utils':
## 
##     timestamp
```

<img src="/project/internal-project/index_files/figure-html/unnamed-chunk-1-1.png" width="672" />

```r
eldata <- read_xes("G:/OneDrive/Documents/buparProject/data/GT_p1_t1.xes")
```

```
## Warning: `data_frame()` is deprecated as of tibble 1.1.0.
## Please use `tibble()` instead.
## This warning is displayed once every 8 hours.
## Call `lifecycle::last_warnings()` to see where this warning was generated.
```

```
## Warning: `as_data_frame()` is deprecated as of tibble 2.0.0.
## Please use `as_tibble()` instead.
## The signature and semantics have changed, see `?as_tibble`.
## This warning is displayed once every 8 hours.
## Call `lifecycle::last_warnings()` to see where this warning was generated.
```

```
## Warning in read_xes("G:/OneDrive/Documents/buparProject/data/GT_p1_t1.xes"): No
## resource_id specified in xes-file
```

```r
#process_map(eldata)
# eldata
nrow(eldata)
```

```
## [1] 676
```




Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. 
