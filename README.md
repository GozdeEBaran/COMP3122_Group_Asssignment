# K-Means Clustering Project - COMP3122

## Project Overview

This project presents a comprehensive explanation and demonstration of the K-Means clustering algorithm, applied to child learning behavior analysis.

## Team Members

1. **Ibo** - Introduction + Theory of K-Means
2. **Gozde** - Math, Distance, Advantages/Disadvantages
3. **Felix** - Implementation in Python + Choosing K
4. **Daniil** - Data Preprocessing + Feature Engineering
5. **Baris** - Results, Interpretation, Real-world Application

## Project Structure

```
comp3122-groupAssignment/
├── README.md                          # This filE
│
├── code/                              # All code files
│   ├── requirements.txt               # Python dependencies
│   ├── kmeans_basic.ipynb            # Basic K-Means implementation (Member 3)
│   ├── kmeans_dataset.ipynb          # Applied to dataset (Member 4)
│   └── visualize_results.ipynb       # Visualization helpers

```

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Required libraries (install via `pip install -r code/requirements.txt`)

### Installation

1. Navigate to the project directory:

```bash
cd comp3122-groupAssignment
```

2. Install dependencies:

```bash
pip install -r code/requirements.txt
```

### Running the Code

#### Basic K-Means Implementation (Member 3)

1. Open `code/kmeans_basic.ipynb` in Jupyter Notebook
2. Run all cells sequentially
3. View the results and visualizations in the notebook

This demonstrates the fundamental K-Means algorithm with sample data.

#### Applied to Dataset (Member 4)

1. Open `code/kmeans_dataset.ipynb` in Jupyter Notebook
2. Run all cells sequentially
3. View the analysis results and visualizations in the notebook

This applies K-Means to the child learning behavior dataset and generates visualizations.

#### Additional Visualizations

1. Open `code/visualize_results.ipynb` in Jupyter Notebook
2. Ensure `kmeans_dataset.ipynb` has been run first (creates clustered dataset)
3. Run all cells to create detailed comparison plots and heatmaps

## Dataset

The `child_learning_behavior.csv` file contains 300 records with the following features:

- `age`: Child's age (6-14)
- `daily_screen_time_hours`: Daily screen time in hours
- `homework_completion_rate`: Percentage of homework completed
- `attention_score`: Attention/engagement score (0-100)
- `sleep_hours`: Average hours of sleep per night
- `math_score`: Math test score (0-100)
- `reading_score`: Reading test score (0-100)
- `parental_involvement_level`: Level of parental involvement (1-5)

## Presentation Requirements

### Slides Structure (17 total)

- 1 Introduction slide (topic name + team names - names NOT presented)
- 15 Content slides (3 per member × 5 members)
- 1 Conclusion slide (minimal text - NOT presented)

### Required Elements

- ✅ At least 1-2 diagrams (hand-drawn or digital)
- ✅ At least 1-3 running code blocks
- ✅ Each member presents 3 slides

### Presentation Order

1. Ibo - Introduction + Theory (3 slides)
2. Gozde - Math, Distance, Advantages/Disadvantages (3 slides)
3. Felix - Implementation in Python + Choosing K (3 slides)
4. Daniil - Data Preprocessing + Feature Engineering (3 slides)
5. Baris - Results, Interpretation, Real-world Application (3 slides)

### kmeans_basic.ipynb

- Step-by-step K-Means implementation
- Clear function structure with markdown explanations
- Educational comments and explanations
- Interactive visualization of results
- Perfect for presentations and demonstrations

### kmeans_dataset.ipynb

- Data loading and exploration
- Feature selection and normalization
- Elbow method for optimal K
- Complete K-Means application
- Cluster analysis and interpretation
- Multiple visualizations embedded in notebook

### visualize_results.ipynb

- Feature comparison plots
- Cluster heatmaps
- Scatter plot matrices
- Box plots by cluster
- All visualizations with explanations

**Good luck with OUR presentation!**
