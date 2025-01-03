# Programming-for-Data-Analysis-Project-1
Programming for Data Analysis Project 1


<p>G00364639</p>
<p>This repository is used for the project given during the Programming for Data Analysis module on Higher Diploma in Data Analytics course from ATU.</p>

<p>I have created Jupyter Notebook in Visual Studio Code, & I have added added comments to explain work, along with references<br>

<p>For this markup sheet, I used the following websites as guides.<br>

<ol>
<li><a href="#">https://www.markdownguide.org/basic-syntax</a></li>
<li><a href="#">https://www.w3schools.io/file/markdown-cheatsheet/</a></li></p>
</ol>

# **Table of contents**
* [Machine-Learning-Project-1](Machine-Learning-Project-1)
    1. [Introduction](#Introduction)
    2. [How to run program](#How-to-run-program)
    3. [Additional Information](#Additional-Information)
    4. [Imported Libraries](#Imported-Libraries)

# Introduction #

<p>This repository is used for the project 2 given during the Machine Learning module on Higher Diploma in Data Analytics course from ATU.</p>

<p>For this module I created one notebook called Machine-Learning-Project-1.</p>

<p>
The layout of this project is as follows:</p>


<li> 1.  </li>
<li> 2.  </li>
<li> 3.  </li>
<li> 4.  </li>
<li> 5.   </li> 
<li> 6.   </li> 
<li> 7.   </li>
<li> 8.   </li>
<li> 9.  </li>

</p>

# How to run program #
<ol>
<li> Install Anaconda </li>
<li> Install Visual Studio Code </li>   
<li> Clone repository </li> 
<li> Open repository in Visual Studio Code </li>
</ol>

# Additional Information #
<ol>
<li> My github repository is @ <a href="#"></a></li>
<li> My github Repository is called "Machine-Learning-Project-2</li>   
<li> This repository contains a .gitignore file, and a README file, </li> 
<li> This repository contains 1 *  Jupyter notebook named 'Project 2.ipynb'.</li> 
<li> This repository contains a folder called 'imported_datasets' which contains all imported datasets</li> 
<li> This repository contains a folder called 'fused datasets' which contains all fused datasets in .csv and .json format. and a folder called 'img which contains images.</li>   
<li> This repository contains a folder 'img which contains images used in notebook</li>     
<li> These are all the additional files required to run program </li>
<li> Libraries that need to be imported are contained in first *text* cell of both Jupyter notebooks </li> 
</ol>

# Imported Libraries #
<ol>
<li>import numpy as np</li>
<p> NumPy is short for "Numerical Python". It allows for matematical and logical operations on arrays efficiently. NumPy also enables user to reshape,slice ,stack and join arrays.</p>
<li>import pandas as pd</li>
<p>Pandas is an open source Python library that provides high performance data manipulation tools and analysis tools. It also allows for reading and writing from various file formats, such as .csv. Pandas has functions for analyzing, cleaning , exploring and manipulating data</p>
<li>import matplotlib.pyplot as plt</li>
<p>Matplotlib is a low level graph plotting library in python. It is open source. Using Mathplotlib, different types of plots can be created, such as scatter plots, histograms,box plots etc.</p>
<li>import seaborn as sns</li>
<p>Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.It is designed to work well with dataframes from Pandas</p>
<li>from sklearn.linear_model import LinearRegression</li>
<p>LinearRegression fits a linear model with coefficients w = (w1, …, wp) to minimize the residual sum of squares between the observed targets in the dataset, and the targets predicted by the linear approximation.[23] *sklearn.linear_model.LinearRegression*, scikit-learn, https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html</p>
<li>from scipy.fft import fft, fftfreq</li>
<p>Return the Discrete Fourier Transform sample frequencies.</p>
<li>from scipy import signal</li>
<p>to modify, analyze and process the signal [24] *Scipy Signal – Helpful Tutorial*, pythonguides, https://pythonguides.com/scipy-signal/</p> 
<li>import json</li>
<p> JSON  (JavaScript Object Notation) is a file that is mainly used to store and transfer data mostly between a server and a web application. It is popularly used for representing structured data.</p> 
<p></p> 
</ol>


Project Part 1 
This sub-project is worth 50% of the overall project grade. 
Task: Interview/Debate Audio Analysis 
This task is to leverage some of the existing models to perform an analysis of 
interviews/debates. This tool could be used to identify media bias/impartiality 
The objective of this task is to develop a notebook that will accept an audio file (mp3 or wav) of 
an interview/debate. (done)
Speaker Diarisation Analysis: 
Using pre-built Speaker Diarisation models, the first task is to identify who spoke when – i.e. the 
model should output the times that each speaker started and stopped talking. (done) This should 
enable calculating how many seconds/minutes each speaker spoke for. (done)
Speech to Text Analysis: 
Once the separate speakers have been identified, the next task is to use a Speech to Text model 
to create a transcript of the audio with the speakers identified in the transcripts: 
E.g: 
[Speaker 1] Hi, how are you today? 
[Speaker 2] I’m good and you? 
[Speaker 1] Good thanks, how about…. (done)
This should enable an analysis of how many words each person spoke and might enable a 
frequency analysis of particular words (i.e. how many times a particular word was used by a 
particular individual). 
Large Language Model Analysis: 
Once you have the transcript with speakers identified and annotated, you can input this into a 
LLM to query it on sentiment etc. 
E.g. ask it can it identify what the names of the speakers are/ask it whether speakers associate 
with more right-wing/left-wing values etc…. 
Testing: 
I will give you an audio file for research purposes (from the Harris V Trump 2024 US Presidential 
Debate) – Note: this file is not to be hosted on a public GitHub repo. 
However, you should test on another (potentially more complex) file (with more 
speakers/multiple speakers of the same sex) and evaluate/annotate the performance of the 
components. 
Development/Documentation: 
All documentation and development should be performed within a Jupyter Notebook. Regular 
commits should be made to a private GitHub repository. You must add me (brianmcgatu) as a 
collaborator. The audio you tested on should be also hosted on your private repo. 
Your final committed notebook should be complete with all code cell outputs populated (i.e. it 
doesn’t require a viewer (me) to replicate the environment and re-execute the notebook to view 
the results) 
Your repository should also include a README – detailing how to recreate your environment for 
the notebook to execute etc. 
Any submission that does not have a full and incremental git history with informative commit 
messages over the course of the project timeline will be accorded a proportionate mark. 
Research: 
All research must be captured through the notebook and collated in a bibliography at the end of 
the notebook. An academic referencing style must be used. 
If doing research/comparisons between different models, include that analysis in a separate 
research notebook and refer to the research in the main notebook. This is to keep the main 
notebook analysis concise. 
Rubric: 
Note: Your final mark will not solely be based on your final results but also on your 
methodology/approach. 
Consistency: 20% 
Research: 25% 
Development: 30% 
Documentation: 25% 
As usual, you are bound by ATU Student Code of Conduct (Student 
Code_Final_August_2022.pdf).
