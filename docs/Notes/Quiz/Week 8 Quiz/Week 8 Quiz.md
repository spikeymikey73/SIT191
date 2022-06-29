**Question 1**

Car tyres are being tested on different cars.
The braking distance is recorded in both wet and dry conditions for each car.

A subset of the data is as follows (braking distance in metres):

| car  | 1    | 2    | 3    | 4    |
| ---- | ---- | ---- | ---- | ---- |
| dry  | 46.2 | 44.3 | 39.5 | 48.7 |
| wet  | 62.3 | 59.1 | 49.9 | 71.3 |

Is the braking distance significantly longer in wet conditions?

Choose the most appropriate statistical test.

- [ ] 2 Proportion z-test
- [ ] 1 Sample t-test
- [x] Paired t-test
- [ ] 1 Proportion z-test



**Question 2**

Reiki is a type of touch therapy which is believed to increase energy balance and promote pain reduction in areas of the body that are experiencing discomfort. Ten volunteers experiencing pain due to a variety of conditions underwent Reiki treatment and their pain level was measured before and after the treatment on a scale of 1 to 10, with 10 being the highest pain level. The results are shown below.



| Subject    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   |
| ---------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| **Before** | 6    | 9    | 9    | 6    | 7    | 5    | 4    | 9    | 5    | 5    |
| **After**  | 8    | 9    | 8    | 6    | 5    | 4    | 3    | 8    | 5    | 3    |

What are the null and alternative hypotheses for a hypothesis test to determine whether Reiki changed the pain level significantly?

Note the following symbols used - b: before, a: after, d: before - after.

- [x] $H_0: \mu_d=0$, $H_a: \mu_d \ne 0$
- [ ] $H_0: \mu_d=0$, $H_a: \mu_d>0$
- [ ] $H_0: \mu_a=\mu_b$, $H_a: \mu_a \ne \mu_b$
- [ ] $H_0:\mu = 10$, $H_a: \mu < 10$
- [ ] $H_0: \mu_d=0$, $H_a: \mu_d<0$

 

**Question 3**

A random sample of 52 adults from one age group is taken and the average height is 168 cm with standard deviation 6.6 cm.

Calculate the standard error (*SE*).

[Enter your value to 2 decimal places]

**Answer:** 0.92
$$
SE &= \frac{s}{\sqrt{n}}\\
&= \frac {6.6}{\sqrt{52}}\\
&= 0.915255323\\
&= 0.92
$$

```R
> round(6.6 / (sqrt(52)), 2)
[1] 0.92
```



**Question 4**

During an angiogram, heart problems can be examined via a small tube (a catheter) threaded into the heart from a vein in the patient’s leg. It is important that the company that manufactures the catheters maintains a diameter of 2.00 mm. A random sample of 26 catheters is taken and the average diameter is 2.03 mm with standard deviation 0.05 mm.

What is the critical value ($t^*_{df}$) that would be used to create a 90% confidence interval?

[Use a t-table and give your value to 2 decimal places]

**Answer:** 1.71

```R
> round(qt(0.10/2, 25, lower.tail = FALSE), 2)
[1] 1.71
```



**Question 5**

For a variety of Ruffles potato chip bags marked with a net weight of 28.3 grams, a random sample of 6 bags was taken and the weights recorded for each bag, in grams. The summary statistics and SPSS t-test output to test whether the average weight of the bags is less than 28.3 grams is shown.

