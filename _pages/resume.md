---
layout: page
permalink: /resume/
title: resume
nav: true
nav_order: 4
description:
_styles: >
  /* ── Two-column wrapper ── */
  .resume-wrapper {
    display: grid;
    grid-template-columns: 150px 1fr;
    gap: 3rem;
    align-items: start;
  }
  @media (max-width: 576px) {
    .resume-wrapper { grid-template-columns: 1fr; }
    .resume-toc { display: none; }
  }

  /* ── Sticky TOC sidebar ── */
  .resume-toc {
    position: sticky;
    top: 5rem;
  }
  .resume-toc ul {
    list-style: none;
    padding: 0;
    margin: 0;
    border-left: 2px solid var(--global-divider-color);
  }
  .resume-toc li { margin-bottom: 0.5rem; }
  .resume-toc a {
    display: block;
    font-size: 0.82rem;
    font-weight: 500;
    color: var(--global-text-color-light);
    text-decoration: none;
    padding-left: 0.8rem;
    border-left: 2px solid transparent;
    margin-left: -2px;
    transition: color 0.15s, border-color 0.15s;
  }
  .resume-toc a:hover {
    color: var(--global-theme-color);
    border-left-color: var(--global-theme-color);
  }

  /* ── Section ── */
  .timeline-section { margin-bottom: 2.5rem; }
  .timeline-section > a[id] { display: block; scroll-margin-top: 5rem; }
  .timeline-section-title {
    font-size: 0.85rem;
    font-weight: 700;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--global-theme-color);
    border-bottom: 2px solid var(--global-theme-color);
    padding-bottom: 0.4rem;
    margin-bottom: 1.2rem;
  }

  /* ── Timeline track ── */
  .timeline {
    position: relative;
    padding-left: 1.6rem;
  }
  .timeline::before {
    content: "";
    position: absolute;
    left: 0.38rem;
    top: 0.5rem;
    bottom: 0;
    width: 2px;
    background: var(--global-divider-color);
  }

  /* ── Timeline entry ── */
  .timeline-item {
    position: relative;
    margin-bottom: 1.25rem;
  }
  .timeline-item:last-child { margin-bottom: 0; }
  /* ── Entry card box ── */
  .timeline-card {
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 1rem 1.25rem;
    background: var(--global-card-bg-color);
  }

  /* ── Org name + date (opposite ends) ── */
  .timeline-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 0.25rem;
    margin-bottom: 0.25rem;
  }
  .timeline-org {
    font-weight: 700;
    font-size: 1.05rem;
    color: var(--global-text-color);
  }
  .timeline-date {
    font-size: 0.8rem;
    font-variant-numeric: tabular-nums;
    color: var(--global-text-color-light);
    white-space: nowrap;
  }

  /* ── Role + location (opposite ends) ── */
  .timeline-subline {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 0.25rem;
    margin-bottom: 0.6rem;
  }
  .timeline-role {
    font-size: 0.9rem;
    font-weight: 500;
    color: var(--global-text-color);
  }
  .timeline-location {
    font-size: 0.8rem;
    color: var(--global-text-color-light);
    white-space: nowrap;
  }
  .timeline-location i {
    color: var(--global-theme-color);
    margin-right: 0.25rem;
    font-size: 0.72rem;
  }

  /* ── Bullet points ── */
  .timeline-bullets {
    margin: 0;
    padding-left: 1.15rem;
    font-size: 0.92rem;
    color: var(--global-text-color);
  }
  .timeline-bullets li { margin-bottom: 0.4rem; line-height: 1.65; }
  .timeline-bullets li:last-child { margin-bottom: 0; }

  /* ── Skills ── */
  .skills-grid {
    display: grid;
    grid-template-columns: max-content 1fr;
    gap: 0.6rem 1.25rem;
    font-size: 0.92rem;
    line-height: 1.5;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 1rem 1.25rem;
    background: var(--global-card-bg-color);
  }
  .skills-label {
    font-weight: 700;
    color: var(--global-theme-color);
    white-space: nowrap;
  }
  .skills-value { color: var(--global-text-color); }
---

<div class="resume-wrapper">

