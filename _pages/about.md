---
title: "About Us"
permalink: /about/
layout: single
classes: wide
---

<div class="about-wrapper">

<div class="about-main">

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

</div> <!-- end about-main -->
---

<!-- ⭐ RIGHT SIDEBAR ACHIEVEMENTS ⭐ -->
<div class="about-sidebar">

<h3 style="text-align:center; margin-top:0;">Achievements</h3>

<div class="achievements-vertical" id="achievementsVertical">

  <div class="ach-item">
    <img src="/assets/images/achievements/award1.jpg">
    <p>Dr. Parminder received best Research Award EASL 2025</p>
  </div>

  <div class="ach-item">
    <img src="/assets/images/achievements/award2.jpg">
    <p>Dr. Nipun, Dr. Parminder and Pratibha received best Oral presentation and best poster awards in INASL 2025</p>
  </div>

  <div class="ach-item">
    <img src="/assets/images/achievements/award3.jpg">
    <p>Pratibha received best oral presentation award at APT 2025</p>
  </div>


  <!-- Duplicate for smooth loop -->
  <div class="ach-item">
    <img src="/assets/images/achievements/award1.jpg">
    <p>Dr. Parminder received best Research Award EASL 2025</p>
  </div>

</div>

</div> <!-- end about-sidebar -->

</div> <!-- end about-wrapper -->


<style>
/* Two-column layout: main content + right sidebar */
.about-wrapper {
  display: flex;
  align-items: flex-start;
  gap: 20px;
}

/* Main content takes more space */
.about-main {
  flex: 3;
}

/* Right achievements sidebar */
.about-sidebar {
  flex: 1;
  max-width: 260px;
  border-left: 1px solid #ddd;
  padding-left: 15px;
  height: 600px;
  overflow: hidden;
  position: sticky;
  top: 20px;
}

/* Vertical auto-scrolling content */
.achievements-vertical {
  display: flex;
  flex-direction: column;
  gap: 20px;
  animation: scrollDown 25s linear infinite;
}

.ach-item img {
  width: 100%;
  height: 140px;
  object-fit: cover;
  border-radius: 8px;
  border: 1px solid #ccc;
}

.ach-item p {
  text-align: center;
  font-size: 0.85rem;
  margin-top: 6px;
}

/* Vertical auto-scroll keyframes */
@keyframes scrollDown {
  from { transform: translateY(0); }
  to { transform: translateY(-50%); }
}
</style>

<script>
const vscroll = document.getElementById("achievementsVertical");

vscroll.addEventListener("mouseover", () => {
  vscroll.style.animationPlayState = "paused";
});

vscroll.addEventListener("mouseout", () => {
  vscroll.style.animationPlayState = "running";
});
</script>
