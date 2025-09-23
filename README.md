<h1 align = "center">MLOps‑Driven Salesforce Lead-Closure Forecast System </h1>

<h3 align='center'>80% reduction in forecast error and delivered 12-months advanced signals as compared to manually entered probabilities by sales representativesfor over 100,000 unique leads over a 3-4 year period</h3><p align="center"> <a href="https://sagar61205.github.io/MLOps-Salesforce-Deal-Closure-Probability-System/">View the Case Study</a> • <a href="https://github.com/sagar61205/MLOps-Salesforce-Deal-Closure-Probability-System">View GitHub</a> </p>

<img width="1200" height="400" alt="Image" src="https://github.com/user-attachments/assets/5eaece22-4092-4ace-8d7d-308ad06b696a" />
<h4>📊 The Business Problem:</h4>

<ul><li>Rep-entered confidence was about 41–44%, while actual closed leads landed around 30–32%, which led to planning gaps and surprise revenue misses across fiscal periods.</li>
<li>Because estimates were manual, pipeline reviews were inconsistent, making quota setting, territory planning, and resource allocation harder quarter to quarter.</li>
<li>The directive was to replace subjective guesses with calibrated, sequence‑aware probabilities that reflect how deals actually move through sales stages.</li>
</ul>

<h4>📊 My role and the solution:</h4>
As the Data Scientist on this project, the mandate was to replace subjective, late-stage rep estimates with an objective, sequence‑aware forecasting system. Built an end‑to‑end ML pipeline that 
analyzes stage progressions and opportunity signals to predict lead closure months earlier, 
giving sales leaders a calibrated, reality‑aligned confidence score for planning and action.
<br>

<h4>Business Impact:</h4>
<ul>
<li>Forecast bias reduction(80%): Reduced absolute forecast error from 10 percentage points (rep 41% vs. actual 31%) to 2 percentage points (model 32% vs. actual 30%) — an 80% error reduction.</li>
<li>Delivered 5 times smaller error than reps (2 pp vs. 10 pp), materially tightening forecast accuracy.</li>
<li>Early signal advantage: 12-months earlier prediction than the typical 1–2 month notice from reps, enabling earlier sales decisions, territory shifts, and resource planning.</li>
<li>Revenue-based decision making using an end-to-end deployed solution on GCP using Vertex AI(Docker and AIrflow DAGs).</li>
</ul>

<h4>Reps vs Model vs actual probabilities:</h4>
<img width="520" height="320" alt="Image" src="https://github.com/user-attachments/assets/d91e25b1-31c0-4dc5-8cac-1b81ad81a680" />

<h4>Forecast Error comparision:</h4>
<img width="520" height="320" alt="Image" src="https://github.com/user-attachments/assets/368fe97b-82f0-43a9-bf8a-541ef2330a4a" />

<h5>Major Challenge: Non-Linear and Variable Sales Cycles:</h5>
<ul>
<li>Sales deals didn't follow a straight line. They often jumped back and forth between stages or moved at wildly different speeds. This messy data made it hard for the model to learn what a typical path to "win" or "loss" looked like.</li>  
</ul>

<h5>Solution: Strategic Data Filtration and a Focused Learning Objective:</h5>
<ul>
<li>Curated Training Data: Instead of training the model on all available opportunities, we filtered the dataset to include only those that demonstrated a clear progression pattern.</li>
<li>Clarified Learning Goal: This filtration allowed the Hidden Markov Model (HMM) to focus on learning the essential transition probabilities between stages that ahighly indicate the final outcome.</li>  
</ul>


<h5>Key Objectives:</h5>
<ul><li>Build an objective lead-closing predictor driven by stage‑sequence behavior rather than rep confidence fields.</li>
<li>Enforce strict sequence filtration (start at 'State 1' or 'State 2'; terminal labels lost/closed) and report results on both strict validation and all leads.</li>
<li>Refactor research code into 5 modules plus main.py, add Dockerfile, and make tasks CLI‑driven for train/evaluate/score for MLOps integration.</li>
<li>Orchestrate training and batch scoring with Airflow (Nitro dx template) using Harbor‑hosted images and GCP storage.</li>
<li>Compare model probabilities vs. rep confidence across fiscal years and ship to production on GCP Vertex AI.</li>
<li>Build an end-to-end MLOps pipeline on GCP (Vertex AI, Docker, Airflow) to operationalize sequence‑aware win‑probability forecasts, replacing subjective estimates with calibrated, reality‑aligned signals.</li>  
</ul>


<h4>🏗️ Technical Architecture:</h4>
<img width="820" height="620" alt="Image" src="https://github.com/user-attachments/assets/1736cd8e-3166-4130-a721-5fb2a4c73d4c" />

<h4>📈 Key Insights Delivered:</h4>
                           
<h5>Validation regimes and Model performance</h5>
<ul>
<li>Strict test/validation (complete sequences): Probability accuracy 86%, Number of unique leads ~6000.</li>   
<li>All opportunities (noisy/late/partial included): Probability accuracy 77%, Number of unique leads ~100,000.</li>
<li>FY23–present: Model ~33% vs. Sales Reps ~41% vs. Actual ~31% Closed leads</li> 
<li>FY24: model ~35% vs. reps ~46% vs. actual ~44% Closed leads.</li>   
<li>FY25: model ~34% vs. reps ~42% vs. actual ~36% Closed leads.</li>   
</ul>


<h4>🛠️ Technical Stack:</h4>

<ul><li>Data Processing & Analysis:Python, Pandas, NumPy</li>
<li>Machine Learning: Hidden Markov Model,hmmlearn</li>
<li>Data Visualization: Matplotlib, Seaborn, Plotly</li>
<li>Deployment: Docker, Cloud-GCP:Vertex AI, Airflow DAGs </li>
<li>Tools: Git, Jupyter Notebook, VS Code</li>
</ul>

<h4>⚠️Disclaimer</h4>

This case study is sanitized for confidentiality; no client identifiers, schemas, or proprietary visuals are disclosed, and metrics are reported at aggregate/cohort levels only.
