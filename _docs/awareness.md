---
layout: default
title: Awareness Diary
---

<h1 class="h3 mb-2 text-gray-800">Charts</h1>
<p class="mb-4">Chart.js is a third party plugin that is used to generate the charts in this theme. The charts below have been customized - for further customization options, please visit the <a target="_blank" href="https://www.chartjs.org/docs/latest/">official Chart.js documentation</a>.</p>


<div class="row">
{% include charts/bar.html title="Total Revenue" width=12 labels="January,February,March,April,May,June" datasets="Revenue:4215,5312,6251,7841,9821,14984," currency="true" %}
</div>

<div class="row">
{% include cards/bars.html title="Projects" data="Server Migration,20,danger|Sales Tracking,40,warning|Payout Details,80,info|Account Setup,100,success" width=12 %}
</div>
