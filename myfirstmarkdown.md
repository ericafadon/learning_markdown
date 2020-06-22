---
title: "My first trial with Markdown"
author: "Erica"
date: "6/22/2020"
output: 
  html_document: 
    keep_md: yes
---
This is my work.

```r
groups <- c("Apple_1", "Apple_2", 
            "Pepper_1", "Pepper_2", 
            "Maize_1", "Maize_2",
            "Tomato")
reviewers <- sample(groups, 7)
d <- data.frame(groups = groups, reviewers = reviewers)
d
```

```
##     groups reviewers
## 1  Apple_1   Maize_1
## 2  Apple_2    Tomato
## 3 Pepper_1  Pepper_1
## 4 Pepper_2  Pepper_2
## 5  Maize_1   Apple_1
## 6  Maize_2   Maize_2
## 7   Tomato   Apple_2
```
