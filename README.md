<div align="center">

<img src="assets/banner.svg" width="100%" alt="Tharun Subramanya. Machine Learning for Industrial and Automotive Systems. Automotive diagnostics today, industrial robotics and IIoT next."/>

<br><br>

<img src="assets/avatar.png" width="132" height="132" alt="Portrait of Tharun Subramanya"/>

</div>

<br>

## 🧭 The Journey

I didn't start in AI. I started in **Industrial & Production Engineering** thinking in tolerances and failure modes, long before I wrote a line of Python. An edge computing course during my Master's changed the trajectory: it introduced me to real-world deployment constraints like latency budgets, sensor noise, compute-at-the-edge trade-offs and I realized that was the actual problem I wanted to work on.

That's the thread connecting everything below: an IoT temperature pipeline on a Raspberry Pi, a serverless digital twin on AWS, and now a full research push into **vehicle diagnostics and predictive maintenance**: brakes, bearings, buzz/squeak/rattle detection. Same question every time: *how do you get a model to tell the truth about a physical system before it fails?*

<br>

## 🔧 What I'm Building Right Now

<table>
<tr>
<td width="50%" valign="top">

### Smart Brake & Wheel-End Condition Monitor

A physics-first brake diagnostic system, built with a collaborator. My half: a lumped-capacitance rotor thermal simulator (speed-dependent convection/radiation), residual caliper drag-torque injection across four severity levels, dual-wheel FL/FR simulation, and a Newtonian cooling-curve feature extractor that inverts torque from the cooling asymptote. Currently landing within **~5% of ground truth** on severe-drag cases. 18-test suite, CI-gated with `ruff` + `pytest` + coverage.

</td>
<td width="50%" valign="top">

### DARE-PM

*Drift-Aware, Event-Triggered Edge Predictive Maintenance*

Reframed with faculty mentorship as a vehicle BSR (buzz/squeak/rattle) detection system. Core idea: ADWIN drift detection *alone* can't tell you whether a signal shift is a real fault or just a benign environmental change, so I'm building a multi-signal layer (per-feature ADWIN + rolling confidence + cross-sensor majority voting) that resolves that ambiguity before it reaches the controller.

</td>
</tr>
</table>

<br>

## ⚙️ How I Actually Work

> I default to the next concrete step, not open-ended reflection.
>
> I run multiple learning tracks in parallel: DSA, ML theory, systems design, domain knowledge, rather than sequencing them.
>
> I build domain fluency *alongside* implementation. You can't model brake drag torque well if you don't understand what a caliper is actually doing.

<br>

## 🧰 Tech I Reach For

**Languages & Data**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Machine Learning & AI**
<br>
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0B6E4F?style=for-the-badge&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-3776AB?style=for-the-badge&logoColor=white)

**AI / LLM Tooling**
<br>
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=for-the-badge&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-2F2F2F?style=for-the-badge&logoColor=white)

**Data Engineering**
<br>
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)

**Cloud & Databases**
<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white)

**Hardware / IoT**
<br>
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi%205-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)

**Visualization & DevOps**
<br>
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

<br>

## 🚀 Projects Worth a Look

<table>
<tr><th align="left">Project</th><th align="left">What it does</th></tr>
<tr><td><b>Smart Brake &amp; Wheel-End Condition Monitor</b></td><td>Physics-based brake diagnostic system: thermal simulation, drag-torque injection, cooling-curve torque inversion</td></tr>
<tr><td><b>DARE-PM</b></td><td>Drift-aware edge predictive maintenance for vehicle BSR detection: ADWIN with cross-sensor voting</td></tr>
<tr><td><b>IoT Sensing Pipeline</b></td><td>Raspberry Pi + DHT sensors + MQTT (Mosquitto) → Python subscriber → CSV storage → matplotlib visualization</td></tr>
<tr><td><b>Digital Twin + Serverless Alerting</b></td><td>AWS IoT Core + Lambda + SES temperature alert system running on physical Raspberry Pi hardware</td></tr>
</table>

<br>

## 📍 Right Now, I'm

🔨 Building the Random Forest classifier + diagnostic evidence card for the Smart Brake project

📖 Grinding NeetCode 150, 3Blue1Brown linear algebra, and a self-directed GenAI/LLM track (Hugging Face, LangChain, RAG)

🎯 Filling a flagged SQL gap and pushing further into ETL/Spark

🚗 Learning the language of OEM vehicle diagnostics, one dataset at a time

<br>

## 💡 Most Importantly

Debugging, implementation, documentation, and editing. That's the job, most days. Not the demo, the ten hours before it.

<br>

<div align="center">

## 📫 Let's Connect

Talk AI, edge computing, or anything with wheels and sensors on it.

[![Gmail](https://img.shields.io/badge/tharunmysuru%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tharunmysuru@gmail.com)
[![LinkedIn](https://img.shields.io/badge/tharun--subramanya--p-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tharun-subramanya-p)

<br>

<img src="assets/rule.svg" width="100%" alt=""/>

</div>
