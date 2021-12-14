## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Questions](#questions)

## General info
The dataset used for training this model is from jmcauley.ucsd.edu/data/amazon/

The goal of the project is to use the model to predict topics of unseen Jumia cellphone reviews 
	
## Technologies
Project is created with:
* Python 3.8
* Sklearn
* Pandas 1.4
* Numpy
	
## Setup
To run this notebook, clone/download it locally then start the env i.e Jupyter Notebook:
If on Linux : 

```
$ jupyter notebook
$ sudo pip install <module_name> (For error: Module not Found)

```
If on Windows:
```
Start Jupyter from Anaconda 

```
OR...
```
Upload the Notebook and run it on Google Colab

```


## Questions:
1. Is it possible to get a sentiment graph and word cloud from prediction?
2. If I use the model on Jumia corpus will it predict in real time or will I have to run it through training as well?
3. In the case of classifying cellphone reviews based on the aspects would I rather explicitly define the topics I am looking for (Text Classification - Supervised Learning)
4. OR can I still used the (Topic Modelling - Unsupervised Learning) to get the topics present
