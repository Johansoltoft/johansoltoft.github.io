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

<script src="https://d3js.org/d3.v6.min.js"></script>

<!-- SVG Network Graph -->
<div class="large-div">
  <svg width="800" height="800" id="network-graph"></svg>
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

  // D3.js Network Graph
  const svg = d3.select("#network-graph"),
        width = +svg.attr("width"),
        height = +svg.attr("height");

  const nodes = [
    { id: "AI_as_citizens", group: "project" },
    { id: "Friction_by_Machine", group: "project" },
    { id: "Controversy_AI_in_Audio-Visual_Media", group: "project" },
    { id: "From_Dice_to_Data", group: "project" },
    { id: "Synthetic_politicians", group: "project" },
    { id: "Synthetic_AI_Film_Lover", group: "project" },
    { id: "Generative_Ethnographic_AI", group: "project" },
    { id: "Strengthening_the_data_imagination_of_SMEs", group: "project" },
    { id: "Johan_Irving_Søltoft", group: "person" },
    { id: "Brit_Winthereik", group: "person" },
    { id: "Anders_Munk", group: "person" },
    { id: "Anders_Koed_Madsen", group: "person" },
    { id: "Morten_Heuser", group: "person" },
    { id: "Roman_Jurowetzki", group: "person" },
    { id: "Daniel_Hain", group: "person" },
    { id: "Torben_Elgaard_Jensen", group: "person" },
    { id: "Mathieu_Jacomy", group: "person" },
    { id: "Laura_Kocksch", group: "person" },
    { id: "Rikke_Ørngreen", group: "person" },
    { id: "Helene_Husted_Hansen", group: "person" },
    { id: "Asger_Gehrt_Olesen", group: "person" },
    { id: "Sara_Paasch_Knudsen", group: "person" }
  ];

  const links = [
    { source: "AI_as_citizens", target: "Johan_Irving_Søltoft" },
    { source: "AI_as_citizens", target: "Brit_Winthereik" },
    { source: "AI_as_citizens", target: "Anders_Munk" },
    { source: "Friction_by_Machine", target: "Johan_Irving_Søltoft" },
    { source: "Friction_by_Machine", target: "Anders_Koed_Madsen" },
    { source: "Friction_by_Machine", target: "Anders_Munk" },
    { source: "Controversy_AI_in_Audio-Visual_Media", target: "Johan_Irving_Søltoft" },
    { source: "From_Dice_to_Data", target: "Johan_Irving_Søltoft" },
    { source: "From_Dice_to_Data", target: "Morten_Heuser" },
    { source: "Synthetic_politicians", target: "Johan_Irving_Søltoft" },
    { source: "Synthetic_politicians", target: "Anders_Koed_Madsen" },
    { source: "Synthetic_AI_Film_Lover", target: "Johan_Irving_Søltoft" },
    { source: "Generative_Ethnographic_AI", target: "Johan_Irving_Søltoft" },
    { source: "Generative_Ethnographic_AI", target: "Anders_Koed_Madsen" },
    { source: "Generative_Ethnographic_AI", target: "Anders_Munk" },
    { source: "Generative_Ethnographic_AI", target: "Roman_Jurowetzki" },
    { source: "Generative_Ethnographic_AI", target: "Daniel_Hain" },
    { source: "Generative_Ethnographic_AI", target: "Torben_Elgaard_Jensen" },
    { source: "Generative_Ethnographic_AI", target: "Mathieu_Jacomy" },
    { source: "Generative_Ethnographic_AI", target: "Laura_Kocksch" },
    { source: "Strengthening_the_data_imagination_of_SMEs", target: "Rikke_Ørngreen" },
    { source: "Strengthening_the_data_imagination_of_SMEs", target: "Anders_Munk" },
    { source: "Strengthening_the_data_imagination_of_SMEs", target: "Mathieu_Jacomy" },
    { source: "Strengthening_the_data_imagination_of_SMEs", target: "Helene_Husted_Hansen" },
    { source: "Strengthening_the_data_imagination_of_SMEs", target: "Asger_Gehrt_Olesen" },
    { source: "Strengthening_the_data_imagination_of_SMEs", target: "Johan_Irving_Søltoft" },
    { source: "Strengthening_the_data_imagination_of_SMEs", target: "Sara_Paasch_Knudsen" }
  ];

  const simulation = d3.forceSimulation(nodes)
      .force("link", d3.forceLink(links).id(d => d.id))
      .force("charge", d3.forceManyBody().strength(-300))
      .force("center", d3.forceCenter(width / 2, height / 2));

  const link = svg.append("g")
      .attr("stroke", "#999")
      .attr("stroke-opacity", 0.6)
    .selectAll("line")
    .data(links)
    .join("line")
      .attr("stroke-width", d => Math.sqrt(d.value));

  const node = svg.append("g")
      .attr("stroke", "#fff")
      .attr("stroke-width", 1.5)
    .selectAll("circle")
    .data(nodes)
    .join("circle")
      .attr("r", d => d.group === "project" ? 20 : 15)
      .attr("fill", d => d.group === "project" ? "skyblue" : "lightgreen")
      .call(drag(simulation));

  node.append("title")
      .text(d => d.id);

  simulation.on("tick", () => {
    link
        .attr("x1", d => d.source.x)
        .attr("y1", d => d.source.y)
        .attr("x2", d => d.target.x)
        .attr("y2", d => d.target.y);

    node
        .attr("cx", d => d.x)
        .attr("cy", d => d.y);
  });

  function drag(simulation) {
    function dragstarted(event, d) {
      if (!event.active) simulation.alphaTarget(0.3).restart();
      d.fx = d.x;
      d.fy = d.y;
    }

    function dragged(event, d) {
      d.fx = event.x;
      d.fy = event.y;
    }

    function dragended(event, d) {
      if (!event.active) simulation.alphaTarget(0);
      d.fx = null;
      d.fy = null;
    }

    return d3.drag()
        .on("start", dragstarted)
        .on("drag", dragged)
        .on("end", dragended);
  }
</script>
