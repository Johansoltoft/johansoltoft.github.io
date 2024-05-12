---
permalink: /
title: "Blog wall"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Base styles for all devices */
  .responsive-div {
    flex-basis: 48%; /* initially set to take almost half of the row */
    max-width: 48%; /* aligns with flex-basis */
    box-sizing: border-box; /* includes padding and border in the element's total width and height */
    padding: 10px; /* space inside the div */
    margin-bottom: 20px; /* extra space at the bottom of each div */
  }

  img {
    width: 100%; /* makes images responsive */
    height: auto; /* maintains aspect ratio */
  }

  h2 {
    font-size: 18px; /* suitable font size for desktop */
    font-weight: normal; /* normal font weight */
    color: #333; /* dark gray color for text */
  }

  /* Styles for devices with a max-width of 768px (tablets and mobile phones) */
  @media (max-width: 768px) {
    .responsive-div {
      flex-basis: 100%; /* each div takes full width of the viewport */
      max-width: 100%; /* aligns with flex-basis */
      padding: 15px; /* slightly larger padding */
    }

    h2 {
      font-size: 16px; /* reduced font size for better space utilization on smaller screens */
    }
  }

  /* Additional styles for handling device orientation */
  @media (max-width: 768px) and (orientation: landscape) {
    .responsive-div {
      flex-basis: 50%; /* in landscape, each div takes about half the width */
      max-width: 50%; /* aligns with flex-basis */
    }

    h2 {
      font-size: 18px; /* restores larger font size for landscape orientation */
    }
  }
</style>

<div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <div class="responsive-div">
    <a href="https://johansoltoft.github.io//publications/2010-10-01-paper-title-number-2.md/">
      <img src="/images/EPIC-computationelANTRO.png" alt="Diagram Computational Anthropology" style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">Article: Friction by Machine: How to Slow Down Reasoning with Computational Methods</h2>
  </div>
  
  <div style="flex: 1 1 48%; max-width: 48%; box-sizing: border-box; padding: 10px;">
    <a href="https://johansoltoft.github.io//publications/2015-10-01-paper-title-number-4.md/">
      <img src="/images/Bellyofthemonster.gif" alt="'In the Belly of the Monster' Controversy Surrounding AI in Audio-Visual Media"     style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">"In the Belly of the Monster": Blogpost-Controversy Surrounding AI in Audio-Visual Media</h2>
  </div>
  
  <div style="flex: 1 1 48%; max-width: 48%; box-sizing: border-box; padding: 10px;">
    <a href="https://johansoltoft.github.io//talks/2012-03-01-talk-9">
      <img src="/images/D&D.png" alt="Collaborative Storytelling" style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">MASSHINE: Unravelling Collaborative Storytelling with Generative AI</h2>
  </div>
  
  <div style="flex: 1 1 48%; max-width: 48%; box-sizing: border-box; padding: 10px;">
    <a href="https://johansoltoft.github.io//talks/2012-03-01-talk-7">
      <img src="/images/Syn-politicans.png" alt="Synthetic Politicians" style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">MASSHINE: Interfacing with Synthetic Mundane Politicians</h2>
  </div>
  
  <div style="flex: 1 1 48%; max-width: 48%; box-sizing: border-box; padding: 10px;">
    <a href="https://johansoltoft.github.io//talks/2012-03-01-talk-1">
      <img src="/images/Epic2-646.jpg" alt="Conference" style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">EPIC2023: Friction by Machine</h2>
  </div>
  
  <div style="flex: 1 1 48%; max-width: 48%; box-sizing: border-box; padding: 10px;">
    <a href="https://johansoltoft.github.io//publications/2015-10-01-paper-title-number-3.md/">
      <img src="/images/twitchnetwork.png" alt="Twitch Emote Network" style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">Blogpost: Studying Community Detection Using Twitch Emotes</h2>
  </div>
  
  <div style="flex: 1 1 48%; max-width: 48%; box-sizing: border-box; padding: 10px;">
    <a href="https://johansoltoft.github.io//publications/2015-10-01-paper-title-number-3.md/">
      <img src="/images/a1a4033a-e5ea-494a-a06f-7b8bde5c1a81.gif" alt="Natmus Network" style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">Blogpost: Studying how the discussion regarding the Danish National Museum evolves over time on Twitter</h2>
  </div>
  
  <div style="flex: 1 1 48%; max-width: 48%; box-sizing: border-box; padding: 10px;">
    <a href="https://johansoltoft.github.io//talks/2014-03-01-talk-3">
      <img src="/images/NordicSTS.jpg" alt="NordicSTS" style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">NordicSTS: Creatively Acceptable AI</h2>
  </div>
  
  <div style="flex: 1 1 48%; max-width: 48%; box-sizing: border-box; padding: 10px;">
    <a href="https://johansoltoft.github.io//publications/2009-10-01-paper-title-number-1.md/">
      <img src="/images/dataimaga.png" alt="Data Imagination Diagram" style="width: 100%; height: auto;">
    </a>
    <h2 style="font-size: 18px; font-weight: normal; color: #333;">Blogpost: Strengthening the data-imagination of SMEs</h2>
  </div>

</div>

