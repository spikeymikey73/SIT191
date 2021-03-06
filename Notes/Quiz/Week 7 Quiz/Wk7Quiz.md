**Question 1**

Consider the different scenarios below and match with the appropriate statistical test/calculation.  

**A one proportion z-test**	
From a random sample of 195 people from one suburb, it was found that 35 go to the movies at least once a month.  We want to know whether the proportion of movie-goers from this suburb differs significantly from the proportion for the whole city, which is stated to be 15%.

**A two proportion z confidence interval**
A recent study on the diet of athletes reported that 12% of females and 21% of males take protein supplements.
We want to know by how much the proportions of athletes taking protein supplements differs between females and males.  

**A two proportion z-test**
A recent study reported that 9% of women and 6% of men are vegetarians.  We want to know if the difference in the proportions of vegetarians between the genders is statistically significant.

**A one proportion z confidence interval**
In a random sample of 315 children, 251 said they use an iPad every day.  We want to estimate the proportion of all children who use an iPad every day.



**Question 2**

Carpal tunnel syndrome is a painful wrist condition that can be treated with surgery or less invasively with wrist splints. In a study of 180 patients with the condition, half had surgery and half used wrist splints. In the surgery group, 70 patients showed improvement after three months while 42 of those who used wrist splints improved. Is surgery more effective than the use of wrist splints for improving symptoms of the condition?

Calculate a 95% confidence interval for the difference (surgery - wrist splints) in improvement rates.

- [ ] -0.177 to 0.445
- [ ] -0.445 to 0.177
- [ ] 0.233 to 0.542
- [ ] 0.467 to 0.778
- [x] 0.177 to 0.445

```R
> prop.test(x=c(70,42), n=c(90, 90), alternative="two.sided", correct=FALSE)

	2-sample test for equality of proportions without continuity correction

data:  c(70, 42) out of c(90, 90)
X-squared = 18.529, df = 1, p-value = 1.673e-05
alternative hypothesis: two.sided
95 percent confidence interval:
 0.1769449 0.4452774
sample estimates:
   prop 1    prop 2 
0.7777778 0.4666667 
```



**Question 3**

A new drug is believed to help in the recovery of stroke patients. A clinical experiment was conducted to test the effects of the new drug against an existing drug. Researchers observed 3154 patients given the new drug and found some improvement of their symptoms in 865 of them. Of the 2016 patients given the existing drug, 509 reported improvement.

A 95% confidence interval was calculated for the difference in the improvement rates

(new drug - existing drug), and is given by [-0.003, 0.046].

Which of the following interpretations is most applicable? 

 

- [ ] Between 0.3% and 4.6% of all the patients reported an improvement in their symptoms.
- [ ] The improvement rate for patients given the new drug was significantly higher than the rate for patients given the existing drug.
- [ ] We are 95% sure that between 0.3% and 4.6% more patients using the new drug showed improvement compared with those on the existing drug.
- [x] The difference in improvement rates between the two drugs was not statistically significant.

```R
> prop.test(x=c(865,509), n=c(3154, 2016), alternative="two.sided", correct=FALSE)

	2-sample test for equality of proportions without continuity correction

data:  c(865, 509) out of c(3154, 2016)
X-squared = 2.9884, df = 1, p-value = 0.08386
alternative hypothesis: two.sided
95 percent confidence interval:
 -0.002761999  0.046311510
sample estimates:
   prop 1    prop 2 
0.2742549 0.2524802 

```



**Question 4**

Carpal tunnel syndrome is a painful wrist condition that can be treated with surgery or less invasively with wrist splints. In a study of 180 patients with the condition, half had surgery and half used wrist splints. In the surgery group, 70 patients showed improvement after three months while 42 of those who used wrist splints improved. Is surgery more effective than the use of wrist splints for improving symptoms of the condition?

Let ps denote the proportion of patients that would show improvement with surgery and pw denote the proportion of patients that would show improvement using wrist splints. 

Select the appropriate hypotheses.

