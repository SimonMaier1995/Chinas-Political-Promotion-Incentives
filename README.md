This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

The paper the problem set is based on examines whether modified promotion criteria for governors helped to reduce excessive provincial river border pollution in China.
Both the paper and the data set can be found here: https://www.aeaweb.org/articles?id=10.1257/pol.20130367

In case you do not want to install the problem set, you may have a look here: https://simonmaier.shinyapps.io/Chinas-Political-Promotion-Incentives/
However, you are not able to store your progress there.

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("SimonMaier1995/Chinas-Political-Promotion-Incentives")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorChinaPromotionIncentives)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorChinaPromotionIncentives")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorChinaPromotionIncentives",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
