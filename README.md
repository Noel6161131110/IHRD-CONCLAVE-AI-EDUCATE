# IHRD-CONCLAVE-AI-EDUCATE
# ELEVATE

<img src="https://github.com/Noel6161131110/IHRD-CONCLAVE-AI-EDUCATE/assets/96733325/b4ff4507-2061-45af-92e3-acf35d92adca" width="300px" height="300px">
# Try the App

[Elevate](https://drive.google.com/file/d/1QVKhufje0CvwGIakJjqH3cBPJ062IRwE/view?usp=sharing)
# Source Code Repositories

- [Application Source Code Repo](https://github.com/NivedGanga/Elevate)
- [Backend Source Code Repo](https://github.com/Noel6161131110/Elevate-backend)
- [Gen-AI Source Code Repo](https://github.com/lordgrim18/Elevate_Story)

# Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

# Introduction

The Elevate App is designed to assist individuals who face challenges in speaking clearly. The app provides a platform for users to practice reading stories, and it offers feedback on pronunciation. Using AI, the app identifies words that need improvement and provides audio assistance. 

<img src="https://github.com/Noel6161131110/IHRD-CONCLAVE-AI-EDUCATE/assets/96733325/9cdda8ab-5bf6-475d-b215-39f1c6a1dd94" width="200px" height="400px">

# Features

- User-friendly interface for easy navigation.
- AI-generated stories for practice.
- Real-time feedback on pronunciation.
- AI-powered analysis for identifying areas of improvement.
- Pronunciation assistance with audio playback.

# Technologies Used

- Flutter for cross-platform mobile app development.
  - Used Bloc State-Management approach. 
- Python for backend and Gen-AI.
  - Django for the backend server.
  - Azure for deploying backend server.
  - Azure for deploying the backend server.
  - selenium for data extraction.
  - bs4(BeautifulSoup) for data extraction.
  - pandas for data manipulation.
  - huggingface_hub for using pre trained models.
  - llama-cpp-python for using the python binding for the C++ library for the implementation of the LoRA algorithm.
  - transformers for training and testing the Gen-AI model.
- Firebase for authentication.
- Git (Version Control System) which is used to collaborate among teams.
- Github which global platform for collaboration among teams.

# Getting Started

# Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Python 3.x](https://www.python.org/downloads/)
- [Django](https://docs.djangoproject.com/en/3.2/topics/install/)

# Usage

1. Register using email and password or using Google SignIn
<img src="https://github.com/Noel6161131110/IHRD-CONCLAVE-AI-EDUCATE/assets/96733325/9775c296-cadd-4f67-948c-e34493d80ab4" width="200px" height="400px">

2. Login with registered email and password or with Google SignIn
<img src="https://github.com/Noel6161131110/IHRD-CONCLAVE-AI-EDUCATE/assets/96733325/25611b73-05ac-44f2-b184-1ebfa2ebbff9" width="200px" height="400px">

3. Select your desired genre for story
<img src="https://github.com/Noel6161131110/IHRD-CONCLAVE-AI-EDUCATE/assets/96733325/212d12a0-3ed5-40f3-8571-75f192f3fa75" width="200px" height="400px">

4. Using microphhone read the story
<img src="https://github.com/Noel6161131110/IHRD-CONCLAVE-AI-EDUCATE/assets/96733325/e2ceae3d-d4fc-41d6-88ed-53860df44a3c" width="200px" height="400px">

5. Mispronounced words will be highlighted
<img src="https://github.com/Noel6161131110/IHRD-CONCLAVE-AI-EDUCATE/assets/96733325/1ddc0d83-ec3a-45cc-824b-37428c6647df" width="200px" height="400px">

6. By clicking on highlighted words you can hear the correct pronounciation of words
<img src="https://github.com/Noel6161131110/IHRD-CONCLAVE-AI-EDUCATE/assets/96733325/2c5b3112-8e4c-47c5-aa70-0ce272b432c0" width="200px" height="400px">


# How it Works

The general flow of the Application is as follows:
1. The user signs up into the application.
2. User details(name, age, genres/tags) are prompted.
3. The user is given AI generated content such as a story or a paragraph based on their specified genres/tags.
4. The user reads this content and this audio data is sent to the server and is processed for pronunciation errors and is indicated in the response.
5. The user can listen to the correct pronunciation of the indicated words.

# Contributing

We welcome contributions from the community. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with a descriptive message.
4. Push your branch to your fork.
5. Create a pull request with a detailed description of your changes.