- [ ] $H_a: ps = pw$
- [ ] $H_0: ps \ne pw$
- [x] $H_0: ps = pw$
- [x] $H_a: ps > pw$
- [ ] $H_a: ps \ne pw$
- [ ] $H_0: ps > pw$



**Question 5**

Carpal tunnel syndrome is a painful wrist condition that can be treated with surgery or less invasively with wrist splints. In a study of patients with the condition, 88 had surgery and 76 used wrist splints. In the surgery group, 62 patients showed improvement after three months while 39 of those who used wrist splints improved. Is surgery more effective than the use of wrist splints for improving symptoms of the condition?

Determine the z test statistic value to be used in the hypothesis test.

Answers will vary slightly due to rounding. Select the closest answer, ignoring any negative sign.

- [ ] 0.05
- [x] 2.51
- [ ] 4.89
- [ ] 3.35
- [ ] 2.16

```R
> prop.test(x=c(62,39), n=c(88,76), alternative="two.sided", correct=FALSE)

	2-sample test for equality of proportions without continuity correction

data:  c(62, 39) out of c(88, 76)
X-squared = 6.314, df = 1, p-value = 0.01198
alternative hypothesis: two.sided
95 percent confidence interval:
 0.04402924 0.33874588
sample estimates:
   prop 1    prop 2 
0.7045455 0.5131579 
```



**Question 6**

Survey results show that 72.3% of men and 58.7% of women have gym memberships. Is the difference in proportions significant? Using a calculated test statistic value of $z = 2.55$ and $P-value = 0.01$, choose the most correct conclusion (use $\alpha = 0.05$).

- [ ] Reject Ha since P-value > 0.05 ??? there appears to be no significant difference in the proportions of men and women who have gym memberships
- [x] Reject $H_0$ since P-value < 0.05 ??? there appears to be a significant difference in the proportions of men and women who have gym memberships
- [ ] Reject $H_0$ since the P-value < 0.05 ??? a significantly greater proportion of women than men have gym memberships
- [ ] Fail to reject $H_0$ since P-value > 0.05 ??? there appears to be no significant difference in the proportions of men and women who have gym memberships
- [ ] Fail to reject $H_0$ since P-value < 0.05 ??? there appears to be a significant difference in the proportions of men and women who have gym memberships



**Question 7**

Smarties (sugar coated chocolate confectionary) come in 8 colours ??? green, yellow, red, orange, pink, purple, blue and brown. You buy a bag containing 120 smarties to investigate the distribution of colours, and count 12 green, 14 yellow, 17 red, 15 orange, 16 pink, 17 purple, 11 blue and 18 brown smarties.

To see if your results are consistent with the colours being equally represented or not, which is the most appropriate test?

- [ ] Chi-square test of independence
- [x] Chi-square goodness-of-fit test
- [ ] One proportion z-test
- [ ] Two proportion z-test



**Question 8**

To determine if there is an association between gender and accident circumstance, 120 people who had been injured in an accident were randomly selected from medical records and categorised by gender and the circumstance. The results are shown below.

|              | **At work  ** | **At home  ** | **Car** | **other   ** | **TOTAL** |
| ------------ | ------------- | ------------- | ------- | ------------ | --------- |
| **Female  ** | 11            | 16            | 11      | 19           | 57        |
| **Male**     | 17            | 8             | 4       | 34           | 63        |
| **TOTAL**    | 28            | 24            | 15      | 53           | 120       |


If gender and accident circumstance are independent, how many males would be expected to be injured at work?

**Choose the correct value.**

- [x] 14.7
- [ ] 17
- [ ] 9.3
- [ ] 15.75
- [ ] 4.0



**Question 9**

The following table shows data on randomly selected crime victims.

|                                  | Homicide | Robbery | Assault |
| -------------------------------- | -------- | ------- | ------- |
| Criminal was a stranger          | 12       | 379     | 727     |
| Criminal was known to the victim | 39       | 106     | 642     |

 

**For a test regarding a possible association between the type of crime and the relationship of the criminal with the victim, what would be the appropriate hypotheses?**

