# Emotion Detection Web Application

## Introduction

Welcome to the Emotion Detection Web Application final project.

This project demonstrates the development and deployment of an emotion detection application using the Watson AI / Watson NLP libraries and the Flask web framework.

The application analyzes a user's text input and identifies the emotions expressed in the statement, including **anger, disgust, fear, joy, and sadness**.

## Emotion Detection

Emotion detection goes beyond basic sentiment analysis by identifying specific emotions expressed in text.

This type of technology can be useful in applications such as:

* AI-based recommendation systems
* Chatbots
* Customer feedback analysis
* Text classification
* Customer service applications

In this project, Watson NLP is used to analyze the input text and determine the emotions associated with it.

## Project Repository

The original project repository provided for this course is:

https://github.com/ibm-developer-skills-network/oaqjp-final-project-emb-ai

This project was cloned and then pushed to my own GitHub repository for development and deployment purposes:

https://github.com/riya1508-hub/oaqjp-final-project-emb-ai

## Project Tasks

### Task 1: Clone the Project Repository

The original project repository was cloned to the local development environment.

The project was then pushed to my own GitHub repository so that it could be developed and deployed using the Cloud IDE.

### Task 2: Create an Emotion Detection Application

The Watson NLP library was used to develop an emotion detection application.

The application accepts a text statement as input and analyzes it to identify the emotions expressed in the statement.

### Task 3: Format the Output

The emotion detection results are formatted in a clear and user-friendly way.

The application displays the detected emotions and their corresponding scores.

The application also identifies the dominant emotion from the analysis.

### Task 4: Package the Application

The application was organized into the required Python files and supporting web resources.

The project includes a `requirements.txt` file containing the required Python dependencies.

### Task 5: Run Unit Tests

Unit tests were created and executed to verify that the emotion detection functionality works correctly.

The tests check different input statements and verify that the application returns the expected emotion information.

### Task 6: Deploy as a Web Application Using Flask

The emotion detection application was integrated with Flask to create a web application.

The Flask server provides an interface where users can enter text and receive emotion detection results.

The web application uses:

* Flask
* HTML
* JavaScript
* Watson NLP
* Python

### Task 7: Incorporate Error Handling

Error handling was implemented to make the application more reliable.

The application handles situations such as invalid input and unexpected errors and provides appropriate responses instead of crashing.

### Task 8: Run Static Code Analysis

Static code analysis was performed using **Pylint** on the `server.py` file.

The code was reviewed and modified to improve code quality, readability, and compliance with Python coding standards.

The goal was to achieve a **10/10 Pylint score**.

## Project Structure

```text
oaqjp-final-project-emb-ai/
│
├── server.py
├── emotion_detection.py
├── test_emotion_detection.py
├── requirements.txt
│
├── templates/
│   └── index.html
│
└── static/
    └── mywebscript.js
```

## Technologies Used

* Python
* Flask
* Watson NLP
* HTML
* JavaScript
* Pylint
* Git
* GitHub

## How to Run the Application

Clone the repository:

```bash
git clone https://github.com/riya1508-hub/oaqjp-final-project-emb-ai.git
```

Navigate to the project directory:

```bash
cd oaqjp-final-project-emb-ai
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python server.py
```

The application can then be accessed through the URL provided by the Flask server or Cloud IDE.

## Testing

Run the unit tests using:

```bash
python test_emotion_detection.py
```

## Static Code Analysis

Run Pylint using:

```bash
pylint server.py
```

The `server.py` file was reviewed and improved to achieve a high Pylint score.

## Conclusion

The completed project demonstrates the development of an emotion detection application using Watson NLP and its integration into a Flask web application.

The project covers application development, output formatting, packaging, unit testing, web deployment, error handling, and static code analysis.

Screenshots and outputs from each task can be used as evidence for the final project submission.

