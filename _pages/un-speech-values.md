---
layout: page
title: Schwartz Values in United Nations Speeches
permalink: /un-speech-values/
nav: false
sitemap: false
---

<style>
  #un-speech-app {
    display: block;
    width: 100%;
    height: 1600px;
    border: 0;
  }
</style>

<iframe id="un-speech-app" title="Schwartz Values in United Nations Speeches"></iframe>

<script>
  // The app lives on shinyapps.io. It follows this site's light/dark switch
  // and reports its height, so it shows without a second scroll bar.
  (function () {
    var appAddress = "https://sharifian.shinyapps.io";
    var frame = document.getElementById("un-speech-app");

    function siteTheme() {
      return document.documentElement.getAttribute("data-theme") === "dark" ? "dark" : "light";
    }

    frame.src = appAddress + "/un-speech-values/?embed=1&theme=" + siteTheme();

    new MutationObserver(function () {
      frame.contentWindow.postMessage({ siteTheme: siteTheme() }, appAddress);
    }).observe(document.documentElement, { attributes: true, attributeFilter: ["data-theme"] });

    window.addEventListener("message", function (e) {
      if (e.origin !== appAddress || !e.data || !e.data.appHeight) return;
      frame.style.height = e.data.appHeight + "px";
    });
  })();
</script>
