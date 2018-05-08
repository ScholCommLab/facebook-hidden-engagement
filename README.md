# Facebook Hidden Engagement

This project run by the [\#ScholCommLab](scholcommlab.ca) explores the collection of social engagement data for scholarly articles through Facebook's Graph API.

Currently, the project entails three distinct areas:

1. Technical Challenges of Collecting Altmetrics through Facebook's Graph API (under review)
2. Public vs Private Engagement (in progress)
3. FHE Microservice (in progress)

More details in the individual project descriptions below.

## Project details

### 1. Technical Challenges of Collecting Altmetrics through Facebook's Graph API  (under review)

In this short research paper, submitted to the [STI 2018](http://sti2018.cwts.nl/), we describe two major areas of challenges that we encountered during the collection of Facebook's engagement data based on URLs. 

Data and code are available in this repository: [STI 2018 Submission](https://github.com/ScholCommLab/fhe-technical-challenges)

Abstract:

> Previous research shows that, despite its popularity, Facebook is less frequently used to share academic content. In order to investigate this discrepancy we set out to explore engagement numbers through their Graph API by querying the Facebook API with multiple URLs for a random set of 103,539 articles from the Web of Science. We identified two major challenge areas: mapping articles to URLs and the mapping URLs to objects inside Facebook. We then explored three problem cases within our dataset: (1) identifying a landing page for any given URL, (2) instances where equivalent URLs are mapped to different Facebook objects, and (3) instances of different articles being mapped onto the same Facebook object. We found that the engagement numbers for 11.8% of all articles that have been shared on Facebook at least once are not reliable because of these problems. Moreover, we were unable to identify the URL for 11.6% of the articles in our data. Taken together, the three problem cases constitute 12.3% of the 103,539 tested articles for which engagement numbers cannot be relied upon. Given that we only tested a small number of problem cases and URL variants, our results point to large challenges facing those wishing to collect Facebook metrics programatically through the available API.

### 2. Public vs Private Engagement (in progress)

The current aim of this project is the collection of Facebook's private engagement numbers through their Graph API in contrast to common approaches which only access data available in postings in public groups.

Data and code is tracked in the following repository: [Public vs Private Engagement](https://github.com/ScholCommLab/fhe-public-private)

### 3. FHE Microservice (in progress)

This third project aims to provide an Open Source microservice for publishers to collect the private engagement for their articles. Furthermore, we hope to provide a possibility to easily push the data to CrossRef's Event Data service.

The source code for the prototype is available in this repository: [FHE Microservice](https://github.com/ScholCommLab/fhe-collector)

