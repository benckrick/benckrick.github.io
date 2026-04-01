---
layout: page
permalink: /teaching/
title: teaching
description: 
nav: true
nav_order: 6
---

In graduate school, I have developed as both a researcher and a teacher—two professional capacities that mutually reinforce one another. At Duke, I have served as a teaching assistant and completed Duke’s [Certificate in College Teaching](https://gradschool.duke.edu/professional-development/programs/certificate-college-teaching/), which included over 40 hours of structured pedagogy training as well as peer feedback and supervision. I am guided by the belief that education should spark intellectual curiosity and equip students with the skills to thrive both inside and beyond the classroom. You can find my full teaching statement <a href="/files/Teaching_Statement.pdf" target="_blank">here</a>.

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

## discussion section instructor

**Introduction to International Relations**  
*Fall 2024*  
Instructor: Kyle Beardsley  

<div class="abstract-container">
  <div class="toggle-button" data-target="abstract-1">
    <span class="triangle"></span>
    <span>Course Description</span>
  </div>
  <div id="abstract-1" style="display:none;">
This course introduces students to the study of international relations. It is designed both for students taking a single course in the field and for those seeking a foundation for further study. The course has four goals: (1) to provide students with concepts and ideas needed to address the core question of IR—what causes international war and what conditions promote peace; (2) to develop a basic understanding of international political economy; (3) to examine emerging global policy challenges; and (4) to develop foundational skills for independent research in political science.
  </div>
</div>

**American Foreign Policy**  
*Spring 2024*  
Instructor: Peter Feaver  

<div class="abstract-container">
  <div class="toggle-button" data-target="abstract-2">
    <span class="triangle"></span>
    <span>Course Description</span>
  </div>
  <div id="abstract-2" style="display:none;">
This course helps students become informed observers—and potentially participants—in American foreign policy. It examines the historical evolution of U.S. foreign policy and the challenges facing policymakers today. The course is organized in four parts: (1) broad forces shaping foreign policy decisions, including the international balance of power, ideas, and domestic political structures; (2) domestic institutions and societal influences on foreign policy decision-making; (3) the tools of statecraft—intelligence, diplomacy, economic statecraft, and military force—and when they are most effective; and (4) contemporary foreign policy challenges facing the United States.
  </div>
</div>

## teaching assistant

**Introduction to Political Attitudes, Groups, and Behavior**  
*Fall 2025*  
Instructor: Shikhar Singh  

<div class="abstract-container">
  <div class="toggle-button" data-target="abstract-3">
    <span class="triangle"></span>
    <span>Course Description</span>
  </div>
  <div id="abstract-3" style="display:none;">
Why do group identities become politically salient, and how do they shape political attitudes and behavior? This course examines ethnicity, religion, partisanship, race, and place-based identities in democracies around the world. The semester proceeds in four parts: conceptualizing political groups and behavior; measuring group attitudes and behavior; understanding why certain identities become politically salient; and examining how these identities influence political participation, policy preferences, social trust, and discrimination.
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


