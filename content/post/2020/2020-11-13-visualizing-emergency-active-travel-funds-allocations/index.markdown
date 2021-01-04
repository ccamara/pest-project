---
title: "Visualizing Emergency Active Travel Funds' Allocations"
subtitle: 'EATF Second Allocation Phase has been announced'
summary: ''
authors:
- carlos-camara
tags:
- EATF
categories:
- Context
date: "2020-11-13T00:00:00Z"
#lastmod: "2019-04-17T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: "Oxford's High Street. Photo: <a href=\"https://unsplash.com/@hpetersen14\">Hannah Petersen</a>"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---




Last 13<sup>th</sup> November the DfT annonunced the second allocation phase of the Emergency Active Travel Funds. While phase 1 (allocated on May 2020) was aimed to support the installation of temporary projects for the COVID-19 pandemic, this second one is aimed to support the creation of longer-term projects.

The following table displays...

I should add a style to be displayed wider.



Add some treemaps (and possibly maps?)

<div class="wide-child">
  <figure class="iframe-wrapper">
    <embed src="/media/html_widgets/EATF-breakdown-datatable.html" style="height:auto;width:100%">
    <figcaption data-pre="Figure " data-post=":" class="numbered">
      Interactive Table with the EATF Allocation</br>Data: Department of Transport.
    </figcaption>
  </figure>
</div>


<figure class="iframe-wrapper">
  <embed src="/media/html_widgets/EATF-breakdown-datatable.html" class="wide-child">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Table with the EATF Allocation</br>Data: Department of Transport.
  </figcaption>
</figure>


That's the original code: 

<figure class="iframe-wrapper">
  <embed src="/media/html_widgets/EATF-breakdown-datatable.html" style="height:900px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Table with the EATF Allocation</br>Data: Department of Transport.
  </figcaption>
</figure>



{{< figure src="featured.jpg" title="A caption" numbered="true" >}}

<div class="wide-child">
{{< figure src="featured.jpg" title="This image should be wider, but it's hidden under the article-container" numbered="true" >}}
</div



<figure class="iframe-wrapper">
  <embed src="/media/html_widgets/EATF-breakdown-treemap-phase1.html" style="height:900px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Treemap displaying total EATF Allocation Phase 1 by local authority. </br>Source: PEST. Data: Department of Transport.
  </figcaption>
</figure>

<figure class="iframe-wrapper">
  <embed src="/media/html_widgets/EATF-breakdown-treemap-phase2.html" style="height:900px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Treemap displaying EATF Allocation Phase 2 by local authority. </br>Source: PEST. Data: Department of Transport.
  </figcaption>
</figure>

<figure class="iframe-wrapper">
  <embed src="/media/html_widgets/EATF-breakdown-treemap-total.html" style="height:900px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Treemap displaying total EATF Allocation by local authority. </br>Source: PEST. Data: Department of Transport.
  </figcaption>
</figure>


