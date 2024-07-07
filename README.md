# mlops-databricks-hands-on
This Repo is used to learn the basics of MLOps using Databricks

- `Databricks Repos` is an essential IDE feature that allows you to connect your Databricks workspace or the Databricks development IDE with the source control so that you can keep your notebooks, source code, code files that you need for the project.

NOTE: It's not a source-control system.

Things **you can do** with Databricks Repos:
1. Create, push to, and pull from a remote Git repository.
2. Create and manage branches for development work.
3. Create notebooks and edit notebooks and other files.
4. Visually compare differences upon commit.

Things **you cannot do** with Databricks Repos:
1. Create a pull request.
2. Resolve merge conflicts.
3. Merge or delete branches.
4. Rebase a branch.

- Workspace is local to Workspace.

## Essential capabilities for MLOps:
- Robust Data processing and Management
- Secure Collaboration
- Testing
- Monitoring
- Reproducibility
- Documentation

## Databricks workflow
- Define a series of activities to complete a Task (centered around data).
- It supports scheduling. 
- It supports logging and alerting
- It supports parallel task execution.
- It's NOT a Data Movement and Transformation Service (DMAT). It's not an ETL tool, it's an orchestration tool.
- Similar to Apache Airflow, Crontab, SQL Server Agent, Windows Scheduler. 

## Workflows use a DAG (Directed Acyclic Graph)
- Vertices (Objects)
- Edges (Relationships)
- Objects and their relationships to other objects.
- Directional (directed)
- No Loops (Acyclic)

## How can you pass variables or parameters into your task?

## Schema on Read --> It makes easier to manipulate and work with files.
- You can infer the data types based on the data you see in the file.
- header "true" --> column names are in the first row of the CSV file.

## Delta Tables
