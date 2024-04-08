# Garmin Versus Oura

The aim of this repository is to gain insight from the difference in specific sleep monitoring variables monitored in the Oura Ring and Garmin Venu 2 Sq.

# Garmin and Oura Data Download

To download your own **Garmin** data, use the following [link](https://www.garmin.com/en-US/account/datamanagement/exportdata/) where you can choose to request your data for export.

For **Oura** data, use the following [link](https://cloud.ouraring.com/profile). Scroll down and click on the "sleep.json" file.

# Garmin Data Format

The data takes a while to be compiled for both Garmin, then it is sent through as an email. To see a full list of the sleep variables that are compiled when you download the data files from both companies, see [this file](https://github.com/andreac0ntreras/GarminVersusOura/blob/main/Garmin%20and%20Oura%20data%20description.pdf).

The data generated is downloaded as a zipped file. It contains a number of folders with all of the different data that is kept.
The data for the sleep is kept in the following directory:

```
/DI_CONNECT/DI-Connect-Wellness/
```

The formats for each of the sleep data files have the following naming schemes:

```
2023-12-29_2024-03-07_123456789_sleepData.json
```
# Oura Data Format

The data generated is downloaded as a JSON file directly onto your PC. It directly contains all of the sleep variables detailed in the [Garmin and Oura data description.pdf](https://github.com/andreac0ntreras/GarminVersusOura/blob/main/Garmin%20and%20Oura%20data%20description.pdf).

```
sleep.json
```

# Descriptive Statistics

See this [link](https://colab.research.google.com/drive/1D9NqOmW-3PdkkB4ow6pWf7ofMBCuBJxD?usp=sharing) to a Google Colab that cleans both the Garmin and Oura data and executes the following descriptive statistics. 

Deep Sleep Seconds - Oura:

Mean:  5670.0 , Median:  5970.0 , Standard Deviation:  1794.1906253238533 

Deep Sleep Seconds - Garmin:

Mean:  5245.714285714285 , Median:  5370.0 , Standard Deviation:  2786.769031091931 

Light Sleep Seconds - Oura:

Mean:  11682.0 , Median:  13500.0 , Standard Deviation:  3768.152863141303 

Light Sleep Seconds - Garmin:

Mean:  16242.857142857143 , Median:  16500.0 , Standard Deviation:  3401.6370608690086 

REM Sleep Seconds - Oura:

Mean:  6074.0 , Median:  6900.0 , Standard Deviation:  2173.31635985192 

REM Sleep Seconds - Garmin:

Mean:  6085.714285714285 , Median:  5880.0 , Standard Deviation:  2053.407322635492 

Average Respiration - Oura:

Mean:  15.533333333333333 , Median:  15.5 , Standard Deviation:  0.37490739597339984 

Average Respiration - Garmin:

Mean:  13.142857142857142 , Median:  13.0 , Standard Deviation:  0.8329931278350431 

## References
[Link to Data Download Steps and Format](https://github.com/tintin305/GarminSleepAnalytics?tab=readme-ov-file#data-download)
