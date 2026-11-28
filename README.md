<div align="center">

<img src="banner.png" alt="Alireza Fazeli Sani — Geospatial and Environmental Software Engineer" width="100%" />

# Alireza Fazeli Sani

**Geospatial & Environmental Software Engineer**  
*Earth Observation · Python · Remote Sensing · Hydrology · Environmental Intelligence*

[![Consulting](https://img.shields.io/badge/Consulting-Open%20to%20Projects-2ea44f?style=flat-square)](mailto:alirezafazeli@live.com?subject=Project%20Inquiry)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alireza-fazeli-sani-a7b41644/)
[![Urmia Lake Observatory](https://img.shields.io/badge/Live%20Research-Urmia%20Lake%20Observatory-008080?style=flat-square)](https://urmia-lake-observatory.pages.dev/)
[![Research DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24554247.svg)](https://doi.org/10.5281/zenodo.24554247)

</div>

---

## About

I develop open-source and research-oriented software that transforms Earth observation data, environmental datasets, and engineering methods into practical analytical tools.

My work focuses on building reproducible Python applications, geospatial intelligence platforms, satellite remote-sensing workflows, and environmental decision-support systems.

I am particularly interested in making advanced scientific methods more accessible through interactive applications, transparent data pipelines, and openly documented research tools.

**My objective is simple: turn complex environmental data into understandable, reproducible, and useful information.**

### Core Areas

- **Earth Observation & Remote Sensing:** Sentinel-1, Sentinel-2, SAR, InSAR, satellite altimetry and environmental monitoring.
- **Geospatial Engineering:** GIS, WebGIS, spatial analysis, raster processing and interactive mapping.
- **Environmental Intelligence:** Land subsidence, water resources, wetlands, climate indicators and ecological monitoring.
- **Software Engineering:** Python, FastAPI, React, TypeScript, Streamlit, APIs and automated testing.
- **Hydrology & Water Engineering:** Water systems, hydraulic calculations, environmental sampling and analytical tools.

---

# Featured Open-Source Projects

The following projects represent my primary research and development areas.

## 1. Tehran Subsidence Observatory

**Province-wide InSAR monitoring and geospatial analysis of land subsidence**

[![Live Observatory](https://img.shields.io/badge/Live%20Observatory-Open-2ea44f?style=flat-square)](https://cd1fb290.tehran-subsidence-observatory.pages.dev/)
[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/fazeli1977-dot/Tehran-Subsidence-Observatory)

An end-to-end InSAR processing and bilingual WebGIS platform designed to monitor land subsidence across all **16 counties of Tehran Province**.

The system processes real Sentinel-1A / Sentinel-1D IW TOPS SLC acquisitions and combines multi-track SBAS processing with ascending and descending observation geometry.

**Key capabilities**

- Multi-burst TOPS processing across three tracks.
- SBAS time-series inversion and phase unwrapping using SNAPHU.
- Two-dimensional vertical and east-west decomposition.
- Curvature-aware IRLS detrending.
- Explicit masking of uncovered areas and low-coherence pixels.
- County-level statistics and interactive point time-series inspection.
- Infrastructure screening using OpenStreetMap data.
- Meteorological context using Open-Meteo datasets.
- Bilingual Persian/English WebGIS interface.

**Research focus:** Understanding the spatial distribution of land subsidence and improving access to satellite-based monitoring information for environmental and infrastructure research.

**Important scientific qualification:** The reported deformation values are processing outputs, not independently validated ground-survey measurements. Infrastructure intersections are screening-level indicators and must not be interpreted as site-specific geotechnical assessments.

[**Explore the live observatory →**](https://cd1fb290.tehran-subsidence-observatory.pages.dev/)

---

## 2. Urmia Lake Observatory

**An open-science platform for lake hydrology, climate and ecological monitoring**

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-Open-2ea44f?style=flat-square)](https://urmia-lake-observatory.pages.dev/)
[![GitHub Repository](https://img.shields.io/badge/Repository-GitHub-181717?style=flat-square&logo=github)](https://github.com/fazeli1977-dot/Urmia-Lake-Observatory)
[![Zenodo DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24554247.svg)](https://doi.org/10.5281/zenodo.24554247)

A bilingual Persian/English environmental observatory for Lake Urmia and its endorheic watershed basin.

The platform brings together satellite observations, climate reanalysis, geospatial datasets, ecological records, and statistical methods in an interactive research and decision-support environment.

**Key capabilities**

- Satellite-altimetry water-level time series.
- Climate and water-balance analysis using ECMWF ERA5.
- Interactive multi-layer WebGIS.
- Watershed, river, wetland and shoreline mapping.
- Long-term trend analysis using Mann-Kendall and Theil-Sen methods.
- Ecological information from GBIF and Ramsar-related datasets.
- Data validation and local browser-based processing.
- Bilingual scientific PDF reporting.
- Automated quality assurance and deployment workflows.

**Scientific integrity:** The platform distinguishes direct observations, model-based data, derived indicators, indirect estimates and user-provided data. Missing measurements are identified explicitly rather than silently replaced with fabricated values.

**Research focus:** Supporting open environmental science, long-term ecosystem monitoring and accessible information about one of the most important saline lake systems in the Middle East.

[**Explore the live observatory →**](https://urmia-lake-observatory.pages.dev/)

---

## 3. SAR-MotionLens

**An interactive multi-frequency SAR/InSAR learning and experimentation environment**

[![Live Application](https://img.shields.io/badge/Live%20Application-Open-2ea44f?style=flat-square)](https://sar-motionlens.streamlit.app/)
[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/fazeli1977-dot/SAR-MotionLens)

SAR-MotionLens is an interactive laboratory for exploring Synthetic Aperture Radar concepts and Earth-surface dynamics across X-, C- and L-band radar frequencies.

**Key capabilities**

- Interactive InSAR interferogram generation.
- Wrapped and unwrapped phase visualization.
- Simulated LOS displacement time series.
- Polarimetric SAR indicators and feature exploration.
- LightGBM-based regime classification.
- IsolationForest anomaly scoring.
- Multi-location comparison and downloadable reports.
- Live NISAR granule metadata discovery through the ASF DAAC API.

**Data transparency:** NISAR granule metadata and coverage information are retrieved from the public ASF DAAC API. The deformation maps, interferograms, time series and machine-learning outputs are physically motivated simulations, not actual satellite-derived deformation measurements. The terrain model is also a synthetic DEM proxy.

**Research focus:** Making SAR/InSAR concepts easier to explore, understand and experiment with through an accessible interactive environment.

[**Try SAR-MotionLens →**](https://sar-motionlens.streamlit.app/)

---

# Additional Engineering Projects

| Project | Description | Repository |
|---|---|---|
| **Water Network Optimizer** | Python toolkit and CLI for pressurized pipe sizing, velocity checks and Hazen-Williams head-loss calculations, with CSV export and automated tests. | [GitHub](https://github.com/fazeli1977-dot/water-network-optimizer) |
| **Water Sampling App** | Persian RTL application for geotagged water and wastewater sampling, laboratory result comparison and PDF reporting. | [GitHub](https://github.com/fazeli1977-dot/water-sampling-app) |
| **TerraScope** | Satellite-based environmental intelligence for Ramsar wetlands, using Sentinel-2 STAC data and NDWI/NDVI time series. | [GitHub](https://github.com/fazeli1977-dot/TerraScope) |
| **ForestPulse-3D** | Environmental telemetry and wildfire early-warning architecture for the Hyrcanian Forests. | [GitHub](https://github.com/fazeli1977-dot/ForestPulse-3D-Docs) |
| **ClimateLens** | Climate-risk and trend-analysis prototype with interactive dashboards. | [GitHub](https://github.com/fazeli1977-dot/ClimateLens) |
| **FireSync MODIS–VIIRS** | Multi-sensor wildfire hotspot harmonization and analysis workflow. | [GitHub](https://github.com/fazeli1977-dot/FireSync-MODIS-VIIRS) |

[**Explore all public repositories →**](https://github.com/fazeli1977-dot?tab=repositories)

---

# Technology Stack

### Programming & Backend
`Python` · `FastAPI` · `Pydantic` · `SQLAlchemy` · `REST APIs`

### Frontend & Visualization
`React` · `TypeScript` · `Vite` · `Streamlit` · `MapLibre GL` · `ECharts`

### Geospatial & Remote Sensing
`GIS` · `WebGIS` · `Raster Processing` · `Sentinel-1` · `Sentinel-2` · `SAR` · `InSAR` · `STAC`

### Environmental & Scientific Analysis
`Hydrology` · `Climate Analysis` · `Time-Series Analysis` · `Statistical Methods` · `Environmental Monitoring`

### Engineering Practices
`Git` · `pytest` · `Automated Testing` · `CI/CD` · `Reproducible Workflows` · `Data Provenance`

---

# Funding & Open-Source Sponsorship

## Help Build Open Environmental Intelligence

I develop and maintain independent open-source tools for environmental monitoring, satellite data analysis and scientific decision support.

These projects are publicly accessible, and their continued development requires time for software engineering, scientific validation, documentation, testing, data integration and infrastructure maintenance.

I am currently seeking **an initial funding target of USD 1,000** to support the next development milestones across three core projects.

### Initial Funding Target

| Project | Target | Planned Development Focus |
|---|---:|---|
| Tehran Subsidence Observatory | **$400** | Processing documentation, scientific QA, uncertainty reporting and monitoring improvements |
| Urmia Lake Observatory | **$300** | Data provenance, scientific documentation, dataset validation and dashboard improvements |
| SAR-MotionLens | **$300** | Interactive SAR learning workflows, documentation and application improvements |
| **Total** | **$1,000** | |

These are proposed initial development allocations, not quotations or guaranteed project costs. Specific deliverables and timelines can be agreed with each sponsor.

## Ways to Support

### 1. Research Grants

I welcome grant opportunities supporting:

- Open-source environmental software.
- Earth observation and remote-sensing research.
- Climate resilience and water-resource monitoring.
- Open geospatial data and scientific reproducibility.
- Environmental technology for underserved regions.

### 2. Corporate Sponsorship

Companies working in satellite imagery, geospatial analytics, environmental consulting, climate technology and water management may support:

- Continued maintenance of open-source tools.
- Development of specific technical features.
- Integration of public environmental datasets.
- Demonstration projects and technical evaluations.
- Research and development collaborations.

### 3. Research & Institutional Partnerships

I am open to collaboration with:

- Universities and research laboratories.
- Environmental organizations and NGOs.
- Earth observation and GIS research groups.
- Climate and water-resource initiatives.
- Open-source foundations and scientific communities.

Partnerships can include technical development, data analysis, prototype development, documentation and collaborative research.

## What Sponsors Can Expect

Depending on the funding arrangement and agreed scope:

- Publicly documented development milestones.
- Transparent project progress and technical updates.
- Reproducible workflows and technical documentation.
- Public release of agreed open-source improvements.
- Acknowledgment of sponsors in project documentation, where appropriate.
- Direct technical communication during the collaboration.

Funding does not automatically imply ownership of an open-source project or exclusive rights to its existing code. Any licensing, intellectual-property, confidentiality or commercial arrangements will be agreed separately and documented.

## Funding Transparency

I aim to maintain a clear distinction between:

- Open-source maintenance and development.
- Sponsored feature development.
- Paid consulting and commercial engineering services.

Funding allocations, completed milestones and relevant project updates can be documented publicly where permitted by the funding agreement.

**Funding eligibility and payment arrangements must be confirmed before any commitment.** I will provide accurate information about the relevant project, beneficiary, residence and payment arrangements during due diligence. No payment route is assumed to be available merely because it supports international or cryptocurrency transfers.

**Interested in supporting a project?**

[Email me about funding or sponsorship](mailto:alirezafazeli@live.com?subject=Open-Source%20Funding%20%26%20Sponsorship) · [Connect on LinkedIn](https://www.linkedin.com/in/alireza-fazeli-sani-a7b41644/)

---

# Professional Services & Consulting

In addition to open-source research and development, I am available for selected remote engineering projects and paid technical collaborations.

| Service Area | Potential Deliverables |
|---|---|
| **Geospatial & Earth Observation** | Satellite-data pipelines, SAR/InSAR workflows, spatial analysis and environmental indicators |
| **WebGIS & Data Applications** | Interactive dashboards, mapping applications, API integration and data visualization |
| **Python Engineering** | Data processing tools, automation, REST APIs and reproducible analytical workflows |
| **Water & Environmental Engineering** | Hydraulic calculation tools, environmental monitoring applications and technical data analysis |
| **Research Prototypes** | Proof-of-concept applications, scientific visualization and technical documentation |

I am particularly interested in projects where software engineering and environmental science can create measurable practical value.

[**Discuss a consulting project →**](mailto:alirezafazeli@live.com?subject=Consulting%20%2F%20Engineering%20Project)

---

# Scientific Integrity & Responsible Development

Scientific transparency is a core principle across my projects.

I aim to:

- Identify the origin and type of datasets used.
- Distinguish observations from simulations, models and derived indicators.
- Document known limitations and data gaps.
- Avoid presenting estimates as direct measurements.
- Provide reproducible methods and accessible technical documentation.
- Use automated tests and quality checks where applicable.

The tools presented here are independent software and research projects. Their publication does not imply official affiliation with, endorsement by, or representation of NASA, ESA, USGS, UNESCO, the Ramsar Convention Secretariat or any government agency.

---

# Contact & Collaboration

I welcome serious inquiries related to open-source sponsorship, research grants, environmental technology, geospatial engineering and technical partnerships.

**Alireza Fazeli Sani**

- **Email:** [alirezafazeli@live.com](mailto:alirezafazeli@live.com)
- **LinkedIn:** [Alireza Fazeli Sani](https://www.linkedin.com/in/alireza-fazeli-sani-a7b41644/)
- **GitHub:** [fazeli1977-dot](https://github.com/fazeli1977-dot)
- **Urmia Lake Observatory:** [Live Platform](https://urmia-lake-observatory.pages.dev/)
- **Tehran Subsidence Observatory:** [Live Platform](https://cd1fb290.tehran-subsidence-observatory.pages.dev/)
- **SAR-MotionLens:** [Live Application](https://sar-motionlens.streamlit.app/)

---

<div align="center">

**Open Science · Practical Engineering · Environmental Intelligence**

*Building transparent tools for understanding a changing planet.*

</div>