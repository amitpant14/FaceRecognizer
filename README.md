# FaceRecognizer
This is the capstone project for the Python 3 Programming specialization by the University of Michigan. It includes:
* Image manipulation using python imaging library - Pillow
* Optical character recognition using tesseract and py-tesseract
* Face-detection in images using opencv library

The task for the project is to write python code which allows one to search through the images looking for the occurrences of keywords and faces. E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza". 

The images used for the project are located [here](/requiredFiles/projectImagesLarge). These are newspapers in english, and contain a variety of stories, advertisements and images. Note that these images are large and thus the program can take some time to work with them.

Here's an example of the output expected. If you search for the string "news", you should get the following result.
![Project example](/Demo/demo1.png)

You are free to modify the code in order to play with the parameters and improve the detection. Also note that if you are taking the above mentioned specialization, use this code only as a reference and try to finish the specialization by yourself.

## Getting started
The following steps will help you in getting a copy of the project up and running on your local machine.

### Prerequisites
You will need python installed on your system.

### Installing
To keep things simple, first download and extract the files from the repository to your local system. Now,
* Create a python virtual environment on your system using the [requirements](/requirements.txt) file. 
* The virtual environment should install jupyter notebook on the virtual environment. If not, install it separately.
* Activate the virtual environment.
* Add the virtual environment to jupyter notebook.
* If you get stuck at any step, google is your friend.
After following the above steps, you will have the required libraries for the code to work.

### Running
To run the code, you will need to open the project notebook on your system. Give it an input string and see the magic!

## License
This project is licensed under the MIT License. You can see the full license [here](/LICENSE).
