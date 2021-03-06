**Question 1**
Which of the following statements is true?

- [ ]	If the data is skewed left, the mean is likely to be higher than the median.
- [ ] All of the statements are true.
- [ ] If the data is symmetric and unimodal, the value of the mode is likely to be much greater than the median.
- [ ] If the data is strongly skewed, the mean and median are close in value.
- [x] Outliers affect the mean and standard deviation.

**Question 2**
Acid rain: Two researchers measured the pH (a scale on which a value of 7 is neutral and values below 7 acidic) of water collected from rain and snow over a 6-month period in Allegheny County, Pennsylvania.  
Consider the following data:

4.84
5.53
5.33
4.49
5.07
4.80
5.26
5.72
5.25
Calculate the **mean** (give your answer correct to 2 decimal places).  

**Answer:**  _5.14_

```R
> Q2 <- c(4.84,5.53,5.33,4.49,5.07,4.80,5.26,5.72,5.25)
> round(mean(Q2), 2)
[1] 5.14
```




**Question 3**
Acid rain: Researchers measured the pH of water collected from rain and snow over a 6-month period in Allegheny County, Pennsylvania.  
Consider the following observations:

4.65
4.24
4.72
5.00
4.13
5.23
Calculate the **sample standard deviation** (give your answer correct to 2 decimal places).  

Use technology, or if you are going to do this by hand (not recommended), don't round the mean or your squared differences - only round at the end.

```R
> Q3 <- c(4.65,4.24,4.72,5.00,4.13,5.23)
> round(sd(Q3), 2)
[1] 0.42
```



**Question 4**
Acid rain: Researchers measured the pH of water collected from rain and snow over a 6-month period in Allegheny County, Pennsylvania.  
Consider the following data:

4.80
4.12
5.05
4.10
5.49
5.78
5.57
5.45
4.89
5.07
Find the **median** (give your answer correct to 2 decimal places). 

```
> Q4 <- c(4.80,4.12,5.05,4.10,5.49,5.78,5.57,5.45,4.89,5.07)
> round(median(Q4), 2)
[1] 5.06
```



**Question 5**
Which of the following statements is true?


- [ ]	50% of data falls between Q1 and the median
- [x]	50% of data falls above the median
- [ ]	only 25% of data falls above Q1
- [ ]	no more than 25% of data falls below Q3
- [ ]	none of the statements are true

**Question 6**
From the SPSS output below, which response shows the mean and median?

![Q6Img](/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Images/Q6Img.png)

- [ ]	$\bar{x} =28.783$, $median=0.4021$
- [ ]	$\bar{x}=28.800$, $median=28.783$
- [ ]	$\bar{x}=28.887$, $median=28.800$
- [ ]	$\bar{x}=28.361$, $median=29.205$
- [x]	$\bar{x}=28.783$, $median=28.800$

**Question 7**
What is the five number summary from the output below? 

<table class="MsoNormalTable" style="border-collapse: collapse; border: none; border-style: solid;" border="1" width="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td style="width: 338.85pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" colspan="5" width="452">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><strong><span style="font-family: Arial, sans-serif; color: #010205;">Descriptives</span></strong></p>
</td>
</tr>
<tr>
<td style="width: 233.6pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" colspan="3" valign="bottom" width="312">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Statistic</span></p>
</td>
<td style="width: 53.8pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="72">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Std. Error</span></p>
</td>
</tr>
<tr>
<td style="width: 39.95pt; border: none; border-bottom: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" rowspan="13" valign="top" width="53">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">skulls</span></p>
</td>
<td style="width: 193.65pt; border: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Mean</span></p>
</td>
<td style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">132.80</span></p>
</td>
<td style="width: 53.8pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="72">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">.744</span></p>
</td>
</tr>
<tr>
<td style="width: 122.95pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" rowspan="2" valign="top" width="164">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">95% Confidence Interval for Mean</span></p>
</td>
<td style="width: 70.7pt; border: none; border-bottom: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" valign="top" width="94">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Lower Bound</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">131.26</span></p>
</td>
<td style="width: 53.8pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 70.7pt; border: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" valign="top" width="94">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Upper Bound</span></p>
</td>
<td style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">134.34</span></p>
</td>
<td style="width: 53.8pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">5% Trimmed Mean</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">132.86</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Median</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">134.00</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Variance</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">13.833</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Std. Deviation</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">3.719</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Minimum</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">125</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Maximum</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">139</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Range</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">14</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Interquartile Range</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">6</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Skewness</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">-.040</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="72">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">.464</span></p>
</td>
</tr>
<tr>
<td style="width: 193.65pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" colspan="2" valign="top" width="258">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Kurtosis</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="69">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">-.589</span></p>
</td>
<td style="width: 53.8pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="72">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">.902</span></p>
</td>
</tr>
</tbody>
</table>

