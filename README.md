# Car_Price_Prediction

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview) 
  * [Directory Tree](#directory-tree)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Future scope of project](#future-scope)


## Demo
Link: [https://cars-resell-price-predictions.herokuapp.com/](https://cars-resell-price-predictions.herokuapp.com/)

![car](https://user-images.githubusercontent.com/40171054/112941799-ca269400-914c-11eb-9117-d09e41d7c6b1.png)

## Overview
This is an end-to-end machine learning project, to predict car resell prices.

## Directory Tree 
```
├── static 
│   ├── css
│     ├── style.css
├── templates
│   ├── index.html
├── Procfile
│── car data.csv
├── README.md
├── app.py
├── car-price-prediction.ipynb
├── requirements.txt
```

## Installation
The Code is written in Python, If you don't have Python installed you can find it [here](https://www.python.org/downloads/). 

```bash
git clone https://github.com/OmkarPatkar/Car_Price_Prediction.git
cd Car_Price_Prediction_main
```
Then run the car-price-prediction.ipynb file to generate the model file, once we have the model(pkl) file we can move forward.

```bash
pip install -r requirements.txt
python app.py
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[Link](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
