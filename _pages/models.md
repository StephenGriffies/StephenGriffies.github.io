---
layout: single 
permalink: /models/
author_profile: true
author: Stephen Griffies
title: "Ocean Circulation Models"
toc: true
toc_label: "On this page"
toc_icon: "sun"
excerpt: "Maths + Physics + Computers = Simulations"
header:
  overlay_color: "#000"
  overlay_image: /assets/images/Southern_ocean_speed_cropped.png
  caption: "Surface current speed in the Southern Ocean from CM2.6 (courtesy A. Morrison)"
---

#  <center> Philosophy + Aims </center>

<p align="justify">

Ocean circulation models are a repository for mechanistic theories of
how the ocean works, with numerical methods used to transform
mathematical expressions of the theories into a computational tool for
scientific investigations.  Physical theories and numerical methods
provide the foundation for ocean circulation models.  The practice of
ocean modeling uses models as an experimental tool to help reveal
mechanisms for patterns of ocean phenomena emerging from the governing
equations.  Models and modeling form the two pillars of numerical and
theoretical oceanography, with these pillars supported by, and in turn
supporting, observational oceanography and laboratory studies.

<br>
<br>

Throughout my career I have endeavored to bring rigor and synthesis to
the many intellectual strands comprising the foundations of ocean
models and forming the practice of ocean modeling.  This work has
spanned nearly all areas of ocean and climate science, from ocean
model algorithms and code development, climate model development,
theoretical studies into subgrid scale parameterizations, and
formulations of experimental protocols supporting the systematic
analysis of model intercomparison projects.  This page summarizes some
of this work, and offers pointers for where research can bring further
insights.

</p>


# <center> Science of Models </center>

<p align="justify">

The science going into ocean models includes theories for how the
ocean works (e.g., the equations of motion including subgrid scale
parameterizations) and numerical methods for discretizing the
mathematical equations. This section outlines areas where I have
contributed to this science.

</p>


## <center>Model Foundations</center>

<p align="justify">

As part of my work on ocean models foundations, I have offered both
novel methods and syntheses across a number of methods.  Here are
samples from this work.

<ul>

<li>Developmenets in Ocean Climate Modelling:
<a href="/assets/pdfs/WGOMD_review_paper.pdf">Griffies
  et al (2000) </a>
</li>

<li>Spurious diapycnal mixing associated with advection in a
z-coordinate ocean model: <a
href="https://journals.ametsoc.org/doi/10.1175/1520-0493%282000%29128%3C0538%3ASDMAWA%3E2.0.CO%3B2">Griffies,
Pacanowski, and Hallberg (2000) </a> </li>

<li>Tracer conservation with an explicit free surface method for
z-coordinate ocean models: <a
href="https://journals.ametsoc.org/doi/10.1175/1520-0493%282001%29129%3C1081%3ATCWAEF%3E2.0.CO%3B2">Griffies
et al (2001) </a> </li>

<li>Fundamentals of Ocean Climate Models (book):
<a href="https://press.princeton.edu/titles/7797.html">Griffies (2005) </a>
</li>

<li>Formulation of an ocean model for global climate simulations: <a
href="https://www.ocean-sci.net/1/45/2005/">Griffies et al (2005) </a>
</li>

<li>Formulating the equations of an ocean model: <a
href="/assets/pdfs/CH18_griffies_adcroft.pdf">Griffies and Adcroft (2008) </a>
</li>

<li>Science of Ocean Climate Models: <a
href="/assets/pdfs/Griffies_Encyclopedia_of_Ocean_Science.pdf">
Griffies (2009) </a>
</li>
  
<li>Problems and Prospects in Large-Scale Ocean Circulation Models: <a
href="http://www.oceanobs09.net/proceedings/cwp/Griffies-OceanObs09.cwp.38.pdf">
Griffies et al (2010) </a>
</li>
  
<li>Ocean circulation models and modelling: <a
href="https://www.elsevier.com/books/ocean-circulation-and-climate/siedler/978-0-12-391851-2">
Griffies and Treguier (2013) </a>
</li>

<li>Vertical resolution of baroclinic modes in global ocean models: <a
href="">
Stewart et al (2017) </a>
</li>


Vertical resolution of baroclinic modes in global ocean models


</ul>

</p>


## <center> Parameterizations </center>

<p align="justify">

The ocean eddy parameterization problem (aka the turbulence closure
problem) remains among the most important and intellectually
challenging problems in theoretical physical oceanography. It is
important since eddy parameterizations, from the planetary boundary
layer to the ocean interior to the bottom boundary layer, have a huge
role in determining the performance of ocean climate models.  It is
challenging since it draws upon a wide variety of physical and
mathematical skill sets. I have an ongoing interest in ocean eddy
parameterization questions, and am particularly motivated by some
exciting theoretical/modeling and observational studies conducted
during recent years.  Notably, there are many unsolved questions
looking for energetic students and post-docs to crack!

<ul>

<li>Isoneutral diffusion in a z-coordinate ocean model: 
<a
  href="https://journals.ametsoc.org/doi/full/10.1175/1520-0485%281998%29028%3C0805%3AIDIAZC%3E2.0.CO%3B2">Griffies
  et al. (1998) </a>
</li>

<li>The Gent-McWilliams skew flux:
<a
  href="https://journals.ametsoc.org/doi/full/10.1175/1520-0485%281998%29028%3C0831%3ATGMSF%3E2.0.CO%3B2">Griffies
  (1998) </a>
</li>

<li>Biharmonic friction with a Smagorinsky-like viscosity for use in large-scale eddy-permitting ocean models:
<a
  href="https://journals.ametsoc.org/doi/full/10.1175/1520-0493%282000%29128%3C2935%3ABFWASL%3E2.0.CO%3B2">Griffies
  and Hallberg  (2000) </a>
