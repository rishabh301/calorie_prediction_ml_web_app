<!DOCTYPE html>
<html lang="en">
<head>
   
</head>
<body>
    <h1>Calorie Burnt Predictor using Machine Learning</h1>
    <p>A simple web-based application that predicts the number of calories burnt based on user inputs like gender, age, height, exercise duration, heart rate, and body temperature.</p>
    <h2>🚀 Features</h2>
    <ul>
        <li>Predicts calories burnt using a pre-trained machine learning model.</li>
        <li>Interactive UI built with Streamlit.</li>
        <li>Easy input selection for users.</li>
        <li>Fast and accurate predictions.</li>
    </ul>
    <h2>🛠 Tech Stack</h2>
    <ul>
        <li><strong>Frontend:</strong> Streamlit</li>
        <li><strong>Backend:</strong> Python</li>
        <li><strong>Machine Learning:</strong> Pre-trained model using Pickle</li>
    </ul>
    <h2>📌 How to Run</h2>
    <pre><code>pip install streamlit numpy pickle-mixin</code></pre>
    <pre><code>streamlit run app.py</code></pre>
    <h2>🔹 Usage</h2>
    <p>Enter the required details in the input fields, click the <strong>Predict</strong> button, and get the estimated calories burnt.</p>
    <h2>📁 File Structure</h2>
    <pre><code>
    ├── app.py  # Main application file
    ├── newmodel.sav  # Pre-trained ML model
    ├── requirements.txt  # Required dependencies
    </code></pre>
    <h2>🎯 Example Code</h2>
    <pre><code>
import streamlit as st 
import pickle
import numpy as np
model = pickle.load(open('newmodel.sav', 'rb'))
...
    </code></pre>
    <h2>📢 Author</h2>
    <p>Developed by Rishabh Sharma</p>
</body>
</html>
