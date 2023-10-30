# A-SSVEP-Paradgim-Dataset-Based-on-Multiple-Sizes-and-Arrangements
A Steady-State Visual Evoked Potential Paradigm Dataset Based on Multiple Stimulus Sizes and Arrangements
# Description

# The distribution includes
EEG data/Paradigm1 : EEG data from 24 subjects under the paradigm 1 experiment
EEG data/Paradigm2 : EEG data from 24 subjects under the paradigm 2 experiment
EEG data/Paradigm3 : EEG data from 24 subjects under the paradigm 3 experiment
EEG data/Paradigm4 : EEG data from 24 subjects under the paradigm 4 experiment
EEG data/Paradigm5 : EEG data from 24 subjects under the paradigm 5 experiment
FBCCA/tutorial_fbcca.m : Tutorial of FBCCA-based SSVEP detection
FBCCA/test_fbcca.m : Classifying SSVEPs using FBCCA-based classifier
FBCCA/filterbank.m : Designing a filter bank
FBCCA/itr.m : Calculating information transfer rate (ITR)
TRCA/tutorial_trca.m : Tutorial of FBCCA-based SSVEP detection
TRCA/test_trca.m : Classifying SSVEPs using TRCA-based classifier
TRCA/train_trca.m : Training classifier based on TRCA
TRCA/filterbank.m : Designing a filter bank
TRCA/itr.m : Calculating information transfer rate (ITR)
# Dataset
The dataset contains 120 MATLAB MAT files corresponding to the data under the 5-paradigm experiment for all 24 subjects (about 450 MB in total). 
The naming scheme is combined according to the subject index as well as the paradigm index, i.e., S1-1.mat, ..., S24-1.mat; S1-2.mat, ..., S24-2.mat; S1-3.mat, ..., S24-3.mat; S1-4. mat, ..., S24-4.mat; S1-5.mat, ..., S24-5.mat. 
[# of channels, # of sampling points, # of targets,  # of blocks] = size(eeg);
Stimulus frequencies : 8.0 - 13.5 Hz with an interval of 0.5 Hz
Stimulus phases : 8.0 - 13.5 Hz with an interval of 0.5 Hz
Number of channels : 9 (1:Pz, 2:PO5, 3:Oz, 4:O1, 5:PO3, 6:O2, 7:PO4, 8:POz and 9:PO6)
Number of recording blocks : 8
Length of an epoch : 4 s
Sampling rate : 250 Hz
# Reference
1. M. Nakanishi, Y. Wang, X. Chen, Y. -T. Wang, X. Gao, and T.-P. Jung, "Enhancing detection of SSVEPs for a high-speed brain speller using task-related component analysis", IEEE Trans. Biomed. Eng, 65(1): 104-112, 2018. http://ieeexplore.ieee.org/document/7904641/
2. X. Chen, Y. Wang, M. Nakanishi, X. Gao, T. -P. Jung, S. Gao, "High-speed spelling with a non-invasive brain-computer interface", Proc. Natl. Acad. Sci. U.S.A, 112(44): E6058-E6067, 2015. http://www.pnas.org/content/early/2015/10/14/1508080112.abstract
