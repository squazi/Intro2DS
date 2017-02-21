# DataScienceProfile
squazi  
February 21, 2017  
# Raw Data

```r
Category <-c('computer programming', 'math', 'statistics', 'machine learning', 'domain expertise', 'communication and presentation skills', 'data visualization')
Ranking <-c(1, 2, 2, 2, 5, 5, 5)
Sunna <-data.frame(Category, Ranking)
Sunna
```

```
##                                Category Ranking
## 1                  computer programming       1
## 2                                  math       2
## 3                            statistics       2
## 4                      machine learning       2
## 5                      domain expertise       5
## 6 communication and presentation skills       5
## 7                    data visualization       5
```

# Bar Graph Representation

```r
cat.freq <-table(rep(Category, Ranking))
barplot(cat.freq, main = "Sunna", xlab = "Category", ylab = "Ranking", names.arg=c("Comm", "Prog", "Dom", "Viz", "Mach", "Math", "Stats")) 
```

![](DataScienceProfile_files/figure-html/unnamed-chunk-2-1.png)<!-- -->