<table class="MsoNormalTable" style="border-collapse: collapse; border: none;" width="0" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr style="page-break-inside: avoid;">
<td colspan="5" style="width: 346.55pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="462">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><b><span style="font-family: 'Arial',sans-serif; color: #010205;">Descriptives</span></b></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="3" style="width: 241.3pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="322" valign="bottom">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Statistic</span></p>
</td>
<td style="width: 53.8pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Error</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="13" style="width: 47.65pt; border: none; border-bottom: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="64" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">weights</span></p>
</td>
<td colspan="2" style="width: 193.65pt; border: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Mean</span></p>
</td>
<td style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.017</span></p>
</td>
<td style="width: 53.8pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.0601</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="2" style="width: 122.95pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="164" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">95% Confidence Interval for Mean</span></p>
</td>
<td style="width: 70.7pt; border: none; border-bottom: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Lower Bound</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; background-color: #FFFF00; color: #010205;">27.862</span></p>
</td>
<td style="width: 53.8pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 70.7pt; border: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Upper Bound</span></p>
</td>
<td style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; background-color: #FFFF00; color: #010205;">28.171</span></p>
</td>
<td style="width: 53.8pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">5% Trimmed Mean</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.019</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Median</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.050</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Variance</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.022</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Deviation</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.1472</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Minimum</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">27.8</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Maximum</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.2</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Range</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.4</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Interquartile Range</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.3</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Skewness</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">-.418</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.845</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.65pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Kurtosis</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">-.859</span></p>
</td>
<td style="width: 53.8pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">1.741<br></span></p>
</td>
</tr>
</tbody>
</table>

<table class="MsoNormalTable" style="border-collapse: collapse; border: none;" width="0" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr style="page-break-inside: avoid;">
<td colspan="7" style="width: 442.5pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="590">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><b><span style="font-family: 'Arial',sans-serif; color: #010205;"><br>One-Sample Test</span></b></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="3" style="width: 47.65pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="64" valign="bottom">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
<td colspan="6" style="width: 394.85pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="527" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Test Value = 28.3</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="2" style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">t</span></p>
</td>
<td rowspan="2" style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">df</span></p>
</td>
<td rowspan="2" style="width: 70.7pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Sig. (2-tailed)</span></p>
</td>
<td rowspan="2" style="width: 73.75pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Mean Difference</span></p>
</td>
<td colspan="2" style="width: 147.5pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="197" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">95% Confidence Interval of the Difference</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 73.75pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Lower</span></p>
</td>
<td style="width: 73.75pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Upper</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 47.65pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="64" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">weights</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">-4.715</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">5</span></p>
</td>
<td style="width: 70.7pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.005</span></p>
</td>
<td style="width: 73.75pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">-.2833</span></p>
</td>
<td style="width: 73.75pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">-.438</span></p>
</td>
<td style="width: 73.75pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">-.129</span></p>
</td>
</tr>
</tbody>
</table>



**Which of the following is a 95% confidence interval for the true mean weight in grams of all such Ruffles chips?**

- [x] 27.862 to 28.171
- [ ] 12.9 to 43.8
- [ ] 0.129 to 0.438
- [ ] -0.438 to -0.129
- [ ] 28.017 to 27.862



**Question 6**

The talk time for a mobile phone battery is the longest time that a single battery charge will last when constantly talking on the phone. The average talk time for a particular battery type is stated as 6 hours. A new battery supplier claims that their batteries have a longer average talk time than 6 hours. For a random sample of 20 of the supplier’s batteries, the mean talk time was 6.65 hours, with standard deviation 0.92 hours.
Calculate a 90% confidence interval for the true mean talk time, and choose the correct interval.

- [x] 6.29 to 7.01 hours
- [ ] 4.81 to 8.49 hours
- [ ] 6 to 6.65 hours
- [ ] 5.65 to 6.34 hours
- [ ] 6.14 to 7.16 hours

$$
\bar{x} \pm t^*_{n-1} \times \frac{s}{\sqrt{n}}\\
6.65 \pm 1.73 \times \frac{0.92}{\sqrt{20}}\\
6.65 \pm 1.73 \times 0.21
$$

```R
> tStat <- round(qt(0.10/2, 19, lower.tail = FALSE), 2)
[1] 1.73

>lower <- round(6.65 - 1.73 * (0.92 / sqrt(20)), 2)
[1] 6.29

> upper <- round(6.65 + 1.73 * (0.92 / sqrt(20)), 2)
[1] 7.01
```





