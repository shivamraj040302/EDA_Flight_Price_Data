**Flight Price Exploratory Data Analysis (EDA) & Feature Engineering**

**Technical Stack**: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

**Exploratory Data Analysis**: Performed comprehensive EDA on a dataset of 10,000+ flight records to identify price trends, airline distributions, and seasonal travel patterns.

**Feature Engineering**: Extracted high-value features from raw text data, transforming "Date of Journey," "Arrival Time," and "Departure Time" into granular temporal components (Day, Month, Hour, Minute) to improve model predictive power.

**Data Preprocessing & Cleaning**: Managed missing data via strategic dropping and imputation; resolved data type inconsistencies and handled outliers in "Price" and "Duration" columns.

**Encoding Strategies**: Implemented Ordinal Encoding for hierarchical data like "Total Stops" and applied One-Hot Encoding using Scikit-learn for nominal variables (Airline, Source, Destination), creating a machine-learning-ready feature set.

**Visualization**: Developed univariate and bivariate plots using Seaborn and Matplotlib to visualize the correlation between stopovers and flight costs, aiding in the discovery of key cost drivers.


Flight Price Exploratory Data Analysis (EDA) & Feature Engineering
**Technical Stack**: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

**Exploratory Data Analysis**: Performed comprehensive EDA on a dataset of 10,000+ flight records to identify price trends, airline distributions, and seasonal travel patterns.

**Feature Engineering**: Extracted high-value features from raw text data, transforming "Date of Journey," "Arrival Time," and "Departure Time" into granular temporal components (Day, Month, Hour, Minute) to improve model predictive power.

**Data Preprocessing & Cleaning**: Managed missing data via strategic dropping and imputation; resolved data type inconsistencies and handled outliers in "Price" and "Duration" columns.

**Encoding Strategies**: Implemented Ordinal Encoding for hierarchical data like "Total Stops" and applied One-Hot Encoding using Scikit-learn for nominal variables (Airline, Source, Destination), creating a machine-learning-ready feature set.

**Visualization**: Developed univariate and bivariate plots using Seaborn and Matplotlib to visualize the correlation between stopovers and flight costs, aiding in the discovery of key cost drivers.


Summary of the Project Workflow (from your files):
Input: Raw CSV/Excel flight data.

Processing:

Cleaned null values in the Route and Total_Stops columns.

Converted Duration (e.g., "2h 50m") into total minutes for mathematical analysis.

Mapped Total_Stops (non-stop → 0, 1 stop → 1, etc.).

One-Hot Encoded Airline, Source, and Destination to handle categorical variations.

**Output**: A clean, numerical final_df ready for Machine Learning algorithms.
