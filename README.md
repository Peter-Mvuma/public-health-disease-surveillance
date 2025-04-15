# public-health-disease-surveillance
# Public Health Disease Surveillance Architecture Project

> Developed by Peter Mvuma| MSc Health Informatics | Executive Director @ National Organization of Nurses and Midwives of Malawi

## Overview
This project simulates a disease outbreak surveillance system across multiple hospitals. Using synthetic health data, OpenEMR, and HAPI-FHIR servers, the system enables the aggregation and visualization of COVID-19 patient data in real-time using Google Looker Studio.

## Architecture Highlights
- **5 Simulated Hospitals** using Virtual Machines: Baraga, Aspirus, Marquette, Portage, and UPHIE
- **OpenEMR Installation** on each VM, hardened with firewall rules and MySQL security best practices
- **HAPI-FHIR Server** hosted on UPHIE VM for standardized data sharing across the network
- **Synthea** used to generate realistic patient data in FHIR format
- **Python Scripts** to parse and aggregate .json records
- **Google Looker Studio Dashboard** for COVID-19 data visualization

## Technologies Used
- Ubuntu Linux
- OpenEMR + MySQL
- HAPI-FHIR Server (with customized UI)
- Postman (FHIR resource creation)
- Synthea (synthetic health record generator)
- Python (Pandas, NumPy, Matplotlib)
- Google Looker Studio

## Challenges Faced
- Handling data generation issues with city-specific demographics in Synthea
- Securing multiple VMs and ensuring consistent MySQL configurations
- Large memory usage when aggregating data from multiple .json sources
  
## Outcomes
- Successfully deployed a multi-node HIE environment with OpenEMR and HAPI-FHIR
- Created and secured patient records from synthetic populations

## COVID-19 Disease Surveillance Dashboard
Explore the COVID-19 surveillance data through this interactive dashboard built with Google Looker Studio:

[Click here to view the dashboard](https://lookerstudio.google.com/reporting/e69cf0c6-e255-4315-ab17-3b1664be02bc/page/ILXEF)

## Contact

Peter Mvuma  
✉️ pmvuma@mtu.edu  
🌐 [LinkedIn](https://www.linkedin.com)

---



