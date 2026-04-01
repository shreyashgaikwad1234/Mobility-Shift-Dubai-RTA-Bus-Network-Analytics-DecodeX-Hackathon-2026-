# Mobility-Shift-Dubai-RTA-Bus-Network-Analytics-DecodeX-Hackathon-2026-
Python-based transport analytics project using 200K+ ridership records to detect structural demand shifts, forecast ridership, and propose cost-neutral fleet optimization for Dubai’s RTA bus network.
Overview

This project analyzes 209K+ ridership records from Dubai’s RTA bus network to:

1. Detect structural demand shifts
2. Forecast post-Metro ridership
3. Propose cost-neutral fleet optimization

Built as part of the DecodeX 2026 Hackathon, this project solves a real-world transportation planning problem triggered by Metro Phase 2 launch (July 2025).

Business Problem :

Dubai RTA faced a critical disruption:

1. 36% growth in ridership (2022–2025)
2. Metro Phase 2 launched → broke all previous demand patterns
3. No reliable forecast for peak season (Nov–Dec 2025)

Key questions:

1. Which routes are overloaded vs underutilized?
2. Is the demand shift temporary or permanent?
3. How to optimize fleet WITHOUT adding buses?

Solution Approach

The project is structured in 3 analytical stages:

Stage 1: Baseline Diagnosis : 

1. CAGR analysis (~11% uniform growth)
2. Seasonal demand modeling (Jan peak, Jul trough)
3. Corridor analysis (CBD = 29% demand)
4. Congestion-demand elasticity (+0.137 correlation)

Stage 2: Structural Break Detection : 

1. Identified regime change after Metro launch
2. Express routes: +29.8% surge
3. Feeder routes: −23.5% drop
   
Classified shifts:
1. Level shift
2. Volatility shift
3. Elasticity shift
   
Rebuilt forecasting model using:
Q4 Forecast = Q3 Actual × Seasonal Index

Stage 3: Model Validation
1. Out-of-time validation (Q4 2025)
2. Route Type	MAPE	Insight
3. Express	1.1%	Highly accurate
4. City	14%	Underestimated seasonality
5. Feeder	9.3%	Partial recovery
6. Intercity	12.3%	Seasonal uplift

Network Accuracy: 9.33% MAPE

Key Features / Techniques: 
1. Time-series analysis
2. Structural break detection
3. Forecast recalibration
4. Sensitivity analysis
5. Load ratio optimization
6. Congestion elasticity modeling
Tech Stack : 
1. Python (pandas, numpy)
2. Plotly (visualization)
3. Power BI (interactive dashboard)
4. Excel (forecast modeling)
Key Insights : 
1. Metro created a permanent regime shift
2. Express routes became last-mile connectors
3. Feeder routes lost CBD relevance
4. Fleet can be optimized without new buses
Business Impact
1. Reduced overload risk in Express routes
2. Reallocated 4–6 buses efficiently
3. Improved service without increasing cost
4. Created a scalable forecasting framework
