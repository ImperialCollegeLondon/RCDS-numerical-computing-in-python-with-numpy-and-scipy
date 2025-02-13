# Numerical-Computing-in-Python-with-NumPy-and-SciPy

## Pre-Course Instructions

### Webinar Instructions

To complete this course, you will need to run Jupyter Notebook files on your computer. The easiest way to do this is to ensure you have a Google account. This will allow us to use the online Google Colab tool to run the notebooks on the day.

Alternatively, if you don’t have and don’t want to create a Google account, you can download and run the notebooks locally instead using whichever program you are most familiar and comfortable with. For instance, install Anaconda on your computer by downloading the appropriate distribution from [here](https://www.anaconda.com/distribution/), or install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) and [install the package](https://cs205uiuc.github.io/guidebook/resources/python-miniconda.html) ```jupyter``` within it.

The presentation and the Notebooks may be found [here](https://github.com/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/archive/refs/heads/master.zip). You should download them before the course. However, you do not need to read them before attending.

### Face to Face Course

This course will take place in an ICT computer room and so laptops are not required but you may bring one if you wish. Please make sure it is fully charged. This course will involve the running of Jupyter Notebook files. The easiest way to do this is to ensure you have a Google account. This will allow you to use the online Google Colab tool to run the notebooks on the day.

Alternatively, if you don’t have and don’t want to create a Google account, Imperial computers (including those in the computer rooms) will have Anaconda available to them through the Software Hub which will also allow the running of Jupyter Notebooks. You may also chose to install Anaconda on your personal machine by downloading the appropriate distribution from [here](https://www.anaconda.com/distribution/).

The presentation and the Notebooks may be found [here](https://github.com/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/archive/refs/heads/master.zip) If you want to undertake the course on your own laptop, you may want to download them. However, you do not need to read them before attending.

### Self-Study Instructions

This course can also be completed through self-study from this repository. To do this, you will need to run the Jupyter Notebooks on your computer. The easiest way to do this is to ensure you have a Google account and are logged in on the your browser. Then, you can follow the links in the "Colab Links" section of this file in order from top-to-bottom in order to work through the notebooks. You will need to create a copy of the notebooks by clicking File>Save a Copy in Drive. This will create a copy of the notebook in your Google Drive and allow you to edit it to add notes, run examples and complete exercises. Underneath the code cells left for you to complete each exercise, there will be a code cell saying "Show Code". Clicking on this will show a sample solution to check your answer.

Alternatively, if you don’t have and don’t want to create a Google account, you may instead install Anaconda on your computer by downloading the appropriate distribution from [here](https://www.anaconda.com/distribution/). The presentation and the Notebooks may be downloaded [here](https://github.com/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/archive/refs/heads/master.zip). You can then open the notebooks using Anaconda (open them in the order written in the "Colab Links" section below). You can edit these files to add notes, run examples or write your solutions to the exercises. Under the code cell left blank for you to write your solution to these exercises and the code cell below contains a sample solution for you to compare your answer to.

## Packages

Whether you attend a face-to-face or webinar version of this course or if you intend to self-study, if you intend to run the code in Anaconda, install the following packages in your Python environment before you attend to avoid having to do so during the course:

* numpy
* scipy
* matplotlib

If you're familiar with how to do so, you can use the file ```requirements.txt``` in this repository to set up your environment.

## Colab Links

The following are links to the Notebooks which will open in Google Colab. To use these links, you will need to log into a Google account. Once you click the link, you may see a page saying "Connected apps". If Google Colaboratory is in the list, click it to open the notebook. If it's not, click "Connect more apps...", search for "Colab" and connect the app before selecting it.

* [What Are NumPy and SciPy](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/What are NumPy and SciPy.ipynb>)
* [Creating and Manipulating NumPy Arrays](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/Creating and Manipulating NumPy Arrays.ipynb>)
* [Array Operations](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/Array Operations.ipynb>)
* [Integration](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/Integration.ipynb>)
* [Built-In Functions](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/Built-In Functions.ipynb>)
* [Initial Value Problems](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/Initial Value Problems.ipynb>)
* [Other Features](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/Other Features.ipynb>)
* [Performance Comparison](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/Performance Comparison.ipynb>)
* [Projects](<https://colab.research.google.com/github/coolernato/Numerical-Computing-in-Python-with-NumPy-and-SciPy/blob/master/Projects.ipynb>)

You do not need to look at these notebooks before the course unless you want to.

## Post-Course Follow-Up: ReCoDE Exemplar
The RCDS team has curated a collection of annotated [exemplar projects](https://imperialcollegelondon.github.io/ReCoDE-home/exemplars/) known as [ReCoDE](https://imperialcollegelondon.github.io/ReCoDE-home/) which demonstrate core research computing and data science principles applied to real problems. Each exemplar is a real project created by an Imperial student based on their research. Each exemplar is accompanied by detailed descriptions of how they work, and the design decisions taken when constructing the code. There are two Fortran exemplars:

* [**Euler Maruyama Method**](https://imperialcollegelondon.github.io/ReCoDe-Euler-Maruyama/): This exemplar focuses on solving Stochastic Differential Equations in Python. The code uses Numpy arrays to store the data of the simulation and progress the simulation. It also shows how to use Numpy in an object-oriented program.
* [**Using Convolutional Neural Networks to extract information from the Cosmic Dawn**](https://imperialcollegelondon.github.io/ReCoDE-FirstDawn/): This exemplar uses a Convolutional Neural Network to extract information about the early universe. Data is prepared for use in TensorFlow using Numpy arrays.
* [**Binary Classification of Patent Text Using Natural Language Processing**](https://imperialcollegelondon.github.io/ReCoDE-AIForPatents/): This exemplar uses Natural Language Processing to classify patents. The code uses Numpy arrays to store and prepare the data.
* [**A Multi-Channel GUI for Real-Time Data Display and Analysis**](https://imperialcollegelondon.github.io/ReCoDE-PythonGUI/): This exemplar presents a GUI for real-time data display and analysis in a medical context. The data used in the GUI is stored in Numpy arrays.