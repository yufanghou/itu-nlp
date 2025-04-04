---
layout: single
title: "Opening"
permalink: /opening/
author_profile: true
---

{% include base_path %}

<div class="opening-container">
  <div class="opening-header">
    <h1><span class="highlight">Join Our Team</span></h1>
    <p class="lead">We are currently looking for postdoctoral researchers, PhD students, visiting students, and intern students to join the IT:U NLP lab!</p>
  </div>

  <h1>How to Apply</h1>
  <div class="opening-application">
    <div class="application-card">
      <div class="card-content">
        <p>Please fill out the form below if you are interested in joining our lab.</p>
        <p>We strongly encourage you to visit the IT:U NLP group's page to explore our current research topics before applying.</p>
        <div class="button-container">
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSfVnllFyucGh7IdlUMiz_R7Q4IUucIQqzlyC7KB9Vs7CnDPVQ/viewform" target="_blank" class="btn btn-custom">Application Form <i class="fas fa-external-link-alt"></i></a>
          <a href="https://it-u.at/en/research/research-groups/natural-language-processing/" target="_blank" class="btn btn-custom">IT:U NLP Group Page <i class="fas fa-external-link-alt"></i></a>
        </div>
      </div>
    </div>
  </div>

  <div class="opening-positions">
    <h1>Postdoctoral Researchers</h1>
    <p>If you want to carry out research in our group as a <strong>post-doc</strong>, there are several funding possibilities:</p>
    
    <div class="funding-cards">
      <div class="funding-card">
        <h3 class="funding-title">IT:U Postdoc Program</h3>
      </div>
      
      <a href="https://ec.europa.eu/research/mariecurieactions/" target="_blank" class="funding-card-link">
        <div class="funding-card">
          <h3 class="funding-title">Marie-Curie Postdoctoral Fellowships <i class="fas fa-external-link-alt"></i></h3>
        </div>
      </a>
      
      <a href="https://www.fwf.ac.at/en/research-funding/fwf-programmes/esprit-programme" target="_blank" class="funding-card-link">
        <div class="funding-card">
          <h3 class="funding-title">FWF ESPRIT Career Advancement for Postdocs <i class="fas fa-external-link-alt"></i></h3>
        </div>
      </a>
      
      <a href="https://www.leopoldina.org/en/funding/leopoldina-fellowship-programme/leopoldina-postdoc-scholarship/" target="_blank" class="funding-card-link">
        <div class="funding-card">
          <h3 class="funding-title">Leopoldina Postdoc Scholarship <i class="fas fa-external-link-alt"></i></h3>
          <p class="funding-subtitle">(incoming from Germany, Austria, or Switzerland)</p>
        </div>
      </a>
    </div>
  </div>
</div>

<style>
  :root {
    --card-bg: white;
    --card-text: #333;
    --card-subtitle: #666;
    --container-bg: #f9f9f9;
    --shadow-color: rgba(0, 0, 0, 0.1);
    --shadow-hover: rgba(0, 0, 0, 0.15);
    --heading-text: #333;
    --highlight-bg: rgba(66, 133, 244, 0.2);
  }

  html.dark {
    --card-bg: #2d2d2d;
    --card-text: #e0e0e0;
    --card-subtitle: #b0b0b0;
    --container-bg: #1e1e1e;
    --shadow-color: rgba(0, 0, 0, 0.3);
    --shadow-hover: rgba(0, 0, 0, 0.4);
    --heading-text: #ffffff;
    --highlight-bg: rgba(66, 133, 244, 0.3);
  }

  .opening-container {
    background-color: var(--container-bg);
    border-radius: 8px;
    padding: 30px;
    margin-bottom: 30px;
    box-shadow: 0 4px 6px var(--shadow-color);
  }

  .opening-container h1 {
    color: var(--heading-text);
  }

  .opening-header {
    text-align: left;
    margin-bottom: 30px;
  }

  .opening-header h1 {
    font-size: 2.5em;
    margin-bottom: 15px;
    color: var(--heading-text);
  }

  .highlight {
    background: linear-gradient(120deg, var(--highlight-bg) 0%, var(--highlight-bg) 100%);
    padding: 0 10px;
    border-radius: 4px;
  }

  .lead {
    font-size: 1.2em;
    line-height: 1.6;
    color: var(--card-text);
  }

  .opening-application, .opening-positions {
    margin-bottom: 30px;
  }

  .application-card {
    background-color: var(--card-bg);
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 4px var(--shadow-color);
    margin-bottom: 20px;
  }

  .card-content {
    padding: 20px;
    color: var(--card-text);
  }

  .button-container {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 15px;
    margin-top: 20px;
    flex-wrap: wrap;
  }

  .btn {
    display: inline-block;
    padding: 10px 20px;
    border-radius: 4px;
    text-decoration: none !important;
    font-weight: bold;
    transition: background-color 0.3s;
  }

  .btn-custom {
    background-color: #86bfff;
    color: #333;
  }

  .btn-custom:hover {
    background-color: #6baeff;
    text-decoration: none !important;
  }

  .btn i {
    margin-left: 5px;
    font-size: 0.8em;
  }

  .opening-positions h1 {
    margin-bottom: 15px;
    font-size: 2em;
    color: var(--heading-text);
  }

  .opening-positions p {
    color: var(--card-text);
  }

  .funding-cards {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-top: 20px;
  }

  .funding-card {
    background-color: var(--card-bg);
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 2px 4px var(--shadow-color);
  }

  .funding-card-link {
    text-decoration: none !important;
    color: inherit;
    display: block;
  }

  .funding-card-link:hover {
    text-decoration: none !important;
  }

  .funding-card-link:hover .funding-card {
    box-shadow: 0 4px 8px var(--shadow-hover);
    transform: translateY(-2px);
    transition: all 0.3s ease;
  }

  .funding-title {
    margin: 0;
    font-size: 1.2em;
    color: var(--card-text);
    display: flex;
    align-items: center;
  }

  .funding-title i {
    margin-left: 8px;
    font-size: 0.8em;
    color: #4285f4;
  }

  .funding-subtitle {
    margin-top: 8px;
    font-size: 0.9em;
    color: var(--card-subtitle);
  }

  @media (max-width: 768px) {
    .opening-container {
      padding: 20px;
    }
    
    .opening-header h1 {
      font-size: 2em;
    }
    
    .button-container {
      flex-direction: column;
      align-items: flex-start;
    }
  }
</style>