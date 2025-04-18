# Recording Data

This folder contains the neuronal spiking activity data that are used in this study. Recording experiments are labeled accordingly in *"spiketimes_data"*. Each file contains the spike times of a neural population from one recording session obtained by Neuropixel probes and pre-processed after spike sorting (see SI methods).

## Data Setup Instructions

1. Download the spike time data as .mat files from the following repository:
   https://doi.org/10.5683/SP3/XZROAH

2. Place the downloaded .mat files in this folder.

3. Convert the data to .pkl format using the data conversion utility:
   ```
   python ../utils/data_converter.py
   ```

4. After conversion, the .pkl files can be used to run the optimization for all cells in the recording.

Please refer to the main README file for detailed instructions on how to run the optimization code.