# competency-data-2023

In March, Spotlight PA and the Pittsburgh Institute for Nonprofit Journalism published an investigation into Pennsylvania’s broken competency system — a series of legal processes meant to protect people whose mental illness may prevent them from participating in their own defense.

The investigation found this system often harms the very people it’s meant to protect.

Integral to the reporting was a unique dataset the newsrooms requested (Competency_Docket_Data_Requesat.xlsx) and purchased from the Administrative Office of Pennsylvania Courts, the government body that oversees local courts and maintains thousands of case records from across the state.

Spotlight PA and PINJ are now making the data acquired through those requests available to the public so that researchers, other journalists, and anyone interested in examining these sources can put them to use. 

Spotlight PA, PINJ, and AOPC officials discussed the request for months to identify case dockets that included evidence that a defendant had been evaluated for competency between 2018 and 2022. Ultimately, using 23 different docket entries and two different dispositions, AOPC found 697 cases across 23 counties and provided the case information in a database.

The newsrooms aimed to obtain the largest possible dataset of cases involving competency proceedings in Pennsylvania and determine what types of crimes the people involved in those proceedings had been charged with.

AOPC provided the newsrooms with four separate but related datasets: 

-Case and disposition data showing the charges brought in a case. (Competency_case_data_cleaned.csv)

-Sentencing data showing the sentence the person received. (Competency_sentencing_data.csv)

-Attorney data showing the attorneys and judges involved in the case. (Competency_attorney_data.xlsx)
 
-Docket entry data showing the competency-related docket entry in a case. (Competency_docket_entry_data.xlsx)

AOPC also provided a data layout (Competency_data_file_layout.xlsx)

Spotlight PA and PINJ used only the first dataset in the analysis, given the limitations of both time and the data.

The data were messy upon delivery because of spelling and punctuation mistakes in the way court clerks docketed competency proceedings, charges, and defendant names. Spotlight PA cleaned the case and disposition data using the software OpenRefine to look for these variations and fix them. All changes were checked against the online dockets and other public records to ensure accuracy.

After fixing spelling and punctuation issues, the newsrooms used pivot tables to count the most common charges brought against people who went through competency proceedings. The newsrooms also used pivot tables to analyze the grade of the charges. Grades indicate whether the charges were more likely to be low-level crimes like summary offenses or misdemeanors than homicides or felonies.

The resulting analysis of cases from 2018 through August 2022 found people going through competency proceedings were most often charged with low-level crimes that could stem from them experiencing mental health issues in public.

#Limitations of the data

The analysis and the dataset likely leave out hundreds of cases across the state, as only 23 counties are represented from 2018 through August 2022. 

This is because some counties, such as Allegheny, do not publicly docket competency proceedings. Others document competency proceedings using a free-text field in the statewide case management system, a field AOPC does not include in data requests because it can contain private information.

Spotlight PA and PINJ used only the “case and disposition” dataset in the analysis. As such, the other datasets have not been examined for inconsistencies or issues. The other datasets should be checked against existing dockets and other records for accuracy before attempting any analysis.

Spotlight PA and PINJ have removed defendant names from the datasets to protect the privacy of the individuals whose cases are included. Names are available by searching the case number in Pennsylvania’s online case management system. 

The full dataset with names included is available upon request. Please email Matt Dempsey at mdempsey@spotlightpa.org to inquire.

