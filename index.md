---
layout: page
title: Derrick Sun
---

<style>
  /* Global font size controls */
  body {
    font-size: 10px; /* Base font size for body text */
    line-height: 1.6; /* Improved readability */
  }
  
  /* Heading sizes */
  h1 { font-size: 2.5em; } /* 40px */
  h2 { font-size: 2em; }   /* 32px */
  h3 { font-size: 1.5em; } /* 24px */
  h4 { font-size: 1.25em; } /* 20px */
  h5 { font-size: 1.1em; }  /* 17.6px */
  h6 { font-size: 1em; }    /* 16px */
  
  /* Paragraph and list text */
  p, li, div {
    font-size: 1em; /* 16px - matches body */
  }
  
  /* Links */
  a {
    font-size: inherit;
  }
  
  /* Inline display for specific elements */
  h2, h3, h4 {
    display: inline;
  }
  
  /* Special styling for experience h4 elements to align dates to the right */
  .experience-section h4 {
    display: flex !important;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    margin: 0;
  }
  
  /* Special styling for education h4 elements to align dates to the right */
  .education-section h4 {
    display: flex !important;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    margin: 0;
  }
  
  /* Ensure summary elements work properly with the flexbox layout */
  .experience-section summary {
    cursor: pointer;
    width: 100%;
  }
  
  /* Style for the job title part */
  .experience-section h4 .job-title {
    display: inline-block;
    text-align: left;
  }
  
  /* Style for the date part */
  .experience-section h4 .job-date {
    display: inline-block;
    text-align: right;
    color: #666;
    font-weight: normal;
    margin-left: 25px;
    float: right;
  }
  
  /* Style for the education title part */
  .education-section h4 .job-title {
    display: inline-block;
    text-align: left;
  }
  
  /* Style for the education date part */
  .education-section h4 .job-date {
    display: inline-block;
    text-align: right;
    color: #666;
    font-weight: normal;
    margin-left: 25px;
    float: right;
  }
  
  /* Projects section styling to match experience section */
  .projects-section summary {
    cursor: pointer;
    width: 100%;
  }
  
  /* Education section styling to match projects section */
  .education-section summary {
    cursor: pointer;
    width: 100%;
  }
  
  /* Skills section styling to match other sections */
  .skills-section summary {
    cursor: pointer;
    width: 100%;
  }
  
  /* Normalize skills list spacing for consistent dropdown behavior */
  .skills-section ul {
    margin: 0;
    padding: 0;
  }
  
  .skills-section li {
    margin: 0;
    padding: 0;
  }
  
  /* Ensure default dropdown arrows are visible */
  summary::-webkit-details-marker {
    display: inline-block !important;
    color: inherit;
  }
  
  summary::marker {
    display: inline-block !important;
    color: inherit;
  }
  
  /* Alternative approach: force arrow display */
  details summary {
    list-style: disclosure-closed;
  }
  
  details[open] summary {
    list-style: disclosure-open;
  }
</style>


<p align="center">
<img src="./images/selfInSuit.jpg" alt="image of me" style="width:300px;"/>
</p>

## About Me

I am a graduate student at Purdue University, studying Computer Science. I am especially interested in machine learning and artificial intelligence. I plan to graduate in December 2025.

I got my Bachelor's degree from the University of California Berkeley, which I graduated from in 2024.

I am also on <a href="https://www.linkedin.com/in/derrick-sun-052130228/">LinkedIn</a>, and much of my work can be found on <a href="https://github.com/DerrickhSun">GitHub</a>.


<details open class="education-section">
  <summary><h2>My Education</h2></summary>

  <details>
    <summary>
      <h4><span class="job-title">Purdue University</span><span class="job-date">(2024-2025)</span></h4>
    </summary>
    <div style="text-align: justify">
    I am a Master's student at Purdue University studying Computer Science. I plan to graduate in December 2025. At Purdue, I have focused mainly on studying AI and machine learning, with a lesser emphasis on computer security, distributed systems, and compilers.</div>
  </details>

  <details>
    <summary>
      <h4><span class="job-title">University of California, Berkeley</span><span class="job-date">(2020-2024)</span></h4>
    </summary>
    <div style="text-align: justify">
    I earned my Bachelor's degree from the University of California, Berkeley, where I did a double major in Computer Science and Applied Math. As a Computer Science major, I focused on machine learning, AI, and algorithms. I also participated in in-context model research.<br><br>As a Applied Math major, I also studied statistics and data science.
    </div>
  </details>

  <details>
    <summary>
      <h4><span class="job-title">Westview High School</span><span class="job-date">(2016-2020)</span></h4>
    </summary>
    <div style="text-align: justify">
    I attended Westview High School.
    </div>
  </details>
</details>
<br>


<details open class="skills-section">
  <summary><h2>Skills</h2></summary>

  <ul class=skilllist>
        <li>Programming Languages: Python, Java, SQL, C/C++, R, MATLAB, Swift, JavaScript, HTML/CSS</li>
        <li>ML/AI Frameworks: PyTorch, TensorFlow, DSPy, Scikit-learn</li>
        <li>Data Tools: Pandas, NumPy, Matplotlib, Seaborn, RStudio, Jupyter</li>
        <li>Cloud & Databases: AWS S3, Redshift, PostgreSQL, MongoDB</li>
        <li>Development Tools: Git, Docker, Prefect, XCode, LaTeX, RISC-V</li>
      </ul>