<table class="MsoNormalTable" style="border-collapse: collapse; border: none; border-style: solid;" border="1" width="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td style="width: 539.2pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" colspan="9" width="719">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><strong><span style="font-family: Arial, sans-serif; color: #010205;"><br>Percentiles</span></strong></p>
</td>
</tr>
<tr>
<td style="width: 167.85pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" colspan="2" rowspan="2" valign="bottom" width="224">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
<td style="width: 371.35pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" colspan="7" valign="bottom" width="495">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Percentiles</span></p>
</td>
</tr>
<tr>
<td style="width: 53.05pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">5</span></p>
</td>
<td style="width: 53.05pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">10</span></p>
</td>
<td style="width: 53.05pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">25</span></p>
</td>
<td style="width: 53.05pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">50</span></p>
</td>
<td style="width: 53.05pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">75</span></p>
</td>
<td style="width: 53.05pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">90</span></p>
</td>
<td style="width: 53.05pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="bottom" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">95</span></p>
</td>
</tr>
<tr>
<td style="width: 126.7pt; border: none; border-top: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" valign="top" width="169">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Weighted Average(Definition 1)</span></p>
</td>
<td style="width: 41.15pt; border: none; border-top: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" valign="top" width="55">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">skulls</span></p>
</td>
<td style="width: 53.05pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">125.90</span></p>
</td>
<td style="width: 53.05pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">128.00</span></p>
</td>
<td style="width: 53.05pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">130.00</span></p>
</td>
<td style="width: 53.05pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">134.00</span></p>
</td>
<td style="width: 53.05pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">135.50</span></p>
</td>
<td style="width: 53.05pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">138.40</span></p>
</td>
<td style="width: 53.05pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">139.00</span></p>
</td>
</tr>
<tr>
<td style="width: 126.7pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" valign="top" width="169">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">Tukey's Hinges</span></p>
</td>
<td style="width: 41.15pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" valign="top" width="55">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #264a60;">skulls</span></p>
</td>
<td style="width: 53.05pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="71">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
<td style="width: 53.05pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="71">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
<td style="width: 53.05pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">131.00</span></p>
</td>
<td style="width: 53.05pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">134.00</span></p>
</td>
<td style="width: 53.05pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" valign="top" width="71">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: Calibri, sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: Arial, sans-serif; color: #010205;">135.00</span></p>
</td>
<td style="width: 53.05pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="71">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
<td style="width: 53.05pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="71">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman', serif;">&nbsp;</span></p>
</td>
</tr>
</tbody>
</table>

- [ ]	min=119, Q1=131, median=132, Q3=136, max=141
- [x]	min=125, Q1=131, median=134, Q3=135, max=139
- [ ]	min=125, Q1=131, mean=132.8, Q3=136, max=139
- [ ]	min=129, Q1=131, median=134, Q3=136, max=139
- [ ]	mean=132.8, std dev=3.719, median=134, IQR=6, range=14

**Question 8**
The following histogram shows the distribution of height (in metres) for 60 randomly selected adults.
histogram
i) Which option best describes the distribution's peak(s)?
Enter the letter only.

- [ ]	uniform
- [x]	unimodal
- [ ]	multi-modal
- [ ]	bimodal
- [ ]	none of the options

ii)  Which option best describes the distribution's shape?
Enter the letter only.
- [ ]	parabolic
- [ ]	strongly left skewed
- [ ]	uniform
- [x]	reasonably symmetric
- [ ]	strongly right skewed