<!-- ── LEFT: Table of Contents ───────────────────────── -->
<nav class="resume-toc">
  <ul>
    <li><a href="#education">Education</a></li>
    <li><a href="#work">Work Experience</a></li>
    <li><a href="#research">Research</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#courses">Courses</a></li>
    <li><a href="#skills">Skills</a></li>
  </ul>
</nav>

<!-- ── RIGHT: Timeline content ───────────────────────── -->
<div class="resume-content">

<!-- EDUCATION -->
<div class="timeline-section">
  <a id="education"></a>
  <div class="timeline-section-title">Education</div>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Carnegie Mellon University</span>
          <span class="timeline-date">Dec 2026</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Master of Science in Machine Learning</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Pittsburgh, PA</span>
        </div>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Anna University, College of Engineering, Guindy</span>
          <span class="timeline-date">June 2022</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Bachelor of Engineering in Computer Science and Engineering (Honors)</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Chennai, India</span>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- WORK EXPERIENCE -->
<div class="timeline-section">
  <a id="work"></a>
  <div class="timeline-section-title">Work Experience</div>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Google</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Hyderabad, India</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Software Engineer III</span>
          <span class="timeline-date">Nov 2024 &ndash; Jul 2025</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Software Engineer II</span>
          <span class="timeline-date">Jul 2022 &ndash; Oct 2024</span>
        </div>
        <ul class="timeline-bullets">
          <li>Primary contributor to the risk strategy for Google Wallet's PIX launch in Brazil, designing mitigation frameworks for P2P and P2M payment flows that supported the product's August 2024 launch.</li>
          <li>Designed and deployed real-time risk evaluation pipelines in Java and Python, engineering features and integrating ML model outputs and rule-based policies across Google Pay US and Wallet Brazil.</li>
          <li>Extended payment risk infrastructure to support recipients external to Google, owning design, implementation, and validation of entity representations, control propagation, and downstream enforcement to expand coverage across new transaction flows.</li>
          <li>Engineered ML pipelines for delinquency fraud detection on stored value transactions, spanning data simulation, GBDT model training in TensorFlow, and offline evaluation against production baselines.</li>
          <li>Built real-time monitoring dashboards and operational runbooks for regulatory compliance in Brazil, enabling post-launch tracking of risk metrics, policy thresholds, and customer impact in collaboration with Trust &amp; Safety and Product teams.</li>
        </ul>
      </div>
    </div>

  </div>
</div>

<!-- RESEARCH EXPERIENCE -->
<div class="timeline-section">
  <a id="research"></a>
  <div class="timeline-section-title">Research Experience</div>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">SPAR (Supervised Program for Alignment Research)</span>
          <span class="timeline-date">Sep 2026 &ndash; Present</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Research Fellow</span>
        </div>
        <ul class="timeline-bullets">
          <li>Researching model character in large language models.</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Forge Lab (Prof. Virginia Smith), Carnegie Mellon University</span>
          <span class="timeline-date">May 2026 &ndash; Present</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Graduate Student Researcher (LLM Safety and Alignment)</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Pittsburgh, PA</span>
        </div>
        <ul class="timeline-bullets">
          <li>Developing and evaluating post-training interventions for 4B&ndash;8B LLMs using SFT, DPO, LoRA, and consistency training to suppress unsafe persona-driven behaviors and assess robustness across prompts and contexts.</li>
          <li>Designed and conducted a field study of <a href="https://open-reflection.com/" target="_blank" rel="noopener noreferrer">Safety Nudges</a>, a chatbot safety intervention for overconfidence, sycophancy and unsafe responses. Analyzed study outcomes and led manuscript preparation for ACM CHI 2027.</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Human Sensing Lab, Carnegie Mellon University (Prof. Fernando De la Torre)</span>
          <span class="timeline-date">Oct 2025 &ndash; Present</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Graduate Student Researcher (Multimodal Models)</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Pittsburgh, PA</span>
        </div>
        <ul class="timeline-bullets">
          <li>Developed geometry-guided visual token pruning for multi-view 3D Visual Question Answering with 2D Vision-Language Models, reducing inference cost by 60%, FLOPs by 88%, and KV-cache usage by 86% while maintaining comparable benchmark accuracy in collaboration with Meta Reality Labs. Under review at 3DV 2027 (<a href="https://arxiv.org/abs/2609.08345" target="_blank" rel="noopener noreferrer">preprint</a>).</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Indian Institute of Technology (IIT), Kharagpur</span>
          <span class="timeline-date">May 2022 &ndash; Sep 2022</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Deep Learning Intern</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Remote (Kharagpur, India)</span>
        </div>
        <ul class="timeline-bullets">
          <li>Trained segmentation models in PyTorch for depth estimation from simulated colonoscopy images as part of the KLIV group and studied effective post-processing techniques. Presented at the MICCAI 2022 Endoscopic Vision Challenge (<a href="https://doi.org/10.1016/j.media.2024.103195" target="_blank" rel="noopener noreferrer">SimCol3D, Medical Image Analysis, 2024</a>).</li>
        </ul>
      </div>
    </div>

  </div>
