# COVID-19-Transmission

This repository includes preprocessing scrips, datafiles, analysis scrips and figures of the analysis of tranmission of COVID-19 in the 98 different municipalities of Denmark.

## There are three folders in the repository:
### "Data Files"
#### Contains all the data referenced in the R-Markdowns. The only exception is for the DMI weather data which can be found here: https://dmigw.govcloud.dk/metObs/v1/bulk/?api-key=e32551a3-e242-45ae-8480-6129201f9a4c.
#### I have made it possible to reproduce the analysis, however in the R-Markdown scripts i sometimes write CSV-files which then can be found in this folder.

### "R-Studio Scripts and Functions"
#### This folder contains three files, a file for a preprocessing function i use to clean the DMI data from the above link. The folder which i am referencing needs to be changed to your own if you wanna reproduce the file, or else the preprocessed data can be found in the Data Files folder.
#### Secondly, the folder contains a preprocessing script, this is for the people that want to reproduce and possibly add new months to the analysis. Caution need to be made as the Danish Government chose to change the way in which they record number of cases in the middle of march.
#### Thirdly, the folder contains an analysis script. This contains the code for running the mixed effects model, making model comparison, getting summary of the model and reproducing the plots from the analysis.

### "Figures"
#### Contains the figures from the analysis, that can be reproduces with the Data Analysis Scrips.

Do not hecitate to contact me if you need help with running the preprocessing or scripts. I can be contacted via the email: lassehyldigh@gmail.com

Best,
Lasse Hyldig Hansen
Cognitive Science
https://scholar.google.com/citations?user=ocLAv8EAAAAJ&hl=da
