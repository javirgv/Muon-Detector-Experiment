# Muon Detector Experiment

*Fourth-year undergraduate Physics laboratory project (University College Dublin)*

## Overview
This project focused on detecting cosmic-ray muons at sea level using a plastic scintillator and measuring their lifetime. The experiment involved acquiring real experimental data, processing and analysing it with Python, and producing a detailed scientific report summarising the results.

## What I did
- Set up and calibrated the muon detection apparatus, including scintillator, photomultiplier tube, discriminator, and time-to-amplitude converter (TAC).  
- Collected time-resolved muon detection data over multiple runs, spanning hours to several days.  
- Implemented Python workflows to convert raw detector signals into time intervals, apply Poisson-based error analysis, and extract the muon lifetime through exponential fitting.  
- Analysed temporal trends in muon counts to identify and mitigate background signals and lab-related interferences.  
- Visualised data using histograms, time-series plots, and comparative analyses across different periods.
- Structured the analysis in a clear, modular Jupyter notebook suitable for reuse and inspection.  
- Documented the full experimental procedure, analysis, and interpretation in a structured PDF report.

## Technical focus
- **Programming & Analysis:** Python, NumPy, SciPy, serial, json
- **Visualisation:** Matplotlib (time-series plots, histograms, bar charts, comparative analyses)
- **Data Acquisition**: Software-based acquisition pipeline using modular NIM electronics, with channel-to-time calibration and structured data logging
- **Scientific methods:** Channel-to-time calibration, Poisson error analysis, exponential decay fitting, chi-squared testing, error propagation
- **Experimental Skills:** Photomultiplier calibration, discriminator threshold selection, TAC usage, Teensy microcontroller integration
- **Workflow:** reproducible analysis using Jupyter notebook and version control with Git 

## Repository structure
- `Teensy-Pulse-Generator/` – Linked sub-repository for Teensy-based pulse calibration  
- `data/` – Raw and processed muon detection datasets  
- `notebook.ipynb` – Python Jupyter notebook with data acquisition, processing and analysis workflows  
- `figures/` – Plots, visualisations, and images used in analysis and report  
- `report/` – PDF report summarising experimental setup, methods, and results
- `README.md` – Project overview and documentation

## Notes
This repository serves as a portfolio example showcasing scientific computing, data analysis, and experimental workflow. 

All data acquisition and analysis code used in the report PDF is available in the accompanying `.ipynb` Python Notebook.  
Report submitted as part of assessed coursework.
