<img align="centre"  width="500" height="500" img src="https://i0.wp.com/www.creatingentrepreneursinfood.eu/wp-content/uploads/2017/02/GMIT-logo.png">

# Fundamentals of Data Analysis: Tasks 2020 Assessment

* **Author:** John Paul Lee
* **Github:** JPLee01
* **Email:** G00387906@gmit.ie
* **Created:** 09-10-2020, **Last update:** 18-12-2020
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
This repository has been created as part of the assessment of the Fundamentals of Data Analysis module. The aim of this assessment is to help the student gain an understanding and confidence in tackling the type of tasks a Data Analyst may face in their line of work. Four seperate tasks have been laid out each with a detailed explanation of the task and the accompanying solution. The four tasks and solutions will be conducted through a Jupyter Notebook which will contain markdown text, images, Python code and Plots.

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
As part of the assessment, the student was given a set of instructions which can be viewed [here](https://github.com/JPLee01/Tasks-2020/blob/main/Assessment%20Instructions.pdf). As seen, within the instructions a set of four tasks were printed. These tasks were the basis of the assessment and were described as follows:

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
The following Python libraries were used in the writing of the programs code and are required to successfully run the program:
* [Numpy](https://www.numpy.org/) - Used for mathematical functions in the [Tasks-2020.ipynb](https://github.com/JPLee01/Tasks-2020/blob/main/Tasks-2020.ipynb) notebook.
* [Matplotlib.pyplot](https://matplotlib.org/tutorials/introductory/pyplot.html) - Used for the manipulation of elements and the creation of certain plots graphs within the [Tasks-2020.ipynb](https://github.com/JPLee01/Tasks-2020/blob/main/Tasks-2020.ipynb) notebook.
* [Seaborn](https://seaborn.pydata.org/) - Used for the manipulation of elements and the creation of certain plots graphs within the [Tasks-2020.ipynb](https://github.com/JPLee01/Tasks-2020/blob/main/Tasks-2020.ipynb) notebook.

## 5 Summary, Conclusion and Future Analysis of the Tasks 2020 Assesssment
------------------------------------------------------------------------------------------------
In summary this repository was created to complete the four tasks laid down in the assessment for the Fundamentals of Data Analysis module. These tasks each dealt with a different area in the field of data analysis and required both research and programming. This assessment tested the author as some of the areas dealt with in the assessment the author had no prior knowledge of. Thankfully through detailed analysis and research the author was able to complete the four tasks. 

In conclusion after completion of the assessment the author feels they have gained an greater understanding into the type of tasks a Data Analyst may face. Due to the four tasks being stand-alone tasks each dealing with a different area extensive research and analysis had to be undertaken. This resulted in the author gaining a broader understanding in the area of data analysis. The author now feels they have a level of confidence with regards to potential data analysis tasks which was not present before undertaking the assessment. The author also feels that this new knowledge, will be of significant benefit as they continue their studies.

In terms of future analysis of the *Tasks 2020* Assessment the scope is endless. In essence, the areas dealt with in the assessment could be analysed up to PhD level. The author in their research discovered some areas in which the tasks could be further researched and alluded to them in their [Tasks-2020.ipynb](https://github.com/JPLee01/Tasks-2020/blob/main/Tasks-2020.ipynb) notebook. With data being described as the new raw material of business topics such as the ones dealt with in the assessment, are more important now than ever.

## 6 References
------------------------------------------------------------------------------------------------
References will be indicated numerically throughout the Jupyter Notebook and will be listed in full at the end.

## 7 Bibliography
------------------------------------------------------------------------------------------------
Within the course of this assignment the following sources were used for research purposes:

### Task 1 - Counts
* Code Academy - "for x in list" verses "for x in range(len(list)), <https://www.codecademy.com/forum_questions/558ae27493767630000004f5?locale=en> 

* Gabriel Cánepa - Manipulating Lists and Dictionaries in Python, <https://www.pluralsight.com/guides/manipulating-lists-dictionaries-python>

* Geeks for Geeks - Counting the frequencies in a list using dictionary in Python, <https://www.geeksforgeeks.org/counting-the-frequencies-in-a-list-using-dictionary-in-python/>

* Geeks for Geeks - Python | Convert a list to dictionary, <https://www.geeksforgeeks.org/python-convert-a-list-to-dictionary/>

* Geeks for Geeks - Python | Count number of items in a dictionary value that is a list, <https://www.geeksforgeeks.org/python-count-number-of-items-in-a-dictionary-value-that-is-a-list/>

* Geeks for Geeks - How to count unique values inside a list, <https://www.geeksforgeeks.org/how-to-count-unique-values-inside-a-list/>

* Grepper - find number of unique keys in the dictionary, <https://www.codegrepper.com/code-examples/python/find+number+of+unique+keys+in+the+dictionary>

* Jamel Dargan - Create a Dictionary From a List, <https://medium.com/swlh/create-a-dictionary-from-a-list-65742246ab4b>

* Stack Overflow - Count how many times a dictionary value is found with more than one key, <https://stackoverflow.com/questions/18582370/count-how-many-times-a-dictionary-value-is-found-with-more-than-one-key>

* Stack Overflow - python dictionary count of unique values, <https://stackoverflow.com/questions/16406329/python-dictionary-count-of-unique-values>

* Xspdf.com - Python dictionary count values per key, <https://www.xspdf.com/resolution/50472727.html>

### Task 2 - Dicerolls
* Dapper Dino - Python Tutorial 4 - Simple Roll A Dice Task, <https://www.youtube.com/watch?v=PN5Mx_Ajrzs>

* Data Science Unlimted - Step By Step: Coding A Dice Roll Simulator In Python, <https://datascienceunlimited.tech/step-by-step-coding-a-dice-roll-simulator-in-python/>

* Hamza Hesham - Dice rolling game using python, <https://dev.to/oxy_oxide/dice-rolling-game-using-python-pn>

* PYnative - Python range() function explained with examples, <https://pynative.com/python-range-function/>

* Python for Beginners - Python Game : Rolling the dice, <https://www.pythonforbeginners.com/code-snippets-source-code/game-rolling-the-dice>

* Rebeca Ansar - How to Simulate a Dice Roll and Guess the Result in Python, <https://medium.com/an-amygdala/how-to-simulate-a-dice-roll-and-guess-the-result-in-python-9785079af6f3>

* Stack Overflow - Dice rolling simulator in Python, <https://stackoverflow.com/questions/44008489/dice-rolling-simulator-in-python>

### Task 3 - numpy.random.binomial
* Prashanth Gowda - Biased Coin Flipping simulation in Python, <https://www.codespeedy.com/biased-coin-flipping-simulation-in-python/>

* R Pubs - Takes 1 random sample from the vector (in this case, c(“heads”, “tails”) you supplied in the first argument, <https://rpubs.com/DThurtleSchmdit/530416>

* Stack Overflow - Binomial distribution simulation python, <https://stackoverflow.com/questions/63839778/binomial-distribution-simulation-python>

* Stack Overflow - binomial distribution using numpy, <https://stackoverflow.com/questions/62305011/binomial-distribution-using-numpy>

* Stack Overflow - Python Coin Toss, <https://stackoverflow.com/questions/14882530/python-coin-toss>

* Stack Overflow - Random experiment of Binomial distribution using stats in python, <https://stackoverflow.com/questions/55113404/random-experiment-of-binomial-distribution-using-stats-in-python>

* w3schools.com - Binomial Distribution, <https://www.w3schools.com/python/numpy_random_binomial.asp>

### Task 4 - Simpson’s Paradox
* Aleix Ruiz de Villa - Solving Simpson’s Paradox, <https://towardsdatascience.com/solving-simpsons-paradox-e85433c68d03>

* California DDS Expenditures - Simpson’s Paradox - In Python, <https://www.kaggle.com/saicataram/simpson-s-paradox-in-python>

* Encyclopædia Britannica -Simpson's Paradox, <https://www.britannica.com/topic/Simpsons-paradox>

* Geek for Geeks - Different ways to create Pandas Dataframe, <https://www.geeksforgeeks.org/different-ways-to-create-pandas-dataframe/>

* Judea Pearl - Understanding Simpson’s Paradox, <https://ftp.cs.ucla.edu/pub/stat_ser/r414.pdf>

* Lucy Hornby et al. - China fake data mask economic rebound, <https://www.ft.com/content/a9889330-f51c-11e7-88f7-5465a6ce1a00>

* note.nkmk.me - pandas: Rename index / columns names (labels) of DataFrame, <https://note.nkmk.me/en/python-pandas-dataframe-rename/>

* Numpy 1.19 Manual - numpy.linspace, <https://numpy.org/doc/stable/reference/generated/numpy.linspace.html>

* Shanto Roy - Creating Bar Charts using Python Matplotlib, <https://shantoroy.com/python/python-bar-chart-using-matplotlib/>

* Stack Overflow - How to create a dataframe from numpy arrays?, <https://stackoverflow.com/questions/53820131/how-to-create-a-dataframe-from-numpy-arrays/53820222#53820222>

* Will Koehrsen - Simpson’s Paradox: How to Prove Opposite Arguments with the Same Data, <https://towardsdatascience.com/simpsons-paradox-how-to-prove-two-opposite-arguments-using-one-dataset-1c9c917f5ff9>