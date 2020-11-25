---
title: 'Sample embedded map'
subtitle: 'Create a beautifully simple website in under 10 minutes :rocket:'
summary: Create a beautifully simple website in under 10 minutes.
authors:
- admin
- 吳恩達
tags:
- Academic
- 开源
categories:
- Demo
- 教程
date: "2016-04-20T00:00:00Z"
lastmod: "2019-04-17T00:00:00Z"
featured: false
draft: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Embed a map, generated with this code from R:


```r
library(leaflet)
library(leaflet.extras)
library(htmlwidgets)

nycounties <- rgdal::readOGR("https://raw.githubusercontent.com/deldersveld/topojson/master/countries/us-states/NY-36-new-york-counties.json")

pal <- colorNumeric("viridis", NULL)

m <- leaflet(nycounties) %>%
  addTiles() %>%
  addPolygons(stroke = FALSE, smoothFactor = 0.3, fillOpacity = 1,
              fillColor = ~pal(log10(as.numeric(COUNTYFP))),
              label = ~paste0(NAME, ": ", formatC(as.numeric(COUNTYFP), big.mark = ","))) %>%
  addLegend(pal = pal, values = ~log10(as.numeric(COUNTYFP)), opacity = 1.0,
            labFormat = labelFormat(transform = function(x) round(10^x))) %>% 
  addFullscreenControl()

m

saveWidget(m, file="leaflet-map-embed.html")
```

<div class="featured-image-wrapper"> 
<div style="position: relative">
<embed class="featured-image" src="/media/html_widgets/leaflet-map-embed.html" style="height:500px">
</div>
</div>
