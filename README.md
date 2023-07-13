# Song-Recommendation-using-Facial-expressions
Recommending music based on your facial expressions using FER 2013 dataset and Sporify api
# Project Description:
The emotion recognition model is trained on FER 2013 dataset. It can detect 7 emotions. The project works by getting live video feed from web cam, pass it through the model to get a prediction of emotion. Then according to the emotion predicted, the app will fetch playlist of songs from Spotify through spotipy wrapper and recommend the songs by displaying them on the screen.
# Image Processing: 
The images were normalised, resized to (48,48) and converted to grayscale in batches of 64 with help of 'ImageDataGenerator' in Keras API.
Training took around 13 hours locally for 75 epochs with an accuracy of ~66 %
