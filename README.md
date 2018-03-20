# PerfBugReplication
Artifacts of an experiment on reproducing performance bugs from bug reports.

The "artifacts" spreadsheet has a few tabs.
The "Reproducible" tab contains statistics on the characteristics of the reproducible bugs.
The "Non-Reproducible" tab contains bugs that we have tried but failed to reproduce.
The "Suggestions" tab contains some tips and solutions on how to handle a specific type of non-reproducible bug.

The statistics on the various distribution of studied bugs can be done easily with the built-in functions in Excel. 
As we plan to expand the size of our dataset, in the near future we want to migrate the dataset from Excel files to a MySQL database images (stored procedures for generating data reports will also be provided).

For those who are interested in trying out the studied reproducible performance bugs, we have shared a VirtualBox image that loaded with all 17 ready to use bugs. The VirtualBox image (about 80GB) can be found here: https://drive.google.com/a/g.uky.edu/file/d/0BwZoeeoiQ2HVVWxFN2pIaFU2bUk/view?usp=sharing_eip&ts=59de67e5 
