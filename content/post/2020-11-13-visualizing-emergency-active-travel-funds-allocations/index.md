---
title: Visualizing Allocation of Active Travel Funds Allocations
subtitle: EATF Second Allocation Phase has been announced
date: 2020-11-13T00:00:00.000Z
summary: ""
draft: false
featured: false
authors:
  - carlos-camara
tags:
  - EATF
categories:
  - Context
projects: []
image:
  placement: 2
  caption: "Oxford's High Street. Photo: <a
    href=\"https://unsplash.com/@hpetersen14\">Hannah Petersen</a>"
  focal_point: ""
  preview_only: false
---

On  13<sup>th</sup> November 2020, the [DfT annonunced the allocation of the second phase of the Active Travel Funds (ATF)](https://www.gov.uk/government/publications/emergency-active-travel-fund-local-transport-authority-allocations). This totalled £175,360,750. While phase 1 Emergency Active Travel funds, allocated in May 2020, and totalling £42,102,451, was aimed to support the rapid installation of temporary projects for the COVID-19 pandemic, the second, allocation was targeted at supporting the implementation of long-term projects. Both allocation phases account for a total of £217,463,201, this seems to be well below the [£250 million that was announced on the 9th May 2020](https://www.gov.uk/government/news/2-billion-package-to-create-new-era-for-cycling-and-walking).

In order to understand the spread of (E)ATF allocations across England, we have prepared a series of interactive visuals[^data-source]. The following interactive table displays how much has been allocated in every region of England. Results can be searched and sorted by clicking on the header, making it easy to see how much has been spent in a specific region, and for comparison between regions for the different phases.

<div class="wide-child">
  <figure class="iframe-wrapper">
    <embed src="/media/html_widgets/eatf-allocation-table-embed.html" style="min-height:600px;width:1050px;display:block;margin-left:auto;margin-right:auto;">
    <figcaption data-pre="Figure " data-post=":" class="numbered">
      Interactive Table with the EATF Allocation</br>Data: <a href="https://www.gov.uk/government/publications/emergency-active-travel-fund-local-transport-authority-allocations">Department of Transport.</a>
    </figcaption>
  </figure>
</div>

Unfortunately, this table is only able to provide information about the minimum unit of analysis (often tier-3 Metropolitan or non-metropolitan counties[^Regions-UK]), but does not explain the geographical distribution in terms of larger geographical areas (namely Ceremonial county -tier 2- or Regions -tier 1). 

Through treemaps, however, we are better to visualize hierarchical data using nested rectangles. Each rectangle in the following interactive treemaps represents the amount allocated by region. Rectangles with the same colour belong to the same tier-1 region and each area matches proportionally the allocated amount, in relation to the total. Additionally, each rectangle has a label displaying the region’s name, the total allocated amount and the percentage in relation to the parent region and in relation to the total displayed in the screen (entry). It is also possible to hover over every rectangle to see the percentage allocated in relation to the total in England. Last, but not least, it is possible to zoom in by clicking on any rectangle and zoom out by clicking on the upper breadcrumb.

<figure class="wide-child">
  <embed src="/media/html_widgets/EATF-breakdown-treemap-total.html" style="height:1000px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Treemap displaying total (E)ATF Allocation by local authority. </br>Source: PEST. Data: <a href="https://www.gov.uk/government/publications/emergency-active-travel-fund-local-transport-authority-allocations">Department of Transport.</a>
  </figcaption>
</figure>

As can be seen in the figure above, if we focus on a regional scale, there is negligible variation between the two phases and the total allocation. In all cases the most allocated regions were, in this order:

* **Phase 1:** South East England (19%), North West England (16%), East of England (12%), London (12%), West Midlands (11%), Yorkshire and the Humber (11%)
* **Phase 2:** South East England (19%), North West England (16%), East of England (12%), London (11%), West Midlands (10%), Yorkshire and the Humber (10%)
* **Total:** South East England (19%), North West England (17%), East of England (12%), London (11%), West Midlands (10%), Yorkshire and the Humber (10%)

As can be seen, there are no differences in absolute therms and few ones in relative terms (with a variation of 1% in the case of London, West Midlands and Yorkshire and the Humber).

However, if we focus on combined or local authorities, there can be seen slightly more variations. The following interactive table can be useful to explore those small variations between authorities and phases:

<div class="wide-child">
  <figure class="iframe-wrapper">
    <embed src="/media/html_widgets/eatf-allocation-variance-table-embed.html" style="min-height:800px;width:1250px;display:block;margin-left:auto;margin-right:auto;">
    <figcaption data-pre="Figure " data-post=":" class="numbered">
      Interactive Table with the (E)ATF Allocation, showing percent of allocated amounts per phase and variation.</br>Data: <a href="https://www.gov.uk/government/publications/emergency-active-travel-fund-local-transport-authority-allocations">Department of Transport.</a>
    </figcaption>
  </figure>
</div>

Our next step in order to better understand (E)ATF will be to conduct a series of in-depth case studies at Oxfordshire (where our institution is based) and the four case areas used for the [Understanding Walking and Cycling study](https://pest-project.org/publication/pooley-2011-understanding-waking-cycling/) (Lancashire, Leeds, Leicestershire and Worcestershire). Case studies will include desk research as well as site visits and interviews with key actors.

[^data-source]: You can [check the data source here](https://docs.google.com/spreadsheets/d/e/2PACX-1vTYSfTrLj5TpExh8d-MTo9BaDb2L1Jc2Gg1E-uGolVkbenHa0z7-0JVITzhHFlZRo3YgDNP7bLOFv4j/pubhtml), which in turn is a copy of the [values provided by DfT](https://www.gov.uk/government/publications/emergency-active-travel-fund-local-transport-authority-allocations/emergency-active-travel-fund-total-indicative-allocations)
[^Regions-UK]: Source: https://en.wikipedia.org/wiki/Subdivisions_of_England#Hierarchical_list_of_regions,_counties_and_districts
