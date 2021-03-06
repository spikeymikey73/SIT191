**Question 1**

People suffering from sacroiliac joint dysfunction can be given a steroid injection to relieve pain.  
After receiving an injection, 15 out of 34 patients reported a reduction in pain.

Calculate the standard error:

[Give your answer to 3 decimal places]

**Answer**: 0.085
$$
\hat{p} = \frac{15}{34} = 0.44117647\\
\hat{q} = 1 - \hat{p} = 0.55882353\\
SE(\hat{p}) = \sqrt{\frac{\hat{p}\hat{q}}{n}}\\
= \sqrt{\frac{0.441 \times 0.559}{34}}\\
= 0.085
$$


**Question 2**

For a 95% confidence interval, choose the most accurate value of z*.

- [ ] 0.025
- [ ] 2
- [ ] 1.65
- [x] 1.96
- [ ] 2.33

```
> abs(qnorm(0.05/2))
[1] 1.959964
```



**Question 3**

People suffering from sacroiliac joint dysfunction can be given a steroid injection to relieve pain.  
After receiving an injection, 11 out of 38 patients reported a reduction in pain.

If you were to create a 90% confidence interval for the true proportion of sufferers of the condition whose symptoms should be improved by the injection, what is the **margin of error?**

[Giver your answer to 3 decimal places]

**Answer:** 0.118

```
> Q3data <- prop.test(x=11, n=38, conf.level=0.90, correct=FALSE)

	1-sample proportions test without continuity correction

data:  11 out of 38, null probability 0.5
X-squared = 6.7368, df = 1, p-value = 0.009444
alternative hypothesis: true p is not equal to 0.5
90 percent confidence interval:
 0.1857105 0.4212226
sample estimates:
        p 
0.2894737

> ME <- round((0.4212226 - 0.1857105) / 2, 3)
> ME
[1] 0.118
```



**Question 4**

In a random sample of 75 Labrador Retriever adult dogs, 60 were found to be overweight. 
The calculated 90% confidence interval from this sample result for the true proportion of adult Labrador Retrievers that are overweight is 0.724 to 0.876.
Are significantly more than 70% of adult Labrador Retrievers overweight?

Select the following statements that are **true.**

- [ ] We can be 95% sure that the percentage of all the sampled adult Labradors that are overweight is between 72.4% and 87.6%.
- [x] A different random sample of adult Labradors will probably result in a different 90% confidence interval.
- [x] Based on this sample, we can be 90% sure that the percentage of all adult Labradors that are overweight is between 72.4% and 87.6%.
- [ ] Since 0.7 (70%) is below the lower bound of the confidence interval, there is evidence that significantly more than 70% of adult Labradors are overweight.
- [ ] Since the sample proportion is 80%, significantly more than 70% of all Labradors must be overweight.



**Question 5**

A random sample of 75 children from a region of rural Victoria found that 50 children consume at least one sugary soft drink per day. 
Construct a 90% confidence interval from this sample result for the true proportion of children consuming at least one sugary soft drink per day.

Choose the correct answer.

- [ ] 0.593 to 0.807
- [ ] 0.560 to 0.774
- [x] 0.578 to 0.757
- [ ] 0.667 to 0.900
- [ ] 0.489 to 0.711

```
> Q5data <- prop.test(x=50, n=75, conf.level= 0.90, correct=TRUE)
> Q5data

	1-sample proportions test with continuity correction

data:  50 out of 75, null probability 0.5
X-squared = 7.68, df = 1, p-value = 0.005584
alternative hypothesis: true p is not equal to 0.5
90 percent confidence interval:
 0.5658618 0.7550183
sample estimates:
        p 
0.6666667

> round(Q5data$conf.int, 3)
[1] 0.566 0.755
attr(,"conf.level")
[1] 0.9
```





**Question 6**

From a random sample of 80 adult Labrador Retrievers, 55 were found to be overweight.

Is there significant evidence that more than 65% of adult Labrador Retrievers are overweight? 

Select the appropriate hypotheses, where p is the proportion of adult Labrador Retrievers that are overweight.

- [x] $H_0: p = 0.65$
- [ ] $H_0: p ??? 0.65$
- [x] $H_a: p > 0.65$
- [ ] $H_a: p = 0.65$
- [ ] $H_0: p = 0.6875$
- [ ] $H_a: p \ne 0.65$



**Question 7**

In a random sample of 80 Labrador Retriever adult dogs, 66 were found to be overweight. 
Are more than 70% of adult Labradors overweight?

Calculate the z test statistic required for the hypothesis test.

Choose the closest answer.

- [ ] -1.96
- [ ] 1.95
- [ ] -2.44
- [x] 0.93
- [ ] 2.94

```
> p <- 66/80
> qnorm(p, lower.tail=TRUE)
[1] 0.9345893
```



**Question 8**

For a two sided hypothesis test with a calculated z test statistic of 2.31, what is the P-value?

- [ ] 0.05
- [ ] 0.0104
- [x] 0.0208
- [ ] 0.9896
- [ ] 0.0107

```
> 2*pnorm(2.31, lower.tail=FALSE)
[1] 0.02088815
```



**Question 9**

In a random sample of children, 65% consumed at least one sugary soft drink per day. Is there evidence that the proportion of children consuming at least one sugary soft drink per day is significantly different to 80%?
Using a calculated test statistic value of z = -2.23 and P-value = 0.0258, choose the most correct conclusion (use ?? = 0.05).

- [ ] Reject Ha since the P-value > 0.05 ??? there is no evidence that the proportion of children who consume at least one sugary soft drink per day is different to 80%.
- [ ] Fail to reject H0 since the P-value > 0.01 ??? there is evidence that the proportion of children who consume at least one sugary soft drink per day is different to 80%.
- [x] Reject H0 since the P-value < 0.05 ??? there is evidence that the proportion of children who consume at least one sugary soft drink per day is significantly different to 80%.
- [ ] Reject H0 since the P-value > 0.05 ??? there is evidence that the proportion of children who consume at least one sugary soft drink per day is significantly different to 80%.
- [ ] Fail to reject H0 since the P-value < 0.05 ??? there is no evidence that the proportion of children who consume at least one sugary soft drink per day is significantly different to 80%.

