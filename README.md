Software Requirements
---------------------
Python 3.2.0

Import matplotlib.pyplot, numpy, and sys.

How to retrieve program
-----------------------
Go to githup.com/ddnguyen666/p1-start.
Can either download or clone files.

Instructions
------------
1. Change your directory to p1-start/, otherwise it will not work.

2. To start generating your stress-strain curve, type python ploy.py raw-data/[data file name].

3. Press enter to run the command your graph will appear on another window.

4. A .png of the graph will automatically be saved in the raw-data folder.

5. Once the graph is closed, the Young's modulus will show.



Example
-------
Generate a graph for one of the aluminum specimens

Step 1: Change directory
$ cd p1-start/

Step 2: Generate stress-strain curve
$ python plot.py raw-data/aluminum-specimen-1.raw

Step 3: A graph will appear

Step 4: Close graph window, Young's modulus will appear above command line
Young's Modulus: ?????? MPa


When starting this project, I had difficulty in conceptionalizing how to use python in bash as I thought they were two completely different programs. Additionally, I wasn't sure how the material we have learned using the jupyter notebooks would translate to bash as I felt that each program used different commands. Throughout this project I was able to better understand how python and bash operate together when generating a graph. It didn't click until the script I created looked just like one of our homework assignments where we had to generate a scatterplot graph. Once I was able to comprehend what I was doing, it made the rest of the process easier to complete.
