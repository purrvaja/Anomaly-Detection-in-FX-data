# FX Analysis and Anomaly Detection with ECB Data

### Project Objectives

-   Analyze historical FX data from the European Central Bank (ECB) for the past 10 years (2013-2023).
-   Identify potential anomalies in individual currency exchange rates against the Euro.
-   Investigate potential reasons behind these anomalies using available data and external sources.

### Overview

This project utilizes the ECB API to retrieve historical FX data for all available currencies against the Euro. Exploratory Data Analysis (EDA) is performed to visualize currency trends and identify potential correlations amongst currencies. 
Anomaly detection is implemented using the Isolation Forest algorithm, with individual models trained for each currency. Detected anomalies are investigated to uncover possible explanations based on historical events and economic data.

### Key Findings

-   Significant correlations observed between specific currency pairs like USD/EUR, USD/SGD and AUD/NZD.
-   Isolation Forest successfully identified anomalies in various currency time series.
-   Further analysis revealed potential explanations for certain anomaly occurrences. E.g. Brexit causing the GBP to fall in 2016, political instability in Greece causing the EUR to depreciate against the USD in 2014. 
