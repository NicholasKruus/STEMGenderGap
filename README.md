STEMGenderGap.zip contains everything referred to below.


Degree_Collection.R and STEM_Analysis.R located in the "Code" .zip file contain all of the necessary code. If you are using the raw data already collected from the NCES IPEDS, follow the instructions at the top of STEM_Analysis.R and run it.

The appendix contains the list of universities and the degrees that were collected from the NCES lookup for each university.
.
.
.
IF you are not using the raw NCES IPEDS data. The programs' working directory (defined in the first few lines of each) will need to be updated to accommodate your computer. The working directory for each is unique and should be updated at the beginning of each program.

For RealDegreeCollection to work with new data, there are a few stipulations:

1. Data must be .csv files collected from the "completions" category in the NCES "compare institutions" lookup: https://nces.ed.gov/ipeds/datacenter/InstitutionList.aspx. Each file must contain the TOTAL and TOTAL FEMALE BACHELOR'S degrees conferred data for one year.

2. The .csv files need to be specifically named:

A) Every file should start with "Raw" followed by the name of the institution or a shortened version of it (e.g. RawPrincetonUniversity truncated to RawPrinceton) with no spaces or other characters (except its number discussed at B).
B) Every file needs to be numbered for the program to determine the year:
The file for 2008 should end in 1 (e.g. RawPrinceton1),
the file for 2007 should end in 2,
the file for 2006 should end in 3,
the file for 2005 should end in 4,
the file for 2004 should end in 5,
the file for 2003 should end in 6,
the file for 2009 should end in 7.