**Question 7**

The following data represents the time in seconds taken by 7 rats to navigate a maze to find food at the end.
Use SPSS to calculate a 99% confidence interval for the true average completion time (in seconds) and select the correct option (correct to one decimal place).

- [ ] 34.4 to 69.6
- [ ] 44.8 to 59.2
- [x] 41.1 to 62.9
- [ ] 52.0 to 44.8
- [ ] 42.7 to 61.3

```R
> times <- c(46.2, 62.5, 40.9, 58.3, 46.7, 51.8, 57.6)
> times
[1] 46.2 62.5 40.9 58.3 46.7 51.8 57.6
```

```
> t.test(times, lower.tail = TRUE, conf.level=0.99)

	One Sample t-test

data:  times
t = 17.608, df = 6, p-value = 2.153e-06
alternative hypothesis: true mean is not equal to 0
99 percent confidence interval:
 41.0515 62.9485
sample estimates:
mean of x 
       52 
```



**Question 8**

For a variety of Ruffles potato chip bags marked with a net weight of 28.3 grams, a random sample of 6 bags was taken and the weights recorded for each bag, in grams. The summary statistics and SPSS t-test output to test whether the average weight of the bags is greater than 28.3 grams is shown.

<table class="MsoNormalTable" style="border-collapse: collapse; border: none;" width="0" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr style="page-break-inside: avoid;">
<td colspan="5" style="width: 346.65pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="462">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><b><span style="font-family: 'Arial',sans-serif; color: #010205;">Descriptives</span></b></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="3" style="width: 241.4pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="322" valign="bottom">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Statistic</span></p>
</td>
<td style="width: 53.8pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Error</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="11" style="width: 47.7pt; border: none; border-bottom: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="64" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">weights</span></p>
</td>
<td colspan="2" style="width: 193.7pt; border: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Mean</span></p>
</td>
<td style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.783</span></p>
</td>
<td style="width: 53.8pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.1641</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="2" style="width: 123.0pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="164" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">95% Confidence Interval for Mean</span></p>
</td>
<td style="width: 70.7pt; border: none; border-bottom: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Lower Bound</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.361</span></p>
</td>
<td style="width: 53.8pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 70.7pt; border: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Upper Bound</span></p>
</td>
<td style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">29.205</span></p>
</td>
<td style="width: 53.8pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.7pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">5% Trimmed Mean</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.787</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.7pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Median</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.800</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.7pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Variance</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.162</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.7pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Deviation</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.4021</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.7pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Minimum</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">28.2</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.7pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Maximum</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">29.3</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.7pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Range</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">1.1</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 193.7pt; border: none; border-top: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="258" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Interquartile Range</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #AEAEAE 1.0pt; border-left: none; border-bottom: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.7</span></p>
</td>
<td style="width: 53.8pt; border: none; border-top: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="72">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
</tr>
</tbody>
</table>

<table class="MsoNormalTable" style="border-collapse: collapse; border: none;" width="0" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr style="page-break-inside: avoid;">
<td colspan="7" style="width: 442.5pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="590">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><b><span style="font-family: 'Arial',sans-serif; color: #010205;">One-Sample Test</span></b></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="3" style="width: 47.65pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="64" valign="bottom">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
<td colspan="6" style="width: 394.85pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="527" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Test Value = 28.3</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="2" style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">t</span></p>
</td>
<td rowspan="2" style="width: 51.45pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">df</span></p>
</td>
<td rowspan="2" style="width: 70.7pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Sig. (2-tailed)</span></p>
</td>
<td rowspan="2" style="width: 73.75pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Mean Difference</span></p>
</td>
<td colspan="2" style="width: 147.5pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="197" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">95% Confidence Interval of the Difference</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 73.75pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Lower</span></p>
</td>
<td style="width: 73.75pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Upper</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 47.65pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="64" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">weights</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; background-color: #FFFF00; color: #010205;">2.945</span></p>
</td>
<td style="width: 51.45pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">5</span></p>
</td>
<td style="width: 70.7pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; background-color: #FFFF00; color: #010205;">.032</span></p>
</td>
<td style="width: 73.75pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.4833</span></p>
</td>
<td style="width: 73.75pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.061</span></p>
</td>
<td style="width: 73.75pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.905</span></p>
</td>
</tr>
</tbody>
</table>



