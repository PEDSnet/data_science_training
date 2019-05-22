#PEDSnet Data Science Training Series

## Session 2 Exercise

The purpose of this exercise is to familiarize you with the specifications form and the process of converting a data request to a scientific query. The assignment will be divided into the following sections:

* Part 1: Request Description 
* Part 2: Initial Response and Discussion with Investigator
* Part 3: Specification Form
* Part 4: Finalizing Output
* Part 5: Considerations

Please save all responses to this exercise in the folder (last name first initial) that you created for the first exercise. Answer all open-ended questions in a file called **session_2_exercises**. Also save a copy of the PEDSnet specification form in your folder and populate the appropriate sections according to the specifications in **Part 3**.


### Part 1. Request Description 

An investigator is recently funded to conduct a study using PEDSnet data that characterizes seizure disorders among children with autism spectrum disorder (ASD). The investigator will also identify differences in treatment and outcomes in children with ASD with and without seizure disorders. Therefore, the cohort of interest is all children with autism in PEDSnet, but `cases` also have accompanying seizure disorder and `controls` do not. Treatments in this study are usually drugs that are commonly taken in children with autism such as anti-stimulants and anti-psychotic medications. However, the investigator does not have a complete list. Outcomes are those associated with healthcare utilization (e.g., hospitalizations, ED visits, imaging studies, and more frequent care by a specialist).

The investigator is asking to pursue the study in two stages.  The first is a feasibility request that determines whether there are enough patients in each subset and whether there are broad differences in outcomes.  If this suggests adequate patients, then the team proposes to look at associations using modeling of each patient's treatment course.

### Part 2: Initial Response and Discussion with Investigator

Based on the information in Part 1, please describe how you would approach the investigator in learning more about the study as well as any questions to the PEDSnet Program Management Office (PMO) regarding initial study startup. 

In responding to this question, remember the three essential categories of information required to move forward with a query:

* Query Purpose 
* Query Evaluation
* Query Output

Specifically, your response should address the following questions:

* _Is there any extra information required to understand the purpose of the query better?_
* _How will you determine complexity? What are the factors that you will consider?_
* _What are the questions you will need to ask the PMO to understand this study in the context of other PEDSnet activity?_
* _What are your initial thoughts about what the final product will be? Do you need to ask any questions of clarification around this? What are some items to consider when thinking through the final output?_

Additionally, please provide a brief description of the process of working with this investigator once you have the initial information covered. What are the major milestones and how will you engage the investigator at each stage?  What will differ in the way you approach the data for each of the two stages?

### Part 3: Specification Form

The goal of the PEDSnet Specification Form is several-fold. First, it provides a roadmap for both the DCC (i.e., the people with access to the data) and the study team to move forward with a data request. Second, it should serve as the source of truth so that everyone relies on written documentation in a central location rather than distributed materials. Third, the form can either contain all the information for the query or point to directories in the repo where the information can be found. This flexibility is needed, since the detailed documentation for a study can be complex. 

In this section, please respond to the following questions with regards to the initial query described in Part 1:

* _How will you approach the specification form? Which sections will you address first?_
* _How might you use the data initially to determine the creation of the complete dataset?_
* _What are your initial thoughts on what the output structure might look like for stage 1?_
* _What are the major options for executing stage 2?  How will the structure of the dataset change for each?_

Additionally, please complete the following sections of the PEDSnet specification form for the first part of the query (the characterization):

* **Variable Identification**
* **Logic Rules for Query**
* **List of Codesets**

To complete these sections, suppose that you have had a couple of discussions with the investigator and have made some decisions about the variables and the initial logic for the feasibility portion of the study. Complete these two sections of the specification form based on these assumptions. 

For the List of Codesets, you will **not** be expected to actually create codesets. You should instead just the list of codesets that you would need to create for **both** the feasibility and modeling portion of the query. As an example, you know you will need a codeset for autism as well as seizure disorders. There may be some assumptions that you will have to make about the variables needed for the study to complete the rest of this section. This is expected and we understand that during an actual study, these would need to be discussed with the investigator. However, please complete this section based on your knowledge of the study, potential variables you will need for identifying events or patients (e.g., in addition to a diagnosis code, would a specialist need to be seen for an autism disorder?), as well as the codesets you will need to identify the potential covariates and outcomes for the study.


### Part 4: Finalizing Output

Based on what you understand from this query type and the associated output,  **please complete the section of the form called *Output Structure* for the first stage of the query.** 

While this part usually does require conversation with the study team, investigators often rely on those with the data expertise to lead the conversation and provide suggestions for the output tables. In Part 3, you described what your initial thoughts might be in the structure. In this section, please complete the form based on your initial set of assumptions.

**Additionally, please provide a description of how stage 2 output might differ.** As a reminder, stage 1 was the feasibility portion and stage 2 likely involves non-aggregate output.

### Part 5: Considerations

The query process can be deceptive in that many people who are not accustomed to working with the data have limitations in their understanding of how complex clinical data can be. Additionally, as data stewards, we have a lot to consider when constructing a dataset, both in returning a product that is usable by the study team but also limiting the output to the minimum amount necessary to conduct the study. 

Given this context, please provide a response to the following questions:

* _How would you evaluate the quality of the data before release?_
* _Intermediate tables are necessary when creating subsets of the data for study purposes. What would be some ways that you would make use of intermediate tables? What would be the content of these tables?_
* _What would you consider in weighing the amount of data you provide to the investigator? For example, if the investigator says to just provide them with every single data element, what would be your response? How would you narrow down the content of the data?_