</details>
<br>

<details open class="experience-section">
  <summary>
    <h2> My Experience </h2>
  </summary>

  <details>
    <summary>
      <h4><span class="job-title">Purdue University: Teaching Assistant</span><span class="job-date">(August 2024 - May 2025)</span></h4>
    </summary>
    <div style="text-align: justify">
    I worked as a graduate teacher's assistant at Purdue University for CS 361 (Great Issues In Computer Science) and 
    CS 182 (Foundations of Computer Science). As a GTA, I designed grading rubrics, led undergraduate assistants in 
    grading assignments, and provided consistent professional correspondence with students and the professors in a 
    timely manner.</div>
  </details>

  <details>
    <summary>
      <h4><span class="job-title">Bridger Investment Partners: Data Scientist Intern</span><span class="job-date">(May 2024 - August 2024)</span></h4>
    </summary>
    <div style="text-align: justify">
    I interned with Bridger Investment Partners, an investment firm that focuses on mortgages. 
    I worked as a data scientist, using Prefect to automate their data processing. 
    I also analyzed mortgage data from AWS S3 and Redshift using Python, SQL, and statistics.</div>
  </details>

  <details>
    <summary>
      <h4><span class="job-title">NewsBreak: iOS Developer Intern</span><span class="job-date">(May 2022 - August 2022)</span></h4>
    </summary>
    <div style="text-align: justify">
    I interned at NewsBreak, a company that focuses on providing news tailored to a user's 
    location and interests through their mobile app, NewsBreak, under my mentor, Zhengwen Wang. I worked as a front-end programmer for the NewsBreak iOS app, where I used XCode to design a part of the app and became proficient in Swift, data fetching, and programmatic coding in UIKit. The part I designed will be released as the discover-search page of the app.</div>
  </details>

  <details>
    <summary>
      <h4><span class="job-title">UCSD Nanomaterials and Nanomedicine Laboratory</span><span class="job-date">(June 2019 - March 2020)</span></h4>
    </summary>
    <div style="text-align: justify">
    I interned at UCSD as a Research Analyst Intern. I implemented modern cell membrane coating technology, including cell counting, pating, culturing, and membrane derivation procedures. I made use of lab equipment such as autoclaves and pipettes. Our results were published in an academic journal: "<a href="https://doi.org/10.1002/btm2.10187">Cartilage-targeting ultrasmall lipid-polymer hybrid nanoparticles for the prevention of cartilage degradation</a>," <i>Bioengineering & Translational Medicine, 2021; 6; e10187.</i></div>
  </details>
</details>
<br>


<details open class="projects-section">
  <summary><h2>My Projects</h2></summary>

  <details open class="projects-section">
    <summary><h3>Recent Projects</h3></summary>

  <details>
    <summary>
      <h4><a href="https://github.com/DerrickhSun/DerrickhSun.github.io">Website Construction</a></h4>
    </summary>
    <div style="text-align: justify">
    This webpage was coded with a mix of markdown, HTML, and Javascript, as well a Bootstrap theme from <a href="https://github.com/nicolas-van/bootstrap-4-github-pages">here</a>. While I have continuously modified the page, it was last modified August 19th, 2025.
    </div>
  </details>

  <details>
    <summary>
      <h4><a href="https://github.com/DerrickhSun/MushroomProject">Deep Learning for Mushroom Classification (2025)</a></h4>
    </summary>
    <div style="text-align: justify">
    I developed neural network models and assisted in the development of decision tree and naive bayes models to classify mushroom edibility, and was able to achieve over 90% accuracy on all three. I also helped apply LIME to enhance model interpretability, which showed smell was one of the most dominant factors.</div>
  </details>

  <details>
    <summary>
      <h4><a href="https://github.com/DerrickhSun/Uncertainty-Project">Uncerainty Evaluation with Neural Networks (2025)</a></h4>
    </summary>
    <div style="text-align: justify">
    I trained neural networks to estimate uncertainty in Walmart sales forecasts, evaluating model performance using quantile calibration error curves. I developed a neural network capable of predicting uncertainty within a 10% margin of error.</div>
  </details>
</details>

<details class="projects-section">
  <summary><h3>Older Projects</h3>
  </summary>

  <details>
    <summary>
      <h4><a href="https://su23-11-57a34b75dce1.herokuapp.com/">County Representatives Website (2023)</a></h4>
    </summary>
    <div style="text-align: justify">
      I wrote the code for an app that allows for the viewing of representatives of counties in the United States. Counties can be looked up by either name or by clicking on a map of the United States. News articles relevant to certain representatives can also be added. The code is written in a mix of Ruby, JavaScript, HTML, and CSS. Testing was done with Cucumber and Rubocop. I had two collaborators when writing this code.
    </div>
  </details>

  <details>
    <summary>
      <h4><a href="https://github.com/DerrickhSun/ProjectArk">Project Ark (2018)</a></h4>
    </summary>
    <div style="text-align: justify">
      A simple video game I made using inspiration from various other games. I started this game as a tool to practice my Java skills. The game is run from the driver file in src.
    </div>
  </details>
</details>