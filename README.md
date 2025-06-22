# RBS-ML

RBS-MLP Datasets for 5G Rogue Base Station Detection

This repository contains datasets used for the research and evaluation of machine learning-based detection of Rogue Base Stations (RBS) in 5G networks. These datasets were generated using realistic signal strength measurements as described in our published papers (see Citation section below).
Each dataset consists of CSV files representing signal strength data from a simulated vehicular scenario, containing both Legitimate Base Stations (LBS) and Rogue Base Stations (RBS), across different window sizes.

# Dataset Structure
## The ZIP file dataset_RBS.zip contains the following CSV files:
90LBS–18RBS
500LBS–90RBS
1000LBS–180RBS
Each dataset is generated using multiple window sizes (WS):
WS=3
WS=5
WS=7
WS=10
Naming Convention
Example:
90LBS–18RBS_WS5.csv
90LBS–18RBS → 90 Legitimate Base Stations and 18 Rogue Base Stations
WS5 → Window Size of 5 samples
Description
The datasets are suitable for training and evaluating machine learning models for detecting rogue base stations based on signal strength patterns observed in mobile network scenarios such as vehicular environments or platooning.
The signal strength data were synthetically generated through simulation of mobile nodes traversing realistic radio environments, capturing both legitimate and adversarial transmissions.
Usage
You are welcome to use these datasets for academic or research purposes. Please ensure proper attribution by citing the following papers:
Citation
1️⃣ Saedi et al., 2020
"Generation of realistic signal strength measurements for a 5G Rogue Base Station attack scenario"
In IEEE Conference on Communications and Network Security (CNS), 2020
@inproceedings{saedi2020generation,
  title={Generation of realistic signal strength measurements for a 5G Rogue Base Station attack scenario},
  author={Saedi, Mohammad and Moore, Adrian and Perry, Philip and Shojafar, Mohammad and Ullah, Hanif and Synnott, Jonathan and Brown, Ruth and Herwono, Ian},
  booktitle={2020 IEEE Conference on Communications and Network Security (CNS)},
  pages={1--7},
  year={2020},
  organization={IEEE}
}
2️⃣ Saedi et al., 2022
"Synthetic generation of realistic signal strength data to enable 5G rogue base station investigation in vehicular platooning"
In Applied Sciences, 2022
@article{saedi2022synthetic,
  title={Synthetic generation of realistic signal strength data to enable 5g rogue base station investigation in vehicular platooning},
  author={Saedi, Mohammad and Moore, Adrian and Perry, Philip},
  journal={Applied Sciences},
  volume={12},
  number={24},
  pages={12516},
  year={2022},
  publisher={MDPI}
}
License
The datasets are provided for academic and research use only.
Commercial use is not permitted without prior written consent.
If you use these datasets, please cite the two papers listed above.
