# Feed Policy and Procedures

In the past it was unclear how to add or remove feeds from blogs.openstreetmap.org; who to ask, what was relevant, who could make changes. This document aims to bring clarity to what should be included, and how changes are made.

The configuration file that contains the list of feeds currently used is [planet.ini](planet.ini)

## Relevant feeds

The aggregator should contain articles from blogs that are relevant to the OpenStreetMap community.

* For personal blogs, we prefer feeds for OpenStreetMap categories or tags, rather than full blogs which can contain a wide variety of subjects
* We prefer feeds which include the full text of the blog posts rather than just the top section/summary.
* We will include Organisation feeds only if a majority of their posts are of interest to mappers, rather than posts about products that contain OpenStreetMap functionality.
* We will consider removing feeds if less than 30% of their recent entries are related to OpenStreetMap.
* We will remove feeds if a domain is no longer relevant to the OpenStreetMap community
* We prefer Atom feeds instead of RSS feeds, given the choice

## Proposing changes

If you want to add a feed, you should open an Issue on this repository. You should provide:

* The name for the blog (usually the name of the person)
* A link to the blog
* A link to the Atom or RSS feed for the blog

If you prefer, you can help us by creating a Pull Request containing the relevant changes to [planet.ini](planet.ini)

If the feed meets the criteria above, it will be added.

If you want to remove a feed, please open an Issue or make a Pull Request describing the change you want to make.
