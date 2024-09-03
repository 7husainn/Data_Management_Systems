# Data_Management_Systems


This repository contains the group project for the Data Management Systems (SMM695) module as part of the MSc Business Analytics program. The project focuses on the effective management, processing, and analysis of data from Decentralized Autonomous Organizations (DAOs) using MongoDB and various data processing techniques. The repository documents the complete workflow, from data ingestion and cleaning to advanced analysis using Natural Language Processing (NLP) techniques.

Project Overview: DAO Data Management and Analysis
Description: This project presents a comprehensive approach to managing and analyzing data from DAOs using MongoDB, a NoSQL database optimized for handling unstructured and semi-structured data. The project is divided into several key phases: data ingestion, data structuring, descriptive insights, and advanced proposal analysis using NLP techniques.

Phase 1: Database Choice and Data Preprocessing

Objective: To select an appropriate database and prepare DAO data for further analysis.

Database Selection: MongoDB was chosen over PostgreSQL due to its flexibility in handling the unstructured and evolving nature of DAO data, especially when dealing with JSON-like documents from sources such as Snapshot APIs.

Data Loading and Structuring:
Implemented a custom function to load data from pickle files into MongoDB collections.
Applied various data cleaning strategies, ensuring the integrity and completeness of the dataset while retaining null values to avoid introducing bias.
Structured data using MongoDB’s aggregation pipeline to optimize query performance and facilitate efficient analysis.




Phase 2: Descriptive Insights

Objective: To provide an initial understanding of DAO engagement and activity through descriptive statistics.
Key Insights:
Votes and Proposals: Analyzed the distribution of votes and proposals across different DAO spaces, identifying high engagement areas like Arbitrum DAO and PancakeSwap.
Voting Strategies: Examined the diversity of voting strategies employed by various DAOs, highlighting the flexibility and inclusivity of governance mechanisms.
Transaction Costs: Compared transaction costs between Ether (ETH) and Polygon (MATIC) networks, offering insights into the economic considerations of using different blockchain platforms.


Phase 3: Advanced Proposal Analysis Using NLP

Objective: To cluster DAO proposals and identify key topics that attract high votes using NLP techniques.

Text Preprocessing: Cleaned and prepared proposal content for analysis, ensuring the text was suitable for clustering and topic modeling.

Clustering Techniques:
Bag of Words (BoW): Applied K-Means clustering using the BoW model to group proposals into topics related to DeFi governance, community support, and token proposals.
BERT Embeddings: Used BERT for deep contextual analysis, identifying clusters that focused on governance, protocol proposals, and miscellaneous topics.
TF-IDF: Highlighted important words across the corpus, clustering proposals into governance-related and liquidity-focused topics.

Insights and Conclusions:
Identified key themes that resonate with the DAO community, such as governance, liquidity management, and community engagement.
Proposed best practices for structuring proposals to maximize community support and voting success.

Conclusion: This project demonstrates a holistic approach to managing and analyzing DAO data, leveraging MongoDB for flexible data handling and NLP techniques for deep analysis. The insights gained can inform better governance and decision-making within DAO ecosystems.
