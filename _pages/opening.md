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
    <p class="lead">We are currently looking for postdoctoral researchers, PhD students, visiting students, and intern students to join the <a href="https://it-u.at/en/research/research-groups/natural-language-processing/" class="highlight-link">IT:U NLP lab</a>!</p>
  </div>

  <div class="opening-application">
    <div class="application-card">
      <div class="card-icon">
        <i class="fas fa-file-alt"></i>
      </div>
      <div class="card-content">
        <h3>How to Apply</h3>
        <p>Please fill out <a href="https://docs.google.com/forms/d/e/1FAIpQLSfVnllFyucGh7IdlUMiz_R7Q4IUucIQqzlyC7KB9Vs7CnDPVQ/viewform" class="btn btn-info">this form</a> (feel free to skip some questions) if you are interested in joining our lab.</p>
        <p>We strongly encourage you to visit the <a href="https://it-u.at/en/research/research-groups/natural-language-processing/">IT:U NLP group's page</a> to explore our current research topics before applying.</p>
      </div>
    </div>
  </div>

  <div class="opening-positions">
    <div class="position-card">
      <div class="card-header">
        <h2>Post-doctoral Researchers</h2>
      </div>
      <div class="card-body">
        <p>If you want to carry out research in our group as a <strong>post-doc</strong>, there are several funding possibilities:</p>
        <ul class="funding-list">
          <li>
            <div class="funding-item">
              <span class="funding-title">IT:U Postdoc Program</span>
            </div>
          </li>
          <li>
            <div class="funding-item">
              <span class="funding-title"><a href="https://ec.europa.eu/research/mariecurieactions/">Marie-Curie Postdoctoral Fellowships</a></span>
            </div>
          </li>
          <li>
            <div class="funding-item">
              <span class="funding-title"><a href="https://www.fwf.ac.at/en/research-funding/fwf-programmes/esprit-programme">FWF ESPRIT Career Advancement for Postdocs</a></span>
            </div>
          </li>
          <li>
            <div class="funding-item">
              <span class="funding-title"><a href="https://www.leopoldina.org/en/funding/leopoldina-fellowship-programme/leopoldina-postdoc-scholarship/">Leopoldina Postdoc Scholarship</a></span>
              <span class="funding-subtitle">(incoming from Germany, Austria, or Switzerland)</span>
            </div>
          </li>
        </ul>
      </div>
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
    text-align: center;
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

  .highlight-link {
    color: #4285f4;
    font-weight: bold;
    text-decoration: none;
    transition: color 0.3s;
  }

  .highlight-link:hover {
    color: #2a75f3;
    text-decoration: underline;
  }

  .opening-application, .opening-positions {
    margin-bottom: 30px;
  }

  .application-card, .position-card {
    display: flex;
    flex-direction: column;
    background-color: white;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  .card-header {
    background-color: #4285f4;
    color: white;
    padding: 15px 20px;
  }

  .card-header h2 {
    margin: 0;
    font-size: 1.5em;
  }

  .card-icon {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 60px;
    height: 60px;
    background-color: #4285f4;
    color: white;
    border-radius: 50%;
    margin: 20px auto;
    font-size: 24px;
  }

  .card-content, .card-body {
    padding: 20px;
  }

  .btn {
    display: inline-block;
    padding: 8px 16px;
    border-radius: 4px;
    text-decoration: none;
    font-weight: bold;
    transition: background-color 0.3s;
  }

  .btn-info {
    background-color: #4285f4;
    color: white;
  }

  .btn-info:hover {
    background-color: #2a75f3;
    text-decoration: none;
  }

  .funding-list {
    list-style-type: none;
    padding: 0;
    margin: 0;
  }

  .funding-list li {
    margin-bottom: 15px;
    padding-left: 20px;
    position: relative;
  }

  .funding-list li:before {
    content: "•";
    position: absolute;
    left: 0;
    color: #4285f4;
    font-weight: bold;
  }

  .funding-item {
    display: flex;
    flex-direction: column;
  }

  .funding-title {
    font-weight: bold;
    color: #333;
  }

  .funding-subtitle {
    font-size: 0.9em;
    color: #666;
    margin-top: 3px;
  }

  @media (max-width: 768px) {
    .opening-container {
      padding: 20px;
    }
    
    .opening-header h1 {
      font-size: 2em;
    }
  }
</style>