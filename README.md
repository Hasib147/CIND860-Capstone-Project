# CIND860-Capstone-Project
This repository includes all the files from CIND860 Capstone Project course taken at TMU during the Fall 2023 term.

This is my very large file for my Fashion MNIST Train dataset(the test dataset is already attached in the main repository):
https://drive.google.com/file/d/1x3TFYN3F1501BGHap4jqohOpI4JougqH/view?usp=share_link


For the Iniital Results & code part of the project, the top 20 pixels were used based on the Random Forest Importance (RFI) Embedded technique on the test dataset.
This was used as the system crashed if too much memory was consumed (from using the top 5-10% of the overall test dataset), so only top 20 were considered.
The .html of the pandaprofiling report will be updated and posted on this repository along with the source code in .ipynb format (done on Google colab).
There were 3 pandaprofiling report submitted on this repository (one for the train set - 60k rows, one for the test set - 10k rows, 
and the other was combined between train & test - 70k rows) for the top 20 pixels ranked according to Importance (based on RFI- 100 trees).
