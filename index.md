---
layout: splash
title: "Dr. Nipun Lab"
permalink: /
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/lab_banner.jpg
excerpt: "Alcohol-Driven Hepatic Injury Spectrum • Systems Biology • Multi-Omics • Clinical Proteomics • Bioinformatics • AI/ML"
---

# Welcome to Dr. Nipun Lab

<div class="home-wrapper">

  <!-- LEFT MAIN CONTENT -->
  <div class="home-main">

  <p>
  We are a translational research group in the <strong>Department of Hepatology at Post Graduate Institute of Medical Education and Research (PGIMER), Chandigarh</strong> focused on understanding Alcohol Associated Liver Diseases (ALD), Acute-on-Chronic Liver Failure (ACLF), and infections through <strong>Clinical trials, Clinical proteomics, Bioinformatics, Multi-omics, Systems biology, and AI-driven modeling</strong>.
  </p>

  <p><strong>Our primary focus areas include:</strong></p>

  <ul>
    <li>Clinical trials in ALD and ACLF</li>
    <li>Clinical trajectory analysis</li>
    <li>Clinical prediction modeling</li>
    <li>Diagnostic and prognostic biomarker discovery</li>
    <li>Point-of-care device development</li>
    <li>Multi-omics (Proteomics, Transcriptomics, Genomics)</li>
    <li>Multi-omics integration</li>
    <li>Host–microbial interaction in cirrhosis</li>
    <li>Microbial diversity & metaproteomics</li>
    <li>Molecular and experimental hepatology</li>
    <li>AI/ML pipelines and workflows</li>
  </ul>

  <p>
  Explore our <strong>Members</strong>, <strong>Research</strong>, <strong>Publications</strong>, and <strong>Tools</strong> using the top navigation menu.
  </p>

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

/* Layout */
.home-wrapper{
  display:flex;
  gap:40px;
  margin-top:30px;
  align-items:flex-start;
}

.home-main{
  flex:3;
}

.home-sidebar{
  flex:1;
  max-width:300px;
  display:flex;
  flex-direction:column;
  gap:25px;
}

/* Panels */
.home-panel{
  border:1px solid #e1e1e1;
  border-radius:10px;
  padding:12px;
  background:#fafafa;
  height:280px;
  overflow:hidden;
  box-shadow:0 2px 8px rgba(0,0,0,0.05);
}

.panel-title{
  text-align:center;
  margin:5px 0 12px 0;
  font-weight:600;
}

/* Scroll Area */
.panel-scroll{
  height:220px;
  overflow:hidden;
}

.panel-item{
  padding:8px 6px;
  border-bottom:1px solid #eee;
  font-size:0.92rem;
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
