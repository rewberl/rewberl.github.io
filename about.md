---
layout: page
title: About
order: 1
---
<!-- Source: http://www.randomsnippets.com/2011/04/10/how-to-hide-show-or-toggle-your-div-with-jquery/ -->
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"></script>
<script type="text/javascript">
function show(block) {
     $('.boxes').each(function(index) {
          if ($(this).attr("id") == block) {
               $(this).show(400);
          }
          else {
               $(this).hide(350);
          }
     });
}
function hide(block) {
     $('.boxes').hide(350);
}
</script>

<br>

## <a id="education-btn" href="javascript:show('boxes1');">Education</a><a id="education-open" href="javascript:show('boxes1');"><i class="fa fa-caret-square-o-down" style="float: right;"></i></a>

<div class="boxes" id="boxes1" markdown="block">
<table>
<tr><td><strong>Ph.D. Human Dimensions of Natural Resources</strong></td><td align="right"><em>In Progress</em></td></tr>
<tr><td><strong>Certificate in Data Analysis</strong></td><td align="right"><em>In Progress</em></td></tr>
<tr><td style="padding-left: 2rem;">Colorado State University, Fort Collins, CO</td><td></td></tr>
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
<tr><td style="padding-left: 2rem;">Washington State University, Pullman, WA</td><td></td></tr>
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
<tr><td style="padding-left: 2rem;">University of Delaware, Newark, DE</td><td></td></tr>
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

<a id="education-close" href="javascript:hide('boxes1');"><i class="fa fa-caret-square-o-up" style="float: right; font-size: 1.5rem; margin-bottom: .5rem;"></i></a>
</div>



## <a id="skills-btn" href="javascript:show('boxes2');">Skills</a><a id="skills-open" href="javascript:show('boxes2');"><i class="fa fa-caret-square-o-down" style="float: right;"></i></a>

<div class="boxes" id="boxes2" markdown="block">

<table>
<tr><td><strong>R</strong></td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></td></tr>
<tr><td colspan="2" style="padding-left: 2rem;">dplyr, tidyr, data.table, ggplot2, knitr (and many more!)</td></tr>
<tr><td><strong>Python</strong></td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td><strong>SQL</strong></td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td colspan="2"><strong>Other Languages</strong></td></tr>
<tr><td style="padding-left: 2rem;">HTML/CSS</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></td></tr>
<tr><td style="padding-left: 2rem;">Logo</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></td></tr>
<tr><td style="padding-left: 2rem;">Java</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">JavaScript</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td colspan="2"><strong>Tools</strong></td></tr>
<tr><td style="padding-left: 2rem;">CLI</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">Git</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">Photoshop</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></td></tr>
</table>

<a id="skills-close" href="javascript:hide('boxes2');"><i class="fa fa-caret-square-o-up" style="float: right; font-size: 1.5rem; margin-bottom: .5rem;"></i></a>
</div>


<!--
<a id="projects-btn" href="javascript:show('boxes3');"><h2>Projects</h2></a>

<div class="boxes" id="boxes3">

Biocultural Diversity in Ethiopia

</div>



Curriculum Vitae [icon]
-->
