Step 1:
    Setup a virtual environment using "python -m venv <Name of the environment>"
Step 2:
    Navigate to Scripts and run activate.bat inside the virtual environment
Step 3:
    Navigate back into the main directory and clone the repository https://github.com/Likith101/Trafficsign-Detection-and-Translation using "git clone https://github.com/Likith101/Trafficsign-Detection-and-Translation"
Step 4:
    Install dependencies inside the cloned repo by navigating into the directory and running "pip install -r requirements.txt"
Step 5(Optional):
    run "python modelTrain.py" to train the model and save it as model.h5
Step 6:
    run "python run.py" with a working webcam to start the application