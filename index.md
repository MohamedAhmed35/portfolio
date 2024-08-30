---
layout: default
title: Home
---

<link rel="stylesheet" href="{{ "/styles.css" | relative_url }}">
<script src="{{ "/scripts.js" | relative_url }}"></script>

# Project

<div class="collapsible-container">
  <button class="collapsible">Subsection 1</button>
  <div class="content">
    <div class="subsection-container">
      <button class="collapsible subsection">Subsection 1.1</button>
      <div class="content">
        <p>Details for Subsection 1.1 go here.</p>
        <button class="collapsible subsection">Subsection 1.1.1</button>
        <div class="content">
          <p>Details for Subsection 1.1.1 go here.</p>
        </div>
      </div>
    </div>
    <p>Details for Subsection 1 go here.</p>
  </div>

  <button class="collapsible">Subsection 2</button>
  <div class="content">
    <div class="subsection-container">
      <button class="collapsible subsection">Subsection 2.1</button>
      <div class="content">
        <p>Details for Subsection 2.1 go here.</p>
        <button class="collapsible subsection">Subsection 2.1.1</button>
        <div class="content">
          <p>Details for Subsection 2.1.1 go here.</p>
        </div>
      </div>
    </div>
    <p>Details for Subsection 2 go here.</p>
  </div>
</div>
