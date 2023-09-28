# SCZ-SCAN: Schizophrenia Detection using Separable Convolution Attention Network

## Overview

Schizophrenia (SCZ) is a severe neurological and physiological syndrome that distorts a patient's perception of reality, resulting in symptoms such as hallucinations, delusions, aberrant behavior, and disordered thinking. Detecting SCZ traditionally relies on laborious and time-consuming verbal and visual tests, which can be prone to errors. In response, this project introduces an automated model for SCZ detection using electroencephalogram (EEG) data and a novel deep learning architecture known as SCZ-SCAN.

## Methodology

SCZ-SCAN leverages Convolutional Neural Networks (CNNs) and attention mechanisms to analyze EEG data and detect signs of schizophrenia. The model processes 2-D scalogram images generated from continuous wavelet transform (CWT) of EEG data. Key components of SCZ-SCAN include:

- Depth-wise separable convolution: This technique contributes to a lightweight network architecture, enhancing efficiency.
- Attention networks: These focus on important features, reducing unnecessary computations by filtering out irrelevant information.

## Results

The SCZ-SCAN model has demonstrated remarkable performance in SCZ detection:

- Average classification accuracy of 99% on the IBIB-PAN dataset.
- Average classification accuracy of 95% on EEG data from basic sensory tasks in the SZ dataset.

To further validate its effectiveness, statistical hypothesis testing was conducted using Wilcoxon's Rank-Sum test, which showed that SCZ-SCAN statistically outperforms nine state-of-the-art methods in SCZ detection.

## Getting Started

To get started with SCZ-SCAN, follow these steps:

1. **Data Preprocessing**: Prepare your EEG data and transform it into 2-D scalogram images using continuous wavelet transform (CWT).

2. **Model Training**: Train the SCZ-SCAN model on your preprocessed EEG data. You can use the provided codebase or adapt it to your specific dataset.

3. **Evaluation**: Evaluate the model's performance using standard evaluation metrics for SCZ detection, such as accuracy, precision, recall, and F1 score.

4. **Integration**: Incorporate the SCZ-SCAN model into your clinical or research workflow for automated SCZ detection.

## Citation

If you use SCZ-SCAN in your research or applications, please consider citing our work [link to your publication or preprint].

## Acknowledgments

We would like to express our gratitude to [List of contributors or institutions] for their contributions and support in the development of SCZ-SCAN.

## Contact

For questions, issues, or collaboration opportunities, please contact [Your Name] at [Your Email Address].

