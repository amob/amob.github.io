---
title: Home
---

# Host-microbiome interactions under stress

We are the O'Brien lab.

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

{% include banner.html image="images/Yellow Creek Duckweed.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
New lab new duckweed collections.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/HighPark Duckweed.jpg"
  link="research"
  title="Our Research"
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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

Team members