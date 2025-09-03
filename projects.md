---
title: Projects
layout: page
permalink: /projects/
---
<link rel="stylesheet" href="{{ '/public/css/poole.css' | relative_url }}">
<link rel="stylesheet" href="{{ '/public/css/hyde.css'  | relative_url }}">
<link rel="stylesheet" href="{{ '/public/css/syntax.css' | relative_url }}">
<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">




Below are representative projects. Each includes the **goal**, **approach**, and **impact**.

<div class="projects">
  <div class="card">
    <h3>Booking Cancellations — Model</h3>
    <p><strong>Goal:</strong> Predict cancels to reduce churn/overbooking.<br>
    <strong>Approach:</strong> Feature engineering, stratified CV, calibration; cost-sensitive threshold.<br>
    <strong>Impact:</strong> Prioritized follow-ups; improved precision@k.</p>
    <p><em>Stack:</em> Python (pandas, scikit-learn)</p>
  </div>

  <div class="card">
    <h3>Launch Opt-ins → Membership</h3>
    <p><strong>Goal:</strong> Measure opt-ins before membership across distinct launches.<br>
    <strong>Approach:</strong> Person-level timelines, windowed joins, cohort tables.<br>
    <strong>Impact:</strong> Better follow-up window & cadence.</p>
    <p><em>Stack:</em> SQL, Python, Power BI</p>
  </div>

  <div class="card">
    <h3>Ad Spend ETL → Excel</h3>
    <p><strong>Goal:</strong> Automate weekly rollups from CSV to a living Excel model.<br>
    <strong>Approach:</strong> Python script to update/append rows by campaign/date keys.<br>
    <strong>Impact:</strong> Minutes instead of manual copy/paste.</p>
    <p><em>Stack:</em> Python (pandas, openpyxl)</p>
  </div>
</div>
