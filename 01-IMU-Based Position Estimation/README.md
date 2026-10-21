# Where Am I? — GPS-Free Geographic Localization

## Overview

This project is part of the *Embedded Machine Learning* course at Graz University of Technology (TU Graz).

The objective is to estimate geographic coordinates (latitude and longitude) using only the onboard sensors of an **Arduino Nano 33 BLE Sense Rev2**, without GPS/GNSS, Wi-Fi positioning, BLE beacons, cellular positioning, or additional sensor hardware.

The project combines physical modeling with embedded machine learning to investigate how geographic information can be extracted from sensor measurements and how ML can improve estimation accuracy and robustness.

## Project Objectives

- Develop a physics-based baseline for latitude and longitude estimation.
- Apply machine learning to improve estimation accuracy or robustness.
- Acquire and process onboard sensor measurements.
- Evaluate generalization to previously unseen locations.
- Investigate trade-offs between accuracy, observation time, computational cost, and memory usage.
- Deploy the final estimator directly on the Arduino.

## Hardware & Software

**Hardware**
- Arduino Nano 33 BLE Sense Rev2
- Integrated onboard sensors
- USB connection for programming and serial communication

**Software**
- Arduino IDE 2 (C/C++)
- Python for data processing, modeling, and evaluation
- Machine learning framework: TBD (to be determined)
- Additional dependencies: TBD

## Methodology

*To be completed during development.*

### 1. Sensor Acquisition & Physical Modeling
Describe the selected onboard sensors, data acquisition, calibration, and physical principles used to estimate geographic coordinates.

### 2. Machine Learning
Describe the selected ML approach, training data, preprocessing, and how the learned model improves the physics-based baseline.

### 3. Embedded Deployment
Explain how the estimator is deployed on the Arduino, including inference, memory requirements, and computational limitations.

## Evaluation & Results

The physics-based baseline and ML-enhanced estimator will be evaluated using the same held-out dataset.

| Metric | Physics Baseline | ML-Enhanced |
|---|---|---|
| Median localization error [km] | TBD | TBD |
| 90th-percentile error [km] | TBD | TBD |
| Transfer test error [km] | TBD | TBD |
| Observation time [min] | TBD | TBD |
| Sampling rate [Hz] | TBD | TBD |
| Flash usage [B, %] | TBD | TBD |
| SRAM usage [B, %] | TBD | TBD |
| Inference time [ms] | TBD | TBD |

Additional evaluation will include geographic transfer testing, sensitivity to UTC time errors (if applicable), and analysis of accuracy versus resource usage.

## Reproducibility

*Instructions will be added after implementation.*

### Dependencies
- Arduino board core version: TBD
- Arduino libraries and versions: TBD
- Python version: TBD
- Python packages and versions: TBD

### Running the Project
1. Install the required Arduino and Python dependencies.
2. Prepare the dataset and configuration files.
3. Run the training and evaluation scripts.
4. Compile and upload the final application to the Arduino.
5. Run the estimator and obtain latitude/longitude coordinates through the serial interface.

## Dataset & Demonstration

**Dataset:** Link to be added.

**Demonstration video:** Link to be added.

## Documentation

**Project report:** [report.pdf](report.pdf) — to be added.

## AI Use Disclosure

- **AI tools used:** TBD
- **Used for:** TBD
- **My main contributions:** TBD

## Project Status

In development.
