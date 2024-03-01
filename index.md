---
layout: page
title: Anumanchi Agastya Sai Ram Likhit
---

<style>
.research-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between; /* Adjusts spacing to maintain layout */
  gap: 20px; /* Adds space between the boxes */
}

.research-item {
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
  position: relative; /* For the animation */
  overflow: hidden; /* Prevent overflow for the border animation */
}

.research-item h4 {
  margin: 5px 0; /* Reduced spacing between title and description */
  font-size: 18px;
  color: #333;
}

.research-item p {
  font-size: 14px;
  color: #666;
}

.research-item::after {
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  border: 2px solid transparent;
  border-radius: 10px;
  transition: border-color 0.4s, transform 0.6s;
  transform: scale(0.1);
  z-index: -1;
}

.research-item:hover::after {
  border-color: lavender; /* Lavender border on hover */
  transform: scale(1);
  transition: border-color 0.4s, transform 0.6s cubic-bezier(0.2, 1, 0.3, 1);
}

@keyframes borderRun {
  0% {
    transform: rotate(0deg) translate(0, 0);
  }
  100% {
    transform: rotate(360deg) translate(0, 0);
  }
}
</style>

# Welcome to My Page!

Hello! I'm Anumanchi Agastya Sai Ram Likhit, an Integrated Masters student specializing in [your specialization], currently studying at [IISER Bhopal, India](https://www.iiserb.ac.in/). My academic journey is driven by a passion for exploring the mysteries of the universe and understanding the underlying principles that govern it. With a keen interest in both theoretical and practical aspects of my field, I am constantly seeking to expand my knowledge and engage in meaningful research.

## Research Interests

My research interests are broad and varied, reflecting my curiosity about the cosmos. Here are a few areas I am particularly passionate about:

<div class="research-grid">
  <div class="research-item">
    <h4>Radio Astronomy</h4>
    <p>Exploring the universe through the radio waves it emits, uncovering the secrets of celestial bodies.</p>
  </div>

  <div class="research-item">
    <h4>Big Data Astronomy</h4>
    <p>Leveraging massive datasets to understand cosmic phenomena and patterns across the universe.</p>
  </div>

  <div class="research-item">
    <h4>Astronomical Instrumentation and Technologies</h4>
    <p>Developing and utilizing advanced technologies to enhance our observational capabilities.</p>
  </div>

  <div class="research-item">
    <h4>Exoplanets Formation and Detection</h4>
    <p>Investigating the birth and discovery of planets beyond our solar system.</p>
  </div>
</div>

## A Personal Quote

> "In the vast expanse of the cosmos, every discovery is a reminder of our humble beginnings and the limitless possibilities that await." - Anumanchi Agastya Sai Ram Likhit

Thank you for visiting my page. Feel free to connect with me to discuss ideas, research, or potential collaborations. Together, let's unravel the mysteries of the universe!

