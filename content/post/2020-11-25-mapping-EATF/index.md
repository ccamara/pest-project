---
title: "Mapping Emergency Active Travel Funds "
subtitle: ""
date: 2020-11-25T00:00:00Z
summary: For the PEST project we aim to develop an understanding of what local
  authorities are doing in relation to supporting Active Travel in light of this
  funding and whether and how this is being documented. We have carried out some
  initial scoping to identify the extent to which (E)ATF schemes are being
  mapped. This has revealed several sources.
draft: false
featured: false
authors:
  - tim-jones
  - carlos-camara
  - ben-spencer
tags:
  - EATF
categories:
  - Context
projects: []
image:
  placement: 2
  caption: Woman locking her cycle. Photo by <a
    href="https://unsplash.com/@duskchuan?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">yichuan
    zhan</a> on <a
    href="https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a>
  focal_point: ""
  preview_only: false
---
As part of the Government's measures to mitigate the impact of Covid-19 pandemic on local travel, [the Department of Transport announced a £250 million package](https://www.gov.uk/government/news/2-billion-package-to-create-new-era-for-cycling-and-walking) to reallocate road space to encourage active travel (walking and cycling) across England. Local authorities were able to apply for funds in two phases. The initial package, known as the **Emergency Active Travel Fund (EATF) phase 1**, announced in May 2020, was to support temporary measures including pop-up ‘emergency’ bike lanes; wider pavements; junction improvements; and, cycle and bus-only streets. These phase one awards were announced in July 2020. Investment to support the creation of longer-term projects as part of a phase two Active Travel Fund (ATF) was announced in November 2020. This [list](https://www.gov.uk/government/publications/emergency-active-travel-fund-local-transport-authority-allocations/emergency-active-travel-fund-total-indicative-allocations) provides details of the allocations for phase 1 and phase 2 funding per authority.

<figure class="iframe-wrapper">
  <embed src="/media/html_widgets/EATF-breakdown-treemap.html" style="height:900px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Interactive Treemap displaying total EATF Allocation by local authority. </br>Source: PEST. Data: Department of Transport.
  </figcaption>
</figure>

<!-- {{< chart data="treemap" >}} -->

For the PEST project we aim to develop an understanding of what local authorities are doing in relation to supporting Active Travel in light of this funding and whether and how this is being documented. We have carried out some initial scoping to identify the extent to which (E)ATF schemes are being mapped. This has revealed several sources.

[Cyclestreets](https://www.cyclestreets.org), [Widen my path](https://www.widenmypath.com/) is a crowdsourced database that enables anyone to add suggestions on how city councils could modify public space to broaden paths for keeping social distance, as well as voting existing suggestions. Proposals can be of these 3 categories: space for cycling, wider pavements; closures to through-traffic. Since the goal is to inform decision-makers about places that are considered to be crucial or feasible, Cyclestreets has made the effort for this tool to be re-used, by providing an Application Programming Interface (API)[^1] to customize how can it be embedded in other websites, releasing all the data under open license and open, structured file formats such as `CSV` and `GeoJson` and providing a link to a page from Cycling UK where informatino can be submitted to city councils.

<figure class="iframe-wrapper">
  <embed src="https://www.widenmypath.com/" style="height:500px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Cyclestreets' Widen my path
  </figcaption>
</figure>

Cycling UK has a [specific page on their website](https://www.cyclinguk.org/cycle-powered-covid-recovery) aimed to explain Covid-related measures to promote active travel. This includes [a map to track Emergency Active Travel Funds](https://www.google.com/maps/d/viewer?mid=1x7LrFvjDTA-hi_3pt7oquOfMAnUV5LKG&usp=sharing) for [England](https://www.google.com/maps/d/viewer?mid=1x7LrFvjDTA-hi_3pt7oquOfMAnUV5LKG&usp=sharing) and another one to [track planned and ongoing measures in Scotland](https://www.google.com/maps/d/u/0/viewer?mid=1NlXO4_g0HjgnEHOKA56e3y5makiisqKs&ll=57.90338742124505%2C-4.039338250000011&z=6). The map includes a contact email address where public can supply missing information, but no other types of collaboration are present.

<figure class="iframe-wrapper">
  <embed src="https://www.google.com/maps/d/embed?mid=1x7LrFvjDTA-hi_3pt7oquOfMAnUV5LKG" style="height:500px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Cycling UK's 
  </figcaption>
</figure>

[Sustrans](https://sustrans.org.uk/)' [Space to Move](https://www.sustrans.org.uk/space-to-move) tool is a crowdsourced database of Active Travel schemes. Space to Move is updated on a weekly basis and currently has more than 1,200 points, making it one of the more comprehensive maps we have identified to date. It is a live map which anyone can contribute to in two different ways. First, sharing their opinion about specific schemes by filling a survey linked to every map entry. Second, populating the database with missing schemes by filling a  [public form](https://www.surveymonkey.co.uk/r/spacetomoveschemes) with the requested information. Last, but not least, data is licensed under ODbL and can be downloaded from [Sustrans' OpenData portal](https://data-sustrans-uk.opendata.arcgis.com/search?tags=space%20to%20move), making it extremely easy to reuse and analyse by anyone who is interested.

<figure class="iframe-wrapper">
  <embed src="https://sustrans-uk.maps.arcgis.com/apps/Styler/index.html?appid=97f27220279d48c3a4bc44e5aecdde3d" style="height:500px;width:100%">
  <figcaption data-pre="Figure " data-post=":" class="numbered">
    Sustrans' Space to Move app.
  </figcaption>
</figure>

In early 2021 we will be contacting the Department for Transport to investigate plans to record and evaluate the progress of (E)ATF awards and resulting schemes. We will also continue to  review these portals and work with our [stakeholders](/about/#people) to develop our co-develop our collective knowledge of (E)ATF schemes and how they are progressing. We anticipate sharing the outcome of our investigations as they unfold on this Blog.

## References

<div class="csl-bib-body" style="line-height:2;margin-left:2em;text-indent:-2em"><div class="csl-entry">Department of Transport. (2020, November). <i>Traffic Management Act 2004: Network management in response to COVID-19</i>. GOV.UK. <a href="https://www.gov.uk/government/publications/reallocating-road-space-in-response-to-covid-19-statutory-guidance-for-local-authorities/traffic-management-act-2004-network-management-in-response-to-covid-19">https://www.gov.uk/government/publications/reallocating-road-space-in-response-to-covid-19-statutory-guidance-for-local-authorities/traffic-management-act-2004-network-management-in-response-to-covid-19</a></div><span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Traffic%20Management%20Act%202004%3A%20network%20management%20in%20response%20to%20COVID-19&amp;rft.identifier=https%3A%2F%2Fwww.gov.uk%2Fgovernment%2Fpublications%2Freallocating-road-space-in-response-to-covid-19-statutory-guidance-for-local-authorities%2Ftraffic-management-act-2004-network-management-in-response-to-covid-19&amp;rft.au=undefined&amp;rft.date=2020-11&amp;rft.language=en"></span></div>
  
[^1]: From \[wikipedia](https://en.wikipedia.org/wiki/API): “An application programming interface (API) is a computing interface that defines interactions between multiple software intermediaries. It defines the kinds of calls or requests that can be made, how to make them, the data formats that should be used, the conventions to follow, etc.