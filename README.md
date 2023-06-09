# FTIR Spectral and Test Strip Data

This repository contains the data utilized in our project. It includes FTIR spectral data and a dataset with test strip data. The purpose of sharing this data is to facilitate transparency, and to allow for others to replicate and validate our analysis. All data is anonymized and does not contain any proprietary or confidential information.

## Contents

This repository contains the following:

1. `spectra.zip`: This compressed file contains the Fourier Transform Infrared (FTIR) spectral data we used in our analysis. Each file in the zip corresponds to a specific spectrum collected during the experiment.

2. `test_site_data.csv`: This file contains data gathered from the test strips used in our study. The data points include various measures taken from each test strip, with each row representing a single test strip.

## Getting Started

To start working with the data:

1. Clone this repository to your local machine using `git clone https://github.com/DrugCheckingBC/nn_fenanyl_prediction`.
2. Unzip the `spectra.zip` file to access the FTIR spectral data.
3. Open the `test_site_data.csv` file in your preferred data analysis tool (R, Python, Excel, etc.).

## Data Description

### FTIR Spectral Data

This dataset is comprised of FTIR spectra collected as outlined in our paper. Each file represents a single spectrum, in jcamp format, and is named according to the sample from which it was derived.

### Test Strip Data

The test strip data is provided in CSV format, with the following columns:

- `FILE_ID`: The name of the associated FTIR file.
- `FENTANYL_STRIP_POS`: Whether the drug tested positive for fentanyl by the strip test (1=Positive, 0=Negative).
- `FENTANYL_FTIR_POS`: Whether the drug tested positive for fentanyl in the FTIR sample (1=Positive, 0=Negative).


## Contributing

While this is a public data repository, it is not open for contributions. However, we encourage you to utilize this data in your own projects and analyses.

## Contact

If you have any specific questions about this dataset, please feel free to contact us at `drugchecking@bccsu.ubc.ca`.

## License

This project is licensed under the terms of the MIT License. For more information, please see the [LICENSE](LICENSE) file.
