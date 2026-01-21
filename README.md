### Introduction:
The world developement measurements aim to monitor and enhance countris' progress toward inclusive, equitable growth.
The world developement is multidimensional concept, this project is based on 3 dimensions: Economic, Health and Population survey.

### Dataset Overview:
  * The world developement indicators (e.g. GDP, life expectancy, population details)
  * Number of countries: 208
  * Number of features: 25
  * Preprocessing steps:
     * Remove special characters
     * Handling outliers
     * Handling missing values
     * Label Encoding
     * Standardization
     * Dimensinality Reduction
     * Regularization

### Methodology:
  * Clustering Algorithm(s):
    * KMeans
    * DBSCAN
    * Agglomerative
    * Gaussian Mixture Model
    * Spectral
    * MeanShift
  * Evaluation Metrics:
    * Silhouette Score
    * Davies–Bouldin index
  * Tracking tool:
    * MLFlow
---------------------------------------------------------------------------------------------------------------------------------------------
### Economic Survey:
Reflect a country’s financial health and productivity.
  * Common indicators:
    * Business Tax Rate
    * Ease of Business
    * GDP
    * Ease of Business
    * Population 15-64
    

<img width="1777" height="905" alt="ECO" src="https://github.com/user-attachments/assets/33f14a86-0f82-4dc3-acad-1a049666e958" />


  * <b>Finalised model</b>
    * Spectral (n_clusters:2; affinity:rbf)
    


<img width="600" height="450" alt="ECO_spectral_2_rbf" src="https://github.com/user-attachments/assets/8af6495b-fc92-46a7-9f5e-80cc7eca7221" />

---------------------------------------------------------------------------------------------------------------------------------------------


### Health Survey:
Capture the well-being and longevity of populations.
  * Common indicators:
    * Birth Rate
    * Health Exp % GDP
    * Health Exp/Capita
    * Life Expectancy 
    * Population

<img width="1826" height="902" alt="HEALTH" src="https://github.com/user-attachments/assets/9a132531-d3f5-43bf-abcd-9ebb2fadfaf5" />


  * **Finalised model**
    * Agglomerative (n_clusters:2)
    

<img width="600" height="450" alt="HEALTH_agglo_2" src="https://github.com/user-attachments/assets/38bcfef4-0a7d-468b-ab2d-4c164ed1c915" />


---------------------------------------------------------------------------------------------------------------------------------------------

### Population Survey:
Describe demographic structure and growth dynamics.
  * Common indicators:
    * Birth Rate
    * Life Expectancy
    * Population Agewise
    * Population Total
    * Population Urban
    * Tourism Inbound/Outbound

<img width="1786" height="928" alt="POPULATION" src="https://github.com/user-attachments/assets/c8c66e8d-8592-4eb8-aa78-027244a9f36c" />

  * **Finalised model**
    * DBSCAN (eps:3; min_smaples:13)

<img width="600" height="450" alt="POP_dbscan_3_13" src="https://github.com/user-attachments/assets/08e46908-4a1f-4344-b0ea-dcbe6081201f" />



---------------------------------------------------------------------------------------------------------------------------------------------

### Deployment:



<img width="1523" height="956" alt="Streamlit" src="https://github.com/user-attachments/assets/8319d54b-64e6-45c0-93e1-3af7e984460f" />









