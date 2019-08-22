
# Deep Learning with Keras® Course

Welcome to the Deep Learning with Keras® Course repository.

## Get started guide

#### Clone this repository on your local computer

```
git clone https://github.com/umutboz/DeepLearningWithKeras.git

```

#### Download and Install Anaconda Python 3.7

https://www.anaconda.com/distribution/

#### Change to course folder

```
cd DeepLearningWithKeras

```

#### Create the course environment

```
conda env create
```

wait for the environment to create.

#### Activate the environment (Mac/Linux)
```
conda activate keras

```

#### Activate the environment (Windows)
```
conda activate keras

```

Check that your prompt changed to

```
(keras) $

```

#### Launch Jupyter Notebook

```
jupyter notebook
```

#### Open your browser to

```
http://localhost:8888
```

#### Run the Check environment Notebook

Go to the course folder, open the notebook `Check_Environment.ipynb` and run it. If you see the message:

    Keras env is Ready!

You are good to go! Enjoy!


#### Troubleshooting installation
If for some reason you don't see `Keras env is Ready!`, the simplest solution is to delete the environment and start from scratch again.

To remove the environment:

- close the browser and go back to your terminal
- stop jupyter notebook (CTRL-C)
- deactivate the environment (Mac/Linux):

```
conda deactivate
```

- deactivate the environment (Windows 10):

```
deactivate keras
```

- delete the environment:

```
conda remove -y -n keras --all
```

- restart from environment creation and make sure that each steps completes till the end.

#### Updating Conda

One thing you can also try is to update your conda executable. This may help if you already had Anaconda installed on your system.

```
conda update conda
```

These instructions have been tested on:

- Mac OSX Sierra 10.14.1
- Ubuntu 18.04
- Windows 10

## Running the course on Google Colaboratory with free GPU support

later, Next time..
