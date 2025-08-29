# SCT_DS_01
Visualized categorical feature distributions from the Mushroom dataset using bar charts in Matplotlib and Seaborn. Features include odor, gill size, habitat, and cap color. This helps understand data distribution patterns, useful for preprocessing and classification tasks.
Dataset: Mushroom Classification (Kaggle / UCI ML Repository)
Type: All features are categorical

📈 Visualizations

The project includes bar charts for categorical attributes in the dataset:

1. Bar Charts

Displays the frequency distribution of each feature (e.g., cap-shape, cap-color, odor, gill-size, stalk-shape, etc.).

Helpful for spotting which categories dominate and how balanced each feature is.

2. Grid Layout

All features are arranged in a subplot grid for side-by-side comparison.

3. (Optional Extension)

Add comparative plots between features and the target (edible vs. poisonous).

Heatmaps or pairplots can be used for deeper insights.

🛠 Tools & Libraries

Python 3.x

pandas – for data handling

matplotlib – for plotting categorical distributions

📌 How to Run

1. Make sure you have Python installed.

2. Install dependencies:

pip install pandas matplotlib

3. Run the script:

python mushroom_viz.py
