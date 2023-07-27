Steps for making changes to the website:

1. edit the desired .Rmd file
2. make sure the required packages are installed  (i.e., distill, rsconnect, rmarkdown)
3. Within RStudio -> Build -> Build Website -> this will automatically render rmarkdown::render_site() which in turn will render .html corresponding files (needed to display the web-pages) of the respective .Rmd
4. push changes to repo
5. build and deploy repo
