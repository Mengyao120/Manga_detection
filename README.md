# Manga_detection
## Introduction 
Manga Detection is a manga-version of 'Shazam app' aiming at discovering the manga name through facial recognition based on a given input manga image. Manga refers to the comics or graphic novels created in Japan.

## Structures 
![Picture1](https://user-images.githubusercontent.com/51313297/64520517-33189380-d2ab-11e9-9a58-ec8eddea6513.png)
### The prototype of Manga Detection consist of two CNN models: 

Face detection model: 'Face detection model.ipynb'

Face classifer model: 'Face classifier model.ipynb'

## Pre-trained model:

Face detection model: 'Face_recog_model_2.h5'

Face classifer model: 'Manga_face_model_2.h5'

## Demo
### A simple demonstration for the application of the classifier model are included:
Video:'demo_video.mp4', weblink: https://youtu.be/6QFuhF5hayM

A jupyter notebook for you to test: 'Demo_Face_classfier_model.ipynb'

## Data source
Manga 109: Manga109 compiled by the Aizawa Yamasaki Laboratory is composed of 109 manga volumes drawn by professional manga artists in Japan for use in academic research on the media processing of manga. 

## Training images
Link for images:https://drive.google.com/file/d/1ChAMylnlyDyz9OoWIbChFubtJjleEsbb/view?usp=sharing

Original manga volumes: folder 'simple model'

Hand-labelled images: folder 'cropped'

Demo purpose images: folder 'demo'
