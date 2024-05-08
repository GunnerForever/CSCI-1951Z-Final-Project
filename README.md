# CSCI-1951Z-Final-Project

### This is the repository that contains code and datasets used in the final project of CSCI 1951Z class. <br>
### The repository has the following structure:

**Directories** 
- resume_without_bias: This directory contains the original dataset and the results after querying the API using the original dataset. <br>
- resume_with_bias: This directory contains the biased datasets created on the original dataset containing uneven feature distributions. <br>

**Files/Subdirectories**
- resume_without_bias/resume.csv: This file contains the original dataset.
- resume_without_bias/resume_result.csv: This file contains the resume scorer output of resume.csv.
- resume_without_bias/resume_with_score.csv: This file contains same information as resume.csv but with last column the resume scores.
- resume_without_bias/candidate_result.csv: This file contains candidate evaluator output for resume_with_score.csv. <br> <br>
- resume_with_bias/authorization_bias: This directory contains the datasets with work authorization biases and API results.
- resume_with_bias/disability_bias: This directory contains the datasets with disability status biases and API results.
- resume_wiht_bias/ethnicity_bias: This directory contains the datasets with ethnicity biases and API results.
- resume_with_bias/gender_bias: This directory contains the datasets with gender biases and API results.
- resume_with_bias/veteran_bias: This directory contains the datasets with veteran status biases and API results. <br> <br>

- generate_data.ipynb: This Jupyter Notebook contains the code that was used to generate all the datasets (original & biased).
- merge_resume_score.ipynb: This Jupyter Notebook contains the code that was used to merge resume scores output from the API to the features set to form input to the candidate evaluator API.
- analysis_bias.ipynb: This Jupyter Notebook contains the code for the analyses we did, including calculations of various metrics and plots.
