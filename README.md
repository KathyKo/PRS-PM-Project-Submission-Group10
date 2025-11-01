# PRS-PM-Project-Submission-Group10

**Project Submission: Group 10** 

**Pattern Recognition Systems-2025-Jul-Nov-AIS07FT-Group10 - Motion Analysis** 

------------------------------------
## **SECTION 1: EXECUTIVE SUMMARY**

Physical exercise is crucial for health, but incorrect execution in gyms often leads to injuries and reduced training effectiveness.   
To address this, our project introduces motion analysis system designed to serve as an intelligent assistant for fitness training

This system is built upon the **Fit3D dataset** and integrates two core components:

**Autoencoder for Motion Feature Learning:** Employs an autoencoder trained in an unsupervised fashion to learn a compact and discriminative latent representation of motion features derived from the SMPL-X parameters.

**GRU-based Motion Classification Model:** Applies GRU to capture the temporal dependencies inherent in sequential pose data. GRU units effectively capture temporal continuity and repetition patterns in exercises such as push-ups or lunges, outperforming static classifiers on time-dependent features.

The project integrates these into a runnable workflow that provides corrective feedback through visual and textual cues. The resulting system achieves high accuracy in recognition and reliable error detection, demonstrating technical effectiveness and user interpretability. This work highlights the potential of machine learning to enhance personal fitness, prevent injuries, and power applications in smart gyms, remote physiotherapy, and wearable fitness devices.


## **SECTION 2: PROJECT CONTRIBUTION**

| Name         | Student ID | Work Items | Email              |
|--------------|------------|-------------|--------------------|
| **Jin Keyi** | A0276819L  | • Data preprocessing and feature extraction from Fit3D (SMPL-X: orientation, pose, translation).<br>• Built motion recognition models using LSTM.<br>• Tested MediaPipe for keypoint extraction and checked compatibility.<br>• Handled normalization, sequence alignment, and dataset balancing.<br>• Evaluated models with accuracy, precision, recall, and F1-score. | e1133134@u.nus.edu |
| **Ko Hung-Chi**  | A0327344E  |Synthesized  research and team results into the project report| e1539175@u.nus.edu |
| **Sun Yuchen**   | A0326248B  | Train Auto_encoder model, using 4D-humans(SMPL-X) to extract key features, motion corecction and model validation| e1538079@u.nus.edu |
| **Zhang Yuxuan** | A0285664N  | Contributions ... | e1216649@u.nus.edu |
| **Zhao Jiahui**  | A0329852U  | Focused on test-set preprocessing, 3D motion tracking, visualization, and model evaluation.| e1554179@u.nus.edu |




## **SECTION 3: VIDEO OF SYSTEM & USE CASE DEMO**

Refer to YouTube link : https://youtu.be/oTbP0CWLxPc


## **SECTION 4: PROJECT REPORT / PAPER**

Refer to `ProjectReport/Project_Report.pdf`


