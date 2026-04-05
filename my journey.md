---
layout: page
title: My Journey
permalink: /myjourney/
---
<style>
.journey-header {
  background: linear-gradient(135deg, #1a1a2e, #16213e);
  color: white;
  border-radius: 15px;
  padding: 40px;
  margin-bottom: 30px;
  text-align: center;
}
.journey-header h1 { font-size: 32px; margin-bottom: 10px; }
.journey-header p { color: #aaa; font-size: 16px; }
.intro-section {
  background: white;
  border-radius: 12px;
  padding: 30px;
  margin-bottom: 30px;
  box-shadow: 0 3px 15px rgba(0,0,0,0.08);
}
.intro-section h2 {
  color: #e94560;
  font-size: 22px;
  margin-bottom: 15px;
  border-bottom: 2px solid #f4f6f9;
  padding-bottom: 10px;
  display: flex;
  align-items: center;
  gap: 10px;
}
.intro-section p {
  line-height: 1.9;
  color: #555;
  font-size: 15px;
  margin-bottom: 15px;
}
.section-title {
  font-size: 22px;
  font-weight: bold;
  color: #1a1a2e;
  margin-bottom: 20px;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
}
.semester-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}
.semester-card {
  background: white;
  border-radius: 12px;
  padding: 30px;
  text-align: center;
  box-shadow: 0 3px 15px rgba(0,0,0,0.08);
  border-left: 4px solid #e94560;
  text-decoration: none;
  color: #1a1a2e;
  display: block;
  transition: transform 0.2s;
}
.semester-card:hover { transform: translateY(-5px); }
.semester-card h2 {
  font-size: 20px;
  margin-bottom: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
}
.semester-card p { font-size: 14px; color: #888; }
.icon-svg { width: 24px; height: 24px; display: inline-block; vertical-align: middle; }
</style>

<div class="journey-header">
  <h1>My Journey</h1>
  <p>Stories, experiences and learnings from my life</p>
</div>

<div class="intro-section">
  <h2>
    <svg class="icon-svg" viewBox="0 0 24 24" fill="none" stroke="#e94560" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <path d="M12 2L15.09 8.26L22 9.27L17 14.14L18.18 21.02L12 17.77L5.82 21.02L7 14.14L2 9.27L8.91 8.26L12 2Z"/>
    </svg>
    Beginning My Journey
  </h2>
  <p>
    My name is Umar, and I am from Faisalabad. My academic journey started with strong determination and a passion for learning.
    I completed my Matriculation with a Biology background from Allied School, where I secured 943 out of 1100 marks.
  </p>
  <p>
    After that, I continued my studies at Punjab College, where I completed my Intermediate (FSc Pre-Engineering)
    and achieved 922 out of 1200 marks. During this time, I developed a growing interest in engineering and technology.
  </p>
  <p>
    I applied for admission to UET Lahore with high hopes, but unfortunately, due to some mistakes in my application form,
    I was unable to secure admission there. It was a disappointing moment for me, but I did not let it stop my progress.
  </p>
  <p>
    Later, through the down-grading process, I successfully got admission to UET Faisalabad.
    This became a turning point in my life, giving me the opportunity to continue my journey in Computer Engineering.
  </p>
  <p>
    Today, I am focused on improving my skills in programming, problem-solving, and modern technologies.
    I strongly believe that challenges are part of growth, and with consistency and hard work,
    every goal can be achieved.
  </p>
</div>

<p class="section-title">
  <svg class="icon-svg" viewBox="0 0 24 24" fill="none" stroke="#1a1a2e" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"/>
    <path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"/>
  </svg>
  My Semesters
</p>

<div class="semester-cards">
  <a class="semester-card" href="/semester1/">
    <h2>
      <svg class="icon-svg" viewBox="0 0 24 24" fill="none" stroke="#e94560" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"/>
        <path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"/>
      </svg>
      Semester 1
    </h2>
    <p>My first semester experience</p>
  </a>

  <a class="semester-card" href="/semester2/">
    <h2>
      <svg class="icon-svg" viewBox="0 0 24 24" fill="none" stroke="#e94560" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <circle cx="12" cy="12" r="10"/>
        <polyline points="12 6 12 12 16 14"/>
      </svg>
      Semester 2
    </h2>
    <p>My second semester experience</p>
  </a>
</div>
