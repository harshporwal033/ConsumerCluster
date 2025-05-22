<table>
  <tr>
    <td><img src="https://github.com/harshjuly12/Customer-Segmentation-Using-KMeans/assets/112745312/031eec24-9af7-4a8e-8519-168965eacfea" width="80" style="margin-right: 10;"></td>
    <td><h1 style="margin: 0;">ConsumerCluster</h1></td>
  </tr>
</table>

## Introduction

This project uses the K-Means clustering algorithm to segment customers based on their buying habits. It’s a practical example showing how businesses can group their customers to tailor marketing efforts and improve engagement.

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

ConsumerClustering is a hands-on project that clusters customers with similar behavior patterns using K-Means. This helps businesses identify and target different customer groups effectively.

## Dataset

The dataset is from [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) and includes:

- `CustomerID`: Unique ID for each customer
- `Gender`: Customer gender
- `Age`: Age of the customer
- `Annual Income (k$)`: Income in thousands of dollars
- `Spending Score (1-100)`: A score assigned by the store based on spending behavior

## Project Structure

```

ConsumerClustering/
├── ConsumerClustering.ipynb      # Jupyter notebook with the full analysis
├── Mall\_Customers.csv            # Dataset file
├── README.md                    # Project documentation

````

## Requirements

You’ll need the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn
- plotly
- scikit-learn

## Installation

1. Clone the repo:

```bash
git clone https://github.com/harshporwal033/ConsumerCluster.git
cd ConsumerCluster
````

2. Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn
```

## Usage

Start the Jupyter notebook and follow the steps:

```bash
jupyter notebook ConsumerClustering.ipynb
```

Explore the data, preprocess it, run K-Means clustering, and visualize the results.

## Analysis and Results

The notebook covers:

* Data exploration and visualization
* Feature scaling and preprocessing
* Choosing the right number of clusters with the Elbow method
* Visualizing clusters in 2D and 3D
* Insights into customer segments for targeted marketing

## Contributing

Feel free to open issues or pull requests. Suggestions and contributions are always welcome!

---

Built with ❤️ by **Harsh Porwal**

