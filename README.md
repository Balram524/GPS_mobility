# Project: Trip and Dwell Analysis Using GPS Data and Google Open Buildings Dataset
## Overview
This project analyzes GPS mobility data to detect trips and dwell events while linking movement patterns to specific buildings using the Google Open Buildings dataset.It enables better urban mobility insights, transportation planning, and location-based analytics.

## Steps in the Analysis
### 1️⃣ Data Preprocessing
>> Load and clean raw GPS location data.
>> Ensure consistency in coordinate reference systems (CRS) for accurate spatial analysis.

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
