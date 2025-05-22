---
layout: archive
permalink: /
title: "Posts"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<meta property="og:title" content="Johan Irving Søltoft" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://johansoltoft.github.io/" />
<meta property="og:image" content="https://johansoltoft.github.io/images/Bellyofthemonster.gif" />
<meta property="og:description" content="Blog" />

<style>
  /* Base styles for all devices */
  .container, .site-content {
    width: 100%;
    max-width: 100% !important;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin: 0;
    padding: 0 20px; /* Optional: Add some padding */
    box-sizing: border-box;
  }

  .responsive-div {
    flex: 1 1 50%;
    max-width: 50%;
    box-sizing: border-box;
    padding: 10px;
    margin-bottom: 20px;
  }

  .large-div {
    flex: 1 1 100%;
    max-width: 100%;
    box-sizing: border-box;
    padding: 10px;
    margin-bottom: 20px;
  }

  .small-image {
    width: 50%;
    height: auto;
    display: block;
    margin: 0 auto 20px auto; /* Center align the image and add bottom margin */
  }

  img {
    width: 100%;
    height: auto;
  }

  h2 {
    font-size: 18px;
    font-weight: normal;
    color: #333;
  }

  /* Styles for devices with a max-width of 768px (tablets and mobile phones) */
  @media (max-width: 768px) {
    .responsive-div, .large-div {
      flex: 1 1 100%;
      max-width: 100%;
    }

    h2 {
      font-size: 16px;
    }

    .small-image {
      width: 75%; /* Make the image larger on smaller screens */
    }
  }

  /* Styles for the filter buttons */
  .filter-buttons {
    text-align: center;
    margin-bottom: 20px;
    font-family: Helvetica, Arial, sans-serif;
  }

  .filter-button {
    padding: 10px 20px;
    margin: 0 10px;
    cursor: pointer;
    background-color: white;
    color: #666666;
    border: 2px solid #666666;
    border-radius: 5px;
    font-family: Helvetica, Arial, sans-serif;
    transition: background-color 0.3s, color 0.3s;
  }

  .filter-button:hover {
    background-color: #666666;
    color: white;
  }
</style>

<div class="filter-buttons">
  <button class="filter-button" onclick="filterPosts('All')">All</button>
  <button class="filter-button" onclick="filterPosts('Article')">Articles</button>
  <button class="filter-button" onclick="filterPosts('Conference')">Conferences</button>
  <button class="filter-button" onclick="filterPosts('Blogpost')">Blogposts</button>
  <button class="filter-button" onclick="filterPosts('Workshop')">Workshops</button>
</div>