**Which option shows the test statistic value and the P-value for this test?**

- [ ] t = 28.783 and P-value = 0.1641
- [x] t = 2.945 and P-value = 0.016
- [ ] t = 2.945 and P-value = 0.032
- [ ] t = 2.945 and P-value = 5
- [ ] t = 2.945 and P-value = 0.064



**Question 9**

The following data represents the time in seconds taken by 7 rats to navigate a maze to find food at the end.
Is the average completion time quicker than 60 seconds?
Use SPSS to perform the hypothesis test then select the option that best corresponds to the test statistic value and P-value.

- [ ] t = 17.608 and P-value = 0.05
- [ ] t = -2.709 and P-value = 0.070
- [ ] t = -2.709 and P-value = 0.0175
- [x] t = 17.608 and P-value = 0.000
- [ ] t = -2.709 and P-value = 0.035

```R
> times <- c(46.2, 62.5, 40.9, 58.3, 46.7, 51.8, 57.6)
> times
[1] 46.2 62.5 40.9 58.3 46.7 51.8 57.6
```

```R
> t.test(times, lower.tail=TRUE, conf.level=0.99)

	One Sample t-test

data:  times
t = 17.608, df = 6, p-value = 2.153e-06
alternative hypothesis: true mean is not equal to 0
99 percent confidence interval:
 41.0515 62.9485
sample estimates:
mean of x 
       52 

```



**Question 10**

From a survey of 25 randomly selected students from Gold University asking about their weekly income, we obtained the following statistics.
$$
\bar{x} = 251.25\\
s = 19.62\\
n = 25
$$
Usually the mean income per week for students is $245 and we are interested in whether the mean income for students at Gold University is different than the standard population.

What is the probability that we would obtain the given sample income if the true mean income was $245 per week? (calculate the t test statistic then find the P-value)

- [ ] Between 0.05 and 0.10
- [ ] Between 0.025 and 0.05
- [ ] Below 0.025
- [ ] Above 0.2
- [x] Between 0.1 and 0.2

$$
SE = \frac{s}{\sqrt{n}} = \frac{19.62}{\sqrt{25}} = 3.924\\

t = \frac{\bar{x} - \mu_0}{SE} = \frac{251.25 − 245}{3.924} = 1.593
$$

```R
> 19.62 / sqrt(25)
[1] 3.924

> round((251.25 - 245) / 3.924, 3)
[1] 1.593

> round(dt(1.593, 24), 2)
[1] 0.11
```



**Question 11**

A random sample of 7 adults was selected to follow a particular diet to assess it's effectiveness for weight loss. Each adult had their weight recorded before starting the diet, and again after following the diet for 6 weeks, in kg.
The relevant summary statistics and SPSS t-test output for the average weight loss is shown.

 <table class="MsoNormalTable" style="border-collapse: collapse; border: none;" width="0" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr style="page-break-inside: avoid;">
