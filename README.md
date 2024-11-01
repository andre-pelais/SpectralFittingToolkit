# SpectralFittingToolkit

## Description
This project analyzes the photoluminescence spectra of semiconductor nanostructures, focusing on the effects of magnetic fields on excitonic complexes. The main objective is to extract relevant parameters from the spectra using curve fitting techniques and analyze the Zeeman effect.

## Table of Contents
- [Installation](#installation)
- [Data](#data)
- [Methods](#methods)
- [Results](#results)
- [Contributing](#contributing)

## Installation
To run this project, ensure you have the following dependencies installed:

```bash
pip install numpy pandas scipy lmfit plotly
```

## Data 

- The data used in this project should be in the format of two-dimensional arrays, where:
  - The first column corresponds to wavelength (or energy).
  - The second column corresponds to intensity counts.

 ## Methods 

 - **Curve Fitting**: The project utilizes _curve_fit_ from the _scipy.optimize_ to fit Gausssian or Lorentzian models to the spectral data.
 - **Zeeman Effect Analysis**: The Zeeman shift is analyzed using a custom model implemented in _lmfit_, allowing for the extraction of g-factors.

## Results

The analysis produces various outputs, including:
- Fitted parameters for each spectrum.
- Graphical representations of the raw and fitted data.
- A summary of the Zeeman effect analysis.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

  
