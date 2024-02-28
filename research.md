---
layout: page
title: Research
permalink: /research/
---

<style>
.research-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.research-item {
  margin-bottom: 20px; 
  border: 1px solid #ddd; 
  padding: 10px; 
  border-radius: 8px; 
  background-color: #f9f9f9; 
  width: 30%; 
  transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out; /* Animation for transform and shadow */
  margin-right: 1%; 
  margin-left: 1%; 
  box-shadow: 0 2px 4px rgba(0,0,0,0.1); /* Initial shadow */
}

.research-item:hover {
  transform: translateY(-5px) scale(1.05); /* Move up slightly and scale */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Enhanced shadow on hover */
}

.research-image {
  max-width: 100%; 
  height: auto; 
  border-radius: 8px;
}

@media (max-width: 800px) {
  .research-item {
    width: 45%; /* Adjust for smaller screens */
  }
}

@media (max-width: 600px) {
  .research-item {
    width: 100%; /* Full width on very small screens */
  }
}
</style>

<div class="research-grid">
  <!-- Research items -->
  <div class="research-item">
    <img class="research-image" src="/img/l1.png" alt="G.L.O.T">
    <h3><a href="/research/webtool/">G.L.O.T</a></h3>
    <p>An innovative Web Tool for Radio Astronomy Observations at G.R.O</p>
  </div>

  <div class="research-item">
    <img class="research-image" src="/img/l1.png" alt="Project Two">
    <h3><a href="/research/lpdasimulations/">Project Two</a></h3>
    <p>Brief description of Project Two.</p>
  </div>

  <div class="research-item">
    <img class="research-image" src="/img/avatar-icon.png" alt="Project Three">
    <h3><a href="/research/project-three">Optimizing Star Galaxy Classification Three</a></h3>
    <p>Brief description of Project Three.</p>
  </div>
  <div class="research-item">
    <img class="research-image" src="/img/avatar-icon.png" alt="Project Two">
    <h3><a href="/research/lpdasimulations/">Project Four</a></h3>
    <p>Brief description of Project Four.</p>
  </div>
  <div class="research-item">
    <img class="research-image" src="/img/avatar-icon.png" alt="Project Two">
    <h3><a href="/research/lpdasimulations/">Project Five</a></h3>
    <p>Brief description of Project Five.</p>
  </div>
</div>

 
