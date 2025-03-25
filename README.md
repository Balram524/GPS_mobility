# Project: Trip and Dwell Analysis Using GPS Data and Google Open Buildings Dataset

Dataset: Raw dataset of GPS for devices movement in Delhi NCR. [Click here](https://drive.google.com/drive/folders/107VIaocC--AyQ104yGqrOT8mFuB6LDL3)
## Overview
This project analyzes GPS mobility data to detect trips and dwell events while linking movement patterns to specific buildings using the Google Open Buildings dataset.It enables better urban mobility insights, transportation planning, and location-based analytics.

## Steps in the Analysis
### 1️⃣ Data Preprocessing
Load and clean raw GPS location data.

Ensure consistency in coordinate reference systems (CRS) for accurate spatial analysis.

### 2️⃣ Data Analysis & Visualization
Plot GPS trajectories on an interactive map to visualize movement.

Perform exploratory data analysis (EDA) to identify patterns in GPS behavior.

### 3️⃣ Trip and Dwell Detection
Trip Detection: Identify significant movements based on distance and time gaps.

Dwell Detection: Detect periods where the device remains in a small area.

### 4️⃣ Integration with Google Open Buildings
Download and preprocess the Google Open Buildings dataset for the target region.

Perform nearest spatial joins to link GPS points with buildings.

### 5️⃣ Trip Synthesis & Evaluation
Identify start & end points of trips using movement pings.

Enhance trip analysis by linking movements to specific buildings or areas.

Evaluate accuracy and patterns using appropriate mobility metrics.


## Outcomes 

### Data before Processing 
![image](https://github.com/user-attachments/assets/4ccc6fee-220f-4fe9-8c7c-83095fbeb2cf)

### Visualization of data
![image](https://github.com/user-attachments/assets/a05f6dd4-1b9e-4ec8-8733-aabd525764b1)


### Paticular Device Analysis
![image](https://github.com/user-attachments/assets/7b0eb34f-ad9b-4f85-8364-90b2cd91c594)

### Trip and dwell detection
Detected 1225 trips and 1225 dwells.

### google open building dataset for ROI
![image](https://github.com/user-attachments/assets/6b91a0c2-18ad-4ee4-9c86-74fd29ed45c2)
### Load and Process GPS Data
![image](https://github.com/user-attachments/assets/56f2b597-3b70-48c5-b0a0-30f4c4788802)

### Synthesize trips
![image](https://github.com/user-attachments/assets/77a47363-1dd0-422c-b316-36fe37bd0834)




