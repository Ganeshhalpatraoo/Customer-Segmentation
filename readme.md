# Customer Segmentation

This project focuses on segmenting customers based on their behavior, preferences, and purchasing patterns. Using unsupervised machine learning techniques, we analyze customer data to group them into distinct segments. The goal is to understand different customer profiles and develop personalized marketing strategies to enhance customer experience and increase sales.

## Project Overview

The analysis includes the following key areas:
- **Clustering of Customers**: Using clustering techniques to segment customers based on purchasing behavior.
- **Feature Engineering**: Creating meaningful features from raw customer data to improve segmentation.
- **Segmentation Model**: Implementation of clustering algorithms like K-means or DBSCAN for customer segmentation.
- **Insights**: Identifying key characteristics of each customer segment to inform business strategies.

## Libraries Used
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations and handling missing values.
- **Matplotlib**: For generating visualizations like scatter plots and histograms.
- **Seaborn**: For creating more advanced visualizations.
- **Scikit-learn**: For machine learning algorithms and clustering techniques (e.g., K-means, DBSCAN).
- **SciPy**: For additional statistical functions and metrics.

## Dataset Description

The dataset contains the following columns:
- **CustomerID**: Unique identifier for each customer.
- **Age**: Age of the customer.
- **AnnualIncome**: Annual income of the customer.
- **SpendingScore**: A score that indicates the customer’s spending behavior (from low to high).
- **Gender**: Gender of the customer.
- **PurchaseHistory**: Details of past transactions (if available).

## Key Findings

1. **Customer Segments**:
   - The dataset was successfully divided into distinct customer segments based on income and spending behavior.
   - Segments include high-income, low-spending customers, and low-income, high-spending customers, among others.

2. **Feature Importance**:
   - Features like **AnnualIncome** and **SpendingScore** were key in identifying customer segments, with other features like **Age** playing a secondary role.

3. **Targeting Strategies**:
   - Recommendations for targeted marketing campaigns based on the unique characteristics of each segment.
   - High-income, low-spending customers may benefit from loyalty programs, while low-income, high-spending customers may respond well to discount offers.

4. **Segmentation Model Performance**:
   - K-means clustering proved effective for segmenting customers, with optimal clusters identified using the elbow method.
   - Alternative algorithms such as DBSCAN were also tested for performance comparison.

## Visualizations

The project includes the following visualizations:
- **Elbow Plot**: To determine the optimal number of clusters for K-means.
- **Scatter Plots**: To visualize customer segments based on income and spending score.
- **Pair Plots**: To explore relationships between features like age, income, and spending score.
- **Cluster Distribution**: Bar chart showing the distribution of customers across different clusters.

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/customer-segmentation.git
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook or Python script to begin analysis:
    ```bash
    jupyter notebook customer_segmentation.ipynb
    ```

## Conclusion

This analysis helps businesses understand their customer base by segmenting them into distinct groups. The insights gained can be used to personalize marketing efforts, improve customer retention, and optimize resource allocation. Future improvements could include integrating additional customer data or refining segmentation models using more advanced algorithms.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
