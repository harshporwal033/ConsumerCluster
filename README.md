<table>
  <tr>
    <td><img src="https://github.com/harshjuly12/Customer-Segmentation-Using-KMeans/assets/112745312/031eec24-9af7-4a8e-8519-168965eacfea" width="80" style="margin-right: 10;"></td>
    <td><h1 style="margin: 0;">Customer Segmentation Using K-Means</h1></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://github.com/harshjuly12/Customer-Segmentation-Using-KMeans/assets/112745312/031eec24-9af7-4a8e-8519-168965eacfea" width="80" style="margin-right: 10;"></td>
    <td><h1 style="margin: 0;">Consumer Clustering</h1></td>
  </tr>
</table>

---

**Consumer Clustering** is a machine learning project that segments retail customers into distinct groups based on their spending behavior using the K-Means clustering algorithm. This segmentation can help businesses understand customer personas and optimize marketing strategies.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Requirements](#requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Analysis and Results](#analysis-and-results)
8. [Contributing](#contributing)
9. [Built By](#built-by)

## Project Overview

**ConsumerClustering** is designed to demonstrate how customer segmentation can be achieved using unsupervised learning. Using the K-means clustering algorithm, customers of a retail store are grouped based on key behavioral features such as income and spending score.

## Dataset

The dataset used for this project is publicly available on [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). It includes:

* `CustomerID`: Unique identifier for each customer
* `Gender`: Gender of the customer
* `Age`: Age of the customer
* `Annual Income (k$)`: Annual income in thousands of dollars
* `Spending Score (1-100)`: Store-assigned score based on spending behavior

## Project Structure

```
ConsumerClustering/
├── CustomerSegmentationUsingKMeans.ipynb   # Full notebook with EDA and clustering
├── Mall_Customers.csv                      # Input dataset
└── README.md                               # Project documentation
```

## Requirements

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/harshporwal033/ConsumerClustering.git
   cd ConsumerClustering
   ```

2. Install the dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn plotly scikit-learn
   ```

## Usage

To run the notebook:

```bash
jupyter notebook CustomerSegmentationUsingKMeans.ipynb
```

## Analysis and Results

The notebook walks through:

1. **Library Imports** – Bringing in all necessary packages
2. **Data Exploration** – Understanding data distribution, trends
3. **Preprocessing** – Feature scaling for accurate clustering
4. **Modeling** – Applying K-Means and determining optimal K
5. **Visualization** – Plotting clusters with Seaborn & Matplotlib

## Contributing

Feel free to fork this repository and make your own improvements. Contributions that enhance performance, visuals, or interpretation are welcome!

## Built By

**Harsh Porwal**

[GitHub Repo Link](https://github.com/harshporwal033/ConsumerClustering)




