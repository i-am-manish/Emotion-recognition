# Emotion-recognition
with TFlearn and normal one


1- Regarding TF learn: 


    First, we use haar cascade to detect faces in each frame of the webcam feed.

    The region of image containing the face is resized to 48x48 and is passed as input to the ConvNet.

    The network outputs a list of softmax scores for the seven classes.

    The emotion with maximum score is displayed on the screen.

Run :
Download weights @ https://drive.google.com/uc?id=1rdgSdMcXIvfoPmf702UCtH6RNcvkKFu7&export=download  and put them in local directory. 

python3 singleface.py --for one face

python3 multiface.py --for multi faces


2- Regarding normal one:
