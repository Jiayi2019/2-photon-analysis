2-photon analysis in MATLAB
This repository contains MATLAB code for analyzing calcium imaging data. The program generates ΔF/F per stimulation, averages neural responses from three stimulations per neuron, generates a time series for each neuron, and computes an average time series across all neurons.

Table of Contents
Overview
Features
Installation
Usage
Contributing

Overview
This MATLAB code automates the analysis of neural response data by:
Generating dF/F0 per stimulation.
Averaging responses from multiple stimulations per neuron.
Generating a time series for each neuron.
Computing an average time series across all neurons.

Features
dF/F0 calculation: Generates dF/F0 for each stimulation.
Averaging Responses: Calculates the average response for three stimulations per neuron.
Time Series Generation: Creates a time series for each neuron based on the averaged responses.
Aggregate Analysis: Computes an average time series across all neurons.

Installation
To use this MATLAB code, you need to have MATLAB installed. There are no additional MATLAB Toolboxes required beyond the default installation.

Usage
Prepare Your Data: Ensure your data is formatted correctly similar to the sample data provided.

Run the Analysis: Use the provided MATLAB script post_calcium_imaging_pipeline.mat. Open MATLAB and navigate to the directory containing the script. Execute the script with the following command:

matlab
Copy code
result=post_calcium_imaging_pipeline(data);
data shall be a matrix in the format like sample_data.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements or bug fixes. For significant changes, open an issue first to discuss the proposed modifications.
