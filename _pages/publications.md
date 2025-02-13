---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---
**Civilian Harm and Military Legitimacy in War: Evidence from the Battle for Mosul in Iraq** (with Jonathan Petkun, Mara Revkin).  <br> 
Accepted. *International Organization*. <a href="https://ssrn.com/abstract=4633249" target="_blank"><i class="fa fa-fw fa-link" aria-hidden="true"></i></a>

<style>
  .toggle-button {
    background-color: transparent;
    color: #000;
    border: none;
    padding: 0;
    cursor: pointer;
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

  .abstract-container {
    margin-bottom: 20px;
  }
</style>
<div class="abstract-container">
  <div class="toggle-button" data-target="abstract-1">
    <span class="triangle"></span>
    <span>Abstract</span>
  </div>
  <div id="abstract-1" style="display: none;">
    The legitimacy of armed forces in the eyes of civilians is increasingly recognized as crucial not only for battlefield effectiveness but also for conflict resolution and peace-building. However, the micro-determinants of “military legitimacy” are poorly understood. We argue that perceptions of military legitimacy are shaped by two key dimensions of warfare: just cause and just conduct. Leveraging naturally occurring variation during one of the most deadly urban battles in recent history—the multi-national campaign to defeat the Islamic State in Mosul, Iraq—we evaluate our theory with a mixed-methods design combining original survey data, satellite imagery, and interviews. Civilians living in neighborhoods where armed forces were less careful to protect civilians view those forces as less legitimate than civilians elsewhere. Surprisingly, these results persist after conditioning on personal experiences with harm, suggesting that perceptions are influenced not only by victimization—consistent with previous studies—but also by beliefs about the morality of armed forces’ conduct and the cause for which they are fighting.
  </div>
</div>

**The Causes and Consequences of Refugee Flows: A Contemporary Re-Analysis** (with Andrew Shaver, et al.). <br> 2025. *American Political Science Review*, 119 (1): 526–534.  <a href="https://doi.org/10.1017/S0003055424000285" target="_blank"><i class="fa fa-fw fa-link" aria-hidden="true"></i></a><a href="/files/cc_final.pdf" target="_blank"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i></a><a href="/files/appendix_cc.pdf" target="_blank"><i class="fas fa-fw fa-paperclip" aria-hidden="true"></i></a><a href="https://doi.org/10.7910/DVN/JADOZL" target="_blank"><i class="fas fa-fw fa-code" aria-hidden="true"></i></a>

<div class="abstract-container">
  <div class="toggle-button" data-target="abstract-2">
    <span class="triangle"></span>
    <span>Abstract</span>
  </div>
  <div id="abstract-2" style="display: none;">
    The world faces a forcible displacement crisis. Tens of millions of individuals have been forced across international boundaries worldwide. Therefore, the causes and consequences of refugee flows are the subjects of significant social science inquiry. Unfortunately, the historical lack of reliable data on actual refugee flows, country-specific data reporting timelines, and more general pre-2000 data quality issues have significantly limited empirical inferences on these topics. We replicate twenty-eight articles on these topics using data newly released after a multi-year collaboration with the United Nations on annual dyadic flows. We observe major inconsistencies between the newly released flow numbers and the stock-based flow estimates upon which decades of research are based; we also find widespread inappropriate treatment of missing historical values. When we replicate the existing literature using the newly introduced flow data, correcting the treatment of missing historical values, and temporally extending/restricting the study periods, we produce significantly different results.
  </div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var toggleButtons = document.querySelectorAll(".toggle-button");
    toggleButtons.forEach(function(button) {
      button.addEventListener("click", function() {
        var targetId = button.getAttribute("data-target");
        var abstract = document.getElementById(targetId);
        var isActive = button.classList.contains("active");
        
        if (!isActive) {
          abstract.style.display = "block";
          button.classList.add("active");
        } else {
          abstract.style.display = "none";
          button.classList.remove("active");
        }
      });
    });
  });
</script>

