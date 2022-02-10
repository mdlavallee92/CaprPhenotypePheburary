# CaprPhenotypePheburary


For Phenotype Pheburary, we are testing out programmatic cohort creation using Capr. This project will be used to debug Capr, assess areas of improvement and provide examples of how to use Capr for cohort creation. We also hope to test ideas of cohort analysis pipelines, incorporating other HADES tools such as `CohortGenerator` and `CohortDiagnositics`. To participate in the project please install [`Capr`](https://github.com/OHDSI/Capr), make sure you have access to an OMOP CDM (connecting to vocabulary, clinical and results tables), and that you can write cohorts to a results schema on your backend db. 


# Organization

This repository is not an R package so it follows a non-standard organizational structure. Please use the Rproj when collaborating but be sure to no upload .Rhistory to any branch in the repository, it should be set in the .gitignore. There are three primary folders in this repository: results, inst, and R. The results folder contains the code for each day in Phenotype Pheburary labeled day 1 through day 28. Within each day folder there are subfolders for R scripts, json, and output txt files. Place work within these folders for each day you work on. At the top of each R file, please provide a summary of the cohort you are working and the names of the collaborators for that cohort. In the inst folder add any relevant installation files needed for this project. It may be left blank if no installation files are required. In the R folder please add dependent R functions relevant to the project. The organization of the project is subject to change as the project progresses. 

# Capr Issues

If you encounter any bugs with Capr, please post an issue first to this repository so that it can be reviewed. After review, the bug may be escalated to an issue in the Capr repository if it is thought to be an issue with the package. Please dont post issues directly to Capr, so that they can be reviewed and discussed first. 