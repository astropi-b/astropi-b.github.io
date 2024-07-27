---
layout: page
title: Research
permalink: /research/
---

<style>
.interest-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between; /* Adjusts spacing to maintain layout */
  gap: 20px; /* Adds space between the boxes */
}

.interest-item {
  flex: 1 0 calc(25% - 20px); /* Flex grow, flex shrink, and basis */
  display: flex;
  flex-direction: column;
  justify-content: space-around; /* Distribute space around items */
  align-items: center; /* Center items vertically */
  text-align: center; /* Ensure text is centered */
  min-width: 240px; /* Fixed minimum width of the box */
  height: 250px; /* Adjusted height for uniformity */
  margin: 5px; /* Margin around the boxes */
  padding: 20px;
  border: 2px solid transparent;
  border-radius: 10px;
  background-color: #f9f9f9;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: all 0.3s ease-in-out;
  position: relative; /* For pseudo-elements */
}

.interest-item h4 {
  margin-bottom: 5px; /* Decreased spacing between title and description */
  font-size: 18px;
  color: #333;
}

.interest-item p {
  font-size: 14px;
  color: #666;
}
/* Border Animation */
.interest-item::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  border: 2px solid transparent;
  border-radius: 10px;
  transition: border-color 0s linear;
}

.interest-item:hover::before {
  border-color: #967bb6; /* Darker shade of lavender */
  animation: slideBorder 4s linear infinite;
}

@keyframes slideBorder {
  0%, 100% {
    border-top-color: #967bb6; /* Darker shade of lavender */
    border-right-color: transparent;
    border-bottom-color: transparent;
    border-left-color: transparent;
  }
  25% {
    border-top-color: #967bb6;
    border-right-color: #967bb6;
    border-bottom-color: transparent;
    border-left-color: transparent;
  }
  50% {
    border-top-color: #967bb6;
    border-right-color: #967bb6;
    border-bottom-color: #967bb6;
    border-left-color: transparent;
  }
  75% {
    border-top-color: #967bb6;
    border-right-color: #967bb6;
    border-bottom-color: #967bb6;
    border-left-color: #967bb6;
  }
}
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

## Research Interests

My research interests are broad and varied, reflecting my curiosity about the cosmos. Here are a few areas I am particularly passionate about:

<div class="interest-grid">
  <div class="interest-item">
    <h4>Radio Astronomy</h4>
    <p>Exploring the universe through the radio waves it emits, uncovering the secrets of celestial bodies.</p>
  </div>

  <div class="interest-item">
    <h4>Data Science in Astronomy & Astrophysics</h4>
    <p>Utilizing data science, machine learning, neural networks, and computer vision to explore and interpret vast astronomical datasets, driving forward the latest advancements in the field.</p>
  </div>

  <div class="interest-item">
    <h4>Observational Cosmology</h4>
    <p>Studying the structure and evolution of the universe through observations and data analysis.</p>
  </div>
  
  <div class="interest-item">
    <h4>Astronomical Instrumentation and Technologies</h4>
    <p>Developing and utilizing advanced technologies to enhance our observational capabilities.</p>
  </div>

  <div class="interest-item">
    <h4>Exoplanets Formation and Detection</h4>
    <p>Investigating the formation and discovery of planets beyond our solar system.</p>
  </div>
  
  <div class="interest-item">
    <h4>Multi-wavelength Observations</h4>
    <p>Employing observations across multiple wavelengths to gain a comprehensive understanding of celestial phenomena, revealing insights that single-wavelength studies cannot provide.</p>
  </div>
</div>

## Research Projects

<div class="research-grid">
  <!-- Research items -->
  <div class="research-item">
    <img class="research-image" src="/img/l1.png" alt="G.L.O.T">
    <h3><a href="/research/webtool/">G.L.O.T</a></h3>
    <p>An innovative Web Tool for Radio Astronomy Observations at G.R.O</p>
  </div>

  <div class="research-item">
    <img class="research-image" src="/img/avatar-icon.png" alt="Project Two">
    <h3><a href="/research/lpdasimulations/">Establishment of L.P.D.A Array at G.R.O</a></h3>
    <p>Brief description of Project Two.</p>
  </div>

  <div class="research-item">
    <img class="research-image" src="/img/l3.png" alt="Project Three">
    <h3><a href="/research/sg/">Optimizing Star Galaxy Classification</a></h3>
    <p>We improve the Star Galaxy Classification Accuracies.</p>
  </div>
  <div class="research-item">
    <img class="research-image" src="/img/avatar-icon.png" alt="Project Two">
    <h3><a href="/research/lpdasimulations/">ExoCluster</a></h3>
    <p>Brief description of Project Four.</p>
  </div>
  <div class="research-item">
    <img class="research-image" src="/img/avatar-icon.png" alt="Project Two">
    <h3><a href="/research/exocluster/">Project Five</a></h3>
    <p>Brief description of Project Five.</p>
  </div>
</div>
