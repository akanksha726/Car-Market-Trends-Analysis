# Car-Market-Trends-Analysis
Car Market Trends Analysis with Car Dekho Data.


Running the Notebook
Clone this repository:
git clone https://github.com/akanksha726/Car-Market-Trends-Analysis.git
Navigate to the cloned directory:
cd Car-Market-Trends-Analysis
Open the Jupyter Notebook:
jupyter notebook "Car Market Trends Analysis with Car Dekho Data.ipynb"
Analysis Steps Performed in the Notebook
The notebook covers the following key analysis steps:

Data Loading and Initial Inspection: The Car Market Trends Analysis with Car Dekho Data.csv dataset is loaded into a pandas DataFrame. Basic checks like df.shape, df.info(), df.describe(), df.head(), df.tail(), and df.isnull().sum() are performed to understand the data structure, summary statistics, and identify missing values.

Categorical Feature Visualization: Count plots are generated for categorical features such as Fuel_Type, Seller_Type, Transmission, and Owner to visualize their distributions.

Outlier Detection: Cars with selling prices in the top 1% are identified and displayed to understand potential outliers.

Relationship Analysis: The average selling price is grouped by the number of owners and visualized using a bar plot.

Pair Plot: A pair plot of the entire DataFrame is generated to visualize relationships and distributions among all numerical variables.

Car Name and Brand Analysis: Unique car names and their counts are extracted. An attempt was made to create a 'brand' column, but the current implementation in the notebook extracts an empty string for all brands, indicating a need for refinement in this step.

Relational Plot: A relational plot showing Selling_Price vs. Kms_Driven is generated.

Pie Charts for Distributions: Pie charts are used to show the percentage distribution of Transmission, Fuel_Type, and Owner types.



Thank you for your time and attention. We hope these insights provide a valuable understanding of the car market trends.

