<div align="center">

# Nguyễn Thị Triệu Vy

### Data Science Student · Agent AI · Physical AI · Computer Vision · Tabular ML

Sophomore student at University of Information Technology (VNU) · Ho Chi Minh City, Vietnam

[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your-email@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-link)
[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/your-username)

</div>

---

## 👩‍💻 About

I am a Data Science student interested in building intelligent systems that perceive, reason and act. My work sits between **machine learning research** and **real-world deployment**: from tabular modelling and computer vision to embodied and agent-based AI.

I care about honest evaluation, so I try to test every idea under realistic conditions (distribution shift, noisy sensors, cross-session settings) before trusting it.

---

## 🎯 Research Interests

| Area | Focus |
|---|---|
| 🤖 **Agent AI** | LLM-based agents, tool use, decision-making pipelines |
| 🦾 **Physical AI** | Perception for embodied systems, sensor-aware learning |
| 👁️ **Computer Vision** | Pose estimation, face recognition, RGB-D perception |
| 📊 **Tabular ML** | Gradient boosting, ensembling, rigorous cross-validation |

---

## 🚀 Featured Projects

### 🔬 1. Reliability-Aware Fusion of Face and 3D Body Features for RGB-D Person Identification
**Research project** · *In progress*

A research study on whether metric 3D body features from an RGB-D camera (OAK-D-S2) can complement face recognition, and whether fusing the two according to their *reliability* makes identification more stable.

- Builds a **3D skeleton** from 2D pose and depth, then derives metric body descriptors (shoulder width, torso length, limb lengths, height, ratios).
- Proposes a **measurement-level reliability** score that combines pose confidence with a **stereo depth-error model** (depth error grows roughly with Z²), to suppress unreliable joints at long range and "flat-wall" depth artifacts.
- Compares **10 configurations**: Face Only, 2D/3D Body, Face + 2D/3D Body, GMU, Bayesian fusion, rule-based reliability-aware fusion, and a proposed **Learned Adaptive Meta-Fusion** (a tiny MLP gate with about 60 parameters, suitable for edge devices).
- Evaluation plan: **30 participants × 2 sessions**, varying distance (1.5 / 2.5 / 3.5 m), viewpoint (0° / 30° / 60°), illumination, face occlusion and cross-session, plus cross-dataset validation on **BIWI RGB-D-ID** and Edge-AI efficiency measurements (FPS, latency, VPU/RAM).

**Tech:** `Python` · `OAK-D-S2 / DepthAI` · `Pose Estimation` · `Face Embeddings` · `PyTorch`

---

### 🏆 2. AISC 2026: [Project Name]
**Team project** · *Finalist, finals in December 2026*

[One or two sentences: what problem your team solves, who it is for, and the main idea of the solution.]

- **My role:** [e.g. data pipeline, modelling, evaluation, front-end, presentation]
- **Approach:** [key methods or models you used]
- **Outcome:** [concrete result, e.g. advanced to the finals among N teams]

**Tech:** `[tech 1]` · `[tech 2]` · `[tech 3]`

[Repository](https://github.com/your-username/repo) · [Demo](https://link-demo)

---

### ✈️ 3. Airline Passenger Satisfaction: Kaggle Playground Series
**Kaggle competition** · *Tabular binary classification, metric: ROC AUC*

Predicting passenger satisfaction from flight and service features in a Kaggle Playground competition.

- **Result:** Rank **#[your rank]** on the [Public / Private] leaderboard
- Feature engineering, gradient boosting models and ensembling, validated with cross-validation
- Focus on avoiding leakage and trusting local CV over leaderboard noise

**Tech:** `Python` · `pandas` · `scikit-learn` · `XGBoost` · `LightGBM` · `CatBoost`

[Notebook / Repository](https://github.com/your-username/repo) · [Kaggle](https://www.kaggle.com/your-username)

---

### 🌐 4. Multione.vn: Corporate Website for a Media & Communications Company
**Client project** · *Web development*

Contributed to the website of **Multione**, a Vietnamese media and communications company, presenting its services and brand to prospective clients.

- **My role:** [e.g. front-end, back-end, UI, content structure, deployment]
- **Highlights:** [e.g. responsive layout, service pages, contact forms, performance or SEO work]

**Tech:** `[e.g. React]` · `[e.g. Node.js]` · `[e.g. MongoDB]`

🔗 [multione.vn](https://multione.vn)

---

## 🛠️ Tech Stack

**Machine Learning & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)

**Computer Vision & Edge**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![DepthAI](https://img.shields.io/badge/OAK--D%20%2F%20DepthAI-00A3E0?style=flat-square)

**Web**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)

---

## 📫 Contact

- 📧 Email: your-email@example.com
- 💼 LinkedIn: [your-link](https://linkedin.com/in/your-link)
- 📊 Kaggle: [your-username](https://www.kaggle.com/your-username)

<div align="center">

*Open to research collaboration and internships in AI, Computer Vision and Data Science.*

</div>
