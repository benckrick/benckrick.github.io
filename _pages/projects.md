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
    How does refugee return shape conflict in migrants' destination communities? We argue that conditions inducing repatriation bear critically on the consequences of return. When refugees return because of worsening conditions in host countries, they are often marginalized and destitute. In this setting, mass return risks amplifying conflict in returnee-receiving communities. We test this theory leveraging the Trump administration's sudden reimposition of sanctions on Iran in 2018. These "Maximum Pressure" sanctions decimated the Iranian economy and spurred mass return of Afghan refugees from Iran. Exploiting historical returnee settlement patterns and the plausibly exogenous timing of the sanctions, we estimate the causal effect of large-scale refugee repatriation on violence. We find that the returnee influx increased insurgent violence in returnees' destination communities. We find suggestive evidence for an opportunity cost mechanism. Sanctions-induced currency depreciation reduced household incomes in returnee-receiving areas, lowering reservation wages and driving up insurgent recruitment. We also find evidence that Iran retaliated against the sanctions by escalating support for Afghan insurgent factions. While insurgent violence increased in repatriation communities, there was no effect on communal conflict.
  </div>
</div>

**IDP Return and Social Cohesion: Evidence from Camp Closures in Iraq**
<a href="https://doi.org/10.33774/apsa-2025-lwnpc" target="_blank"><i class="fa fa-fw fa-link" aria-hidden="true"></i></a>

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
  <div class="toggle-button" data-target="abstract-2">
    <span class="triangle"></span>
    <span>Abstract</span>
  </div>
  <div id="abstract-2" style="display: none;">
After the resolution of a civil conflict, how does the return of the internally displaced population (IDPs) impact social cohesion? Little attention has been paid to the consequences of IDP return, despite extensive research on the causes and effects of displacement. I investigate this question in Iraq after the defeat of the Islamic State. Coercive and unexpected camp closures by the Iraqi federal government starting in July 2019 forced hundreds of thousands of internal migrants to return. The exogenous timing of the closure campaign provides a unique setting to estimate a plausibly causal effect of return. Leveraging village-level displacement data, community assessments, respondent-level surveys, and qualitative fieldwork, I find that the closure-induced returns frayed social cohesion. My theory provides a critical mechanism underpinning this relationship: return creates communal tensions by inducing feelings of fear and suspicion. These findings hold significant policy implications, as the approach of post-conflict governments to address internal migration profoundly influences the social legacy of civil conflicts.
  </div>
</div>


## works in progress 

**Authoritarian Nostalgia Unpacked: The Reflective and Restorative Divide in Iraqi Kurdistan** (with Stephanie Wright) 

**The Moral Economy of of Authoritarian Nostalgia: How Institutional Betrayal Erodes Collective Memory**

**Institutionalizing Memory: A Natural Experiment in Transitional Justice Education**


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

