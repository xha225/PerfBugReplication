# PerfBugReplication
Artifacts of an experiment on reproducing performance bugs from bug reports.

The "artifacts" spreadsheet has a few tabs.
The "Reproducible" tab contains statistics on the characteristics of the reproducible bugs.
The "Non-Reproducible" tab contains bugs that we have tried but failed to reproduce.
The "Suggestions" tab contains some tips and solutions on how to handle a specific type of non-reproducible bug.

The statistics on the various distribution of studied bugs can be done easily with the built-in functions in Excel. 
As we plan to expand the size of our dataset, in the near future we want to migrate the dataset from Excel files to a MySQL database images (stored procedures for generating data reports will also be provided).

For those who are interested in trying out the studied reproducible performance bugs, we have shared a VirtualBox image that loaded with all 17 ready to use bugs (~/Work/bugs/success/). The VirtualBox image (about 80GB) can be found <a href="https://drive.google.com/file/d/1mMQ4pcf1ZlLlCGej9BnztK5hmlMXoQnk/view?usp=sharing">here</a>. 
