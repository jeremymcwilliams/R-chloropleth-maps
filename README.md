# LC Summer Coding Club with R - week 77
## Chloropleth Maps



### For use with Lewis & Clark's RStudio Server

* Visit <a href='https://datasci.watzek.cloud' target='_blank'>https://datasci.watzek.cloud</a>
* Sign in with your Lewis & Clark username and password. If you haven't created an account yet, you'll be prompted to create a password.
* Once signed in, click "RStudio Server", after which you will need to sign in again (LC username / password you just created)

in console (lower left-hand corner):
* `library(usethis)`
* `use_course("https://github.com/jeremymcwilliams/R-chloropleth-maps/archive/refs/tags/0.7.zip")`

After running the command above, you'll be prompted whether to download to your current directory. Go ahead and answer in the affirmative (you'll be presented with variations on "yes"). Once the course files download, you'll be prompted as to whether to delete the zip file. Again, answer in the affirmative. Once you do, click "Save", and your window will refresh to a new R session.


### For use with rstudio.cloud 

* Visit https://rstudio.cloud, and sign in with your google account  
* Click the arrow next to "New Project", and select "from Github Repository"
* Enter the url: https://github.com/jeremymcwilliams/R-chloropleth-maps
* Once the project loads, run `install.packages("tidyverse")` in the console.


#### To get started, click "workshop-notebook.Rmd" in the files window, and then minimize the console window.


This is largely based upon the tutorial by the Urban Institute...thank you! (https://urban-institute.medium.com/how-to-create-state-and-county-maps-easily-in-r-577d29300bb2)

