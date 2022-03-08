### This repo contains the program to test the models used for the paper:
# A convolutional neural network to recognize Chagas disease vectors using mobile phone images
# 
## A Convolutional Neural Network to recognize Triatoma infestans, a Chagas disease vector, using images from standard mobile phones.

This repo can be used as a starting point to build your Docker image and deploy it in a cloud service.

Under the [models](models) folder you will find the cvs files with the parameters for the sample app

This sample app is up at [Triatoma](https://triatoma.herokuapp.com). Test it out with your images!

You can test it locally with the command: `python server.py`  or by installing Docker and using the following command:
```
docker build -t vinchuca . && docker run --rm -it -p 5000:5000 vinchuca
```

In the [training](https://github.com/lpattori/GeoVin_train) repo you will find notebooks and images used to train the CNNs.

Portions of the code have been copied from [Fastai](https://Fast.ai)