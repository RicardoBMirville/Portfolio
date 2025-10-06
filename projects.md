---
title: Projects
layout: default
permalink: /projects/
---

<link rel="stylesheet" href="{{ '/public/css/poole.css' | relative_url }}">
<link rel="stylesheet" href="{{ '/public/css/hyde.css'  | relative_url }}">
<link rel="stylesheet" href="{{ '/public/css/syntax.css' | relative_url }}">
<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

Below are representative projects. Each includes the **goal**, **approach**, and **impact**.

<h2> Python Machine Learning Projects </h2> 

<div class="projects">

  <!-- Project 1 -->
  <div class="card">
    <h3>Loan Default Prediction</h3>
    <p><strong>Problem:</strong> Banks and lenders need to assess the risk of loan defaults to minimize financial losses and make data-driven lending decisions.</p>
    <p><strong>Approach:</strong> Explored and preprocessed a loan dataset with Python. Engineered financial and customer-related features (e.g., credit score, debt-to-income ratio, employment history). Trained multiple classification models (Logistic Regression, Random Forest, Gradient Boosting) and performed hyperparameter tuning with cross-validation. Evaluated models using AUC, precision, recall, and confusion matrices.</p>
    <p><strong>Outcome:</strong> Built a predictive pipeline that achieved strong accuracy and recall for defaulted loans, showing that machine learning can flag high-risk borrowers early. This provides a foundation for lenders to incorporate ML into risk assessment and loan approval workflows.</p>
    <p class="links">
      🔗 <a href="https://ricardobmirville.github.io/Portfolio/assets/notebooks/loan_default_prediction.html" target="_blank">View Report (HTML)</a>
      &nbsp;|&nbsp;
      🔗 <a href="https://github.com/RicardoBMirville/Portfolio/blob/main/assets/notebooks/loan_default_prediction.ipynb" target="_blank">Notebook on GitHub</a>
      &nbsp;|&nbsp;
    </p>
  </div>

  <!-- Project 2 -->
  <div class="card">
    <h3>Extraa Learn: Predicting Lead Generation</h3>
    <p><strong>Problem:</strong> Extraa Learn is a start up company designed to offer programs to assist with learning and development. With a large number of leads being generated on a regular basis, one of the issues faced by ExtraaLearn is to identify which of the leads are more likely to convert so that they can allocate resources accordingly.</p>
    <p><strong>Approach:</strong> Explored and preprocessed a Extraa Learn's dataset with Python. Engineered financial and customer-related features (e.g., credit score, debt-to-income ratio, employment history). Trained multiple models including Decision Tree models and Random Forest Models and performed hyperparameter tuning with cross-validation. Evaluated models using AUC, precision, recall, and confusion matrices.</p>
    <p><strong>Outcome:</strong> Segment users based on important features and characteristics that influence conversion. Users who are professionals, spend significant time on the website, and have a high profile completion rate will receive targeted promotional content to encourage sign-ups.</p>
    <p class="links">
      🔗 <a href="https://ricardobmirville.github.io/Portfolio/assets/notebooks/potential_customers_prediction.html" target="_blank">View Report (HTML)</a>
      &nbsp;|&nbsp;
      🔗 <a href="https://github.com/RicardoBMirville/Portfolio/blob/main/assets/notebooks/potential_customers_prediction.ipynb" target="_blank">Notebook on GitHub</a>
      &nbsp;|&nbsp;
    </p>
  </div>

</div>


<h2> SQL / Power BI Projects </h2>


  <div class="card">
    <h3>Supermarket Analytics — ChatGPT as the Stakeholder Part 1 </h3>
    <p><strong>Problem:</strong> Evaluate performance across three supermarket branches using a real-world retail dataset, answering stakeholder questions about revenue, product lines, customer mix, and payment preferences.</p>
    <p><strong>Approach:</strong> Loaded and prepared the Kaggle “Supermarket” dataset in PostgreSQL/pgAdmin (deduping, null checks, typed columns, and a cleaned view). Answered stakeholder questions with SQL (CTEs for month-by-month revenue, aggregations for product-line gross income, customer type splits, and payment method distributions). Built a lightweight, filterable dashboard to explore results.</p>
    <p><strong>Outcome:</strong> Clear branch-level revenue comparisons, top-earning product lines, and customer patterns (e.g., e-wallet and cash as most popular payments), giving decision-makers a fast path to branch and category prioritization.</p>
    <p class="links">
      🔗 <a href="https://medium.com/@rmirville/analyzing-supermarket-data-with-chatgpt-as-my-stakeholder-573a07ed8ad5" target="_blank">Read the write-up on Medium</a>
    </p>
  </div>
  
</h2>


