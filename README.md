# shiny_plot
This is an interactive shiny plot for the insurance dataset from [myPack](https://github.com/Elnaz-Khaveh/myPack.git). 
You can see how the target column "charges" changes with changing the numercial and non-numerical variables.

To see the interactive plots clone to the repository with following command in your command line:

```
git clone git@github.com:Elnaz-Khaveh/shiny_plot.git
```

Then open shiny.Rproj and run the following line in the R console:

```
install_packages("renv")
renv::restore()
```

Then to run the shiny app:

```
install_packages("shiny")
shiny::runApp(".")
```

Then you can see the interactive plots.
