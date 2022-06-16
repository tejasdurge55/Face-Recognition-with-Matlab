# Face-Recognition-with-Matlab
The project makes use of Matlab and Camera to Identify a person using Viola Jones Algorithm.
The Camera used here is the Integrated web-cam of a Laptop,even the Selfie Camera of a mobile can be connected for better clarity.
Here,firstly a database has to be created using facial images of different people.
Then, a model is trained using the database.
Finally when the model is deployed,it recognizes the person in front of the camera and displays that person's name on an LCD Screen.

# Data Collection
Matlab code for collecting images of different people and creating a database on the local computer .

# training Model
Matlab code for training the model using alexnet model.

# testing model
Matlab code for Real Time testing of model.The output displays the name of the person facing the camera.Also,it sebd a signal to the arduino uno board through Serial communication. 

# arduino code for lcd with matlab
Arduino C code for recieving Serial COM Port input from matlab in the form of string and displaying it on a 16X2 LCD Screen