- [ ] $H_a$: There are unequal numbers of each type of crime
- [ ] $H_a$: Robberies are more likely to be committed by strangers than assaults.
- [ ] $H_0$: Type of crime and relationship to victim are related.
- [x] $H_a$: Type of crime and relationship to the victim are not independent.
- [x] $H_0$: Type of crime and relationship to the victim are independent.
- [ ] $H_0$: There are equal numbers of each type of crime.

 

**Question 10**

Smarties (sugar coated chocolate confectionary) come in 8 colours ??? green, yellow, red, orange, pink, purple, blue and brown. You buy a bag to investigate the distribution of colours, and count 12 green, 16 yellow, 12 red, 13 orange, 12 pink, 12 purple, 15 blue and 18 brown smarties.

**What is the value of the degrees of freedom for a goodness-of-fit test?
Give the integer (whole number) answer.**

**Answer:** $df = n - 1 = 7$



**Question 11**

Smarties (sugar coated chocolate confectionary) come in 8 colours ??? green, yellow, red, orange, pink, purple, blue and brown. You buy a bag of 120 smarties to investigate the distribution of colours, and count 16 green, 10 yellow, 16 orange, 16 pink, 16 purple, 16 blue, 12 brown smarties and the remainder red.
Are the colours represented equally?

**Calculate the value of the $\chi^2$ test statistic.**

[Give your answer to 1 decimal place]

**Answer**: 3.2

```R
> smarties <- c(16, 10, 16, 16, 16, 16, 12, 18)
> chisq.test(smarties)

	Chi-squared test for given probabilities

data:  smarties
X-squared = 3.2, df = 7, p-value = 0.8659
```



**Question 12**

Suppose we were interested in whether the current year's enrolments in the Science faculty differed to previous years in terms of the distribution of students across different areas.  We usually expect a ratio of 3:2:1:1:2:1 across the areas of Ecology, Biology, Chemistry, Engineering, Architecture, IT.  

In conducting a goodness-of-fit test, we obtained a $\chi^2$ value of 9.7.  

**Choose the correct P-value range.
**Note, if you have found an exact value with technology, choose the range that contains your value.

- [ ] 0.005 < P-value < 0.01
- [ ] P-value > 0.3
- [ ] 0.1 < P-value < 0.2
- [ ] P-value < 0.05
- [x] 0.05 < P-value < 0.1



**Question 13**

When someone is charged with a crime, a jury may be required to decide the result in court. One study in a large city compared the ages of jury members with the general population to see if the jury were representative. In the city 35% of residents are less than 30 years old, 32% are aged between 31 to 50 years, 22% are aged 51 to 60 years and 11% are older than 60 years.

A sample of 100 jury members was taken in the city. Below are the observed counts:      

| Age (years)  | Observed Count |
| ------------ | -------------- |
| Less than 30 | 37             |
| 31 - 50      | 28             |
| 51 - 60      | 24             |
| Over 60      | 11             |

Is the age distribution for the jury members consistent with the age distribution for the general population?

A Chi-square Goodness of fit test was conducted with the test statistic calculated as 0.79 and P-value>0.3.

**Using a significance level of 5%, what would you conclude?
(select all that apply)**



- [x] Fail to reject $H_0$ since P-value >0.05  The ages of the sampled jury members seem representative of the population.
- [ ] The over 60s are less represented amongst the jury than the population.
- [x] For each age group, the percentages of the jury members are similar to those for the population.
- [ ] Reject $H_0$ since P-value <0.05 The ages of the sampled jury members do not appear to be representative of the population.
- [ ] $H_a$ is proved.The ages of the sampled jury members are not representative of the population.
- [ ] Fail to reject $H_0$ since P-value >0.05. The jury is independent.

```
> age <- c(37,28,24,11)
> chisq.test(age, p=c(.35,.32,.22,.11))

	Chi-squared test for given probabilities

data:  age
X-squared = 0.7961, df = 3, p-value = 0.8504
```

