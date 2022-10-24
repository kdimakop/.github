# Welcome

This is the GitHub Organization site for EXPANSE's WP3, where we can share and discuss code for the different analyses within the group.

## Papers

| Paper | Title                                                                                          | Lead        | Submission    | Repository                                                   |
|-------|------------------------------------------------------------------------------------------------|-------------|---------------|--------------------------------------------------------------|
| 1     | Socioeconomic inequalities in urban exposome patterns across the life span in European cohorts | ISGlobal    | December 2022 | [paper1_exposure-pca](https://github.com/expanse-wp-3/paper1_exosure-pca) |
| 2     | External exposome and mortality across Europe                                                  | Rome-Greece | December 2022 | [Paper2_mortality](https://github.com/expanse-wp-3/paper2_mortality) |
| 3     | External exposome and stroke risk across Europe                                                | KI          | December 2022 | [Paper3_stroke](https://github.com/expanse-wp-3/paper3_stroke) |
| 4     | Evaluating interplay between urban exposome specific exposures on total mortality              | Greece      | October  2022 | [Paper4_mortality](https://github.com/expanse-wp-3/paper4_mortality) |

## Results

Below you can see which cohorts have provided the most up to date results for each paper:

| Cohort      | Paper 1            | Paper 2 | Paper 3 | Paper 4             |
|-------------|--------------------|---------|---------|---------------------|
| Adult cohorts:                                                             |
| KORA        | :heavy_check_mark: | :heavy_check_mark:, check PCA and redo analyses | :heavy_check_mark:, check PCA and redo analyses | :heavy_check_mark:                    |
| CEANS       | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| EPIC-NL     | ? |  :x:, check PCA and redo analyses |  :x:, check PCA and do all the analyses |   :x: |
| Admin cohorts:                                                             |
| Catalonia   | :heavy_check_mark: |  :x:, check PCA and do all the analyses       | :x:, check PCA and do all the analyses        | :heavy_check_mark:, but needs to check the results|
| Greece      |  :heavy_check_mark:| :heavy_check_mark:, check PCA and redo analyses |  :heavy_check_mark:, check PCA and redo analyses |  :heavy_check_mark:|
| Rome        | :heavy_check_mark:  | :heavy_check_mark: |  :heavy_check_mark: |:heavy_check_mark:|
| Switzerland | ? | :heavy_check_mark:, check PCA and redo analyses |   Not participating | :heavy_check_mark: |
| SIMSAM      | ? | :x:, check PCA and do all the analyses |  :x: , check PCA and do all the analyses | :heavy_check_mark: |
| Netherlands | ? | :x:, check PCA and do all the analyses |  :x: , check PCA and do all the analyses | :x: Do all the analyses |


## Getting Started

Each analysis should have its own repository within the Organization. Consider choosing a short and informative name for your repository.

>**Important**: Confidential data should not be stored in GitHub and therefore should not be version controlled. Make sure the possibly sensitive data files that are inside the repository are included in your .gitignore file. Contact the GitHub Organization's maintainer when in doubt.

### Creating a new repository

1. Create a new private GitHub repo in this organization using the available template at [repo-template](https://github.com/expanse-wp-3/repo-template). It contains a .gitignore file with common data folders and file formats which makes sure these files are not tracked. Any sensitive files within the repository not covered by the template's .gitignore should added.

2. Clone this remote repository inside the appropriate folder in your machine. If using RStudio, use *`File > New Project > Version Control > Git`*.

3. Work on the analysis locally commiting when significant changes/additions have been made.

4. Push your commits to the remote repository regularly.

### Adding an existing non-Git repository

1. Create a .gitignore file. Make sure all possibly sensitive data files are included in this file.

2. Make your non-version controlled project a local Git repository (i.e. `git init`).

3. Connect local repo to GitHub repo.

4. Work on the analysis locally commiting when significant changes/additions have been made.

5. Push your commits to the remote repository when you feel confortable sharing the changes.

### Adding an existing Git repository

1. Make sure the possibly sensitive data in your existing project has not been version controlled at any stage.

2. Create an *empty* GitHub repository with the same name as your existing project directory.

3. Connect local repo to GitHub repo.

4. Work on the analysis locally commiting when significant changes/additions have been made.

5. Push your commits to the remote repository regularly.
