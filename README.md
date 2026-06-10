Medicinal Plant Identification Web Application that uses Machine Learning to classify plants from images.

Project Description:
This is a Flask web application that combines:

Deep Learning Model (mediplant.h5) - A CNN (Convolutional Neural Network) trained to identify medicinal plants
Web Interface - Flask backend with HTML templates for user interaction
Plant Database - CSV file (plantinfo.csv) containing information about identified plants
Tech Stack:
Backend: Flask (Python)
ML/AI: TensorFlow, Keras (trained model:
Frontend: HTML templates + PIL for image processing
Deployment: Heroku (Procfile configured)
Development: Jupyter Notebook for experimentation
Key Features:
User Authentication - Login page (login.html)
Image Upload & Classification - Submit form for plant image analysis
Plant Information Display - Shows identified plant details from CSV
Web Pages:
/ - Login page
/home - Home page
/index - Main application page
/submit - Image upload & prediction
/Contact-us - Contact page
Code You Pushed:
Jupyter notebook with Flask app code
Pre-trained ML model (mediplant.h5)
Plant information database (plantinfo.csv)
HTML templates for web UI
Procfile for Heroku deployment