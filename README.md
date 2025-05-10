# WellBot.AI

[!(Home page)(Home page.mp4)]

## Introduction

WellBot.AI is an intelligent web application designed to diagnose health issues based on user descriptions of pain and other symptoms. With advanced AI models and a 3D human body integration, users can interact with specific areas of the body to pinpoint their symptoms and get tailored suggestions for possible health concerns.

## Features

* 3D Human Body Integration: Users can select specific points on a 3D human body model where they feel pain. This interactive feature allows for precise symptom descriptions.
* Pain Type: Users can describe the type of pain (sharp, dull, throbbing, etc.) they are experiencing.
* Pain Duration: Specify how long the pain has been occurring (e.g., minutes, hours, days).
* Pain Severity: Users can rate the severity of the pain on a scale (e.g., mild, moderate, severe).
* Age and Gender: These factors help in providing personalized diagnostic suggestions.
* Additional Symptoms: Users can list any other symptoms they are experiencing alongside the pain.
* Extra Details: Users can provide any additional information relevant to the diagnosis.
* Medication History: Optionally, users can include details about any medications they are currently taking or have taken in the past.

## Installation / Run Locally

To run WellBot.AI locally on your system, follow these steps:

### 1. Clone the Repository

bash
git clone [REPOSITORY_URL]
cd WellBot.AI


### 2. Install Backend Dependencies

Navigate to the backend directory and install the required dependencies:

bash
cd backend
pip install -r requirements.txt


### 3 In the frontend directory, install the necessary npm packages:

bash

npm install

### 4. Environment Variables

Create an `.env` file in the root directory of the project and include the following variable:


OPENROUTER_API_KEY=[YOUR_API_KEY_HERE]


You can obtain your OpenRouter API Key for free by signing up at [OpenRouter](https://openrouter.ai/). We are using a specially trained Mistral AI 7B parameter model (free version) to analyze the user's descriptions.

### 5. Start the Application

Once everything is set up, start both the backend and frontend servers:

For backend:

bash
cd backend
python app.py


For frontend:

bash
npm start
```

Now, the application should be accessible locally on http://localhost:3000 (or whichever port is specified).

## Credits

WellBot.AI is made with 💖 by Aanas and Zodrick in Hackindia hackathon.
