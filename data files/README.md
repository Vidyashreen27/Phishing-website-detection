DATA FILES
This folder contains all the raw and processed datasets used in the phishing website detection project. Below is a brief description of each file:

Benign_list_big_final.csv
Contains 35,300 legitimate URLs sourced from the University of New Brunswick's dataset.
Source: https://www.unb.ca/cic/datasets/url-2016.html

online-valid.csv
A collection of phishing URLs obtained from the open-source service PhishTank. This dataset is updated regularly.
Latest data available at: https://www.phishtank.com/developer_info.php

legitimate.csv
Contains extracted features of 5,000 legitimate URLs, randomly selected from the Benign_list_big_final.csv file.

phishing.csv
Contains extracted features of 5,000 phishing URLs, randomly selected from the online-valid.csv file.

urldata.csv
A combined dataset of 10,000 URLs (5,000 phishing + 5,000 legitimate), with all relevant extracted features used for training and evaluating machine learning models.
