---
title: Home
---

# Host-microbiome interactions under stress

How does the environment shape the outcome of adaptation in species interactions? 
How do species interactions shape adaptation to stressful environments? 
We study the interplay of stressors and microbiomes in shaping plant local adaptation and phenotypes.
<!-- 
{%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
 -->
 
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/Yellow Creek excerpt.png" %}

{% include section.html %}

# Highlights

{% capture text %}
Browse our research.

{%
  include link.html
  link="research"
  text="See summarized research directions"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include link.html
  link="publications"
  text="Or browse what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/HighPark Duckweed.jpg"
  link="publications"
  title="Our Publications"
  text=text
%}

{% capture text %}
Check out what has been happening 

{%
  include link.html
  link="blog"
  text="Browse our recent posts"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/Putah Creek Tangled Bank Duckweed.jpg"
  link="blog"
  title="Browse our recent posts"
  flip=true
  text=text
%}


{% capture text %}
We are a new and growing team.

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/cyanobacteria-on-lemna-frond-underside.jpg"
  link="team"
  title="Our Team"
  text=text
%}