</li>

<li>A boundary-value problem for the parameterized mesoscale eddy transport:
<a
  href="https://www.sciencedirect.com/science/article/pii/S1463500310000065">Ferrari,
  Griffies, Nurser, and Vallis (2010) </a>
  </li>

<li>On geometrical aspects of interior ocean mixing: 
<a href="https://journals.ametsoc.org/doi/abs/10.1175/JPO-D-13-0270.1">
  McDougall, Groeskamp, and Griffies  (2014) </a>
  </li>

<li>Impacts of parameterized Langmuir turbulence and non-breaking
waves on global climate simulations: <a
href="https://journals.ametsoc.org/doi/10.1175/JCLI-D-13-00583.1"> Fan
and Griffies (2014) </a> </li>
  
<li>The KPP boundary layer scheme for the ocean: revisiting its
formulation and benchmarking one-dimensional simulations relative to
LES: 
<a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2018MS001336">Van
  Roekel et al (2018) </a>
  </li>

</ul>

</p>

## <center>Modular Ocean Model (MOM)</center>

<p align="justify">

During the years 1997-2013, much of my working day consisted of
developing MOM versions 3,4, and 5.  This work remains among the more
satisfying of my career. Although I stopped focusing on development
after <a href="https://mom-ocean.github.io/"> MOM5</a> in early 2013,
I remain engaged in a variety of scientific activities that make use
of this code, most notably the <a href="http://cosima.org.au/"> COSIMA
(Consortium for Ocean-Sea Ice Modelling in Australia)</a> and the <a
href="/research/"> CM2.6 project.</a> Both projects pursue studies of
global climate at model resolutions that admit a rich field of
mesoscale eddies.

<br> <br>

More recent efforts of ocean code development at GFDL center on <a
href="https://github.com/NOAA-GFDL/MOM6"> MOM6,</a> which is a project
led by Alistair Adcroft and Robert Hallberg.  My role in MOM6 has
largely focused on its diagnostic capabilities, with much work
remaining on my plate.  Quite generally, MOM6 offers many
sophisticated features beyond MOM5, thus providing modelers with
critical tools needed to address a number of high profile climate
related questions such as sea level rise and ocean heat uptake.

</p>


# <center> Science of Modeling</center>

<p align="justify">

When handed a model, the modeler must decide how to use it for
revealing phenomena (e.g., waves, turbulence, boundary currents,
overturning circulations, climate variations) emerging from the
fundamental equations. Questions thus arise surrounding how to design
a numerical experiment that is reproducible by others who may wish to
compare/contrast their model's results. And when simulation results
are obtained, questions then arise concerning how to rationalize the
output through analysis and interpretation. Here I summarize areas
where my research efforts have contributed to help answer these
questions.

</p>

## <center> CORE/OMIP</center>

<p align="justify">

Global ocean/sea-ice models are commonly used to help understand the
mechanics for ocean climate variations and to directly compare to
observations. In the absence of an interactive atmospheric model, the
modeler must make decisions for how to force the ocean/sea-ice model
in a way that does not compromise on the scientific investigation.

<br>
<br>

During the period from 2000 to 2009, I worked with colleagues on the
CLIVAR Working Group for Ocean Model Development <a
href="http://www.clivar.org/clivar-panels/omdp"> </a>, now called the
<a href="http://www.clivar.org/clivar-panels/omdp"> Ocean Model
Development Panel (OMDP),</a> to develop an experimental protocol for
running global ocean/sea-ice models.  This protocol is known as the <a
href="http://www.clivar.org/omdp/core"> Coordinated Ocean-sea ice
Reference Experiments (CORE).</a> The CORE protocol has become a
community standard, thus forming the basis for the <a
href="https://www.wcrp-climate.org/modelling-wgcm-mip-catalogue/cmip6-endorsed-mips-article/1063-modelling-cmip6-omip">
Ocean Model Intercomparison Project (OMIP) </a> ongoing as part of CMIP6.

<ul>

<li>Coordinated Ocean-ice Reference Experiments (COREs): <a
href="https://www.sciencedirect.com/science/article/pii/S1463500308001182">Griffies
et al (2009) </a> </li>

<li>OMIP contribution to CMIP6: experimental and diagnostic protocol
for the physical component of the Ocean Model Intercomparison Project:
<a href="https://www.geosci-model-dev.net/9/3231/2016/">Griffies et al
(2016) </a> </li>

</ul>

</p>

## <center>Analysis methods</center>

<p align="justify">

Given a robust model, a sensible experimental design, and sufficient
computing, one then moves onto questions about how to rationalize the
output from the simulation.  This task brings us back to fundamentals,
with the associated analysis confronting us with very basic questions
about the underlying fluid mechanics.  Here are some papers that
develop a suite of analysis methods, some of which are of use for
analyzing data from both models and  observations.

<ul>

<li>Physical processes that impact the evolution of global mean sea
level in ocean climate models: <a
href="https://www.sciencedirect.com/science/article/pii/S1463500312000637">Griffies
and Greatbatch (2012) </a> </li>

<li>The deep ocean buoyancy budget and its temporal variability: <a
href="https://journals.ametsoc.org/doi/10.1175/JCLI-D-13-00016.1">Palter,
Griffies, et al (2013) </a> </li>

<li>Lagrangian ocean analysis: fundamentals and practices: <a
href="https://www.sciencedirect.com/science/article/pii/S1463500317301853">van Sebille, Griffies, et al
(2018) </a> </li>

<li>The water mass transformation framework for ocean physics and
biogeochemistry: <a
href="https://www.annualreviews.org/doi/abs/10.1146/annurev-marine-010318-095421">Groeskamp,
Griffies, et al (2019) </a> </li>

</ul>


</p>











