# survey-mining
Fork from survey-mining by Barbara McGillivray and Gard Jenset (see below).
All scripts are for Python 3.7
Changes:
- WordCloud has been replaced by the new implementation found at https://github.com/amueller/word_cloud
- topia-termextract has been replaced by the 3.6 version found at https://github.com/tetyanaloskutova/topia.termextract-py3.6-2.0.0
The input data requires to be put in folder like company_name\company_name_keyword\keyword.xlsx, 
where keyword should be replaced with the topic of the survey. In the current example, 'pride' is used as an example keyword. See pride.xlsx for the example of file format. 


Previous (original) version for Python 2.7

Authors: Barbara McGillivray and Gard Jenset

A Natural Language Processing pipeline for processing survey data by extracting keywords, semantically clustering them, and visualizing the results.

The script pipeline_27112016.py is the main script, which calls the other scripts.
All scripts should be saved in the same folder. 

All scripts are for Python 2.7.
