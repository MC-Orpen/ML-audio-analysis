# Application of ML in audio detection and analysis
The aim of this project is the application of machine learning techniques to the real-world problem of audio detection and analysis. The first section classified audio segements depending on the intonations/tones. The second section attempted to predict the student who recorded the audio segement out of a class of 184 students.

### Project introduction
The class contained 184 students, each of whom was required to make a series of voice recordings saying a series of numbers, which are shown below. The participant had to take a recording in four different intonations/tones, which were then catergorised accordingly. The different tones used were "question", "neutral", "bored" and "excited".

### Intontation prediction
In the first section, different audio features are extracted and processed, including MFCCs, zero crossing rates and spectral centroids. A basic solution used a variety of classification models to predict the intontation of audio sequences.

### Prediction of student
An advanced solution was created, using neural networks to try and match the voice to the student. Four different neural networks were trained and validated, with the optimal neural network able to successfully predict the student from the class 35% of the time.
