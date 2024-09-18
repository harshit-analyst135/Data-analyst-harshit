# Data-analyst-harshit
Project 1: Vancouver Animal Control Inventory Analytics Platform (VACIAP)
Objective:
To design and implement a comprehensive data analytics platform for analyzing the City of Vancouver's Animal Control Inventory data, enabling data-driven decision making for animal welfare policies, operational improvements, and public transparency, while ensuring data protection, governance, and monitoring.
Background:
The City of Vancouver's Animal Services department manages various aspects of animal control, including lost and found animals, deceased animals, and general animal custody records. Currently, this data is stored in separate datasets, limiting the ability to perform comprehensive analysis. A unified analytics platform is needed to gain deeper insights into animal control operations, trends, and outcomes, while adhering to best practices in data management and security.
Dataset:
We will use three primary datasets from the City of Vancouver Open Data Portal:
Animal control inventory - register
Animal control inventory - lost and found
Animal control inventory - deceased animal
These datasets contain information on animals in the custody of Vancouver Animal Control, including species, breed, intake date, outcome, and location details.
Methodology:
Data Analytical Question Formulation
Data Discovery
Data Storage Design
Dataset Preparation
Data Ingestion
Data Storage
Data Pipeline Design
Data Protection Implementation
Data Governance Framework Development
Data Monitoring System Design
DAP Architecture Analysis (focusing on AWS Well-Architected Framework pillars)
Tools and Technologies:
Data Storage: Amazon S3, Amazon RDS
Data Processing: AWS Glue
Data Analysis: Amazon Athena, Amazon QuickSight
Security: AWS Identity and Access Management (IAM), AWS Key Management Service (KMS)
Monitoring: Amazon CloudWatch
Infrastructure as Code: AWS CloudFormation
Version Control: Git, GitHub
Project Management: Jira
Deliverables:
Detailed project plan and architecture design document
Implemented data lake on Amazon S3 with proper structure and access controls
Data ingestion pipelines for all three datasets
Data catalog with metadata for all datasets
ETL jobs for data cleaning and transformation
SQL queries for common analytical tasks
QuickSight dashboards for key animal control metrics
Comprehensive data protection plan
Data governance framework and policies
Real-time data monitoring dashboard
Detailed DAP architecture analysis report covering all six AWS Well-Architected pillars
Implementation guide for each pillar's best practices
Cost optimization recommendations
Sustainability assessment and improvement plan
Final project report with insights and recommendations
Timeline:
Weeks 1-2: Requirements gathering and architecture design
Weeks 3-4: Data lake setup and initial data ingestion
Weeks 5-6: Data catalog creation and ETL job development
Weeks 7-8: Query development and initial analysis
Weeks 9-10: Dashboard creation and visualization
Weeks 11-12: Data protection and governance implementation
Weeks 13-14: Monitoring system setup and testing
Weeks 15-16: Architecture analysis and optimization
Weeks 17-18: Documentation and final report preparation
Data Wrangling:
Consolidate data from the three separate animal control inventory datasets
Standardize date formats across all datasets
Clean and normalize animal species and breed information
Handle missing values in key fields (e.g., intake date, outcome)
Create derived features (e.g., length of stay, seasonal trends)
Implement data quality checks to ensure consistency across datasets
Develop a unified schema that accommodates all animal control inventory data
Create aggregated views for common analysis scenarios (e.g., monthly intake summaries)
Implement data anonymization techniques for privacy protection
Develop data validation rules for ongoing data ingestion
This project will result in a comprehensive Animal Control Inventory Analytics Platform for the City of Vancouver, providing valuable insights into animal control operations, trends in animal intake and outcomes, and supporting data-driven policy decisions for improved animal welfare in the city. The platform will adhere to best practices in data protection, governance, and cloud architecture design, ensuring operational excellence, security, reliability, performance efficiency, cost optimization, and sustainability.

Project 2: UCW Academic Faculty Analytics Platform (AFAP)
Objective:
To design and implement a comprehensive data analytics platform for analyzing University Canada West's academic faculty data, enabling data-driven decision making for faculty management, performance evaluation, and resource allocation while ensuring data protection, governance, and monitoring.
Background:
University Canada West needs a robust system to analyze and manage data related to its academic faculty. Currently, faculty data is stored in disparate systems, limiting the ability to perform comprehensive analysis. A unified analytics platform is needed to gain deeper insights into faculty performance, research output, teaching effectiveness, and workload distribution.
Dataset:
Faculty demographic information
Course teaching history and student evaluations
Research publications and citations
Grant funding information
Faculty workload data (teaching, research, administrative duties)
Professional development activities
Performance review data
Methodology:
Data Analytical Question Formulation
Data Discovery
Data Storage Design
Dataset Preparation
Data Ingestion
Data Storage
Data Pipeline Design
Data Protection Implementation
Data Governance Framework Development
Data Monitoring System Design
DAP Architecture Analysis (focusing on AWS Well-Architected Framework pillars)
Tools and Technologies:
Data Storage: Amazon S3, Amazon RDS
Data Processing: AWS Glue
Data Analysis: Amazon Athena, Amazon QuickSight
Security: AWS Identity and Access Management (IAM), AWS Key Management Service (KMS)
Monitoring: Amazon CloudWatch
Infrastructure as Code: AWS CloudFormation
Version Control: Git, GitHub
Project Management: Jira
Deliverables:
Detailed project plan and architecture design document
Implemented data lake on Amazon S3 with proper structure and access controls
Data ingestion pipelines for all faculty data sources
Data catalog with metadata for all datasets
ETL jobs for data cleaning and transformation
SQL queries for common analytical tasks
QuickSight dashboards for key faculty performance metrics
Comprehensive data protection plan
Data governance framework and policies
Real-time data monitoring dashboard
Detailed DAP architecture analysis report covering all six AWS Well-Architected pillars
Implementation guide for each pillar's best practices
Cost optimization recommendations
Sustainability assessment and improvement plan
Final project report with insights and recommendations
Timeline:
Weeks 1-2: Requirements gathering and architecture design
Weeks 3-4: Data lake setup and initial data ingestion
Weeks 5-6: Data catalog creation and ETL job development
Weeks 7-8: Query development and initial analysis
Weeks 9-10: Dashboard creation and visualization
Weeks 11-12: Data protection and governance implementation
Weeks 13-14: Monitoring system setup and testing
Weeks 15-16: Architecture analysis and optimization
Weeks 17-18: Documentation and final report preparation
Data Wrangling:
Consolidate faculty data from various university systems (HR, LMS, research databases)
Standardize naming conventions and data formats across all datasets
Clean and normalize research publication data (journal names, author affiliations)
Handle missing values in key fields (e.g., course evaluations, research outputs)
Create derived features (e.g., publication impact factors, teaching effectiveness scores)
Implement data quality checks to ensure consistency across datasets
Develop a unified schema that accommodates all faculty-related data
Create aggregated views for common analysis scenarios (e.g., departmental performance, research output by year)
Implement data anonymization techniques for sensitive information (e.g., salary data)
Develop data validation rules for ongoing data ingestion
This project will result in a comprehensive Academic Faculty Analytics Platform for University Canada West, providing valuable insights into faculty performance, research output, and teaching effectiveness. The platform will adhere to best practices in data protection, governance, and cloud architecture design, ensuring operational excellence, security, reliability, performance efficiency, cost optimization, and sustainability.
