preference-analysis
===================
Analyze behavioral data for mere exposure effect

Ipython notebook produces charts in Mere Exposure Paper from the behavioral data in the text file. The notebook provides details on how the text files are organized.

like_data.txt
If the subject is missing entries, the end is padded with NaN. Note that we have day 1 and day 10 ratings for everyone.
Some subjects are missing intervening days. We plot as a function of exposure, assuming that subjects did not drink the
juice on the days that they didn't report.

preference_data.txt
Just the liking ratings for the scanning data