---
layout: post
title: "An operational view of Elasticsearch"
speaker: "Guillaume Lederrey"
slides: ""
date: 2019-01-2318:30:00
---

How to scale Elasticsearch to the size of Wikipedias

If you have not entirely sold your soul to Google, you might have noticed a search box on the top right corner of [Wikipedias](https://en.wikipedia.org/w/index.php?search=search&title=Special%3ASearch&go=Go&fulltext=1). You might have even wondered at what's behind it. Spoiler: it's Elasticsearch.

Guillaume is going to give an overview of how full text search works for Wikipedias. You will learn what it takes to make Elasticsearch work for a top 5 website in 200 > langages. From the basic principles of full text search, to the scalability issues of a large site, with stop in how to design a resilient search cluster.

#### Speaker

After a few years working for various industries in Switzerland, Guillaume decided it was time to redeem his karma. He is now working for Wikimedia Foundation (Imagine a world in which every single human being can freely share in the sum of all knowledge. [That’s our commitment](https://wikimediafoundation.org/about/vision/)). His current work is focused on Site Reliability Engineering for [Search](https://wikitech.wikimedia.org/wiki/Search), [Maps](https://wikitech.wikimedia.org/wiki/Maps) and [Wikidata Query Service](https://wikitech.wikimedia.org/wiki/Wikidata_query_service).