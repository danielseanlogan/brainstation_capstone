BrainStation Final Capstone Submission:
------------------------------------------------------------
My project involved two CNN classification tasks based on images of skin lesion.

These classification tasks were:

-	Whether or not a lesion suggests an elevated risk of cancer.

-	What the precise classification of a lesion is.

Contents
------------------------------------------------------------

In this folder, you will find the following:

-	Tableau File - Contains a single visual created out of a .csv file which is created upon the successful execution
	of the second notebook file (Notebook 2; EDA and Image Preprocessing).

-	Business Report - Contains a pdf version of this project's final business report

-	Notebook 1; Importing Our Data - In this notebook, all of the image data and metadata nessassary for this project
	are retrieved from a public google drive folder and unziped into the working directory.

-	Notebook 2; EDA and Image Preprocessing - In this notebook, I loaded in data aquired from the previous step, conducted
	EDA and cleaning on our metadata, and sorted and preprocessed our image data to be ready for modeling.

-	Notebook 3; Cancer Risk CNN Modeling - In this notebook, I loaded in our preprocessed image data to perform CNN modeling
	for our binary classification task. Then, I created models, fitted them, evaluated them, and improved them until I was
	satisfied with model performance.

-	Notebook 4; Lesion Type CNN Modeling - In this notebook, I loaded in our preprocessed image data to perform CNN modeling
	for our categorical classification task. Then, I created models, fitted them, evaluated them, and improved them until I
	was satisfied with model performance.

-	README - This file.

-	requirements - A text file containing a script which can be run in an anaconda prompt to set up a kernel capable of running
	all of the notebooks in this project.