<td colspan="6" style="width: 304.8pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="406">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><b><span style="font-family: 'Arial',sans-serif; color: #010205;">Paired Samples Statistics</span></b></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 81.45pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="109" valign="bottom">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
<td style="width: 51.5pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Mean</span></p>
</td>
<td style="width: 37.15pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="50" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">N</span></p>
</td>
<td style="width: 63.8pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="85" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Deviation</span></p>
</td>
<td style="width: 70.9pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="95" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Error Mean</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="2" style="width: 39.15pt; border: none; border-bottom: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="52" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Pair 1</span></p>
</td>
<td style="width: 42.3pt; border: none; border-bottom: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="56" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Before</span></p>
</td>
<td style="width: 51.5pt; border-top: none; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">87.29</span></p>
</td>
<td style="width: 37.15pt; border-top: none; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="50" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">7</span></p>
</td>
<td style="width: 63.8pt; border-top: none; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="85" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">10.657</span></p>
</td>
<td style="width: 70.9pt; border: none; border-bottom: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="95" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">4.028</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 42.3pt; border: none; border-bottom: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="56" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">After</span></p>
</td>
<td style="width: 51.5pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">86.43</span></p>
</td>
<td style="width: 37.15pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="50" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">7</span></p>
</td>
<td style="width: 63.8pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="85" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">9.829</span></p>
</td>
<td style="width: 70.9pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="95" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">3.715</span></p>
</td>
</tr>
</tbody>
</table>

<table class="MsoNormalTable" style="border-collapse: collapse; border: none;" width="0" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr style="page-break-inside: avoid;">
<td colspan="10" style="width: 22.0cm; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="832">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><b><span style="font-family: 'Arial',sans-serif; color: #010205;"><br>Paired Samples Test</span></b></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" rowspan="3" style="width: 115.7pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="154" valign="bottom">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
<td colspan="5" style="width: 359.2pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="479" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Paired Differences</span></p>
</td>
<td rowspan="3" style="width: 35.4pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="47" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">t</span></p>
</td>
<td rowspan="3" style="width: 42.55pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="57" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">df</span></p>
</td>
<td rowspan="3" style="width: 70.85pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Sig. (2-tailed)</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="2" style="width: 33.15pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="44" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Mean</span></p>
</td>
<td rowspan="2" style="width: 70.9pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="95" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Deviation</span></p>
</td>
<td rowspan="2" style="width: 77.95pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="104" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Error Mean</span></p>
</td>
<td colspan="2" style="width: 177.2pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="236" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">95% Confidence Interval of the Difference</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 92.15pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="123" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Lower</span></p>
</td>
<td style="width: 3.0cm; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="113" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Upper</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 42.15pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="56" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Pair 1</span></p>
</td>
<td style="width: 73.55pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Before - After</span></p>
</td>
<td style="width: 33.15pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="44" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.857</span></p>
</td>
<td style="width: 70.9pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="95" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">1.069</span></p>
</td>
<td style="width: 77.95pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="104" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.404</span></p>
</td>
<td style="width: 92.15pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="123" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; background-color: #FFFF00; color: #010205;">-.132</span></p>
</td>
<td style="width: 3.0cm; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="113" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; background-color: #FFFF00; color: #010205;">1.846</span></p>
</td>
<td style="width: 35.4pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="47" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">2.121</span></p>
</td>
<td style="width: 42.55pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="57" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">6</span></p>
</td>
<td style="width: 70.85pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.078</span></p>
</td>
</tr>
</tbody>
</table>

Which of the following is a 95% confidence interval for the true mean weight loss (in kg, and correct to 1 decimal place)?

- [ ] 1.8 to 2.1
- [ ] -1.3 to 1.8
- [ ] 0.1 to 1.8
- [x] -0.1 to 1.8
- [ ] 86.4 to 87.3



**Question 12**

A random sample of 7 adults was selected to follow a particular diet.
Each adult had their weight recorded before starting the diet, and again after following the diet for 6 weeks, in kg.

Use SPSS to calculate a 99% confidence interval for the true mean difference (before - after) in weight for adults following the diet then select the correct option (in kg and correct to one decimal place).

| *Adult* | Before | *After* |
| ------- | ------ | ------- |
| 1       | 85     | 78      |
| 2       | 83     | 79      |
| 3       | 90     | 88      |
| 4       | 99     | 96      |
| 5       | 85     | 83      |
| 6       | 95     | 94      |
| 7       | 71     | 69      |

