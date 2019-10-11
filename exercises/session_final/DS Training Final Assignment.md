#PEDSnet Data Science Training Series

## Final Assignment

### Requirements

The purpose of this assignment is to complete all the steps required in a data request. 

The description of the data request is in the section called **Data Request Overview**. 

The completed assignment will contain the following:

* Scientific Specifications:
	* Completion of all the sections of the specifications form created by the DCC
	* Query logic
	* Field and domain requirements from the CDM
	* Codesets for all variables
	* Listing of intermediate tables
* Reporting of any potential data quality issues and description of how to identify these issues
* Query in the R standard framework developed by Dr. Charles Bailey 
* Report in an R notebook that prints to an HTML or Word document
* Appropriate Jira tasks and BitBucket repository

### Completion Options / Tracks

You have four options for assignment completion; you may choose more than one.  In order to serve as the data center for a PEDSnet projet, a site will need at least 1) one person with Data Science Analyst certification and 2) at least one person with either Clinical Data Researcher or Clinical Informaticist certification on the project.

* **Option A: Clinical Data Researcher** 
	* Scientific specifications (and all components)
	* Description of data quality checks to build into query
* **Option B: ATLAS Specialist**
	* Given a set of specifications, implement in Atlas and provide output
* **Option C: Clinical Informaticist**
	* Scientific specifications (and all components)
	* Description of data quality checks 
	* Specifications implemented in ATLAS and provide output
	* Given output from tables from which queries were run, create final report in R markdown
* **Option D: Data Science Analyst**
	* Given a set of specifications, complete query in standard R framework
	* Final report in R markdown
	
### Data Request Overview

An investigator is interested in the utilization of anti-epileptic drugs (AED) by age group. Her request is to summarize AED utilization across all sites and stratified by age group. 

She is not quite sure what the final report will look like, but she has some ideas:

* The drugs of interest are anti-seizure medications in the ATC class "Antiepileptics". 
* Frequency of use in children with and without a seizure disorder
* Incidence of use per age group per 1000 person-years (roughly: infants, toddlers, children, adolescents)
* Most frequent comorbidities in the age group
* General healthcare utilization patterns in this cohort
* Kidney function, as measured by median (IRQ) serum creatinine, in treated vs untreated patients


Please provide output for all sites. If you are completing specifications and would like to set up a call with the "requestor" (i.e., CHOP DCC team) to answer questions you have about the specifications, please contact us to arrange a call.


