---
title: "Publications"
permalink: /publications/
---

**The Causes and Consequences of Refugee Flows: A Contemporary Re-Analysis** (with Andrew Shaver, et al.) 
<br>Conditionally Accepted. *American Political Science Review*
<!--* Referenced in [The Economist](https://www.economist.com/graphic-detail/2022/03/30/how-the-war-in-ukraine-compares-to-other-refugee-crises)-->
<!-- abstract dropdown?; otherwise just add another button -->

<style>
  #abstract {
    display: none;
  }

  #toggleButton {
    background-color: transparent; /* Transparent background */
    color: #000; /* Black text color */
    border: none;
    padding: 0; /* Remove padding */
    cursor: pointer;
  }

  #triangle {
    width: 0;
    height: 0;
    border-left: 5px solid transparent; /* Adjust the size of the triangle */
    border-right: 5px solid transparent;
    border-bottom: 8px solid #000; /* Solid black triangle */
    display: inline-block;
    margin-left: 5px; /* Adjust the spacing between text and triangle */
  }
</style>

<button id="toggleButton">
  Show Abstract
  <span id="triangle"></span> <!-- Triangle icon -->
</button>
<div id="abstract">
The world faces a forcible displacement crisis. Tens of millions of individuals have been forced across international boundaries worldwide. Therefore, the causes and consequences of refugee flows are the subjects of significant social science inquiry. Unfortunately, the historical lack of reliable data on actual refugee flows, country-specific data reporting timelines, and more general pre-2000 data quality issues have significantly limited empirical inferences on these topics. We replicate twenty-eight articles on these topics using data newly released after a multi-year collaboration with the United Nations on annual dyadic flows. We observe major inconsistencies between the newly released flow numbers and the stock-based flow estimates upon which decades of research are based; we also find widespread inappropriate treatment of missing historical values. When we replicate the existing literature using the newly introduced flow data, correcting the treatment of missing historical values, and temporally extending/restricting the study periods, we produce significantly different results.
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var button = document.getElementById("toggleButton");
    var abstract = document.getElementById("abstract");
    var triangle = document.getElementById("triangle");

    button.addEventListener("click", function() {
      if (abstract.style.display === "none" || abstract.style.display === "") {
        abstract.style.display = "block";
        button.textContent = "Hide Abstract";
        triangle.style.borderTop = "8px solid #000"; /* Rotate triangle to point up */
      } else {
        abstract.style.display = "none";
        button.textContent = "Abstract";
        triangle.style.borderTop = "0"; /* Rotate triangle to point down */
      }
    });
  });
</script>

[Preprint](http://esoc.princeton.edu/wp29){: .btn--research}
<!-- Below will make nice buttons for publications link: can make "abstract" "article" and "preprint" -->
<!-- [Article](http://esoc.princeton.edu/wp29){: .btn--research} -->
<!-- [Prepint](http://esoc.princeton.edu/wp29){: .btn--research} -->
<!-- [Appendix](http://esoc.princeton.edu/wp29){: .btn--research} -->
<!-- [Replication](http://esoc.princeton.edu/wp29){: .btn--research} -->

<!--Full Citation -->
