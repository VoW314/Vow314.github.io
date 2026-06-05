---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **B.S. Computational Modeling and Data Analytics** — Virginia Tech, December 2026 (expected)
  * Minor: Computer Science
  * Concentration: Cryptography & Cybersecurity
  * Relevant Coursework: Machine Learning, Data Analytics, Statistical Methods, Probability & Statistics, Linear Algebra, Data Structures & Software Design

Work Experience
======
* **Machine Learning Researcher** — May 2022 to May 2024
  * Hume Center for National Security and Technology, Virginia Tech
  * Led a 25+ member undergraduate research team on reinforcement learning, adversarial ML, and network simulation
  * Developed Deep Q-Network (DQN) agents to automate penetration-testing workflows and model adversarial behavior in simulated network environments
  * Conducted large-scale RL experiments: 10,000 training episodes, 1M+ exploration steps across multiple adversarial agents
  * Co-authored IEEE-published research presented at SIEDS 2023 and HammerCon 2023

* **Undergraduate Researcher** — Sep 2021 to Apr 2022
  * Hume Center for National Security and Technology, Virginia Tech
  * Built fraud detection models using Random Forest and KNN on 300K+ credit card records
  * Applied SMOTE and ADASYN to address class imbalance and improve model robustness
  * Achieved AUC scores up to 1.0 with Scikit-learn across Random Forest, KNN, and Logistic Regression

* **Research Intern** — Summer 2020
  * Virginia Tech (Dr. Tafti) & University of Virginia (Dr. Vullikanti)
  * Built a GUI mockup to modernize a legacy application at VT
  * Created a visual data analysis on school reopening safety in Virginia during COVID-19 at UVA

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Languages:** Python, Java, SQL, R, C
* **ML / AI:** PyTorch, Scikit-learn, Reinforcement Learning, Deep Q-Networks (DQN), YOLOv11 (Ultralytics), Computer Vision
* **Data:** Pandas, NumPy, Statistical Modeling, Power BI, Jupyter Notebook
* **Cloud & Web:** AWS EC2, Streamlit, MySQL, WildFly, Git
