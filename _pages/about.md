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
.profile { margin-top: 0.5rem; margin-right: -3rem; }
.profile img { max-width: 210px; aspect-ratio: 1 / 1.25; object-fit: cover; object-position: bottom; }
.post .clearfix p {
  font-size: 0.9rem;
  font-weight: 400;
  -webkit-text-stroke: 0.25px currentColor;
}

@media (min-width: 768px) { #navbar .navbar-collapse { margin-right: -3rem; } }

.selected-work { clear: both; margin-top: 3rem; }
.selected-work h2 { font-weight: 700; font-size: 1.35rem; margin-bottom: 1.2rem; }
.work-item { padding: 1.2rem 0; border-bottom: 1px solid var(--global-divider-color); }
.work-item:first-of-type { border-top: 1px solid var(--global-divider-color); }
.work-kicker { font-size: 0.72rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.06em; color: var(--global-text-color); margin: 0 0 0.35rem; }
.work-with { font-size: 0.8rem; font-weight: 500; color: var(--global-text-color); margin: 0 0 0.5rem; }
.work-item h3 { font-size: 1.15rem; font-weight: 700; color: var(--global-theme-color); margin: 0 0 0.2rem; }
.work-sub { font-size: 0.92rem; font-weight: 500; margin: 0 0 0.5rem; }
.work-desc { font-size: 0.88rem; line-height: 1.6; margin: 0; max-width: 46rem; }
.work-links { display: flex; flex-wrap: wrap; gap: 0.4rem 1.1rem; margin-top: 0.7rem; font-size: 0.86rem; }
.selected-work { padding: 1.5rem 1.75rem 0.5rem; border-radius: 10px; background: color-mix(in srgb, var(--global-theme-color) 7%, transparent); }
.selected-work.research { margin-top: 1.75rem; }
.work-item.previously h3 { font-size: 1rem; color: var(--global-text-color); }
</style>

Hi, I'm a Master's student in Machine Learning at Carnegie Mellon University, graduating in December 2026.

I'm interested in foundation model behavior, post-training, and evaluation, particularly how training and data interventions shape model behavior and alignment. I'm also interested in multimodal models with a focus on reasoning and interaction with complex environments.

At CMU, I currently work with [Prof. Virginia Smith](https://www.cs.cmu.edu/~smithv/) and [Aashiq Muhamed](https://aashiqmuhamed.github.io/) on post-training interventions for LLM alignment, and previously worked with Prof. Fernando de la Torre at the [Human Sensing Lab](https://www.cmu.edu/cs/humansensing/pages/home.htm) on efficient multimodal reasoning for 3D VQA with 2D vision-language models. Before CMU, I spent three years at Google Hyderabad, as part of the Global Payments Platform Risk team, working on production risk systems for Google Pay and Google Wallet.

I'm currently seeking full-time roles in ML research and engineering starting January 2027.

<!--after-social-->

<section class="selected-work industry">
<h2>Industry Experience</h2>

<article class="work-item">
<p class="work-kicker">Jul 2022&ndash;Jul 2025</p>
<h3>Google</h3>
<p class="work-desc">As part of Google's Global Payments Platform Risk team in Hyderabad, I worked on real-time payment risk systems for Google Pay and Google Wallet, across fraud mitigation, feature engineering pipelines, ML and rule-based decision policies, and the engineering risk strategy for Wallet’s Brazil PIX launch in 2024. </p>
</article>

</section>

<section class="selected-work research">
<h2>Research Experience</h2>

<article class="work-item">
<p class="work-kicker">LLM post-training &amp; alignment &middot; CMU &middot; May 2026&ndash;present</p>
<p class="work-with">with Virginia Smith and Aashiq Muhamed</p>
<h3>Suppressing Persona-Conditioned Behaviors in LLMs</h3>
<p class="work-sub">How does post-training modify the accessibility of personas?</p>
<p class="work-desc">Investigating how persona-conditioned behaviors emerge across LLM post-training, how they can be selectively suppressed, and whether suppression generalizes across elicitation settings while preserving general capabilities.</p>
</article>

<article class="work-item">
<p class="work-kicker">Model character &amp; misalignment &middot; Sep 2026&ndash;present</p>
<h3>Domain-Specific Entanglements and Persona Characterization in Emergent Misalignment</h3>
<p class="work-sub">Research Fellow at SPAR (Supervised Program for Alignment Research), with <a href="https://praxis-research.org/">Praxis Research Group</a></p>
</article>

<article class="work-item">
<p class="work-kicker">Multimodal reasoning &amp; efficient inference &middot; CMU &middot; Oct 2025&ndash;Aug 2026</p>
<p class="work-with">with Fernando de la Torre &middot; in collaboration with Meta Reality Labs</p>
<h3>CoVeR: Coverage-Based Token Pruning for Multi-View 3D Reasoning in VLMs</h3>
<p class="work-sub">What visual information do VLMs need for multi-view 3D reasoning?</p>
<p class="work-desc">Multi-view reasoning can overwhelm 2D VLMs with redundant visual tokens. We developed a training-free, geometry-guided selection method that preserves spatial coverage across views, retaining 93.5% of full-token performance with about 8% of the visual tokens, reducing LLM compute by 13.3× and speeding up inference by 2.9×.</p>
<div class="work-links"><a href="https://arxiv.org/abs/2609.08345">Paper</a><a href="https://humansensinglab.github.io/CoVeR">Project Page</a></div>
</article>

<article class="work-item">
<p class="work-kicker">Human-centered AI safety &middot; CMU &middot; May&ndash;Sep 2026</p>
<p class="work-with">with Virginia Smith</p>
<h3>Safety Nudges: User-Facing Interventions for Real-Time AI Risk Awareness</h3>
<p class="work-sub">Can real-time warnings help users recognize problematic AI behavior?</p>
<p class="work-desc"> Conducted a two-week, 50-participant user field study of Safety Nudges, a Chrome extension that surfaces real-time warnings for behaviors such as sycophancy and overconfidence, examining how these warnings affect user trust and verification behavior. </p>
<div class="work-links"><a href="https://arxiv.org/abs/2609.26865">Paper</a><a href="https://open-reflection.com/">Project Page</a></div>
</article>

</section>

