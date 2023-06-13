# Automate-report-generator
This project is use to generate report from a row data 

R project includes: 
•	Resources folder 
•	Codes folder 
•	Read me file 
 
The folder of the resources includes data and code-map files. In order to create the “Summary tables,” the code-map is needed. Code-map contains:
•	Old and new Variable names
•	Old and new labels
•	Formulae to create new variables like “qn6” witch extracted from “q6”
 
If we need to change the country codes to standard codes, we can modify the code-map for that purpose. To create “Summary tables,” there is needed to open the Statistical programming roster test.proj on the Rstudio, and after that, open the "Summary Table.Rmd" and  knite that.
 

After running this R markdown file, the “Summary table” report will automatically be generated. 

Note: 

•	For creating a PDF document, LaTEX software is required.

•	The “Table T3_q.rmd” file was used in Summary Table.Rmd and any change in this file may cause some errors.

•	The report is just taken for five variables (i.e. qn6-qn10)
