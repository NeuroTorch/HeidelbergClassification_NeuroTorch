# Heidelberg Application.


#### This work is currently in progress. However, the code is functional and can be used to train a model on Heidelberg dataset.


In this application we are using NeuroTorch to classify the Heidelberg dataset. In the folder 
you can find the [main script](main.py) which contains a simple run of NeuroTorch for audio classification.


Here is an exemple of the Heidelberg dataset:

![Heidelberg_exemples](images/heidelberg_exemples.png)



For the one who want more statistical information about the dynamics of NeuroTorch on classification task, you
can run the [results generation script](results_generation.py) which will generate a file with the results of the
trainings and the testings with different models and different parameters. Note that this script can take a while to
run.

In the first place, whether you want to run the tutoriel or the entire analysis, you will want to install the 
dependencies.
```
pip install git+https://github.com/NeuroTorch/NeuroTorch
pip install -r requirements.txt
```






