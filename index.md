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
  position: relative; /* For pseudo-elements */
}

.research-item h4 {
  margin-bottom: 5px; /* Decreased spacing between title and description */
  font-size: 18px;
  color: #333;
}

.research-item p {
  font-size: 14px;
  color: #666;
}
/* Border Animation */
.research-item::before {
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

.research-item:hover::before {
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
    <h4>Data Science in Astronomy & Astrophysics</h4>
    <p>Utilizing data science, machine learning, neural networks, and computer vision to explore and interpret vast astronomical datasets, driving forward the latest advancements in the field.</p>
  </div>


  <div class="research-item">
    <h4>Observational Cosmology</h4>
    <p>Studying the structure and evolution of the universe through observations and data analysis.</p>
  </div>
  
  <div class="research-item">
    <h4>Astronomical Instrumentation and Technologies</h4>
    <p>Developing and utilizing advanced technologies to enhance our observational capabilities.</p>
  </div>

  <div class="research-item">
    <h4>Exoplanets Formation and Detection</h4>
    <p>Investigating the birth and discovery of planets beyond our solar system.</p>
  </div>
  
  <div class="research-item">
    <h4>Multi-wavelength Observations</h4>
    <p>Employing observations across multiple wavelengths to gain a comprehensive understanding of celestial phenomena, revealing insights that single-wavelength studies cannot provide.</p>
  </div>

</div>

## A Thought-Provoking Quote

> "If the rate of expansion one second after the Big Bang had been smaller by even one part in a hundred thousand million million, it would have recollapsed before it reached its present size. On the other hand, if it had been greater by a part in a million, the universe would have expanded too rapidly for stars and planets to form."  ~ Stephen Hawking


Thank you for visiting my page. Feel free to connect with me to discuss ideas, research, or potential collaborations. Together, let's unravel the mysteries of the universe.
