# AudioMosaicing-Freesound-Essentia

The main goal of this project is to explore the combination of Freesound API [1]
and Essentia library [2] analysis in order to create a creative application: AudioMosaicing.

[1]: https://freesound.org/
[2]: https://essentia.upf.edu/

The Audio  Mosaicing technique aims to reconstruct a target audio using frames of a source audio. The reconstructed sound uses frames from the source preserving characteristic of the target sound.

In particular, in this project the target sound will be recostructed using a collection of sounds downloaded from Freesound using the Freesound API. The frames used to recostructed the target sound will be selected according to some particular features analyzed using Essentia library. 

The project has been divided in three main steps:
- Creation of sounds source collection.
- Analysis of sound sources collection and target file.
- Reconstruction of target file with source collection frames.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

Python and the following modules are necessary to run the notebook correctly: numpy, matplotlib, pandas, freesound and essentia. 

You can install the modules required (excpet from essentia and freesound) simply typing on the terminal the following command: 
```
$ pip install -r requirements.txt
```
(the file requiremennts.txt is in the repository)

Otherwise, you can manually install the single modules with the following commands. 

In **Ubuntu** the user can install all these modules it is as simple as typing on the terminal:
```
$ sudo apt-get install python-dev python-numpy python-matplotlib python-pandas
```

In **OSX** the user can install these modules by typing on the terminal:

```
$ brew install python
$ pip install numpy matplotlib pandas
````

In **Windows** the user can refer to this link to install python on your local machine: https://docs.python.org/3/using/windows.html and install the other modules by typing on the terminal: 

```
$ pip install pandas numpy matplotlib 
```

#### Installing Freesound

Plase, refer to this link to install Freesound-python: https://github.com/MTG/freesound-python

#### Installing Essentia

Plase, refer to this link to install Essentia library: https://essentia.upf.edu/installing.html

### Clone or Download the repository 

Clone or download the repository. 
It contains a jupyter notebook, please read Jupyter Notebook instruction to properly change directories paths and run the notebook correctly.

Command to clone the repository:
```
$ git clone https://github.com/RonFrancesca/AudioMosaicing-Freesound-Essentia.git
```

### Jupyter Notebook instructions
Install Jupyter Notebook according to the its instructions https://jupyter.org/install

Start up jupyter notebook

```
$ jupyter notebook
```

Follow the instructions appearing in the console regarding navigating your browser to the notebook

### Target sound link

The target sound used for this project could be downloaded here: https://freesound.org/search/?q=180053. 
After downloading the sound, save in in the same folder where the jupyter notebooks are saved to currently run the project. 

## Run the code

Read carefully the instruction the jupyter notebook to set folder path and variable properly. 
Please consider that you should make a Freesound account and get your own key to run the code, which need to be set in the first jupyter notebook (Create a sound collection). 
You can get a key here: https://freesound.org/apiv2/apply/. 

When all the modules are installed and the target file downloaded and saved in the right folder, run them in sequence. 
- Create source sounds collection 
- Analyze source collection and target file
- Reconstruct target file with source collection frames

Run it as many times as you want to find the sound that you like the most, the results will be randomized every time. 

# License
This project is licensed under a Creative Commons Attribution 4.0 International License (CC BY4.0). 

## Authors 
- Francesca Ronchini


