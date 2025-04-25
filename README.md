# Query Quest: The Adventures of Data and the Cloudy with a Chance of BigQuery

## Project Overview

This interactive, cloud-driven data analytics project explores the features and capabilities of Google BigQuery for real-time querying, external data integration, and modern visualization. Through hands-on exercises using Datastream, Gemini AI, and Tableau/Looker Studio, I showcase how to set up cloud analytics pipelines from ingestion to visualization.

## Objectives

- Introduce BigQuery and its real-time, serverless analytics capabilities
- Perform interactive querying on public and in-class survey data
- Connect and query external datasets using federated tables
- Explore Gemini's AI query support tools in BigQuery
- Visualize data using Tableau and Looker Studio

## Key Topics Covered

1. BigQuery Introduction

* Serverless, SQL-based cloud data warehouse
* Real-time analytics with auto-scaling
* Federated queries: No need to move data across services

2. Interactive Session 1:

* Setting up a BigQuery project (via Google Cloud Console)
* Enabling sandbox, creating projects, and adding public datasets
* Running basic SQL queries on bigquery-public-data

3. Interactive Session 2: Real-Time Analytics

* Created a Google Form for live in-class survey
* Used Datastream to ingest results into BigQuery
* Queried and visualized live responses

4. External Data & Federated Queries

* Connected BigQuery to external sources
* Created external tables without duplicating data
* Discussed limitations and cost/efficiency advantages

5. Gemini AI Integration

* Eabled Gemini in BigQuery for code generation and query explanations
* Prompted Gemini to:
* Generate queries
* Explain SQL statements
* Answer questions via AI Chatbox

## Visualization Tools

* Tableau (Desktop): Connected to BigQuery using OAuth, Created dashboards with filters, KPIs, and maps and Explored pre-built templates (Accelerators).
* Looker Studio (Web-based): Free Google tool for cloud dashboards, Connected via BigQuery source and Designed dashboards with bar charts, pie charts, filters, maps, and tables.

## Sample Queries Run in BigQuery

- SELECT state_name FROM `bigquery-public-data.america_health_rankings.ahr` WHERE subpopulation = 'Other Race';

- SELECT value FROM `bigquery-public-data.america_health_rankings.ahr` 
WHERE value > 70 AND subpopulation = 'Multiracial';

## Key Learnings

- BigQuery is ideal for scalable, real-time, cloud-native analytics
- Gemini AI enhances productivity with SQL explanations and generation
- Federated queries allow secure, low-cost data access without replication
- Data visualization tools like Tableau and Looker make insights accessible and interactive

## References

- (Google BigQuery Docs)[https://cloud.google.com/bigquery]
- (Federated Queries in BigQuery)[https://cloud.google.com/bigquery/docs/federated-queries-intro]
- (Tableau BigQuery Help)[https://help.tableau.com/current/pro/desktop/en-us/examples_googlebigquery.html]
- (BigQuery with Datastream)[https://cloud.google.com/datastream/docs/quickstart-replication-to-bigquery]
- (Looker Studio)[https://lookerstudio.google.com/overview]

## Conclusion

This project highlights the ease and power of modern cloud-based data analytics with Google BigQuery. By combining SQL querying, real-time data streaming, federated data access, AI-assisted exploration, and dynamic dashboarding, I successfully demonstrated the potential of BigQuery in both academic and professional contexts.


