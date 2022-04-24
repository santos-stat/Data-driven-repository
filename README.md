First step is to save your professional skill and companaies you worked for in two csv files: skill_data.csv and position_data.csv.

Then, Update the build_skill_bars function in helper_functions.R according to the maximum number of years of your experience in "ggplot(aes(x= reorder(skill, level), y =11))".

Then update the Aside and main section of resume2.Rmd file as per your need and situation. Your github, linkedin and website sections need to be appropriate sites otherwise it will show 404.page not found.

The css files also need to be uploaded into RStudio inorder to style and format the resulting HTML or PDF files.

I have had issues converting the HTML into PDF. I tried to follow two approaches:  rmarkdown::render() and pagedown::chrome_print() functions. Both take an RMD file to convert HTML into PDF. The render option is preferrable because it can pass paameters into R markdown_pagedown options in YAML section of the RMD code. The chrome_print option requires Google chrome installed in your PC or Linux. 

Here is my session info:

R version 4.1.1 (2021-08-10)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Red Hat Enterprise Linux

Matrix products: default
BLAS:   /usr/lib64/libblas.so.3.4.2
LAPACK: /usr/lib64/liblapack.so.3.4.2

locale:
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C               LC_TIME=en_US.UTF-8       
 [4] LC_COLLATE=en_US.UTF-8     LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8   
 [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                  LC_ADDRESS=C              
[10] LC_TELEPHONE=C             LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
 [1] compiler_4.1.1   fastmap_1.1.0    rsconnect_0.8.25 htmltools_0.5.2  tools_4.1.1     
 [6] glue_1.4.2       yaml_2.2.1       rmarkdown_2.13   knitr_1.33       pagedown_0.17   
[11] xfun_0.30        digest_0.6.27    rlang_0.4.11     evaluate_0.14  
