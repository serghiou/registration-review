# Registration of biomedical research: history & lessons learned

<div align="justify">

## Data

All data can be downloaded under a CC-BY license from OSF: https://www.doi.org/10.17605/OSF.IO/PX6VF. Please maintain the directory structure and place the data directory within the directory forked from GitHub to reproduce the code. Note that you do not need to download the contents of `interim_data` or `tidy_data`, as these are programmatically created by the code found in the `data_ code` directory.


## Code

The code is available under the GPL-3 license. Download the data from OSF as indicated above before running the code. Fork this repository to run the code appropriately. Note that the `data` directory has to be stored within the same directory as the `code` directory.

In terms of naming convetion, all code files inherit the name of their data source (e.g. the code using the data saved in "clinicaltrials.csv" is called "clinicaltrials.Rmd") and all outputs inherit the name of the code that produced them (e.g. the plot produced by "clinicaltrials.Rmd" is called "clinicaltrials.jpg"). When a code produces more than one output, these are denoted by using "\_" (e.g. "clinicaltrials_over-time.jpg"). 

In terms of code file structure convention, `data_code` contains code that modifies data (run this first), `eval_code` contains code that analyzes the data (run this second) and `tidy_code` contains the code that produces all of the analyses shown in the publication (i.e. it is a tidy version of `eval_code`; run this third). You can find time-stamped outputs for each analysis (recommended as they are easier to read than the code files) and all analyses done were included.

</div>
