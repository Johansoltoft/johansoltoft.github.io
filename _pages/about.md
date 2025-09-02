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
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f8f9fa;
  }
  
  .header {
    background: white;
    padding: 20px 0;
    border-bottom: 1px solid #e9ecef;
    margin-bottom: 30px;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  .filter-buttons {
    text-align: center;
    margin-bottom: 30px;
  }
  
  .filter-button {
    display: inline-block;
    padding: 8px 16px;
    margin: 0 5px 10px 5px;
    cursor: pointer;
    background-color: white;
    color: #666;
    border: 1px solid #ddd;
    border-radius: 20px;
    text-decoration: none;
    font-size: 14px;
    transition: all 0.3s ease;
  }
  
  .filter-button:hover {
    background-color: #007bff;
    color: white;
    border-color: #007bff;
  }
  
  .posts-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  
  .post-item {
    display: flex;
    background: white;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    text-decoration: none;
    color: inherit;
  }
  
  .post-item:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  }
  
  .post-image {
    flex: 0 0 200px;
    height: 140px;
    overflow: hidden;
  }
  
  .post-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
  .post-content {
    flex: 1;
    padding: 20px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  
  .post-meta {
    font-size: 12px;
    color: #666;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 8px;
  }
  
  .post-title {
    font-size: 18px;
    font-weight: 600;
    color: #333;
    line-height: 1.4;
    margin-bottom: 10px;
  }
  
  .post-description {
    font-size: 14px;
    color: #666;
    line-height: 1.5;
  }
  
  .category-article { border-left: 4px solid #28a745; }
  .category-conference { border-left: 4px solid #007bff; }
  .category-blogpost { border-left: 4px solid #ffc107; }
  .category-workshop { border-left: 4px solid #6f42c1; }
  
  @media (max-width: 768px) {
    .post-item {
      flex-direction: column;
    }
    
    .post-image {
      flex: none;
      height: 200px;
    }
    
    .post-title {
      font-size: 16px;
    }
  }
  
  .hidden {
    display: none !important;
  }
</style>

<div class="filter-buttons">
  <button class="filter-button" onclick="filterPosts('All')">All</button>
  <button class="filter-button" onclick="filterPosts('Article')">Articles</button>
  <button class="filter-button" onclick="filterPosts('Conference')">Conferences</button>
  <button class="filter-button" onclick="filterPosts('Blogpost')">Blogposts</button>
  <button class="filter-button" onclick="filterPosts('Workshop')">Workshops</button>
</div>

<div class="posts-container">

  <a href="https://johansoltoft.github.io/publications/Recalcitrant-audiencing.md/" class="post-item category-article" data-category="Article">
    <div class="post-image">
      <img src="/images/Recalcitrant-audiencing.png" alt="Recalcitrant-audiencing">
    </div>
    <div class="post-content">
      <div class="post-meta">Article</div>
      <div class="post-title">Recalcitrant audiencing: Between analytics and creative practice in the film industry</div>
      <div class="post-description">Exploring the tension between data analytics and creative practices in contemporary film production, examining how audience insights shape creative decisions.</div>
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/datafantasi.md/" class="post-item category-article" data-category="Article">
    <div class="post-image">
      <img src="/images/Datafantasi2.png" alt="datafantasi">
    </div>
    <div class="post-content">
      <div class="post-meta">Book Chapter</div>
      <div class="post-title">Datafantasi: Fra styring til læring i en verden af vilde problemer</div>
      <div class="post-description">A Danish book chapter exploring the transition from control to learning in a world of wicked problems, examining data imagination and its role in complex systems.</div>
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/Danish-Tech-Museum.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-image">
      <img src="/images/map2.gif" alt="Grounding-AI">
    </div>
    <div class="post-content">
      <div class="post-meta">Exhibition</div>
      <div class="post-title">Danish Technological Museum: Grounding AI</div>
      <div class="post-description">An interactive exhibition that makes artificial intelligence tangible and accessible through hands-on experiences and visualization tools.</div>
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/Text-Unit-Tool.md/" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/TUT-johan.jpg" alt="Text Unit Tool">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">Text Unit Tool (TUT): An open-source tool for archiving and exploration of large-scale text data</div>
      <div class="post-description">Presenting an innovative open-source tool designed for researchers to archive, explore, and analyze large-scale textual datasets efficiently.</div>
    </div>
  </a>
  
  <a href="https://grounding-ai.github.io/web-application/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-image">
      <img src="/images/grounding-AI2.png" alt="Grounding-AI">
    </div>
    <div class="post-content">
      <div class="post-meta">Website</div>
      <div class="post-title">Grounding AI - AI Atlas of AI</div>
      <div class="post-description">A comprehensive web application that maps the landscape of artificial intelligence research and applications, making AI knowledge more accessible and navigable.</div>
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/2010-10-01-paper-title-number-18.md/" class="post-item category-article" data-category="Article">
    <div class="post-image">
      <img src="/images/Synthetic-Interlocutors.png" alt="Synthetic-I">
    </div>
    <div class="post-content">
      <div class="post-meta">Article</div>
      <div class="post-title">Synthetic Interlocutors</div>
      <div class="post-description">Investigating the role of AI-generated conversational agents and their impact on human communication patterns and social interaction dynamics.</div>
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-17.md/" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/ISA-1.JPG" alt="ISA">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">From digital methods to computational methods</div>
      <div class="post-description">Exploring the evolution of research methodologies from traditional digital approaches to advanced computational techniques in social science research.</div>
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/experimenting-with-large-scale-ethnographic-data.md/" class="post-item category-workshop" data-category="Workshop">
    <div class="post-image">
      <img src="/images/Workshop-1-Etno.jpg" alt="Workshop-etno">
    </div>
    <div class="post-content">
      <div class="post-meta">Workshop</div>
      <div class="post-title">Experimenting With Large-Scale Ethnographic Data</div>
      <div class="post-description">A hands-on workshop exploring innovative approaches to analyzing and interpreting large-scale ethnographic datasets using computational methods.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-15.md/" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/EASA2024.jpg" alt="EASA">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">Speculating with generative AI</div>
      <div class="post-description">Examining the speculative potential of generative AI technologies and their implications for creative and analytical practices in anthropology.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-14.md/" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/EASTS4s.jpg" alt="EASST/4s">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">The human in audience-centered film production</div>
      <div class="post-description">Investigating how human elements persist and evolve in film production processes increasingly driven by audience data and algorithmic insights.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-11.md/" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/AIasCitizen.png" alt="AIasCitizen.png">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">AI as citizens?</div>
      <div class="post-description">A provocative exploration of the potential for artificial intelligence systems to participate in civic life and democratic processes as digital citizens.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2010-10-01-paper-title-number-2.md/" class="post-item category-article" data-category="Article">
    <div class="post-image">
      <img src="/images/EPIC-computationelANTRO.png" alt="Diagram Computational Anthropology">
    </div>
    <div class="post-content">
      <div class="post-meta">Article</div>
      <div class="post-title">Friction by Machine: How to Slow Down Reasoning with Computational Methods</div>
      <div class="post-description">Examining how computational methods can introduce productive friction into research processes, encouraging deeper reflection and more nuanced analysis.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-4.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-image">
      <img src="/images/Bellyofthemonster.gif" alt="'In the Belly of the Monster' Controversy Surrounding AI in Audio-Visual Media">
    </div>
    <div class="post-content">
      <div class="post-meta">Blogpost</div>
      <div class="post-title">"In the Belly of the Monster" Controversy Surrounding AI in Audio-Visual Media</div>
      <div class="post-description">Analyzing the heated debates and ethical concerns surrounding the integration of AI technologies in film and media production workflows.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-9" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/D&D.png" alt="Collaborative Storytelling">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">Unravelling Collaborative Storytelling with Generative AI</div>
      <div class="post-description">Exploring how generative AI transforms collaborative narrative creation, examining new forms of human-machine creative partnerships.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-7" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/Syn-politicans.png" alt="Synthetic Politicians">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">Interfacing with Synthetic Mundane Politicians</div>
      <div class="post-description">Investigating the emergence of AI-generated political personas and their potential impact on democratic discourse and political engagement.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-10" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/MASSHINE-syn.jpg" alt="SyntheticFiLM">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">Exploring Cinematic Engagement through a Synthetic AI Film Lover</div>
      <div class="post-description">Developing AI systems that can engage with cinema as passionate viewers, exploring new forms of computational film criticism and analysis.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-1" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/Epic2-646.jpg" alt="Conference">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">Friction by Machine</div>
      <div class="post-description">Conference presentation on using computational methods to introduce productive friction in research processes and analytical thinking.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2014-02-01-talk-2" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/EPIC1.jpg" alt="Epic10">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">Audience Awareness Through Machine Anthropology</div>
      <div class="post-description">Exploring how computational anthropological methods can enhance understanding of audience behavior and cultural patterns.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-6.md/" class="post-item category-workshop" data-category="Workshop">
    <div class="post-image">
      <img src="/images/MASSHINE-retreat1.jpg" alt="Dragør retreat Generative Ethnographic AI">
    </div>
    <div class="post-content">
      <div class="post-meta">Workshop</div>
      <div class="post-title">Dragør retreat Generative Ethnographic AI</div>
      <div class="post-description">Intensive workshop retreat exploring the intersection of generative AI technologies and ethnographic research methodologies.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-3.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-image">
      <img src="/images/twitchnetwork.png" alt="Twitch Emote Network">
    </div>
    <div class="post-content">
      <div class="post-meta">Blogpost</div>
      <div class="post-title">Studying Community Detection Using Twitch Emotes</div>
      <div class="post-description">Analyzing online community structures and behaviors through the lens of Twitch emote usage patterns and network analysis.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-5.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-image">
      <img src="/images/a1a4033a-e5ea-494a-a06f-7b8bde5c1a81.gif" alt="Natmus Network">
    </div>
    <div class="post-content">
      <div class="post-meta">Blogpost</div>
      <div class="post-title">Studying how the discussion regarding the Danish National Museum evolves over time on Twitter</div>
      <div class="post-description">Tracking and analyzing the evolution of public discourse about cultural institutions through social media conversation patterns.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2014-03-01-talk-3" class="post-item category-conference" data-category="Conference">
    <div class="post-image">
      <img src="/images/NordicSTS.jpg" alt="NordicSTS">
    </div>
    <div class="post-content">
      <div class="post-meta">Conference</div>
      <div class="post-title">Creatively Acceptable AI</div>
      <div class="post-description">Examining the conditions under which AI technologies become acceptable and valuable tools within creative industries and artistic practices.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-1.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-image">
      <img src="/images/dataimaga.png" alt="Data Imagination Diagram">
    </div>
    <div class="post-content">
      <div class="post-meta">Blogpost</div>
      <div class="post-title">Strengthening the data-imagination of SMEs</div>
      <div class="post-description">Helping small and medium enterprises develop their capacity to imagine and implement data-driven innovations and strategies.</div>
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-4" class="post-item category-workshop" data-category="Workshop">
    <div class="post-image">
      <img src="/images/bertistheword(1).png" alt="Bert is the word">
    </div>
    <div class="post-content">
      <div class="post-meta">Workshop</div>
      <div class="post-title">BERT is the word</div>
      <div class="post-description">Hands-on workshop exploring BERT and other transformer models for natural language processing applications in research contexts.</div>
    </div>
  </a>
</div>


<script>
  function filterPosts(category) {
    const posts = document.querySelectorAll('[data-category]');
    posts.forEach(post => {
      if (category === 'All' || post.dataset.category === category) {
        post.classList.remove('hidden');
      } else {
        post.classList.add('hidden');
      }
    });
    
    // Update active button
    document.querySelectorAll('.filter-button').forEach(btn => {
      btn.style.backgroundColor = 'white';
      btn.style.color = '#666';
      btn.style.borderColor = '#ddd';
    });
    
    event.target.style.backgroundColor = '#007bff';
    event.target.style.color = 'white';
    event.target.style.borderColor = '#007bff';
  }
</script>
