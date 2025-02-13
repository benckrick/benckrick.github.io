---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
nav_order: 3
---

## submitted manuscripts 
**Refugee Repatriation and Conflict: Evidence from the Maximum Pressure Campaign** (with Christopher Blair, Austin Wright) 
<a href="https://esoc.princeton.edu/wp39" target="_blank"><i class="fa fa-fw fa-link" aria-hidden="true"></i></a>

<div class="abstract-container">
  <div class="toggle-button" data-target="abstract-2">
    <span class="triangle"></span>
    <span>Abstract</span>
  </div>
  <div id="abstract-2" style="display: none;">
    How does refugee return shape conflict in migrants' destination communities? We argue that conditions inducing repatriation bear critically on the consequences of return. When refugees return because of worsening conditions in host countries, they are often marginalized and destitute. In this setting, mass return risks amplifying conflict in returnee-receiving communities. We test this theory leveraging the Trump administration's sudden reimposition of sanctions on Iran in 2018. These "Maximum Pressure" sanctions decimated the Iranian economy and spurred mass return of Afghan refugees from Iran. Exploiting historical returnee settlement patterns and the plausibly exogenous timing of the sanctions, we estimate the causal effect of large-scale refugee repatriation on violence. We find that the returnee influx increased insurgent violence in returnees' destination communities. We find suggestive evidence for an opportunity cost mechanism. Sanctions-induced currency depreciation reduced household incomes in returnee-receiving areas, lowering reservation wages and driving up insurgent recruitment. We also find evidence that Iran retaliated against the sanctions by escalating support for Afghan insurgent factions. While insurgent violence increased in repatriation communities, there was no effect on communal conflict.
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

<style>
  /* Style for the triangle */
  .triangle {
    width: 0;
    height: 0;
    border-left: 5px solid transparent;
    border-right: 5px solid transparent;
    border-bottom: 10px solid black;
    display: inline-block;
    margin-right: 10px;
    transition: transform 0.3s ease;
  }

  /* Rotate triangle when the abstract is expanded */
  .toggle-button.active .triangle {
    transform: rotate(180deg);
  }
</style>




## works in progress 

**IDP Return and Social Cohesion: Evidence from Camp Closures in Iraq**

**The Determinants of Displacement: A Micro-Founded Global Analysis** (with Andrew Shaver, Teagan Zuniga) 
