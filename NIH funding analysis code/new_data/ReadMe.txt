========Analysis code structure===

Do not change function_data folder

Place input csv files into new_data folder

NIH_Funding_Grant_linker.py should be left outside of other two folders

=========Input Prep============

Go into new_data folder.

Place csv inputs and rename to match:

P_B_Drug.csv

P_B_Target.csv

(can be divided by applied/Drug vs basic/Target research or two copies of any PMID list, so long as the csv are renamed correctly) 

========Run analysis code======

Run NIH_Funding_Grant_linker.py

(this may take a few min depending on hardware limits)

========main outputs==========

Overview.csv (main overview of input PMID NIH funding)

resultUQ_APY_COST.csv (Funding of relevant grants/projects)

resultUQ_FULL.csv (main data output of all relevant funding data relative to each PMID/publication)


All other csv are for debug/archive and can be ignored if not needed
