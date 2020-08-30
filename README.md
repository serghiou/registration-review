# Registration of biomedical research: history & lessons learned

<div align="justify">

## Data

All data can be downloaded under a CC-BY license from OSF: https://osf.io/px6vf/. Please maintain the directory structure and place the data directory within the forked directory to reproduce the code. Note that you do not need to download the contents of `interim_data` or `tidy_data`, as these are programmatically created by the code in the `data_ code` directory.


## Code

The code is available under the GPL-3 license. Fork this repository to run the code appropriately. Download the data from OSF as indicated above before running the code. All code files inherit the name of their data source (e.g. the code using the data saved in "clinicaltrials.csv" is called "clinicaltrials.Rmd") and all outputs inherit the name of the code that produced them (e.g. the plot produced by "clinicaltrials.Rmd" is called "clinicaltrials.jpg"). When a code produces more than one outputs, these are denoted by using "\_" (e.g. "clinicaltrials_over-time.jpg"). `data_code` contains code that modifies data (run this first), `eval_code` contains code that analyzes the data (run this second) and `tidy_code` contains the code that produces all of the analyses shown in the publication (i.e. it is a tidy version of `eval_code`; run this third).

</div>
