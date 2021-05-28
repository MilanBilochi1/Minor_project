To run this project on your machine, follow the steps:

1) install all dependencies from environment.yml file or write the code in command promt:
	conda env create -f environment.yml
   it will download all dependencies in a conda virtual enviornment.

2) Launch the Unity self driving car simulator.
   start training mode and start recording.	
   drive the simulator to train.
   Get the Unity self driving car simulator from https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f3a4_simulator-windows-64/simulator-windows-64.zip

3) save the csv file and images folder created by the simulator in data folder in project directory.


4) activate the environment and run model.ipynb.
   execute all codes line wise.
   save the model.h5 file in the project diroctory.


5) run the drive.py file in the virtual environment.
   Launch the unity car simulator(open sourced by Udacity).
   once the port is active click on autonomous mode in simulator.