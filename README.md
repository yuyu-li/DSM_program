# Psychiatric Hospital Records

The purposes of this program are:
1. to keep a database of patients,
2. to simplify the process of going through the diagnostic criteria for psychological disorders, and
3. to allow for analysis of data regarding patients.

This project was created because of the need for an alternative format for the Diagnostic and Statistical Manual of Mental Disorders (DSM).
Typically, this is presented in sequential form, and often is in paper format, which might make it difficult for clinicians to diagnose patients in practice.
We implemented a database of patients and their crucial information (ex. symptoms), and loaded in 3 disorders as text files that were be parsed by the program. 
By comparing their symptoms against the criteria for the disorders, the clinician can determine whether they fit the diagnosis or not.

Additionally, after the patients are diagnosed, there is a panel with an analytical feature. This can be used to isolate patients by age, gender, and disorder.
Using this, clinicians can find possible relationships between patient information and diagnosis of a certain disorder, for instance.

The database of patients was implemented using Linked Lists, and the process for determining whether a patient fit the criteria for diagnosis used a heavily unbalanced Binary Decision Tree.

-----
Before using this program, please consult the User's Manual for detailed instructions on how to use the program!
To use the program, open and run HospitalProgram.java.
