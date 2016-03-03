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

<div class="circular200 fa-pull-left" style="background-image: url(/public/img/profile_small.jpg); margin: 0rem 2rem 2rem 0rem;"></div>
<p><strong>I study the evolutionary origins and development of sociality, social learning, and social and cultural traits in humans, canids, and other non-human animal species.</strong> By integrating perspectives from animal behavior, evolutionary biology, and evolutionary cultural anthropology, I investigate the concept of cultural evolution in order to illuminate our own place in the natural world.</p>
<p style="text-indent: 2rem;">To this end, my research is presently focused on the experimental examination of the effects of <strong>cultural transmission biases</strong>. Past and ongoing projects include cross-cultural studies of the cognitive bases of <strong>social learning and culture</strong>, the social behavior and structure of <strong>gray wolves</strong> (<a href="http://eol.org/pages/328607/overview" target="_blank"><em>Canis lupus</em></a>) in captivity and in the wild, and the genetic, cultural, linguistic, and demographic history of the <strong>Chabu</strong>, an isolated group of hunter-gatherers in southwestern Ethiopia. I intend to apply this knowledge of cultural evolution and transmission processes to benefit threatened indigenous populations such as the Chabu and conserve biocultural diversity.</p>

<table style="margin: 1.5rem 0rem;">
<tr>
<td style="text-align: left;"><a href="/public/pdf/rewberl_cv.pdf" target="_blank"><i class="fa fa-file-pdf-o fa-lg"></i></a>
&nbsp;&nbsp;Curriculum Vitae</td>
<td style="text-align: right;"><a href="email.me" rel="nofollow" onclick="this.href='mailto:' + 'rewberl' + '@' + 'colostate' + '.' + 'edu'"><i class="fa fa-envelope-o fa-lg"></i></a>
&nbsp;&nbsp;rewberl <span class="avoidwrap"><i class="fa fa-at"></i> colostate <i class="fa fa-circle"></i> edu</span></td>
</tr>
</table>

## <a id="education-btn" href="javascript:show('boxes1');">Education</a><a id="education-open" href="javascript:show('boxes1');"><i class="fa fa-caret-square-o-down" style="float: right;"></i></a>

<div class="boxes" id="boxes1" markdown="block">
<table>
<tr><td><strong style="font-size: 1.25rem;">Ph.D. Human Dimensions of Natural Resources</strong></td><td style="text-align: right;"><span class="avoidwrap"><em>In Progress</em></span></td></tr>
<tr><td><strong style="font-size: 1.25rem;">Certificate in Data Analysis</strong></td><td style="text-align: right;"><span class="avoidwrap"><em>In Progress</em></span></td></tr>
<tr><td style="padding-left: 2rem;">Colorado State University, Fort Collins, CO</td><td></td></tr>
</table>

<h4>Relevant Coursework</h4>
<dl>
<dt><strong>Quantitative</strong></dt>
<dd>Linear Algebra; Design & Data Analysis I/II; Probability; Regression Models; Generalized Regression Models; Applied Bayesian Statistics; Statistical Learning & Data Mining</dd>
<dt><strong>Domain Expertise</strong></dt>
<dd>Anthropology & Sustainable Development</dd>
<dt><strong>Communication</strong></dt>
<dd>Citizen Science</dd>
</dl>


<br>
<table>
<tr><td><strong style="font-size: 1.25rem;">M.S. Zoology</strong></td><td style="text-align: right;">2015</td></tr>
<tr><td style="padding-left: 2rem;">Washington State University, Pullman, WA</td><td></td></tr>
</table>

<h4>Relevant Coursework</h4>
<dl>
<dt><strong>Quantitative</strong></dt>
<dd>Variance Designed Experiments; Statistical Programming with R; Agent-Based Models & Simulation</dd>
<dt><strong>Domain Expertise</strong></dt>
<dd>Population Genetics; Quantitative Genetics; Mathematical Genetics; Advanced Evolutionary Genetics; Evolutionary Ecology; Animal Behavior; Human Evolution; Evolutionary Cultural Anthropology</dd>
<dt><strong>Communication</strong></dt>
<dd>Teaching Practicum; Grant Writing</dd>
</dl>


