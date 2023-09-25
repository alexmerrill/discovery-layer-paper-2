# Rstudio Instructions


## Download and install RStudio and dependencies

- Download RStudio from: [https://posit.co/download/rstudio-desktop/](https://posit.co/download/rstudio-desktop/)
    - RStudio also requires R to be installed alongside Rstudio (link to download from the offical R repository is available from the link above)
- R Packages to enable in RStudio:
    - System Library (these should all be on by default)
        - base
        - datasets
        - graphics
        - grDevices
        - methods
        - stats
        - utils
    - User Library (will need to be installed and enabled)
        - [stringdist](https://cran.r-project.org/web/packages/stringdist/index.html)
            - This package can be installed and managed through the RStudio>Packages>Install interface





## Running the scripts within Rstudio
- The RMarkdown file [Scripts/Rstudio/framework_notebook.Rmd](/Scripts/Rstudio/framework_notebook.Rmd)
- Sample Input and Output files are in the [Sample Data](https://github.com/alexmerrill/discovery-layer-paper-2/tree/main/Sample%20Data) folder
  - Input:  Primo Search Results [/Sample Data/primo-api-results-articlesOnly-normalized.csv](/Sample%20Data/primo-api-results-articlesOnly-normalized.csv)
  - Input:  Source Citations [/Sample Data/source-paper-citations-normalized.csv](/Sample%20Data/source-paper-citations-normalized.csv)
  - Output: Resulting Matches .CSV [/Sample Data/ArticlesOnly_normalized_matches.csv](/Sample%20Data/ArticlesOnly_normalized_matches.csv)
  


