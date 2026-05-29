# Governance Role Clustering Framework

Applied NLP and clustering project that uses cybersecurity job-role data to identify governance, risk, compliance, audit, and security operations domains.

## Project Overview

This project applies unsupervised learning to cybersecurity job-role data to build a **Governance Role Clustering Framework**. The notebook uses text preprocessing, TF-IDF vectorization, K-means clustering, silhouette score analysis, and hierarchical clustering visualization to identify natural role groupings across cybersecurity and technology governance work.

The purpose of the project is to translate raw cybersecurity job-role text into interpretable governance domains such as:

- Audit
- Compliance
- Risk
- Security Operations
- Governance

The portfolio version also includes a reinforcement learning extension that compares how different learning rates affect Q-learning agent performance. The learning-rate experiment is framed as a governance training policy simulation, where agents update their decision strategies at different speeds.

---

## Dataset Credit

This project uses the Kaggle dataset **Salary Cyber Security Jobs**, created by **Danny Revaldo**.

- Dataset source: Kaggle — Salary Cyber Security Jobs
- Dataset author / contributor: Danny Revaldo
- Dataset link: https://www.kaggle.com/datasets/dannyrevaldo/salary-cyber-security-jobs

Danny Revaldo is credited as the dataset author/data contributor for the cybersecurity job data used in the clustering analysis. The notebook, preprocessing workflow, clustering interpretation, governance role framework, reinforcement learning interpretation, and portfolio framing were developed separately.

---

## Methods Used

### Text Clustering and Governance Role Analysis

- KaggleHub dataset download
- Dataset loading and inspection with Pandas
- Text field construction from cybersecurity job-role data
- Tokenization with NLTK
- Stop-word removal
- Punctuation cleanup
- Snowball stemming
- TF-IDF vectorization
- K-means clustering
- Cluster assignment and distribution analysis
- Top representative term extraction
- Silhouette score testing from k = 2 to k = 20
- Hierarchical clustering dendrogram for role-domain visualization
- Governance role interpretation and cluster labeling

### Reinforcement Learning Extension

- Q-learning agent comparison
- Learning-rate parameter experiment
- Conservative learner vs. aggressive learner comparison
- Reward and performance interpretation
- Governance training policy analogy

---

## Repository Structure

```text
.
├── Governance_Role_Clustering_Portfolio.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Governance Interpretation

The clustering model is interpreted as a governance role assignment framework. Job-role records that share similar terms and responsibilities are grouped into clusters, then translated into possible governance domains. This supports a workforce-analysis view of how cybersecurity responsibilities can be organized around risk, controls, evidence, compliance, remediation, and oversight.

In practical terms, the project asks:

- Which cybersecurity roles use similar language?
- Which roles align most closely with audit, compliance, risk, security operations, or governance?
- What role domains naturally emerge from cybersecurity job-description text?
- How can clustering support role assignment or workforce planning?
- How does training speed affect decision-making behavior in a reinforcement learning agent?

---

## Suggested Visuals to Export

Recommended visuals from the notebook for GitHub or portfolio use:

1. Silhouette score plot
2. Cluster distribution chart
3. Top terms per cluster table
4. Hierarchical dendrogram
5. Governance role cluster assignment table
6. Q-learning learning-rate comparison chart

---

## Portfolio Description

Built a governance-focused machine learning notebook that applies NLP, TF-IDF vectorization, K-means clustering, silhouette score analysis, and hierarchical clustering visualization to cybersecurity job-role data. The project groups similar cyber/GRC responsibilities into governance role domains such as audit, compliance, risk, security operations, and governance. A reinforcement learning extension compares how different learning rates affect Q-learning agent behavior and uses that comparison as a governance training policy analogy.

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- SciPy
- KaggleHub

---

## Portfolio Context

This project was developed as an applied governance analytics notebook. It demonstrates how unsupervised learning can support cybersecurity workforce analysis, governance role assignment, and technology assurance interpretation.
