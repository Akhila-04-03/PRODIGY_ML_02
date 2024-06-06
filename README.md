# PRODIGY_ML_02
 # Introduction
 Customer Segmentation using K-Means Clustering.
 This project aims to segment customers into different groups based on their shopping trends.

# Dataset
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
The dataset used in this project is the `Mall_Customers.csv` which contains information about mall customers such as their age, annual income, and spending score.

# Overview
#The project begins with data preprocessing where missing data is handled by replacing missing values with the mean of the respective column. The categorical attribute ‘Gender’ is converted to a numerical attribute for further processing.
#spliting of data into training and testing set.
#k-means clustering to training data and finding optimal number of clusters using Gap statistic method.
![image](https://github.com/Akhila-04-03/PRODIGY_ML_02/assets/159133840/4a5b4cc5-a4a1-4485-a7bc-28db8c88a769)

#creating a K-means model using test data with optimal number of clusters determined from training data.

# Conclusion
![image](https://github.com/Akhila-04-03/PRODIGY_ML_02/assets/159133840/1bf02186-cb0a-4c2a-9b8a-7014899baf82)

-Distinct Segments:The eight clusters represent distinct customer segments, each with unique characteristics.
--From the cluster plot it can be identified a general idea of what these characteristics might be in a retail context:

1. Cluster 1: Customers with high annual income and high spending scores. These are likely to be premium customers who shop frequently and spend a lot. They could be targeted with new product lines and loyalty programs.
2. Cluster 2: Customers with high annual income but low spending scores. These customers have the potential to be converted into cluster 1 with the right strategies, such as personalized marketing.
3. Cluster 3: Customers with moderate annual income and moderate spending scores. These are the average customers who can be targeted with seasonal offers and promotions.
4. Cluster 4: Customers with low annual income but high spending scores. They're likely to be highly price-sensitive and may respond well to discounts and sales.
5. Cluster 5: Customers with low annual income and low spending scores. They might be infrequent shoppers and could require different engagement strategies to enhance their shopping frequency and volume.
6. Cluster 6: Customers with varying annual incomes but consistently high spending scores. This segment might contain impulsive buyers who are less concerned about price.
7. Cluster 7: Customers with varying annual incomes but consistently low spending scores. Strategies for this group could include a mix of discounts, loyalty programs, and personalized marketing.
8. Cluster 8: Customers with medium annual income and varying spending scores. This segment might contain regular customers with diverse shopping behaviors.
   
-Targeted Strategies: The clear separation of clusters suggests that targeted marketing strategies could be developed for each segment to address their specific needs and preferences.

-Potential Overlaps: While the clusters are distinct, any overlaps could indicate customers with similar behaviors across different segments, which could be an opportunity for cross-promotion.

# Contact
For any questions, comments, or feedback, You can contact me via given email.
• Email: akhilaraveendranpm@gmail.com
