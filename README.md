
## My_Netflix_data_analysis
Using my Netflix account data that was aquired by submitting a request to Netflix, I will analyze my viewing habits of the household and visualize some of my findings.  This project was very informative in that I was not aware of all the different data that Netflix actually collects from its users.  I have used my viewing activity dataset along with a dataset from Kaggle.com to get movie ratings to compare what ratings have been viewed the most along with several other findings of my data.



# Getting the Program to Run:

Confirm that a version of Python 3 has been installed on your local machine

Use Git Bash and navigate to where you would like the cloned repository using CD'command(the desired path)

Clone the repo from github.  git clone https://github.com/darrenc9828/My_Netflix_data_analysis

I used VS code for this project with Jupyter Notebook extensions installed along with a virtual environment.  To install and run a virtual environment please see the bottom of this README file.  Once you created the virtual environment please install the necessary requirements for this project by using the below command in you terminal

pip intall -r requirements.txt

Once this setup is complete open the Jupyter Notebook file: My_Netflix_data_analysis.ipynb

You could also run the file above in Jupyter Notebook:

Navigate to the command promt. 

From the command line, run "jupyter notebook", this will open a browser window.

From the browser window open "My_Netflix_data_analysis.ipynb",to run the program.

Once you have opened the file click "Run All' on the top of the notebook.

## Requirements

Requiremnets are from the project requirements list from Code Kentucky list of requirements for Data analysis part 2:

1. Read in data: Read in two data files. This project consist of two csv files that used the pandas function in the pandas python package to   read the files to create dataframes.

2. Manipulated and cleaned the data: Used built-pandas and numpy functions to remove such things as NAN values in the data. Also used other pandas functions to manipulate the data to provide new values such as renaming of columns and merged the dataframes later in the project to get other data into one datafrmae table.

3. Visulize/Present the data: Make at least 3 visualizations. I use matplotlib and seaborn libraries to do these visulalizations. 

4. Utilize best practices.  I created a virtual environment for my project.  Instructions on how to set a virtual environment are listed below.

## You will need to use your terminal to create a virtual environment and be sure you have Python 3 or higher installed on your machine.
    Creation of virtual environments is done by executing the command venv:

    python3 -m venv /path/to/new/virtual/environment

    Example would be - c:\user\myfolder\destop> python -m venv venv

    Once you create this environment you will need to activate this environment.  To do this you will need to type environment name\Scripts\Activate.bat or you may have to use 
    environment name\Scripts\Activate.ps1
    

    See below if the procedure does not work on your machine.  Sometimes windows have a policy set that will not let you activate the environment on VS code editor. 

    Activiating a virtual environment in windows using VS code you will need to Run powershell in administrator mode and copy and paste this command: set-executionpolicy remotesigned ; then agree to the message.  Finally, Run your_virtualenv_name\Scripts\activiate.ps1

5. Interpretation of the data. I have used markdown cells in Jupyter Notebook to do this interpretation of my code.

All work in this repo has been done by the owner Darren Caldwell 