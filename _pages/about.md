---
layout: archive
permalink: /
title: ""
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
    text-decoration: none !important;
    color: inherit;
    border-bottom: 1px solid #eee;
    padding-bottom: 40px;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  
  .post-item:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  }
  
  .post-item * {
    text-decoration: none !important;
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
    text-decoration: none;
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
      <div class="post-year">2025</div>
    </div>
    <div class="post-content">
      <div class="post-title">Recalcitrant audiencing: Between analytics and creative practice in the film industry</div>
      <div class="post-authors">Johan Irving Søltoft, Anders Munk</div>
      <div class="post-description">This article explores the evolution of audience analytics in filmmaking in the context of digital platforms and AI. We propose the term recalcitrant audiencing to describe a mode of audience engagement that resists confirming filmmakers' assumptions, instead challenging dominant ideas about who the audience is or should be. In place of a docile, knowable audience, we trace the emergence of one that is intentionally recalcitrant- ambivalent, heterogeneous, and constructed to be troubling.</div>
    </div>
    <div class="post-image">
      <img src="/images/Recalcitrant-audiencing.png" alt="Recalcitrant-audiencing">
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/datafantasi.md/" class="post-item category-article" data-category="Article">
    <div class="post-meta-left">
      <div class="post-source">Book Chapter</div>
      <div class="post-year">2025</div>
    </div>
    <div class="post-content">
      <div class="post-title">Datafantasi: Fra styring til læring i en verden af vilde problemer</div>
      <div class="post-authors">Anders Koed Madsen, Johan Irving Søltoft, Ann-Sofie Klitgaard</div>
      <div class="post-description">The chapter introduces the Data Diamond as a heuristic tool for analyzing and mapping data situations. We illustrate the model with a case from Helsingør Municipality, where semantic analysis was used to understand student well-being as part of an MDO project.</div>
    </div>
    <div class="post-image">
      <img src="/images/Datafantasi2.png" alt="datafantasi">
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/Danish-Tech-Museum.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-meta-left">
      <div class="post-source">Exhibition</div>
      <div class="post-year">2025</div>
    </div>
    <div class="post-content">
      <div class="post-title">Danish Technological Museum: Grounding AI</div>
      <div class="post-authors">Anders Kristian Munk, Mathieu Jacomy, Matilde Ficozzi, Dario Rodighiero, Johan Irving Søltoft, Ainoa Pubill, Sarah Feldes</div>
      <div class="post-description">The Grounded AI Map is a 10x10 meter floor mat representing 2M scientific papers involving AI and algorithms since the 1980s. The Danish Technical Museum will be exhibiting it until June 2, 2025, in dialogue with objects selected from its collections.</div>
    </div>
    <div class="post-image">
      <img src="/images/map2.gif" alt="Grounding-AI">
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/Text-Unit-Tool.md/" class="post-item category-conference" data-category="Conference">
    <div class="post-meta-left">
      <div class="post-source">Conference</div>
      <div class="post-year">2025</div>
    </div>
    <div class="post-content">
      <div class="post-title">Text Unit Tool (TUT): An open-source tool for archiving and exploration of large-scale text data</div>
      <div class="post-authors">Johan Irving Søltoft</div>
      <div class="post-description">Presenting Text Unit Tool (TUT) which is an open-source software designed for archiving large-scale datasets of text units. It enables semantic exploration as a navigation strategy for qualitative text material, and close and distant reading analysis.</div>
    </div>
    <div class="post-image">
      <img src="/images/TUT-johan.jpg" alt="Text Unit Tool">
    </div>
  </a>
  
  <a href="https://grounding-ai.github.io/web-application/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-meta-left">
      <div class="post-source">Website</div>
      <div class="post-year">2025</div>
    </div>
    <div class="post-content">
      <div class="post-title">Grounding AI - AI Atlas of AI</div>
      <div class="post-authors">Anders Kristian Munk, Mathieu Jacomy, Matilde Ficozzi, Dario Rodighiero, Johan Irving Søltoft, Ainoa Pubill, Sarah Feldes</div>
      <div class="post-description">AI is everywhere and nowhere. Public discussions about AI often focus on specific applications, like ChatGPT, leading us to associate AI primarily with these well-known tools. As a result, we may overlook the fact that AI is deeply embedded in many aspects of our daily lives, and involves a much broader range of technologies than we would perhaps normally think.</div>
    </div>
    <div class="post-image">
      <img src="/images/grounding-AI2.png" alt="Grounding-AI">
    </div>
  </a>
  
  <a href="https://johansoltoft.github.io/publications/2010-10-01-paper-title-number-18.md/" class="post-item category-article" data-category="Article">
    <div class="post-meta-left">
      <div class="post-source">Preprint Article</div>
      <div class="post-year">2024</div>
    </div>
    <div class="post-content">
      <div class="post-title">Synthetic Interlocutors</div>
      <div class="post-authors">Johan Irving Søltoft, Laura Kocksch, Anders Munk</div>
      <div class="post-description">This pre-print introduces “Synthetic Interlocutors” for ethnographic research. Synthetic Interlocutors are chatbots ingested with ethnographic textual material (interviews and observations) by using Retrieval Augmented Generation (RAG). We integrated an open-source large language model with ethnographic data from three projects to explore two questions: Can RAG digest ethnographic material and act as ethnographic interlocutor? And, if so, can Synthetic Interlocutors prolong encounters with the field and extend our analysis?.</div>
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
      <div class="post-authors">Lasse Uhrskov Kristensen, Johan Irving Søltoft</div>
      <div class="post-description">In this presentation we argued that engagements with new computational techniques, such as large language models, could be seen as a continuation of digital methods. While digital methods repurposed the web as both topic and resource (Rogers, 2019; 2013; Marres, 2017), we showed how computational methods adapted computer and data science not only as tools but also as research objects.</div>
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
      <div class="post-authors">Johan Irving Søltoft, Anders Munk, Brit Winthereik</div>
      <div class="post-description">We held a workshop in ECHOlab on the theme of experimenting with large-scale etnographic data. The session began with a presentation by Brit Ross Winthereik, who introduced us to various approaches and modes of experimentation through her book, Experimenting with Ethnography.</div>
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
      <div class="post-authors">Laura Kocksch, Johan Irving Søltoft</div>
      <div class="post-description">Based on a series of experiments with a large language model ingested with ethnographic interviews, we reflect on moments of disconcertment, re-experiencing and estranging ethnographic encounters. We argue for a speculative use of Generative AI in Anthropology.</div>
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
      <div class="post-description">The study examines the methods developed by the consultancy firm, including mobile ethnography for engaging global audiences, automatic transcription for processing interviews, emotion detection algorithms applied to transcribed data, and generative AI in order to showcase different practices of constructing the audience for the movie production process.</div>
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
      <div class="post-authors">Anders Munk, Brit Winthereik, Johan Søltoft</div>
      <div class="post-description">The public conversation may be partially generated by AI. But can we handle language models as participants in our democracy? and should we? To test this, we trained two language models, in the Human Centered Innovation research group, to participate in a panel debate at Folkemødet.</div>
    </div>
    <div class="post-image">
      <img src="/images/AIasCitizen.png" alt="AIasCitizen.png">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2010-10-01-paper-title-number-2.md/" class="post-item category-article" data-category="Article">
    <div class="post-meta-left">
      <div class="post-source">Article</div>
      <div class="post-year">2023</div>
    </div>
    <div class="post-content">
      <div class="post-title">Friction by Machine: How to Slow Down Reasoning with Computational Methods</div>
      <div class="post-authors">Anders Koed Madsen, Anders Munk, Johan Irving Søltoft</div>
      <div class="post-description">This paper provides a theoretical alternative to the prevailing perception of machine learning as synonymous with speed and efficiency. Inspired by ethnographic fieldwork and grounded in pragmatist philosophy, we introduce the concept of “data friction” as the situation when encounters between held beliefs and data patterns posses the potential to stimulate innovative thinking.</div>
    </div>
    <div class="post-image">
      <img src="/images/EPIC-computationelANTRO.png" alt="Diagram Computational Anthropology">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-4.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-meta-left">
      <div class="post-source">Blogpost</div>
      <div class="post-year">2023</div>
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
      <div class="post-year">2023</div>
    </div>
    <div class="post-content">
      <div class="post-title">Unravelling Collaborative Storytelling with Generative AI</div>
      <div class="post-authors">Morten Heuser, Johan Søltoft</div>
      <div class="post-description">Generative artificial intelligence (AI) has demonstrated proficiency in composing sentences and structures that conform to grammatical precepts. However, our focus centres on an explorative ethnographic inquiry of generative AI within the context of Dungeons & Dragons. </div>
    </div>
    <div class="post-image">
      <img src="/images/D&D.png" alt="Collaborative Storytelling">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-7" class="post-item category-conference" data-category="Conference">
    <div class="post-meta-left">
      <div class="post-source">Conference</div>
      <div class="post-year">2023</div>
    </div>
    <div class="post-content">
      <div class="post-title">Interfacing with Synthetic Mundane Politicians</div>
      <div class="post-authors">Johan Søltoft, Anders Koed Madsen</div>
      <div class="post-description">In urban settings, connecting with local political agendas can be challenging. Existing methods for interfacing with politicians are often mediated by journalists or involve staged events like rallies or town hall meetings, which may not reflect everyday mundane politics. To address this, we’ve initiated an experiment utilizing a generative AI model to facilitate conversations with synthetic mundane politicians.</div>
    </div>
    <div class="post-image">
      <img src="/images/Syn-politicans.png" alt="Synthetic Politicians">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-10" class="post-item category-conference" data-category="Conference">
    <div class="post-meta-left">
      <div class="post-source">Conference</div>
      <div class="post-year">2023</div>
    </div>
    <div class="post-content">
      <div class="post-title">Exploring Cinematic Engagement through a Synthetic AI Film Lover</div>
      <div class="post-authors">Johan Søltoft</div>
      <div class="post-description">We are currently conducting an ongoing experiment that involves inputting these interviews into an open LLM model. The chatbot, has been prompted to have a film enthusiast “persona”.</div>
    </div>
    <div class="post-image">
      <img src="/images/MASSHINE-syn.jpg" alt="SyntheticFiLM">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-1" class="post-item category-conference" data-category="Conference">
    <div class="post-meta-left">
      <div class="post-source">Conference</div>
      <div class="post-year">2023</div>
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
      <div class="post-year">2023</div>
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
      <div class="post-year">2023</div>
    </div>
    <div class="post-content">
      <div class="post-title">Dragør retreat Generative Ethnographic AI</div>
      <div class="post-authors">MASSHINE</div>
      <div class="post-description">Intensive workshop retreat exploring the intersection of generative AI technologies and ethnographic research methodologies.</div>
    </div>
    <div class="post-image">
      <img src="/images/MASSHINE-retreat1.jpg" alt="Dragør retreat Generative Ethnographic AI">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2015-10-01-paper-title-number-3.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-meta-left">
      <div class="post-source">Blogpost</div>
      <div class="post-year">2023</div>
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
      <div class="post-year">2023</div>
    </div>
    <div class="post-content">
      <div class="post-title">Studying how the discussion regarding the Danish National Museum evolves over time on Twitter</div>
      <div class="post-authors">Johan Søltoft</div>
      <div class="post-description">Tracking and analyzing the evolution of public dicussions about Danish National Museum.</div>
    </div>
    <div class="post-image">
      <img src="/images/a1a4033a-e5ea-494a-a06f-7b8bde5c1a81.gif" alt="Natmus Network">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2014-03-01-talk-3" class="post-item category-conference" data-category="Conference">
    <div class="post-meta-left">
      <div class="post-source">Conference</div>
      <div class="post-year">2023</div>
    </div>
    <div class="post-content">
      <div class="post-title">Creatively Acceptable AI</div>
      <div class="post-authors">Johan Søltoft</div>
      <div class="post-description">Examining the conditions under which AI technologies become acceptable and applicable tools within creative industries and artistic practices.</div>
    </div>
    <div class="post-image">
      <img src="/images/NordicSTS.jpg" alt="NordicSTS">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/publications/2009-10-01-paper-title-number-1.md/" class="post-item category-blogpost" data-category="Blogpost">
    <div class="post-meta-left">
      <div class="post-source">Blogpost</div>
      <div class="post-year">2022</div>
    </div>
    <div class="post-content">
      <div class="post-title">Strengthening the data-imagination of SMEs</div>
      <div class="post-authors">Rikke Ørngreen, Anders Kristian Munk, Sara Paasch Knudsen, Johan Irving Søltoft, Helene Husted Hansen, Mathieu Jacomy, Asger Gehrt Knudsen</div>
      <div class="post-description">Helping small and medium enterprises develop their capacity to imagine and implement data-driven innovations and strategies.</div>
    </div>
    <div class="post-image">
      <img src="/images/dataimaga.png" alt="Data Imagination Diagram">
    </div>
  </a>

  <a href="https://johansoltoft.github.io/talks/2012-03-01-talk-4" class="post-item category-workshop" data-category="Workshop">
    <div class="post-meta-left">
      <div class="post-source">Workshop</div>
      <div class="post-year">2022</div>
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
  }
</script>
