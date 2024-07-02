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

<!-- SVG Network Graph -->
<div class="large-div">
  <svg width="800" height="800" xmlns="http://www.w3.org/2000/svg">
    <style>
      .project { fill: skyblue; }
      .person { fill: lightgreen; }
      .edge { stroke: black; stroke-width: 1.5; }
      text { font-family: Arial, sans-serif; font-size: 12px; }
    </style>
    
    <!-- Nodes -->
    <circle cx="400" cy="50" r="20" class="project" id="AI_as_citizens"/>
    <text x="370" y="50" fill="black">AI as citizens</text>
    
    <circle cx="600" cy="150" r="20" class="project" id="Friction_by_Machine"/>
    <text x="620" y="150" fill="black">Friction by Machine</text>
    
    <circle cx="200" cy="150" r="20" class="project" id="Controversy_AI_in_Audio-Visual_Media"/>
    <text x="20" y="150" fill="black">Controversy AI in Audio-Visual Media</text>
    
    <circle cx="400" cy="250" r="20" class="project" id="From_Dice_to_Data"/>
    <text x="420" y="250" fill="black">From Dice to Data</text>
    
    <circle cx="600" cy="350" r="20" class="project" id="Synthetic_politicians"/>
    <text x="620" y="350" fill="black">Synthetic politicians</text>
    
    <circle cx="200" cy="350" r="20" class="project" id="Synthetic_AI_Film_Lover"/>
    <text x="20" y="350" fill="black">Synthetic AI Film Lover</text>
    
    <circle cx="400" cy="450" r="20" class="project" id="Generative_Ethnographic_AI"/>
    <text x="420" y="450" fill="black">Generative Ethnographic AI</text>
    
    <circle cx="600" cy="550" r="20" class="project" id="Strengthening_the_data_imagination_of_SMEs"/>
    <text x="620" y="550" fill="black">Strengthening the data-imagination of SMEs</text>
  
    <circle cx="300" cy="550" r="15" class="person" id="Johan_Irving_Søltoft"/>
    <text x="315" y="550" fill="black">Johan Irving Søltoft</text>
    
    <circle cx="500" cy="650" r="15" class="person" id="Brit_Winthereik"/>
    <text x="515" y="650" fill="black">Brit Winthereik</text>
    
    <circle cx="200" cy="650" r="15" class="person" id="Anders_Munk"/>
    <text x="215" y="650" fill="black">Anders Munk</text>
    
    <circle cx="400" cy="750" r="15" class="person" id="Anders_Koed_Madsen"/>
    <text x="415" y="750" fill="black">Anders Koed Madsen</text>
    
    <circle cx="100" cy="750" r="15" class="person" id="Morten_Heuser"/>
    <text x="115" y="750" fill="black">Morten Heuser</text>
    
    <circle cx="600" cy="750" r="15" class="person" id="Roman_Jurowetzki"/>
    <text x="615" y="750" fill="black">Roman Jurowetzki</text>
    
    <circle cx="200" cy="850" r="15" class="person" id="Daniel_Hain"/>
    <text x="215" y="850" fill="black">Daniel Hain</text>
    
    <circle cx="400" cy="850" r="15" class="person" id="Torben_Elgaard_Jensen"/>
    <text x="415" y="850" fill="black">Torben Elgaard Jensen</text>
    
    <circle cx="600" cy="850" r="15" class="person" id="Mathieu_Jacomy"/>
    <text x="615" y="850" fill="black">Mathieu Jacomy</text>
    
    <circle cx="100" cy="950" r="15" class="person" id="Laura_Kocksch"/>
    <text x="115" y="950" fill="black">Laura Kocksch</text>
    
    <circle cx="300" cy="950" r="15" class="person" id="Rikke_Ørngreen"/>
    <text x="315" y="950" fill="black">Rikke Ørngreen</text>
    
    <circle cx="500" cy="950" r="15" class="person" id="Helene_Husted_Hansen"/>
    <text x="515" y="950" fill="black">Helene Husted Hansen</text>
    
    <circle cx="200" cy="1050" r="15" class="person" id="Asger_Gehrt_Olesen"/>
    <text x="215" y="1050" fill="black">Asger Gehrt Olesen</text>
    
    <circle cx="400" cy="1050" r="15" class="person" id="Sara_Paasch_Knudsen"/>
    <text x="415" y="1050" fill="black">Sara Paasch Knudsen</text>
    
    <!-- Edges -->
    <line x1="400" y1="50" x2="300" y2="550" class="edge"/>
    <line x1="400" y1="50" x2="500" y2="650" class="edge"/>
    <line x1="400" y1="50" x2="200" y2="650" class="edge"/>
    
    <line x1="600" y1="150" x2="300" y2="550" class="edge"/>
    <line x1="600" y1="150" x2="400" y2="750" class="edge"/>
    <line x1="600" y1="150" x2="200" y2="650" class="edge"/>
    
    <line x1="200" y1="150" x2="300" y2="550" class="edge"/>
    
    <line x1="400" y1="250" x2="300" y2="550" class="edge"/>
    <line x1="400" y1="250" x2="100" y2="750" class="edge"/>
    
    <line x1="600" y1="350" x2="300" y2="550" class="edge"/>
    <line x1="600" y1="350" x2="400" y2="750" class="edge"/>
    
    <line x1="200" y1="350" x2="300" y2="550" class="edge"/>
    
    <line x1="400" y1="450" x2="300" y2="550" class="edge"/>
    <line x1="400" y1="450" x2="400" y2="750" class="edge"/>
    <line x1="400" y1="450" x2="200" y2="650" class="edge"/>
    <line x1="400" y1="450" x2="600" y2="750" class="edge"/>
    <line x1="400" y1="450" x2="200" y2="850" class="edge"/>
    <line x1="400" y1="450" x2="400" y2="850" class="edge"/>
    <line x1="400" y1="450" x2="600" y2="850" class="edge"/>
    <line x1="400" y1="450" x2="100" y2="950" class="edge"/>
    
    <line x1="600" y1="550" x2="300" y2="950" class="edge"/>
    <line x1="600" y1="550" x2="200" y2="650" class="edge"/>
    <line x1="600" y1="550" x2="600" y2="850" class="edge"/>
    <line x1="600" y1="550" x2="500" y2="950" class="edge"/>
    <line x1="600" y1="550" x2="200" y2="1050" class="edge"/>
    <line x1="600" y1="550" x2="300" y2="550" class="edge"/>
    <line x1="600" y1="550" x2="400" y2="1050" class="edge"/>
  </svg>
