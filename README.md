# high-school-sat-scores

This project focuses on data cleaning. The efficacy of standardized testing has often been called into question. The purpose of this project is to find correlations between SAT scores and factors like gender, race, etc. and determine if standardized testing is unfair to certain demographics.

New York City makes its data on high school SAT scores and the demographics available online. The data sets were obtained [here](https://opendata.cityofnewyork.us/) and were renamed for the sake of convenience. The following data sets were used for this project:
File name | Description | Link
--- | --- | ---
`ap_2010.csv` | Data on AP test results for each high school | [Link](https://data.cityofnewyork.us/Education/2010-AP-College-Board-School-Level-Results/itfs-ms3e)
`class_size.csv` | Data on class sizes for each high school | [Link](https://data.cityofnewyork.us/Education/2010-2011-Class-Size-School-level-detail/urz7-pzb3)
`demographics.csv` | Data on demographics for each high school | [Link](https://data.cityofnewyork.us/Education/2006-2012-School-Demographics-and-Accountability-S/ihfw-zy9j)
`graduation.csv` | Data on graduation outcomes and other information | [Link](https://data.cityofnewyork.us/Education/2005-2010-Graduation-Outcomes-School-Level/vh2h-md7a)
`hs_directory.csv` | A directory of high schools | [Link](https://data.cityofnewyork.us/Education/2014-2015-DOE-High-School-Directory/n3p6-zve2)
`sat_results.csv` | Data on SAT scores for each high school | [Link](https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4)
`survey_all.txt` | Data on surveys from all schools | [Link](https://data.cityofnewyork.us/Education/2010-2011-NYC-School-Survey/mnz3-dyi8)
`survey_d75.txt` | Data on surveys from NYC distrct 75 | [Link](http://schools.nyc.gov/academics/specialEducation/D75/default.htm)

All these data sets are related, and combining them to a single data set would make analysis more efficient. Each high school has a unique code called DBN, which would allow us to sort high schools based on district. `00_Cleaning&Visualization` contains all the code and visualizations. Pandas and numpy were used for the analysis, and matplotlib was used for visualization. Additionally, basemap was used for plotting high school safety zones on a map of NYC.
