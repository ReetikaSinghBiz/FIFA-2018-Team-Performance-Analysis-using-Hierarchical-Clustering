# FIFA 2018 Team Performance Analysis: Hierarchical Clustering and Strategic Recommendations

## Overview
This project analyzes FIFA 2018 team performance metrics using hierarchical clustering. Teams are categorized into performance groups, and actionable recommendations are generated based on their cluster.



## Workflow

### 1. Data Preprocessing
- **Data Selection**: Focused on key team performance metrics, such as `Goal Scored` and `Ball Possession %`.
- **Outlier Treatment**: Winsorization applied to mitigate the influence of extreme values.
- **Feature Selection**: Columns relevant to clustering were selected for analysis.

### 2. Hierarchical Clustering
- **Dendrogram**: Visualized hierarchical relationships between teams.
- **Agglomerative Clustering**: Teams clustered into three groups using Ward’s method with Euclidean distance.

### 3. Clustering Visualization
- Scatter plot highlighting the performance clusters:
  - `Low` performance
  - `Medium` performance
  - `High` performance

### 4. Strategic Recommendations
- Assigned tailored suggestions based on team clusters:
  - Low: Focus on defense and offensive strategies.
  - Medium: Balanced improvements to core strategies.
  - High: Fine-tune offensive tactics and improve stamina.



## Libraries Used
- **pandas**: For data manipulation.
- **numpy**: For numerical operations.
- **matplotlib**: For visualizing data and dendrograms.
- **seaborn**: For enhanced scatter plot visualizations.
- **scipy**: For hierarchical clustering.
- **scikit-learn**: For implementing agglomerative clustering.



## Key Outputs
1. **Clusters Identified**: 
   - `Low`: Teams needing defensive focus.
   - `Medium`: Teams requiring balanced strategies.
   - `High`: Teams ready to enhance offensive play.
2. **Dendrogram**: Illustrated hierarchical clustering process.
3. **Cluster Visualization**: Scatter plot displaying team groupings.
4. **Strategic Suggestions**: Recommendations for performance improvement based on cluster assignments.



## How to Run
1. Ensure the dataset `FIFA 2018 Statistics.csv` is in your working directory.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn
3. Run the script in a Python environment (e.g., Jupyter Notebook).
4. View the final output table, which includes team groupings and recommendations.



## Results
- Teams were segmented into three distinct groups (Low, Medium, High).
- Suggestions provided actionable insights tailored to each team’s performance metrics.
- The final table combines performance data, group assignments, and strategic recommendations.



## Author
Reetika Singh
