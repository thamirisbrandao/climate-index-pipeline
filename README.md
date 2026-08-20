# Climate Risk Analytics Platform

Transformed manual climate analysis scripts into an API-driven climate risk application.

## Business Problem

The climate risk workflow relied on approximately independent scripts that had to be manually configured and executed for every analysis. Adjusting parameters, geographies, and timeframes directly in the code made the process time-consuming and heavily dependent on technical expertise. This bottleneck made it difficult to scale climate risk assessments across multiple locations, scenarios, and time periods, while restricting direct access to results for non-technical users. The business priority was to transform this manual scientific workflow into a scalable and user-oriented solution—enabling automated, user-defined data generation delivered through an accessible interface.

The project aimed to evolve the process from: 

**Manual scripts → Technical processing → Static results**

to:

**User inputs → Automated climate pipeline → API → Interactive risk visualization**

## My Role

Climate Data Scientist

Key Contributions
- ** Refactored and integrated 14 manually executed scripts** into a structured, object-oriented Python pipeline
- ** Automated** climate data processing based on client asset locations (latitude and longitude).
- ** Developed** workflows to extract and process ERA5 historical data and IPCC climate projections for individual assets.
- ** Built an API** to provide climate risk results programmatically.
- ** Developed an interactive Streamlit application** for climate risk visualization and analysis.

## Data 

* ERA5 reanalysis 
* IPCC projections

## Methodology

Client Assets
(CSV + Lat/Lon)
       │
       ▼
┌────────────────────┐
│ Geospatial Climate │
│ Data Extraction    │
└─────────┬──────────┘
          │
     ┌────┴────┐
     ▼         ▼
   ERA5       IPCC
     │         │
     └────┬────┘
          ▼
 Climate Variables
          │
          ▼
 Climate Risk Processing
          │
          ▼
        API
          │
          ▼
 Streamlit Application
          │
          ▼
 Maps / Risk Matrices /
 Asset-level Results
  
## Repository Disclaimer

This repository serves to document my professional experience and highlight my contributions to the project without disclosing proprietary solutions. To respect confidentiality, all implementation details, company-owned source code, credentials, internal infrastructure, and sensitive data have been strictly omitted.
