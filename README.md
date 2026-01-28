# FaceMatch-Celebrity-Look-alike-with-Computer-Vision
Celebrity Look-alike with Computer Vision
Discover which celebrity you resemble the most using the power of Computer Vision!

This project uses the face_recognition library (built on dlib’s deep learning models) to detect, analyze, and compare faces with a database of celebrity images.

Key Features

Detects faces from uploaded images with high accuracy.

Compares your facial features with a database of celebrity images.

Finds the closest matching celebrity using Euclidean distance between face encodings.

Displays your image side-by-side with the matched celebrity.

Fully implemented in Python with face_recognition and matplotlib.

Practical Impact

Fun and Engagement: Provides users a personalized entertainment experience by showing their celebrity look-alike.

Business Applications:

Marketing & Advertising: Brands can create interactive campaigns using celebrity look-alike filters to increase user engagement.

Retail & Fashion: Virtual try-ons or customized recommendations based on celebrity facial features.

Entertainment & Media: Apps for fans to see which celebrity they resemble, boosting engagement on social media platforms.

Already in Use: Similar technology is used in apps like Snapchat, TikTok, and Instagram filters to enhance user interaction and gamify experiences.

Learning Tool: Demonstrates practical applications of face recognition in real-world scenarios.

Foundation for Advanced Projects: Can be extended to real-time video streams, attendance systems, identity verification, or personalized recommendation systems.

How It Works

Upload your image to the designated folder.

Load a set of celebrity images with precomputed face encodings.

Compare your face with all celebrity faces using face_recognition and find the closest match.

Display your image alongside the matched celebrity.

Share your results with friends or on social media!

Dependencies

Python 3.x

face_recognition

dlib

numpy

matplotlib

Getting Started

Clone this repository.

Install dependencies:

pip install face_recognition numpy matplotlib


Upload your image to the folder lookalikeceleb.

Run the script face_match.py.

See which celebrity you look like!


Example output with 2 different pictures of the same person but the output is the same....highlighting the accuracy of the model in identifying image features



<img width="652" height="350" alt="image" src="https://github.com/user-attachments/assets/eff96551-23bd-4326-97ea-3ab666af3b56" />


<img width="569" height="352" alt="image" src="https://github.com/user-attachments/assets/17963211-de24-43ff-ae12-57fbc66c2406" />


