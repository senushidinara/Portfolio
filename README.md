# 🌌 Senushi's Galactic Portfolio – Interactive README

Welcome to my galaxy! Explore my projects, skills, and achievements in a **living, interactive experience**.

---

## 🚀 Galactic Projects – Collapsible Universe

<details>
<summary>🛰 NeuroGuard – Cognitive Sentinel</summary>

**Overview:**  
Real-time monitoring system for early detection of cognitive patterns using EEG and AI.

**Interactive Features:**  
- Animated data streams with **GSAP**  
- Hover to reveal hidden project milestones  
- Clickable buttons to simulate “data pulses”  
- Ambient brainwave sounds triggered on hover  

</details>

<details>
<summary>🌟 Stardust Academy – Neural Constellations</summary>

**Overview:**  
Mentorship platform gamifying STEM learning and AI exploration.

**Interactive Features:**  
- Collapsible skill trees that glow when hovered  
- Dynamic radar charts animated with **Chart.js**  
- Hidden tooltips with project stories  
- Ambient cosmic background sounds  

</details>

<details>
<summary>🧠 Cognitive Digital Twin – NASA Mission</summary>

**Overview:**  
Digital twin for astronauts tracking cognitive performance in space.

**Interactive Features:**  
- Motion-controlled 3D brain model with **Three.js**  
- Toggle layers of neuron activity with collapsibles  
- Glowing particle effects representing neuron firing  
- Sound effects of space/mission events  

</details>

---

## 📊 Skills – Constellation Charts

<div id="skill-charts" style="width:100%; height:400px;"></div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('skill-charts').getContext('2d');
const myChart = new Chart(ctx, {
    type: 'radar',
    data: {
        labels: ['AI/ML', 'WebGL/3D', 'Frontend Animations', 'Game Design', 'Data Visualization'],
        datasets: [{
            label: 'Senushi Skill Intensity',
            data: [95, 85, 98, 80, 90],
            fill: true,
            backgroundColor: 'rgba(58,123,213,0.2)',
            borderColor: '#3a7bd5',
            pointBackgroundColor: '#fff',
            pointBorderColor: '#3a7bd5',
            pointHoverBackgroundColor: '#3a7bd5'
        }]
    },
    options: { responsive: true, scales: { r: { angleLines: { display: true }, suggestedMin: 0, suggestedMax: 100 } } }
});
</script>

> Hover over chart points to see hidden skill descriptions (use GitHub Pages for full interactivity).

---

## 🏆 Achievements – Motion & Reveal

<details>
<summary>Hackathon Wins & Recognition</summary>

- Interactive badges that glow on hover  
- Sliding panels reveal extra context  
- Click to reveal mini-video demos of projects  
- Cosmic sound triggers for each achievement  

</details>

<details>
<summary>Mentorship & Workshops</summary>

- Collapsible timeline of events  
- Animated icons for each milestone  
- Hidden “Easter egg” insights appear when hovered  
- Ambient starfield background with motion  

</details>

---

## ⚡ Motion, Sound & Interactivity Notes

- **GSAP:** smooth fade-ins, sliding panels, rotating nodes  
- **Three.js:** 3D starfield/galaxy background  
- **Chart.js / D3.js:** animated radar charts  
- **CSS Animations:** hover, glow, slide, pulse effects  
- **Collapsible `<details>`:** for story sections, skill trees, achievements  
- **SSML Integration:** optional voiceover triggers on hover or click  
- **Interactive Sounds:** hover/click triggers for cosmic ambiance, project effects  

---

---

## 🌌 Summary

This **all-in-one interactive README** combines **storytelling, sci-fi cosmic theme, interactivity, motion, sound, and collapsible elements**. It is designed to:  

- Engage judges immediately  
- Show **full technical range** (frontend, animations, charts, 3D, audio)  
- Serve as a **futuristic, personal digital identity**  

---

**Built With:**  
HTML  
CSS  
JavaScript  
GSAP  
Three.js  
Chart.js  
D3.js  
SSML  
Firebase  
Vercel  
Netlify  
GitHub Pages
