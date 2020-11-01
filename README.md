# covidtracking
Track covid19 in France

# Dependencies
numpy==1.15.4
pandas==0.23.4
pygsheets==2.0.3.1

# Description
This program aims to update a google spreadsheet with the lastest covid19 data provided by gov website.
It works this way:
  1- load raw data from gov github (https://raw.githubusercontent.com/opencovid19-fr/data/master/dist/chiffres-cles.csv)
  2- clean and process data
  3- open google spreadsheet (using credentials) and update it ()
  4- the google spreadsheet is data source for datastudio vizualisations (https://datastudio.google.com/reporting/cc122660-88e2-4778-adf2-884a999d94b7/page/hxDIB)
  
  # Executing program
  First install dependencies using "pip install lib_name"
  Then run main.py file (python main.py)
