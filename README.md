KMeans Clustering with Python

This repository contains an implementation of KMeans clustering using Python and the `scikit-learn` library. The code generates synthetic data using `make_blobs`, then applies KMeans clustering to categorize the data into distinct clusters.

## Project Structure

- **main.py**: The script containing the implementation of KMeans clustering.
- **README.md**: Documentation for the project (this file).

## Getting Started

### Prerequisites

Make sure you have Python installed along with the required libraries:

- Python 3.x
- `numpy`
- `matplotlib`
- `scikit-learn`

You can install the necessary libraries using:

```bash
pip install numpy matplotlib scikit-learn
```

### Running the Code

1. Clone the repository:

```bash
git clone https://github.com/your-username/kmeans-clustering.git
```

2. Navigate to the project directory:

```bash
cd kmeans-clustering
```

3. Run the script:

```bash
python main.py
```

### Expected Output

1. **Sample Data Plot**: The initial plot shows randomly generated data points with four distinct clusters.
2. **Clustered Data Plot**: The output plot displays the clustered data, where each point is colored according to its assigned cluster, along with the cluster centroids marked in red.

## Code Overview

1. **Data Generation**: The synthetic data is generated using `make_blobs`, which creates multiple Gaussian blobs with specified centers and standard deviations.
2. **KMeans Initialization and Fitting**: The `KMeans` model is initialized with 4 clusters and is fitted to the generated data.
3. **Cluster Visualization**: The clustered data is visualized using `matplotlib`, with each point colored according to its cluster label. The centroids of the clusters are highlighted in red.

## Example Plots

### Sample Data
![Sample Data](./images/sample_data.png)

### Clustered Data
![Clustered Data](./images/clustered_data.png)

## Notes

- The code includes warnings related to default values in scikit-learn, which you can resolve by setting the `n_init` parameter explicitly or adjusting your environment variables.
- The project demonstrates the basics of clustering using KMeans but can be extended with more advanced techniques and analyses.

## License

This project is licensed under the MIT License.

