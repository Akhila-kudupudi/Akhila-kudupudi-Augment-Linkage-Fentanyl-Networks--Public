# Augment-Linkage-Fentanyl-Networks--Public
A public demo of graph modeling techniques using Neo4j, AWS Neptune, and Tableau to explore inter-organizational linkages—based on my DAEN 690 capstone project. This version contains no real data and is designed for educational showcase only.


This repository demonstrates graph-based modeling and querying approaches for analyzing organizational linkages using tools like Neo4j, AWS Neptune, and Tableau. It serves as a public showcase of my capstone project, without sharing any data or sensitive content.

> ⚠️ Note: No real or synthetic datasets are included in this repository. Code and structure are for conceptual demonstration only.

---

## 🔍 Objective

To highlight how graph techniques can be used to uncover relationships between entities based on communication methods like:

- Email
- Phone
- Chat handles (e.g., WhatsApp, Telegram)
- Payment identifiers

---

## 🛠 Technologies Featured

- **AWS Neptune** with Gremlin
- **Neo4j** with Cypher
- **Tableau** dashboards
- **Python** (networkx for local modeling)

---

## 📂 What’s Inside

- `notebooks/graph_modeling_template.ipynb`: Template for building a simple entity graph (nodes & edges)
- `neo4j/sample_cypher_queries.txt`: Sample Cypher queries to explore graph relationships
- `neptune/sample_gremlin_queries.txt`: Common traversal examples for AWS Neptune
- `tableau/dashboard_mockup.png`: Visual sketch of a dashboard built in Tableau (for illustration only)

---

## 💡 Sample Graph Schema

- **Company** nodes connected by shared **Attribute Values** (e.g., email, phone)
- Relationship types:
  - `:USES_EMAIL`, `:USES_PHONE`, `:USES_CHAT`, `:USES_PAYMENT`
- Traversals to find common contacts or indirect associations

---

## 📜 License

This repository is open-sourced under the **MIT License**.
