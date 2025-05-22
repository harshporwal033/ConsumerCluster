
<table>
  <tr>
    <td><img src="https://github.com/harshjuly12/Customer-Segmentation-Using-KMeans/assets/112745312/031eec24-9af7-4a8e-8519-168965eacfea" width="80" style="margin-right: 10;"></td>
    <td><h1 style="margin: 0;">Consumer Clustering with K-Means</h1></td>
  </tr>
</table>

## Brief Introduction

ConsumerClustering is a practical machine learning project focused on segmenting customers into meaningful groups based on their purchasing behavior. Using the K-Means clustering algorithm, this project helps uncover patterns in customer data that businesses can leverage for targeted marketing and improving customer engagement.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Requirements](#requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Analysis and Results](#analysis-and-results)
8. [Contributing](#contributing)

## Project Overview
**ConsumerClustering** demonstrates customer segmentation with K-Means clustering. The aim is to identify clusters of customers exhibiting similar behavior to enable personalized marketing strategies.

## Dataset
The dataset is from [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python), containing these columns:
- `CustomerID`: Unique customer identifier
- `Gender`: Customer gender
- `Age`: Customer age
- `Annual Income (k$)`: Annual income in thousands of dollars
- `Spending Score (1-100)`: Store-assigned score based on spending habits

## Project Structure
```

ConsumerClustering/
├── ConsumerClustering.ipynb      # Jupyter notebook with full analysis and K-Means implementation
├── Mall\_Customers.csv            # Dataset file
├── README.md                     # This documentation

````

## Requirements
Python libraries needed:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- scikit-learn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/harshporwal033/ConsumerCluster.git
   cd ConsumerCluster
````

2. Install dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn plotly scikit-learn
   ```

## Usage

Run the Jupyter notebook:

```bash
jupyter notebook ConsumerClustering.ipynb
```

Follow the notebook steps to explore, preprocess, cluster, and visualize customer segments.

## Analysis and Results

The notebook walks through:

1. Data exploration and visualization of key customer attributes
2. Data preprocessing including feature scaling
3. Applying K-Means clustering and selecting cluster count using the Elbow method
4. Visualizing clusters in 2D/3D plots for interpretation
5. Deriving actionable insights about different customer segments

## Contributing

Built with ❤️ by **Harsh Porwal**

