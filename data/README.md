# data
This directory includes data for evaluation

## Contents
- `platinum.smi`: SMILES of the Platinum dataset
- `platinum_dataset_2017_01.sdf`: The Platinum dataset which is available [here](https://www.zbh.uni-hamburg.de/forschung/acm/software-datasets.html).

`platinum.smi` is generated by Open Babel (v2.4.1).
```
obabel platinum_dataset_2017_01.sdf -O platinum.smi
```
