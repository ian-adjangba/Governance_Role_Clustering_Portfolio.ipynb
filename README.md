# Governance Role Clustering Framework

Applied NLP and clustering project that groups cybersecurity job-role text into governance, risk, compliance, audit, and assurance domains.

## Project Overview

This project applies unsupervised learning to cybersecurity job-role data to build a **Governance Role Assigning Clustering Framework**. The notebook uses text preprocessing, TF-IDF vectorization, K-means clustering, silhouette score analysis, and hierarchical clustering visualization to identify natural role groupings across cybersecurity and technology governance work.

The goal is to translate raw job-role text into interpretable governance domains such as:

- IT audit and assurance
- Governance, risk, and compliance
- Security operations
- Risk and remediation
- Program oversight
- Leadership and management

The project also includes a reinforcement learning section using Q-learning to compare two bots trained with different exploration rates.

## Dataset Credit

This project uses the Kaggle dataset **Salary Cyber Security Jobs**, created by **Danny Revaldo**.

- Dataset source: Kaggle — Salary Cyber Security Jobs
- Dataset author / contributor: Danny Revaldo
- Dataset link: https://www.kaggle.com/datasets/dannyrevaldo/salary-cyber-security-jobs

Danny Revaldo is credited as the dataset author/data contributor for the cybersecurity job data used in the clustering analysis. The notebook, preprocessing workflow, clustering interpretation, governance role framework, reinforcement learning section, and portfolio framing were developed separately for academic and portfolio purposes.

## Methods Used

### Part I — Text Clustering

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

### Part II — Reinforcement Learning

- Q-learning simulation
- Two-bot comparison: Simon vs. Olive
- Exploration-rate parameter testing
- Reward and step comparison
- Gameplay/performance interpretation

## Repository Structure

```text
.
├── Governance_Role_Clustering_Assignment4.ipynb
├── README.md
├── requirements.txt
└── .gitignore
