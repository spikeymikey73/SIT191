## Quiz Submissions - Week 4 Quiz

**Question 1:**

Suppose for a given country:

23% of the population have type A blood

34% of the population have type B blood

3% of the population have type AB blood

and the rest have type O.



**What is the probability that a person volunteering to donate blood does not have type A blood?**

**Answer:** 0.77

![Q1Venn](/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 4 Quiz/Images/Q1Venn.jpg)

```R
> a <- 0.23
> b <- 0.34
> ab <- 0.03
> o <- 1 - (a + b + ab)

> Q1 <- b + ab + o
> Q1
[1] 0.77
```



**Question 2:**

Suppose for a given country:

27% of the population have type A blood

33% of the population have type B blood

9% of the population have type AB blood

and the rest have type O.

**Among 4 potential donors, what is the probability that none of them are type O?** _Write as a decimal between 0 and 1 to **three decimal places**, e.g. 45.7812% would be 0.458_

**Answer**: 0.227

![Q2Venn](/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 4 Quiz/Images/Q2Venn.jpg)

```R
> a <- 0.27
> b <- 0.33
> ab <- 0.09
> o <- 1 - (a + b + ab)
> o
[1] 0.31

> round(not_o^4, 3)
[1] 0.227
```



**Question 3:**

Assume that 41% of households have at least one dog, 27% of households have at least one cat and 15% of households have both animals.

**What is the probability that a randomly selected household has a dog but not a cat?**

[Enter as a decimal between 0 and 1 to **two decimal places**, e.g. for 45% write 0.45]

**Answer:** *0.26*

![Q3Venn](/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 4 Quiz/Images/Q3Venn.jpg)

```
> d <- 0.41
> c <- 0.27
> cd <- 0.15
> dog_only <- d - cd
> dog_only
[1] 0.26
```





**Question 4:**

Assume that 29% of households have at least one dog, 18% of households have at least one cat and 12% of households have both animals.

**If a household has a dog, what is the probability that they also have a cat?**

*Enter as a decimal between 0 and 1 to **\*three\* decimal places**, e.g. for 45.123% write 0.451*

**Answer:** 0.12

<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 4 Quiz/Images/Q4venn.jpg" alt="Q4venn"  />

> It helps to use a Venn diagram to model these. This is an example of conditional probability.  We want to know the probability of a cat, **given** that they have a dog.  
>
> The conditional probability formula is:
> $$
> Pr(A∣B) = \frac{Pr(A\ and\ B)}{Pr(B)}
> $$

```R
>library(VennDiagram)

> grid.newpage()
> draw.pairwise.venn(area1=0.29, area2=0.18, cross.area=0.12, fill = 2:3)

```



**Question 5:**

Given the Venn Diagram, which of the following can be assumed about events A and B?

<img src="https://d2l.deakin.edu.au/content/enforced/1031733-SIT191_TRI-2_2021/Screen%20Shot%202017-04-04%20at%2011.45.12%20AM.png?_&d2lSessionVal=PvmeBE8v8Gd5fAr7FwOqcBUx4" alt="sub" style="zoom: 50%;" />

- [x] if event A occurs, then B must occur
- [x] events A and B are not mutually exclusive
- [ ] events A and B are mutually exclusive
- [ ] if event B occurs, then A must occur
- [ ] if event A occurs, then B can't occur
- [x] it is possible for both A and B to occur



**Question 6:**

Malaria is a mosquito-borne infectious blood disease of humans and other animals caused by a bite from a female mosquito infected with *Plasmodium*. A number of different species of *Plasmodium* which cause malaria can be found across different geographic regions. The following table shows the number of deaths (in hundreds of thousands) from three different *Plasmodium* species for three continents:

|                        |                   | Continent | Total      |                   |           |
| ---------------------- | ----------------- | --------- | ---------- | ----------------- | --------- |
|                        |                   | **Asia**  | **Africa** | **South America** | **Total** |
| **Plasmodium species** | **P. ovale**      | 30        | 14         | 32                | **76**    |
|                        | **P. vivax**      | 5         | 6          | 53                | **64**    |
|                        | **P. falciparum** | 52        | 44         | 6                 | **102**   |
|                        | **Total**         | **87**    | **64**     | 91                | **242**   |

Event A is that a malaria death was caused by the *P. vivax* species and event B is the malaria death was in Africa.

a) Find the following probabilities:

i) P(A)  (1 mark)

- [x] a. 0.264
- [ ] b. 0.078
- [ ] c. 0.360
- [ ] d. 0.421
- [ ] e. 0.627

ii) P(B)  (1 mark)

- [ ] A.0.360
- [ ] B. 0.395
- [ ] C. 0.025
- [x] D. 0.264
- [ ] E. 0.376

iii) P(A and B)  (1 mark)

- [ ] A. 0.248
- [ ] B. 0.219
- [x] C. 0.025
- [ ] D. 0.124
- [ ] E. 0.070

iv) P(A or B)   (2 marks)

- [ ] A. 0.421
- [ ] B. 0.529
- [ ] C. 0.550
- [ ] D. 0.070
- [x] E. 0.504

b) P(A|B)   (2 marks)

- [ ] A. 1
- [ ] B. 0.025
- [x] C. 0.094
- [ ] D. 0.828
- [ ] E. 0.264

c) Are events A and B mutually exclusive?  (1 mark)

- [ ] A. No, because a death can occur from the *P. vivax* species on only one continent
- [x] B. No, because a death can be caused by the *P. vivax* species and be in Africa
- [ ] C. No, because deaths caused by the *P. vivax* species are more likely to occur in Africa
- [ ] D. Yes, because a death can be caused by the *P. vivax* species and be in Africa
- [ ] E. Yes, because a malaria death is caused by only one of the species



**Question 7:**

Suppose the following probability for the number of units enrolled in, X, for Deakin students.

| X         | 1    | 2    | 3    | 4    | 5    |
| --------- | ---- | ---- | ---- | ---- | ---- |
| $Pr(X=x)$ | 0.07 | 0.18 | 0.37 | 0.33 | 0.05 |

Calculate the mean number of units a student will be enrolled in. _Express correct to **2 decimal places**_

Answer: 3.11

> *The mean of the distribution is calculated as:*
> $$
> \mu = 0.07(1) + 0.18(2) + 0.37(3) + 0.33(4) + 0.05(5)
> 		= 3.11
> $$



**Question 8:**

Suppose the following probability for the number of units enrolled in, X, for Deakin students.

| X         | 1    | 2    | 3    | 4    | 5    |
| --------- | ---- | ---- | ---- | ---- | ---- |
| $Pr(X=x)$ | 0.07 | 0.18 | 0.37 | 0.33 | 0.05 |

Calculate the standard deviation for the number of units a student will be enrolled in. _Express correct to **2 decimal places**_

Answer: 0.99

> Standard deviation from a probability distribution is calculated as:
> $$
> \sigma = \sqrt{\Sigma^n_{i=1}P(x_i)\times(x_i − \mu)^2}\\
> $$
> which in this case is:
> $$
> \sigma = \sqrt{0.07(1−\mu)^2+0.18(2−\mu)^2+0.37(3−\mu)^2+0.33(4−\mu)^2+0.05(5−\mu)^2}
> $$
> 
>
> where $\mu$ is the mean of the distributions:
> $$
> \mu =0.07(1) + 0.18(2) + 0.37(3) + 0.33(4) + 0.05(5) = 3.11
> $$
