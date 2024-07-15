# CODETECH TASK 1
<b>NAME </b>- ISHITA VERMA <br>
<b>COMPANY</b> - CODETECH IT SOLUTION<br>
<b>ID</b> - CT4DA4095<br>
<b>DOMAIN</b> - DATA ANALYTICS<br>
<b>DURATION</b> - 5 JULY TO 5 AUGUST<br>

<b> <u>OVERVIEW OF THE PROJECT</b> </u> <br>
 <b> PROJECT - CUSTOMER SEGMENTATION AND ANALYSIS</b><br>
 Objective <br>
 The objective of this project is to perform DATA ANALYSIS on a dataset containing customers annual income and their spending scores of a mall. This dataset helps to analyse the data and also help to analyse the details about the revenue attained by the customers spending values.Customer segmentation involves dividing a customer base into distinct groups with similar characteristics to better target marketing efforts and personalize customer experiences.<br>

**KEY ACTIVITIES** <br>
1. **Data Collection**: Gathering comprehensive data from various sources such as sales transactions, customer feedback, social media, surveys, and website analytics. <br>
2. **Data Cleaning and Preprocessing**: Ensuring the data is clean, accurate, and consistent. This involves handling missing values, removing duplicates, and correcting errors.<br>
3. **Identifying Segmentation Criteria**: Choosing the basis on which customers will be segmented. Common criteria include demographics, geographic location, psychographics, and behavioral data.<br>
4. **Applying Segmentation Techniques**: Common methods include:<br>
   - **Clustering Algorithms**: K-means, Hierarchical clustering, DBSCAN.<br>
   - **Classification Algorithms**: Decision Trees, Random Forest, Logistic Regression.<br>
   - **Market Basket Analysis**: Identifying associations between different products.<br>
5. **Validating Segments**: Ensuring the segments are distinct and meaningful. This involves checking the stability and consistency of the segments over time.<br>
6. **Profiling and Understanding Segments**: Analyzing and understanding the characteristics of each segment. <br>
7. **Targeting and Personalization**: Developing targeted marketing strategies and personalized customer experiences based on the segment profiles.<br> 
8. **Monitoring and Updating Segments**: Regularly reviewing and updating the segments to ensure they remain relevant. <br>
9. **Measuring Effectiveness**: Evaluating the impact of segmentation on business objectives such as customer satisfaction, retention, and revenue growth.<br>

**ENVIROMENTS AND TOOLS FOR THE PROJECT**<br>
Language: Python<br>
Libraries: Pandas, Numpy, Matplotlib, SciKit learn ,Seaborn<br>

 **TYPES OF SEGMENTAION FACTORS**<br>
1. **Demographics**- Age, Gender, Income, Location, Education, Ethnicity<br>
2. **Psychographic**- Interests, Lifestyle, Psychological Influences, Motivation, Priorities<br>
3. **Behavioural**- Purchasing Habits, Spending Habits, User Status, Brand Iteractions<br>
4. **Gegraphic**- ZIP Code, City, Country, Climate, Urban or Rural<br>

**K- MEANS ALGORITHM**<br>
It is an iterative algorithm that divides the unlabelled dataset into k different clusters in such a way that each dataset belongs to only one group that has similar properties.<br>
![k means](https://github.com/Ishita-verma20/CODETECH_TASK_1/assets/174854145/0be2399e-e062-4f77-9117-fbbd05131526)<br>
K-means is a popular clustering algorithm used in machine learning and data analysis to partition a dataset into K distinct, non-overlapping subsets or clusters.<br>
**Steps of the K-means Algorithm**<br>
**1.Initialization:**<br>
Choose the number of clusters, K. Initialize K cluster centroids. This can be done randomly or using specific initialization methods like K-means++.<br>
**2.Assignment Step:**<br>
Assign each data point to the nearest cluster centroid. The assignment is typically based on minimizing the Euclidean distance between the data point and the cluster centroid.<br>
**3.Update Step:**<br>
Recalculate the centroids of the clusters by computing the mean of all data points assigned to each cluster.<br>
**4.Convergence Check:**<br>
Repeat the assignment and update steps until the centroids no longer change significantly or a maximum number of iterations is reached.<br>

Kmeans algorithm can be used in two  ways to choose optimum k value:<br>
![WhatsApp Image 2024-07-10 at 14 51 49_59b41a23](https://github.com/Ishita-verma20/CODETECH_TASK_1/assets/174854145/000dc4e1-efdc-42c5-8aac-e2e158da2c90)

**Elbow method:**<br>
The Elbow Method is a heuristic used to determine the optimal number of clusters (K) in K-means clustering. It involves running K-means clustering on the dataset for a range of K values and then plotting the within-cluster sum of squares (WCSS) against the number of clusters. The point where the WCSS begins to diminish more slowly (forming an "elbow") is considered the optimal number of clusters.<br>
**Purpose based1:**<br>
The purpose-based approach to selecting the optimal number of clusters in K-means clustering involves choosing the number of clusters based on the specific goals and requirements of the analysis rather than relying solely on statistical or heuristic methods like the Elbow Method. This approach takes into consideration the context and objectives of the clustering task to determine the most meaningful number of clusters.<br>

**ADVANTAGES OF CUSTOMER SEGMENTATION**<br>
1. Price optimization<br>
 2. enhances competitiveness<br>
 3. Brand awareness<br>
 4. Acquisition and retegntion<br>
 5. Increases revenue and ROI<br>



