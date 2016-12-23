Filename: OP_PGYR2015_README_P06302016.txt
Version: 1.0
Date: June 2016

1. Program Year 2015 Data Files

This data set includes records submitted for the 2015 program year data that were matched with total confidence to a particular covered recipient (i.e., physician, teaching hospital, or principal investigator) and displays information about that recipient. This data set includes the most recent attested-to data for program year 2015.

However, the data contained in the CSV files may not include all of the data submitted to Open Payments for program year 2015. Consult the Open Payments Data Dictionary and Methodology document for an explanation of the criteria that the Centers for Medicare and Medicaid Services (CMS) used to determine what data to publish. This document can be found on the Resources page of the Open Payments website (https://www.cms.gov/OpenPayments/About/Resources.html). The Data Dictionary and Methodology document also includes information on the data collection and reporting methodology, data fields included in the files, and any notes or special considerations that users should be aware of.

Each record now includes a Change Type indicator field. The Change Type value indicates that the payment record is new in General Payment, Research Payment, and Ownership/Investment records for program year 2015.

2. Considerations for using the CSV Files

Microsoft Excel removes leading zeroes from data fields in the CSV files. Certain fields in these data sets may have leading zeroes. These zeroes will be missing when viewing the information within Microsoft Excel. 

Additionally, the latest versions of Microsoft Excel cannot display data sets with more than 1,048,576 rows. Some of these CSV files may exceed that limit. Displaying the data in its entirety may require the use of spreadsheet programs capable of handling very large numbers of records.

3. Details about the Datasets Included in this PGYR15_P063016.zip File

This compressed (.zip) file contains three (3) character-separated value (.csv) format files that use commas as delimiters and one (1) README.txt file. Descriptions of each file contained in this compressed (.zip) file are provided below.

File #1 - OP_DTL_GNRL_PGYR2015_P06302016.csv: 
This file contains the data set of General Payments reported for the 2015 program year. General Payments are defined as payments or other transfers of value made to a covered recipient (physician or teaching hospital) that are not made in connection with a research agreement or research protocol.

File #2 - OP_DTL_RSRCH_PGYR2015_P06302016.csv:
This file contains the data set of Research Payments reported for the 2015 program year. Research Payments are defined as payments or other transfers of value made in connection with a research agreement or research protocol.

File #3 - OP_DTL_OWNRSHP_PGYR2015_P06302016.csv:
This file contains the data set of Ownership and Investment Interest information reported for the 2015 program year. Ownership and Investment Interest Information is defined as information about the value of ownership or investment interests that a physician or an immediate family member of a physician held in an applicable manufacturer or applicable group purchasing organization (GPO).  

Also available is a supplementary file that displays information for physicians and principal investigators indicated as recipients of payments. This supplementary file can be found in a separate zip file: OP_PH_PRFL_SPLMTL_P06302016.csv.

The physician profile information included in the data sets is submitted by the reporting entity. In contrast, the physician information included in the supplementary file is derived from the information in the National Plan and Provider Enumeration System (NPPES) and supplemented by information in the Provider Enrollment, Chain and Ownership System (PECOS). As a result, the data in these two sources may differ slightly. When searching for physicians using the Open Payments search tool on https://openpaymentsdata.cms.gov, use the physician profile information as listed in the supplementary file.



