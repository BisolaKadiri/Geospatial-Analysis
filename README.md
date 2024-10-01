# Geospatial Analysis of Anambra Election Data: Detecting Voting Anomalies
Election integrity is crucial for democratic processes. Ensuring that election results are accurate and free from tampering is essential for maintaining public trust. Geospatial analysis provides a powerful tool for detecting anomalies in election data. This report presents a detailed geospatial analysis of the Anambra State election data to identify potential voting irregularities.

# Data Overview
The dataset used in this analysis consists of polling unit (PU) data from the Anambra State election. The key attributes in the dataset include:
Latitude and Longitude: Coordinates obtained using geocoding in Google Sheets.
State, Local Government Area (LGA), Ward, Polling Unit Code (PU-Code), Polling Unit Name (PU-Name), Address.
Votes for major parties: APC, LP, PDP, and NNPP.

# Methodology
- Data Acquisition and Geocoding
The original dataset lacked geographic coordinates. Using Google Sheets' geocoding feature, I derived latitude and longitude for each polling unit based on their addresses. This geocoding process was crucial for enabling the geospatial analysis.

- Data Cleaning
To ensure the accuracy of the analysis, I removed entries with missing latitude, longitude, and key identifiers. This data cleaning step ensured that only complete and accurate data points were used in the analysis.

# Conclusion
The visualizations presented in this report provided a comprehensive overview of the voting anomalies in the Anambra State election data. They highlight regions and polling units with potential irregularities, facilitating targeted investigations. By combining geographical representations with statistical distributions, these visualizations offer a powerful tool for ensuring election integrity and transparency.

Link to the report: https://colab.research.google.com/drive/1uXAXtqMy9rxjaHDo_aj0BpGwp2SGdxQW

https://docs.google.com/document/d/1A4-ALKBT2czQA4Mm1NkgdbEIXbfg2EiMrVzjvaLensQ/edit
