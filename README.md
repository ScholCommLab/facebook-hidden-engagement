# Facebook Hidden Engagement

This project run by the [\#ScholCommLab](scholcommlab.ca) explores the collection of social engagement data for scholarly articles through Facebook's Graph API.

- [Facebook Hidden Engagement](#facebook-hidden-engagement)
    - [Technical Challenges of Collecting Altmetrics through Facebook's Graph API](#technical-challenges-of-collecting-altmetrics-through-facebooks-graph-api)
    - [Public vs Private Engagement (WIP)](#public-vs-private-engagement-wip)
    - [Study of Facebook Engagement of PLoS ONE publications from 2013-2018 (WIP)](#study-of-facebook-engagement-of-plos-one-publications-from-2013-2018-wip)
    - [FHE Microservice (WIP)](#fhe-microservice-wip)

More details in the individual project descriptions below:

## Technical Challenges of Collecting Altmetrics through Facebook's Graph API

Zenodo: [![DOI](https://zenodo.org/badge/125935481.svg)](https://zenodo.org/badge/latestdoi/125935481)

In this short research paper, to be presented at the [STI 2018](http://sti2018.cwts.nl/), we describe two major areas of challenges that we encountered during the collection of Facebook's engagement data based on URLs. 

Data and code are available in this repository: [STI 2018 Submission](https://github.com/ScholCommLab/fhe-technical-challenges)

Abstract:

> Previous research shows that, despite its popularity, Facebook is less frequently used to share academic content. In order to investigate this discrepancy we set out to explore engagement numbers through their Graph API by querying the Facebook API with multiple URLs for a random set of 103,539 articles from the Web of Science. We identified two major challenge areas: mapping articles to URLs and the mapping URLs to objects inside Facebook. We then explored three problem cases within our dataset: (1) identifying a landing page for any given URL, (2) instances where equivalent URLs are mapped to different Facebook objects, and (3) instances of different articles being mapped onto the same Facebook object. We found that the engagement numbers for 11.8% of all articles that have been shared on Facebook at least once are not reliable because of these problems. Moreover, we were unable to identify the URL for 11.6% of the articles in our data. Taken together, the three problem cases constitute 12.3% of the 103,539 tested articles for which engagement numbers cannot be relied upon. Given that we only tested a small number of problem cases and URL variants, our results point to large challenges facing those wishing to collect Facebook metrics programatically through the available API.

## Public vs Private Engagement (WIP)

Zenodo: [![DOI](https://zenodo.org/badge/107598922.svg)](https://zenodo.org/badge/latestdoi/107598922)

GitHub: [Public vs Private Engagement](https://github.com/ScholCommLab/fhe-public-private)

The current aim of this project is the collection of Facebook's private engagement numbers through their Graph API in contrast to common approaches which only access data available in postings in public groups.

## Study of Facebook Engagement of PLoS ONE publications from 2013-2018 (WIP)

Zenodo: [![DOI](https://zenodo.org/badge/136392868.svg)](https://zenodo.org/badge/latestdoi/136392868)

## FHE Microservice (WIP)

This third project aims to provide an Open Source microservice for publishers to collect the private engagement for their articles. Furthermore, we hope to provide a possibility to easily push the data to CrossRef's Event Data service.

The source code for the prototype is available in this repository: [FHE Microservice](https://github.com/ScholCommLab/fhe-collector)

