# Flask App Cat Dog Classifier using CNN

The problem Statement:-

Given a set of labeled images of cats and dogs, a machine learning model is to be learnt and later it is to be used to classify a set of new images as cats or dogs.

Classification of images between two class cat and dog using CNN with image augmentation .
We are using image augmentation to increase the amount of training data using augmentation by using from keras.preprocessing.image import ImageDataGenerator

Data - https://www.kaggle.com/c/dogs-vs-cats

<h2>Dependencies</h2>
• Jupyter notebook</br>
• Tensorflow 1.10</br>
• Python 3.6</br>
• Matplotlib</br>
• Seaborn</br>
• Scikit-Learn</br>
• Pandas</br>
• Numpy</br></br>


First we build the build and train the model and save it. We then import this saved model to be used in our flask app.


For this project, we used pre-trained model MobileNetV2 from keras. MobileNetV2 is a model that was trained on a large dataset to solve a similar problem to this project, so it will help us to save lots of time on buiding low-level layers and focus on the application.

Keras documentation for MobileNetV2 - https://keras.io/api/applications/mobilenet/

The model has the accuracy of 97.79 % for the train dataset and 97.32 % for the test dataset.
