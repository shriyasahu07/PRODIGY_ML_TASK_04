Project File Descriptions: 
train_model.ipynb: This notebook handles the training of the CNN model for hand gesture recognition.It includes data loading, preprocessing, model architecture (using Keras), training, and saving the final model as gesture_model.h5.

gesture_model.h5: This is the trained deep learning model file saved after training in train_model.ipynb.It contains the weights and structure of the CNN model used to recognize hand gestures.

evaluate_model.ipynb: This notebook evaluates the performance of the trained model on the validation dataset.It includes preprocessing, loading the model, making predictions, and printing a classification report with accuracy, precision, recall, and F1-score.

predict_gesture.ipynb: Allows you to predict the class of a single gesture image using the trained model.You can input an image file (like a frame from the dataset) and get the predicted gesture label.

live_webcam_predict.ipynb: A notebook for real-time gesture recognition using your webcam.It captures frames from the webcam, preprocesses them, and uses the model to predict and display the gesture live on-screen.


