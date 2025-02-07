# Customer-Cluster
Power BI visualizations exploring its integration with Python

Cristiane Mecca Giacomazzi (Data Analyst)
This project was developed with Cross-industry standard process for data mining (CRISP-DM) methodology.

The following topics will be presented:
### 1. Business Understanding
### 2. Data Understanding
### 3. Ethical Statements
### 4. Data Preparation
### 5. Dictionary
### 6. Libraries used for this project
### 7. Project plan
### 8. Analysis  
### 9. EDA
### 10. Segmentation results
### 11. Metrics
### 12. Data visualization
### 13. Communication and Action
### 14. Diagram

----------
## 1. Business Understanding


* The business has a variety of customers and abundant data in your databases. The challenge for many businesses arises when it is time to leverage this data for strategic decisions. While manually identifying patterns and making conclusions is impossible, it is a complex and lengthy process.
* Machine learning-based customer segmentation enables analysts to categorize customer databases based on shared traits, which helps identify trends and create more focused marketing strategies and special offers, for instance. Traditionally, this segmentation is done using demographic characteristics such as gender, size, and location. 
* My objective in this project was to use **machine learning** to segment customers into different groups based on historical data and their characteristics, and to report the results to stakeholders using **Power BI visualizations** and **diagram method**, while also exploring its **integration with Python**.
* After segmentation, it becomes possible to understand the shared characteristics of customers, enabling companies to better address their needs and define business strategies more effectively.
* It was identifyed the **high-value customer groups** and provided strategic tailor **strategies**.
* This allows the marketing department to personalize strategies to enhance customer engagement in advertisements. Ultimately, businesses can maximize their impact and profitability.

## 2. Data Understanding

**Data Source:** This project used a dataset prepared for academic purposes called “data_clients” and available in this [link](https://drive.google.com/file/d/1qrIZ3nk6CWXUlUFFBCrhio_aMGNKZnBs/view), a structured dataset. 

**Tools**: Python, Power BI.

## 3. Ethical Statements

**Ethical issues**: This project complies with the TCPS 2. The dataset is in the public domain and the data is fictitious. 
**Conflict of interest**: no conflict of interest declared.

## 4. Data preparation - Preprocessing

There were 0.19% of the dataset missing data (specifically in “annual income”) and 1 duplicated observation (row number 10). Then, the missing data was replaced with the average annual income and delete the duplicated data. 
The dataset has different scales among features, then, it was necessary to standardize the data. 

## 5. Dictionary

<img width="802" alt="Screen Shot 2024-12-01 at 2 18 03 PM" src="https://github.com/user-attachments/assets/202472dc-a590-4d8b-a105-e9e8e3b16a81">

## 6. Libraries used in this project

Pandas

Numpy

Sklearn (Kmeans and StandardScaler)

Powerbiclient (QuickVisualize, get_dataset_config, Report)

Powerbiclient.authentication (DeviceCodeLoginAuthentication)

Google.colab (output)

output.enable_custom_widget_manager()

Matplotlib

## 7. Project plan

Using the Python programming language in Google Colab, the data was cleaned and preprocessed, applied the K-Means machine learning algorithm to generate different customer segments, and connected it to Power BI for data visualization. Then, it is accessible to stakeholders through Power BI Desktop.

## 8. Analysis

a. Exploratory Data Analysis (EDA)
The data from 500 customers was analyzed, revealing an average age of 45 years, an annual income of USD 81,500.00, and a Purchase Power Score of 48 points. Cluster “0” has the most customers (184), holding the highest average Purchase Power Score (66 points), while cluster “2” has the highest average annual income. The youngest customers belong to cluster “2,” with an average age of 30 years.

b. Segmentation results

<img width="811" alt="Screen Shot 2024-12-01 at 2 20 23 PM" src="https://github.com/user-attachments/assets/c4f79515-0446-43d1-b70d-bc8341f4dbd2">

## 9. Metrics - best number of clusters

The elbow method was used to choose the best k and calculate the Sum of Squared Errors (SSE). The k was defined in 3, and SSE result was 886.

## 10.Data visualization

After building the model, it was connected to Power BI using the “Powerbiclient” library in Google Colab with Python.
The dashboard can be visualized here [Dashboard](https://app.powerbi.com/links/IDFrEPiyWI?ctid=eb34f74a-58e7-4a8b-9e59-433e4c412757&pbi_source=linkShare)

<img width="641" alt="Screen Shot 2025-02-07 at 6 20 42 PM" src="https://github.com/user-attachments/assets/b3e4c684-8473-4098-b7e9-c295cacf1a4b" />


## 11. Communication and Action

After segmentation, it becomes possible to understand the shared characteristics of customers, enabling companies to better address their needs and define business strategies more effectively. Here, we can clearly see the differences in age among the groups. This allows the marketing department to personalize strategies to enhance customer engagement in advertisements. Ultimately, businesses can maximize their impact and profitability.

## 12. Diagram

 <img width="692" alt="Screen Shot 2024-12-01 at 2 22 28 PM" src="https://github.com/user-attachments/assets/fcf6613e-a7b5-4e05-a069-d8d857497d9c">

# References

IBM. (n.d.). _What is machine learning (ML)_?
[https://www.ibm.com/topics/machine-learning] 


Idiomatic.(n.d.). _How to use machine learning for customer segmentation_?
[https://idiomatic.com/] 












