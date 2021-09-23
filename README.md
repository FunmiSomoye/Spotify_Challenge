# Spotify_Challenge
Project at Turing College | June 2021
<div><img style="width: 80%; " src="https://upload.wikimedia.org/wikipedia/commons/1/14/Iyyaka_Nastain_QR-Code_Spotify_Black.png" /></div>


## Sprint 3: Intro to Modeling
The goal was to analyze some popular songs from Spotify. The dataset contains a number of variables that describe the songs, which would be used to predict which genre it belongs to. 

### Background

The dataset can be found [from Kaggle](https://www.kaggle.com/insiyeah/musicfeatures) (`data.csv`)

### Requirements

* Perform basic EDA.
* Perform dimensionality reduction on song features, verify data separability by genre (PCA and/or t-SNE).
* Infer genre using song features with logistic regression.
* Cluster songs by features. Generate lists of 5 of similar songs. Verify their similarity by actually listening to some of cluster items on Youtube / Spotify / any other streaming platform.

### Summary and Findings after Analysis

Having 10 music Genres to predict: <br/>
* The different genres showed clear differences in distibution when assessed across the frequency content of its spectrum.
* The Kmeans clustering algorithm was best able to group the music files into 3 genres.
* The Logistic Regression model was best able to predict Blues, Jazz and Metal, music, more than the others.

##### Python Libraries Used / Explored

``` Pandas ```
``` Seaborn ```
``` Kmeans ```
``` PCA ```
``` Standard Scaler ```
``` Power Transformer ```
``` Label Encoder ```
``` Pipeline ```
``` Logistic Regression ```
``` metrics ```

## License
The MIT License - Copyright (c) 2021 - Oluwafunmilayo Somoye
