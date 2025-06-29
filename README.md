# 🧠 UTD24-SCH: A Scientific Collaboration Hypergraph Dataset
**UTD24-SCH** is an academic collaboration dataset constructed from the UTD 24 journal list, which includes the most prestigious journals in business and management research. This dataset focuses on publications from 2020 to 2024, and is designed to support research on scientific collaborator recommendation, academic network modeling, and hypergraph representation learning.

## 🔍 Dataset Highlights
**Source**: [UTD 24 journals](https://jindal.utdallas.edu/the-utd-top-100-business-school-research-rankings/).

**Time window**: 2020–2024, 5 years.

**Collected metadata**:
(1) Article title & abstract
(2) Author names & order
(3) Author affiliations & institutions
(4) Publication venue & year
(5) Author semantic attributes: gender, career stage, research domain.

## 🧩 Hypergraph Construction
The dataset is used to construct a Scientific Collaboration Hypergraph (SCH), where nodes represent:
Scholars, papers, institutions, venues, research expertise, gender, and more.
Hyperedges represent high-order relations such as:
Coauthorship (Scholar–Paper),
Institutional affiliation (Scholar–Institution),
Research interest (Scholar–Topic),
Productivity & demographic links.

## 💡 Applications
This dataset supports a wide range of academic tasks:
Scientific collaborator recommendation,
Hypergraph neural network training,
Interpretability-enhanced academic recommendation systems,
Cold-start performance analysis.
