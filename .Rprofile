local({
  r = getOption("repos")             
  r["CRAN"] = 'https://cran.rstudio.com/'
  options(repos = r)
})

options(pkgType = "binary")
options(
  # to automatically serve the site on RStudio startup, set this option to TRUE
  blogdown.serve_site.startup = FALSE,
  # to disable knitting Rmd files on save, set this option to FALSE
  blogdown.knit.on_save = FALSE, 
  blogdown.author = "First Last",
  blogdown.ext = ".Rmd",
  blogdown.subdir = "post"
)
options(blogdown.hugo.version = "0.83.1")
options("citation_format" = "pandoc")
source("renv/activate.R")
