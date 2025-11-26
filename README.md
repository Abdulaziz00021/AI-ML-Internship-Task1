#  Iris Dataset Exploration – AI/ML Internship Task

##  Task Objective
The objective of this task was to explore a simple dataset and perform basic data analysis and visualization.  
This includes loading the dataset, inspecting its structure, understanding feature distributions, and visualizing relationships between variables using **matplotlib** and **seaborn**.  
The task helps build foundational skills in data handling, EDA (Exploratory Data Analysis), and visualization—core components of any AI/ML workflow.

---

##  Dataset Used
**Iris Dataset** (Available in seaborn library)

The dataset contains:
- **150 samples**
- **3 species** of Iris flower  
  - *setosa*  
  - *versicolor*  
  - *virginica*
- **4 numeric features**:
  - sepal_length  
  - sepal_width  
  - petal_length  
  - petal_width  

This dataset is widely used for introductory machine learning and data visualization tasks.

---

##  Methods & Models Applied
Since this task focuses on data understanding rather than machine learning modeling, the following methods were applied:

###  Data Loading & Inspection
- Loaded dataset using **pandas** and **seaborn**
- Printed dataset shape and column names
- Displayed first few rows using `.head()`
- Used `.info()` for datatype overview
- Used `.describe()` for summary statistics

###  Data Visualization
All visualizations were created using **matplotlib** and **seaborn**:

- **Scatter Plot**  
  - Showed relationship between *sepal length* and *sepal width* across species.
- **Histograms**  
  - Displayed distribution of each numeric feature.
- **Box Plots**  
  - Identified variations and potential outliers in the dataset.

---

##  Key Results & Findings

###  1. Feature Relationships
- The **scatter plot** revealed that *setosa* is clearly separable from other species based on sepal dimensions.
- *Versicolor* and *Virginica* show some overlap, but still exhibit noticeable patterns.

###  2. Feature Distributions
- **Histograms** show:
  - *Petal length* and *petal width* have clear separation between species.
  - Sepal measurements are more overlapping compared to petal measurements.

###  3. Outliers and Variability
- **Box plots** indicate:
  - Some mild variations across features, especially in sepal width.
  - Petal features have more consistent separation between species.

---

##  Conclusion
This task demonstrated how basic Exploratory Data Analysis (EDA) helps in:
- Understanding dataset structure  
- Identifying useful patterns  
- Recognizing potential feature importance  
- Preparing data for future ML modeling  

