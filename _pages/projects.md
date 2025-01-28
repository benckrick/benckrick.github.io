---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
nav_order: 3
---

## submitted manuscripts 
**Civilian Harm and Military Legitimacy in War: Evidence from the Battle for Mosul in Iraq** (with Jonathan Petkun, Mara Revkin) 
<a href="https://ssrn.com/abstract=4633249" target="_blank"><i class="fa fa-fw fa-link" aria-hidden="true"></i></a>

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
    margin-bottom: 20px; /* Space after the button */
  }
</style>
<div class="abstract-container">
  <div class="toggle-button" id="toggle-abstract-1">
    <span class="triangle"></span>
    <span>Abstract</span>
  </div>
  <div id="abstract-1" style="display: none;">
    The legitimacy of armed forces in the eyes of civilians is increasingly recognized as crucial not only for battlefield effectiveness but also for conflict resolution and peace-building. However, the micro-determinants of “military legitimacy” are poorly understood. We argue that perceptions of military legitimacy are shaped by two key dimensions of warfare: just cause and just conduct. Leveraging naturally occurring variation during one of the most deadly urban battles in recent history—the multi-national campaign to defeat the Islamic State in Mosul, Iraq—we evaluate our theory with a mixed-methods design combining original survey data, satellite imagery, and interviews. Civilians living in neighborhoods where armed forces were less careful to protect civilians view those forces as less legitimate than civilians elsewhere. Surprisingly, these results persist after conditioning on personal experiences with harm, suggesting that perceptions are influenced not only by victimization—consistent with previous studies—but also by beliefs about the morality of armed forces’ conduct and the cause for which they are fighting.
  </div>
</div>

**Refugee Repatriation and Conflict: Evidence from the Maximum Pressure Campaign** (with Christopher Blair, Austin Wright) 
<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5081898" target="_blank"><i class="fa fa-fw fa-link" aria-hidden="true"></i></a>

<div class="abstract-container">
  <div class="toggle-button" id="toggle-abstract-2">
    <span class="triangle"></span>
    <span>Abstract</span>
  </div>
  <div id="abstract-2" style="display: none;">
    How does refugee return shape conflict in migrants' destination communities? We argue that conditions inducing repatriation bear critically on the consequences of return. When refugees return because of worsening conditions in host countries, they are often marginalized and destitute. In this setting, mass return risks amplifying conflict in returnee-receiving communities. We test this theory leveraging the Trump administration's sudden reimposition of sanctions on Iran in 2018. These "Maximum Pressure" sanctions decimated the Iranian economy and spurred mass return of Afghan refugees from Iran. Exploiting historical returnee settlement patterns and the plausibly exogenous timing of the sanctions, we estimate the causal effect of large-scale refugee repatriation on violence. We find that the returnee influx increased insurgent violence in returnees' destination communities. We find suggestive evidence for an opportunity cost mechanism. Sanctions-induced currency depreciation reduced household incomes in returnee-receiving areas, lowering reservation wages and driving up insurgent recruitment. We also find evidence that Iran retaliated against the sanctions by escalating support for Afghan insurgent factions. While insurgent violence increased in repatriation communities, there was no effect on communal conflict.
  </div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var toggleButton1 = document.getElementById("toggle-abstract-1");
    var abstract1 = document.getElementById("abstract-1");

    toggleButton1.addEventListener("click", function() {
      var isActive = toggleButton1.classList.contains("active");
      if (!isActive) {
        abstract1.style.display = "block";
        toggleButton1.classList.add("active");
      } else {
        abstract1.style.display = "none";
        toggleButton1.classList.remove("active");
      }
    });

    var toggleButton2 = document.getElementById("toggle-abstract-2");
    var abstract2 = document.getElementById("abstract-2");

    toggleButton2.addEventListener("click", function() {
      var isActive = toggleButton2.classList.contains("active");
      if (!isActive) {
        abstract2.style.display = "block";
        toggleButton2.classList.add("active");
      } else {
        abstract2.style.display = "none";
        toggleButton2.classList.remove("active");
      }
    });
  });
</script>


## works in progress 

**IDP Return and Social Cohesion: Evidence from Camp Closures in Iraq**

**The Determinants of Displacement: A Micro-Founded Global Analysis** (with Andrew Shaver, Teagan Zuniga) 
