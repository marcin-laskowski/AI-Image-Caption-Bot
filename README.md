# AI-Image-Caption-Bot
The goal of the project was to develop a model that generates a caption that best describes the input image.This initiative can aid with Google Image search, self-driving automobiles, and providing assistance to the blind. Python is used to create the project. The project was built using the Keras (Tensor flow), numpy, matplotlib, and pandas libraries. Flask was utilised as the framework.

### Project Deployed on heroku -
Link - https://peaceful-plateau-34289.herokuapp.com   

# Cloud Storage used
Cloudinary
# Model Pipeline -
Data collection -> Data cleaning -> Loading the training set -> Data preprocessing (images and caption) -> Using Generator function to prepare data in batches ->
word embedding -> Model Architecture

# Developer -
To run in development mode -
```
$ git clone https://github.com/Apoorvgarg-creator/AI-Image-Caption-Bot.git
$ export FLASK_APP=wsgi
$ flask run
```
