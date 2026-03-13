---
layout: page
title: Projects
subtitle: Selected work in environmental engineering, spatial modeling, and public health
---

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.8rem;
  margin-top: 2rem;
}

.project-card {
  background: #fff;
  border: 1px solid #ddd6c8;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.07);
  display: flex;
  flex-direction: column;
  transition: box-shadow 0.2s ease;
}

.project-card:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.13);
}

.project-card-img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  background: #e8e4dc;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #8a8070;
  font-size: 0.9rem;
  font-style: italic;
}

.project-card-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.project-card-body {
  padding: 1.2rem 1.4rem;
  flex: 1;
  display: flex;
  flex-direction: column;
}

.project-card-title {
  font-size: 1.1rem;
  font-weight: 700;
  color: #3d4f3a;
  margin-bottom: 0.4rem;
}

.project-card-meta {
  font-size: 0.78rem;
  color: #7a7060;
  margin-bottom: 0.75rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
}

.badge {
  background: #eef2ec;
  color: #4a6b3f;
  border-radius: 12px;
  padding: 2px 9px;
  font-size: 0.75rem;
  font-weight: 600;
  white-space: nowrap;
}

.badge-status {
  background: #f5f0e8;
  color: #7a6040;
}

.badge-personal {
  background: #eef0f8;
  color: #4a5080;
}

.project-card-desc {
  font-size: 0.92rem;
  color: #444;
  line-height: 1.55;
  flex: 1;
  margin-bottom: 1rem;
}

.project-card-tools {
  font-size: 0.8rem;
  color: #666;
  margin-bottom: 1rem;
}

.project-card-tools span {
  font-weight: 600;
  color: #3d4f3a;
}

.project-card-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: auto;
}

.project-link-btn {
  font-size: 0.8rem;
  padding: 4px 12px;
  border-radius: 4px;
  border: 1px solid #6b8f5e;
  color: #6b8f5e;
  text-decoration: none;
  background: #fff;
  transition: background 0.15s, color 0.15s;
}

.project-link-btn:hover {
  background: #6b8f5e;
  color: #fff;
  text-decoration: none;
}

.project-link-btn.placeholder {
  border-color: #ccc;
  color: #aaa;
  cursor: default;
  pointer-events: none;
}

.funding-note {
  font-size: 0.78rem;
  color: #888;
  font-style: italic;
  margin-top: 0.5rem;
}

.section-intro {
  font-size: 1.05rem;
  color: #444;
  line-height: 1.65;
  margin-bottom: 0.5rem;
}
</style>

<p class="section-intro">I build data-driven tools that help agencies and public health teams turn complex environmental data into clear, actionable decisions — from prioritizing abandoned mine cleanup across the American Southwest to mapping pathogen hotspots in low-resource settings worldwide. My work sits at the intersection of environmental engineering, spatial modeling, and public health.</p>

---

## Abandoned Mine Lands