iii) The range of the height data is best given as:
- [ ]	0 to 17
- [ ]	0 to 1.90
- [ ]	1.60 to 1.65
- [x]	1.40 to 1.85
- [ ]	1.30 to 1.80

iv)  Pick the most correct statement regarding the centre of the distribution.

- [x]	the median, mode and mean are all approximately equal
- [ ]	the mode is definitely higher than the mean
- [ ]	the median is much lower than the mean
- [ ]	the median is much higher than the mean
- [ ]	none of the statements are correct

v)  Which summary statistics are best used to describe the centre and spread of this data?  

- [ ]	the mean and IQR
- [ ]	the mode and range
- [ ]	the median and standard deviation
- [ ]	the mean and median
- [x]	the mean and standard deviation

vi) Use the 5 number summary to calculate the lower fence for identifying low outliers.
Enter the letter only.

Min: 1.41  Q1: 1.57   Med: 1.64   Q3: 1.71   Max: 1.82

- [ ]	1.41
- [x]	1.36
- [ ]	0.21
- [ ]	1.92
- [ ]	1.43

**Question 9**
Copy the data below into SPSS and use it to produce a histogram.
Select the option corresponding to your graph.
131, 136, 132, 135, 141, 131, 125, 131, 119, 136, 138, 139, 125, 131, 134, 129, 134, 126, 132, 141, 131, 135, 132, 139, 132

- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Images/Q9_1.png" alt="Q9_1" style="zoom: 67%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Images/Q9_2.png" alt="Q9_2" style="zoom:67%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Images/Q9_3.png" alt="Q9_3" style="zoom:67%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Images/Q9_4.png" alt="Q9_4" style="zoom:67%;" />
- [x]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Images/Q9_5.png" alt="Q9_5" style="zoom: 50%;" />

```
> Q9 <- c(131, 136, 132, 135, 141, 131, 125, 131, 119, 136, 138, 139, 125, 131, 134, 129, 134, 126, 132, 141, 131, 135, 132, 139, 132)
> hist(Q9, breaks=16)
```


**R Output:**

<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Images/Q9Hist.jpg" alt="Q9Hist" style="zoom: 67%;" />

**Question 10**
Copy the data below into SPSS and use it to produce a boxplot.
Select the option corresponding to your graph.
126, 135, 134, 128, 130, 138, 128, 127, 131, 124, 141, 141, 135, 133, 131, 140, 139, 140, 138, 132, 134, 135, 133, 136, 134



>````R
>> Q10 <- c(126, 135, 134, 128, 130, 138, 128, 127, 131, 124, 141, 141, 135, 133, 131, 140, 139, 140, 138, 132, 134, 135, 133, 136, 134)
>> boxplot(Q10)
>````
>
><img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q10_boxplot.jpg" alt="Q10_boxplot" style="zoom: 67%;" />



**Question 11**
Histograms and boxplots displaying the height distribution for three groups are shown below.
Match the histogram for each group to the correct boxplot.

![Q11_1](/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q11_1.png)

![Q11_2](/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q11_2.png)

![Q11_3](/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q11_3.png)

<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q11_4.png" alt="Q11_4" style="zoom:50%;" />

| Histogram         | Boxplot   |
| ----------------- | --------- |
| Group 3 Histogram | Boxplot A |
| Group 2 Histogram | Boxplot B |
| Group 1 Histogram | Boxplot C |

**Question 12**
Copy the data below into SPSS and use it to produce numerical summaries. Select the correct mean and sample standard deviation.
125, 131, 119, 136, 138, 139, 125, 131, 134, 129, 134, 126, 132, 141, 131, 135, 132, 139, 132

- [ ]	$\bar{x} = 129.36$, $s=5.59$
- [ ]	$\bar{x} = 132.05$, $s=1.28$
- [x]	$\bar{x}=132.05$, $s=5.59$
- [ ]	$\bar{x}=132.471$, $s=3.986$
- [ ]	$\bar{x}=132$, $s=7$

