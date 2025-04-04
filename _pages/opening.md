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

  <h3>How to Apply</h3>
  <div class="opening-application">
    <div class="application-card">
      <div class="card-content">
        <p>Please fill out the form below if you are interested in joining our lab.</p>
        <p>We strongly encourage you to visit the IT:U NLP group's page to explore our current research topics before applying.</p>
        <div class="button-container">
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSfVnllFyucGh7IdlUMiz_R7Q4IUucIQqzlyC7KB9Vs7CnDPVQ/viewform" class="btn btn-custom">Application Form</a>
          <a href="https://it-u.at/en/research/research-groups/natural-language-processing/" class="btn btn-custom">IT:U-NLP Group Page</a>
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
      
      <a href="https://ec.europa.eu/research/mariecurieactions/" class="funding-card-link">
        <div class="funding-card">
          <h3 class="funding-title">Marie-Curie Postdoctoral Fellowships</h3>
        </div>
      </a>
      
      <a href="https://www.fwf.ac.at/en/research-funding/fwf-programmes/esprit-programme" class="funding-card-link">
        <div class="funding-card">
          <h3 class="funding-title">FWF ESPRIT Career Advancement for Postdocs</h3>
        </div>
      </a>
      
      <a href="https://www.leopoldina.org/en/funding/leopoldina-fellowship-programme/leopoldina-postdoc-scholarship/" class="funding-card-link">
        <div class="funding-card">
          <h3 class="funding-title">Leopoldina Postdoc Scholarship</h3>
          <p class="funding-subtitle">(incoming from Germany, Austria, or Switzerland)</p>
        </div>
      </a>
    </div>
  </div>
</div>

<style>
  .opening-container {
    background-color: #f9f9f9;
    border-radius: 8px;
    padding: 30px;
    margin-bottom: 30px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }

  .opening-header {
    text-align: left;
    margin-bottom: 30px;
  }

  .opening-header h1 {
    font-size: 2.5em;
    margin-bottom: 15px;
  }

  .highlight {
    background: linear-gradient(120deg, rgba(66, 133, 244, 0.2) 0%, rgba(66, 133, 244, 0.2) 100%);
    padding: 0 10px;
    border-radius: 4px;
  }

  .lead {
    font-size: 1.2em;
    line-height: 1.6;
    color: #555;
  }

  .opening-application, .opening-positions {
    margin-bottom: 30px;
  }

  .application-card {
    background-color: white;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
  }

  .card-content {
    padding: 20px;
  }

  .button-container {
    display: flex;
    flex-direction: column;
    gap: 15px;
    margin-top: 20px;
  }

  .btn {
    display: inline-block;
    padding: 10px 20px;
    border-radius: 4px;
    text-decoration: none;
    font-weight: bold;
    transition: background-color 0.3s;
  }

  .btn-custom {
    background-color: #86bfff;
    color: #333;
  }

  .btn-custom:hover {
    background-color: #6baeff;
    text-decoration: none;
  }

  .opening-positions h1 {
    margin-bottom: 15px;
    font-size: 2em;
  }

  .funding-cards {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-top: 20px;
  }

  .funding-card {
    background-color: white;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  .funding-card-link {
    text-decoration: none;
    color: inherit;
    display: block;
  }

  .funding-card-link:hover .funding-card {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
    transform: translateY(-2px);
    transition: all 0.3s ease;
  }

  .funding-title {
    margin: 0;
    font-size: 1.2em;
    color: #333;
  }

  .funding-subtitle {
    margin-top: 8px;
    font-size: 0.9em;
    color: #666;
  }

  @media (max-width: 768px) {
    .opening-container {
      padding: 20px;
    }
    
    .opening-header h1 {
      font-size: 2em;
    }
    
    .btn {
      width: 100%;
      text-align: center;
    }
  }
</style>