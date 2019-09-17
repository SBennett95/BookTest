# BookTest
This repository will be used for testing different statistical techniques from the book "There's a Stat for That".

## Frequency Tests

1. Binomial Test.
First, we will read in our data. 
```{r}
demo <- read.csv("data/Demographic_Statistics_By_Zip_Code.csv")
```

Next we will perform a binomial test based on our data
```{r}
binom.test(16, 25, p = 0.5, alternative = c("two.sided", "less", "greater"), conf.level = 0.95)
```

2. Chi-Squared Test
