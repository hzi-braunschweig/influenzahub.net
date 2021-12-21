---
title: "Shortcode Test"
date: 2021-12-07
disable_date: true
menu:
  main:
    weight: 7
data:
---

This is a test menu item showcasing the fetchapi shortcode:

<!-- For search term, all special characters must be URL encoded. Spaces may be replaced by '+' signs. -->

<!-- Articles retrieved is the total number of articles from the PubMed input set to be retrieved, up to a maximum of 10,000 -->

<!-- The two parameters (mindate, maxdate) must be used together to specify an arbitrary date range. The general date format is YYYY/MM/DD, and these variants are also allowed: YYYY, YYYY/MM. -->

<!-- Api Docs: https://www.ncbi.nlm.nih.gov/books/NBK25499/  -->

{{< fetchapi searchterm="influenza" articlesretrieved="2" mindate="2021/11" maxdate="2021/11" >}}
