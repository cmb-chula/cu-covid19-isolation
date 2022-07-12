# cu-covid19-isolation
Self-reported vital sign and symptom data from COVID-19 isolation cohort, KCMH, Bangkok, Thailand
The data are available in `data`.



Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

The included datasets are licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


## Dependencies 

A list of all required python packages can be found in `requirement.txt`.

To install dependencies, run

`pip3 install -r requirements.txt`

## How to train model?

The code for training the XGBoost model is provided in `training_model.ipynb`.

The performance of the XGBoost model on each task.

| Task   | PRAUC |
| ------------- |:-------------:|
| Admitted within 1 day  | 0.7700±0.0693 |
| Admitted within 2 days | 0.8359±0.0372 |
| Admitted within 3 days | 0.9451±0.0185 |