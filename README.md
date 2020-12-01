<img align="centre"  width="500" height="500" img src="https://i0.wp.com/www.creatingentrepreneursinfood.eu/wp-content/uploads/2017/02/GMIT-logo.png">

# Fundamentals of Data Analysis: Tasks 2020 Assessment

* **Author:** John Paul Lee
* **Github:** JPLee01
* **Email:** G00387906@gmit.ie
* **Created:** 09-10-2020, **Last update:** -12-2020
------------------------------------------------------------------------------------------------
**Fundamentals of Data Analysis:** Tasks 2020 Assessment

A Jupyter Notebook has been created to store and demonstrate the four tasks for the Tasks 2020 Assessment for the Fundamentals of Data Analysis Subject.

**Lecturer:** Dr. Ian McLoughlin

The Assessment instructions can be found at [here](https://github.com/JPLee01/Tasks-2020/blob/main/Assessment%20Instructions.pdf)

**Table of Contents**
------------------------------------------------------------------------------------------------

[* Fundamentals of Data Analysis: Tasks 2020 Assessment](#Fundamentals-of-Data-Analysis:-Tasks-2020-Assessment)

[1. Introduction](#1-introduction)

[2. Assessment Repository](#2-Assessment-repository)

[3. Tasks](#3-Tasks)

  [3.1 Counts](#3.1-Counts)

  [3.2 Dicerolls](#3.2-Dicerolls)

  [3.3 numpy.random.binomial](#3.3-numpy.random.binomial)

  [3.4 Simpson’s Paradox](#3.4-Simpson’s-Paradox)

[4. User Guide](#4-User-Guide)

  [4.1 Downloading the Repository](#4.1-Downloading-the-Repository)

  [4.2  Running the Program](#4.2-Running-the-Program)

  [4.3  Libraries](#4.3-Libraries)

[5. Summary, Conclusion and Future Analysis of the Tasks 2020 Assesssment](#5.-Summary,-Conclusion-and-Future-Analysis-of-the-Tasks-2020-Assesssment)

[6. References](#6-References)

[7. Bibliography](#7-Bibliography)

## 1 Introduction
------------------------------------------------------------------------------------------------



## 2 Assessment Repository
------------------------------------------------------------------------------------------------

The Assessment Repository is the source where all the work associated with
the assessment will be stored. It contains the following files and can be
located [here](https://github.com/JPLee01/Tasks-2020):

  **File**    |     **Description**
  ---------   |   --------------------------------------------------------
  .gitignore | A Text File explicitly explaining to Git which files or folders to ignore in the Assessment
  Assessment Instructions.pdf | A PDF copy of the Assessment Instructions
  LICENSE     |    MIT License for the project
  Tasks-2020.ipynb | Jupyter Notebook created to explain and demonstrate the four tasks in the Assessment
  README.md   |    This file; A Description of the Assessment and Instructions

## 3 Tasks
------------------------------------------------------------------------------------------------
As part of the assessment, the student was given a set of instructions which can be viewed [here](XXXX). As seen, within the instructions a set of four tasks were printed. These tasks were the basis of the assessment and were described as follows:

### 3.1 Counts
Write a Python function called ```counts``` that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So, the input ```['A', 'A', 'B', 'C', 'A']``` should have output ```{'A': 3, 'B': 1, 'C': 1}```. Your code should not depend on any module from the standard library1 or otherwise. You should research the task first and include a description with references of your algorithm in the notebook.

### 3.2 Dicerolls
Write a Python function called ```dicerolls``` that simulates rolling dice. Your function should take two parameters: the number of dice *k* and the number of times to roll the dice *n*. The function should simulate randomly rolling *k* dice *n* times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as ```diceroll(k=2, n=1000)``` should return a dictionary like:```{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}``` You can use any module from the Python standard library you wish and you should include a description with references of your algorithm in the notebook.

### 3.3 numpy.random.binomial
The ```numpy.random.binomial``` function can be used to simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a coin is flipped many times then the number of heads is well approximated by a bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100. Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code.

### 3.4 Simpson’s Paradox
Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an ```x``` array and a corresponding ```y``` array, to demonstrate Simpson’s paradox. You might create your ```x``` arrays using ```numpy.linspace``` and create the ```y``` array for each ```x``` using notation like ```y = a * x + b``` where you choose the ```a``` and ```b``` for each ```x``` , ```y``` pair to demonstrate the paradox.

## 4 User Guide
------------------------------------------------------------------------------------------------
This section will describe the steps required to download and run the files in the repository.

### 4.1 Downloading the Repository
The repository is stored at the following: https://github.com/JPLee01/Tasks-2020

To download the repository, do the following:
1.  Click on the above link to open the repository
2.  Once in the repository, click on the green “clone or download” button on the right side of the screen.
3.  Select "Download ZIP". This will open a prompt allowing you to save the file to a desired location on your computer.
4.  Navigate to where  the ZIP files are located on your computer and extract the compressed (.zip) files.

### 4.2 Running the Program
Once the repository has been downloaded, you will need to ensure that you are running it in the correct environment. It should be noted that this repository has been written using Python 3.8.2 and consequently it will require a Python version of 3.7 at a minimum to run as designed. The repository also requires a number of external Python libraries [seen below](#4.3-Libaries) to execute correctly. Once the correct version of Python has been installed complete with necessary libraries and the ZIP has been downloaded and extracted the user can run the program. The running of any of the programs from the command line can be executed as follows:
1.  Open a command prompt (cmd) or equivalent on your computer.([Cmdr](https://cmder.net) is recommended for Windows computers, Mac Computers via the terminal)
2.  Navigate to the desired location through the use of the change directory (cd) command.
3. Run Jupyter Notebook by typing the following at the command prompt (do not close the command prompt window throughout):
```
jupyter notebook
```
4. A notebook server should automatically launch in your default web browser (URL should be http://localhost:8888). If this does not happen, read the command prompt output. You can copy and paste the above URL into your web browser to access Jupyter Notebook.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
```
Tasks-2020.ipynb
```
7. The notebook should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.

### 4.3 Libraries
The following Python libraries were used in the writing of the programs code and are required to successfully run the programs:
* XXXXXXX

## 5 Summary, Conclusion and Future Analysis of the Tasks 2020 Assesssment
------------------------------------------------------------------------------------------------
In summary 

In conclusion 

In terms of future analysis of the *Tasks 2020* Assessment

## 6 References
------------------------------------------------------------------------------------------------
References will be indicated numerically throughout the Jupyter Notebook and will be listed in full at the end.

## 7 Bibliography
------------------------------------------------------------------------------------------------
Within the course of this assignment the following sources were used for research purposes:

### Task 1 - Counts

### Task 2 - Dicerolls

### Task 3 - numpy.random.binomial

### Task 4 - Simpson’s Paradox