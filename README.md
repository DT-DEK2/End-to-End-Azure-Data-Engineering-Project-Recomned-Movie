<h1 align="center">RECOMMEND_MOVIED</h1>

# RECOMMEND_MOVIED: End-to-End Project Overview
The RECOMMEND_MOVIED project illustrates a comprehensive pipeline from data collection and preparation to model training, deployment, and user interface integration, utilizing various Azure services. Here's a detailed description based on the provided image:
<!-- PROJECT LOGO -->
 <br />
<div align="center">
  <a href="Document/work flow.png">
    <img src="Document/work flow.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div> 


# Data Preparation and Modeling:
-  Data Collection: Data is sourced from The Movie Database (TMDB) API and ingested using Azure Data Factory.
- Storage: The collected data is stored in Azure Storage and SQL Server.
- Processing: Azure Databricks processes the data for modeling purposes.

# Model Training:
- Azure Machine Learning Service: The processed data is fed into Azure Machine Learning Service for model training.

# Live Serving:
 - Data Storage: Trained models and necessary data are stored in Azure Cosmos DB.
 - Model Deployment: The models are deployed using Azure Kubernetes Service for live serving.
# User Interface:
 - Integration with PowerApps: Microsoft PowerApps provides the user interface, enabling user clients to interact with the deployed model.

This architecture demonstrates an efficient workflow that leverages Azure's capabilities for seamless data handling, model training, deployment, and user interaction, forming a robust recommendation system.