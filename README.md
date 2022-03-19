## Online Malaria Predictor
Online malaria Predictor is a webapp to demonistrate a model which can predict malaria with 96% Accuracy
site can be viewed live <br>
(hosted at miscrosft Azure) : https://onlinemalariapredictor.azurewebsites.net/

site is also deployed in herokuapp (online web hosting site) :https://onlinemalariaprediction.herokuapp.com/ 

# Note - please scroll down the site as images are bigger in  size

# Screenshots of Project

# Home page of project
![Screenshot (607)](https://user-images.githubusercontent.com/40494619/155872550-e7db11d2-b152-4a14-810d-f8c714a4a6b9.png)
# Home page containing Information about Disease
![Screenshot (608)](https://user-images.githubusercontent.com/40494619/155872561-6f15a2c6-f92f-4eb7-a0ab-a8ee3f7cc521.png)
# Malaria (Disease predictor) page in navigation it is next to Home page tab when clicked on it and scrolled down  it appyears
![Screenshot (609)](https://user-images.githubusercontent.com/40494619/155872572-86d312a7-f632-4471-b804-80ecfe7d322f.png)
Selecting sample image to be tested for prediction for upload
![Screenshot (612)](https://user-images.githubusercontent.com/40494619/155872590-035243af-8f1e-4b11-9ecb-1d2d7eec63b2.png)
# uploaded sample image (when clicked on submit ,it starts predicting by classifying image
![Screenshot (613)](https://user-images.githubusercontent.com/40494619/155872593-ce48dfec-babe-419e-ab78-a45b91073839.png)
# Output -infected cell (malaria positive)
![Screenshot (617)](https://user-images.githubusercontent.com/40494619/155872612-abcb679c-0789-49bb-ab10-e1b40a01c3a4.png)
# Another sample image taken for prediction
![Screenshot (618)](https://user-images.githubusercontent.com/40494619/155872619-34937f54-bfc2-4d8b-a3a0-ea97c8784e33.png)
# Output image (Malaria not present)
![Screenshot (619)](https://user-images.githubusercontent.com/40494619/155872629-bb447a5c-9dbf-45e3-bd22-47cf87aafe7a.png)

# Video of Project

https://user-images.githubusercontent.com/40494619/155873377-164f5b8d-c183-4e14-9e04-847078f6b04a.mp4


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

==> You can access the website live at: https://onlinemalariapredictor.azurewebsites.net/<br>
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

