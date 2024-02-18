# Fetal BPM Finder from ECG Data

## Overview
This project is focused on extracting the fetal heart rate from abdominal ECG data using MATLAB. It combines Fast Fourier Transform (FFT) and Moving Average Filter techniques for signal processing, as described in the paper "Fetal Heart Rate Extraction from Abdominal ECG Data Using Fast Fourier Transform and Moving Average Filter" by Saffan Firdaus and Mia Rizkinia (2022). The aim is to provide a reliable method for analyzing ECG data to find fetal BPM.

## About the Project
To learn more about the underlying research and methodologies used in this project, refer to the detailed study available at [Lib UI](https://lib.ui.ac.id/detail?id=20525901).

## Components
- **`fft_filter.m`**: A MATLAB function for FFT-based signal filtering to isolate the fetal heart rate from raw ECG data.
- **`findFetalBPM.m`**: The main script that utilizes `fft_filter.m` and `ma.m` to calculate the fetal BPM from the ECG data.
- **`ma.m`**: A MATLAB function for applying a moving average filter to smooth the ECG signal.

## How to Use
1. Ensure MATLAB is installed on your system.
2. Clone this repository to your local machine.
3. Place your ECG data file in the project directory. Adjust `findFetalBPM.m` if your data file has a different name or path.
4. Run `findFetalBPM.m` in MATLAB. The script will process the ECG data and output the fetal BPM.

## Acknowledgments and References
This project builds upon the foundational work on fetal electrocardiograms by Adam Matonia, Janusz Jezewski, Tomasz Kupka, Michał Jezewski, Krzysztof Horoba, Janusz Wrobel, Robert Czabanski, and Radana Kahankowa. Their extensive research into direct and abdominal fetal electrocardiograms with reference heartbeat annotations has significantly contributed to the development of non-invasive fetal monitoring techniques. For further reading, see their publication in Scientific Data, 2020.
