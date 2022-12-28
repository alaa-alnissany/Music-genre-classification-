# Music genre classification
This project is a part of the [SHAI](https://shaiforai.com/) machien learning internship at [Amman, Jordan](https://goo.gl/maps/hSGhVMzNeCMcjyYG9).

#### Status: [Completed]

## Introduction
In this project we will try to figure the genre of music using Machein learning models by a specific list of features which presented by [Music genre classification dataset](https://www.kaggle.com/competitions/shai-training-level-1-b/data), it's a multiclass classification problem.

![Music](https://github.com/alaa-alnissany/Music-genre-classification-/19438c50aea5bd8a6f452446b0ea4090-563x368.jpg?raw=true)

## Team Members

**Team Leader : [Alaa Alnissany](https://github.com/alaa-alnissany) Electronic-Systems Engineer from Higher Institute for Applied Sciences and Technology**

#### Other Members:

|Name     |  position   | 
|---------|-----------------|
|[Saba Salah](https://github.com/sabasalah)| Master's in Artificial Intelligence and Robotics at Islamic Azad University        |
|[Asmaa Laila](https://github.com/asmaalaila/) |     Telecommunications Engineer graduated from Damascus University    |

### Used Methods
* Descriptive Statistics
* Data Visualization:
   * Box plots
   * Scatter plots
* Features Importance:
   * Chi-2 test
   * Mutual information theory
   * Based on models' features importance
   * Linear correlation  
* Outliers Handling:
   * Quartile-transform
*  balancing data (Data augmentation) using:
   * Synthetic Minority Oversampling Technique SMOTE method.
   * SMOTE-Tomek Links method.
* Machine Learning:
   * LGBM
   * XGB
   * SVM
   * Random Forest
   * Extra Trees
   * Cat-Boost

### Technologies
* Python
* Google colaboratory
* Pandas
* Numpy
* Seaborn
* Scikit learn
* Imblearn
* Lazy predict
* Catboost

## Project Description
In this project we deal with so many features, let's take a brief look on them:
* **artist name**: Name of the Artist.
* **track name**: Name of the Track.
* **popularity**: The higher the value the more popular the song is.
* **danceability**: Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm
* **energy**: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.
* **key**: The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on..
* **loudness**: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative
* **mode**: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
* **speechiness**: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
* **acousticness**: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
* **instrumentalness**: Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
* **liveness**: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
* **valence**: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
* **tempo**: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
* duration in milliseconds :Time of the song
* **time_signature** : a notational convention used in Western musical notation to specify how many beats (pulses) are contained in each measure (bar), and which note value is equivalent to a beat.

Where the target is:
* **Class**: Genre of the track
