# Recommendation Engine

### Overview

This is a project to explore new packages/frameworks and tools on the way to building an article recommendation engine. The goal is to be able to interpret a large set of 'atomic' notes pages as commonly found in a digital garden and provide a few relevant links to other notes that are related.

The UI will be a website where you can supply a specific subdomain (i.e. example.site.com) and it will index through all of the pages to analyze their content and tabulate recommendations for each. Long-term it may be built to modify .md files and add the recommendations within each note page automatically but I am not planning that for the initial sprint.

This project uses a Django/FastAPI backend and a React frontend. Swagger, Jest, and Cypress will help with test and documentation. Docker and Kubernetes will containerize and deploy the application on AWS.