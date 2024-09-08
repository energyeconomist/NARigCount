# North American Rig Count

## Overview

This notebook performs an analysis of Baker Hughes' weekly rig count data for the US and Canada. It fetches the latest rig count reports, processes the data to calculate weekly changes, and generates a brief commentary on changes in natural gas and oil rig counts.

## Steps
### 1. Data Fetching:
- Fetches the latest rig count report from Baker Hughes' website.
- Parses the HTML to locate and download the most recent Excel file.
- Reads the data into a Pandas DataFrame for further processing.

### 2. Data Processing:
- Filters the data for the last four reporting weeks and adjusts the DataFrame format by setting the report date as the index.
- Creates separate DataFrames for different rig types (gas, oil, miscellaneous) and basins.

### 3. Weekly Change Calculation:
- Calculates weekly changes in rig counts by comparing data from consecutive weeks.
- Generates tables displaying the weekly changes for various categories.

### 4. Commentary Generation:
- Constructs a textual summary based on the latest rig count data and weekly changes.
- Provides a readable report that highlights changes in natural gas and oil rig counts.
