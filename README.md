# Mood Based Music Recommendation 
Machin Learning Project - A mood-based 
music recommendation system in which system was designed to 
judge the emotions of a person based on that we try to 
recommend music or song viva a third-party application 
(YouTube) made with Python programming language main 
packages were OpenCV, TensorFlow, SVM, Flask,numpy,Keras.

Let's break down the code and libraries being used:

Flask: Flask is a lightweight web framework for Python. It allows you to build web applications quickly and with minimal code. In this script, Flask is being used to create a web application.

render_template: This function is used to render HTML templates in Flask. It's often used to generate HTML pages dynamically by combining static HTML with dynamic data.

request: This module allows you to handle HTTP requests in Flask. It provides access to incoming request data such as form data, query parameters, and files uploaded by the client.

numpy (np): NumPy is a fundamental package for scientific computing with Python. It provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays efficiently. It's commonly used in numerical computing tasks.

cv2: OpenCV (Open Source Computer Vision Library) is an open-source computer vision and machine learning software library. It provides various tools and functions for image and video processing, including loading, manipulating, and analyzing images. In this script, cv2 is being used for image processing tasks.

keras.models: Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It allows for easy and fast prototyping of deep learning models. In this script, load_model is used to load a pre-trained Keras model saved in a file.

webbrowser: This module provides a high-level interface to allow displaying web-based documents to users. It can be used to open web browsers programmatically. In this script, it might be used to open a web browser window for the Flask application.
