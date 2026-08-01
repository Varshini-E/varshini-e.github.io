---
layout: page
permalink: /resume/
title: resume
nav: true
nav_order: 4
description:
_styles: >
  .resume-download {
    float: right;
    color: var(--global-theme-color);
    font-size: 1.4rem;
    margin-top: -0.2rem;
    transition: opacity 0.2s;
  }
  .resume-download:hover { opacity: 0.7; }

  /* ── Two-column wrapper ── */
  .resume-wrapper {
    display: grid;
    grid-template-columns: 130px 1fr;
    gap: 2.5rem;
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
  .resume-toc li { margin-bottom: 0.4rem; }
  .resume-toc a {
    display: block;
    font-size: 0.75rem;
    color: var(--global-text-color-light);
    text-decoration: none;
    padding-left: 0.7rem;
    transition: color 0.15s;
  }
  .resume-toc a:hover { color: var(--global-theme-color); }

  /* ── Section ── */
  .timeline-section { margin-bottom: 2.2rem; }
  .timeline-section > a[id] { display: block; scroll-margin-top: 5rem; }
  .timeline-section-title {
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--global-theme-color);
    border-bottom: 2px solid var(--global-theme-color);
    padding-bottom: 0.3rem;
    margin-bottom: 1rem;
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
    margin-bottom: 1rem;
  }
  .timeline-item:last-child { margin-bottom: 0; }
  /* ── Entry card box ── */
  .timeline-card {
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    padding: 0.8rem 1rem;
    background: var(--global-card-bg-color);
  }

  /* ── Org name + date (opposite ends) ── */
  .timeline-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 0.25rem;
    margin-bottom: 0.2rem;
  }
  .timeline-org {
    font-weight: 700;
    font-size: 0.95rem;
    color: var(--global-text-color);
  }
  .timeline-date {
    font-size: 0.75rem;
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
    margin-bottom: 0.5rem;
  }
  .timeline-role {
    font-size: 0.85rem;
    color: var(--global-text-color-light);
    font-style: italic;
  }
  .timeline-location {
    font-size: 0.75rem;
    color: var(--global-text-color-light);
    white-space: nowrap;
  }
  .timeline-location i {
    color: var(--global-theme-color);
    margin-right: 0.2rem;
    font-size: 0.68rem;
  }

  /* ── Bullet points ── */
  .timeline-bullets {
    margin: 0;
    padding-left: 1.1rem;
    font-size: 0.83rem;
    color: var(--global-text-color);
  }
  .timeline-bullets li { margin-bottom: 0.3rem; line-height: 1.55; }

  /* ── Skills ── */
  .skills-grid {
    display: grid;
    grid-template-columns: max-content 1fr;
    gap: 0.45rem 1rem;
    font-size: 0.85rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    padding: 0.8rem 1rem;
    background: var(--global-card-bg-color);
  }
  .skills-label { font-weight: 600; color: var(--global-theme-color); white-space: nowrap; }
  .skills-value { color: var(--global-text-color); }

  /* ── Publications ── */
  .pub-list {
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    padding: 0.8rem 1rem;
    background: var(--global-card-bg-color);
  }
  .pub-item {
    font-size: 0.83rem;
    color: var(--global-text-color);
    margin-bottom: 0.6rem;
    line-height: 1.6;
    padding-left: 1rem;
    position: relative;
  }
  .pub-item:last-child { margin-bottom: 0; }
  .pub-item::before { content: "▸"; position: absolute; left: 0; color: var(--global-theme-color); }
  .pub-title { font-weight: 600; }
---

<a href="{{ '/assets/pdf/Varshini_Elangovan_Resume.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" class="resume-download" title="Download PDF">
  <i class="fa-solid fa-file-pdf"></i>
</a>

<div class="resume-wrapper">

