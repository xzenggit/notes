# R Notes
Xiangming Zeng  
`r Sys.Date()`  
This is my personal note for learning R. A lot of contents come from online resources.

## Basic R, R markdown, and git

### R markdown

Rmarkdown is very useful tool for putting notes together. More references can be found at [Rstudio rmarkdown reference](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf) and the [official cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf).

### git

create a new repository on the command line:

```r
echo "# notes" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/xzenggit/notes.git
git push -u origin master
```

or push an existing repository from the command line

```r
git remote add origin https://github.com/xzenggit/notes.git
git push -u origin master
```



## Data manipulation (dplyr related)

The dplyr package provides very powerful functions for data manipulation:
* `filter()` and `slice()`
* `arrange()`
* `select()` and `rename()`
* `distinct()`
* `mutate()` and `transmute()`
* `summarise()`
* `sample_n()` and `sample_farc()`

Here is a good [introduction](https://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html) about dplyr.

## Exploratory data analysis

## Regression and statistical inference

## Machine learing and big data

