# A minimal R Markdown example

A quote:

> Markdown is not LaTeX.

## code chunks

A _paragraph_ here. A code chunk below (remember the three backticks):


```r
1 + 1
```

```
## [1] 2
```

```r
0.4 - 0.7 + 0.3  # what? it is not zero!l
```

```
## [1] 5.551e-17
```


## graphics

It is easy.


```r
plot(1:10)
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-21.png) 

```r
hist(rnorm(1000))
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-22.png) 


## inline code

Yes I know the value of pi is 3.1416, and 2 times pi is 6.2832.

## math

Sigh. You cannot live without math equations. OK, here we go: $\alpha+\beta=\gamma$. Note this is not supported by native markdown. You probably want to try RStudio, or at least the R package **markdown**, or the function `knitr::knit2html()`.

## nested code chunks

You can write code within other elements, e.g. a list

1. foo is good
    
    ```r
    strsplit("hello indented world", " ")[[1]]
    ```
    
    ```
    ## [1] "hello"    "indented" "world"
    ```

2. bar is better

## conclusion
