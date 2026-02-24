---
layout: single
title: "Annual Additions & Retirements"
permalink: /fig1-annual-additions-retirements/
author_profile: true
---

<div id="map-container" style="width:100%; overflow:hidden;">
  <iframe id="map-iframe" src="/files/webpages/fig1_annual_additions_retirements.html" scrolling="no" style="border:none; width:1200px; height:600px; transform-origin:0 0;"></iframe>
</div>

<script>
function scaleMap() {
  var container = document.getElementById('map-container');
  var iframe = document.getElementById('map-iframe');
  var scale = container.offsetWidth / 1200;
  if (scale > 1) scale = 1;
  iframe.style.transform = 'scale(' + scale + ')';
  container.style.height = (600 * scale) + 'px';
}
window.addEventListener('load', scaleMap);
window.addEventListener('resize', scaleMap);
</script>