</div>

<!-- Filter Buttons -->
<div class="filter-buttons">
  <button class="filter-button" onclick="filterPosts('All')">All</button>
  <button class="filter-button" onclick="filterPosts('Article')">Articles</button>
  <button class="filter-button" onclick="filterPosts('Conference')">Conferences</button>
  <button class="filter-button" onclick="filterPosts('Blogpost')">Blogposts</button>
  <button class="filter-button" onclick="filterPosts('Workshop')">Workshops</button>
</div>

<!-- Posts Container -->
<div class="container">
  <div class="large-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-11.md/">
      <img src="/images/AIasCitizen.png" alt="AIsommedborger">
    </a>
    <h2>Conference: AI as citizens?</h2>
  </div>

  <div class="responsive-div post" data-category="Article">
    <a href="https://johansoltoft.github.io//publications/2010-10-01-paper-title-number-2.md/">
      <img src="/images/EPIC-computationelANTRO.png" alt="Diagram Computational Anthropology">
    </a>
    <h2>Article: Friction by Machine: How to Slow Down Reasoning with Computational Methods</h2>
  </div>

  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io//publications/2015-10-01-paper-title-number-4.md/">
      <img src="/images/Bellyofthemonster.gif" alt="'In the Belly of the Monster' Controversy Surrounding AI in Audio-Visual Media">
    </a>
    <h2>Blogpost: "In the Belly of the Monster" Controversy Surrounding AI in Audio-Visual Media</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io//talks/2012-03-01-talk-9">
      <img src="/images/D&D.png" alt="Collaborative Storytelling">
    </a>
    <h2>Conference: Unravelling Collaborative Storytelling with Generative AI</h2>
  </div>
  
  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io//talks/2012-03-01-talk-7">
      <img src="/images/Syn-politicans.png" alt="Synthetic Politicians">
    </a>
    <h2>Conference: Interfacing with Synthetic Mundane Politicians</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io//talks/2012-03-01-talk-10">
      <img src="/images/MASSHINE-syn.jpg" alt="SyntheticFiLM">
    </a>
    <h2>Conference: Exploring Cinematic Engagement through a Synthetic AI Film Lover</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io//talks/2012-03-01-talk-1">
      <img src="/images/Epic2-646.jpg" alt="Conference">
    </a>
    <h2>Conference: Friction by Machine</h2>
  </div>

  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io//talks/2014-02-01-talk-2">
      <img src="/images/EPIC1.jpg" alt="Epic10">
    </a>
    <h2>Conference: Audience Awareness Through Machine Anthropology</h2>
  </div>

  <div class="responsive-div post" data-category="Workshop">
    <a href="https://johansoltoft.github.io//publications/2009-10-01-paper-title-number-6.md/">
      <img src="/images/MASSHINE-retreat1.jpg" alt="Dragør retreat Generative Ethnographic AI">
    </a>
    <h2>Workshop: Dragør retreat Generative Ethnographic AI</h2>
  </div>

  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io//publications/2015-10-01-paper-title-number-3.md/">
      <img src="/images/twitchnetwork.png" alt="Twitch Emote Network">
    </a>
    <h2>Blogpost: Studying Community Detection Using Twitch Emotes</h2>
  </div>
  
  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io//publications/2015-10-01-paper-title-number-5.md/">
      <img src="/images/a1a4033a-e5ea-494a-a06f-7b8bde5c1a81.gif" alt="Natmus Network">
    </a>
    <h2>Blogpost: Studying how the discussion regarding the Danish National Museum evolves over time on Twitter</h2>
  </div>
  
  <div class="responsive-div post" data-category="Conference">
    <a href="https://johansoltoft.github.io//talks/2014-03-01-talk-3">
      <img src="/images/NordicSTS.jpg" alt="NordicSTS">
    </a>
    <h2>Conference: Creatively Acceptable AI</h2>
  </div>
  
  <div class="responsive-div post" data-category="Blogpost">
    <a href="https://johansoltoft.github.io//publications/2009-10-01-paper-title-number-1.md/">
      <img src="/images/dataimaga.png" alt="Data Imagination Diagram">
    </a>
    <h2>Blogpost: Strengthening the data-imagination of SMEs</h2>
  </div>

  <div class="responsive-div post" data-category="Workshop">
    <a href="https://johansoltoft.github.io//talks/2012-03-01-talk-4">
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
