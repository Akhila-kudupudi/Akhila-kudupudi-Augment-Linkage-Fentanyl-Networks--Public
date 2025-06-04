
# Augment Linkage: Evidence and Exploration

Welcome to the GitHub repository for our **DAEN 690 Capstone Project**:  
**Augment Linkage: Evidence and Exploration**

This project explores the **linkages between companies involved in the illicit fentanyl supply chain**, aiming to uncover hidden networks and communication trails through interactive visualizations and cloud-based graph analytics.

---

## Project Structure

This repository is organized into multiple branches, each dedicated to a specific technology or visualization method:

| Branch                     | Description                                                                 | Status   |
|---------------------------|-----------------------------------------------------------------------------|----------|
| `tableau-Interactive-graphs` | Dynamic Tableau dashboards and filters to visualize corporate linkages.      | ✅ Active |
| `Neo4j-Graph-Implementation` | Local graph modeling using Neo4j and Cypher for relationship exploration.     | ✅ Active |
| `AWS-Neptune`               | Preprocessed datasets formatted for loading and querying in AWS Neptune.     | ✅ Active |

---

## Overview

Our work focuses on **identifying and analyzing connections among companies that play a role in fentanyl trafficking**, using key communication identifiers such as:

- Emails
- Phone numbers
- Chat handles
- Payment identifiers

We combine:
- Local graph databases (**Neo4j**)
- Scalable cloud graph engines (**AWS Neptune**)
- Rich interactive dashboards (**Tableau**)

---

## Explore Sub-Branches

Explore each module directly:

- [🔗 Tableau Dashboards](../../tree/tableau-Interactive-graphs)
- [🔗 Neo4j Graph Implementation](../../tree/Neo4j-Graph-Implementation)
- [🔗 AWS Neptune](../../tree/AWS-Neptune)

---

## 📊 Visual Results

The project outputs include:

- Weighted graphs showing communication and financial linkages
- Centrality and clustering of top company hubs
- Drill-downs into connection trails
- Interactive filters based on roles and regions
- Deep entity lookups via Gremlin queries

---

## 📁 Datasets Used

We utilized and cleaned the following sources:

- TraCCC’s normalized and key-value datasets
- Reset versions of linkage data
- Manually cleaned Spring 2025 Excel sheets

See the `AWS-Neptune` branch for detailed processing.

---

## 🚀 How to Run

Each branch contains a guide to running its environment:

- **Neo4j**: Launch local server + run Cypher queries
- **AWS Neptune**: Use Jupyter Workbench + Gremlin
- **Tableau**: Open `.twbx` files with processed datasets

---

## 👥 Contributors

- Sai Surya Gadiraju  
- Sai Charan Somineni
- **Akhila Kudupudi**  
- Pooja Manjunatha Swamy  
- Jerry Vishal Joseph  
- Shreya Reddy Jukanna  
- Sai Sameer Sri Vastav Pillutla  

---

## 📜 License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for more details.
