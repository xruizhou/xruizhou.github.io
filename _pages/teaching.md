---
layout: single
title: "Teaching"
permalink: /teaching/
author_profile: true
---

<style>
.toggle-button {
  float: right;
  padding: 6px 12px;
  font-size: 14px;
  color: white;
  background-color: #007bff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  transition: background-color 0.2s ease;
  margin-bottom: 1em;
}

.toggle-button:hover {
  background-color: #0056b3;
}
</style>

<div style="overflow: auto;">
  <button onclick="toggleAll()" id="toggleButton" class="toggle-button">Show All</button>
</div>

### Graduate Student Instructor, University of Michigan

<a href="javascript:void(0);" onclick="toggleContent('econ435')" style="font-weight:bold; color:#007bff; text-decoration:none;">
ECON 435: Financial Economics (with Prof. Toni Whited, 2024 Winter)
</a>  
<div id="econ435" class="course-desc" style="display:none; margin: 0.5em 0 1em 1em;">
Upper-level undergraduate course on the economic analysis of financial markets and financial decision making. Asset pricing theory, net present value, arbitrage strategies, portfolio management, and financial market behavior. Case studies of current policy. Led review sessions and assisted with exam preparation.
</div>

<a href="javascript:void(0);" onclick="toggleContent('econ101')" style="font-weight:bold; color:#007bff; text-decoration:none;">
ECON 101: Principles of Economics (Head GSI, 2021–2023 Fall)
</a>  
<div id="econ101" class="course-desc" style="display:none; margin: 0.5em 0 1em 1em;">
Introductory economics course covering microeconomic fundamentals (how markets function, where markets fail, the distribution of income and wealth, the public sector, international trade). Responsibilities included running discussion sections, designing problem sets and exams, and bridging communication between students and instructors.
</div>

---

### Teaching Assistant, Renmin University of China

<a href="javascript:void(0);" onclick="toggleContent('econmetrics')" style="font-weight:bold; color:#007bff; text-decoration:none;">
Intermediate Econometrics (2019 Fall)
</a>  
<div id="econmetrics" class="course-desc" style="display:none; margin: 0.5em 0 1em 1em;">
An upper-level undergraduate course centered on understanding the “why” behind econometric techniques through theoretical derivation and statistical proof. Students rigorously derive the properties of estimators and apply these methods to real-world data using Stata, integrating formal theory with hands-on empirical analysis.
</div>

---

<script>
function toggleContent(id) {
  var content = document.getElementById(id);
  content.style.display = content.style.display === "none" ? "block" : "none";
}

let allShown = false;
function toggleAll() {
  const items = document.querySelectorAll('.course-desc');
  items.forEach(div => {
    div.style.display = allShown ? "none" : "block";
  });
  document.getElementById("toggleButton").innerText = allShown ? "Show All" : "Hide All";
  allShown = !allShown;
}
</script>
