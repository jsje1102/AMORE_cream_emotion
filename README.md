# AMORE_cream_emotion
Deep learning method for classification for emotions 
# Project Title

Emotion recognition while applying cosmetic cream using deep learning from EEG data; cross-subject analysis

## About project

These files include the analysis code and preprocessed data presented in the paper "Emotion recognition while applying cosmetic cream using deep learning from EEG data; cross-subject analysis" submitted to the PLOS ONE journal.

### Code

These codes were developed in the environment of MATLAB R2020b.
The four CNN-based deep learning methods presented in the paper were created in the following four mlx files, respectively.
1. Emotion_EEGlayout_stacked_band_all_test_no_dropout.mlx
2. Emotion_EEGlayout_inception_all_test_3module_no_dropout.mlx
3. Emotion_EEGlayout_each_band_all_test_no_dropout.mlx
4. Emotion_EEGlayout_Multi_input_all_test_no_dropout.mlx


### Data

This is the pre-processed data of the data measured by EEG. This is data classified for the following positive and negative emotions. Each data consists of 16 cells (16 subjects in total), and each cell contains EEG data of size 10x10x1x140. For detailed data information, please refer to the paper.
1. positive_class_bands_chan2_all_subj.m
2. negative_class_bands_chan2_all_subj.m