<br>
<table>
<tr><td><strong style="font-size: 1.25rem;">B.A. Biological Sciences, Honors</strong></td><td style="text-align: right;">2009</td></tr>
<tr><td><strong style="font-size: 1.25rem;">B.A. Anthropology, Honors</strong></td><td style="text-align: right;">2009</td></tr>
<tr><td style="padding-left: 2rem;">University of Delaware, Newark, DE</td><td></td></tr>
</table>

<h4>Relevant Coursework</h4>
<dl>
<dt><strong>Quantitative</strong></dt>
<dd>Analytic Geometry & Calculus A/B; Statistical Methods I/II; Biological Data Analysis</dd>
<dt><strong>Domain Expertise</strong></dt>
<dd>Genetics & Evolutionary Biology; Population Ecology; Physical Anthropology; Social & Cultural Anthropology; Human Evolution; Human Nature; Psychology; Personality</dd>
<dt><strong>Communication</strong></dt>
<dd>Writing, Research & Presentation; Oral Communications</dd>
</dl>


<br>
<h3>Online Coursework</h3>
<dl>
<dt><strong>Data Science</strong></dt>
<dd>Data Scientist’s Toolbox; Getting & Cleaning Data; Exploratory Data Analysis; Reproducible Research (Johns Hopkins University)</dd>
<dt><strong>Python</strong></dt>
<dd>Google's Python Class (Google for Education); Python (Codecademy); R Programming (Johns Hopkins University); Programming for Everybody; Python Data Structures (University of Michigan); Interactive Programming in Python I (Rice University)</dd>
<dt><strong>Domain Expertise</strong></dt>
<dd>Genomic Technologies (Johns Hopkins University)</dd>
</dl>

<a id="education-close" href="javascript:hide('boxes1');"><i class="fa fa-caret-square-o-up" style="float: right; font-size: 1.5rem; margin-bottom: .5rem;"></i></a>
</div>



## <a id="skills-btn" href="javascript:show('boxes2');">Skills</a><a id="skills-open" href="javascript:show('boxes2');"><i class="fa fa-caret-square-o-down" style="float: right;"></i></a>

<div class="boxes" id="boxes2" markdown="block">

<table>
<tr><td><strong>R</strong></td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></td></tr>
<tr><td colspan="2" style="padding-left: 2rem;">dplyr; tidyr; data.table; ggplot2; knitr; sp; ape; ade4; adehabitat (and many more!)</td></tr>
<tr><td><strong>Python</strong></td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td colspan="2" style="padding-left: 2rem;">2.7; 3.x</td></tr>
<tr><td><strong>Databases</strong></td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td colspan="2" style="padding-left: 2rem;">MySQL; SQLite; PostgreSQL</td></tr>
<tr><td colspan="2"><strong>Other Languages</strong></td></tr>
<tr><td style="padding-left: 2rem;">HTML/CSS</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></td></tr>
<tr><td style="padding-left: 2rem;">Logo</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></td></tr>
<tr><td style="padding-left: 2rem;">Java</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">JavaScript</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td colspan="2"><strong>Other Analysis Tools</strong></td></tr>
<tr><td style="padding-left: 2rem;">MATLAB</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">SAS</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">SPSS</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">Minitab</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">JMP</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">Excel</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i></td></tr>
<tr><td colspan="2"><strong>Additional Tools</strong></td></tr>
<tr><td style="padding-left: 2rem;">CLI (Unix; Windows)</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">Markdown</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">LaTeX</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">Git</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">ArcGIS</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i></td></tr>
<tr><td style="padding-left: 2rem;">Photoshop</td><td style="text-align: right;"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></td></tr>
</table>

<!-- Add systematic key/legend for star meanings, e.g. basic functions, advanced tasks, "full-stack"? -->

<a id="skills-close" href="javascript:hide('boxes2');"><i class="fa fa-caret-square-o-up" style="float: right; font-size: 1.5rem; margin-bottom: .5rem;"></i></a>
</div>


<!--
<a id="projects-btn" href="javascript:show('boxes3');"><h2>Projects</h2></a>

<div class="boxes" id="boxes3">

Biocultural Diversity in Ethiopia

</div>



Curriculum Vitae [icon]
-->
