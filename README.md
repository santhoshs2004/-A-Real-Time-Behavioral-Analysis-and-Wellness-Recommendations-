## Title of the Project
A Real-Time Behavioral Analysis and Wellness Recommendations 


## About
<!--Detailed Description about the project-->
Human Activity Recognition (HAR) plays a pivotal role in accurately interpreting human actions and emotions, with significant applications in medical and healthcare domains. This project aims to leverage cutting-edge deep learning techniques to enhance patient care through real-time analysis of human behavior and mood. By utilizing Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks, the project provides an innovative solution for monitoring and analyzing emotional of the people. The combination of CNNs and LSTMs enables the creation of a real-time system capable of detecting and analyzing both emotional and physical states of an individual. This system can track changes in mood, identify signs of distress, and provide immediate recommendations or alerts to healthcare providers for timely intervention.

## Features
<!--List the features of the project as shown below-->
1) Mood Detection and Emotional State Analysis.
2) High Accuracy and Precision.
3) Convolutional Neural Networks (CNNs) for Feature Extraction.
4) Long Short-Term Memory (LSTM) Networks for Sequential Analysis.
5) Wellness Recommendation based on the acquired emotions.

## Requirements
<!--List the requirements of the project as shown below-->
1) Hardware Requirements:
Camera or Video Capture Device: To record and capture video frames for human activity recognition.
Computer with a GPU: Required for running deep learning models (CNNs and LSTMs) efficiently.

2) Software Requirements:
Operating System: Windows, macOS, or Linux (depending on your preference).
Programming Languages: Python (for machine learning and video processing).
Libraries/Frameworks:
TensorFlow / Keras: For building and training deep learning models (CNNs and LSTMs).
OpenCV: For video processing and real-time frame extraction.
NumPy and Pandas: For handling data and performing basic operations.
Matplotlib / Seaborn: For data visualization of the results.
Scikit-learn: For any additional machine learning tasks like classification or regression.

3) Data Requirements:
Video Datasets: Datasets of human activities and emotions -FER2013 datasets.

4) Modeling Requirements:
CNN for Feature Extraction: To extract spatial features from video frames.
LSTM for Sequential Analysis: To analyze the temporal relationships of human activities over time.
Emotion Detection Algorithms: For interpreting emotional states from actions.

## System Architecture
<!--Embed the system architecture diagram as shown below-->
![Screenshot 2024-11-13 004839](https://github.com/user-attachments/assets/18bfd41b-d9d6-4b3a-b6fc-9e3be150b7fc)




## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Evaluation of the Model


![Screenshot 2024-11-13 005330](https://github.com/user-attachments/assets/ea775aae-811c-4b8b-91d7-41203ab36354)


![Screenshot 2024-11-13 005225](https://github.com/user-attachments/assets/fe4d9f58-9b0a-4353-9df4-1abc3801da2b)


![Screenshot 2024-11-13 005250](https://github.com/user-attachments/assets/477f1ee8-4fee-4b4e-975c-1c03445c5f28)


![Screenshot 2024-11-13 005347](https://github.com/user-attachments/assets/0067a212-4bf4-456e-9db5-d3a66b5a3584)


#### Output2 - Wellness Recommendation


![Screenshot 2024-11-13 005427](https://github.com/user-attachments/assets/2060ae75-a8f2-4d33-9048-e79944885817)




![Screenshot 2024-11-13 005459](https://github.com/user-attachments/assets/d940312d-854b-45ed-ab10-9edb360595bb)




Detection Accuracy: 84.6% (nearly 85%)
Test Loss: 0.487 
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
<!--Give the results and impact as shown below-->
This model will enable real-time tracking of patients’ moods and behaviors, identifying patterns over time. By continuously analyzing these trends, it can deliver wellness recommendations tailored to individual emotional needs, like stress-relief exercises or sleep improvements.It will ensure reliable, real-time insights into patient behavior, enhancing the quality of monitoring.

This project stands to significantly impact healthcare by enabling real-time patient monitoring, personalized care, and a deeper understanding of mental and emotional health, ultimately leading to better patient outcomes and streamlined caregiving.



## Articles published / References
1) E. Ghaleb, M. Popa and S. Asteriadis, “Multimodal and Temporal Perception of Audio-visual Cues for Emotion Recognition," 8th International Conference on Affective Computing and Intelligent Interaction, 2019, pp. 552 -558.
2) Z. Rzayeva and E. Alasgarov, “Facial Emotion Recognition using Convolutional Neural Networks,” IEEE 13th International Conference on Application of Information and Communication Technologies 2019, pp. 1 -5.
3) S. R. Livingstone, F. A. Russo, “The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS):” A dynamic, multimodal set of facial and vocal expressions in North American English. PLoS ONE Vol. 13 No. 5, 2018, e0196391.
4) S. Bursic, G. Boccignone, A. Ferrara, A. D’Amelio, R. Lanzarotti, “Improving the Accuracy of Automatic Facial Expression Recognition in Speaking Subjects with Deep Learning.” Appl. Sci. Vol. 10, No. 11, 2020, 4002.
5) M. S. Hossain, G. Muhammad, “Emotion recognition using deep learning approach from audio–visual emotional big data.” Information Fusion Vol. 49, 2019, pp. 69–78.



