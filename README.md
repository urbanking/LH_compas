LH COMPAS Contest 
Project Title
Strategies to Minimize Vacancy Rates in Knowledge Industry Centers in Seongnam

Background
Due to prolonged stagnation in the profitable real estate market and oversupply of knowledge industry centers in the Seoul Metropolitan Area (with occupancy rates falling below 80%), vacancy in industrial complexes has emerged as a serious issue.

Despite this, there is a lack of reliable indicators to explain or predict vacancy rates, making it difficult to establish effective policy responses or development strategies.

Objective
To identify key factors influencing vacancy rates in Seongnam's knowledge industry centers and derive actionable insights.

To apply the derived indicators and models to assess the feasibility of a planned knowledge industry complex in Gyeyang District, Incheon (part of the 3rd New Town project).

Ultimately, to support policy-making and planning for future industrial center developments by providing explainable models and recommendations to reduce vacancy.

Scope
Analysis Target Area: Seongnam City, including multiple knowledge industry centers.

Application Target Area: Gyeyang Techno Valley site in Incheon.

Methodology Overview
Step 1: Variable Selection
Based on prior research and domain analysis, variables were categorized into five dimensions:

Transportation Accessibility

OD (Origin-Destination) commuting flow analysis

Distance to bus stops, subway stations, interchanges (IC)

Congestion cost and transfer convenience

Commercial Activity (Market Score)

Floating population (by time zone)

Card sales and purchasing power

Store opening/closure rates

Land Price (Officially Appraised Land Value)

Grid-based analysis using cadastral and transaction data

Demographics (Population)

Working-age residential population (20s–50s)

Density of potential commuting population within 500m radius

Knowledge Industry Center Features

Number of available vs. used units (to estimate vacancy rate)

Industry cluster patterns and competitive saturation

Step 2: Data Processing and Tools
All spatial and statistical analysis was conducted using Python and QGIS.

Diverse datasets were integrated: spatial (SHP), tabular (CSV), and geocoded APIs.

Preprocessing included geospatial joins, buffer analysis, KDE plots, and clustering.

Step 3: Modeling
Regression analysis was performed to identify the relationship between variables and vacancy rates.

Clustering was used to detect demand concentration (East vs. West Seongnam) and evaluate feasibility for new centers.

Key Findings
High Dependency on Internal Commuting

Over 30% of commuting inflow during peak hours came from within Seongnam's Jungwon District.

Accessibility from Seoul's southern districts (e.g., Gangnam, Songpa) was relatively low due to long travel times.

Market and Land Value Correlation

Areas with high market scores and land values tended to exhibit lower vacancy.

Industry Competition Intensity

Centers with high industry overlap (e.g., cosmetics, software, semiconductors) showed higher competition intensity and lower vacancy.

A balanced mix of 3+ industries per center correlated with better performance.

Feasibility Assessment of Gyeyang Techno Valley

Transportation, market activity, and population indicators were mapped and scored.

Recommendations were made regarding optimal layout and industry composition.

Policy Recommendations
Optimize Industry Composition

Assign 1-2 anchor industries per center

Allocate 40–50% floor space to anchors, 30–40% to complementary sectors

Manage Competition Intensity

Limit similar-use centers within 1 km radius

Apply differentiated strategies based on location characteristics

Monitor Vacancy Risk

Track signals such as contract renewals, rent negotiations, and tenant inquiries

Team
Team Name: YBIGTA DA
Members: Han Yeji, Kim Minseo, Moon Chanwoo, Yoo Junsun, Lim Dogeun
Date: February 2025
