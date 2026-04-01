# Mobility-Shift-Dubai-RTA-Bus-Network-Analytics-DecodeX-Hackathon-2026-
Python-based transport analytics project using 200K+ ridership records to detect structural demand shifts, forecast ridership, and propose cost-neutral fleet optimization for Dubai’s RTA bus network.
Overview

1. Overview :-

This project analyzes over 200,000 ridership records from Dubai’s RTA bus network to detect structural demand shifts, forecast post-Metro ridership, and optimize fleet allocation under a cost-neutral constraint.
The analysis is built around the impact of Metro Phase 2 (launched July 2025), which disrupted historical demand patterns and invalidated existing forecasting models.

2. Business Problem :-

Dubai RTA faced multiple operational challenges:-

Rapid demand growth of approximately 36% between 2022 and 2025
   Structural disruption due to Metro Phase 2 launch
   Lack of reliable forecasting for peak demand periods
   Imbalance between overloaded and underutilized routes
   Need for optimization without increasing fleet size

Key objective:-
To redesign forecasting and fleet allocation strategy under a post-Metro demand regime.

3. Solution Approach :-
3.1 Stage 1: Baseline Diagnosis
   Computed CAGR across routes (~11% uniform growth)
   Identified seasonal demand patterns (January peak, July trough)
   Performed corridor analysis (CBD contributes ~29% demand)
   Measured congestion-demand elasticity (positive correlation)
   Built baseline forecast using historical growth and seasonality
3.2 Stage 2: Structural Break Detection
   Compared Q3 2025 actuals with Stage 1 forecasts
   Identified demand shifts:
     Express routes increased by 29.8%
     Feeder routes declined by 23.5%
Classified structural changes into:
   Level shift
   Volatility shift
   Elasticity shift
   Determined regime change vs temporary shock
   Rebuilt forecasting model using Q3 data as new base

Forecast model used:
Q4 Forecast = Q3 Actual × Seasonal Index

3.3 Stage 3: Model Validation
   Performed out-of-time validation using Q4 2025 data
   Evaluated accuracy using MAPE

Results:

Express routes: 1.1% (high accuracy)
City routes: 14.0% (underestimated seasonality)
Feeder routes: 9.3% (partial recovery)
Intercity routes: 12.3% (seasonal uplift)

Overall network accuracy: 9.33% MAPE

4. Key Features and Techniques :-
   Time-series analysis
   Structural break detection
   Forecast recalibration
   Sensitivity analysis
   Load ratio optimization
Congestion elasticity modeling
5. Tech Stack :- 
   Python (pandas, numpy)
   Plotly for visualization
   Power BI for dashboard development
   Excel for forecasting and sensitivity modeling
6. Key Insights :- 
   Metro Phase 2 caused a permanent regime shift in demand
   Express routes became primary last-mile connectors
   Feeder routes lost relevance in CBD corridors
   Demand patterns diverged significantly across route types
   Historical models are no longer valid for all segments
7. Business Impact :-
   Identified overload risk in high-demand routes
   Enabled reallocation of 4–6 buses across the network
   Achieved cost-neutral optimization without new procurement
   Improved service efficiency in peak demand periods
   Developed a scalable forecasting framework for future use
