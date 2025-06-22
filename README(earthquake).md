#  Earthquake Anomaly Detection using DBSCAN

##  Project Description
This project demonstrates how to use the **DBSCAN clustering algorithm** to detect anomalies in earthquake data. The primary objective is to identify unusual seismic events that deviate from normal patterns based on spatial features like **latitude, longitude**, and **magnitude**.

**DBSCAN** (Density-Based Spatial Clustering of Applications with Noise) is well-suited for this task because it can find clusters of arbitrary shape and directly label outliers — making it ideal for unsupervised anomaly detection.

## Key Features
- Unsupervised anomaly detection using DBSCAN
- Earthquake data clustering based on geospatial features
- Identification of noise points as seismic anomalies
- Visualizations of clusters and anomalies
- Full step-by-step analysis in a single notebook

## Project Structure
earthquake-anomaly-dbscan/
├── Earthquake anomaly using DBSCAN.ipynb # Jupyter Notebook with all code and plots
├── README.md # Project overview (this file)

## Technologies Used
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

##  Dataset Info
This project uses an earthquake dataset that includes:
- **Latitude**
- **Longitude**
- **Magnitude**
- **Depth**

##  How to Run

1. **Clone the repository**
```bash
git clone https://github.com/your-username/earthquake-anomaly-dbscan.git
2. Navigate to the project folder

cd earthquake-anomaly-dbscan
3. Run the notebook


jupyter notebook "Earthquake anomaly using DBSCAN.ipynb"

4. Explore!

Follow along cell by cell to see data loading, preprocessing, DBSCAN clustering, and result visualization

## Author
Sreya Bhattacharya
https://github.com/SreyaRaiGit
https://www.linkedin.com/in/sreyabhattacharya19/

##  License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and distribute this project with proper attribution.
