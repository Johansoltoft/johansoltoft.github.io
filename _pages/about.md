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
  body {
    background-color: #e0e0e0; /* Light grey for the body */
    margin: 0;
    padding: 0;
  }
  .site-content {
    background-color: #e0e0e0; /* Ensure site-content has the same background */
    width: 100%;
    max-width: 100% !important;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin: 0;
    padding: 0; /* Remove padding */
    box-sizing: border-box;
  }

  .sidebar {
    background-color: #e0e0e0; /* Medium grey for the sidebar */
    flex: 1 1 20%; /* Adjust width as needed */
    padding: 10px;
    box-sizing: border-box;
  }

  .main-content {
    flex: 1 1 75%; /* Adjust width as needed */
    padding: 10px;
    box-sizing: border-box;
  }

  .masthead {
    background-color: #a0a0a0; /* Dark grey for the masthead */
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

<div class="site-content">
  <div class="sidebar">
    <!-- Sidebar content here -->
  </div>
  <div class="main-content">
    <div class="large-div post" data-category="Conference">
      <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-11.md/">
        <img src="/images/AIasCitizen.png" alt="AIsommedborger">
      </a>
      <h2>Conference: AI as citizens?</h2>
    </div>
    <!-- Add your responsive-div and large-div content here -->
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
