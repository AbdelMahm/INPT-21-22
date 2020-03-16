# INPT-2020

# Machine Learning Lab Guidlines

## Links to google forms

1. Linear Regression: https://forms.gle/8ZE9PRxEPPrzEFpF6 (deadline: before **17 March**)
   
2. Logistic Regression: https://forms.gle/8ZE9PRxEPPrzEFpF6 (deadline: before **17 March**)
   
3. Support Vector Machines: https://forms.gle/8ZE9PRxEPPrzEFpF6 (deadline: before **18 March**)
   
4. Ensemble Learning: https://forms.gle/8ZE9PRxEPPrzEFpF6 (deadline: before **18 March**)
   
5. Artificial Neural Networks: https://forms.gle/8ZE9PRxEPPrzEFpF6 (deadline: before **19 March**)
   
6. Unsupervised Learning: https://forms.gle/y1fuZ9XhkY2Z7eki6 (deadline: before **19 March**)


## Lab setup

You just need a google account for using Colab. Otherwise, you can use a virtual environment like conda to run locally.

### On local: Install Miniconda

#### Download

Miniconda from https://conda.io/miniconda.html

#### install

\$bash Miniconda3-latest-Linux-x86_64.sh

### Create environment

#### Create env

\$conda create --name inptlab python=3.6

#### activate env

\$source activate inptlab

### Install packages

(inptlab)$pip3 install --upgrade pip
(inptlab)$pip3 install numpy scipy pandas matplotlib
(inptlab)$pip3 install scikit-learn
(inptlab)$pip3 install jupyter
(inptlab)\$pip install --ignore-installed --upgrade tensorflow

#### list packages

(inptlab)\$ conda list

### Jupyter notebook

#### run jupyter

(inptlab)\$ jupyter notebook

#### install package inside a jupyter notebook cell

!pip install numpy

