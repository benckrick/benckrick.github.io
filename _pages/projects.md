---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
nav_order: 3
---

## Submitted Manuscripts 
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
The legitimacy of armed forces in the eyes of civilians is widely recognized as crucial for the success of counterinsurgency. However, the micro-determinants of ``military legitimacy" are poorly understood. We argue that perceptions of military legitimacy are shaped by two key dimensions of warfare: just cause and just conduct. Leveraging variation during the battle to liberate the Iraqi city of Mosul from the Islamic State, we evaluate our theory with an iterative mixed-methods design combining household survey data, satellite imagery, and interviews. Civilians living in neighborhoods where counterinsurgents' tactics and strategies reflected less concern for civilian protection view counterinsurgent forces as less legitimate than civilians elsewhere. These results persist after conditioning for personal experiences with harm, suggesting that perceptions are influenced not only by victimization---consistent with previous studies---but also by beliefs about the morality of armed forces' conduct and the cause for which they are fighting.
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


## In Progress 

**Refugee Repatriation and Conflict: Evidence from the Maximum Pressure Campaign** (with Christopher Blair, Austin Wright) 

**IDP Return and Social Cohesion: Evidence from Camp Closures in Iraq**

**The Determinants of Displacement: A Micro-Founded Global Analysis** (with Andrew Shaver, Teagan Zuniga) 
