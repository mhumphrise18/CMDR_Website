# CMDR_Website
This is a repo that I am working on to see if I can build out a website that pulls in a bunch of different reports that the army gives commanders and combine them into one easy to read report

Currently it is set to only read .xlsx or .csv files

## Steps to run website
1. Go to the following websites and pull all of the reports that are needed
* MEDPROS (MRC/DRC)
* AFAM (TAOD, Reservation & Wait Report)
* IPPS-A 
* EES (O/NCOER)
* iPERMS (DD93, SGLV, etc.)

- the unique key is the first & last name of the soldier

2. You then will save them all in the same folder on your local machine
3. From there you will double click on CMDR_Website.html from the folder & it will give you a very basic page. 
4. You will want to click the button that allows you to upload files
	- Quick shortcoming of the site, you have to load them all at the same time
	- it should tell you how many files you uploaded once you hit OK
5. From there you can hit export & it should combine all of the reports you provide into one single excel spreadsheet that you can then understand the Soldiers status across a plethura of different systems. 


# Future work:
- I want to have it so that you can drag & drop files into the website
- I want to have the functionality to be able to preview the new spreadsheet prior to exporting it
- I want to have the ability to pick and choose what is going to go into the spreadsheet from each file
- The ability to auto-detect duplicate information/conflicts and show warnings
- Provide a progress bar of some sort so that you are able to when the files are done uploading   
