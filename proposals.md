# Project Proposal List of Team Green for Analytics Algorithms 1

## Members:
* Leonard Balon aka Bong
* Helen Mary Labao-Barrameda aka H
* Karenina Marie Comia aka Nina
* Rhodora Ipac aka Rhoda

Github Repository Link: https://github.com/lswh/maba_analytics_algorithms_project

## Proposed Topics for Algo 1 Capstone

### Policy and Decision Making: Understanding Voting Habits of the Filipino People with Clustering and Geospatial Indicators

#### Description
Using previous election datasets and geospatial datasets at the most granular level possible, we will check behavioral patterns in voting habits by geography, demographic group (if data is available to this extent), and overall sentiment for a particular region. 

#### Potential Datasets
- HALALAN 2016 Dataset c/o Bong
- Mirror of Data Gov Election Data https://github.com/rukku/data.gov.ph-datasets  
- Geospatial Environmental and Socioeconomic https://www.kaggle.com/cathetorres/geospatial-environmental-and-socioeconomic-data
- Relevant indicators from the World Bank Open Data Repository
- MMUTIS and MMUCEP Dataset https://openjicareport.jica.go.jp/pdf/12247664.pdf  (socioeconomic and land use data)
- A sample or web scraped datasets of news articles or social media reactions for sentiment analysis segment

#### Potential Models
- Geospatial Clustering Methods (for evaluation) https://towardsdatascience.com/geospatial-clustering-kinds-and-uses-9aef7601f386 
- KMeans or Hierarchical
- Potential Ensemble/Combo if Time Permits


### Marketing: Attribution and Funnel Analysis

#### Description
We intend to simulate a multi-conversion event in a startup or e-commerce dataset. Instead of using first click or last click attribution, we will use a suitable model such as a scientific attribution model that will allow us to predict a prospect's ability to "convert" based on website behavior. This model will generate recommendations on how to spend marketing budget and we are trying to find something that can potentially be tech stack agnostic or usable for various businesses in startups, midlevel or enterprise scale. We will simulate 200 conversion events first and then train the model to predict new prospect behavior if they have a higher probability of becoming a customer. 

#### Potential Datasets
- Education Related product dataset https://www.kaggle.com/amritachatterjee09/lead-scoring-dataset?select=Lead+Scoring.cs https://www.kaggle.com/lakshmikalyan/lead-scoring-x-online-education
- Google Analytics 360 sample dataset from BigQuery https://www.kaggle.com/bigquery/google-analytics-sample https://www.blog.google/products/marketingplatform/analytics/introducing-google-analytics-sample
- Exported Google Analytics Data https://www.kaggle.com/satian/exported-google-analytics-data   
- Instacart Transaction dataset https://www.kaggle.com/c/instacart-market-basket-analysis/data 
- Banking Lead Conversion Data: https://www.kaggle.com/arashnic/banking-loan-prediction 
- Sales Pipeline Conversion for a Startup dataset https://www.kaggle.com/gauravduttakiit/sales-pipeline-conversion-at-a-saas-startup
- Advertising Campaign Analytics Data https://www.kaggle.com/avinashlalith/merkle-sokrati-advertising-campaign
- Criteo Uplift Modeling https://www.kaggle.com/arashnic/uplift-modeling 

#### Potential Models 
- Markov Chain Model (https://www.linkedin.com/pulse/marketing-channel-attribution-modelling-markov-chains-morten-hegewald)
- Scientific Attribution Model (https://visual.ly/community/Infographics/business/scientific-attribution-modeling-increase-sales-20)
- Time Series Forecasting Models 
- Cohort Analysis
- Logistic Regression Model
- Potential Ensemble/Combo if Time Permits

### Transport: Identifying Ideal Ratio of Transport Modes in High Traffic Area/s in NCR

#### Description
Depending on the available historical data, we plan to help detect the ideal ratio of transport modes for passengers at any given time. We will take into account times of day and volume of transporting customers and the methods that they travel along selected segments and create a predictive algorithm that will allow the detection of the optimal ratio of public transport modes. 

This is just a preliminary brainstorm on the industry. We are also open to another transport related modeling problem if there are better problems to solve with available data. 

#### Potential Datasets
- MMUTIS and MMUCEP Dataset https://openjicareport.jica.go.jp/pdf/12247664.pdf
- Transport Government Datasets if available and as listed on this publication: https://psa.gov.ph/sites/default/files/7.5.1%20Current%20State%20of%20Transportation%20Data%20and%20Statistics%20in%20the%20Philippines%20and%20Opportunities%20for%20Improvement%20Towards%20Usability%20_0.pdf 
- Other datasets from NCTS that we can get our hands on
- Philippine population data on areas of interest for the analysis
- Waze dataset
- Any transport dataset that will allow us to map out coronavirus impact, if available

#### Potential Models
- Potential Ensemble/Combo if Time Permits
- Logistic Regression Model or LDA
