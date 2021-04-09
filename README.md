# TensorFlowExamples

A repository playing around with applications of neural nets with TensorFlow/Keras.

The earliest Jupyter notebooks simply work through various tutorial examples found online. There are then some notebooks with some original projects. My focus is on use cases which could be of interest to Rekki. e.g:
- Classifying buyers into cuisines based on purchases (text classifier where text = items)
- Predicting the next item to be added to an ordering list, training by the chat to learn the sequence + what items are normally ordered together (next word predicition/predictive text).
- Spelling corrector neutral network trained by simulating typos in our products or supplier names. 

Where Rekki data is used the data files are not uploaded to git and the data is sufficiently anonymised. 

I am trying out a new virtual env setup for this project, making use of pyenv. To install relevant python packages to pyenv:

```
pyenv activate tensorflow
pip install <package>
pyenv deactivate tensorflow
```
The tensorflow environment was originally created and connected to jupyter following this blog post: https://www.alfredo.motta.name/create-isolated-jupyter-ipython-kernels-with-pyenv-and-virtualenv/

I am using this pyenv method to have the newest version of TensorFlow, which requires newer versions of a lot of dependency packages than I have installed on my MAcbook. 