- [x] 0.2 to 5.8
- [ ] 83.9 to 86.9
- [ ] 1.2 to 4.8
- [ ] 1.9 to 5.8
- [ ] -7.9 to 13.9

$$
t = \frac{\bar{d}}{\frac{s_d}{\sqrt{n}}} = \frac{3}{\frac{2}{\sqrt{7}}} = 3.9686\\
\bar{d} \pm t^*_{n-1} \times \frac{s_d}{\sqrt{n}}\\
3 \pm 3.707428 \times \frac{2}{\sqrt{7}}\\
3 \pm 3.707428 \times 0.756\\
3 \pm 2.80281557\\
0.2, 5.8
$$



```R
> before <- c(85,83,90,99,85,95,71)
> after <- c(78,79,88,96,83,94,69)
> Q15 <- data.frame(before, after)
> Q15$diff <- Q15$before - Q15$after
> Q15
  before after diff
1     85    78    7
2     83    79    4
3     90    88    2
4     99    96    3
5     85    83    2
6     95    94    1
7     71    69    2

> dbar <- mean(Q15$diff)
[1] 3

> s <- sd(Q15$diff)
[1] 2

> t = qt(0.01/2, 6, lower.tail = FALSE)
> t
[1] 3.707428

> SE <- sd/sqrt(n)
> SE
[1] 0.7559289

> lower <- round(3 - (t * SE), 2)
[1] 0.2
> upper <- round(3 + (t * SE), 2)
[1] 5.8

```



**Question 13**

The talk time for a mobile phone battery is the longest time that a single battery charge will last when constantly talking on the phone. The average talk time for a particular brand of battery type is stated as 6.5 hours. A new battery supplier claims that their batteries have a longer average talk time than 6.5 hours. For a random sample of 12 of the supplier’s batteries, the mean talk time was 6.85 hours, with standard deviation 0.78 hours.

A 90% confidence interval for the mean talk time was calculated as 6.45 to 7.25 hours.
Choose the most appropriate interpretation of the confidence interval.

- [ ] Since 6.5 is within the interval, this result is consistent with rejecting the null hypothesis that the mean talk time is 6.5.
- [ ] We can be certain that the mean talk time for the new supplier's batteries is between 6.45 and 7.25 hours.
- [ ] We are 90% confident that the mean talk time for the sampled batteries is between 6.45 and 7.25 hours.
- [ ] We are 95% confident that the mean talk time for the new supplier's batteries is between 6.45 and 7.25 hours.
- [x] We are 90% confident that the mean talk time for the new supplier's batteries is between 6.45 and 7.25 hours.



**Question 14**

A random sample of 7 adults was selected to follow a particular diet.
Each adult had their weight recorded before starting the diet, and again after following the diet for 6 weeks, in kg.
The relevant summary statistics and SPSS t-test output for the average weight loss is shown.
Did the adults' weight increase due to the diet?

<table class="MsoNormalTable" style="border-collapse: collapse; border: none;" width="0" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr style="page-break-inside: avoid;">
<td colspan="6" style="width: 330.25pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="441">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><b><span style="font-family: 'Arial',sans-serif; color: #010205;">Paired Samples Statistics</span></b></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" style="width: 81.4pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="109" valign="bottom">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Mean</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">N</span></p>
</td>
<td style="width: 72.2pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="96" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Deviation</span></p>
</td>
<td style="width: 73.75pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Error Mean</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="2" style="width: 39.15pt; border: none; border-bottom: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="52" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Pair 1</span></p>
</td>
<td style="width: 42.25pt; border: none; border-bottom: solid #AEAEAE 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="56" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Before</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">86.86</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">7</span></p>
</td>
<td style="width: 72.2pt; border-top: none; border-left: none; border-bottom: solid #AEAEAE 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="96" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">11.936</span></p>
</td>
<td style="width: 73.75pt; border: none; border-bottom: solid #AEAEAE 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">4.512</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 42.25pt; border: none; border-bottom: solid #152935 1.0pt; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="56" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">After</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">83.86</span></p>
</td>
<td style="width: 51.45pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="69" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">7</span></p>
</td>
<td style="width: 72.2pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="96" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">11.978</span></p>
</td>
<td style="width: 73.75pt; border: none; border-bottom: solid #152935 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="98" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">4.527</span></p>
</td>
</tr>
</tbody>
</table> 

