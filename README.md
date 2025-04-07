# LH COMPAS Contest - 장려상(3rd prize)

## Project Title
**Strategies to Minimize Vacancy Rates in Knowledge Industry Centers in Seongnam**

##  Background
Due to long-term stagnation in the profitable real estate market, oversupply of knowledge industry centers (especially in the Seoul Metropolitan Area), and worsening business conditions for SMEs, the vacancy issue in industrial complexes has emerged as a serious problem.

However, a lack of concrete indicators explaining the vacancy rates has hindered the development of persuasive solutions.

##  Objective
- Build a composite indicator that explains the vacancy rate using various regional datasets for knowledge industry centers in Seongnam.
- Apply the insights to a site in **Gyeyang District, Incheon**, part of the 3rd New Town, to evaluate its location feasibility.
- Provide practical implications for minimizing vacancy rates in upcoming developments.

##  Scope
- **Analysis Target Area:** Seongnam City (Knowledge Industry Centers)
- **Application Area:** Gyeyang Techno Valley site (Incheon)

---

##  Methodology

### 1. Variable Selection
Key categories and their representative variables:

| Category            | Example Variables                                      |
|---------------------|--------------------------------------------------------|
| Transportation      | OD commuting flow, distance to IC, congestion cost     |
| Market Activity      | Floating population, card sales, store closure rate   |
| Land Value          | Official land value per grid                          |
| Population          | Number of residents aged 20–50 within 500m radius     |
| Industry Center Data | Total rooms, number of tenants, occupancy rate       |

### 2. Tools Used
- Python (pandas, geopandas, matplotlib, seaborn)
- QGIS (Buffer analysis, network distance using QNEAT3)
- Data types: `.csv`, `.shp`, `.geojson`, API (Kakao address geocoding)

### 3. Modeling
- Regression analysis for identifying key variables affecting vacancy
- OD Matrix and KDE visualizations for analyzing commuting patterns
- Spatial clustering to segment demand zones (East vs. West)

---

##  Key Insights

- **Internal commuting dominance:** Over 30% of inflows come from within Seongnam (Jungwon District).
- **High land value ↔ low vacancy:** Commercially valuable zones showed stronger demand.
- **Competition intensity matters:** Mixed-industry clusters (3 or more dominant sectors) perform better.
- **Accessibility matters:** Distance to subway/bus stops and ICs correlate with occupancy.

---

##  Strategic Recommendations

### 1. Industry Composition Strategy
- Select 1–2 anchor industries per center (e.g., IT, biotech)
- Allocate 40–50% of space to anchors and 30–40% to complementary industries
- Avoid oversaturation of a single industry

### 2. Competition Management
- Maintain balance in nearby centers (max 3–4 within 1 km)
- Monitor **competition score**:  
  `Competition Score = α(NC) + β(SIC) + γ(IMS)`

  Where:
  - NC = Nearby Center Ratio  
  - SIC = Same Industry Count  
  - IMS = Industry Market Share  

### 3. Vacancy Monitoring System
- Track tenant turnover, new inquiries, lease renewals, and rent negotiation trends

---

##  Team Information

**Team Name:** YBIGTA DA  
**Members:** Han Yeji, Kim Minseo, Moon Chanwoo, Yoo Junsun, Lim Dogeun  
**Submission Date:** February 2025  
**Affiliation:** Yonsei University

