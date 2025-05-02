# DSAN 5500 Final Project: 

# National Park Insights: An ETL Pipeline for Alerts, Activities, and Trip Planning Using Prefect

This project automates the extraction, transformation, and loading (ETL) of data from the **National Park Service (NPS) API** to deliver weekly insights on park alerts, activities, and planning tools. It is designed to help travelers, researchers, and policymakers understand current conditions across U.S. national parks and plan safer, more informed visits.

## Project Structure
```
├── README.md                       # Project overview and instructions
├── _quarto.yml                     # Quarto configuration for the site
├── assets/                         # Project visuals and report source files
│ ├── artifact.qmd                    # Final artifact markdown
│ ├── banner.jpg                      # Banner image for report
│ ├── flow_code.qmd                   # Code and explanation of pipeline steps
│ ├── nps-report-flow.png             # Artifact flow diagram
│ ├── nps-scraper-deployment.png      # ETL deployment diagram
│ └── nps-scraper-flow.png            # ETL flow diagram
├── code/
│ └── NPS_Alerts_Flow.ipynb           # Main Prefect ETL notebook
├── docs/                           # Output site
├── index.qmd                       # Home page for Quarto report
├── references.bib                  # Bibliography and citation info
└── site_libs/                      # Quarto-generated support files
```

## Features
- **ETL Pipeline with Prefect:** Automates weekly extraction and transformation of alerts, park info, and activity data.
- **Validation with Pydantic:** Ensures type safety and structure in raw API responses.
- **Markdown Artifact Generation:** Compiles a clean, human-readable summary of park alerts by state.
- **Visual Pipeline Documentation:** Flowcharts and deployment diagrams to explain the architecture.
- **Quarto Website Integration:** Generates a report website or PDF from annotated `.qmd` files.


## Future Work  
- Email/SMS alert subscriptions
- Real-time dashboard using Streamlit or Dash
- Activity-based itinerary planning
- Integration with third-party datasets (e.g., wildfire zones, trail conditions)