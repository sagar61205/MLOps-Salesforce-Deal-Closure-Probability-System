<h1 align = "center">MLOps‑Driven Salesforce Lead-Closure Forecast System </h1>

<h3 align='center'>80% reduction in forecast error and delivered 10-months advanced signals as compared to manual sales rep-entered lead-closing probabilities</h3><p align="center"> <a href="https://sagar61205.github.io/Thyroid-detection/">View the Case Study</a> • <a href="https://github.com/sagar61205/Thyroid-detection">View the Code</a> </p>

<img width="800" height="600" alt="Image" src="https://github.com/user-attachments/assets/5eaece22-4092-4ace-8d7d-308ad06b696a" />
<h4>📊 The Business Problem:</h4>

<ul><li>Rep-entered confidence was about 41–44%, while actual closied leads landed around 30–32%, which led to planning gaps and surprise revenue misses across fiscal periods.</li>
<li>Because estimates were manual, pipeline reviews were inconsistent, making quota setting, territory planning, and resource allocation harder quarter to quarter.</li>
<li>The directive was to replace subjective guesses with calibrated, sequence‑aware probabilities that reflect how deals actually move through sales stages.</li>
<li>Reduced forecast error by 80% and delivered 12 months advanced signals: model 32% prediction for closed deals and the actual closing was between 30-32%</li>  
</ul>

<h4>📊 My role and the solution:</h4>
As the Data Scientist on this project, the mandate was to replace subjective, late-stage rep estimates with an objective, sequence‑aware forecasting system. Built an end‑to‑end ML pipeline that 
analyzes stage progressions and opportunity signals to predict lead closure months earlier, 
giving sales leaders a calibrated, reality‑aligned confidence score for planning and action.
<br>

<h4>Business Impact:</h4>
<ul>
<li>Forecast bias reduction(80%): Reduced absolute forecast error from 10 percentage points (rep 40% vs. actual 30%) to 2 percentage points (model 32% vs. actual 30%) — an 80% error reduction.</li>
<li>Delivered 5 times smaller error than reps (2 pp vs. 10 pp), materially tightening forecast accuracy.</li>
<li>Early signal advantage: 10-months earlier prediction than the typical 1–2 month notice from reps, enabling earlier sales decisions, territory shifts, and resource planning.</li>
<li>Revenue-based decision making using an end-to-end deployed solution on GCP using Vertex AI(Docker,Harbor,Nitrodx pipeline and AIrflow DAGs).</li>
</ul>

<h5>Forecast Error comparision</h5>
<img width="620" height="420" alt="Image" src="https://github.com/user-attachments/assets/368fe97b-82f0-43a9-bf8a-541ef2330a4a" />


<h5>Key Objectives:</h5>
<ul><li>Build an objective lead-closing predictor driven by stage‑sequence behavior rather than rep confidence fields.</li>
<li>Enforce strict sequence filtration (start at 'State 1' or 'State 2'; terminal labels lost/closed) and report results on both strict validation and all leads.</li>
<li>Refactor research code into 5 modules plus main.py, add Dockerfile, and make tasks CLI‑driven for train/evaluate/score for MLOps integration.</li>
<li>Orchestrate training and batch scoring with Airflow (Nitro dx template) using Harbor‑hosted images and GCP storage.</li>
<li>Compare model probabilities vs. rep confidence across fiscal years and ship to production on GCP Vertex AI.</li>
<li>Build an end-to-end MLOps pipeline on GCP (Vertex AI, Docker, Airflow) to operationalize sequence‑aware win‑probability forecasts, replacing subjective estimates with calibrated, reality‑aligned signals.</li>  
</ul>


<h4>🏗️ Technical Architecture:</h4>
<img width="400" height="600" alt="Image" src="https://github.com/user-attachments/assets/ffe27bfc-7283-4a33-aff4-8ab6e03fef98" />

<h4>📈 Key Insights Delivered:</h4>
                           
<h5>Feature Importance:</h5>
<ul>
<li>Identified the most critical clinical markers for accurate thyroid disorder classification.</li>   
<li>Discovered non-linear relationships between biomarkers that human analysis might overlook.</li>
</ul>

<h5>Model Performance:</h5>
<ul>
<li>Achieved 90% accuracy alongwith ROC_AUC score of 0.9 using Random Forest, KNN and XGBoost with selected features.</li><br>
<li>Maintained robust performance across different patient demographics and subtypes.</li><br>
</ul>

<h4>🛠️ Technical Stack:</h4>

<ul><li>Data Processing & Analysis:Python, Pandas, NumPy, Scikit-learn, Statsmodels</li>
<li>Machine Learning: Hidden Markov Model</li>
<li>Data Visualization: Matplotlib, Seaborn, Plotly</li>
<li>Deployment: Docker, Cloud-GCP:Vertex AI, Airflow DAGs </li>
<li>Tools: Git, Jupyter Notebook, VS Code</li>
</ul>

<h5>Prediction app(Screenshot):</h5>
<img width="620" height="220" alt="Image" src="https://github.com/user-attachments/assets/c6e68e13-46c8-4dad-b08d-74b5af86326d" />

<h5>Prediction output:</h5>
<img width="306" height="189" alt="Image" src="https://github.com/user-attachments/assets/152d7b1b-9107-40a0-9c37-261b249f0191" />

<h4>⚠️Disclaimer</h4>

This project serves as a Proof of Concept (POC). This project demonstrates how machine learning classification is applied in medical practice and the potential impact it can generate.
