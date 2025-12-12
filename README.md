# 🌿 AURALIS: The Future of Urban Air Quality Management

<div align="center">

<img src="assets/logo.jpg" alt="Team Auralis Logo" width="250" />

<h3>🏆 Winner - Smart India Hackathon 2025 (SIH25216) 🏆</h3>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=22c55e&center=true&vCenter=true&width=435&lines=Physics-Aware+Air+Quality+Forecasting;Satellite-Based+Pollution+Source+Tracking;Health-Centric+Navigation;AI-Driven+Policy+Analysis;Winner+SIH+2025" alt="Typing SVG" /></a>

<br>

[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge&logo=open-source-initiative)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge&logo=activity)](https://github.com/antonyjoseph2111/auralis)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=for-the-badge&logo=git)](http://makeapullrequest.com)

<p>
  <b>Auralis</b> is an integrated multi-modal system designed to combat the air pollution crisis in Delhi-NCR. <br>
  We leverage <b>Physics-Aware Deep Learning</b>, <b>Satellite Intelligence (Sentinel-5P)</b>, and <b>Graph Algorithms</b> to monitor, predict, and mitigate pollution.
</p>

<a href="#">Explore Docs</a> • <a href="#">View Demo</a> • <a href="#">Report Bug</a>

</div>

---

## 🛠️ Tech Stack & Tools

<div align="center">

| **Core AI & Data** | **Frontend & Maps** | **Backend & Cloud** | **Tools & DevOps** |
| :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) | ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) | ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) |
| ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) | ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) | ![Firebase](https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black) | ![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) | ![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white) | ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) | ![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white) |
| ![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white) | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) | ![Sentinel-5P](https://img.shields.io/badge/ESA-Sentinel--5P-003366?style=for-the-badge) | ![Mermaid](https://img.shields.io/badge/Mermaid-CA9CE1?style=for-the-badge) |

</div>

---

## 💎 The ClearSight Ecosystem

This repository consolidates the entire **Auralis** ecosystem into a single unified monorepo.

### 🌟 Key Modules

| Module | Description | Key Tech |
| :--- | :--- | :--- |
| **🔮 AQI Forecasting** | **72-Hour Predictions** using Hybrid Physics-Aware BiLSTM Models. Constrained by meteorological laws to prevent hallucinations. | `BiLSTM` `TensorFlow` |
| **🗺️ Pollution Routing** | **Pollution-Free Navigation** using A* Search algorithms to weigh path distance against exposure. | `Graph Theory` `Leaflet` |
| **🏭 Source ID** | **Plume Tracking** via Sentinel-5P satellite imagery to detect NO2 and aerosol plumes from space. | `Sentinel-5P` `CV` |
| **🏥 Health Advisory** | **Personalized Risk Assessment** using Gemini AI to generate custom health reports based on user profiles. | `Gemini API` `GenAI` |
| **📜 Policy Analysis** | **Counterfactual Modeling** to simulate the impact of policy interventions like Odd-Even rules. | `Data Analytics` |

---

## 🏗️ Technical Architecture

```mermaid
graph TD
  subgraph Data Ingestion
    A["Real-Time Sensors (CPCB)"] -->|JSON| B("Unified Data Layer")
    S["Sentinel-5P Satellites"] -->|Tiff| B
    W["Weather APIs"] -->|REST| B
  end
  
  subgraph AI Engine
    B --> C{"Hybrid Physics-Aware Model"}
    C -->|BiLSTM Sequence| D["Forecasting Module"]
    C -->|Computer Vision| E["Source Detection"]
    C -->|A* Algorithm| F["Routing Engine"]
    C -->|LLM RAG| G["Health Advisory"]
  end
  
  subgraph User Interface
    D --> H["Web Dashboard"]
    E --> H
    F --> H
    G --> H
  end
  
  style C fill:#22c55e,stroke:#fff,stroke-width:4px,color:#fff
```

---

## 🏆 Team Auralis

We are the proud **Winners of Smart India Hackathon 2025 (SIH25216)**.

<div align="center">
    <img src="assets/winning_team.jpg" alt="Team Auralis Winning Moment" width="600" style="border-radius: 10px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);" />
</div>
<br>

| **Antony Joseph** | **Nate Kurian** | **Aparna Anil Nair** |
| :---: | :---: | :---: |
| 🧑‍💻 Team Leader | 🚀 Member | 🎨 Member |

| **George Tomson** | **Athul Lal SP** | **Divya Tresa Thomas** |
| :---: | :---: | :---: |
| 🔧 Member | 📊 Member | 💡 Member |

---

## 🛠️ Installation & Setup

This is a monorepo. You can run individual modules by navigating to their directories.

```bash
# Clone the master repo
git clone https://github.com/antonyjoseph2111/auralis.git
cd auralis

# Example: Run Forecasting Module
cd clearsight-aqi-forecasting
pip install -r requirements.txt
python run_pipeline.py
```

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

---

<div align="center">
    <b>Star this repo 🌟 if you found it useful!</b>
    <br>
    Made with ❤️ by Team Auralis
</div>

<div align="center">

![SIH2025](https://img.shields.io/badge/Competition-SIH_2025-gold?style=for-the-badge)
![Winner](https://img.shields.io/badge/Status-Winner-success?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Smart_Automation-blue?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Air_Quality-green?style=for-the-badge)

</div>
