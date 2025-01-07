Road Safety Index (RSI)

The Road Safety Index (RSI) is a machine learning-based program designed to predict the vulnerability of roads to accidents. It uses images of roads, processes them through machine learning models, and provides a safety score based on the road's features. The project combines computer vision, machine learning, and web technologies to visually predict and display the Road Safety Index through an interactive map interface.

Table of Contents

Overview

Technologies Used

Setup

How to Run

License

Acknowledgements

Additional Notes for VS Code Users

Extensions for Productivity

Overview

The Road Safety Index (RSI) aims to reduce road accident risks by providing predictions about road safety. By analyzing images of roads and classifying them based on their risk levels, RSI empowers individuals to make safer travel decisions.

Technologies Used

Machine Learning: For training models to analyze road images and assign safety scores.

Python: Backend programming language for machine learning and API handling.

Flask: Framework for creating the web application.

OpenCV: For processing road images and extracting features.

Leaflet.js: JavaScript library for displaying interactive maps.

HTML, CSS, JavaScript: For frontend web development.

Setup

Prerequisites

Before setting up the project, ensure you have:

VS Code installed.

Python 3.x installed.

pip (Python package manager) installed.

Steps to Setup

Clone the Repository

Navigate to the folder where you want to clone the project and run:

git clone https://github.com/Prakhar1980/Road-Safety-Index.git

Open the Project in VS Code

Navigate to the project directory:

cd Road-Safety-Index

Open the project in VS Code:

code .

Install Dependencies

Install the required dependencies listed in requirements.txt:

pip install -r requirements.txt

This will install all the necessary Python libraries for the project.

How to Run

Launch VS Code Integrated Terminal

Open the integrated terminal in VS Code by pressing Ctrl + `` (backtick) or navigating to View > Terminal.

Run the Flask App

Start the Flask application by running the following command:

python app.py

This will start the Flask development server locally.

Access the Application

Once the server starts, access the application in your browser by navigating to:

http://127.0.0.1:5000/

Upload Images

On the web page, upload images of roads. The system will analyze the images and provide a road safety score, displayed on an interactive map.

License

This project is distributed under the MIT License. See the LICENSE file for more details.

Acknowledgements

OpenCV: For image processing.

Leaflet.js: For creating interactive maps.

Contributors: Thanks to all contributors who have helped improve the project.

Additional Notes for VS Code Users

Linting and Formatting: Use the Python extension in VS Code to enable linting and formatting for Python files.

Install the Python extension.

Configure settings like auto-formatting (e.g., autopep8, black) for Python files.

Run/Debug: Use VS Code's built-in debugging features to run and test your Python code. Add breakpoints in your script and press F5 to start debugging.

