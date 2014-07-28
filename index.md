---
layout: default
title: Erik Olsen
---

<img src="/assets/erik_ute.jpg" style="float: right;  width: 200px;  padding:0px 0px 0px 5px;"/>

## About Erik 


I'm a principal scientist at <a href="http://www.imr.no">Institute of Marine Research, Norway, </a> and currently working as a visiting scientist at <a href="http://nefsc.noaa.gov"> NOAA Northeast Fisheries Science Center</a> in Woods Hole MA, USA.</br> </br>
My background is as a marine mammal biologist (PhD in 2002), but I have since 2002 been  developing ecosystem-based science and management (EBM) through leading the Barents Sea ecosystem surveys ('05-'07) and contributing to the Norwegian Integrated Management plans for the Lofoten - Barents Sea ('06), the Norwegian Sea ('09) and the Skagerrak - North Sea ('13). </br></br>
Developing ecosystem-based marine spatial planning (MSP) has been a cornerstone of my research since 2002 and has broadened my field of view. Successful ecosystem-based management requires comprehensive and relevant science and quantitative tools (eg. Ecosystem model - <a href="http://www.csiro.au/organisation-structure/divisions/marine--atmospheric-research/atlantis-ecosystem-model"> Atlantis </a>), as well as comprehensive and relevant governance. Understanding the interactions between the socio-cultural-economic system on one hand and the ecological science needed to support sound management is at the core of my current research. 
 


### Research areas:

#### Ecosystem models 
<li> Skill assessment of the Northeast US Atlantis model </li>
<li> Spatial scenarios (eg. MSP - wind farms) using the Atlantis model </li>
<li> Simulating  pollution events in ecosystem models </li>
<li> Developing <a href="https://github.com/cddesjardins/R4Atlantis"> R4Atlantis </a> R-statistics package for interacting with Atlantis input and output


#### Governance and advice
<li> The science base of EBM and MSP </li>
<li> Role of experts and models in EBM </li>
<li> Importance of culture in marine governance </li>

#### Oil spill assessments and risk
<li> Effects of spatial variability in survival on oil spill risk assessments</li>
<li> Communication of risks of oil spills </li>
</br>

### Publications & pictures 

<li><a href="http://scholar.google.no/citations?user=JbTaBZkAAAAJ">GoogleScholar listed publications </a> </li>
<li><a href="https://www.flickr.com/photos/90745523@N06/"> Flicker photo stream  </a> </li>
</br>




<div id="home">
  <h1>Blog Posts</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>