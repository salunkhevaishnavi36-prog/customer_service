# customer_service
📊 Customer Service Request Analysis
📌 Project Overview
This project analyzes customer service request data to identify patterns in complaints, response times, and locations. The dataset is based on service requests handled by the New York City Police Department (NYPD).
📂 Dataset Information
Total Records: 364,558
Features: 53 columns
Key Columns:
Created Date
Closed Date
Complaint Type
City
Location
Status
⚙️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
SciPy
🔍 Steps Performed
1. Data Loading & Inspection
Loaded dataset using Pandas
Checked structure using .info() and .head()
Identified dataset shape and columns
2. Data Cleaning
Removed records with missing Closed Date
Converted date columns to datetime format
Removed incorrect records where Closed Date < Created Date
3. Feature Engineering
Created new column:
Request_Closing_Time (in seconds)
4. Handling Missing Values
Filled missing City values with "Unknown City"
📊 Exploratory Data Analysis
Complaint Distribution
Top complaint types:
Blocked Driveway
Illegal Parking
Noise - Street/Sidewalk
Noise - Commercial
City-wise Analysis
Most complaints come from New York City
Geographical Analysis
High complaint concentration in Brooklyn
Visualizations
Bar charts for complaint types
City-wise complaint distribution
Response time analysis
⏱️ Response Time Analysis
Mean: ~14,866 seconds
Minimum: 60 seconds
Maximum: 2,134,342 seconds
📈 Statistical Analysis
T-Test
Compared top 2 complaint types
Result: Significant difference found
Kruskal-Wallis Test
Compared multiple complaint types
Result: Different distributions observed
📌 Key Insights
Majority of complaints are from New York City
Noise and parking issues are most common
Response time varies across complaint types
Brooklyn has high complaint density
