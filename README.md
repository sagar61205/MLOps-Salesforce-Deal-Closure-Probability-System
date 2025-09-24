<h1 align="center">MLOps‑Driven Salesforce Lead-Closure Forecast System</h1>

<h3 align="center">80% reduction in forecast error with 12-month advanced signals for 100,000+ leads</h3>

<p align="center">
  <a href="https://sagar61205.github.io/MLOps-Salesforce-Deal-Closure-Probability-System/">View Case Study</a> • 
  <a href="https://github.com/sagar61205/MLOps-Salesforce-Deal-Closure-Probability-System">View GitHub</a>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/5eaece22-4092-4ace-8d7d-308ad06b696a" 
       alt="Sales Forecast System Overview" 
       style="max-width: 100%; height: auto; border: 1px solid #e1e4e8; border-radius: 8px; padding: 10px; background: white;"/>
</div>

## 📊 The Business Problem

<ul>
  <li><strong>Forecast Gap:</strong> Sales confidence (41-44%) vs. actual performance (30-32%) created unreliable forecasts</li>
  <li><strong>Manual Inconsistency:</strong> Pipeline reviews were inconsistent, hurting quota setting and resource allocation</li>
  <li><strong>Solution Goal:</strong> Replace subjective guesses with calibrated, sequence-aware probabilities</li>
</ul>

## 🎯 My Role & Solution

<ul>
  <li><strong>Lead Data Scientist:</strong> Replaced subjective estimates with objective forecasting system</li>
  <li><strong>End-to-End Pipeline:</strong> Built ML system analyzing stage progressions for early closure predictions</li>
  <li><strong>Production Deployment:</strong> GCP Vertex AI with Docker and Airflow DAGs</li>
</ul>

## 💰 Business Impact

<ul>
  <li><strong>80% Forecast Error Reduction:</strong> 10pp → 2pp error (rep 41% vs. actual 31% → model 32% vs. actual 30%)</li>
  <li><strong>5x Smaller Error:</strong> 2pp vs. 10pp compared to sales reps</li>
  <li><strong>12-Month Early Signals:</strong> Enabled earlier sales decisions and resource planning</li>
  <li><strong>Production System:</strong> End-to-end deployment on GCP Vertex AI</li>
</ul>

## 📊 Performance Comparison

<div align="center">
  <img src="https://github.com/user-attachments/assets/d91e25b1-31c0-4dc5-8cac-1b81ad81a680" 
       alt="Reps vs Model vs Actual Probabilities" 
       style="max-width: 100%; height: auto; border: 1px solid #e1e4e8; border-radius: 8px; padding: 10px; background: white;"/>
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/368fe97b-82f0-43a9-bf8a-541ef2330a4a" 
       alt="Forecast Error Comparison" 
       style="max-width: 100%; height: auto; border: 1px solid #e1e4e8; border-radius: 8px; padding: 10px; background: white;"/>
</div>

## 🚩 Major Challenge: Non-Linear Sales Cycles

<ul>
  <li><strong>Erratic Progression:</strong> Deals jumped back/forth between stages unpredictably</li>
  <li><strong>Variable Velocity:</strong> Wildly different speeds between opportunities</li>
  <li><strong>Data Quality:</strong> Messy sequences made pattern recognition difficult</li>
</ul>

## 💡 Solution: Strategic Data Approach

<ul>
  <li><strong>Curated Training Data:</strong> Filtered for clear progression patterns only</li>
  <li><strong>Focused Learning:</strong> HMM trained on essential stage transition probabilities</li>
  <li><strong>Validation Rigor:</strong> Separate testing on clean vs. noisy data</li>
</ul>

## 🎯 Key Objectives Achieved

<ul>
  <li>✅ Objective lead-closing predictor using stage-sequence behavior</li>
  <li>✅ Strict sequence filtration with dual validation regimes</li>
  <li>✅ Modular codebase with CLI-driven train/evaluate/score</li>
  <li>✅ Airflow orchestration with Docker on GCP</li>
  <li>✅ Production deployment on Vertex AI</li>
  <li>✅ End-to-end MLOps pipeline operationalization</li>
</ul>

## 🏗️ Technical Architecture

<div align="center">
  <img src="https://github.com/user-attachments/assets/0f732616-f5c7-416b-972c-83cbff815eca" 
       alt="Technical Architecture Diagram" 
       style="max-width: 100%; height: auto; border: 1px solid #e1e4e8; border-radius: 8px; padding: 10px; background: white;"/>
</div>

## 📈 Model Performance Results

### Validation Metrics
<ul>
  <li><strong>Strict Validation (6,000 leads):</strong> 86% probability accuracy</li>
  <li><strong>All Opportunities (100,000 leads):</strong> 77% probability accuracy</li>
</ul>

### Fiscal Year Performance
<ul>
  <li><strong>FY23-Present:</strong> Model 33% vs. Reps 41% vs. Actual 31%</li>
  <li><strong>FY24:</strong> Model 35% vs. Reps 46% vs. Actual 44%</li>
  <li><strong>FY25:</strong> Model 34% vs. Reps 42% vs. Actual 36%</li>
</ul>

## 🛠️ Technical Stack

<ul>
  <li><strong>Data Processing:</strong> Python, Pandas, NumPy</li>
  <li><strong>Machine Learning:</strong> Hidden Markov Model (hmmlearn)</li>
  <li><strong>Visualization:</strong> Matplotlib, Seaborn, Plotly</li>
  <li><strong>Deployment:</strong> Docker, GCP Vertex AI, Airflow DAGs</li>
  <li><strong>Tools:</strong> Git, Jupyter Notebook, VS Code</li>
</ul>

## ⚠️ Disclaimer

This case study is sanitized for confidentiality; no client identifiers, schemas, or proprietary visuals are disclosed. Metrics are reported at aggregate levels only.

---

<div align="center">
  <strong>Open to discussing how this approach can drive forecasting accuracy in your organization</strong>
</div>
