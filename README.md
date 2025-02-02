# README: K-Means Clustering for Customer Segmentation

## Project Overview
This project implements **K-Means Clustering** to segment customers based on their purchasing behavior. The dataset contains customer attributes, such as annual income and spending score, which help identify different customer groups.

## Dataset
- **Dataset Name**: `Mall_Customers.csv`
- **Source**: [Kaggle Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features Used**:
  - `Annual Income (k$)`: Customer’s yearly income in thousand dollars.
  - `Spending Score (1-100)`: Customer spending behavior rating.

## Installation & Setup
### Prerequisites
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
### Steps to Execute in Google Colab:
1. **Download the dataset** from Kaggle and upload `Mall_Customers.csv` to Google Colab.
2. **Run the Python script** `kmeans_clustering.py`.
3. The script will:
   - Load and preprocess the dataset
   - Use **Elbow Method** to determine the optimal number of clusters
   - Apply **K-Means Clustering** to segment customers
   - Visualize the customer groups with a scatter plot
   - Evaluate clustering performance using the **Silhouette Score**

## Model Evaluation
- **Elbow Method**: Helps determine the best number of clusters by analyzing WCSS (Within-Cluster Sum of Squares).
- **Silhouette Score**: Measures the clustering efficiency (higher is better).

## Output
- **Graph**: A scatter plot displaying different customer segments.
- **Silhouette Score**: A numerical metric evaluating clustering quality.

## Troubleshooting
- If you get a `FileNotFoundError`, ensure the correct dataset path is used.
- If clustering does not look clear, try normalizing the dataset.
- Experiment with different cluster numbers to refine segmentation.

## Author
This project was developed as part of **Prodigy Infotech Internship Task 2**.

## License
This project is open-source and free for educational use.

