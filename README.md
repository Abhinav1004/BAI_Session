
# Cluster Analysis & Visualization Project

This repository contains Jupyter Notebooks for performing and visualizing clustering using KMeans on two datasets:

- **Mall_Customers.csv**: Customer segmentation using KMeans and visualization in 2D and 3D.
- **MNIST (Handwritten Digits)**: Clustering and visualization of digit images using KMeans.

## Contents
- `Cluster-visualization.ipynb`: KMeans clustering and visualization on Mall Customers dataset.
- `Kmeans_Clustering.ipynb`: KMeans clustering on the MNIST dataset with cluster center visualization.
- `Mall_Customers.csv`: Dataset for customer segmentation.
- `requirements.txt`: All required Python packages.

## Setup Instructions

1. **Clone the repository**
	```sh
	git clone <repo-url>
	cd BAI_Session
	```

2. **Create a virtual environment (recommended)**
	```sh
	python3 -m venv venv
	source venv/bin/activate
	```

3. **Install dependencies**
	```sh
	pip install -r requirements.txt
	```

4. **Start Jupyter Notebook**
	```sh
	jupyter notebook
	```
	Open the desired notebook (`Cluster-visualization.ipynb` or `Kmeans_Clustering.ipynb`) in your browser.

## Usage

- **Mall Customers Clustering**: Run all cells in `Cluster-visualization.ipynb` to perform KMeans clustering on the customer data and visualize clusters in 2D and 3D.
- **MNIST Clustering**: Run all cells in `Kmeans_Clustering.ipynb` to cluster handwritten digits and visualize cluster centers and closest instances.

## Notes
- Ensure you have a stable internet connection to download the MNIST dataset (used in `Kmeans_Clustering.ipynb`).
- All visualizations are interactive and require running the notebook cells.

## License
This project is for educational purposes.
