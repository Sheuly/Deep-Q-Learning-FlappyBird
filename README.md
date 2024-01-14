## Deep-Q-Learning-FlappyBird -- Exercise Task Description
### 1) Install Python Environment according to the 'readme.txt' file given below:
### a) Installation: On windows 10
* install Python 3.10+ version on the system. I have installed Python 3.10.8 on my system.
* restart system.
### b) Creating virtual environment:
* open cmd
* create a directory for our new project and navigate to that directory.
* create a python virtual environment folder (.venv)
* activate virtual environment.
* install necessary modules.
* install spyder editor
#### In my case:
-D:  
-cd D:\Personal\BHTstudy\software project\PracticeCopy_BHT_advanced_software_engineering_WiSe23main\DeepQLearn_FlappyBird  
-python -m venv .venv  
-.venv\Scripts\activate.bat  
-pip install -r requirements.txt  
-pip install spyder  
-exit

### 2) Use Spyder as an editor:
### a) Launch 
* go to the project directory.
* activate virtual environment.
* launch spyder.
#### In my case:
-D:  
-cd D:\Personal\BHTstudy\software project\PracticeCopy_BHT_advanced_software_engineering_WiSe23-main\DeepQLearn_FlappyBird  
-.venv\Scripts\activate.bat  
-spyder  

### 3a) Open file train.py and train a model for 100,000 rounds:
* Trained model saved in '/trained_models/flappy_bird_100000'
### 3b) Open file test.py and test models:
-test outputs are provided in the 'result' folder  
* The trained own model: test file - 'test_flappyBird_100000.py' and the result saved in '/video_file_for_submission/flappy_100000.mp4'
* /trained_models/flappy_bird_2000000: test file - 'test_flappyBird_2000000.py' and the result saved in 'result/flappy_2000000.mp4'
### 4) Advanced: Train a model on Google Colab completely with 1,2 Mio. rounds:
* Could run 100000 rounds only due to run out of time for submission
* file name : colab_implimentation.ipynb
### 5) Save the 'result' and 'Python environment instructions' into a personal GitHub repo:
-Link: https://github.com/Sheuly/Deep-Q-Learning-FlappyBird.git


