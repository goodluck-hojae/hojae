---
layout: about
title: about
permalink: /
subtitle: 

profile:
  align: right
  image: pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Amherst, Massachusetts</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  header nav.navbar.sticky-top {
    position: static !important;
    border-bottom: none !important;
    box-shadow: none !important;
  }

  #progress,
  .progress-container,
  .progress-bar {
    display: none !important;
  }

  .about-bio {
    font-size: 1.12rem;
    line-height: 1.75;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var cvLink = document.querySelector('#navbar a.nav-link[href$="/cv/"]');
    if (cvLink) {
      cvLink.setAttribute("href", "{{ '/assets/pdf/cv.pdf' | relative_url }}");
    }
  });
</script>

<div class="about-bio">
  <p>
    Hi, I'm Hojae Son, a Ph.D. candidate in Computer Science at UMass Amherst, advised by
    <a href="https://marcoserafini.github.io/" target="_blank" rel="noopener noreferrer">Professor Marco Serafini</a>.
    My research interests are in systems for machine learning, especially LLM inference, KV cache optimization,
    vector databases, and graph neural network systems.
  </p>
  <p>
    I am also a Research Computing Assistant for the
    <a href="https://unityhpc.org/" target="_blank" rel="noopener noreferrer">Unity Cluster</a> at the UMass Amherst Center for Data Science and Artificial Intelligence.
  </p>
  <p>Previously, I worked as a Research Engineer at Hyundai Mobis and lululab (Samsung C-Lab).</p>
</div>
