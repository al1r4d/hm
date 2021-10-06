---
title: Pencarian
layout: default
permalink: /cari
---
<div id="search-container">
	<h2> Kolom Pencarian </h2>
	<p> Ketik apa yang ingin dicari </p>
<input type="text" id="search-input" placeholder="Ketik apa yang ingin dicari">
<ul id="results-container"></ul>
</div>

<!-- Script pointing to search-script.js -->
<script>
// @license magnet:?xt=urn:btih:d3d9a9a6595521f9666a5e94cc830dab83b65699&dn=expat.txt MIT
// @license-end
</script>
<script src="simple-jekyll-search.min.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
// @license magnet:?xt=urn:btih:d3d9a9a6595521f9666a5e94cc830dab83b65699&dn=expat.txt MIT
	SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: 'search.json'
})
// @license-end
</script>



