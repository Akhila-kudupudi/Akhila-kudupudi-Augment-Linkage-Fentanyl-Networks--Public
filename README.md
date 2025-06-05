# Augment-Linkage-Fentanyl-Networks--Public

Welcome to the GitHub repository for our **DAEN 690 Capstone Project**:  
**Augment Linkage: Evidence and Exploration**

This project investigates **fentanyl trafficking networks** by uncovering complex corporate linkages using interactive dashboards, graph databases, and curated data modeling.

---

## 🚨 Disclaimer

⚠️ **Sensitive datasets are not included in this public repository** due to privacy and institutional restrictions.  
The repository includes schema diagrams, code samples, and usage instructions that demonstrate our graph modeling, data visualization, and dashboarding pipelines.

---

## Project Overview

We explored hidden **communication** and **payment-based connections** among companies using:

- Shared identifiers (email, phone, chat)
- Normalized and curated datasets (not publicly shared)
- Multi-platform visualizations via **Tableau**, **Neo4j**, and **AWS Neptune**

---

## Project Structure

| Branch                      | Description                                                           |
|----------------------------|------------------------------------------------------------------------|
| `tableau-Interactive-graphs` | Tree graph dashboard (structure + dummy config)                       |
| `Neo4j-Graph-Implementation` | Sample Cypher queries and schema for relationship exploration         |
| `AWS-Neptune`                | Code and Gremlin scripts for graph ingestion and query patterns        |

---

## Visual Models (No Real Data Included)

### Tableau

- Tree-based visualization model using Tableau Extension Gallery
- Interactive filters and mock tooltips

### Neo4j Graph Schema

(BaseConsolidation)
├─[:HAS_METHOD]→ (LinkageMethod)
├─[:HAS_LINKAGE]→ (LinkageValue)
└─[:HAS_ASSOCIATED_COMPANY]→ (AssociatedCompany)


Includes example Cypher queries for:
- Identifying top connected nodes
- Tracing indirect relationships

### AWS Neptune (Gremlin)

- Includes notebooks with:
  - Graph modeling patterns
  - Sample ingestion logic
  - Gremlin traversal patterns

---

## How to Use

| Platform | Instructions |
|----------|--------------|
| Tableau  | Load `.twbx`, enable Tree Extension (demo structure only) |
| Neo4j    | Launch local server, import schema and test queries        |
| Neptune  | Use Gremlin notebooks with placeholder data or local mocks |

---

## Dataset Notice

The following datasets were used **privately** during development:

- Curated Excel sheets with communication identifiers
- Normalized linkage files with corporate metadata
- Derived evidence scores and metadata

**These are not included** in this public repository.


---

## 👥 Contributors

- Sai Surya Gadiraju  
- Sai Charan Somineni  
- Pooja Manjunatha Swamy  
- Jerry Vishal Joseph  
- Shreya Reddy Jukanna  
- **Akhila Kudupudi**  
- Sai Sameer Sri Vastav Pillutla

---

## 📜 License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for usage guidelines.


