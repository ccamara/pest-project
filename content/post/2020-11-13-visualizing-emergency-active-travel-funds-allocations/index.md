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

Last 13<sup>th</sup> November the DfT annonunced the allocation of £107,778,288, corresponding to the second phase of the Emergency Active Travel Funds (EATF). While phase 1, allocated on May 2020 and accounting for £42,102,451, was aimed to support the installation of temporary projects for the COVID-19 pandemic, this second, more ambitious, one is aimed to support the creation of longer-term projects. Both allocation phases account for a total of £149,880,739, which is notably smaller (60%) than the [announced £250 million](https://www.gov.uk/government/news/2-billion-package-to-create-new-era-for-cycling-and-walking).

In our aim to get an understanding about EATF, we have prepared a series of interactive visuals in order to contribute to better understand where the funds have been allocated. The following interactive table displays how much has been allocated in every region of England. Results can be searched and sorted by clicking on the header, making it easy to see how much has been spent in a specific region, and how does it stand compared to other regions and/or phases.

<div class="wide-child">
  <figure class="iframe-wrapper">
    <embed src="/media/html_widgets/EATF-breakdown-datatable.html" style="min-height:600px;width:1050px;display:block;margin-left:auto;margin-right:auto;">
    <figcaption data-pre="Figure " data-post=":" class="numbered">
      Interactive Table with the EATF Allocation</br>Data: Department of Transport.
    </figcaption>
  </figure>
</div>

Unfortunately, this table only provides information about the minimum unit of analysis (often tier-3 Metropolitan or
non-metropolitan counties[^Regions-UK]), but does not explain the geographical distribution in terms of bigger areas (namely Ceremonial county -tier 2- or Regions -tier 1). Treemaps, however, are better to visualize hierarchical data using nested rectangles.

Each rectangle in the following interactive treemaps represent the amount allocated by region. Rectangles with same colour belong to the same tier-1 region and each area matches proportionally the allocated amount, in relation to the total. Additionally, each rectangle has a label displaying the region's name, the total allocated amount and the percentage in relation to the parent region and in relation to the total displayed in the screen (entry). It is possible to zoom in by clicking on any rectangle and zoom out by clicking on the upper breadcrumb.

<figure class="wide-child">
  <embed src="/media/html_widgets/EATF-breakdown-treemap-phase1.html" style="height:1000px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Treemap displaying total EATF Allocation Phase 1 by local authority. </br>Source: PEST. Data: Department of Transport.
  </figcaption>
</figure>

As can be seen in figure 2, the top-5 allocation regions in the phase 1 where, in this order, South East England; North West England; East of England; West Midlands; and Yorkshire and the Humber.

<figure class="wide-child">
  <embed src="/media/html_widgets/EATF-breakdown-treemap-phase2.html" style="height:1000px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Treemap displaying EATF Allocation Phase 2 by local authority. </br>Source: PEST. Data: Department of Transport.
  </figcaption>
</figure>

On the second allocation phase, however, the top-5 allocation regions where, in this order, 1) North West England (previously on 2nd position); 2) London (previously, 6th); 3) Yorkshire and the Humber (previously, 5th); 4) North East England (previously, 8th); and 5) South East England (previously, 1st)
 
<figure class="wide-child">
  <embed src="/media/html_widgets/EATF-breakdown-treemap-total.html" style="height:1000px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Treemap displaying total EATF Allocation by local authority. </br>Source: PEST. Data: Department of Transport.
  </figcaption>
</figure>

As can be seen comparing the treemaps above, the most funded regions differ slightly between phases. It appears to be an aim to compensate regions between the two phases, although figure 3 clearly shows how North West England and London stand out from the other regions in terms of total allocated funding (both of them account almost for one third of the total funds). This, in turn, opens interesting questions that are to be explored in the future, such as comparing the total allocated funds with the actual budget requested by the authorities in their bids, or, what has been done with the allocated funds. We expect to address some of these questions as the project develops.



[^Regions-UK]: Source: https://en.wikipedia.org/wiki/Subdivisions_of_England#Hierarchical_list_of_regions,_counties_and_districts
