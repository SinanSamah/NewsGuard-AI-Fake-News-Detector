Project Submission README

This file explains all the files and folders in the project submission. It is organized into documents, presentation files, and the source code.


Main Directory 

groupDeclarationSheet.docx
This document shows who did what in the team, as required by the assignment.

NewsGuard Demo.mp4
A video showing how the NewsGuard AI app works.

NewsGuard_AI_Presentation.pptx
The slides for our final project presentation.

NewsGuard_AI_Report.pdf
This is the main project report. It explains everything about the project, from the idea to the final results.

NewsGuardAI_UserGuide
This is the user guide, it contains steps for end users to deploy locally and markers to regenerate results.

Source Code/
This folder has all the code, notebooks, and models for the project.


Source Code Folder

    Google_Colab_Files Folder 
    This folder contains the notebooks used to develop and train the AI model.

    	ICT304_Assignment1_BaseLine_LSTM...ipynb
    	This notebook was used to create a simple 'baseline' model to compare our main model against.

    	ICT304_Assignment1_Main_LSTM_Final.ipynb
    	This is the main notebook where we did all our work. It shows how we explored the data, prepared it, and trained 	our final AI model.


    Streamlit_Code Folder
    This folder contains all the files needed to run the NewsGuard AI web app.

    	.streamlit/
    	A folder that holds the secrets.toml file for the NewsAPI key.

    	main_app.py
    	The main script that you run to start the web app.

    	utils.py
    	A helper file with all the important functions that main_app.py uses.

    	complete_fake_news_model.h5
    	The saved AI model that checks if a news article is real or fake.

    	tokenizer.pkl
    	A file that turns words from articles into numbers for the AI model.

    	isotonic_calibrator.pkl & calibration_models.pkl
    	These files help make the AI's confidence score more accurate.

    	requirements.txt
    	A list of all the code libraries you need to install to run the project.

    	download_nltk.py
    	A small script that downloads data needed for processing text.

    	python-3.11.9.exe
    	The installer for the recommended version of Python (3.11.9).

    	__pycache__/ , newsguard.log , 2.13.0
    	These are auto-generated files and logs. You can ignore them.