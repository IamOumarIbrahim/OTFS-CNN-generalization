<div align="center">

# Evaluation of Input Domain Representation and Generalization in Deep Learning-Based OTFS Detection

[![PDF](https://img.shields.io/badge/Paper-PDF-red?logo=adobeacrobatreader&logoColor=white)](docs/manuscript/main.pdf)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![MATLAB](https://img.shields.io/badge/MATLAB-R2026a-orange?logo=mathworks&logoColor=white)](https://www.mathworks.com/products/matlab.html)


**Oumar Ibrahim** and **Bassel Al Homssi**  
*Department of Computer Engineering, University of Sharjah, Sharjah, UAE*  
`U22200741@sharjah.ac.ae` | `bhomssi@sharjah.ac.ae`

</div>

> [!TIP]
> Work in progress: Code updates follow research progress. GRU and Mamba are postponed to focus solely on 1D time-domain representation, compared exclusively against 1D CNN.

## Project Structure

```
src/
├── config/
│   └── config_params.m
├── signal/
│   ├── otfs_tx.m
│   ├── otfs_rx_domains.m
│   └── apply_channel.m
├── learning/
│   ├── make_dataset.m
│   ├── build_network.m
│   └── train_detector.m
├── detectors/
│   └── detect_mmse.m
├── evaluation/
│   ├── evaluate_ber.m
│   └── export_pgfplots.m
├── tests/
│   └── test_sanity.m
├── scripts/
│   ├── run_train_all.m
│   ├── run_ber_vs_snr.m
│   ├── run_mismatch.m
│   └── run_complexity.m
├── data/
├── models/
├── results/
└── figures/
```
