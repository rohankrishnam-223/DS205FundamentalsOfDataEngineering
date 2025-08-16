# DS205FundamentalsOfDataEngineering
UC Berkeley Masters of Data Science course DS205: Fundamentals of Data Engineering


This repository contains coursework and the final project for the UC Berkeley Data Engineering course. Throughout the semester, we explored modern database systems and cloud-native workflows using:

PostgreSQL — Relational database management

MongoDB — Document-oriented NoSQL database

Redis — In-memory key-value store

Neo4j — Graph database (for final project focus)

All services were run in Docker containerized JupyterLab environments hosted on cloud compute instances. This setup allowed us to simulate production-like workflows for cloud databases while maintaining the flexibility of interactive development.

Course Components
1. Labs & Exercises

Learned to spin up Postgres, MongoDB, Redis in Dockerized JupyterLab environments.

Practiced CRUD operations, indexing, querying, and schema design across different database paradigms.

Connected Python notebooks to databases using libraries such as psycopg2, pymongo, and redis-py.

2. Cloud Deployment

Deployed databases and Jupyter notebooks on remote compute instances, simulating real-world cloud engineering workflows.

Used container orchestration for isolated services and reproducible environments.

3. Comparative Analysis

Explored differences between relational and non-relational databases.

Benchmarked query performance, scalability, and data modeling trade-offs.

Final Project — Acme Gourmet Meals (AGM) Business Case

For the capstone project, teams worked as data engineers transitioning into data scientists for Acme Gourmet Meals (AGM). The project explored how different database technologies could support AGM’s future vision, including delivery via BART, drones, and robots.

Deliverables

Presentation (PDF slides) — Business case and technical demos.

Code Directory — Prototypes for database connections, data loading, and queries.

README Updates — Team member names and project documentation.

Project Requirements

Neo4j (Primary Focus)

Create at least one graph database.

Run 3+ graph data science algorithms (e.g., shortest path, centrality, community detection).

Business case examples tied to AGM’s future delivery vision.

MongoDB (Secondary Focus)

Demonstrate a business case where document-oriented modeling is a better fit than relational databases.

Redis (Secondary Focus)

Demonstrate a business case for in-memory caching and real-time lookups.

Teamwork & Workflow

Teams of 3–4 students collaborated through GitHub Classroom.

Weekly check-ins via Zoom/Slack to ensure equal effort and progress.

GitHub workflow:

Each member cloned the team repo.

Work committed to a project branch.

Pull Request created to merge into main.
