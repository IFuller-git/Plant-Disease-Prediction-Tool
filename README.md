# Plant-Disease-Prediction-Tool
A Jupyter Notebook that uses a tool using logistic regression to predict plant disease. The Jupyter Notebook details some of the creation process of the prediction tool and data used. It also features multiple visualizations of the data used, alongside having a section detailing accuracy tests and validation of the predictive tool.

## USER GUIDE
 -- The following steps detail what a user needs to do to install and use the predictive tool:
1.	The user must have Anaconda downloaded onto their system.
•	If the user does not have Anaconda downloaded, they can go to https://www.anaconda.com/download to download it. 
3.	The user must download the current version of the following libraries or ensure they are already downloaded onto their system. Many of these are included in the Anaconda Distribution, but any not included can be downloaded through pip (Python installer for packages) or conda.\
•	Pandas\
•	NumPy\
•	Seaborn\
•	Scikit Learn\
•	Matplotlib\
•	IPython
4.	The user must download the zip file titled ‘C964_Task2_App_IFuller’ onto their system. The zip file is attached to this documentation.
5.	The user must navigate to the zip file in their file directory and extract the file.
•	The user can do this by right-clicking on the zip file and clicking the ‘Extract all’
6.	The user must open Anaconda Prompt and open Jupyter Notebook by entering ‘Jupyter Notebook’ into Anaconda Prompt.\
•	This should open a local host page.
7.	The user must navigate to the extracted ‘C964_Predictive_Tool_IFuller’ folder.
8.	The user must then open the file titled ‘C964_Task2_IsabellaFuller.’\
•	This should open a separate local host page that features the Jupyter Notebook project.
9.	The user must navigate to the ‘Run’ option at the top of the page and click on it. The user must then navigate and click on the ‘Run All Cells.’\
•	This will send the user to the bottom of the page, so the user should scroll to the top of the page.
10.	It is also recommended that if the user does not wish to see the code of the tool, they can navigate to ‘View’ and then click ‘Collapse All Code.’ \
•	If the user wishes to see all of the code, the user can navigate to and hover over ‘View’ and then click ‘Expand All code.’
11.	The user can then navigate the page and the predictive tool. If the user wishes to see any of the code, they can click on the gray boxes that are titled with Python comments in the format ‘#This is a comment.’ This will expand the code and allow the user to see it.
12.	On the page, there are buttons and interactable sliders. All the user must do is click on the buttons and adjust the sliders. \
•	The buttons available allow the user to generate a correlogram (which may take a moment to generate), a pie chart, a prediction based on the values of the sliders, and the accuracy score of the predictive model.\
•	The sliders correspond to four unique values that will be used by the predictive model. The sliders are labeled, representing specific values. 


**To use the predictive model:**
1.	The user must open the Jupyter Notebook page for the project, the details of which are listed in the user guide above.
2.	The user must navigate down the page until they reach the four sliders. These sliders correspond to the values that will be input into the predictive model. So, the user should adjust the sliders to four values that they want to use to determine whether plant disease is likely in an area.
3.	The user must click the button that says ‘Predict.’ A prediction will then be generated and displayed.
