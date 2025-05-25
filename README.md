# EduPepper

**EduPepper** is an interactive robot assistant developed using the Pepper robot in the qiBullet simulation environment. It helps students choose suitable elective courses based on their personal preferences. The system features personalized interactions using face recognition, natural language processing, and intelligent decision-making using Bayesian Networks.

## Features
- Personalized greeting using face recognition.
- Speech-based interaction using NLP.
- Recommendation of electives using a Bayesian Network.
- Runs in the qiBullet simulation environment for Pepper Robot.

## Technologies Used
- Python
- `face_recognition` library
- `spaCy` (NLP)
- `speech_recognition`, `gTTS`, `playsound`
- `pgmpy` for Bayesian Networks
- `qiBullet` simulation for Pepper robot

## Prerequisites

### Update System Libraries
Please update root libraries 
```shell
sudo apt-update && sudo apt-upgrade
```

### Install dependencies either in conda environment or python virtual environment
Download spacy language model
```shell
python -m spacy download en_core_web_md
```
Install the requirements using
```shell
pip install -r requirements.txt
```

## Face Recognition and Greeting Module

### Face Recognition
- Create a folder named known_faces in the main project directory.
- Add an image of yourself to this folder with the filename as your name (e.g., ayusee.jpg).
- In main directory
```shell
cd /HCIR_PROJECT-MAIN
```
- Run the module using the command
```shell
python3 pepperassistance.py
```
### Speech Recognition
To use the speech recognition and text-to-speech functionalities, you need to install the following Python libraries:
- speech_recognition: For recognizing speech from audio.
- gTTS: Google Text-to-Speech for converting text to speech.
- playsound: For playing the generated speech audio.
Installation Commands
You can install these libraries using pip:
```shell
pip install speechrecognition
pip install gtts
pip install playsound
```
### Bayesian netowrk
To work with Bayesian Networks, you need to install the following Python libraries:
- numpy: For numerical operations.
- pgmpy: For probabilistic graphical models.
Installation Commands
You can install these libraries using pip:

```shell
pip install numpy
pip install pgmpy
```

⚠️ Note: All required packages are included in requirements.txt. However, you may need to upgrade some of them manually if you run into compatibility issues.

### Summary
EduPepper integrates:
- Face recognition for personalized greetings
- Speech recognition & NLP for natural interaction
- Bayesian reasoning to provide intelligent elective recommendations
This creates an engaging and useful assistant for students to navigate elective options in an informed and friendly manner.
