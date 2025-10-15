## NYT Data Engineering Project

### Architecture
 ![Architecture](https://github.com/Sathvika2721/The-NewYork-Times-Data-Pipeline/blob/main/Architecture.pdf)

 
# Project Overview

The New York Times API Data Engineering Project focuses on recreating and managing the NYT Books and Articles API using a modern data pipeline architecture. The goal is to extract, store, and serve structured NYT data through a FastAPI interface connected to a PostgreSQL database.
This project demonstrates how to build an efficient, containerized data system capable of integrating external APIs, managing data pipelines, and exposing reliable endpoints for querying information. By combining Python, FastAPI, and Docker, the project ensures scalability, maintainability, and ease of deployment.

# Features

1. **Data Extraction**: Retrieves Books and Articles data from the NYT Developer Portal via REST API.
2. **Data Storage**: Persists structured data in a PostgreSQL database for long-term access.
3. **ORM Integration**: Uses SQLAlchemy to manage database models and handle data operations efficiently.
4. **API Endpoints**: Exposes RESTful endpoints built with FastAPI for seamless data retrieval and interaction.
5. **Containerization**: Fully containerized using Docker for reproducible environments and simplified deployment.
6. **Automation Ready**: Supports scheduling or event-driven data extraction for regular updates.

# Tech Stack
- Python
- FastAPI
- PostgreSQL
- SQLAlchemy
- Docker
- Requests / NYT Developer API

# How It Works

- The system connects to the NYT Developer API to extract Books and Articles data.
- Extracted data is cleaned, validated, and loaded into PostgreSQL using SQLAlchemy ORM.
- A FastAPI service exposes endpoints to retrieve and query stored NYT data.
- The entire project is containerized using Docker, allowing consistent setup across environments.
- Optional scheduling (e.g., via cron or AWS Lambda) can automate data refresh cycles.

# Required Libraries
- pandas
- sqlalchemy
- psycopg2
- fastapi
- uvicorn
- requests
- docker  

# Execution Flow

1. Extract data from NYT Developer API (Books and Articles endpoints).
2. Store the raw and cleaned data in PostgreSQL tables.
3. Use SQLAlchemy to define schemas and manage database interactions.

Serve processed data through FastAPI endpoints.

Containerize the application using Docker for easy deployment and scalability.
