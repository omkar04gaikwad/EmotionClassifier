# Emotion Classifier using EEG Signal Analysis

**Authors**: Omkar Gaikwad, Raksha Jain, Sahil Gharat  
**Affiliation**: Final Year Electronics Department, Sardar Patel Institute of Technology, Andheri 400058, Mumbai.

## Abstract

Identifying human emotions through EEG signals is a challenging task. This project utilizes a Support Vector Machine (SVM) classifier trained with the DEAP dataset to predict emotions based on valence and arousal. The results obtained can further be used to predict emotional expression.

## Introduction

Emotions are crucial in human interactions and decision-making. Recognizing emotions has applications in various fields such as medical, education, intelligent systems, psychology, and human-computer interaction. This project focuses on emotion detection using EEG signals for more accurate results.

## Methodology

1. **Extracting the Dataset:**
   - DEAP dataset is utilized, containing ratings from self-assessment and physiological recordings from participants watching music videos.
   - Labels and data from each channel are extracted into separate files.

2. **Finding the Features:**
   - Wavelet transform is applied to decompose each channel data into five frequency bands.
   - Frequencies near 0-0.5 Hz and 50 Hz are neglected to remove artifacts.
   - EEG bands are obtained for each channel.

3. **Reducing the Dimension:**
   - Standard Deviation is used to reduce dimensionality.
   - Welch's periodogram is employed to compute the power spectral density.

4. **Training the Vector:**
   - SVM Classifier is used to train the model for classifying emotions into Valence and Arousal.

## Results

The project successfully implemented the methodology, resulting in a processed dataset with reduced dimensions. The SVM classifier efficiently classified test data into Valence and Arousal categories, demonstrating the effectiveness of EEG signals in emotion recognition.

## Conclusion

The results indicate that electroencephalography can be a viable method for recognizing human emotions. Further exploration in signal processing and data analysis is recommended. Understanding the capabilities of EEG technology is crucial for its advancement and potential applications in various fields.

## Acknowledgement

The authors express gratitude to their project guide and the Electronics department staff for their support and guidance. Special thanks are extended to teachers and friends for their assistance during the project.

## References

1. H. Zhang, S. Zheng, and J. Yuan, "A personalized TV guide system compliant with MHP," IEEE Trans. Consumer Electronics, vol. 51, no.2, May 2005, pp. 731-737.
2. A. Pentland and T. Choudhury, “Face recognition for smart environments," IEEE Computer, vol. 33, no. 2, Feb 2000, pp. 50-55.
3. K. Ho An and M. Jin Chung,“Cognitive Facial Analysis System for Future Interactive TV," IEEE Transactions on Consumer Electronics, Vol. 55, No. 4, November 2009, pp. 2271-2279.
