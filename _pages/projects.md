---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
nav_order: 3
---

## submitted manuscripts 
**Civilian Harm and Military Legitimacy in War: Evidence from the Battle for Mosul in Iraq** (with Jonathan Petkun, Mara Revkin) <a href="https://ssrn.com/abstract=4633249" target="_blank"><i class="fa fa-fw fa-link" aria-hidden="true"></i></a>

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
</style>
<div class="toggle-button">
  <span class="triangle"></span>
  <span>Abstract</span>
</div>
<div id="abstract">
The legitimacy of armed forces in the eyes of civilians is increasingly recognized as crucial not only for battlefield effectiveness but also for conflict resolution and peace-building. However, the micro-determinants of “military legitimacy” are poorly understood. We argue that perceptions of military legitimacy are shaped by two key dimensions of warfare: just cause and just conduct. Leveraging naturally occurring variation during one of the most deadly urban battles in recent history—the multi-national campaign to defeat the Islamic State in Mosul, Iraq—we evaluate our theory with a mixed-methods design combining original survey data, satellite imagery, and interviews. Civilians living in neighborhoods where armed forces were less careful to protect civilians view those forces as less legitimate than civilians elsewhere. Surprisingly, these results persist after conditioning on personal experiences with harm, suggesting that perceptions are influenced not only by victimization—consistent with previous studies—but also by beliefs about the morality of armed forces’ conduct and the cause for which they are fighting.
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


## works in progress 

**Refugee Repatriation and Conflict: Evidence from the Maximum Pressure Campaign** (with Christopher Blair, Austin Wright) 

**IDP Return and Social Cohesion: Evidence from Camp Closures in Iraq**

**The Determinants of Displacement: A Micro-Founded Global Analysis** (with Andrew Shaver, Teagan Zuniga) 
