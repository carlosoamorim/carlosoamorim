<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&lines=Hi+there%2C+I'm+Carlos+Amorim;MSc+Data+Science+%40+Nova+IMS;ML+%7C+Deep+Learning+%7C+Energy+Systems;Building+the+Iberian+grid+of+the+future." alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/carlosortaamorim)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:clnoamorim@gmail.com)
[![Nova IMS](https://img.shields.io/badge/Nova%20IMS-003087?style=for-the-badge&logo=academia&logoColor=white)](https://www.novaims.unl.pt/en/)

</div>

---

## About Me

I'm a Data Scientist and MSc student at **NOVA IMS** (ranked #1 in Data Analytics in Western Europe) building at the intersection of **machine learning and energy systems**.

My thesis is focused on the **Iberian power grid**, on probabilistic forecasting of grid frequency deviations and reinforcement learning for battery dispatch under MIBEL price signals. The April 2025 Iberian blackout made this work feel a lot less academic.

Before the master's, I worked at **Oney Bank** doing financial analytics — clustering, propensity modelling, Power BI dashboards — which is where I first realised that the gap between a model and a decision is mostly a data quality problem.

```python
carlos = {
    "currently"  : "MSc Data Science & Advanced Analytics @ Nova IMS (2027)",
    "thesis"     : "Probabilistic forecasting + RL dispatch · Iberian energy grid",
    "background" : "Financial analytics · Oney Bank",
    "location"   : "Lisbon, Portugal",
    "languages"  : ["Portuguese", "English C2", "Spanish B2", "German A2"],
}
```

---

## Tech Stack

<div align="center">

**Languages & Data**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)](https://r-project.org)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)](https://postgresql.org)

**ML & Deep Learning**

[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)](https://keras.io)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)

**Data Engineering & Cloud**

[![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)](https://spark.apache.org)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://docker.com)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://mongodb.com)

**BI & Visualisation**

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)

</div>

---

## Featured Projects

### [WikiArt Painter Classification](https://github.com/carlosoamorim/wikiart-painter-classification)
> Artist attribution from pixels alone — a genuinely hard vision problem.

Classified paintings across **23 artists** on a 13,172-image subset of WikiArt using a progressive fine-tuning pipeline and softmax ensemble.

| Model | Val F1 | Test F1 |
|---|---|---|
| CNN from Scratch | 0.633 | — |
| EfficientNetV2S (3-phase) | 0.851 | — |
| MobileNetV3Large | 0.803 | — |
| **Ensemble (50/50)** | **0.862** | **F1: 0.860 · AUC: 0.991** |

Key finding: standard augmentation pipelines built for natural images actively hurt performance on paintings — geometric transforms destroy compositional cues that are genuine style signals.

`TensorFlow` `Keras` `EfficientNetV2S` `MobileNetV3Large` `Kaggle P100`

---

### [Used Car Price Prediction](https://github.com/rmmandrade/ml2526)
> End-to-end regression pipeline for a UK used car resale company.

The core challenge was data quality: seller-provided brand and model fields contained hundreds of misspellings. Built a **hybrid fuzzy string matcher** (Levenshtein + token sort ratio) to standardise inputs before modelling.

| Model | Kaggle MAE |
|---|---|
| Ridge | £2,507 |
| Histogram Gradient Boosting | £1,308 |
| Extra Trees | £1,293 |
| **Ensemble (ET + RF + HGB)** | **£1,263** |

Placed in the **upper quartile** of the course Kaggle leaderboard. Includes a Gradio inference dashboard with live predictions from all 5 models + disagreement metric.

`scikit-learn` `rapidfuzz` `Gradio` `Plotly`

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=carlosoamorim&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=carlosoamorim&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=carlosoamorim&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## What I'm Working On

- **Thesis** — Probabilistic frequency deviation forecasting for the Iberian grid post-April 2025 blackout
- **RL dispatch** — Battery storage optimisation under MIBEL day-ahead price signals
- **Automatic Statistician** — Modular CRISP-DM pipeline for automated data analysis (coming soon)

---

<div align="center">

*"The goal is not to predict the future — it's to make better decisions under uncertainty."*

![Visitor Count](https://komarev.com/ghpvc/?username=carlosoamorim&color=00d9ff&style=flat-square&label=profile+views)

</div>