</div>

<!-- PROJECTS -->
<div class="timeline-section">
  <a id="projects"></a>
  <div class="timeline-section-title">Projects</div>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Watch &amp; Learn: Teacher-Student Distillation for Robotic Arm Tasks (<a href="https://github.com/Varshini-E/robotic-arm-manipulation" target="_blank" rel="noopener noreferrer">GitHub</a>)</span>
          <span class="timeline-date">Nov 2025 &ndash; Dec 2025</span>
        </div>
        <ul class="timeline-bullets">
          <li>Developed a vision-only student policy via distillation from a full-state teacher for camera-based robotic manipulation on MetaWorld tasks, achieving 90% of teacher performance through teacher-guided RL and imitation learning.</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Environmental ML: Modeling Sequential Disaster Cascades (<a href="https://github.com/ml-girls/cascading-disaster-prediction" target="_blank" rel="noopener noreferrer">GitHub</a>)</span>
          <span class="timeline-date">Jan 2026 &ndash; Apr 2026</span>
        </div>
        <ul class="timeline-bullets">
          <li>Built an end-to-end multilabel disaster cascade prediction pipeline on 15 years of NOAA Storm Events data, engineering ~170 temporal, spatial, and historical features and evaluating XGBoost, weather-embedded neural networks and GNNs to predict rare secondary hazards and spatial cascade patterns.</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Adaptive Day Planner: LLM-Based Task Scheduling and Voice Agent (<a href="https://github.com/Varshini-E/focus-bestie" target="_blank" rel="noopener noreferrer">GitHub</a>)</span>
          <span class="timeline-date">Feb 2026</span>
        </div>
        <ul class="timeline-bullets">
          <li>Built an AI-powered adaptive planner using Mistral LLMs, FastAPI and Eleven Labs speech APIs to dynamically schedule tasks, replan sessions based on user feedback and support focus sessions via conversational body doubling. (Mistral AI Worldwide Hackathon, SF)</li>
        </ul>
      </div>
    </div>

  </div>
</div>

<!-- COURSES -->
<div class="timeline-section">
  <a id="courses"></a>
  <div class="timeline-section-title">Courses</div>
  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">BlueDot Impact</span>
          <span class="timeline-date">Issued May 2026</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Technical AI Safety Course</span>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- SKILLS -->
<div class="timeline-section">
  <a id="skills"></a>
  <div class="timeline-section-title">Skills</div>
  <div class="skills-grid">
    <span class="skills-label">Languages</span>
    <span class="skills-value">Python, Java, C/C++, SQL, JavaScript</span>
    <span class="skills-label">ML / Deep Learning</span>
    <span class="skills-value">PyTorch, TensorFlow, Keras, NumPy, Pandas, scikit-learn, Hugging Face Transformers, Gymnasium</span>
    <span class="skills-label">Developer Tools</span>
    <span class="skills-value">Weights &amp; Biases, Docker, Git, FastAPI</span>
    <span class="skills-label">Research Interests</span>
    <span class="skills-value">LLM Post-Training, LLM Alignment, Multimodal Learning, Reinforcement Learning, AI Safety, VLMs, VLAs</span>
  </div>
</div>

</div><!-- end resume-content -->
</div><!-- end resume-wrapper -->

