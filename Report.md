# Title

## Synopsis (no more than 10 sentences)

## Data Processing (at least one figure but no more than 3)

```r
require(R.utils)
```

```
## Loading required package: R.utils
## Loading required package: R.oo
## Loading required package: R.methodsS3
## R.methodsS3 v1.6.1 (2014-01-04) successfully loaded. See ?R.methodsS3 for help.
## R.oo v1.18.0 (2014-02-22) successfully loaded. See ?R.oo for help.
## 
## Attaching package: 'R.oo'
## 
## The following objects are masked from 'package:methods':
## 
##     getClasses, getMethods
## 
## The following objects are masked from 'package:base':
## 
##     attach, detach, gc, load, save
## 
## R.utils v1.32.4 (2014-05-14) successfully loaded. See ?R.utils for help.
## 
## Attaching package: 'R.utils'
## 
## The following object is masked from 'package:utils':
## 
##     timestamp
## 
## The following objects are masked from 'package:base':
## 
##     cat, commandArgs, getOption, inherits, isOpen, parse, warnings
```


```r
if (!file.exists("StormData.csv")) {
  bunzip2("StormData.csv.bz2")
}

data <- read.csv("StormData.csv.bz2")
```

## Results
### Across the United States, which types of events (as indicated in the EVTYPE variable) are most harmful with respect to population health?

### Across the United States, which types of events have the greatest economic consequences?




