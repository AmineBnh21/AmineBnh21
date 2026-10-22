<h1 align="center">Bonjour, je suis Mohamed Amine BENHAMAID 👋</h1>

<p align="center">
  <b>Étudiant en Master 2 Intelligence Artificielle — Université Claude Bernard Lyon 1</b><br>
  Je recherche un <b>stage Data Science / IA de 6 mois à partir de février 2027</b> (Lyon ou remote)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohamed-amine-benhamaid"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:benhamaidmohamedamine@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Lyon-France-002654?style=for-the-badge" alt="Lyon, France">
</p>

---

## 🧠 À propos

- 🎓 M2 Intelligence Artificielle à Lyon 1, après un M1 Informatique et une Licence Informatique (Skikda, Algérie)
- 🔬 Expérience du cycle complet d'un projet de données : préparation, modélisation ML/DL, **évaluation rigoureuse**
- 🕸️ Centres d'intérêt : **Graph Neural Networks**, **IA générative / RAG**, sécurité des LLM, systèmes multi-agents
- 🗣️ Français courant · Anglais B2 (technique)

---

## 🚀 Projets phares

### 📜 [Assistant de conformité à l'AI Act européen (RAG)](https://github.com/AmineBnh21/RAG-AI-Act)
`Python` `LLM` `ChromaDB` `bge-m3` `Ministral 8B` `Pydantic`

À partir de la description d'un système d'IA, l'assistant détermine son **niveau de risque**, le **rôle de l'opérateur** et ses **obligations datées**, en citant les articles exacts du règlement.
- Pipeline RAG écrit **sans framework**, couvert par **121 tests**, déployé en démo en ligne
- Recherche augmentée garantissant un candidat par niveau de risque : exactitude **64 % → 92 %** sur 25 cas annotés (recall des extraits 70 % → 100 %)
- Comparaison de deux stratégies de découpage : recall@8 **70 % vs 91 %**
- Défenses contre le **prompt injection** (filtre d'entrée, délimitation des données, validation des citations en code) : 8 attaques sur 10 neutralisées contre 5 sans défenses, **100 % des citations vérifiées**

### ₿ [Détection de fraude Bitcoin par Graph Neural Networks](https://github.com/AmineBnh21/FRAUDE-DETECTION)
`PyTorch Geometric` `scikit-learn` `GCN` `GraphSAGE` `GAT`

Classification de **203 000+ transactions Bitcoin** (234 000 flux, dataset Elliptic) en licites / illicites.
- Comparaison GCN, GraphSAGE et GAT face à une baseline Random Forest, avec **split temporel** et F1 sur la classe illicite (2 % des données)
- Embeddings GraphSAGE + Random Forest : précision portée à **0,97**, fausses alertes **divisées par 3** (55 → 19) à F1 égal
- Résultats cohérents avec Weber et al. (2019) : RF 0,81 vs 0,64 pour le meilleur GNN seul

### ✈️ [British Airways — Data Science Job Simulation](https://github.com/AmineBnh21/British_Airways_Project)
`CatBoost` `Optuna` `SHAP` `pandas`

- Prédiction de la finalisation de **50 000 demandes de réservation** (15 % de positifs) : ROC-AUC **0,795**, PR-AUC **0,372** (hasard : 0,15) sur un test jamais vu ; **lift ×2,5** (50 % des réservations captées en ciblant 20 % des clients)
- **Fuite de données détectée et corrigée** (un encodage naïf gonflait l'AUC à 0,81) via un target encoding en cross-fitting ; variable originale « rôle du voyageur », interprétation SHAP
- Estimation de l'éligibilité aux salons de Heathrow sur 10 000 vols (table réutilisable type de route × région)

### 🚗 Négociation automatique multi-agents — stage de recherche (Lyon 1)
`Python` `asyncio` `NumPy` `pandas` `Matplotlib`

Modélisation du stationnement urbain comme un système multi-agents où véhicules et parkings négocient place et tarif : utilité multicritère côté conducteur, tarification dynamique côté parking, simulation distribuée et asynchrone avec suivi de l'occupation en temps réel.

---

## 🛠️ Stack technique

**Machine Learning / Deep Learning**<br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/PyG-3C2179?style=flat-square&logo=pyg&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat-square">
<img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black">
<img src="https://img.shields.io/badge/Optuna-2C5BB4?style=flat-square">
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white">

**IA générative / NLP**<br>
<img src="https://img.shields.io/badge/LLM-412991?style=flat-square">
<img src="https://img.shields.io/badge/RAG-6E40C9?style=flat-square">
<img src="https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square">
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white">

**Langages & outils**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white">
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white">
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white">
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">

**Techniques** : GNN (GCN, GraphSAGE, GAT) · classification déséquilibrée · feature engineering · validation croisée stratifiée · prévention de la fuite de données · interprétabilité (SHAP) · évaluation de RAG · sécurité des LLM · systèmes multi-agents

---

## 📜 Certifications

- Forage — Tata Group Data Analytics Job Simulation
- Kaggle — Intermediate Machine Learning
- Kaggle — Intro to Deep Learning

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AmineBnh21&show_icons=true&hide_border=true&count_private=true" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmineBnh21&layout=compact&hide_border=true" height="160">
</p>

<p align="center"><i>📫 Ouvert aux opportunités de stage en Data Science / IA — n'hésitez pas à me contacter !</i></p>
