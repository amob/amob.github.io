---
title: Home
---

# Host-microbiome interactions under stress

This website is UNDER CONSTRUCTION. 
We seek to understand how evolution and ecology in host-microbiome interactions modify stress tolerance, and how stressors modify evolution and ecology of host-microbiome interactions

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

{% include banner.html image="images/Yellow Creek excerpt.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
New lab new duckweed collections.

{%
  include link.html
  link="publications"
  text="See what we've published"
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
New projects getting started. 

{%
  include link.html
  link="tools"
  text="See our repos on Github"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/HighPark Duckweed.jpg"
  link="resources"
  title="Resources for lab members"
  flip=true
  text=text
%}

{% capture text %}
See our laboratory agreement

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
  image="images/HighPark Duckweed.jpg"
  link="team"
  title="Our Team"
  text=text
%}

Team members