<div class="container">

  <div class="responsive-div post" data-category="Article">
    <a href="https://johansoltoft.github.io/publications/Recalcitrant-audiencing.md/">
      <img src="/images/Recalcitrant-audiencing.png" alt="Recalcitrant-audiencing">
    </a>
    <h2>Article: Recalcitrant audiencing: Between analytics and creative practice in the film industry</h2>
  </div>
  
   <div class="responsive-div post" data-category="Article">
    <a href="">
      <img src="/images/Datafantasi2.png" alt="datafantasi">
    </a>
    <h2>Book Chapter: Datafantasi: Fra styring til læring i en verden af vilde problemer</h2>
  </div>
  
  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io/publications/Danish-Tech-Museum.md/">
      <img src="/images/map2.gif" alt="Grounding-AI">
    </a>
    <h2>Exhibition: Danish Technological Museum: Grounding AI</h2>
  </div>
  
  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/publications/Text-Unit-Tool.md/">
      <img src="/images/TUT-johan.jpg" alt="Grounding-AI">
    </a>
    <h2>Conference: Text Unit Tool (TUT): An open-source tool for archiving and exploration of large-scale text data</h2>
  </div>
  
   <div class="responsive-div post" data-category="Blogpost">
    <a href="https://grounding-ai.github.io/web-application/">
      <img src="/images/grounding-AI2.png" alt="Grounding-AI">
    </a>
    <h2>Website: Grounding AI - AI Atlas of AI</h2>
  </div>
  
  <div class="responsive-div post" data-category="Article">
    <a href="https://johansoltoft.github.io/publications/2010-10-01-paper-title-number-18.md/">
      <img src="/images/Synthetic-Interlocutors.png" alt="Synthetic-I">
    </a>
    <h2>Article: Synthetic Interlocutors</h2>
  </div>
  
  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-17.md/">
      <img src="/images/ISA-1.JPG" alt="ISA">
    </a>
    <h2>Conference: From digital methods to computationel methods</h2>
  </div>
  
  <div class="responsive-div post" data-category="Workshop">
    <a href="https://johansoltoft.github.io/publications/experimenting-with-large-scale-ethnographic-data.md/">
      <img src="/images/Workshop-1-Etno.jpg" alt="Workshop-etno">
    </a>
    <h2>Workshop: Experimenting With Large-Scale Ethnographic Data</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-15.md/">
      <img src="/images/EASA2024.jpg" alt="EASA">
    </a>
    <h2>Conference: Speculating with generative AI</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-14.md/">
      <img src="/images/EASTS4s.jpg" alt="EASST/4s">
    </a>
    <h2>Conference: The human in audience-centered film production</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-11.md/">
      <img src="/images/AIasCitizen.png" alt="AIasCitizen.png">
    </a>
    <h2>Conference: AI as citizens?</h2>
  </div>

  <div class="responsive-div post" data-category="Article">
    <a href="https://johansoltoft.github.io/publications/2010-10-01-paper-title-number-2.md/">
      <img src="/images/EPIC-computationelANTRO.png" alt="Diagram Computational Anthropology">
    </a>
    <h2>Article: Friction by Machine: How to Slow Down Reasoning with Computational Methods</h2>
  </div>

  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-4.md/">
      <img src="/images/Bellyofthemonster.gif" alt="'In the Belly of the Monster' Controversy Surrounding AI in Audio-Visual Media">
    </a>
    <h2>Blogpost: "In the Belly of the Monster" Controversy Surrounding AI in Audio-Visual Media</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-9">
      <img src="/images/D&D.png" alt="Collaborative Storytelling">
    </a>
    <h2>Conference: Unravelling Collaborative Storytelling with Generative AI</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-7">
      <img src="/images/Syn-politicans.png" alt="Synthetic Politicians">
    </a>
    <h2>Conference: Interfacing with Synthetic Mundane Politicians</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-10">
      <img src="/images/MASSHINE-syn.jpg" alt="SyntheticFiLM">
    </a>
    <h2>Conference: Exploring Cinematic Engagement through a Synthetic AI Film Lover</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-1">
      <img src="/images/Epic2-646.jpg" alt="Conference">
    </a>
    <h2>Conference: Friction by Machine</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/talks/2014-02-01-talk-2">
      <img src="/images/EPIC1.jpg" alt="Epic10">
    </a>
    <h2>Conference: Audience Awareness Through Machine Anthropology</h2>
  </div>

  <div class="responsive-div post" data-category="Workshop">
    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-6.md/">
      <img src="/images/MASSHINE-retreat1.jpg" alt="Dragør retreat Generative Ethnographic AI">
    </a>
    <h2>Workshop: Dragør retreat Generative Ethnographic AI</h2>
  </div>

  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-3.md/">
      <img src="/images/twitchnetwork.png" alt="Twitch Emote Network">
    </a>
    <h2>Blogpost: Studying Community Detection Using Twitch Emotes</h2>
  </div>

  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-5.md/">
      <img src="/images/a1a4033a-e5ea-494a-a06f-7b8bde5c1a81.gif" alt="Natmus Network">
    </a>
    <h2>Blogpost: Studying how the discussion regarding the Danish National Museum evolves over time on Twitter</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/talks/2014-03-01-talk-3">
      <img src="/images/NordicSTS.jpg" alt="NordicSTS">
    </a>
    <h2>Conference: Creatively Acceptable AI</h2>
  </div>

  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-1.md/">
      <img src="/images/dataimaga.png" alt="Data Imagination Diagram">
    </a>
    <h2>Blogpost: Strengthening the data-imagination of SMEs</h2>
  </div>

  <div class="responsive-div post" data-category="Workshop">
    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-4">
      <img src="/images/bertistheword(1).png" alt="Bert is the word">
    </a>
    <h2>Workshop: BERT is the word</h2>
  </div>
</div>


<script>
  function filterPosts(category) {
    const posts = document.querySelectorAll('.post');
    posts.forEach(post => {
      if (category === 'All' || post.dataset.category === category) {
        post.style.display = 'block';
      } else {
        post.style.display = 'none';
      }
    });
  }
</script>
