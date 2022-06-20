# CSCI-566 Assignment 2

## The objectives of this assignment
* Implement Variational Autoencoders (VAEs)
* Implement Transformers for language modeling and sentiment analysis

## Working on the Assignment
**We highly recommend the use of Google Colab, so that you can use free GPUs to speed up training.**

Without it, training will be painfully slow.

To do this, simply click on the "Open in Colab" button at the top of each notebook while viewing the notebook on Github (or locally). Make sure to right click -> open in new tab for it to work on Github.

You can then make a copy of the notebook in Google Colab (`Copy to Drive`) and start working on it!

**Remember to use a GPU**: Click Runtime -> Change runtime type -> Select GPU as the Hardware accelerator.

If you really want to use your own computer, see the following instructions:
________________________________________________________
In this assignment, please use Python `3.6`.
You will need to make sure that your virtualenv setup is of the correct version of python.

Please see below for executing a virtual environment.
```shell
cd csci566-assignment2
pip3 install virtualenv # If you didn't install it

# replace your_virtual_env with the virtual env name you want
virtualenv -p $(which python3) your_virtual_env
source your_virtual_env/bin/activate

# install dependencies
pip3 install -r requirements.txt

# work on the assignment
deactivate # Exit the virtual environment
```
To start working on the assignment, simply run the following command to start an ipython kernel.
```shell
# add your virtual environment to jupyter notebook
source your_virtual_env/bin/activate
python -m ipykernel install --user --name=your_virtual_env

# port is only needed if you want to work on more than one notebooks
jupyter notebook --port=your_port_number

```
and then work on each problem with their corresponding `.ipynb` notebooks.
Check the python environment you are using on the top right corner.
If the name of environment doesn't match, change it to your virtual environment in "Kernel>Change kernel".

## Problems
In each of the notebook file, we indicate `TODO` or `Your Code` for you to fill in with your implementation.

### Problem 1: Variational Autoencoders 
The IPython Notebook `CSCI566_Assignment2_problem_1_VAE.ipynb` will walk you through implementing VAEs with PyTorch.

### Problem 2: Transformers for language modeling and sentiment analysis 
The IPython Notebook `CSCI566_Assignment2_problem_2_Transformer.ipynb` will walk you through implementing a Transformer model with PyTorch.
