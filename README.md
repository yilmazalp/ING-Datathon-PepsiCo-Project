# ING-Datathon-PepsiCo-Project
This competition is organized with the cooperation of ING, PepsiCo, and the Student Club of Operational Research at Bogazici University. In this competition we will work with a challenging time-series data set consisting of monthly sales data for 3 years. This sales are only Snacks data in PepsiCo for 500 customers (grocery, kiosk etc) with their demographic data, placed in Istanbul Turkey. We are asking you to predict total sancks sales for every store in the next months.


You are provided with monthly historical snacks sales data. The task is to forecast the total amount of products sold in every shop for the test set. Creating a robust model that can handle such situations is part of the challenge.


## File descriptions

- testtrain.csv - monthly snacks data in Istanbul Turkey. You are expected to split this file into train and test. It contains following information for the dates between January 2017 – July 2019.
- samplesubmission.csv - The file contains store id with expected months to be forecated.


## Data fields

- ID - Customer ID
- Date - Sales date between January 2017 – July 2019
- KG_N - Sales quantity for snacks
- Age_0btw14 - Consumer profile around store age between 0 and 14
- Age_15btw24 - Consumer profile around store age between 15 and 24
- Age_25btw34 - Consumer profile around store age between 25 and 34
- Age_35_plus - Consumer profile around store above 35
- SES_AB - Consumer profile around store socio economic statu AB
- SES_C - Consumer profile around store socio economic statu C
- SES_DE - Consumer profile around store socio economic statu DE


NOTE : In the sample submission ID & Date are given in same column.
