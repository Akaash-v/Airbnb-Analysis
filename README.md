# Airbnb Analysis

**Introduction**

Airbnb delves into a comprehensive exploration of Airbnb data. Airbnb has revolutionized the travel and property management industry, making it crucial to analyze its data to gain insights into pricing, availability patterns, and location-based trends. This project employs MongoDB Atlas, Streamlit, and data visualization techniques to provide an in-depth analysis.


**Table of Contents**

1. Key Technologies and Skills
2. Installation
3. Usage
4. Features
5. Contributing
6. License
7. Contact


**Key Technologies and Skills**
- Python
- Pandas
- MongoDB
- PostgreSQL
- Streamlit
- Plotly
- Tableau


**Installation**

To run this project, you need to install the following packages:

```python
pip install pandas
pip install pymongo
pip install psycopg2
pip install streamlit
pip install plotly
```

**Usage**

To use this project, follow these steps:

1. Clone the repository: ```git clone https://github.com/Akaash-v/Airbnb-Analysis.git```
2. Install the required packages: ```pip install -r requirements.txt```
3. Run the ```preprocessing.ipynb```
4. Run the Streamlit app: ```streamlit run app.py```
5. Access the app in your browser at ```http://localhost:8501```


**Features**

**Data Collection and Preprocessing**
- **MongoDB Data Retrieval**: Acquire the Airbnb dataset from MongoDB for analysis.
- **Handling Null and Duplicate Values**: Implement preprocessing techniques to address missing data and duplicates.
- **ETL and Dataframes**: Perform Extract, Transform, Load (ETL) operations to convert the data into structured dataframes for analysis.

**Streamlit-based EDA (Exploratory Data Analysis)**
- **Interactive Data Exploration**: Utilize Streamlit to create a user-friendly, interactive interface for exploring Airbnb data.
- **Plotly Charts**: Employ plotly charts to visualize key insights and trends in the dataset.

**Features Analysis**
- **Property Insights**: Analyze the total number of properties based on property type, room type, and bed type.
- **Stay Duration Analysis**: Investigate the minimum and maximum nights guests typically stay.
- **Cancellation Policy Impact**: Understand the impact of cancellation policies on booking trends.
- **Accommodation Metrics**: Explore accommodates, bedrooms, and beds-related statistics.
- **Review Analysis**: Examine total reviews, average review scores, and the distribution of reviews.
- **Bathroom and Pricing Analysis**: Investigate bathroom count, pricing, cleaning prices, and extra guest charges.
- **Guest Inclusion Trends**: Analyze the number of guests included in bookings.
- **Host Insights**: Explore host-related metrics, including host response time, response rate, and the number of properties hosted.
- **Geographic Analysis**: Investigate the market and country-level distribution of Airbnb listings.
- **Availability Trends**: Visualize property availability for the next 30, 60, 90, and 360 days.

**Top Host Analysis**

Identify and analyze the top 10 hosts based on various features, providing insights into host performance and success.

**Visualizations**

Utilize Plotly to create interactive and informative visualizations for EDA, making data exploration efficient and insightful.





