# Elections-Database
Created an election database using MySQL and showcased in on powerpoint. 
Parsed election data for the 2015 federal election using Python into separate files 
Created an election database using MySQL to analyze data

Executive Summary


Overview: Analyze the election data for the 2015 Federal Elections. Take data given by Elections Canada and create a
database to organize the data to make is easier to draw conclusions out of.

Steps:
1. Acquire raw data
2. Parse the raw data using Python and output into cv files
3. Create database and tables to import data into MySQL
4. Use SQL to look into data further and draw conclusions

Some questions that were answered included: What was the greatest margin that a candidate won by, how does the
rejected vote count correlate with the margin of votes for each electoral districts and how many incumbent candidates
re-ran in the election. For instance, it was seen that only 29 incumbent candidates re-ran for Liberals meaning most of the
party was fairly new. For more analysis look at the later slides.

Raw Data Input

Elections Canada Link Format 2:
http://www.elections.ca/content.aspx?section=res&dir=rep/off/42gedata&document=bypro&lang=e 

Note: The other format of data was format 1 which only had 1 row for each polling station in each
electoral district. This would have made it harder to analyze the results of each candidate as it
had less detail. For example format 1 did not have the incumbent indicator or the electoral
indicator which was needed to answer questions regarding incumbent candidates. Format 2
was chosen because it had more data that was needed for this analysis and in a more efficient
format.
