## Gender_and_age_detection_common_voice_dataset_audio_processing
##### Created an age and gender detection system using audio data
The project uses the [common voice dataset](https://www.kaggle.com/datasets/mozillaorg/common-voice) which is a corpus of speech data read by some users on the common voice website. The dataset has a very rich metadata. Here in this project we used only the age and gender attributes among the many other attributes. 
The audio file were first converted from mp3 to wav file extension which is more convinent file type while preprocessing audio data. The features were then extracted from these audio file using MFCC feature extractor, which gave us 30 independent features which were then feature scaled. The dataset was then trained on various algorithms, the best results were given by
1) For gender detection: Support Vector Machine 
    F1_score: 0.952
    accuracy_score: 0.93
2) For age detection: K Nearest Neighbor
    F1_score: 0.7962
    accuracy_score: 0.7957
