# bimm143-project3

This is my final draft of Project 3 for BIMM143 (SP21).

**Scientific Question**: Does the postmortem interval have a negative impact on RNA integrity of normal human tissue?

**Scientific Hypothesis**: If there is an increase postmortem interval (PMI), then there will be a inverse, linear change in RNA Integrity Number (RIN).

To run this project, two files are required:
* Project 3 Final.ipynb
* Project 3 Data.csv

Information about where data was sourced:
		To locate the data in _Project 3 Data.csv_, I searched through the PubMed database using the query: "PMI AND RIN." PMI and RIN values for the bioinformatics analysis in this project were obtained from a data table (Table 4 in Fan et al. [2016]). The information from the data table was copied and pasted into Excel and downloaded as a CSV file. Non-numerical values were edited, so that unspecified values ("> 24") were removed and not included in data analysis. Asterisks were removed from any starred values to ensure float type conversion and were included in data analysis. 
		
The output of this project includes linear regression analysis; this was visualized through scatterplots and the linear regression model.
