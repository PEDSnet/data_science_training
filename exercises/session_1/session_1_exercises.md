#PEDSnet Data Science Training Series

## Session 1 Exercises

### 1. Test workspace

1. Connect to the PEDSnet VDI instance at CHOP, using the instructions provided.
2. Once you have started a session, create a working folder:
  1. Right-click on the desktop, and select `Open Terminal`
  1. In the window that opens, type **ln -s /mnt/isilon/PEDSnet\_Projects/data\_science\_training ~/Desktop/ds\_training**
  1. Exit the window
  1. Open the `ds_training` shortcut.
  1. Create a new folder using your last name and first initial as the folder name.
1. For the exercises that don't give other instructions, please save the answers to the questions in a file in this directory named **session\_1\_exercises**.

### 2. Test R

1. Launch RStudio
1. Create a tibble or dataframe containig four elements
	* `name` - your name (string)
	* `date` - today's date (date)
	* `site` - name of your institution (string)
	* `temp` - the current temperature where you are (number)
	
	If you have difficulty writing R code to produce this, please reach out to the DCC.
3. Save that data to a CSV file, named **session\_1\_demo.csv**, in the folder you created above.  (Hint: use `write_csv()`)
4. Save the R script using RStudio into the folder you created above, naming it **session\_1\_demo.R**.

### 3. Test database

1. Launch postbird
1. Establish a connection to the training database
  * host = **SENT OUT IN EMAIL**
  * database = **data\_science\_training**
  * Use your CHOP username and password
1. Using the `Content` tab and search bar, find the standard concept for each of the male, female, and unknown/other genders.


### 4. Find codes

1. Using [https://mor.nlm.nih.gov/RxNav]()  or another tool of your choice, please construct a list of RxNorm terms or terms on the ATC hierarchy you would use to find patients with systemic exposure to calcineurin inhibitors.
2. Using [https://athena.ohdsi.org]() or another tool of your choice (e.g., the OHDSI vocabulary tables), find the values you would expect to see in the `drug_exposure` table for this exposure.

### 5. Find patients

You have been asked by an investigator to estimate how many patients were given antibiotics in the emergency department for cellulitis, but did not need to be admitted for treatment.  Please describe how you would approach this using the PEDSnet CDM.  You don't need to create codesets or write query code, but please describe each table you would use, and which columns in each table you would consult.
