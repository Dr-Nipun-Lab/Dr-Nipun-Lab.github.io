---
title: "About Us"
permalink: /about/
layout: single
classes: wide
---

<div class="about-wrapper">

<!-- ⭐ MAIN CONTENT AREA ⭐ -->
<div class="about-main" markdown="1">

The **Dr. Nipun Lab** is a translational research group focused on decoding the biology of **acute hepatic decompensation, alcohol-associated liver diseases, and acute-on-chronic liver failure (ACLF)** through multi-omics and computational science.

We integrate **clinical proteomics, systems biology, microbial–host interaction profiling, and data-driven modeling** to uncover mechanisms that drive inflammation, immune dysfunction, organ failure, and mortality in critically ill patients.

---

## Our Research Focuses On 

### Clinical Proteomics  
We apply high-resolution mass spectrometry to study circulating host and microbial proteins in patients with acute and chronic liver diseases. Our research aims to identify dynamic protein biomarkers spanning both host and meta-proteomic signals that reflect inflammation, immune dysfunction, organ failure, and mortality risk.

---

### Multi-Omics Integration and Trajectory Analysis  
We integrate transcriptomics, proteomics, and clinical datasets to gain systems-level insights into disease biology. Using early & late integration, WGCNA, and joint modeling, we identify co-regulated gene–protein modules, hub gene/proteins, temporal patterns, and cross-omic networks associated with disease severity and outcomes.

---

### Causal Inference  
We employ causal modeling frameworks including Bayesian causal networks and Grain to infer directional relationships among genes, proteins, pathways, and clinical phenotypes.

---

### Microbial Diversity & Metaproteomics  
We characterize microbial peptides and proteins circulating in patient plasma to understand how microbiota influence host immunity and organ dysfunction. Integrating microbial signals with host omics allows us to investigate pathogen–host interactions that contribute to systemic inflammation, immune paralysis, and acute liver decompensation.

---

### Computational Method Development  
We build robust, reproducible workflows for quality control, normalization, integration, causal inference, module detection, and biomarker prioritization in R and Python. These tools support both internal research and collaborative projects.

</div> <!-- END about-main -->



<!-- ⭐ RIGHT SIDEBAR ACHIEVEMENTS ⭐ -->
<div class="about-sidebar">

<h3 class="ach-title">Achievements</h3>

<div class="achievements-vertical" id="achievementsVertical">

  <div class="ach-item">
    <img src="/assets/images/achievements/award1.jpg">
    <p>Dr. Parminder received Best Research Award, EASL 2025</p>
  </div>

  <div class="ach-item">
    <img src="/assets/images/achievements/award2.jpg">
    <p>Dr. Nipun, Dr. Parminder & Pratibha received Best Oral & Poster Awards, INASL 2025</p>
  </div>

  <div class="ach-item">
    <img src="/assets/images/achievements/award3.jpg">
    <p>Pratibha received Best Oral Presentation Award at APT 2025</p>
  </div>

  <!-- Duplicate for smooth loop -->
  <div class="ach-item">
    <img src="/assets/images/achievements/award1.jpg">
    <p>Dr. Parminder received Best Research Award, EASL 2025</p>
  </div>

</div>

</div> <!-- END about-sidebar -->

</div> <!-- END about-wrapper -->


<style>
/* Layout: main content + right sidebar */
.about-wrapper {
  display: flex;
  gap: 20px;
  align-items: flex-start;
}

/* Main content column */
.about-main {
  flex: 3;
}

/* Right achievements sidebar */
.about-sidebar {
  flex: 1;
  max-width: 260px;
  height: 600px;
  overflow: hidden;
  position: sticky;
  top: 20px;
  border-left: 1px solid #ddd;
  padding-left: 15px;
}

/* Achievements Title */
.ach-title {
  text-align: center;
  margin-top: 0;
  padding-bottom: 6px;
  background: #fff;
  z-index: 10;
  position: relative;
  font-weight: 600;
}

/* Vertical scrolling container */
.achievements-vertical {
  display: flex;
  flex-direction: column;
  gap: 20px;
  padding-top: 10px; /* prevents overlap with heading */
  animation: scrollDown 25s linear infinite;
}

/* Achievement card styling */
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

/* Vertical auto-scroll animation */
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
