# Spectral-gated MoE for robust multitask fault diagnosis
Code and evaluation manifests for: [paper title]
## Data
Download the public CWRU dataset from https://engineering.case.edu/bearingdatacenter/download-data-file, then run:
python scripts/make_cwru_windows.py
## Reproduce
python src/train_eval.py --config configs/cwru_matched_noise.yaml --seed 89994
## License
MIT. CWRU data are not redistributed.
