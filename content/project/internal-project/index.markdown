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
eldata <- read_xes("G:/OneDrive/Documents/buparProject/data/Disc_p1_t1.xes")
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
## Warning in read_xes("G:/OneDrive/Documents/buparProject/data/Disc_p1_t1.xes"):
## No resource_id specified in xes-file
```

```r
process_map(eldata)
```

<!--html_preserve--><div id="htmlwidget-630f2856bd31df428cb2" style="width:672px;height:480px;" class="grViz html-widget"></div>
<script type="application/json" data-for="htmlwidget-630f2856bd31df428cb2">{"x":{"diagram":"digraph {\n\ngraph [layout = \"dot\",\n       outputorder = \"edgesfirst\",\n       bgcolor = \"white\",\n       rankdir = \"LR\"]\n\nnode [fontname = \"Helvetica\",\n      fontsize = \"10\",\n      shape = \"circle\",\n      fixedsize = \"true\",\n      width = \"0.5\",\n      style = \"filled\",\n      fillcolor = \"aliceblue\",\n      color = \"gray70\",\n      fontcolor = \"gray50\"]\n\nedge [fontname = \"Helvetica\",\n     fontsize = \"8\",\n     weight = \"1.5\",\n     color = \"gray80\",\n     arrowsize = \"0.5\"]\n\n  \"1\" [label = \"1\n50\", shape = \"rectangle\", style = \"rounded,filled\", fontcolor = \"black\", color = \"grey\", tooltip = \"1\n50\", penwidth = \"1.5\", fixedsize = \"FALSE\", fontname = \"Arial\", fontsize = \"10\", fillcolor = \"#ECE7F2\"] \n  \"2\" [label = \"2\n50\", shape = \"rectangle\", style = \"rounded,filled\", fontcolor = \"black\", color = \"grey\", tooltip = \"2\n50\", penwidth = \"1.5\", fixedsize = \"FALSE\", fontname = \"Arial\", fontsize = \"10\", fillcolor = \"#ECE7F2\"] \n  \"3\" [label = \"3\n50\", shape = \"rectangle\", style = \"rounded,filled\", fontcolor = \"black\", color = \"grey\", tooltip = \"3\n50\", penwidth = \"1.5\", fixedsize = \"FALSE\", fontname = \"Arial\", fontsize = \"10\", fillcolor = \"#ECE7F2\"] \n  \"4\" [label = \"4\n50\", shape = \"rectangle\", style = \"rounded,filled\", fontcolor = \"black\", color = \"grey\", tooltip = \"4\n50\", penwidth = \"1.5\", fixedsize = \"FALSE\", fontname = \"Arial\", fontsize = \"10\", fillcolor = \"#ECE7F2\"] \n  \"5\" [label = \"5\n62\", shape = \"rectangle\", style = \"rounded,filled\", fontcolor = \"black\", color = \"grey\", tooltip = \"5\n62\", penwidth = \"1.5\", fixedsize = \"FALSE\", fontname = \"Arial\", fontsize = \"10\", fillcolor = \"#A6BDDB\"] \n  \"6\" [label = \"6\n76\", shape = \"rectangle\", style = \"rounded,filled\", fontcolor = \"white\", color = \"grey\", tooltip = \"6\n76\", penwidth = \"1.5\", fixedsize = \"FALSE\", fontname = \"Arial\", fontsize = \"10\", fillcolor = \"#0570B0\"] \n  \"7\" [label = \"End\", shape = \"circle\", style = \"rounded,filled\", fontcolor = \"brown4\", color = \"brown4\", tooltip = \"ARTIFICIAL_END\n47\", penwidth = \"1.5\", fixedsize = \"FALSE\", fontname = \"Arial\", fontsize = \"10\", fillcolor = \"#FFFFFF\"] \n  \"8\" [label = \"Start\", shape = \"circle\", style = \"rounded,filled\", fontcolor = \"chartreuse4\", color = \"chartreuse4\", tooltip = \"ARTIFICIAL_START\n47\", penwidth = \"1.5\", fixedsize = \"FALSE\", fontname = \"Arial\", fontsize = \"10\", fillcolor = \"#FFFFFF\"] \n\"1\"->\"2\" [label = \"42\", penwidth = \"4.42857142857143\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"1\"->\"6\" [label = \"8\", penwidth = \"1.6530612244898\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"2\"->\"3\" [label = \"49\", penwidth = \"5\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"2\"->\"6\" [label = \"1\", penwidth = \"1.08163265306122\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"3\"->\"4\" [label = \"46\", penwidth = \"4.75510204081633\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"3\"->\"5\" [label = \"3\", penwidth = \"1.24489795918367\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"3\"->\"6\" [label = \"1\", penwidth = \"1.08163265306122\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"4\"->\"5\" [label = \"48\", penwidth = \"4.91836734693878\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"4\"->\"6\" [label = \"2\", penwidth = \"1.16326530612245\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"5\"->\"1\" [label = \"3\", penwidth = \"1.24489795918367\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"5\"->\"4\" [label = \"3\", penwidth = \"1.24489795918367\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"5\"->\"5\" [label = \"9\", penwidth = \"1.73469387755102\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"5\"->\"6\" [label = \"47\", penwidth = \"4.83673469387755\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"6\"->\"2\" [label = \"8\", penwidth = \"1.6530612244898\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"6\"->\"3\" [label = \"1\", penwidth = \"1.08163265306122\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"6\"->\"4\" [label = \"1\", penwidth = \"1.08163265306122\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"6\"->\"5\" [label = \"2\", penwidth = \"1.16326530612245\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"6\"->\"6\" [label = \"17\", penwidth = \"2.38775510204082\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"6\"->\"7\" [label = \"47\", penwidth = \"4.83673469387755\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n\"8\"->\"1\" [label = \"47\", penwidth = \"4.83673469387755\", color = \"dodgerblue4\", fontname = \"Arial\", fontsize = \"10\", weight = \"1\", constraint = \"TRUE\"] \n}","config":{"engine":"dot","options":null}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->




Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. 
