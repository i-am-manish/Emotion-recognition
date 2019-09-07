# Emotion-recognition
with TFlearn and normal one


1- Regarding TF learn(TFlearn folder): 


    First, we use haar cascade to detect faces in each frame of the webcam feed.

    The region of image containing the face is resized to 48x48 and is passed as input to the ConvNet.

    The network outputs a list of softmax scores for the seven classes.

    The emotion with maximum score is displayed on the screen.

Run :
Download weights @ https://drive.google.com/uc?id=1rdgSdMcXIvfoPmf702UCtH6RNcvkKFu7&export=download  and put them in local directory. 

python3 singleface.py --for one face

python3 multiface.py --for multi faces
![alt text](https://github.com/i-am-manish/Emotion-recognition/blob/master/Screenshot%20from%202019-09-07%2018-20-29.png)




2- Regarding normal one:

just execute emotion.py file 
![alt text](https://github.com/i-am-manish/Emotion-recognition/blob/master/Screenshot%20from%202019-09-07%2018-18-13.png)
