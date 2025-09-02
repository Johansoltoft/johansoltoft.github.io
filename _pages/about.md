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
    background-color: white;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  .filter-buttons {
    text-align: left;
    margin-bottom: 30px;
    font-size: 14px;
    color: #999;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }
  
  .filter-buttons::before {
    content: "FILTER BY: ";
    font-weight: 500;
  }
  
  .filter-button {
    color: #999;
    text-decoration: none;
    background: none;
    border: none;
    cursor: pointer;
    font-size: inherit;
    font-family: inherit;
    margin: 0;
    padding: 0;
    transition: color 0.2s ease;
  }
  
  .filter-button:hover {
    color: #333;
  }
  
  .filter-button:not(:last-child)::after {
    content: " | ";
    text-decoration: none;
    color: #ccc;
    margin: 0 2px;
  }
  
  .posts-container {
    display: flex;
    flex-direction: column;
    gap: 40px;
  }
  
  .post-item {
    display: flex;
    background: white;
    text-decoration: none;
    color: inherit;
    border-bottom: 1px solid #eee;
    padding-bottom: 40px;
  }
  
  .post-item:hover .post-title {
    color: #007bff;
  }
  
  .post-meta-left {
    flex: 0 0 150px;
    padding-right: 20px;
  }
  
  .post-source {
    font-style: italic;
    color: #666;
    font-size: 14px;
    margin-bottom: 4px;
  }
  
  .post-year {
    color: #999;
    font-size: 14px;
  }
  
  .post-content {
    flex: 1;
    padding-right: 40px;
  }
  
  .post-title {
    font-size: 16px;
    font-weight: 600;
    color: #333;
    line-height: 1.4;
    margin-bottom: 12px;
    transition: color 0.2s ease;
  }
  
  .post-authors {
    font-size: 14px;
    color: #666;
    margin-bottom: 8px;
    text-decoration: none;
  }
  
  .post-description {
    font-size: 14px;
    color: #666;
    line-height: 1.5;
    text-decoration: none;
  }
  
  .post-image {
    flex: 0 0 300px;
    height: 200px;
    overflow: hidden;
  }
  
  .post-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
  .category-article .post-source { color: #28a745; }
  .category-conference .post-source { color: #007bff; }
  .category-blogpost .post-source { color: #fd7e14; }
  .category-workshop .post-source { color: #6f42c1; }
  
  @media (max-width: 768px) {
    .post-item {
      flex-direction: column;
    }
    
    .post-meta-left {
      flex: none;
      padding-right: 0;
      margin-bottom: 15px;
    }
    
    .post-content {
      padding-right: 0;
      margin-bottom: 15px;
    }
    
    .post-image {
      flex: none;
      height: 200px;
    }
  }
  
  .hidden {
    display: none !important;
  }
</style>

<div class="container">
  <div class="filter-buttons">
    <button class="filter-button" onclick="filterPosts('All')">All</button>
    <button class="filter-button" onclick="filterPosts('Article')">Articles</button>
    <button class="filter-button" onclick="filterPosts('Conference')">Conferences</button>
    <button class="filter-button" onclick="filterPosts('Blogpost')">Blogposts</button>
    <button class="filter-button" onclick="filterPosts('Workshop')">Workshops</button>
  </div>

  <div class="posts-container">

    <a href="https://johansoltoft.github.io/publications/Recalcitrant-audiencing.md/" class="post-item category-article" data-category="Article">
      <div class="post-meta-left">
        <div class="post-source">Article</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Recalcitrant audiencing: Between analytics and creative practice in the film industry</div>
        <div class="post-authors">Johan Søltoft, Mathieu Jacomy, Dario Rodighiero</div>
        <div class="post-description">Exploring the tension between data analytics and creative practices in contemporary film production, examining how audience insights shape creative decisions and the resistance encountered in integrating algorithmic tools into creative workflows.</div>
      </div>
      <div class="post-image">
        <img src="/images/Recalcitrant-audiencing.png" alt="Recalcitrant-audiencing">
      </div>
    </a>
    
    <a href="https://johansoltoft.github.io/publications/datafantasi.md/" class="post-item category-article" data-category="Article">
      <div class="post-meta-left">
        <div class="post-source">Book Chapter</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Datafantasi: Fra styring til læring i en verden af vilde problemer</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">A Danish book chapter exploring the transition from control to learning in a world of wicked problems, examining data imagination and its role in complex systems and decision-making processes.</div>
      </div>
      <div class="post-image">
        <img src="/images/Datafantasi2.png" alt="datafantasi">
      </div>
    </a>
    
    <a href="https://johansoltoft.github.io/publications/Danish-Tech-Museum.md/" class="post-item category-blogpost" data-category="Blogpost">
      <div class="post-meta-left">
        <div class="post-source">Exhibition</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Danish Technological Museum: Grounding AI</div>
        <div class="post-authors">Johan Søltoft, Anne Beaulieu, Anders Kristian Munk</div>
        <div class="post-description">An interactive exhibition that makes artificial intelligence tangible and accessible through hands-on experiences and visualization tools, helping visitors understand AI through physical and digital interactions.</div>
      </div>
      <div class="post-image">
        <img src="/images/map2.gif" alt="Grounding-AI">
      </div>
    </a>
    
    <a href="https://johansoltoft.github.io/publications/Text-Unit-Tool.md/" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Text Unit Tool (TUT): An open-source tool for archiving and exploration of large-scale text data</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Presenting an innovative open-source tool designed for researchers to archive, explore, and analyze large-scale textual datasets efficiently.</div>
      </div>
      <div class="post-image">
        <img src="/images/TUT-johan.jpg" alt="Text Unit Tool">
      </div>
    </a>
    
    <a href="https://grounding-ai.github.io/web-application/" class="post-item category-blogpost" data-category="Blogpost">
      <div class="post-meta-left">
        <div class="post-source">Website</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Grounding AI - AI Atlas of AI</div>
        <div class="post-authors">Johan Søltoft, Research Team</div>
        <div class="post-description">A comprehensive web application that maps the landscape of artificial intelligence research and applications, making AI knowledge more accessible and navigable.</div>
      </div>
      <div class="post-image">
        <img src="/images/grounding-AI2.png" alt="Grounding-AI">
      </div>
    </a>
    
    <a href="https://johansoltoft.github.io/publications/2010-10-01-paper-title-number-18.md/" class="post-item category-article" data-category="Article">
      <div class="post-meta-left">
        <div class="post-source">Article</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Synthetic Interlocutors</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Investigating the role of AI-generated conversational agents and their impact on human communication patterns and social interaction dynamics.</div>
      </div>
      <div class="post-image">
        <img src="/images/Synthetic-Interlocutors.png" alt="Synthetic-I">
      </div>
    </a>
    
    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-17.md/" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">From digital methods to computational methods</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Exploring the evolution of research methodologies from traditional digital approaches to advanced computational techniques in social science research.</div>
      </div>
      <div class="post-image">
        <img src="/images/ISA-1.JPG" alt="ISA">
      </div>
    </a>
    
    <a href="https://johansoltoft.github.io/publications/experimenting-with-large-scale-ethnographic-data.md/" class="post-item category-workshop" data-category="Workshop">
      <div class="post-meta-left">
        <div class="post-source">Workshop</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Experimenting With Large-Scale Ethnographic Data</div>
        <div class="post-authors">Johan Søltoft, Research Team</div>
        <div class="post-description">A hands-on workshop exploring innovative approaches to analyzing and interpreting large-scale ethnographic datasets using computational methods.</div>
      </div>
      <div class="post-image">
        <img src="/images/Workshop-1-Etno.jpg" alt="Workshop-etno">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-15.md/" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Speculating with generative AI</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Examining the speculative potential of generative AI technologies and their implications for creative and analytical practices in anthropology.</div>
      </div>
      <div class="post-image">
        <img src="/images/EASA2024.jpg" alt="EASA">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-14.md/" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">The human in audience-centered film production</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Investigating how human elements persist and evolve in film production processes increasingly driven by audience data and algorithmic insights.</div>
      </div>
      <div class="post-image">
        <img src="/images/EASTS4s.jpg" alt="EASST/4s">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-11.md/" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">AI as citizens?</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">A provocative exploration of the potential for artificial intelligence systems to participate in civic life and democratic processes as digital citizens.</div>
      </div>
      <div class="post-image">
        <img src="/images/AIasCitizen.png" alt="AIasCitizen.png">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2010-10-01-paper-title-number-2.md/" class="post-item category-article" data-category="Article">
      <div class="post-meta-left">
        <div class="post-source">Article</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Friction by Machine: How to Slow Down Reasoning with Computational Methods</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Examining how computational methods can introduce productive friction into research processes, encouraging deeper reflection and more nuanced analysis.</div>
      </div>
      <div class="post-image">
        <img src="/images/EPIC-computationelANTRO.png" alt="Diagram Computational Anthropology">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-4.md/" class="post-item category-blogpost" data-category="Blogpost">
      <div class="post-meta-left">
        <div class="post-source">Blogpost</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">"In the Belly of the Monster" Controversy Surrounding AI in Audio-Visual Media</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Analyzing the heated debates and ethical concerns surrounding the integration of AI technologies in film and media production workflows.</div>
      </div>
      <div class="post-image">
        <img src="/images/Bellyofthemonster.gif" alt="'In the Belly of the Monster' Controversy Surrounding AI in Audio-Visual Media">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-9" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Unravelling Collaborative Storytelling with Generative AI</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Exploring how generative AI transforms collaborative narrative creation, examining new forms of human-machine creative partnerships.</div>
      </div>
      <div class="post-image">
        <img src="/images/D&D.png" alt="Collaborative Storytelling">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-7" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Interfacing with Synthetic Mundane Politicians</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Investigating the emergence of AI-generated political personas and their potential impact on democratic discourse and political engagement.</div>
      </div>
      <div class="post-image">
        <img src="/images/Syn-politicans.png" alt="Synthetic Politicians">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-10" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Exploring Cinematic Engagement through a Synthetic AI Film Lover</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Developing AI systems that can engage with cinema as passionate viewers, exploring new forms of computational film criticism and analysis.</div>
      </div>
      <div class="post-image">
        <img src="/images/MASSHINE-syn.jpg" alt="SyntheticFiLM">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-1" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Friction by Machine</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Conference presentation on using computational methods to introduce productive friction in research processes and analytical thinking.</div>
      </div>
      <div class="post-image">
        <img src="/images/Epic2-646.jpg" alt="Conference">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/talks/2014-02-01-talk-2" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Audience Awareness Through Machine Anthropology</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Exploring how computational anthropological methods can enhance understanding of audience behavior and cultural patterns.</div>
      </div>
      <div class="post-image">
        <img src="/images/EPIC1.jpg" alt="Epic10">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-6.md/" class="post-item category-workshop" data-category="Workshop">
      <div class="post-meta-left">
        <div class="post-source">Workshop</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Dragør retreat Generative Ethnographic AI</div>
        <div class="post-authors">Johan Søltoft, Research Team</div>
        <div class="post-description">Intensive workshop retreat exploring the intersection of generative AI technologies and ethnographic research methodologies.</div>
      </div>
      <div class="post-image">
        <img src="/images/MASSHINE-retreat1.jpg" alt="Dragør retreat Generative Ethnographic AI">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-3.md/" class="post-item category-blogpost" data-category="Blogpost">
      <div class="post-meta-left">
        <div class="post-source">Blogpost</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Studying Community Detection Using Twitch Emotes</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Analyzing online community structures and behaviors through the lens of Twitch emote usage patterns and network analysis.</div>
      </div>
      <div class="post-image">
        <img src="/images/twitchnetwork.png" alt="Twitch Emote Network">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-5.md/" class="post-item category-blogpost" data-category="Blogpost">
      <div class="post-meta-left">
        <div class="post-source">Blogpost</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Studying how the discussion regarding the Danish National Museum evolves over time on Twitter</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Tracking and analyzing the evolution of public discourse about cultural institutions through social media conversation patterns.</div>
      </div>
      <div class="post-image">
        <img src="/images/a1a4033a-e5ea-494a-a06f-7b8bde5c1a81.gif" alt="Natmus Network">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/talks/2014-03-01-talk-3" class="post-item category-conference" data-category="Conference">
      <div class="post-meta-left">
        <div class="post-source">Conference</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Creatively Acceptable AI</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Examining the conditions under which AI technologies become acceptable and valuable tools within creative industries and artistic practices.</div>
      </div>
      <div class="post-image">
        <img src="/images/NordicSTS.jpg" alt="NordicSTS">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-1.md/" class="post-item category-blogpost" data-category="Blogpost">
      <div class="post-meta-left">
        <div class="post-source">Blogpost</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">Strengthening the data-imagination of SMEs</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Helping small and medium enterprises develop their capacity to imagine and implement data-driven innovations and strategies.</div>
      </div>
      <div class="post-image">
        <img src="/images/dataimaga.png" alt="Data Imagination Diagram">
      </div>
    </a>

    <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-4" class="post-item category-workshop" data-category="Workshop">
      <div class="post-meta-left">
        <div class="post-source">Workshop</div>
        <div class="post-year">2024</div>
      </div>
      <div class="post-content">
        <div class="post-title">BERT is the word</div>
        <div class="post-authors">Johan Søltoft</div>
        <div class="post-description">Hands-on workshop exploring BERT and other transformer models for natural language processing applications in research contexts.</div>
      </div>
      <div class="post-image">
        <img src="/images/bertistheword(1).png" alt="Bert is the word">
      </div>
    </a>

  </div>
</div>-4" class="post-item category-workshop" data-category="Workshop">
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