<table class="MsoNormalTable" style="border-collapse: collapse; border: none;" width="0" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr style="page-break-inside: avoid;">
<td colspan="10" style="width: 22.0cm; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="832">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><b><span style="font-family: 'Arial',sans-serif; color: #010205;"><br><br>Paired Samples Test</span></b></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td colspan="2" rowspan="3" style="width: 106.35pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="142" valign="bottom">
<p style="margin: 0cm 0cm 0.0001pt; line-height: normal; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Times New Roman',serif;">&nbsp;</span></p>
</td>
<td colspan="5" style="width: 13.0cm; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="491" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Paired Differences</span></p>
</td>
<td rowspan="3" style="width: 35.4pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="47" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">t</span></p>
</td>
<td rowspan="3" style="width: 42.55pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="57" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">df</span></p>
</td>
<td rowspan="3" style="width: 70.85pt; border: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Sig. (2-tailed)</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td rowspan="2" style="width: 42.5pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="57" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Mean</span></p>
</td>
<td rowspan="2" style="width: 63.8pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="85" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Deviation</span></p>
</td>
<td rowspan="2" style="width: 70.85pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Std. Error Mean</span></p>
</td>
<td colspan="2" style="width: 191.4pt; border: none; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="255" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">90% Confidence Interval of the Difference</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 92.15pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="123" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Lower</span></p>
</td>
<td style="width: 99.25pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="132" valign="bottom">
<p style="margin: 0cm 3pt 0.0001pt; text-align: center; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="center"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Upper</span></p>
</td>
</tr>
<tr style="page-break-inside: avoid;">
<td style="width: 42.15pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="56" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Pair 1</span></p>
</td>
<td style="width: 64.2pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: #E0E0E0; padding: 0cm 0cm 0cm 0cm;" width="86" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #264a60;">Before - After</span></p>
</td>
<td style="width: 42.5pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="57" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">3.000</span></p>
</td>
<td style="width: 63.8pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="85" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">1.633</span></p>
</td>
<td style="width: 70.85pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">.617</span></p>
</td>
<td style="width: 92.15pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="123" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">1.801</span></p>
</td>
<td style="width: 99.25pt; border-top: none; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="132" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">4.199</span></p>
</td>
<td style="width: 35.4pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="47" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; background-color: #FFFF00; color: #010205;">4.861</span></p>
</td>
<td style="width: 42.55pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: solid #E0E0E0 1.0pt; background: white; padding: 0cm 0cm 0cm 0cm;" width="57" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; color: #010205;">6</span></p>
</td>
<td style="width: 70.85pt; border-top: solid #152935 1.0pt; border-left: none; border-bottom: solid #152935 1.0pt; border-right: none; background: white; padding: 0cm 0cm 0cm 0cm;" width="94" valign="top">
<p style="margin: 0cm 3pt 0.0001pt; text-align: right; line-height: 16pt; font-size: 11pt; font-family: 'Calibri', sans-serif;" align="right"><span style="font-size: 9.0pt; font-family: 'Arial',sans-serif; background-color: #FFFF00; color: #010205;">.003</span></p>
</td>
</tr>
</tbody>
</table> 

**Which option shows the test statistic value and the P-value for this test?**

