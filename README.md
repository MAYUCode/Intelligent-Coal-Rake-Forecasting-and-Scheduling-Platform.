# Intelligent-Coal-Rake-Forecasting-and-Scheduling-Platform

**Overview**

The Intelligent Coal Rake Forecasting and Scheduling Platform is a solution that uses ML to predict coal stock levels at railway sidings. It optimizes rake allocation to cut down demurrage charges. The platform combines time series forecasting, scheduling optimization, and a streamlit-based dashboard to enhance railway logistics management.

**Key Features**

- Coal Stock Forecasting: This feature uses time-series models like Prophet to predict stock levels at each siding.

- Dynamic Rake Scheduling: It allocates rakes using Linear Programming, aiming for minimal delays.

- Demurrage Reduction: The platform tracks demurrage charges and recommends cost-saving options.

- Interactive Dashboard: It shows real-time coal levels, rake movements, and scheduling suggestions.

- Data-Driven Decisions: The platform uses historical data to align demand and supply.

**Problem Statement**

Railway logistics often face the following issues:

- Inefficient rake allocation, which results in idle time or congestion.

- High demurrage charges from delayed unloading or poor scheduling.

- Insufficient forecasting for coal demand and stock levels.

This platform addresses these problems by offering real-time, AI-driven planning.

**Tech Stack**

- Programming Language: Python

- Machine Learning: Prophet for forecasting

- Optimization: Linear Programming (PuLP)

- Frontend: Streamlit

- Database: MySQL 

- Visualization: Plotly , Matplotlib , Seaborn

**Dataset Structure**

The dataset includes these key variables:

- Siding ID and Location

- Stock Level and Max Stock Capacity

- Rake ID, Capacity, and Movement Details

- Loading and Unloading Times

- Demand and Supply

- Demurrage Charges

- Travel Costs

**Project Workflow**

1.Data Collection and Preprocessing

- This step involves cleaning, encoding, and handling missing values.

2.Forecasting Module

- It predicts coal stock levels through time-series analysis.

3.Scheduling Module

- This part optimizes rake allocation based on forecasted demand and available capacity.

4.Dashboard Integration

- It visualizes predictions, schedules, and costs in real-time.

5.Performance Evaluation

- This measures forecast accuracy using RMSE and MAPE, along with scheduling efficiency.

**Impact**

- 20 to 30% reduction in demurrage charges

- Better rake utilization and turnaround time

- Improved coordination among coal mines, railways, and unloading facilities

**Future Enhancements**

- Integration with live railway data APIs

- Using reinforcement learning for adaptive scheduling

-Multi-resource optimization involving coal, wagons, and crew.
