This repo includes the assignment "Mini Data Analysis Deliverable 1" for the Baylor class CSI 2300.

Files in this repo:

    - MiniDataAnalysis1.qmd
        - The code/analysis

    - MiniDataAnalysis1.md
        - The rendered qmd file

    - MiniDataAnalysis1_files/
        - All rendered graphs

    - dat/
        - All avaiable datasets to work with for this assignment

To use the files in this repo:

1. Install R, positron or RStudio, and Quarto
2. Download needed packages: tidyverse, diversedata and moderndive.
    a. "diversedata" isn't on CRAN, so you must install it with pak::pak("diverse-data-hub/diversedata")
3. Clone/Download Repository
4. Open MiniDataAnalysis1.qmd
5. Render the file


Generative AI Statement:

Claude was used to help me debug when I had syntax errors, such as finding when I put a space (" ") instead of an underscore ("_") for a variable.  One specific instance of this was finding "SALE PRICE" when I needed to have "SALE_PRICE" instead.

It also helped me with this line: mutate(brew_method = str_remove_all(brew_method, "^\\(|\\)$")), because I did not know how to format the regex.