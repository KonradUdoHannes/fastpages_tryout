---
toc: true
layout: post
description: Inspiration for open data sources 
comments: true
categories: [data sources, markdown]
author: Konrad Wölms
image: images/book_shelf.jpg
title: Open Data Sources 
---
# Open Data Sources

The goal of this post is simply to collect sources of
along with any clients that might exist for them.

As CorrelAid is originally a german organization
there is a bias towards open data from/about Germany.
But as CorrelAid is constantly trying to expand its
open data and data for good efforts, links to other
data sources posted in the comments are very much appriciated.

## German Data

### Destatis 

A lot of official german statistical data is publically evailable
through the [statistics ministries](https://www.destatis.de/EN/Home/_node.html).
They also provide a SOAP and a RESTful API to get access to the data.
In order to simplify access to the data the [datenguide](https://datengui.de/) projects
provides systmatic access to the same data through a GraphQL API. Correlaid worked
with datenguide to create a [python clien](https://github.com/CorrelAid/datenguide-python)
and an [R client](https://github.com/CorrelAid/datenguideR) for the datenguide API.