<!-- ── LEFT: Table of Contents ───────────────────────── -->
<nav class="resume-toc">
  <ul>
    <li><a href="#education">Education</a></li>
    <li><a href="#work">Work Experience</a></li>
    <li><a href="#research">Research</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#publications">Publications</a></li>
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
          <span class="timeline-date">Expected Dec 2026</span>
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
          <span class="timeline-role">B.E. (Honors) in Computer Science &amp; Engineering</span>
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
          <span class="timeline-date">Jul 2022 &ndash; Jul 2025</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Software Engineer III (Nov 2024 &ndash; Jul 2025); Software Engineer II (Jul 2022 &ndash; Oct 2024)</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Hyderabad, India</span>
        </div>
        <ul class="timeline-bullets">
          <li>Drove risk strategy design for Google Wallet via PIX in Brazil, developing mitigation frameworks to reduce transaction losses across P2P and P2M payment flows for the August 2024 launch.</li>
          <li>Designed and deployed feature engineering pipelines in Java and rule-based decision policies in Python integrating ML model outputs for real-time transaction risk assessment across Google Pay US and Wallet Brazil.</li>
          <li>Owned design, implementation, and validation of payment risk infrastructure extensions for recipients external to Google, including entity representation, control propagation, and downstream enforcement across the transaction pipeline.</li>
          <li>Engineered ML pipelines for delinquency fraud detection on Stored Value transactions, spanning data simulation, GBDT model training in TensorFlow and offline evaluation against production baselines.</li>
          <li>Built real-time monitoring dashboards and operational runbooks for regulatory compliance in Brazil. Collaborated with Trust &amp; Safety and Product teams on post-launch metrics, thresholds and customer impact.</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Goldman Sachs</span>
          <span class="timeline-date">Jun 2021 &ndash; Jul 2021</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Summer Analyst</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Remote (Bengaluru, India)</span>
        </div>
        <ul class="timeline-bullets">
          <li>Created a Python-based data curation and analysis tool converting JSON inputs into multiple outputs for GS proprietary systems. Integrated into ETL workflows, optimizing a 2-week process to under one minute.</li>
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
          <span class="timeline-org">Forge Lab (Prof. Virginia Smith), Carnegie Mellon University</span>
          <span class="timeline-date">May 2026 &ndash; Present</span>
        </div>
        <div class="timeline-subline">
          <span class="timeline-role">Graduate Student Researcher (LLM Safety and Alignment)</span>
          <span class="timeline-location"><i class="fa-solid fa-location-dot"></i>Pittsburgh, PA</span>
        </div>
        <ul class="timeline-bullets">
          <li>Developing post-training interventions for LLM alignment, focused on identifying and suppressing unsafe persona-driven behaviours through on-policy consistency training and RL.</li>
          <li>Conducting a user study for <a href="https://open-reflection.com/" target="_blank" rel="noopener noreferrer">Safety Nudges</a>, a real-time Chrome extension that audits chatbot conversations and surfaces contextual warnings for overconfidence, sycophancy, anthropomorphization and unsafe responses.</li>
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
          <li>Developed geometry-guided visual token pruning methods for multi-view 3D Visual Question Answering with 2D Vision-Language models, reducing inference cost by 60%, FLOPs by 88%, and KV-cache usage by 86% while maintaining comparable benchmark accuracy (in collaboration with Meta Reality Labs). Preprint coming soon.</li>
          <li>Working on safety benchmarking for Vision-Language Action models (in collaboration with Fujitsu Research).</li>
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
          <li>Trained semantic segmentation models in PyTorch for depth estimation from simulated colonoscopy images as part of the KLIV group and studied effective post-processing techniques. Presented at the MICCAI 2022 Endoscopic Vision Challenge.</li>
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
          <li>Developed a vision-only student agent from distillation of a full-state teacher policy for camera-based robotic manipulation on MetaWorld tasks. Achieved 90% of full-state teacher performance via teacher-guided RL with imitation learning.</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Environmental ML: Modelling Sequential Disaster Cascades</span>
          <span class="timeline-date">Jan 2026 &ndash; Apr 2026</span>
        </div>
        <ul class="timeline-bullets">
          <li>Built an end-to-end disaster cascade prediction pipeline on 15 years of NOAA Storm Events data, using multilabel classification, weather embedded neural networks and graph neural networks to model rare secondary hazards and spatial cascade patterns.</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-card">
        <div class="timeline-header">
          <span class="timeline-org">Adaptive Day Planner: LLM-Based Task Scheduling and Voice Agent</span>
          <span class="timeline-date">Feb 2026</span>
        </div>
        <ul class="timeline-bullets">
          <li>Built an AI-powered adaptive planner using Mistral LLMs, FastAPI and Eleven Labs speech APIs to dynamically schedule tasks, replan sessions based on user feedback and support focus sessions via conversational body doubling. (Mistral AI Worldwide Hackathon, SF)</li>
        </ul>
      </div>
    </div>

  </div>
</div>

<!-- PUBLICATIONS -->
<div class="timeline-section">
  <a id="publications"></a>
  <div class="timeline-section-title">Publications</div>
  <div class="pub-list">
    <div class="pub-item">
      <span class="pub-title">SimCol3D - 3D reconstruction during colonoscopy challenge</span>, A. Rau, S. Bano, Y. Jin, Varshini Elangovan, et al. <em>Medical Image Analysis</em>, 2024. <a href="https://doi.org/10.1016/j.media.2024.103195" target="_blank" rel="noopener noreferrer">doi: 10.1016/j.media.2024.103195</a>
    </div>
    <div class="pub-item">
      <span class="pub-title">Reverse Image Search Engine for Garment Industry</span>, Anushri Eswaran and Varshini E. <em>8th International Conference on Advanced Computing and Communication Systems (ICACCS)</em>, 2022. <a href="https://doi.org/10.1109/ICACCS54159.2022.9785089" target="_blank" rel="noopener noreferrer">doi: 10.1109/ICACCS54159.2022.9785089</a>
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
    <span class="skills-value">PyTorch, TensorFlow, Keras, NumPy, Pandas, scikit-learn, Hugging Face, OpenCV, Gymnasium</span>
    <span class="skills-label">Developer Tools</span>
    <span class="skills-value">Weights &amp; Biases, Docker, Git, FastAPI</span>
    <span class="skills-label">Research Interests</span>
    <span class="skills-value">VLMs, LLMs, post-training, RL, multimodal reasoning, technical AI safety</span>
  </div>
</div>

</div><!-- end resume-content -->
</div><!-- end resume-wrapper -->

