<h1 align="center">RECOMMEND_MOVIED</h1>

# RECOMMEND_MOVIED: End-to-End Project Overview
The RECOMMEND_MOVIED project illustrates a comprehensive pipeline from data collection and preparation to model training, deployment, and user interface integration, utilizing various Azure services. Here's a detailed description based on the provided image:
<!-- PROJECT LOGO -->
 <br />
<div align="center">
  <a href="Document/work flow.png">
    <img src="Document/work flow.png/" >
  </a>
</div>

# Demo
  ## 1. Setting Call API, Build Pipeline in Azure Data Factory
  [![Watch the video](https://img.youtube.com/vi/od2siqwEgSo/maxresdefault.jpg)](https://youtu.be/od2siqwEgSo?si=SahvtoT7YWb3tCKd)

  ## 2. Deploy model in Databricks
  [![Watch the video](https://img.youtube.com/vi/gcFgPiljkzA/maxresdefault.jpg)](https://youtu.be/gcFgPiljkzA?si=U3wINPLN-_J-LJz7)

  ## 3. Demo User Interface
  [![Watch the video](https://img.youtube.com/vi/-LpfIuldd2o/maxresdefault.jpg)](https://youtu.be/-LpfIuldd2o?si=rvK_mFuSP_0lel0r)


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

