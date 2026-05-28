# Governance Role Clustering Framework

Applied NLP and clustering project that groups cybersecurity job-role text into governance, risk, compliance, audit, and assurance domains.

## Project Overview

This project applies unsupervised learning to cybersecurity job-role data to build a **Governance Role Assigning Clustering Framework**. The notebook uses text preprocessing, TF-IDF vectorization, K-means clustering, silhouette score analysis, and hierarchical clustering visualization to identify natural role groupings across cybersecurity and technology governance work.

The purpose of the project is to translate raw cybersecurity job-role text into interpretable governance domains such as:

- IT audit and assurance
- Governance, risk, and compliance
- Security operations
- Risk and remediation
- Program oversight
- Leadership and management

The current portfolio version focuses on **unsupervised learning, NLP preprocessing, K-means clustering, silhouette analysis, and hierarchical visualization** for governance role analysis.

---

## Dataset Credit

This project uses the Kaggle dataset **Salary Cyber Security Jobs**, created by **Danny Revaldo**.

- Dataset source: Kaggle — Salary Cyber Security Jobs
- Dataset author / contributor: Danny Revaldo
- Dataset link: https://www.kaggle.com/datasets/dannyrevaldo/salary-cyber-security-jobs

Danny Revaldo is credited as the dataset author/data contributor for the cybersecurity job data used in the clustering analysis. The notebook, preprocessing workflow, clustering interpretation, governance role framework, and portfolio framing were developed separately for academic and portfolio purposes.

---

## Methods Used

### Text Clustering and Governance Role Analysis

- Dataset loading and inspection with Pandas
- Text column creation from cybersecurity job-role fields
- Tokenization with NLTK
- Stop-word removal
- Punctuation and contraction cleanup
- Snowball stemming
- TF-IDF vectorization
- K-means clustering
- Cluster assignment and distribution analysis
- Top representative term extraction
- Silhouette score testing from k = 2 to k = 20
- Hierarchical clustering dendrogram for role-domain visualization
- Governance role interpretation and cluster labeling

---

## Repository Structure

```text
.
├── Governance_Role_Clustering.ipynb
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
- Which roles appear closest to governance, risk, compliance, audit, or assurance work?
- What role domains naturally emerge from job-description text?
- How can clustering support role assignment or workforce planning?
