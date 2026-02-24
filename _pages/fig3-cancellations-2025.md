---
layout: single
title: "Cancellations 2025"
permalink: /fig3-cancellations-2025/
author_profile: true
---

<div id="map-container" style="width:100%; overflow:hidden;">
  <iframe id="map-iframe" src="/files/webpages/fig3_cancellations_2025.html" scrolling="no" style="border:none; width:1100px; height:650px; transform-origin:0 0;"></iframe>
</div>

<script>
function scaleMap() {
  var container = document.getElementById('map-container');
  var iframe = document.getElementById('map-iframe');
  var scale = container.offsetWidth / 1100;
  if (scale > 1) scale = 1;
  iframe.style.transform = 'scale(' + scale + ')';
  container.style.height = (650 * scale) + 'px';
}
window.addEventListener('load', scaleMap);
window.addEventListener('resize', scaleMap);
</script>
