# Emoji-creation-using-real-time-vedio-capture
The purpose of emotion recognition systems is the appliance of emotion related knowledge in such a way that human computer communication will be enhanced and furthermore the user's experience will become more satisfying. By enabling computers to sense the emotional state of the user and react accordingly, this communication can be renovated to a satisfying one. There can be specialised systems that can be developed and can be used for even more serious problems like in various medical applications aggression detection, stress detection, autistic disorder, asperger syndrome, hepatolenticular degeneration, frustration detection.
In the below steps will build a convolution neural network architecture and train the model on FER2013 dataset for Emotion recognition from images.

Download the dataset from the above link. Extract it in the data folder with separate train and test directories.
Make a file train.py and follow the steps:
1. Imports:
2. Initialize the training and validation generators:
3. Build the convolution network architecture:
4. Compile and train the model:
5. Save the model weights:
6. Using openCV haarcascade xml detect the bounding boxes of face in the webcam and predict the emotions:

Code for GUI and mapping with emojis
Create a folder named emojis and save the emojis corresponding to each of the seven emotions in the dataset.
