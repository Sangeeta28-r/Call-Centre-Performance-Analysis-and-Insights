# Call Centre Performance Analysis and Insights
![call_center_snapshot](https://github.com/user-attachments/assets/70ac834e-86d7-4cfc-831f-48d4dab64aa2)



## Problem Statement
The objective of this project is to analyze a call centre dataset to extract meaningful insights and provide actionable information for improving operations and meeting company requirements. The dataset contains the following columns:

- **CALLER ID**: Unique identification number of each caller.
- **AGENT**: Name of the agent handling the call.
- **DATE**: Date the call was received.
- **TIME**: Time the call was received (hh:mm:ss).
- **TOPIC**: Subject/topic of the call.
- **ANSWERED**: Indicates whether the call was answered or abandoned (Y/N).
- **RESOLVED**: Indicates whether the call was resolved by the agent (Y/N).
- **SPEED OF ANSWER IN SECONDS**: Time taken to answer the call.
- **AVG. TALK DURATION**: Average time spent by the agent on the call.
- **SATISFACTION RATE**: Satisfaction rating for the agent based on the call.

## Steps to Solve the Project

### Data Preprocessing
1. **Handle Missing Values**: Replace all null or blank values with `0`.
2. **Change Data Types**: Adjust data types as needed for analysis.
3. **Extract Time Metrics**: Extract seconds and minutes from `AVG. TALK DURATION` and create a new column `DURATION ON CALLS`.

### Data Analysis and Reporting
1. Calculate the total number of calls.
2. Create new columns:
   - Total number of calls answered.
   - Total number of calls rejected.
3. Calculate percentages:
   - % of calls answered.
   - % of calls rejected.
4. Create new columns:
   - Total resolved calls.
   - Total unresolved calls.
5. Identify:
   - The top agent who answered the maximum calls.
   - The top agent with the highest satisfaction rate.
6. Visualize:
   - Total number of calls by topic.
   - Call durations by each agent.
   - Total calls by days and months for the year 2021.
7. Add slicers for interactive charts based on month and day.
8. Provide overall 2021 performance ratings:
   - Use custom charts to show overall satisfaction ratings.

### Additional Insights
- Identify patterns or trends in calls and resolutions.
- Compare agents' performances based on call handling and satisfaction ratings.
- Highlight areas for improvement in operational efficiency.

## Solutions and Insights

### Key Performance Indicators (KPIs)
- **Total Number of Calls**: Provide the total count of all calls.
- **Answered vs Rejected Calls**: Calculate and visualize the distribution.
- **Resolved vs Unresolved Calls**: Assess agent performance in resolving issues.
- **Agent Performance**: Highlight top-performing agents based on answered calls and satisfaction ratings.
- **Topic Distribution**: Analyze call volume by topics to prioritize resources.
- **Call Duration Insights**: Evaluate agents' talk times to identify efficiency.

### Visualization Examples
- **Bar Chart**: Total calls by topic.
- **Line Chart**: Calls received over days and months in 2021.
- **Pie Chart**: Percentage of calls answered vs rejected.
- **Custom Chart**: Overall satisfaction rating.


---

## 2021 Performance Review
### Overall Rating
Provide a custom chart summarizing the overall satisfaction and operational efficiency of the call centre.

---

## Future Enhancements
- Automate the analysis process with scripts or workflows.
- Incorporate real-time data monitoring.
- Use machine learning to predict call volumes and optimize staffing.

### Repository Structure
```
📂 Call_Centre_Analysis
├── 📁 data
│   └── call_centre_data.csv
├── 📁 reports
│   └── 2021_performance_report.pbix
└── README.md
```



