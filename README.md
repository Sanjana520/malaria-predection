## Online Malaria Predictor
Online malaria Predictor is a webapp to demonistrate a model which can predict malaria with 96% Accuracy
site can be viewed live <br>
(hosted at miscrosft Azure) : https://onlinemalariatest.azurewebsites.net/



# Note - please scroll down the site as images are bigger in  size

# Screenshots of Project

# Home page of project
![Screenshot (623)](https://user-images.githubusercontent.com/69461336/159123771-aa8ba3b5-ba09-4394-8dc4-69947bf19008.png)


# Home page containing Information about Disease
![Screenshot (624)](https://user-images.githubusercontent.com/69461336/159123788-24db11ca-5b38-45a0-94bb-ec452f3e509b.png)

# Malaria (Disease predictor) page in navigation it is next to Home page tab when clicked on it and scrolled down  it appears
![Screenshot (609)](https://user-images.githubusercontent.com/40494619/155872572-86d312a7-f632-4471-b804-80ecfe7d322f.png)
# Selecting sample image to be tested for prediction for upload
![Screenshot (625)](https://user-images.githubusercontent.com/69461336/159125625-cb6a8cf0-f0b8-43c6-9ded-ce33862db11f.png)



# Output -infected cell (malaria positive)
![Screenshot (631)](https://user-images.githubusercontent.com/69461336/159125729-29590364-1bcc-470a-80d7-681a8f771a25.png)

# Another sample image taken for prediction
![Screenshot (627)](https://user-images.githubusercontent.com/69461336/159125742-bfa3c451-b6fa-440b-9547-1dd4c7256c1b.png)

# Output image (Malaria not present)

![Screenshot (630)](https://user-images.githubusercontent.com/69461336/159125744-d6a391a7-a08c-42f6-8094-feca391f0993.png)

# Video of Project



https://user-images.githubusercontent.com/69461336/159126097-6147dbb8-13fb-428f-aede-e9d34183e7bf.mp4




## Aim / Purpose
Online Malaria Detector - Detects sample weather it is infected with malaria or not this model uses CNN (convolutional neural network) for classifying the images ,This project aims to demonstrate how online disease prediction/detection through Machine learning can save time and prove helpful for remote areas and villages also this helps in digitalization of records and error free mechanism saving time  cost and energy

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:
## Future scope

Multiple Disease detectors can be made by taking more accurate datasets training the models model for various diseases. 
Sytem if efficiently Designed will be helpful in faster report generation and treatment decreasing workload.
This system will have Digital copy of medical records and will provehelpful in telemedicine and virtual consultancy.
Saves Time work and energy gives error free result. 
People living in Remote areas and villages they can get their sample report to their mobiles and would reduce the travel to hospital everytime.
Overall wil;l result in Developing smart healtyh Ecosystem.



- **Malaria**

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Malaria     |    Deep Learning Model(CNN) | 96%      |

## NOTE

==> You can access the website live at: https://onlinemalariatest.azurewebsites.net//<br>
==> Python version 3.7 was used for the whole project.<br>

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle can be found in below link also images of samples.

https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria

