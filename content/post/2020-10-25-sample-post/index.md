---
summary: Create a beautifully simple website in under 10 minutes.
draft: true
authors:
  - admin
  - 吳恩達
lastmod: 2019-04-17T00:00:00Z
title: Sample embedded map (not to be published)
subtitle: "Create a beautifully simple website in under 10 minutes :rocket:"
date: 2016-04-20T00:00:00Z
featured: false
tags:
  - Academic
  - 开源
categories:
  - Demo
  - 教程
projects: []
image:
  placement: 2
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)"
  focal_point: ""
  preview_only: false
---
This is a **sample blog** post for informative purposes only. Therefore, **it has to be set as `draft**`

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