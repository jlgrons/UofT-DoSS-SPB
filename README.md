# UofT DoSS Summer Prep Bootcamp (DoSS SPB)

How to update the website:
- The bootcamp page is made using the Distill package for R Markdown: https://rstudio.github.io/distill/. 
- To add content, add it to the directory "Mycourse/2023".
- To update a web page, update its .Rmd file and then click "Build Website" in the Build panel in RStudio. The symbols \<!-- and \--> comment out content in R Markdown. To link to content in the repository, write something like this in the .Rmd page: \[this text will be hyperlinked]("Mycourse/2023/myfile.pdf").
