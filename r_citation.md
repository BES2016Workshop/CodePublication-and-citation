# R's citation function

In R, if you type the function `citation()` you will be given detailed instructions on how to cite it.

```
> citation()

To cite R in publications use:

  R Core Team (2016). R: A language and environment for statistical computing. R
  Foundation for Statistical Computing, Vienna, Austria. URL https://www.R-project.org/.

A BibTeX entry for LaTeX users is

  @Manual{,
    title = {R: A Language and Environment for Statistical Computing},
    author = {{R Core Team}},
    organization = {R Foundation for Statistical Computing},
    address = {Vienna, Austria},
    year = {2016},
    url = {https://www.R-project.org/},
  }

We have invested a lot of time and effort in creating R, please cite it when using it for
data analysis. See also ‘citation("pkgname")’ for citing R packages.
```

Most R packages have similarly detailed citation instructions. For example here's is the one for `ggplot2`

```
> citation('ggplot2')

To cite ggplot2 in publications, please use:

  H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York,
  2009.

A BibTeX entry for LaTeX users is

  @Book{,
    author = {Hadley Wickham},
    title = {ggplot2: Elegant Graphics for Data Analysis},
    publisher = {Springer-Verlag New York},
    year = {2009},
    isbn = {978-0-387-98140-6},
    url = {http://ggplot2.org},
  }
  ```

If you use R packages in your research, we encourage you to use these citation guidelines.
