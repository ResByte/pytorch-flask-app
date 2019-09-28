# pytorch-flask-app
Simple app to provide inference with web interface

## Todo:
- [x] create flask backend with pytorch prediction
- [x] create simple frontend using html and css
- [ ] dockerize app for deployments


## requirements 
- pytorch>=1.0.0
- torchvision
- flask 
- Pillow

## Run flask server 
- clone this repo
- run the following to launch flask server 
```
FLASK_ENV=development FLASK_APP=app.py flask run
```
- go to `http://127.0.0.1:5000` to see the front page rendered
- upload image you have or you can got to this repo and upload `input.jpg`

## Note:
- to render all the changes you make in the code, use `SHIFT`+reload button on the browser. 


## References :
This app is used for learning purpose and therefore some of the  resources are from : 
- [Pytorch Flask App Tutorial](https://www.notion.so/Deploying-ML-Model-933b6a8ec085418199d57aeebe57069d#10ae8952f7014e64829d5c61494e1bbe)
- [HeartFitz guide to Model development](https://www.notion.so/Deploying-ML-Model-933b6a8ec085418199d57aeebe57069d#9544e65932cf4f27b2e048997768cda3)
- [Style CSS background](https://www.notion.so/Deploying-ML-Model-933b6a8ec085418199d57aeebe57069d#3dbf362133254fc180fa78517f161ac3)