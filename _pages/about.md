---
layout: about
title: about
permalink: /

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Spectral:wght@500;600;700&family=Inter:wght@400;500;600&display=swap');

body { font-family: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; }
.post-title, .selected-work h2, .work-item h3 { font-family: "Spectral", Georgia, serif; letter-spacing: -0.01em; }
.post-title, .post-title .font-weight-bold { font-weight: 700; }

.profile { margin-top: 0.3rem; margin-left: 0.9rem; }
.profile img { max-width: 210px; aspect-ratio: 1 / 1.12; object-fit: cover; object-position: bottom; }
.post .clearfix p { font-size: 0.92rem; line-height: 1.6; }

.post-header { margin-bottom: 1.4rem; }
.post-title { margin-bottom: 0.4rem; }
.header-links { display: flex; flex-wrap: wrap; gap: 0.35rem 1.4rem; margin: 0; font-size: 0.88rem; font-weight: 500; }
.header-links a { color: var(--global-text-color-light); text-decoration: none; transition: color 0.15s; }
.header-links a:hover { color: var(--global-theme-color); text-decoration: none; }
.header-links i { margin-right: 0.4rem; font-size: 0.95em; }

.selected-work { clear: both; margin-top: 1.5rem; }
.selected-work h2 {
  font-size: 1.45rem; font-weight: 600; margin: 0 0 1rem; color: var(--global-text-color);
  padding-bottom: 0.35rem; border-bottom: 2px solid color-mix(in srgb, var(--global-theme-color) 35%, transparent);
}
.work-item { margin-bottom: 1.5rem; }
.work-item h3 { font-size: 1.2rem; font-weight: 600; line-height: 1.3; margin: 0 0 0.25rem; color: var(--global-theme-color); }
.work-meta { font-size: 0.8rem; font-weight: 500; color: var(--global-text-color-light); margin: 0 0 0.4rem; }
.work-desc { font-size: 0.88rem; line-height: 1.6; margin: 0; }
.work-links { display: flex; flex-wrap: wrap; gap: 0.3rem 1rem; margin-top: 0.4rem; font-size: 0.84rem; font-weight: 600; }
.work-links a { text-decoration: underline; text-underline-offset: 3px; }
</style>

Hi, I'm a Master's student in Machine Learning at Carnegie Mellon University, graduating in December 2026.

I'm interested in foundation model behavior, post-training, and evaluation, particularly how training and data interventions shape model behavior and alignment. I'm also interested in multimodal models and reinforcement learning, especially for reasoning and interaction with complex environments.

At CMU, I currently work with [Prof. Virginia Smith](https://www.cs.cmu.edu/~smithv/) and [Aashiq Muhamed](https://aashiqmuhamed.github.io/) to understand persona-conditioned behaviors in LLM post-training, and previously worked with Prof. Fernando de la Torre at the [Human Sensing Lab](https://www.cmu.edu/cs/humansensing/pages/home.htm) on efficient multimodal reasoning for 3D VQA with 2D vision-language models. Before CMU, I spent three years at Google Hyderabad, as part of the Global Payments Platform Risk team, working on production risk systems for Google Pay and Google Wallet.

I'm currently seeking full-time roles in ML research and engineering starting January 2027.

I'm happy to chat, so feel free to reach out about anything :)

<!--after-social-->

<section class="selected-work">
<h2>Industry Experience</h2>

<article class="work-item">
<h3>Google</h3>
<p class="work-meta">Software Engineer &middot; Hyderabad &middot; Jul 2022&ndash;Jul 2025</p>
<p class="work-desc">As part of Google's Global Payments Platform Risk team, I worked on real-time payment risk systems for Google Pay and Google Wallet, across fraud mitigation, feature engineering pipelines, ML and rule-based decision policies, and the engineering risk strategy for Wallet's Brazil PIX launch in 2024.</p>
</article>

</section>

<section class="selected-work">
<h2>Research Experience</h2>

<article class="work-item">
<h3>Suppressing Persona-Conditioned Behaviors in LLMs</h3>
<p class="work-meta">Forge Lab, CMU &middot; May 2026&ndash;Present</p>
<p class="work-desc">Investigating how persona-conditioned behaviors emerge across LLM post-training, how they can be selectively suppressed, and whether suppression generalizes across elicitation settings while preserving general capabilities.</p>
</article>

<article class="work-item">
<h3>Domain-Specific Entanglements and Persona Characterization in Emergent Misalignment</h3>
<p class="work-meta">SPAR Research Fellow &middot; with <a href="https://praxis-research.org/">Praxis Research Group</a> &middot; Sep 2026&ndash;Present</p>
<p class="work-desc">Exploring how training domain and inferred personas relate to emergent misalignment through character inference and roleplay evaluations.</p>
</article>

<article class="work-item">
<h3>CoVeR: Coverage-Based Token Pruning for Multi-View 3D Reasoning in VLMs</h3>
<p class="work-meta">Human Sensing Lab, CMU &middot; Oct 2025&ndash;Aug 2026</p>
<p class="work-desc">We developed a training-free, geometry-guided token selection method for multi-view 3D reasoning with 2D VLMs. The method retains 93.5% of full-token performance with about 8% of the visual tokens, reducing LLM compute by 13.3&times; and speeding up inference by 2.9&times;.</p>
<div class="work-links"><a href="https://arxiv.org/abs/2609.08345">Paper</a><a href="https://humansensinglab.github.io/CoVeR">Project Page</a></div>
</article>

<article class="work-item">
<h3>Safety Nudges: User-Facing Interventions for Real-Time AI Risk Awareness</h3>
<p class="work-meta">Forge Lab, CMU &middot; May&ndash;Sep 2026</p>
<p class="work-desc">Conducted a two-week, 50-participant field study of a Chrome extension that surfaces real-time warnings for behaviors such as sycophancy and overconfidence, examining how they affect user trust and verification behavior.</p>
<div class="work-links"><a href="https://arxiv.org/abs/2609.26865">Paper</a><a href="https://open-reflection.com/">Project Page</a></div>
</article>

</section>
