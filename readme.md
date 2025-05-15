# Vehicle Fuel Efficiency Analysis

This project is part of the ASC23 assignment focused on transport, specifically analyzing vehicle fuel efficiency and CO₂ emissions. The goal is to visualize and understand relationships between fuel economy, emissions, and vehicle characteristics using Python data visualization libraries.

##  Files Included

- `Plotting_Assignment.ipynb`: The main Jupyter Notebook containing code, visualizations, and interpretations.
- `fuel_econ.csv`: Dataset containing vehicle and fuel-related features.
- `heatmap.png`: A heatmap image visualizing correlations between numeric features.
- `histogram.png`: A histogram image showing the distribution of combined fuel economy.
- `README.md`: This documentation file.

##  Libraries Used

- `pandas`: For loading and manipulating the dataset.
- `matplotlib.pyplot`: For plotting visualizations like histograms.
- `seaborn`: For advanced visualizations like heatmaps.
- `numpy`: (if used) for numerical operations.

##  Project Objectives

- Load and explore the `fuel_econ.csv` dataset.
- Visualize the distribution of combined fuel economy using a histogram.
- Generate a heatmap showing correlations between numerical features (e.g., `comb`, `co2`, `feScore`).
- Interpret each visualization in the notebook for AI training and inference insights.

##  Key Visualizations

1. **Histogram**
   - Shows how combined fuel economy (MPG) is distributed across the dataset.
   - Helps identify fuel-efficient vs inefficient vehicle clusters.

2. **Heatmap**
   - Displays pairwise correlations between features like fuel economy, CO₂ emissions, and engine size.
   - Confirms expected relationships such as higher MPG = lower CO₂ emissions.

##  How to Run

1. Clone or download the repository.
2. Open `Plotting Assignment.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells sequentially to generate and interpret visualizations.
4. Ensure `fuel_econ.csv` is in the same directory.

##  Interpretation Summary

- Vehicles with better fuel economy emit less CO₂.
- Engine displacement and cylinder count are positively correlated with CO₂ emissions.
- Fuel economy metrics (city, highway, combined) are strongly correlated with each other.

##  Submission Notes

- Submit the `Plotting Assignment.ipynb`, histogram and heatmap `.png` files in a folder.
- Interpretations must be written in Markdown or Python comments within the notebook.

---

**Authors**: Denis Mitali 
            Patricia Mugabo 
**Assignment**: ASC23 Transport Track – Data Visualization  
