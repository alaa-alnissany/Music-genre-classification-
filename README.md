# Music-genre-classification-
This project is a part of the [SHAI](https://shaiforai.com/) machien learning internship at [Amman, Jordan](https://goo.gl/maps/hSGhVMzNeCMcjyYG9).

#### Status: [Completed]

## Introduction
In this project we will try to figure the genre of music by a specific list of features which presented by [Music genre classification dataset](https://www.kaggle.com/competitions/shai-training-level-1-b/data), it's a multiclass classification problem.

### Partners
* Saba Salah Master's in Artificial Intelligence and Robotics at Islamic Azad University.
* Asmaa laila Telecommunications Engineer graduated from Damascus University.

### Methods Used
* Descriptive Statistics
* Data Visualization
* Features Importance
* Outliers Handling
* Machine Learning

### Technologies
* Python
* Pandas, Numpy, seaborn, scikit learn, imblearn
* Catboost

## Project Description
in this project we deal with so many features, let's take a breif look on them:
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
where the target is:
* **Class**: Genre of the track

## Needs of this project
- data processing/cleaning
- statistical modeling

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Contributing DSWG Members

**Team Leads (Contacts) : [Alaa Alnissany](https://github.com/alaa-alnissany)(@alaa-alnissany)**

#### Other Members:

|Name     |  Slack Handle   | 
|---------|-----------------|
|[Saba Salah](https://github.com/sabasalah)| @sabasalah        |
|[Asmaa Laila](https://github.com/asmaalaila/) |     @asmaalaila    |

## Contact
* If you haven't joined the SF Brigade Slack, [you can do that here](http://c4sf.me/slack).  
* Our slack channel is `#datasci-projectname`
* Feel free to contact team leads with any questions or if you are interested in contributing!
