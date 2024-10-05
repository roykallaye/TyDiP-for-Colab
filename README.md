Adapted Regressor for Google Colab
This repository contains an adapted version of regressor.py specifically tailored to run in the Google Colab environment. It serves as a component of the original project, TyDiP, which trains a model on a large annotated English dataset. The project aims to analyze and interpret sentences from a test file for politeness annotations.

Overview
The model processes a test dataset and predicts politeness scores, providing insights through metrics such as F1 scores and accuracy. The outputs are structured in a comprehensive format that includes:

Sentences: The input sentences from the test file.
True Scores: The actual politeness scores.
True Labels: The actual labels indicating politeness.
Predicted Labels: The model's predictions.
Politeness Probabilities: The likelihood of each sentence being polite.
Impoliteness Probabilities: The likelihood of each sentence being impolite.
Additionally, the results are extracted into a CSV or Excel file, which can be utilized for further investigation and analysis.

Requirements
This version of the project requires the original files from the TyDiP repository. Please ensure you have access to the complete original project for all necessary components.

Setting Up in Google Colab
To successfully run this project in Google Colab, you will need to:

Authorize Google Drive Access: If you have the original project folder stored in your Google Drive, you will need to authorize access to it in your Colab environment. This allows you to load the necessary files directly from your Drive.

Upload Test Files: You can add different test files in the correct CSV format for various languages. Ensure that the structure of the test files matches the expected input format.

Getting Started
Clone this repository to your Google Colab environment.
Ensure that you have the original TyDiP project files accessible.
Authorize access to your Google Drive when prompted.
Upload your test CSV files and run the adapted regressor.py to start the analysis.

License (MIT)
Please refer to the original TyDiP repository for licensing information regarding the source code.
