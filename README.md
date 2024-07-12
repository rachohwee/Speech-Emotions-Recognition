![image](https://github.com/user-attachments/assets/55d23d10-8e2f-42ed-9973-0d639c335bb7)# Speech-Emotions-Recognition

# Motivation 🫶🏼 
Individuals with Down syndrome often face several common challenges, or pain points, that can affect various aspects of their lives. Creating a system for identifying emotions through speech (Speech Emotion Recognition) can significantly benefit individuals with Down syndrome by addressing communication barriers and enhancing social interactions. By providing real-time feedback on emotional states, the system can aid caregivers and educators in offering timely support, reducing frustration, and improving behavioral management. Additionally, it can assist individuals in developing self-awareness and emotional literacy, ultimately fostering greater independence and social skills. This technology has the potential to significantly improve the quality of life for those with Down syndrome.

# Exploratory Data Analysis (EDA) ✍
1. Data Augmentation
- Adding Noise to the audio files
- Shifting audio
- Stretching audio

2. Resampling Techniques for imbalanced data
- SMOTE & ROS

# Results based on F1-Score Metrics
1. KNN: 0.5326
2. CNN: 0.8055
3. RNN: 0.7648

From the table above, it is evident that CNN has the highest performance measures. However, we will choose RNN as the best model. 

RNN has the ability to process sequential data and is commonly used for audio classification tasks. In addition, the performance measures for RNN did not deviate far from CNN, with a 4% difference. 

# Dataset(s) & Resources
1. Kaggle datasets:
- Crema-D: https://www.kaggle.com/datasets/ejlok1/cremad/data
- Toronto: https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess
- Ravdess: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio



