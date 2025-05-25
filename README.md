# HCIR_Project


### Cloning the repository

Clone the repository

### Update and Upgrade
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

## Run face recognition integrated with greeting module 


### Face Recognition
- Create known_faces direcotory
- Place a picture of yourself in the "known_faces" directory with your name.
  For example, ayusee.jpg
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


Please note, the requirment file contains all the necessary libraries, however you may need to upgrade some libraries



