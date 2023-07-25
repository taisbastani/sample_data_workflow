# Sample data workflow
These are samples from the data workflow coded by me (Tais Bastani) for my master's thesis, including cleaning and harmonizing, merging and preprocessing, and presenting descriptives and visualizations.

The files in this repository are: 
- dicts.ipynb creates mappings from how answers are saved in the exported file from the virtual learning platform to a letter answer, and saves them to answer_dict.json, to be used in the cleaning file.
- clean.ipynb cleans and harmonizes exported data from standardized electromagnetism tests taken on a virtual learning platform.
- merge.ipynb merges cleaned and harmonized data coming from multiple semesters and preprocesses this data, calculating derived columns such as test scores, normalized gain and inferred students' gender from names.
- plots_and_tables.ipynb loads the preprocessed data, presents descriptive tables on score breakdowns by teaching methodology and student gender, as well as plots of the distributions of these, including a discrete version of the relative distribution method implemented in this file.

For student confidentiality reasons, the original data files are not included. Aggregated output in the plots and tables files is included. 
