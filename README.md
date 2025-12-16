# BNA-flight-delay-covid_impact
This capstone project analyzes flight performance at Nashville International Airport (BNA), focusing on departure delays, arrival delays, and cancellations across major U.S. airlines. The goal is to understand how airline operations at BNA were affected before, during, and after the COVID-19 pandemic, and how recovery patterns varied by airline.
This project seeks to analyze flight delays, arrivals, departures, and cancellations at **Nashville International Airport (BNA)** and compare trends across three phases: **Pre-COVID (2018-2019), During COVID(2020-2021, and Post-COVID(2022-Jul,2025)**. Specifically, it will:
- Examine patterns in departure and arrival delays.
- Evaluate cancellation trends across airlines.
- Compare the performance of major airlines and low-cost carriers.
- Analyze correlations between airport traffic and flight delays during these phases.
By addressing these questions, the project aims to uncover key insights into how COVID-19 impacted flight operations at BNA , providing a better understanding of airline performance and passenger experience.

## Table of Contents

- PowerBI Dashboard
- Motivation
- Questions
- Data Cleaning & Normalization
- Technologies Used
- Data Sources

---

### PowerBI Dashboard

Link:

PPT Presentation Link:

------

###Motivation

The COVID-19 pandemic caused unprecedented disruptions in the airline industry, leading to fluctuating flight schedules, delays, and cancellations.
This project is motivated by both professional and analytical interests:
With 4 years of experience working in airlines, handling flight ticket issuance and reissuance, I have firsthand knowledge of operational challenges, passenger impact, and airline performance metrics.
I am interested in analyzing how flight delays and cancellations affect operations and customer experience, especially across different phases of COVID-19.
The project aims to combine practical industry experience with data analysis skills to uncover actionable insights on airline performance.

------
### Questions

- What were the trends in departure and arrival delays before, during, and after COVID-19?  
- Which airlines experienced the most delays or cancellations during each phase?  
- How did low-cost carriers compare to major airlines in terms of punctuality?  
- Are there correlations between airport traffic and flight delays or cancellations?

-------

### Data Cleaning & Normalization

- The original datasets contained null values and inconsistent formatting.  
- Columns removed. 
- BOM (Byte Order Mark) issues in the CSV files were handled using Python (`utf-8-sig` encoding).  
- A new column was created mapping **airport codes** to their corresponding **city and state** for better readability.  
- All three datasets (Departures, Arrivals, and Cancellations) were combined in a single Jupyter notebook for unified analysis.

-------

### Technologies Used
- Excel/Power Query - Data Cleaning/Combining Csv files
- Python / Pandas – Data cleaning, exploration, and analysis  
- Power BI – Interactive dashboard creation  
- Canva – Presentation slides and visuals  
- Git – Version control and repository management  

------

### Data Sources

- Departure, Arrival, and Cancellation CSV files (BNA)  
- U.S. Department of Transportation: [Airline On-Time Performance Data](https://www.transtats.bts.gov/)  
- Airline classification references for low-cost vs. major carriers  
- Additional airport and city,State mapping data created in-house

- ------
Conclusion----
