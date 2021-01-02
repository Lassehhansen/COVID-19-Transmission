# COVID-19-Transmission

This repository includes an analysis of the tranmission of COVID-19 in the 98 different municipalities of Denmark.

# The first file in the repository is the R Markdown in which the analysis is done

The code starts off with a function that takes zip-files of weather data from DMI and cleans it for accessible use for a 2SLS analysis.

Furthermore, it moves on to load in COVID-19 data from SSI. 

Therenext, data from Danish Statistics is loaded in and merged with both the weather variables and cases per test from SSI.

Lastly, Google Mobility data is loaded in, merged with the rest and the data is then analyzed.

This combined Markdown document should be able to reveal which effect demographic data from the different municipalities has on the tranmission of COVID-19 in Denmark. Furthermore, it should also reveal how government restrictions and mobility data from the people of Denmark influences cases per test.

# The two other files contains a variable importance plot and a plot of tranmission over time in Denmark
