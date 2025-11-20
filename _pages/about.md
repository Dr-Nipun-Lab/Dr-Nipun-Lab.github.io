---
title: "About Us"
permalink: /about/
layout: single
classes: wide
---


The **Dr. Nipun Lab** is a translational research group focused on decoding the biology of **acute hepatic decompensation, alcohol-associated liver diseases, and acute-on-chronic liver failure (ACLF)** through multi-omics and computational science.

We integrate **clinical proteomics, systems biology, microbial–host interaction profiling, and data-driven modeling** to uncover mechanisms that drive inflammation, immune dysfunction, organ failure, and mortality in critically ill patients.

## Our Research Focuses on 

### Clinical Proteomics  
We apply high-resolution mass spectrometry to study circulating host and microbial proteins in patients with acute and chronic liver diseases. Our research aims to identify dynamic protein biomarkers spanning both host and meta-proteomic signals that reflect inflammation, immune dysfunction, organ failure, and mortality risk. These protein signatures are evaluated for their clinical utility and mechanistic relevance.

---

### Multi-Omics Integration and Trajectory analysis 
We integrate transcriptomics, proteomics, and clinical datasets to gain systems-level insights into disease biology. Using methods such as early & late integration, WGCNA and Joint modelling we identify co-regulated gene–protein modules, Hub gene/proteins, temporal patterns, and cross-omic networks associated with disease severity, progression, and patient outcomes.

---

### Causal Inference  
Association alone is not enough; our lab employs causal modeling frameworks including Bayesian causal networks and Grain to infer directional relationships among genes, proteins, pathways, and clinical phenotypes. These models help uncover drivers of disease progression and allow mechanistically guided biomarker discovery.

---

### Microbial Diversity & Metaproteomics
We characterize microbial peptides and proteins circulating in patient plasma to understand how microbiota influence host immunity and organ dysfunction. By integrating microbial signals (Diversity and proteomics) with host transcriptomic and proteomic data, we investigate pathogen–host interactions that contribute to systemic inflammation, immune paralysis, and acute liver decompensation.

---

### Computational Method Development  
Our lab develops robust, reproducible computational workflows for multi-omics data processing and analysis. We build pipelines for quality control, normalization, integration, causal inference, module detection, and biomarker prioritization in R and Python. These tools support both internal research and collaborative projects across clinical and computational teams.

---

# ⭐ Achievements

Below are some highlights from our scientific, academic, and clinical research activities.

<div class="achievements-container">
  <div class="achievements-scroll" id="achievementsScroll">
    
    <!-- Add as many items as you want -->
    <div class="achievement-item">
      <img src="/assets/images/achievements/award1.jpg" alt="Achievement 1">
      <p>Best Research Award at EASL 2025</p>
    </div>

    <div class="achievement-item">
      <img src="/assets/images/achievements/award2.jpg" alt="Achievement 2">
      <p>Best Poster and oral presentation at INASL 2025</p>
    </div>

    <div class="achievement-item">
      <img src="/assets/images/achievements/award3.jpg" alt="Achievement 3">
      <p>Best oral presentation at APT 2025</p>
    </div>

    <!-- Duplicate for smooth infinite scroll -->
    <div class="achievement-item">
      <img src="/assets/images/achievements/award1.jpg" alt="Achievement 1">
      <p>Best Research Award at EASL 2025</p>
    </div>
    <div class="achievement-item">
      <img src="/assets/images/achievements/award2.jpg" alt="Achievement 2">
      <p>Best Poster and oral presentation at INASL 2025</p>
    </div>

  </div>
</div>

---
<style>
/* Achievements Panel Styling */
.achievements-container {
  width: 100%;
  overflow: hidden;
  position: relative;
  margin: 20px 0;
  border-radius: 10px;
  border: 1px solid #ddd;
  background: #fafafa;
}

.achievements-scroll {
  display: flex;
  gap: 20px;
  padding: 20px;
  animation: scrollLeft 25s linear infinite;
}

.achievement-item {
  min-width: 220px;
  text-align: center;
}

.achievement-item img {
  width: 200px;
  height: 130px;
  object-fit: cover;
  border-radius: 8px;
  border: 1px solid #ccc;
}

.achievement-item p {
  font-size: 0.9rem;
  margin-top: 8px;
  font-weight: 500;
}

/* Auto-scroll Animation */
@keyframes scrollLeft {
  from { transform: translateX(0); }
  to { transform: translateX(-50%); }
}
</style>

<script>
const scrollBox = document.getElementById("achievementsScroll");
scrollBox.addEventListener("mouseover", () => {
  scrollBox.style.animationPlayState = "paused";
});
scrollBox.addEventListener("mouseout", () => {
  scrollBox.style.animationPlayState = "running";
});
</script>
