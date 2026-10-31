# Laser-based-Heart-Health-Monitoring-System-on-MATLAB-Simulink.
My project is **Laser-Based Heart Health Monitoring System Using Machine Learning on MATLAB Simulink**. It was a team project developed as part of our Digital Signal Processing subject.

The main objective of this project was to simulate a non-invasive heart monitoring system that can estimate heart rate from a pulse signal and classify the pulse condition using machine learning.

Our project is based on a technique called **Photoplethysmography, or PPG**. The basic principle is that when light interacts with human tissue, changes in blood volume during each heartbeat cause variations in the detected light intensity. These variations can be represented as a pulse waveform.

We implemented the system using MATLAB and Simulink. In Simulink, we used a pulse generator to represent heartbeat activity, a transfer function to model the tissue response, and a noise block to simulate real-world disturbances. We then used a low-pass filter to reduce noise and obtain a cleaner signal.

After that, we exported the processed signal to MATLAB, where we performed peak detection to calculate heart rate in beats per minute. We also extracted statistical features such as mean, standard deviation, maximum, and minimum values from the signal.

Next, we used a **Support Vector Machine, or SVM, classifier** to classify the pulse condition into three categories: normal, bradycardia, and tachycardia.

We also included additional analysis such as heart rate variability, signal quality evaluation, risk assessment, and simulated ECG-like waveform visualization.

In our reported simulation results, the estimated heart rate was approximately 72.37 BPM, and the system classified the condition as normal with a low-risk assessment.

Through this project, I gained practical understanding of digital signal processing, signal filtering, feature extraction, MATLAB Simulink modeling, and the application of machine learning to biomedical signals.

Currently, the system is simulation-based. As future improvements, we can integrate real optical sensing hardware and validate the model using real medical datasets to develop a more reliable real-time monitoring system.
