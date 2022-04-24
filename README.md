First step is to dave your documents in two csv files: skill_data.csv and position_data.csv
Then, Update the build_skill_bars function in helper_functions.R according to the maximum number of years of your experience in "ggplot(aes(x= reorder(skill, level), y =11))".
Then update the Aside and main section of resume2.Rmd file as per your need and situation. Your github, linkedin and website sections need to be appropriate sites otherwise it will show 404.page not found.
The css files also need to be uploaded into RStudio inorder to style and format the resulting HTML or PDF files.
I have had issues converting the HTML into PDF. I tried to follow two approaches:  rmarkdown::render() and rmarkdown::print_chrome() functions. Both take an RMD file to convert HTML into PDF. The render option is preferrable because it can pass paameters into R markdown_pagedown options in YAML section of the RMD code. 
