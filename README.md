# Schedules

# Project title
Project imports data from MCAD downloaded file, categorizes data for each store per relevant account, and create schedules per store.

## Motivation
Manually creating excel schedules can be tedious. This project helps save time and focus for more relevant tasks. 

### Technologies
-Python 3.7

####Other information
Notes to help understand the dynamics of the project. Involves a lot of duplicate and drop. 
-mcadcsv - raw datafile
-agedROs = saved csv file where oldest item age greater 61 days and sum not equal $0
-combinedROs = Dataframe merged from raw data and agedROs files
-archiveROs = brute forced special items that get filtered by agedROs criteria. Adds comp,account,control1 
-to_agedROs = Dataframe prep, on its way to agedROs
-mcad_prep = prep mcadcsv to relevant store-accounts
-summary = formatted Dataframe to be exported as first tab in excel schedule file
-sch_details = formatted Dataframe to be exported as second tab in excel schedule file








