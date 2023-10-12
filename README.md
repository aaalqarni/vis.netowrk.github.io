# Introduction

This visualization was developed using the Pyvis Python library. The data used in this visualization was collected from Twitter for wearable devices in the sports industry from January 2018 to March 2023.

## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Cluster Breakdown](#cluster-breakdown)

## Data Source

The data used for this visualization was collected from Twitter over a period spanning from January 2018 to March 2023. This dataset contains discussions, comments, and mentions related to sport products, specifically wearable devices, in the sports industry.

## Cluster Breakdown

### Table 1: Issues and Their Corresponding Keywords

| Cluster                   | Issues                                                                                                   |
|---------------------------|---------------------------------------------------------------------------------------------------------|
| Hardware Issues           | broken, malfunctioning, stopped working, not working, poor quality, not durable, not reliable, faulty, defective |
| User Experience Issues    | disappointed, frustrated, terrible, unreliable, difficult to use, not user-friendly                   |
| Pricing and Value Issues  | not worth, waste of money, overpriced, too expensive                                                  |
| Accuracy and Tracking Issues | not accurate, inaccurate, not accurate heart rate monitor, not accurate sleep tracker, not accurate step counter, not accurate calorie tracker, not accurate distance tracker, not accurate GPS |
| Customer Service and Support Issues | customer service, support, warranty, return policy                                          |
| Delivery and Packaging Issues | shipping, delivery, package not delivered, package lost, package damaged                               |

Table 1 provides a breakdown of different clusters and associated issues related to sport products, specifically wearable devices. By categorizing the issues into clusters, this table provides an organized overview of the common problems reported by users of sport products, specifically wearable devices.


## Visualization Network Description

The visualization network depicts relationships between nodes in the graph, with three types of nodes: Tweets, Brands, and Clusters of Issues. The edges connect these nodes to illustrate connections and associations:

- Edges connect tweet nodes to brand nodes when a tweet mentions a particular brand, representing the relationship between the tweet and the referenced brand.

- Edges also connect brand nodes to clusters of issues nodes, indicating associations between a brand and specific clusters of issues. This connection signifies the relationship between the brand and the relevant issues discussed in the graph.

Consider a sample graph visualization:

- Tweet 1 mentions Brand A, so there is an edge connecting Tweet 1 to Brand A.
- Tweet 2 mentions Brand B, so there is an edge connecting Tweet 2 to Brand B.
- Tweet 3 mentions both Brand A and Brand B, so there are edges connecting Tweet 3 to both Brand A and Brand B.

Additionally, assume the graph has three clusters of issues:

- Issue Cluster 1 represents hardware issues.
- Issue Cluster 2 represents user experience issues.
- Issue Cluster 3 represents pricing and value issues.

In this case:

- Brand A is connected to Issue Cluster 1 and Issue Cluster 2, indicating its association with both hardware and user experience issues.
- Brand B is connected to Issue Cluster 2 and Issue Cluster 3, implying its link to user experience and pricing/value issues.

There are no direct connections between the tweet nodes and the issue cluster nodes. Instead, relationships are established through connections between tweet nodes and brand nodes, as well as between brand nodes and issue cluster nodes.

By examining the edges in the graph, you can identify relationships between tweets, brands, and clusters of issues, helping understand which brands are mentioned in the tweets and the specific issue clusters associated with each brand. The size of each edge between a brand and an issue cluster represents the number of complaints received for the respective issue. Larger or thicker edges indicate a higher number of complaints, while smaller or thinner edges suggest fewer complaints.
This Markdown code integrates the provided visualization network description into your GitHub README, creating a comprehensive document for your project.






