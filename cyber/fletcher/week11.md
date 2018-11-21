# Weekly Activity Reports
11-09-18
## Fletcher's Weekly Activity Report - Friday, Nov 9, 2018
### Legend
 - [Objective](#objective)
 - [Work I Did](#work-i-did)
 - [Meetings](#meetings)
 - [Summary](#summary)
 - [Follow up](#follow-up)
 
 ### Big Three
 - Worked on identifying correlation of TORGI data.
 - Worked to determine useful way to visualize TORGI data
 - Worked on locating patterns that identify GPS jamming in TORGI data.
 
 ### Objective
 - Further analyze Torgi data in a time series format as per Tracy's dictation
 
 ### Work I Did
Performed time series analysis on Torgi as per Tracy's direction
 ### Meetings
 
 ### Summary/Remarks:
 - Some of the issues we are running into with the TORGI data are:
  - Not all positioning signals (GPS/GLONASS) are affected by same jamming signal.
  - Jamming can affect positioning signals from similar sources in different ways.
  - Positioning signal is not continuous from one source.

 ### Follow Up
- Solutions Ive prepped:
  - Using LCD for intervals regarding local_time values to handle data gaping from SVID data points
  - Focus on GLONASS vs GPS AGC comparison to identify variances in the affects of the attack to develop higher accuracy Decision tree models
