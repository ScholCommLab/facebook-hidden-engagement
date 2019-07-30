![fhe](/assets/fhe.png)

# Facebook's Hidden Engagement

> Exploring the extent of private engagement with scholarship that is hidden from the public view

This project run by the [\#ScholCommLab](scholcommlab.ca) explores the public and private side of engagement with scholarly documents on Facebook. The project entailed the exploration and development of a new data collection method that aggregates shares, reactions, and likes across several URLs for each article.

Several smaller sub-projects emerged to address various dimensions of the project:

1. A first evaluation of the feasibility of this method and presentation of the technical challenges of collecting private engagement data on Facebook?
2. An application of our method to PLOS ONE publications to compare the nature and extent of private vs public engagement.
3. The development of a plugin for the Open Journals System to collect, aggregate, and provide Facebook metrics collected with the proposed method.

Table of Research Outputs:

- [Facebook's Hidden Engagement](#facebooks-hidden-engagement)
  - [1. «Conference Article» Technical Challenges of Collecting Altmetrics through Facebook's Graph API](#1-%c2%abconference-article%c2%bb-technical-challenges-of-collecting-altmetrics-through-facebooks-graph-api)
  - [2. Collecting public and private FB engagement for PLOS ONE publications](#2-collecting-public-and-private-fb-engagement-for-plos-one-publications)
    - [2.1 «Workshop» Comparing public and private Facebook activity linking to PLOS ONE papers?](#21-%c2%abworkshop%c2%bb-comparing-public-and-private-facebook-activity-linking-to-plos-one-papers)
    - [2.2 «Journal Article» How much research shared on Facebook is hidden from public view? [WIP]](#22-%c2%abjournal-article%c2%bb-how-much-research-shared-on-facebook-is-hidden-from-public-view-wip)
    - [2.3 «Short Paper» The Nature of Private Sharing of Scholarly Articles on Facebook [WIP]](#23-%c2%abshort-paper%c2%bb-the-nature-of-private-sharing-of-scholarly-articles-on-facebook-wip)
  - [3. Making Public Engagement Accessible](#3-making-public-engagement-accessible)
    - [3.1 «Poster» Collecting, Calculating and Displaying Altmetrics with Open Source](#31-%c2%abposter%c2%bb-collecting-calculating-and-displaying-altmetrics-with-open-source)
    - [3.2 «Software» FHE Collector [WIP]](#32-%c2%absoftware%c2%bb-fhe-collector-wip)

## 1. «Conference Article» Technical Challenges of Collecting Altmetrics through Facebook's Graph API

*Authors: Asura Enkhbayar, Juan Pablo Alperin*

In this short research paper, to presented at [STI 2018](http://sti2018.cwts.nl/), we describe two major areas of challenges that we encountered during the collection of Facebook's engagement data based on URLs.

Abstract:

> Previous research shows that, despite its popularity, Facebook is less frequently used to share academic content. In order to investigate this discrepancy we set out to explore engagement numbers through their Graph API by querying the Facebook API with multiple URLs for a random set of 103,539 articles from the Web of Science. We identified two major challenge areas: mapping articles to URLs and the mapping URLs to objects inside Facebook. We then explored three problem cases within our dataset: (1) identifying a landing page for any given URL, (2) instances where equivalent URLs are mapped to different Facebook objects, and (3) instances of different articles being mapped onto the same Facebook object. We found that the engagement numbers for 11.8% of all articles that have been shared on Facebook at least once are not reliable because of these problems. Moreover, we were unable to identify the URL for 11.6% of the articles in our data. Taken together, the three problem cases constitute 12.3% of the 103,539 tested articles for which engagement numbers cannot be relied upon. Given that we only tested a small number of problem cases and URL variants, our results point to large challenges facing those wishing to collect Facebook metrics programatically through the available API.

| Resource | Link |
|-|-|
| Article | [IR](https://openaccess.leidenuniv.nl/handle/1887/65189), [arXiv](https://arxiv.org/abs/1809.01194) |
| Code | [GitHub Repository](https://github.com/ScholCommLab/fhe-technical-challenges)|
| Data | [GitHub Repository](https://github.com/ScholCommLab/fhe-technical-challenges) |

<!-- [![DOI](https://zenodo.org/badge/125935481.svg)](https://zenodo.org/badge/latestdoi/125935481) -->

## 2. Collecting public and private FB engagement for PLOS ONE publications

*Contributors: Asura Enkhbayar, Stefanie Haustein, Germana Barata, Juan Pablo Alperin*

The aim of this project is the collection of Facebook's private engagement numbers through their Graph API in contrast to common approaches which only access data available in postings in public groups.

While the previous project outlined the technical challenges of the method, here we attempt to use our approach on a homogeneous set of articles from a single publisher.

| Resource | Link |
|-|-|
| Data Collection Method | [GitHub Repository](https://github.com/ScholCommLab/fhe-plos)|
| Data [TBC] | [Dataverse Repository]() |

### 2.1 «Workshop» Comparing public and private Facebook activity linking to PLOS ONE papers?

*Authors: Asura Enkhbayar, Stefanie Haustein, Germana Barata, Juan Pablo Alperin*

Workshop proposal submitted to the 2019 Altmetrics Workshop. Oct 11, 2019, Stirling, Scotland.

### 2.2 «Journal Article» How much research shared on Facebook is hidden from public view? [WIP]
> A comparison of public and private online activity around PLOS ONE papers

*Authors: Asura Enkhbayar, Stefanie Haustein, Germana Barata, Juan Pablo Alperin*

A study using the data collected with the previously described method:

**Abstract**

Over the years, Facebook never succeeded to enter the main stage of altmetrics research despite its undisputed position as the biggest social platforms for the general public as well as scholars alike. In this study, we argue that the lack of attention for Facebook is rooted in nature of the data collection methods hitherto, which limits the results to data generated by activity on a select group of public pages and groups. We present a new method of collecting shares, reactions, and comments across the platform including private timelines and use it to gather data for scholarly articles published with PLOS ONE in 2015, 2016, and 2017 and compare the results with data retrieved from Altmetric.com. The results not only show that half of all papers are missed by the limitation to public activity, but the actual volume of private engagement also approximates the patterns of engagement previously only observed for Twitter. Both results suggest that the role and impact of Facebook as a medium for science and scholarly communication has been underestimated. Furthermore, they emphasise the importance of openness and transparency around the collection and aggregation of altmetrics.

| Resource | Link |
|-|-|
| Preprint | [TBA]() |
| Article | [TBA]() |
| Code | [GitHub Repository](https://github.com/ScholCommLab/fhe-plos-paper)|
| Data | [Dataverse link TBA]() |

### 2.3 «Short Paper» The Nature of Private Sharing of Scholarly Articles on Facebook [WIP]

*Authors: TBD*

This short article investigates the nature of private engagement data for PLOS ONE articles.

| Resource | Link |
|-|-|
| Preprint | [TBA]() |
| Article | [TBA]() |
| Code | [TBA]()|
| Data | [TBA]() |

## 3. Making Public Engagement Accessible

*Contributors: Stefan Kasberger, Asura Enkhbayar, Joe Wass, Christine Buske, Juan Pablo Alperin*

This project's goal is the development of an Open Source microservice for the Open Journals System (OJS) run by the Public Knowledge Project to collect private engagement using the proposed method.

### 3.1 «Poster» Collecting, Calculating and Displaying Altmetrics with Open Source

*Authors: Juan Pablo Alperin, Asura Enkhbayar, Heather Piwowar, Jason Priem, Joe Wass*

Poster Lightning Talks presented at 5AM: Altmetrics Conference 16:20-17:20. Sept 26 2018, London, U.K.

| Resource | Link |
|-|-|
| Poster | [Institutional Repository](http://summit.sfu.ca/item/18390) |

### 3.2 «Software» FHE Collector [WIP]

*Authors: Stefan Kasberger, Asura Enkhbayar, Juan Pablo Alperin*

The source code for the prototype is available in this repository: [FHE Microservice](https://github.com/ScholCommLab/fhe-collector)
