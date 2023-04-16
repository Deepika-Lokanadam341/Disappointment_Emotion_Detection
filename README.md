# Disappointment_Emotion_Detection
In this example code, we first load the pre-trained model from the model.h5 file and define a list of emotion labels. We then generate some test data (which you would replace with your own data) and use the model.predict method to make predictions on this data. We get the index of the predicted emotion with the highest probability using np.argmax, and map this index to the corresponding emotion label using the emotions list. Finally, we check if 'disappoitment' is in the predicted labels and print the appropriate output.

Note that the specifics of this code may depend on the details of your pre-trained model and the data you are working with.
