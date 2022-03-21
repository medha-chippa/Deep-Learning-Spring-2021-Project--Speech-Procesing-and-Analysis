# Deep-Learning-Spring-2021-Project--Speech-Procesing-and-Analysis
This project is centered around the idea of processing and analyzing speech data. We propose 
to carry two tasks viz. Gender identification and Speaker Recognition. In other words, we propose to 
carry out gender identification and speaker recognition based on the acoustic features of the features 
extracted. A corpus of audio files (speech data) will be processed, this would result in the generation 
of spectrograms (image files). The nature of each of these audio files would be studied through the 
use of visualization techniques. Feature extraction would then be carried to extract spectral
features/acoustic features viz. MFCCs, Zero crossings etc. The resultant spectral features would then 
be supplied to Machine Learning models and Deep Learning models to carry out gender identification 
and speaker recognition.

# Methods
• Extensive visualization of the audio corpus collected using libraries like librosa, matplotlib, 
pandas, seaborn etc.

• The extraction of spectral and other speech related features from the corpus using the librosa 
library.

• Pre-Processing of these spectral features

• The Construction of gender identification and speaker recognition models through the use of 
Neural Networks and other relevant machine learning models 

• Deployment of the gender identification model on the audio sourced from a live subject.

# Approach

Differences in frequency, acoustic variations etc. constitute the critical aspects of an audio 
specimen that are used for the purpose of carrying out gender identification and speaker recognition. 
The following is the workflow of our project:

![image](https://user-images.githubusercontent.com/55135185/159243708-6c625303-9623-452a-858a-e2a58c29cb84.png)

# Results

![image](https://user-images.githubusercontent.com/55135185/159244306-c0a2ab83-838d-478c-a23d-26eaa36bd33f.png)

![image](https://user-images.githubusercontent.com/55135185/159244525-3dad0f21-6a85-463f-aa87-46c77a6ed64f.png)

# Deployment:

The trained gender identification neural network model is deployed on a set of audio files 
collected from live specimens. 
3 files are collected, 2 of them being male audio specimens and 1 being a female audio 
specimen

![image](https://user-images.githubusercontent.com/55135185/159244888-1e9e5a90-bd32-4355-9f4c-fbf74e51905a.png)


