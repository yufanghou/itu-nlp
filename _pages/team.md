---
layout: single
title: "Team"
permalink: /team/
author_profile: true
---

<style>
.member__container {
  margin-bottom: 1.5em;
}

.member__link {
  display: block;
  text-decoration: none !important;
  color: inherit;
}

.member__link:hover {
  text-decoration: none !important;
}

.member__link:hover .member__card {
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.15);
}

.member__card {
  display: flex;
  align-items: center;
  padding: 1em;
  background-color: var(--global-bg-color);
  border-radius: 8px;
  border: 1px solid var(--global-border-color);
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  transition: box-shadow 0.3s ease;
}

/* Dark mode specific styling */
html[data-theme="dark"] .member__card {
  background-color: #252525; /* Slightly lighter than dark mode background */
  border-color: #333; /* Darker border instead of white */
}

html[data-theme="dark"] .member__link:hover .member__card {
  box-shadow: 0 5px 15px rgba(255, 255, 255, 0.15); /* Lighter shadow for dark mode */
}

.member__avatar {
  margin-right: 1.5em;
}

.member__avatar img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  object-fit: cover;
}

.member__info {
  flex: 1;
}

.member__name {
  margin: 0 0 0.25em 0;
  font-size: 1.2em;
  font-weight: bold;
}

.member__role {
  margin: 0;
  font-size: 0.9em;
  color: var(--global-text-color-light);
}
</style>

## Team Lead

<div class="member__container">
  <a href="https://yufanghou.github.io" class="member__link">
    <div class="member__card">
      <div class="member__avatar">
        <img src="/images/yufang.jpg" alt="Yufang Hou">
      </div>
      <div class="member__info">
        <h3 class="member__name">Prof. Dr. Yufang Hou</h3>
        <p class="member__role">Head of ITU-NLP Lab</p>
      </div>
    </div>
  </a>
</div>

## Postdocs

<div class="member__container">
  <a href="https://github.com/hsuvas" class="member__link">
    <div class="member__card">
      <div class="member__avatar">
        <img src="/images/hsuvas-borkakoty.png" alt="Hsuvas Borkakoty">
      </div>
      <div class="member__info">
        <h3 class="member__name">Hsuvas Borkakoty</h3>
        <p class="member__role">Postdoctoral Research</p>
      </div>
    </div>
  </a>
</div>

<div class="member__container">
  <a href="https://github.com/arsalan98m" class="member__link">
    <div class="member__card">
      <div class="member__avatar">
        <img src="/images/muhammad-arslan-manzoor.png" alt="Muhammad Arslan Manzoor">
      </div>
      <div class="member__info">
        <h3 class="member__name">Muhammad Arslan Manzoor</h3>
        <p class="member__role">Postdoctoral Research</p>
      </div>
    </div>
  </a>
</div>
