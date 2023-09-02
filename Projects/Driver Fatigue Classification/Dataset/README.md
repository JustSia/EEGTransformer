# EEGTransformer
This repository contains the EEG driver drowsiness dataset.

## Description
The dataset comprises EEG signals from 11 subjects with labels indicating either an alert or drowsy state. The data can be opened using Matlab. 

This dataset was extracted for research purposes from another public dataset:

[Cao, Z., et al., Multi-channel EEG recordings during a sustained-attention driving task. Scientific data, 2019. 6(1): p. 1-8.](https://arxiv.org/abs/1809.06534)

## Dataset Variables
The data file contains three primary variables:

EEGsample: Contains 2022 EEG samples of size 20x384 from 11 subjects. Each sample represents 3s of EEG data at 128Hz from 30 EEG channels.
subindex: An array of size 2022x1, indicating the subject indexes (ranging from 1-11) corresponding to each EEG sample.
substate: An array of size 2022x1, providing the labels for the samples. A label of 0 corresponds to the alert state, while a label of 1 indicates the drowsy state.
