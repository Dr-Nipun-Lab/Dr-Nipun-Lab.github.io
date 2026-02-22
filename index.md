---
layout: splash
title: "Dr. Nipun Lab"
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/lab_banner.jpg
excerpt: " Alcohol-Driven Hepatic Injury Spectrum • Systems Biology • Multi-Omics • Clinical Proteomics • Bioinformatics • AI/ML"
---

# Welcome to Dr. Nipun Lab

We are a translational research group in the **Department of Hepatology at Post Graduate Institute of Medical Education and Research (PGIMER), Chandigarh** focused on understanding Alcohol associated liver Diseases (ALD), Acute on chronic liver failure (ACLF) and infections 
through **Clinical trials, Clinical proteomics, Bioinformatics, Multi-omics, Systems biology, and Cognitive computing**.

**Our primary focus areas include:**
- Clinical trials in ALD
- clinical trajectory analysis
- Clinical prediction modeling
- Diagnostic and prognostic Biomarker discovery
- Point of care device development
- Multiomics (Proteomics, Transcriptomics, Genomics)  
- Multi-omics integration
- Host- microbial interaction in cirrhosis
- Microbial diversity & metaproteomics in liver diseases
- Molecular and experimental hepatology
- AI/ML pipelines and workflows

Explore our **Members**, **Research**, **Publications**, and **Tools** using the top menu.

<div class="home-wrapper">

  <div class="home-main">
  </div>

  <!-- RIGHT SIDEBAR -->
  <div class="home-sidebar">

    <!-- WHAT'S NEW -->
    <div class="home-panel">
      <h3 class="panel-title">What's New</h3>
      <div class="panel-scroll" id="newsScroll">

        <div class="panel-item">Lab website launched</div>
        <div class="panel-item">New ACLF cohort recruitment started</div>
        <div class="panel-item">Paper submitted to Hepatology</div>
        <div class="panel-item">Conference presentation accepted</div>

      </div>
    </div>

    <!-- PODCASTS -->
    <div class="home-panel">
      <h3 class="panel-title">Podcasts</h3>
      <div class="panel-scroll" id="podcastScroll">

        <div class="panel-item">Episode 1 — ACLF overview</div>
        <div class="panel-item">Episode 2 — Microbiome in cirrhosis</div>
        <div class="panel-item">Episode 3 — AI in hepatology</div>

      </div>
    </div>

  </div>
</div>

<style>

/* layout */
.home-wrapper{
  display:flex;
  gap:30px;
  margin-top:30px;
}

.home-main{
  flex:3;
}

.home-sidebar{
  flex:1;
  max-width:280px;
  display:flex;
  flex-direction:column;
  gap:25px;
}

/* panels */
.home-panel{
  border:1px solid #ddd;
  border-radius:10px;
  padding:10px;
  background:#fafafa;
  height:260px;
  overflow:hidden;
}

.panel-title{
  text-align:center;
  margin:5px 0 10px 0;
  font-weight:600;
}

/* scrolling area */
.panel-scroll{
  height:210px;
  overflow:hidden;
}

.panel-item{
  padding:8px 5px;
  border-bottom:1px solid #eee;
  font-size:0.9rem;
}

.panel-item:last-child{
  border-bottom:none;
}

</style>

<script>

function makeScroller(id, speed=0.35){
  const box=document.getElementById(id);
  let pause=false;

  function scroll(){
    if(!pause){
      box.scrollTop+=speed;
      if(box.scrollTop>=box.scrollHeight-box.clientHeight){
        box.scrollTop=0;
      }
    }
    requestAnimationFrame(scroll);
  }

  box.addEventListener("mouseenter",()=>pause=true);
  box.addEventListener("mouseleave",()=>pause=false);

  scroll();
}

makeScroller("newsScroll");
makeScroller("podcastScroll");

</script>
