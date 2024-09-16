# README

# Acute Myeloid Leukemia Heatmap Analysis

This project analyzes RNA-seq data from acute myeloid leukemia (AML) model mice to create heatmaps and identify patterns in gene expression.

## Project Details

### Author
CCDL for ALSF - Adapted for this repository by Candace Savonen

### Last Updated
October 2021

### Goals
- Analyze RNA-seq data from AML model mice
- Create heatmaps to visualize gene expression patterns
- Identify potential clusters or subtypes within the AML samples

## Software Requirements

- R
- RStudio
- pheatmap package
- magrittr package

## How to Run the Project

1. Ensure you have R and RStudio installed on your system.

2. Open the R script in RStudio.

3. Install required packages:
   ```r
   if (!("pheatmap" %in% installed.packages())) {
     install.packages("pheatmap", update = FALSE)
   }
   ```

4. Run the script in RStudio.

5. The script will create necessary directories and load the data.

6. It will then generate heatmaps and save them in the designated plot directory.

## Data Description

This analysis uses RNA-seq data from 19 AML model mouse samples. The data is obtained from [refine.bio](https://www.refine.bio/experiments/SRP070849) and includes:

- 19 samples from AML model mice
- RNA-seq results for various AML subtypes under controlled treatment conditions
- Pre-processed and quantile-normalized data

## Usage Notes

- The script assumes the data files are in the expected locations.
- Make sure you have sufficient disk space for storing the results.
- The script sets a random seed for reproducibility.

## Contact

For any questions or issues, please contact Candace Savonen at [your email].
```

This README provides an overview of the project, its goals, requirements, and basic steps to run the analysis. It also includes information about the data and usage notes. You may need to adjust some details based on your specific needs and the actual content of your project.

Citations:
[1] https://usethis.r-lib.org/reference/use_readme_rmd.html
[2] https://stackoverflow.com/questions/56358347/how-to-generate-readme-md-from-readme-rmd-for-r-package
[3] https://www.reddit.com/r/cscareerquestions/comments/h17blk/always_write_a_clear_readme_if_you_want_to_find_a/
[4] https://cran.r-project.org/web/packages/projects/readme/README.html
[5] https://r-pkgs.org/other-markdown.html
[6] https://www.quora.com/How-important-is-it-to-create-a-Readme-document-before-or-during-a-software-dev-project
[7] https://github.com/eli64s/readme-ai
[8] https://eheidi.dev/tech-writing/20221212_documentation-101/
[9] https://forum.posit.co/t/readme-rmd-in-a-bookdown-repo/93191
[10] https://search.r-project.org/CRAN/refmans/usethis/html/use_readme_rmd.html
