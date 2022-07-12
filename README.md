# Premature Ventricular Complexes (PVCs) and Premature Atrial Complexes (PACs) detector using an ECG-based Deep Learning approach

This repository contains the code for the project of the course Applied AI 
in Biomedicine at PoliMi.
Checkout the [report](https://github.com/giovannidispoto/applied-ai-in-biomedicine-ECG-classifier/blob/main/report_Applied_AI_in_Biomedicine_Project.pdf) for further details.

## Summary 
In this project, we propose a 1D-CNN that is able to predict, in an 
inter-patient fashion, if a beat is Normal,
Premature Ventricular Complex or Premature Atrial Complex relying on only a portion of the ECG. In particular, the CNN 
requires in input a window length of 500 samples around the R-peak of the beat that we want to predict. This 
model gives us a quite good result with an accuracy ≥ 0.75 in the worst case related to the PVC class
