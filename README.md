# ChatBot - MovieFace

## Updating...

### Environment

​	Linux + Python3.6.5 + Pytorch0.4.0

### Where it is

The source on the 81 server.

Dataset in the /home/public/ChatBotData/

Code in the /home/zjb/workspace/project/ChatBot/

### Introduction of files 

* **train_text.py**  be used to train and test [text without history]
* **train_face.py**  be used to train and test [face without history]
* **train.py** be used to train and test [text and face with history]
* **parameters.py**  set parameters
* **model.py**  defined models
* **helpers.py**  some encapsulated auxiliary functions and classes
* **predata.py**  preparations for datasets and models

### Start

parameters and other settings are mainly in **parameters.py** and some in **predata.py**

before your training, you should check it, and there are some comments(though they may be not very clear haha)

* train [text] without history:

``` python
python train_text.py
```

* train [face] without history:

``` python
python train_face.py
```

* train [text and face] with history:

``` python
python train.py
```

