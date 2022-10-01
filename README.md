Epilepsy is a neurological disorder in which brain activity becomes abnormal, causing
seizures or periods of unusual behavior, sensations and sometimes loss of awareness. An
epileptic seizure is a transient occurrence of signs and/or symptoms due to abnormal
excessive or synchronous neuronal activity in the brain. Thus, epilepsy is a disorder of the
brain characterized by an enduring predisposition to generate epileptic seizures and by the
neurobiologic, cognitive, psychological, and social consequences of this condition. The
World Health Organization (WHO) estimated 50 million of the world’s population today
are afflicted with epilepsy. Due to unexpected seizure times, epilepsy has a strong
psychological and social effect. Accurate seizure prediction is based on the research of
complex electroencephalogram (EEG) signals.

In this project, the convolutional neural network is used to extract the significant spatial
features from EEG signals and classification task is performed on the extracted features
to detect the onset of a seizure. The network is trained and tested using MATLAB. An
accuracy of 95.09% is achieved.



This repository contains three files: 
epilepsy2.m ----> Preprocessing of EEG Signals taken from Bonn Epilepsy dataset is done. Preprocessing step involves FIR Bandpass Filtering, DWT, Spectrogram generation

features_extraction.m -----> Features such as GradCam and Occlusion Sensitivity are executed to understand what's happening inside the CNN in each layer

transfer_learning_new.m ----> Building CNN Model AlexNet for classification: Seizure/Healthy

