---
layout: page
title: Search
permalink: /search/
---

<input type="text" id="search-input" placeholder="Search...">
<ul id="results-container"></ul>

<script src="/assets/js/simple-jekyll-search.min.js"></script>
<script>
  SimpleJekyllSearch({
    searchInput: document.getElementById('search-input'),
    resultsContainer: document.getElementById('results-container'),
    json: '/search.json'
  })
</script>
