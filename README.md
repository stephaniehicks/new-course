These are the course materials for Advanced Data Science taught at Johns Hopkins Bloomberg School of Public Health by [Stephanie Hicks](http://stephaniehicks.com) and [Roger Peng](http://www.biostat.jhsph.edu/~rpeng/). The Fall 2018 course website can be found at [http://jhu-advdatasci.github.io/2018](http://jhu-advdatasci.github.io/2018). 

All materials are licensed CC-BY. 

#### Helpful notes  

This website was built using [R Markdown websites](https://rmarkdown.rstudio.com/rmarkdown_websites.html) and hosted on [GitHub Pages](https://pages.github.com) in the [`master` branch](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/). A custom `Makefile` script is in this folder, which is used to knit all the `.Rmd` files in the main source folder to `.html`. 

There is a `lectures` folder which is used to store files used for each lecture. These files are not knit using `make` and need to be knit into static `.html` files. Images in these lecture files that are not created automatically when kniting the document, should be included in the `/imgs` sub-directory and linked using `![](../imgs/<filename>.png)`. 

Example slides used in previous iterations from this course can be found [here](https://github.com/jtleek/advdatasci/blob/master/slides/01-introduction-slides.Rmd). 

To use this repo for your course, use `git clone git@github.com:stephaniehicks/new-course.git` to clone the repo locally, change into the directory using `cd new-course`, and then `rm -rf .git` to remove the git history. Make the changes you want to for your new course, commit the changes, and push to your new course website! If using [GitHub Pages](https://pages.github.com), make sure you change the settings for the [`master` branch](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/).

Pull requests are welcome! 