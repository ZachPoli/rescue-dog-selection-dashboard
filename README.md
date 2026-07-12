# Rescue Dog Selection Dashboard

An interactive dashboard that helps a rescue organization review animal shelter records and identify dogs that may be suitable for specialized training programs.

## Business Problem

Grazioso Salvare needed a faster and more consistent way to search a large shelter dataset for dogs that matched its rescue-training criteria. Reviewing records manually would make it difficult to compare candidates, apply the same selection rules, and understand the available dog population.

## Project Value

This project turns shelter records stored in MongoDB into an accessible decision-support dashboard. Users can filter the data, review matching animals, and visualize relevant information without writing database queries. The result is a more efficient and data-driven way to identify potential rescue-training candidates.

## Key Features

- Filters shelter records according to rescue-training requirements
- Displays matching animals in an interactive dashboard
- Connects the dashboard to a MongoDB database through a reusable Python CRUD module
- Supports creating, reading, updating, and deleting database records
- Separates database operations from the dashboard interface for easier maintenance
- Presents data visually to support faster comparison and decision-making

## Data Workflow

1. Animal shelter data is stored in MongoDB.
2. A reusable Python CRUD module handles database access and record operations.
3. The dashboard sends filter criteria to the database layer.
4. Matching records are returned to the user interface.
5. The results are displayed in interactive tables and visualizations for review.

## Technologies Used

- **Python** — application logic and database integration
- **MongoDB** — document-based storage and querying
- **PyMongo** — connection between Python and MongoDB
- **Dash** — interactive web dashboard
- **Plotly** — data visualization
- **Jupyter Notebook** — development and testing environment

## Skills Demonstrated

- Translating client requirements into a working data product
- Designing reusable CRUD operations for a NoSQL database
- Filtering and presenting operational data for decision support
- Connecting a database backend to an interactive dashboard
- Organizing code for readability, maintenance, and reuse
- Communicating technical results through a user-focused interface

## Potential Enhancements

- Add more flexible user-defined filtering options
- Include data-quality checks for missing or inconsistent shelter records
- Add summary metrics for candidate counts and breed distribution
- Export filtered results for reporting and follow-up
- Add automated tests for database and dashboard functionality

## Background

This project was originally completed as part of Southern New Hampshire University's CS-340 Client/Server Development course. It is presented here as a portfolio example of database integration, dashboard development, and data-driven problem-solving.

---

*Created by Zachary Maness.*