<div class="project-grid">

  <div class="project-card">
    <div class="project-card-img">
      <!-- Replace with: <img src="/assets/img/YOUR-IMAGE.png" alt="AML Shiny Tool screenshot"> -->
      Screenshot / figure placeholder
    </div>
    <div class="project-card-body">
      <div class="project-card-title">Abandoned Mine Hazard Prioritization Tool</div>
      <div class="project-card-meta">
        <span class="badge">R Shiny</span>
        <span class="badge">GIS</span>
        <span class="badge">Water Quality</span>
        <span class="badge badge-status">In Progress</span>
      </div>
      <div class="project-card-desc">
        An interactive R Shiny application that integrates water quality data, GIS layers, and user-adjustable vulnerability weights to help agencies identify and rank abandoned mine sites for remediation across Arizona and the Southwest.
      </div>
      <div class="project-card-tools"><span>Tools:</span> R, R Shiny, sf, terra, leaflet, ArcGIS Pro</div>
      <p class="funding-note"><!-- Funding source: e.g., USDA Forest Service · In collaboration with [Partner] --></p>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Shiny App (coming soon)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
        <a href="#" class="project-link-btn placeholder">Paper (in review)</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card-img">
      <!-- Replace with: <img src="/assets/img/YOUR-IMAGE.png" alt="Water quality signatures figure"> -->
      Screenshot / figure placeholder
    </div>
    <div class="project-card-body">
      <div class="project-card-title">Water Quality Signatures for AML Ground-truthing</div>
      <div class="project-card-meta">
        <span class="badge">Spatial Modeling</span>
        <span class="badge">R</span>
        <span class="badge badge-status">In Review</span>
      </div>
      <div class="project-card-desc">
        Developed water quality signatures to distinguish abandoned mine land impacts from background conditions, supporting prioritization of ground-truthing efforts across the Southwestern United States.
      </div>
      <div class="project-card-tools"><span>Tools:</span> R, ArcGIS Pro, statistical modeling</div>
      <p class="funding-note"><!-- Funding source / collaborators placeholder --></p>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Paper (in review)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card-img">
      <!-- Replace with: <img src="/assets/img/YOUR-IMAGE.png" alt="Vulnerability scoring map"> -->
      Screenshot / figure placeholder
    </div>
    <div class="project-card-body">
      <div class="project-card-title">Vulnerability Scoring System for Mine Remediation</div>
      <div class="project-card-meta">
        <span class="badge">GIS</span>
        <span class="badge">Scoring Model</span>
        <span class="badge badge-status">In Preparation</span>
      </div>
      <div class="project-card-desc">
        A vulnerability scoring framework to prioritize and manage land remediation with a focus on abandoned mines in Arizona. Integrates environmental, socioeconomic, and proximity factors into an adjustable scoring model.
      </div>
      <div class="project-card-tools"><span>Tools:</span> R, ArcGIS Pro, ArcGIS Online</div>
      <p class="funding-note"><!-- Funding source / collaborators placeholder --></p>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Paper (in prep)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card-img">
      <!-- Replace with: <img src="/assets/img/YOUR-IMAGE.png" alt="Predictive mining model figure"> -->
      Screenshot / figure placeholder
    </div>
    <div class="project-card-body">
      <div class="project-card-title">Predicting Mining Activity from Water Quality Data</div>
      <div class="project-card-meta">
        <span class="badge">Predictive Modeling</span>
        <span class="badge">Machine Learning</span>
        <span class="badge">R</span>
        <span class="badge badge-status">In Preparation</span>
      </div>
      <div class="project-card-desc">
        Develops predictive models using water quality and environmental data to infer historical and current mining activity in the Southwestern United States — supporting remote identification of unmapped mine sites.
      </div>
      <div class="project-card-tools"><span>Tools:</span> R, machine learning, spatial analysis</div>
      <p class="funding-note"><!-- Funding source / collaborators placeholder --></p>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Paper (in prep)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
      </div>
    </div>
  </div>

</div>

---

## Wastewater-Based Epidemiology & Public Health

<div class="project-grid">

  <div class="project-card">
    <div class="project-card-img">
      <!-- Replace with: <img src="/assets/img/YOUR-IMAGE.png" alt="Decision framework diagram"> -->
      Screenshot / figure placeholder
    </div>
    <div class="project-card-body">
      <div class="project-card-title">Wastewater Surveillance Decision Frameworks</div>
      <div class="project-card-meta">
        <span class="badge">Decision Tools</span>
        <span class="badge">Stakeholder Engagement</span>
        <span class="badge badge-status">In Progress</span>
      </div>
      <div class="project-card-desc">
        Decision algorithms and partner maps for wastewater-based epidemiology programs, helping public health agencies move from raw detection data to coordinated action. Involves stakeholder engagement across Arizona, Kentucky, Alaska, and Uganda.
      </div>
      <div class="project-card-tools"><span>Tools:</span> R, Qualtrics, GIS, decision-tree modeling</div>
      <p class="funding-note">Funded by NSF Pandemic ESCAPE (PIPP Phase II) · Partners: Maricopa County DPH, Arizona DHS<!-- add others --></p>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Project Site (coming soon)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card-img">
      <!-- Replace with: <img src="/assets/img/YOUR-IMAGE.png" alt="Uganda hotspot map"> -->
      Screenshot / figure placeholder
    </div>
    <div class="project-card-body">
      <div class="project-card-title">Pathogen Hotspot Mapping — Uganda</div>
      <div class="project-card-meta">
        <span class="badge">Machine Learning</span>
        <span class="badge">GIS</span>
        <span class="badge">Hydraulic Modeling</span>
        <span class="badge badge-status">In Progress</span>
      </div>
      <div class="project-card-desc">
        GIS and integrated hydraulic/hydrologic modeling to identify priority sampling locations in non-sewered communities in Uganda. Uses XGBoost, Bayesian modeling, and agent-based waste release estimates to distinguish true pathogen hotspots from low-signal sites.
      </div>
      <div class="project-card-tools"><span>Tools:</span> R, XGBoost, Bayesian modeling, ArcGIS Pro, EPANET</div>
      <p class="funding-note">Funded by NSF Pandemic ESCAPE (PIPP Phase II)<!-- add collaborators --></p>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
        <a href="#" class="project-link-btn placeholder">Paper (coming soon)</a>
      </div>
    </div>
  </div>

