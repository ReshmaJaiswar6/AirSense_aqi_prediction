# AirSense-Mumbai-Spatiotemporal-AQI-Prediction-using-Deep-Learning-Python-CNN-Regression-head
 Developed a satellite-based air quality prediction system using INSAT-3DR Aerosol Optical Depth (AOD) data and a CNN-LSTM with regression head to estimate surface-level PM₂.₅ and PM₁₀. The project involved multi-source data preprocessing, spatial image analysis, and predicts PM₂.₅ and PM₁₀ for urban air quality monitoring.
 
GitHub hosted website: https://reshmajaiswar6.github.io/AirSense_aqi_prediction/

### Project Objectives
Predict AQI, PM2.5, and PM10 accurately
Use satellite imagery for pollution estimation
Build a hybrid CNN-LSTM deep learning model
Create a user-friendly web platform for visualization
Provide health alerts and pollution awareness
Study indoor air purification using phytoremediation

Raw H5 AOD extreacted using Python and h5.py 

<img width="543" height="487" alt="image" src="https://github.com/user-attachments/assets/868cb9f4-0806-47e4-8930-bb3b3bda8fb6" />

Geospatially subsetted Mumbai & Preprossed & summerized AOD map

<img width="2091" height="2100" alt="3RIMG_09FEB2023_0845_L2G_AOD_V02R00" src="https://github.com/user-attachments/assets/894c5033-299a-4ebb-aa8e-a17ed4a90604" />


Interface of WinSCP client used for automated bulk acquisition of INSAT-3DR
data
<img width="1171" height="571" alt="image" src="https://github.com/user-attachments/assets/8a77448d-d864-4980-8432-e8bf0b77b833" />

Automating bulk data acquisition from MOSDAC via the WinSCP client.
<img width="1180" height="626" alt="image" src="https://github.com/user-attachments/assets/27c86b61-a830-44a0-8174-b8204546a2af" />


 ### Data Sources
#### 1. INSAT-3DR Satellite Data
Aerosol Optical Depth (AOD)
HDF5 (.h5) files
Downloaded from MOSDAC/ISRO
#### 2. MPCB Ground Truth Data
AQI
PM2.5
PM10
BKC Monitoring Station
#### 3. IMD Weather Data
Temperature
Rainfall
Wind Speed

### Technologies Used
##### Programming & Development
Python
Google Colab
GitHub Pages
WinSCP
#### Libraries
Pandas
NumPy
Matplotlib
Scikit-learn
TensorFlow
PyTorch
h5py
Rasterio
#### Deep Learning
ResNet-18
CNN-LSTM Architecture

### Workflow
#### Phase 1: Data Collection
Collect satellite .h5 files
Gather MPCB pollution data
Obtain weather records
#### Phase 2: Data Cleaning
Handle missing values
Standardize date formats
Align datasets temporally
Phase 3: Image Preprocessing
Extract AOD data from HDF5 files
Crop Mumbai region
Normalize data
Convert daily maps into images
#### Phase 4: Feature Engineering
Create pollution fingerprints
Generate temporal sequences
#### Phase 5: Model Training
Use ResNet-18 for spatial feature extraction
Use LSTM for temporal learning
Predict AQI values
#### Phase 6: Deployment
Deploy web platform using GitHub Pages

#### AirSense Web Platform Features
Real-time AQI dashboard
Pollution forecasting
Health advisory system
Indoor air quality recommendations
Geospatial pollution visualization
Personalized user modes

### Performance
Model Precision: ±19.1 AQI units
Uses NVIDIA T4 GPU acceleration
Handles approximately 400,000 satellite files

### Additional Research

The project also explores Phytoremediation, where indoor plants are studied for improving indoor air quality and reducing pollutants.


### Future Improvements
Real-time AQI prediction
Mobile application integration
Live API support
Improved forecasting accuracy
Street-level pollution mapping
### Team Members
Dhwani Chheda
Reshma Jaiswar
Iqra Miyaji

### Guided By
Dr. Arundhati Niwatkar

Department of Data Science
Usha Mittal Institute of Technology
SNDT Women’s University, Mumbai

