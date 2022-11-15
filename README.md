# R Workshop @ 2022 Autumn School Interdisciplinary Human Past and Quantitative Uralistics

University of Turku 

## Preparation before the workshop

### Installing R

To follow the course you will need to install two programmes on your computer, R and R Studio. The precise instructions for doing this on different platforms should be available when you follow the links below. In addition, we have uploaded a video called *Installing R and R Cloud* to Moodle, which will guide you through the process.

- First, install [R](https://cloud.r-project.org/). R is a statistical computer language, and the install is necessary for your computer to understand things written in this language. 
  
  This might fail if you don't have administrative rights to your computer. If that's the case you should either get administrative rights, or make your administrator do this and the next steps for you.

- It's possible to interact with R directly, but learning it is simpler if you use the special program called [RStudio](https://www.rstudio.com/products/rstudio/download/#download). You should install this only after R itself is installed. RStudio includes lots of useful things, like the *console*, where you can type in text which your computer will immediately interpret as things written in the R language, a *help window*, where you can get information about different R commands, an interface for install and update *R packages* (collections of R commands that aren't available by default), graphics viewers, and much more.

Once you're installed R and RStudio you need to install the *tidyverse* package. This is a big collection of R packages which are all designed to give a consistent interface following a consistent logic, and to produce modern and attractive graphics. There are several ways to install a package, but for now let's just use the following:

- Open RStudio and select **Tools** from the menubar, then **Install 
  Packages...**. A little dialog box will pop up:

  * Leave *Install from* as it is.
  
  * Under *Packages* type *tidyverse*
  
  * The *Install to library* item tells RStudio where to put the files belonging to this new library. The default should be okay (this will be a directory which all accounts on your computer can see), but there might also be an option to put it in a directory which only you have access to. Either option is fine. 

  * Make sure the *Install dependencies* box is checked (☑︎) so that all the packages that are part of the tidyverse package will be installed as well.

The tidyverse package is big, so installing it might take some time. While it is installing you will see lots of text scrolling past in the console window of RStudio. Once the tidyverse package is installed you only have to load it, which is much quicker. To test that it has been installed properly, type `libary(tidyverse)` into the console window. If it works you will see messages about **Attaching packages** and **Conflicts**. If you see a scary red massage starting *Error: package or namespace load failed for ‘tidyverse’* then the installation has failed. This usually happens because R was already installed on your computer a long time ago, and the version is too old to support the current version of tidyverse. You will probably need to start again at the top with reinstalling all the software.

In addition, it can be good to create an [RStudio Cloud](https://rstudio.cloud/plans/free) account. Select the *Cloud Free* option and click the *Sign Up* button to create an account with your name and email address. You'll need to verify you email address after signing up. RStudio Cloud is an online version of RStudio. We won't necessarily be using it because the desktop version is faster and more stable, but if for some reason something goes wrong during the workshop you can use the cloud version as a backup plan to still follow along.

On Moodle you will also find a short video *Introduction to R*, in which we explain in a bit more detail what R is and does.

### Instruction videos

In addition to installing R, there are two instruction videos on Moodle we ask you to watch. One of them is an introduction to R Markdown, showing you how to use it to structure your text. The other is an introduction to some of the concepts in programming -- such as variables, data types and structures -- and how these work in R. This is meant to get everyone familiar with the basics that we will use in the workshop itself. Each video comes with an accompanying R Markdown file, which you can find in the *Pre-Workshop Files* folder.

## Schedule

Coming soon!