</div>

---

## Personal Tools & Demos

<p style="color:#555; font-size:0.95rem; margin-bottom:1.5rem;">Independent projects built to explore methods and demonstrate capabilities outside of funded research. More coming soon.</p>

<div class="project-grid">

  <!-- PLACEHOLDER: Interactive data viz / dashboard -->
  <!-- When ready: fill in title, description, tools, and swap placeholder links for real ones -->
  <div class="project-card">
    <div class="project-card-img">
      Coming soon
    </div>
    <div class="project-card-body">
      <div class="project-card-title">Interactive Data Visualization</div>
      <div class="project-card-meta">
        <span class="badge">Interactive Viz</span>
        <span class="badge">Dashboard</span>
        <span class="badge badge-personal">Personal Project</span>
      </div>
      <div class="project-card-desc">
        <!-- Describe what this dashboard shows, what data it uses, and what decision or insight it supports. -->
      </div>
      <div class="project-card-tools"><span>Tools:</span> <!-- e.g., R, ggplot2, plotly, flexdashboard --></div>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Demo (coming soon)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
      </div>
    </div>
  </div>

  <!-- PLACEHOLDER: R Shiny app -->
  <div class="project-card">
    <div class="project-card-img">
      Coming soon
    </div>
    <div class="project-card-body">
      <div class="project-card-title">R Shiny App</div>
      <div class="project-card-meta">
        <span class="badge">R Shiny</span>
        <span class="badge badge-personal">Personal Project</span>
      </div>
      <div class="project-card-desc">
        <!-- Describe the app's purpose, inputs, and outputs. What problem does it solve or illustrate? -->
      </div>
      <div class="project-card-tools"><span>Tools:</span> <!-- e.g., R, Shiny, leaflet, sf --></div>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Shiny App (coming soon)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
      </div>
    </div>
  </div>

  <!-- PLACEHOLDER: GIS / mapping tool -->
  <div class="project-card">
    <div class="project-card-img">
      Coming soon
    </div>
    <div class="project-card-body">
      <div class="project-card-title">GIS / Mapping Tool</div>
      <div class="project-card-meta">
        <span class="badge">GIS</span>
        <span class="badge">Mapping</span>
        <span class="badge badge-personal">Personal Project</span>
      </div>
      <div class="project-card-desc">
        <!-- Describe the spatial question this tool addresses, the data sources, and how outputs are used. -->
      </div>
      <div class="project-card-tools"><span>Tools:</span> <!-- e.g., R, sf, leaflet, ArcGIS Online --></div>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Map (coming soon)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
      </div>
    </div>
  </div>

  <!-- PLACEHOLDER: ML / modeling demo -->
  <div class="project-card">
    <div class="project-card-img">
      Coming soon
    </div>
    <div class="project-card-body">
      <div class="project-card-title">ML / Modeling Demo</div>
      <div class="project-card-meta">
        <span class="badge">Machine Learning</span>
        <span class="badge">Modeling</span>
        <span class="badge badge-personal">Personal Project</span>
      </div>
      <div class="project-card-desc">
        <!-- Describe the modeling approach, dataset, and what the demo illustrates about your ML workflow. -->
      </div>
      <div class="project-card-tools"><span>Tools:</span> <!-- e.g., R, tidymodels, XGBoost, caret --></div>
      <div class="project-card-links">
        <a href="#" class="project-link-btn placeholder">Demo (coming soon)</a>
        <a href="#" class="project-link-btn placeholder">GitHub (coming soon)</a>
      </div>
    </div>
  </div>

</div>
