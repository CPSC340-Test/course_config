DSCI571 Quiz1
================

``` r
suppressPackageStartupMessages(library(tidyverse))
```

Quiz Instructions
-----------------

rubric={mechanics:6}

Edit this `.md` file directly with your answers. `save`, `commit`, and `push` your answers to your quiz repo before the deadline.

Closed-book, aside from R and python documentation.

Rubric weights add up to 100.

Exercise Set 1 (Worth 16% total)
--------------------------------

The following is a scatterplot of 9 training observations labelled either `x` or `o`, and one "new" unlabelled observation indicated by `?`

<img src="quiz1_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-2-1.png" style="display: block; margin: auto;" />

For these questions, you are to classify `?` using *k*-Nearest Neighbours. Do not use R or python.

### 1(a)

rubric={reasoning:8}

Classify `?` with *k* = 1. Explain your answer with one very brief sentence.

> Your\_response\_here

### 1(b)

rubric={reasoning:8}

Classify `?` with *k* = 3. Explain your answer with one very brief sentence.

> Your\_response\_here

Exercise Set 2 (Worth 30% total)
--------------------------------

Below is a decision tree for features `X1` and `X2`. The leaves are missing. The training data are shown in the following plot (as in Exercise Set 1), with the decision tree regions labelled A through D.

![](quiz1_files/decisiontree.png)

![](quiz1_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-3-1.png)

### 2(a)

rubric={reasoning:10}

Indicate which regions in the scatterplot (indicated A through D) correspond to the missing leaves in the decision tree, from left to right.

> Your\_response\_here

### 2(b)

rubric={reasoning:10}

Indicate the decision that would be made (`x` or `o`) for each of the four regions (A through D).

> -   A: **your\_answer\_here**
> -   B: **your\_answer\_here**
> -   C: **your\_answer\_here**
> -   D: **your\_answer\_here**

### 2(c)

rubric={reasoning:10}

*Suppose* the decisions are as follows (HINT: this is not the answer to the previous question! These were randomly chosen.):

-   A: **x**
-   B: **o**
-   C: **x**
-   D: **x**

What is the *training error*? Give your answer as a fraction.

> Your\_response\_here

Exercise Set 3 (Worth 48% total)
--------------------------------

### 3(a)

rubric={reasoning:12}

***Briefly*** explain (using one or two brief sentences) the key difference between classification and regression.

> Your\_response\_here

### 3(b)

rubric={reasoning:12}

The following displays three *k*-NN classification boundaries using three values of *k*.

![](quiz1_files/overfitting.png)

Which of the three is most likely overfitting? ***Briefly*** explain why (one or two sentences).

> Your\_response\_here

### 3(c)

rubric={reasoning:12}

In an overfit classification model, how would the test error compare to the training error? (One brief sentence). What does this mean, in terms of using the classifier in the real world? (One brief sentence).

> Your\_response\_here

### 3(d)

rubric={reasoning:12}

Why might we not want a decision tree to split until the training data are perfectly classified? What aspect of a decision tree can we control to prevent creating a decision tree that large? (***Briefly***, in one or two sentences)

> Your\_response\_here
