# Shiny 

Shiny is a new package from RStudio that makes it incredibly easy to build interactive web applications with R.

## Features

* Build useful web applications with only a few lines of code&mdash;no JavaScript required.
* Shiny applications are automatically "live" in the same way that spreadsheets are live. Outputs change instantly as users modify inputs, without requiring a reload of the browser.
* Shiny user interfaces can be built entirely using R, or can be written directly in HTML, CSS, and JavaScript for more flexibility.
* Works in any R environment (Console R, Rgui for Windows or Mac, ESS, StatET, RStudio, etc.)
* Attractive default UI theme based on [Twitter Bootstrap](http://twitter.github.com/bootstrap).
* A highly customizable slider widget with built-in support for animation.
* Pre-built output widgets for displaying plots, tables, and printed output of R objects.
* Fast bidirectional communication between the web browser and R using the [websockets](http://illposed.net/websockets.html) package.
* Uses a [reactive](http://en.wikipedia.org/wiki/Reactive_programming) programming model that eliminates messy event handling code, so you can focus on the code that really matters.
* Develop and redistribute your own Shiny widgets that other developers can easily drop into their own applications (coming soon!).

## Installation

Shiny is currently available only directly from this GitHub repository (it will eventually be available on CRAN). You can download the Shiny source code using one of these methods:

* [Download tar.gz](https://github.com/rstudio/shiny/tarball/master) 
* [Download zip](https://github.com/rstudio/shiny/zipball/master)
* `git clone git@github.com:rstudio/shiny.git` **[Recommended]**

Once you've extracted the Shiny source code to a directory you can install it using the [devtools](http://cran.r-project.org/web/packages/devtools/index.html) package as follows:

```r
library(devtools); install("<shiny-dir>");
```

If you are on Windows you also need to be sure to have installed [Rtools](http://cran.r-project.org/bin/windows/Rtools/) prior to attempting to install Shiny.

## Getting Started

To learn more we highly recommend you check out the [Shiny Tutorial](http://rstudio.github.com/shiny/tutorial). The tutorial explains the framework in-depth, walks you through building a simple application, and includes extensive annotated examples.

We hope you enjoy using Shiny. As you learn more and work with the package please [let us know](https://github.com/rstudio/shiny/issues) what problems you encounter and how you'd like to see Shiny evolve.

## License

The shiny package is licensed under the GPLv3. See these files in the inst directory for additional details:

- COPYING - shiny package license (GPLv3)
- NOTICE  - Copyright notices for additional included software