- [ ] t = 3.000 and P-value = 0.617
- [x] t = 4.861 and P-value = 0.0015
- [ ] t = 4.861 and P-value = 0.006
- [ ] t = 4.199 and P-value = 0.003
- [ ] t = 4.861 and P-value = 0.003



**Question 15**

A random sample of 7 adults was selected to follow a particular diet.
Each adult had their weight recorded before starting the diet, and again after following the diet for 6 weeks, in kg.
Is there a reduction in weight due to the diet?
Use SPSS to perform the hypothesis test then select the option that best corresponds to the test statistic value and P-value.

| *Adult* | Before | *After* |
| ------- | ------ | ------- |
| 1       | 80     | 78      |
| 2       | 80     | 79      |
| 3       | 89     | 88      |
| 4       | 100    | 98      |
| 5       | 83     | 83      |
| 6       | 94     | 95      |
| 7       | 70     | 69      |

- [ ] t = 2.121 and P-value = 0.056
- [ ] t = 2.121 and P-value = 0.078
- [ ] t = 2.121 and P-value = 0.01
- [ ] t = 2.121 and P-value = 0.05
- [x] t = 2.121 and P-value = 0.039

```R
> before <- c(80,80,89,100,83,94,70)
> after <- c(78,79,88,98,83,95,69)
> Q15 <- data.frame(before, after)
> Q15
  before after
1     80    78
2     80    79
3     89    88
4    100    98
5     83    83
6     94    95
7     70    69

> t.test(Q15$before, Q15$after, alternative="greater", paired=TRUE)

	Paired t-test

data:  Q15$before and Q15$after
t = 2.1213, df = 6, p-value = 0.03907
alternative hypothesis: true difference in means is greater than 0
95 percent confidence interval:
 0.07197946        Inf
sample estimates:
mean of the differences 
              0.8571429 
```



**Question 16**

Two laboratory methods for determining the amylase level in human body fluids were compared.
Both methods were used on each of 10 subjects. The results are shown below (amylase level in units per millilitre).

|              | **1** | **2** | **3** | **4** | **5** | **6** | **7** | **8** | **9** | **10** |
| ------------ | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------ |
| **method 1** | 38    | 48    | 52    | 53    | 79    | 68    | 73    | 57    | 83    | 72     |
| **method 2** | 36    | 41    | 51    | 50    | 75    | 69    | 67    | 55    | 83    | 70     |

The calculated test statistic value (with differences = method 1 - method 2) was 3.28 with P-value<0.005.
Using $\alpha=0.01$, does method 1 show significantly higher amylase levels on average than method 2?
Choose the most appropriate conclusion.



- [ ] Since the P-value is greater than 0.01, there is no evidence that method 1 shows significantly higher amylase levels than method 2.
- [ ] Both methods showed similar amylase levels.
- [x] Since the P-value is less than 0.01, there is evidence that method 1 shows significantly higher amylase levels than method 2.
- [ ] Since the P-value is greater than 0.01, there is evidence that method 1 shows significantly higher amylase levels than method 2.
- [ ] Since the P-value is less than 0.01, there is no evidence that method 1 shows significantly higher amylase levels than method 2.

```R
> method1 <- c(38,48,52,53,79,68,73,57,83,72)
> method2 <- c(36,41,51,50,75,69,67,55,83,70)
> Q16 <- data.frame(method1, method2)
> Q16
   method1 method2
1       38      36
2       48      41
3       52      51
4       53      50
5       79      75
6       68      69
7       73      67
8       57      55
9       83      83
10      72      70

> t.test(Q16$method1, Q16$method2, alternative="greater", conf.level=0.99, paired=TRUE)

	Paired t-test

data:  Q16$method1 and Q16$method2
t = 3.2844, df = 9, p-value = 0.004731
alternative hypothesis: true difference in means is greater than 0
99 percent confidence interval:
 0.3664854       Inf
sample estimates:
mean of the differences 
                    2.6
```

