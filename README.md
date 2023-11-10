# CIND860-Capstone-Project
This repository includes all the files from CIND860 Capstone Project course taken at TMU during the Fall 2023 term.

This is my very large file for my Fashion MNIST Train dataset(the test dataset is already attached in the main repository):
https://drive.google.com/file/d/1x3TFYN3F1501BGHap4jqohOpI4JougqH/view?usp=share_link


For the Iniital Results & code part of the project, the top 20 pixels were used based on the Random Forest Importance (RFI) Embedded technique on the test dataset.
This was used as the system crashed if too much memory was consumed (from using the top 5-10% of the overall test dataset), so only top 20 were considered.
The .html of the pandaprofiling report will be updated and posted on this repository along with the source code in .ipynb format (done on Google colab).
There were 3 pandaprofiling report submitted on this repository (one for the train set - 60k rows, one for the test set - 10k rows, 
and the other was combined between train & test - 70k rows) for the top 20 pixels ranked according to Importance (based on RFI- 100 trees).


*** The main .csv file that the .ipynb file was read from was the "combined_top_20_pixels_with_labels.csv" consisiting of 70,000 rows with 21 columns (column 1 being the dependent variable, the other
20 columns being the top 20 pixels) and the main pandaprofiling report was "combined_top_20_pixels_report.html" where the EDA was done. However, I attached the pandarprofiling report for both the training &
testing set for top 20 pixels in .csv format as well as the pandaprofiling report for extra reference.



The "Initial Results & Code [FINAL DRAFT].docx" is the word document containing the screenshot of the code along with the explanations and the results that were given in the output and 
"CIND860_InitialResults_Code.ipynb" is the official .ipynb notebook of the code for the initial results of this project. This was done on Google colab (using GPU runtime) and may not work with other editors.
