---
layout: single
title: "Capacity Projection 2030"
permalink: /fig2-capacity-projection-2030/
author_profile: true
---

<div id="map-container" style="width:100%; overflow:hidden;">
  <iframe id="map-iframe" src="/files/webpages/fig2_capacity_projection_2030.html" scrolling="no" style="border:none; width:700px; height:600px; transform-origin:0 0;"></iframe>
</div>

<script>
function scaleMap() {
  var container = document.getElementById('map-container');
  var iframe = document.getElementById('map-iframe');
  var scale = container.offsetWidth / 700;
  if (scale > 1) scale = 1;
  iframe.style.transform = 'scale(' + scale + ')';
  container.style.height = (600 * scale) + 'px';
}
window.addEventListener('load', scaleMap);
window.addEventListener('resize', scaleMap);
</script>
