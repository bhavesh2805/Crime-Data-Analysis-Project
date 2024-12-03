Crime Data Analysis Project
IE6400 - Foundations of Data Analytics Engineering 

Objective
This project focuses on cleaning, inspecting, and analyzing a real-world crime dataset (2020–present) to identify trends, seasonal patterns, and other factors influencing crime rates. The analysis follows a structured approach as per the project guidelines.

Table of Contents
Overview of Tasks
Setup Instructions
Data Preprocessing
Analysis Framework
Visualizations
Recommendations
Contributing
License

Overview of Tasks
The project is structured as follows:
Task 1: Data Preprocessing
Clean and prepare the dataset for analysis.
Task 2: RFM Calculation
Compute Recency, Frequency, and Monetary values.
Task 3: RFM Segmentation
Group customers based on RFM scores.
Task 4: Customer Segmentation
Use clustering techniques (e.g., K-Means) for deeper segmentation.
Task 5: Segment Profiling
Define profiles for customer segments.
Task 6: Marketing Recommendation
Develop actionable strategies based on the analysis.
Task 7: Visualization
Present findings through effective charts and graphs.

Setup Instructions
Clone the repository:
bash
Copy code
git clone https://github.com/your-repo/IE6400_Project2.git
cd IE6400_Project2


Install dependencies: Ensure Python 3.8+ is installed. Use pip to install required libraries:
bash
Copy code
pip install -r requirements.txt


Run the project: Execute the main analysis script:
bash
Copy code
python main_analysis.py



Data Preprocessing
Key preprocessing steps include:
Handling missing data via imputation or row removal.
Converting date columns for time-based analysis.
Removing duplicate rows and invalid data (e.g., negative values).
Ensuring correct data types for efficient processing.

Analysis Framework
RFM Analysis: Calculate recency, frequency, and monetary scores to understand customer behaviors.
Segmentation: Use K-Means clustering to group customers into actionable segments.
Profiling: Profile each segment to guide marketing strategies.

Visualizations
Insights are presented through:
Trends and seasonal patterns in crime rates.
Distribution of RFM scores and customer segmentation.
Cluster characteristics using box plots and heatmaps.

Recommendations
Key strategies include:
Engagement for High-Value Customers: Loyalty programs and exclusive offers.
Reactivation Campaigns: Incentives for inactive customers.
Upselling Opportunities: Encourage frequent customers to spend more.

Contributing
Contributions are welcome. Follow these steps:
Fork the repository.
Create a new branch for your feature (git checkout -b feature-name).
Commit your changes (git commit -m "Add feature").
Push to the branch (git push origin feature-name).
Open a Pull Request.

License
This project is licensed under the MIT License. See LICENSE for details.

