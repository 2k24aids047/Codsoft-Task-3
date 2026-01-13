TASK 3: Image Captioning AI
Project Description

This project is an Image Captioning AI that generates meaningful captions for images.
It combines computer vision concepts and natural language generation to analyze images and describe them in simple sentences.

The system analyzes image properties like colors, brightness, texture, and composition, detects possible objects, and then generates an appropriate caption.

Features

Upload an image through a web interface

Automatically analyzes the image

Detects possible objects such as:

Dog

Cat

Person

Car

Food

Nature scenes

Generates a descriptive caption

Displays detected objects with confidence scores

Shows processing time and analysis details

User-friendly web UI built using Flask

Technologies Used

Python

Flask (for web application)

Pillow (PIL) (for image processing)

HTML, CSS, JavaScript (for frontend)

How It Works

User uploads an image through the browser.

The image is processed on the server.

Image features such as:

Dominant colors

Brightness and contrast

Texture

Image composition
are analyzed.

Possible objects are detected based on image characteristics.

A suitable caption is generated using predefined templates.

The caption and analysis are displayed to the user.

How to Run the Project

Make sure Python is installed.

Install required libraries:

pip install flask pillow


Run the program:

python image_captioning_improved.py


Open your browser and go to:

http://localhost:5000


Upload an image and generate a caption.

Example Output

Caption:
“A cute brown dog sitting outdoors with good lighting.”

Detected Objects:
Dog (85%), Animal (78%)

Confidence:
90%

Project Structure
Task3/
 ├── image_captioning_improved.py
 └── README.md

What I Learned

Basics of image processing

Feature extraction from images

Object detection using rule-based logic

Caption generation using templates

Building a Flask-based web application

Integrating frontend and backend