>**R Input:**
>`Q12 <- c(125, 131, 119, 136, 138, 139, 125, 131, 134, 129, 134, 126, 132, 141, 131, 135, 132, 139, 132)`
>`summary(Q12)`
>**R Output:**
>
>  `Min.    1st Qu. Median  Mean    3rd Qu. Max.`
>  
>  `119.0   130.0   132.0   132.1   135.5   141.0`

**Question 13**
Copy the data below into SPSS and use it to produce numerical summaries.
Select the correct quartiles.
Note: there are several different methods for determining quartiles. Pick the closest answer if you have used different technology and have slightly different values.
27.1
38.5
35.2
21.0
24.5
36.3
25.7
32.3
29.7
37.8

- [ ]	Q1=21.0, Q3=38.5
- [x]	Q1=25.7, Q3=36.3
- [ ]	Q1=26.4, Q3=35.2
- [ ]	Q1=25.7, Q3=31.0
- [ ]	Q1=31.0, Q3=36.3

>**R Input**
>
>`Q13 <- c(27.1, 38.5, 35.2, 21.0, 24.5, 36.3, 25.7, 32.3, 29.7, 37.8)`
>`Summary(Q13)`
>
>**R Output**
>
>`   Min.    1st Qu. Median  Mean    3rd Qu. Max. `   
>`21.00   26.05   31.00   30.81   36.02   38.50 `

**Question 14**
Pick the bar chart that displays the same movie classification information as the pie chart.

![Q14_1](/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q14_1.png)

- [x]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q14_2.png" alt="Q14_2" style="zoom:50%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q14_3-3584625.png" alt="Q14_3" style="zoom:50%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q14_4.png" alt="Q14_4" style="zoom:50%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/Q14_4.png" style="zoom:50%;" />


**Question 15**
The following table shows the classification of 348 movies into their genre and by rating.

|                          | G    | PG   | PG-13 | R    | Total |
| ------------------------ | ---- | ---- | ----- | ---- | ----- |
| Action/Adventure         | 3    | 18   | 18    | 14   | 53    |
| Comedy                   | 2    | 18   | 29    | 41   | 90    |
| Documentary              | 4    | 8    | 8     | 9    | 29    |
| Drama                    | 0    | 16   | 36    | 65   | 117   |
| Musical                  | 0    | 2    | 2     | 0    | 4     |
| Suspense/Thriller/Horror | 0    | 1    | 13    | 41   | 55    |
| Total                    | 9    | 63   | 106   | 170  | 348   |

Considering Comedies only, which of the following graphs would be suitable to display the rating distribution?

[Select all that apply]

- [ ]	Stacked bar chart
- [x]	Pie chart
- [ ]	Histogram
- [ ]	Stem and leaf plot
- [ ]	Time-series graph
- [x]	Bar chart

**Question 16**
The following table shows the classification of 348 movies into their genre and by rating.

|                          | G    | PG   | PG-13 | R    | Total |
| ------------------------ | ---- | ---- | ----- | ---- | ----- |
| Action/Adventure         | 3    | 18   | 18    | 14   | 53    |
| Comedy                   | 2    | 18   | 29    | 41   | 90    |
| Documentary              | 4    | 8    | 8     | 9    | 29    |
| Drama                    | 0    | 16   | 36    | 65   | 117   |
| Musical                  | 0    | 2    | 2     | 0    | 4     |
| Suspense/Thriller/Horror | 0    | 1    | 13    | 41   | 55    |
| Total                    | 9    | 63   | 106   | 170  | 348   |

Considering Comedies only, which of the following would be suitable graph(s) that displays the rating distribution of the comedies.

[Select all that apply]

- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/16_1.png" alt="16_1" style="zoom: 50%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/16_2.png" alt="16_2" style="zoom: 33%;" />
- [x]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/16_3.png" alt="16_3" style="zoom:50%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/16_4.png" alt="16_4" style="zoom:50%;" />
- [ ]	<img src="/Users/malford/Documents/BPscyhSci/SIT191 - Statistics/Notes/Quiz/Week 3 Quiz/16_5.png" alt="16_5" style="zoom:50%;" />