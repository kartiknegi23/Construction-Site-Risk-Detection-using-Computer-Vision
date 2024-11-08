
## About Project

An application that helps to detect the different types of risks that are associated with the construction workers while working at the sites. The app sends the image that is being uploaded by the user to the server where it is analysed using SSD (Single Short Detector) model. Once the backend is done, the detected image is displayed to the user with the bounding boxes and its respective confidence scores.

---

## Model

The model is trained to identify 4 classes for **Construction Site Risk Detection**
These 4 classes are:

- helmet
- vest
- without_vest
- without_helmet

The dataset has been taken out from various sources like kaggle, Open Images etc.
The annotation of the dataset is being performed on MakeSense tool in XML format.

---


## How to run this project? 
 
  1. clone this repository
 ```
	git clone https://github.com/kartiknegi23/Construction-Site-Risk-Detection-using-Computer-Vision.git
```
 
 1. Install the required dependencies 
 ```
	pip install -r requirements.txt 
```
2. Command for running app 

```
   streamlit run app.py
```
"# Construction-Site-Risk-Detection-using-Computer-Vision" 
