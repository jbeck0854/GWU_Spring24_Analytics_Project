# GWU_Spring24_Analytics_Project
Semester Long Project completed at GWU in Spring 2024 in Programming Analytics course. First Data Analytics and Machine Learning related project using Superstore dataset from Kaggle.

## Basic Information
- **Programmmer and Model Developer**: Jonathan, jonathan.beck@gwmail.gwu.edu
- **Date**: April, 2024
- **Code and Model version**: 0.1
- **License**: MIT
- **Link to Notebooks**: https://drive.google.com/drive/folders/1LJqxoJ7WkJ7wE8mGqGBW6uJik5BfFafd?usp=drive_link

 ## Intended Use & Purpose
 - **Primary Purpose**: This project served as an introduction to Data Analytics and Machine Learning. Completion of the project tasks aggregated a variety of analytical coding techniques that were learned during the Fall 2024 semester and on my own time. Deliverables, including all notebook scripts and the final portfolio of insights, were completed sequentially in increments. The objective was to find a business-oriented dataset from Kaggle, github, or relevant site, import it into a coding environment, gain experience in using data analysis and machine learning packages in Python or R, and leverage these tools to provide an ROI to company "shareholders".
 - **Intended users**: Professor Hulseman and classmates.
 - **Out-of-scope use cases**: Any use beyond GWU DNSC 4211, as an educational piece, is out-of-scope.

## Data
- **Source of data**: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final
- **How data was divided into training and validation data**: The training data was divided into training and validation sets using the *train_test_split* function from the *model_selection* module of the *scikit-learn* library. The *test_size* parameter was set to 0.2 so that 20% of the 9994 rows in the csv would be set aside for validation and the remaining 80% of the data would be used for fitting the model. Furthermore, the *random_state* parameter was set to 0 for reproducibility.
- **Number of rows in training and validation data**:
  - Training rows: 7995
  - Validation rows: 1999
- **Data Dictionary (as initially imported)**:
**Data Overview**: Dataset contains information related to Sales, Profits and other facts of a Superstore giant (Kaggle).
  
| Name       | Data Type       | Description       |**
|----------------|----------------|----------------|----------------|
| Row ID  | int  | Unique ID for each row.|
| Order ID  | object  | Unique Order ID for each customer. |
| Order Date  | object  | Order Date of the product. |
| Ship Date  | object | Shipping Date of the Product. |
| Ship Mode  | object  | Shipping Mode specified by the Customer. |
| Customer ID  | object  | Unique ID to identify each Customer.|
| Customer Name  | object | Name of the Customer. |
| Segment  | object  | The segment where the Customer belongs. |
| Country  | object | Country of residence of the Customer. |
| City  | object  | City of residence of the Customer.  |
| State | object | State of residence of the Customer. |
| Postal Code | int | Postal Code of every Customer. |
| Region | object | Region where the Customer belong. |
| Product ID | object | Unique ID of the Product. |
| Category | object | Category of the product ordered. |
| Sub-Category | object | Sub-Category of the product ordered. |
| Product Name | object | Name of the Product. |
| Sales | float | Sales of the Product. |
| Quantity | int | Quantity of the Product. |
| Discount | float | Discount provided. |
| Profit | float | Profit/Loss incured. |



