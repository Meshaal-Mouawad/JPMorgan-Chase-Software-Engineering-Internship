![image](https://user-images.githubusercontent.com/72484101/187799604-a75843e0-4669-4b81-87a2-83bbe9ead49c.png)
![image](https://user-images.githubusercontent.com/72484101/187801042-c8b12279-7859-4512-b8ee-a8c4ef266260.png)


# JPMorgan-Chase-Software-Engineering-Internship

# Task 1:
Please do NOT copy my soultions if you are doing your assigntmnt as this will not help you to practice and my not be ethical to do so.

before you start to find the problem in the python files, make sure that you have installed tand set up the enviroment.

Here is my answer

https://github.com/Meshaal-Mouawad/JPMorgan-Chase-Software-Engineering-Internship/tree/main/JPMC-tech-task-1-py3



# Task 2

## Module 2 Task Overview
Use JP Morgan Chase's frameworks and tools Implement JP Morgan Chase’s Perspective open source code in preparation for data 
visualization.

Aim:Take an incomplete setup of Perspective, i.e. a graph that updates manually, and make it work with the code from Task 1 such that it now updates automatically by continuously requesting from the server application.

### Please clone this repository to start the task
1. [goal-a] In the client application, observe that when new data feed is retrieved whenever you click the 'Start Streaming Data' button, the previous entry is re-entered into the table. Update the application so that the table does not have duplicated entries.
2. [goal-b] We also want the react app to keep continuosly requesting data from the python server. Currently, the data feed is called only once every time the 'Start Streaming' button is clicked. Change the application to continuously query the datafeed every 100ms when the 'Start Streaming' is clicked.
3. [goal-c] Currently, the Perspective element only shows the data in table view after the data loads. Add Perspective configurations so that when the data is loaded, it shows the historical data of ask_price ABC in the Y line chart.
Upload a git patch file as the submission to this task.

## Set up / Installation
In order to get the server and client application code working on your machine, follow the setup here

Note:This is the version of the JPM 2 exercise that uses Python 3. The Python 2.7 version is in this other repo

## How to Run
Similar to Task 1, start the data feed server by running the python server.

Make sure your terminal / command line is in the repository first before doing any of this.

If you are using Windows, make sure to run your terminal/command prompt as administrator.

python datafeed/server3.py

If you encounter an issue with datautil.parser, run this command:

pip install python-dateutil
If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run npm install && npm start to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have npm (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.

## Known Issues
Some users seem to be having trouble with the unzipped version of the node_modules back up for windows. This is the alternative unzipped version: https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz
Note: You may need to (hard) refresh the link to the public gdrive to see all of the files/folders e.g. @jpmorganchase/perspective as it takes gdrive a bit to load them for you.

## How to fix the code to meet the objectives
To make the changes necessary to complete the objectives of this task, follow this guide.

## How to submit your work
A patch file is what is required from you to submit. To create a patch file, follow this guide. Then submit the patch file in the JPM Module 2 Page.
