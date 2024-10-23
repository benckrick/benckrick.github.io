---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---
**The Causes and Consequences of Refugee Flows: A Contemporary Re-Analysis** (with Andrew Shaver, et al.) <br>Forthcoming. *American Political Science Review* <a href="https://doi.org/10.1017/S0003055424000285" target="_blank"><i class="fa fa-fw fa-link" aria-hidden="true"></i></a><a href="/files/cc_final.pdf" target="_blank"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i></a><a href="/files/appendix_cc.pdf" target="_blank"><i class="fas fa-fw fa-paperclip" aria-hidden="true"></i></a><a href="https://doi.org/10.7910/DVN/JADOZL" target="_blank"><i class="fas fa-fw fa-code" aria-hidden="true"></i></a>

<style>
  #abstract {
    display: none;
  }

  .toggle-button {
    background-color: transparent;
    color: #000;
    border: none;
    padding: 0;
    cursor: pointer;
    margin-bottom: 10px; /* Added spacing */
  }

  .triangle {
    width: 0;
    height: 0;
    border-top: 5px solid transparent;
    border-bottom: 5px solid transparent;
    border-left: 8px solid #000;
    display: inline-block;
    margin-right: 5px;
    transform: rotate(0deg);
    transition: transform 0.3s;
  }

  .toggle-button.active .triangle {
    transform: rotate(90deg);
  }

  .button-container {
    display: inline-block;
    vertical-align: top;
  }
</style>
<div class="button-container">
  <div class="toggle-button">
    <span class="triangle"></span>
    <span>Abstract</span>
  </div>
  <div id="abstract">
    The world faces a forcible displacement crisis. Tens of millions of individuals have been forced across international boundaries worldwide. Therefore, the causes and consequences of refugee flows are the subjects of significant social science inquiry. Unfortunately, the historical lack of reliable data on actual refugee flows, country-specific data reporting timelines, and more general pre-2000 data quality issues have significantly limited empirical inferences on these topics. We replicate twenty-eight articles on these topics using data newly released after a multi-year collaboration with the United Nations on annual dyadic flows. We observe major inconsistencies between the newly released flow numbers and the stock-based flow estimates upon which decades of research are based; we also find widespread inappropriate treatment of missing historical values. When we replicate the existing literature using the newly introduced flow data, correcting the treatment of missing historical values, and temporally extending/restricting the study periods, we produce significantly different results.
  </div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var toggleButton = document.querySelector(".toggle-button");
    var abstract = document.getElementById("abstract");

    toggleButton.addEventListener("click", function() {
      var isActive = toggleButton.classList.contains("active");
      if (!isActive) {
        abstract.style.display = "block";
        toggleButton.classList.add("active");
      } else {
        abstract.style.display = "none";
        toggleButton.classList.remove("active");
      }
    });
  });
</script>
