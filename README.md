# K-Means Clustering on Environmental Factors

This project applies K-Means clustering to group countries or regions based on environmental indicators such as CO2 emissions, population, GDP, and waste production. The resulting clusters reveal patterns that support sustainability planning and decision-making.

---

## Problem Statement
Environmental performance varies widely across regions. Identifying similar groups manually is difficult and may overlook hidden relationships. Clustering helps detect patterns that guide smarter environmental policies and resource allocation.

---

## Dataset
**File:** environmental factors.csv

Example attributes:
- CO2 emissions  
- Waste production  
- Population  
- GDP

---

## Approach
1. Load and clean dataset  
2. Scale features using StandardScaler  
3. Apply K-Means clustering  
4. Visualize clusters  
5. Interpret environmental patterns

---

## Tools & Libraries
- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn

---

## Outputs
- Cluster labels added to dataset
- 2D scatter visualizations
- Insights into resource use and pollution profiles
- Identification of high and low-impact regions

---

## Insights & Use Cases
- Discover climate-impacting regions
- Compare countries with shared challenges
- Support government sustainability decisions
- Prioritize environmental investments
- Inform global policy collaboration

---

## Future Enhancements
- Test silhouette and elbow methods for better k
- Compare with DBSCAN and Hierarchical Clustering
- Add renewable energy and water usage features
- Create an interactive dashboard (Streamlit)
- Deploy with Flask/FastAPI

---

## File Included
`environmental-factors-kmeans.ipynb`

---

## Conclusion
Unsupervised learning helps uncover environmental similarities that would otherwise remain hidden. K-Means clustering reveals meaningful patterns in pollution and resource usage, guiding more informed environmental planning and sustainability action.

---

