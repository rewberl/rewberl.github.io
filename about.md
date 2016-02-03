---
layout: page
title: About
order: 1
---
<!-- Source: http://www.randomsnippets.com/2011/04/10/how-to-hide-show-or-toggle-your-div-with-jquery/ -->
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"></script>
<script type="text/javascript">
function show(thechosenone) {
     $('.boxes').each(function(index) {
          if ($(this).attr("id") == thechosenone) {
               $(this).show(400);
          }
          else {
               $(this).hide(400);
          }
     });
}
</script>

---

<a id="education-btn" href="javascript:show('boxes1');"><h2>Education</h2></a>

<div class="boxes" id="boxes1">

<table>
<tr><td><strong>Ph.D. Human Dimensions of Natural Resources</strong></td><td align="right"><em>In Progress</em></td></tr>
<tr><td><strong>Certificate in Data Analysis</strong></td><td align="right"><em>In Progress</em></td></tr>
<tr><td style="padding-left: 2rem";>Colorado State University, Fort Collins, CO</td><td></td></tr>
</table>

<h5>Relevant Coursework</h5>
<dl style="font-size: 0.8rem;">
<dt><strong>Quantitative</strong></dt>
<dd>Linear Algebra; Design & Data Analysis I/II; Probability; Regression Models; Generalized Regression Models; Applied Bayesian Statistics; Statistical Learning & Data Mining</dd>
<dt><strong>Domain Expertise</strong></dt>
<dd>Anthropology & Sustainable Development</dd>
<dt><strong>Communication</strong></dt>
<dd>Citizen Science</dd>
</dl>


<br>
<table>
<tr><td><strong>M.S. Zoology</strong></td><td align="right">2015</td></tr>
<tr><td style="padding-left: 2rem";>Washington State University, Pullman, WA</td><td></td></tr>
</table>

<h5>Relevant Coursework</h5>
<dl style="font-size: 0.8rem;">
<dt><strong>Quantitative</strong></dt>
<dd>Variance Designed Experiments; Statistical Programming with R; Agent-Based Models & Simulation</dd>
<dt><strong>Domain Expertise</strong></dt>
<dd>Population Genetics; Quantitative Genetics; Mathematical Genetics; Advanced Evolutionary Genetics; Evolutionary Ecology; Animal Behavior; Human Evolution; Evolutionary Cultural Anthropology</dd>
<dt><strong>Communication</strong></dt>
<dd>Teaching Practicum; Grant Writing</dd>
</dl>


<br>
<table>
<tr><td><strong>B.A. Biological Sciences, Honors</strong></td><td align="right">2009</td></tr>
<tr><td><strong>B.A. Anthropology, Honors</strong></td><td align="right">2009</td></tr>
<tr><td style="padding-left: 2rem";>University of Delaware, Newark, DE</td><td></td></tr>
</table>

<h5>Relevant Coursework</h5>
<dl style="font-size: 0.8rem;">
<dt><strong>Quantitative</strong></dt>
<dd>Analytic Geometry & Calculus A/B; Statistical Methods I/II; Biological Data Analysis</dd>
<dt><strong>Domain Expertise</strong></dt>
<dd>Genetics & Evolutionary Biology; Population Ecology; Physical Anthropology; Social & Cultural Anthropology; Human Evolution; Human Nature; Psychology</dd>
<dt><strong>Communication</strong></dt>
<dd>Writing, Research & Presentation; Oral Communications</dd>
</dl>

</div>


<!--
<a id="skills-btn" href="javascript:show('boxes2');"><h2>Skills</h2></a>

<div class="boxes" id="boxes2">

R dplyr, tidyr, ggplot2
Python
Other Languages HTML/CSS, NetLogo
Tools CLI, Git

</div>



<a id="projects-btn" href="javascript:show('boxes3');"><h2>Projects</h2></a>

<div class="boxes" id="boxes3">

Biocultural Diversity in Ethiopia

</div>



Curriculum Vitae [icon]
-->
