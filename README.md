SPT-Based Liquefaction Prediction Tool

A standalone Windows application for predicting soil liquefaction susceptibility from Standard Penetration Test (SPT) and seismic parameters, using an Optuna-optimized Deep Neural Network (DNN).

This tool accompanies the manuscript:

Kumar K., Kumar D.R., Wipulanusat W., Samui P., Kumar S. Explainable and Deployable Deep Learning for SPT-Based Liquefaction Susceptibility Prediction: An Optuna-SHAP Framework

What it does

Given eight soil and seismic input parameters, the application returns:

A binary liquefaction prediction (Liquefaction: YES / NO)
The model's predicted probability of liquefaction

The underlying DNN was trained on a 1,943-record SPT-based liquefaction dataset, achieving a test accuracy of 98.3%. Full model development, training details, and validation are described in the manuscript.

Input parameters
Parameter	Description	Unit
z	Depth	m
FC	Fines content	%
(N1)60	Corrected SPT blow count	—
Hw	Depth to groundwater	m
amax	Peak horizontal ground acceleration	g
Mw	Earthquake moment magnitude	—
σ	Total overburden stress	kPa
σ'	Effective overburden stress	kPa
How to run
Download liquefaction_app.exe from this repository.
Run it on a Windows machine — no installation or additional software required.
Enter values for all eight input parameters.
Click Predict to view the liquefaction classification and probability.

Note: Windows SmartScreen or antivirus software may flag the file as unrecognized on first run, since it is not digitally signed. This is expected for independently distributed executables — select "More info" → "Run anyway" if prompted.

Citation

If you use this tool, please cite:

[Full citation to be added upon publication]


Contact
Kishan Kumar, Department of Civil Engineering, National Institute of Technology, Patna, India kishank.phd22.ce@nitp.ac.in
