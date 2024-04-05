# Multivariate Control Chart with Dimension Reduction using FAMD and Autoencoder

This repository contains the implementation of a multivariate control chart with dimension reduction techniques, namely Factor Analysis of Mixed Data (FAMD) and Autoencoder. The control chart is designed for detecting network intrusions using network data traffic.

## Problem Statement

Conventional multivariate control diagrams for detecting network intrusions face several challenges:

1. **False Alarms:** Occur due to network data traffic distributions not aligning with existing theories.
2. **Masking Effects:** Limitations in detecting outlier intrusions.
3. **Various Data Types:** Handling both categorical and continuous data types.

## Solution Proposed

To address these challenges, this project proposes a multivariate control chart with the following techniques:

1. **Factor Analysis of Mixed Data (FAMD):** A technique for reducing data that contains both quantitative and qualitative variables.
2. **Autoencoder:** A technique for dimensional reduction specifically designed for quantitative variables, aimed at enhancing the performance of multivariate control charts.

## Implementation

The proposed multivariate control chart is based on the conventional T2 control chart. We compare the performance of conventional T2 with T2 integrated with FAMD and Autoencoder for dimension reduction.

Using data simulation from UNSW-NB 15 dataset, the results demonstrate the following accuracies:

- Conventional T2: 64%
- T2 with FAMD: 74%
- T2 with Autoencoder: 76%

## Repository Contents

- `Hotelling-T-Square-with-FAMD-Autoencoder.ipynb`: Jupyter notebook containing the implementation of the multivariate control chart with FAMD and Autoencoder.
- `UNSW DATA.zip`: Contains the dataset files `NUSW-NB15_features.csv`, `UNSW_NB15_testing-set.csv`, and `UNSW_NB15_training-set.csv`.
- `inferensi article`: Link to the published paper detailing the methodology and results.

## Usage

1. Clone the repository:
git clone https://github.com/zenklinov/Hotelling-T-Square.git

2. Extract the dataset files from `UNSW DATA.zip`.

3. Open and run `Hotelling-T-Square-with-FAMD-Autoencoder.ipynb` in a Jupyter notebook environment.

## References

- [Link to Published Paper](https://iptek.its.ac.id/index.php/inferensi/article/view/18751)

For more detailed information, refer to the published paper linked above.

## Contributors

- Kevin Agung Fernanda Rifki
- Niam Rosyadi
- Novri Suhermi
- Amanatullah Pandu Zenklinov

Feel free to contribute by submitting issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
