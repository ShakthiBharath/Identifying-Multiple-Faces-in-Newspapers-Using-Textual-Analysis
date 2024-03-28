# Identifying-Multiple-Faces-in-Newspapers-Using-Textual-Analysis
OpenCV excels in face detection with its speed, versatility, and real-time compatibility. Integration with LSTM networks achieves 87% accuracy in text processing, surpassing previous techniques. Empirical testing confirms its efficacy in joint face identification, addressing accuracy challenges.This project utilizes computer vision and natural language processing techniques to perform face recognition on images retrieved from news articles, and then summarizes the content of these articles using LSTM networks.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Results](#results)
6. [Dependencies](#dependencies)
7. [Contributing](#contributing)


## Introduction
The aim of this project is to demonstrate how face recognition and text summarization techniques can be combined to analyze news articles. It fetches articles related to a specified person's name, detects faces in the associated images, and then summarizes the article content using LSTM networks.

## Features
- Fetches news articles from the News API based on a specified person's name.
- Utilizes OpenCV for face detection and identification in retrieved images.
- Implements LSTM networks for text summarization of article descriptions.
- Visualizes the frequency of article publications using a bar graph.

## Setup
To set up this project, follow these steps:
1. Clone this repository to your local machine.
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Obtain an API key from News API and update it in the `main()` function of `main.py`.
4. Run the `main.py` script to execute the project.

## Usage
After setup, you can use this project by executing the `main.py` script and entering the name of the person you want to search for news articles about. The program will fetch relevant articles, detect faces in the associated images, and summarize the article content.

## Results
The project provides visualizations of the published dates of articles and displays the summarized content along with the associated images containing detected faces.

## Dependencies
- Python 3.x
- OpenCV
- NumPy
- Requests
- TensorFlow
- Matplotlib
- News API
- PIL
- Tabulate

## Contributing
Contributions to this project are welcome! Feel free to open issues or pull requests with any improvements or suggestions.
Feel free to contact me @psbharath897@gmail.com


