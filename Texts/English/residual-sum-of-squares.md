---
keywords: Investing,Fundamental Analysis
title: Residual Sum of Squares (RSS)
description: The residual sum of squares (RSS) is a statistical technique used to measure the variance in a data set that isn&#39;t explained by the regression model.
---

# Residual Sum of Squares (RSS)
## What Is the Residual Sum of Squares (RSS)?

The residual sum of squares (RSS) is a statistical technique used to measure the amount of [variance](/variance) in a data set that isn't explained by a regression model itself. Instead, it estimates the variance in the residuals, or [error term](/errorterm).

[Linear regression](/regression) is a measurement that decides the strength of the relationship between a dependent variable and one or more other factors, known as independent or explanatory variables.

## Understanding the Residual Sum of Squares

In general terms, the [sum of squares](/sum-of-squares) is a statistical technique utilized in regression analysis to determine the dispersion of data points. In a regression analysis, the goal is to determine how well a data series can be fitted to a function that could assist with explaining how the data series was generated. The sum of squares is utilized as a mathematical method for finding the function that [best fits](/line-of-best-fit) (varies least) from the data.

The RSS measures the amount of error remaining between the regression function and the data set after the model has been run. A smaller RSS figure represents a regression function that is very much fit to the data.

The RSS, otherwise called the sum of squared residuals, essentially determines how well a regression model explains or represents the data in the model.

## The most effective method to Calculate the Residual Sum of Squares
>
> RSS = **∑**^n^~i=1~ (**yi** - **f**(**xi**))^2^
>
>
> Where:
>
>
> y~i~ = the i^th^ value of the variable to be predicted
>
>
> **f**(x~i~) = predicted value of y~i~
>
>
> n = upper limit of summation
>
## Residual Sum of Squares (RSS) versus Residual Standard Error (RSE)

The residual standard error (RSE) is another statistical term used to describe the difference in [standard deviations](/standarddeviation) of observed values versus predicted values as shown by points in a regression analysis. It is a [goodness-of-fit](/goodness-of-fit) measure that can be utilized to analyze how well a set of data points fit with the real model.

RSE is figured by dividing the RSS by the number of observations in the sample less 2, and then taking the square root: RSE = [RSS/(n-2)]^1/2^

## Special Considerations

Financial markets have increasingly become more quantitatively driven; thusly, in search of an edge, many investors are using advanced statistical techniques to aid in their decisions. Big data, machine learning, and artificial intelligence applications further necessitate the utilization of statistical properties to direct contemporary investment strategies. The residual sum of squares — or RSS statistics — is one of many statistical properties enjoying a renaissance.

Statistical models are utilized by investors and portfolio managers to track an investment's price and utilize that data to predict future movements. The study — called regression analysis — could involve analyzing the relationship in price movements between a commodity and the stocks of companies engaged in producing the commodity.

> Finding the residual sum of squares (RSS) by hand can be troublesome and tedious. Since it involves a ton of subtracting, squaring, and summing, the calculations can be prone to errors. For this reason, you might choose to utilize software, for example, Excel, to do the calculations.
>

Any model could have variances between the predicted values and genuine results. Albeit the variances may be explained by the regression analysis, the RSS represents the variances or errors that are not explained.

Since a sufficiently complex regression function can be made to closely fit virtually any data set, further study is necessary to determine whether the regression function is, as a matter of fact, helpful in explaining the variance of the dataset.

Normally, however, a smaller or lower value for the RSS is ideal in any model since it means there's less variation in the data set. In other words, the lower the sum of squared residuals, the better the regression model is at explaining the data.

## Illustration of the Residual Sum of Squares

For a simple (yet lengthy) demonstration of the RSS calculation, consider the notable correlation between a country's consumer spending and its [GDP](/gdp). The following chart reflects the distributed values of [consumer spending](/consumer-spending) and Gross Domestic Product for the 27 states of the European Union, starting around 2020.
<table>
<thead>
<tr>
<th colspan='AngleSharp.Dom.Attr'>Consumer Spending vs. GDP for EU Member States</th></tr>
</thead>
<tbody>
<tr>
<td>Country</td><td>Consumer Spending(Millions)</td><td>GDP(Millions)</td></tr>
<tr>
<td>Austria</td><td>309,018.88</td><td>433,258.47</td></tr>
<tr>
<td>Belgium</td><td>388,436.00</td><td>521,861.29</td></tr>
<tr>
<td>Bulgaria</td><td>54,647.31</td><td>69,889.35</td></tr>
<tr>
<td>Croatia</td><td>47,392.86</td><td>57,203.78</td></tr>
<tr>
<td>Cyprus</td><td>20,592.74</td><td>24,612.65</td></tr>
<tr>
<td>Czech Republic</td><td>164,933.47</td><td>245,349.49</td></tr>
<tr>
<td>Denmark</td><td>251,478.47</td><td>356,084.87</td></tr>
<tr>
<td>Estonia</td><td>21,776.00</td><td>30,650.29</td></tr>
<tr>
<td>Finland</td><td>203,731.24</td><td>269,751.31</td></tr>
<tr>
<td>France</td><td>2,057,126.03</td><td>2,630,317.73</td></tr>
<tr>
<td>Germany</td><td>2,812,718.45</td><td>3,846,413.93</td></tr>
<tr>
<td>Greece</td><td>174,893.21</td><td>188,835.20</td></tr>
<tr>
<td>Hungary</td><td>110,323.35</td><td>155,808.44</td></tr>
<tr>
<td>Ireland</td><td>160,561.07</td><td>425,888.95</td></tr>
<tr>
<td>Italy</td><td>1,486,910.44</td><td>1,888,709.44</td></tr>
<tr>
<td>Latvia</td><td>25,776.74</td><td>33,707.32</td></tr>
<tr>
<td>Lithuania</td><td>43,679.20</td><td>56,546.96</td></tr>
<tr>
<td>Luxembourg</td><td>35,953.29</td><td>73,353.13</td></tr>
<tr>
<td>Malta</td><td>9,808.76</td><td>14,647.38</td></tr>
<tr>
<td>Netherlands</td><td>620,050.30</td><td>913,865.40</td></tr>
<tr>
<td>Poland</td><td>453,186.14</td><td>596,624.36</td></tr>
<tr>
<td>Portugal</td><td>190,509.98</td><td>228,539.25</td></tr>
<tr>
<td>Romania</td><td>198,867.77</td><td>248,715.55</td></tr>
<tr>
<td>Slovak Republic</td><td>83,845.27</td><td>105,172.56</td></tr>
<tr>
<td>Slovenia</td><td>37,929.24</td><td>53,589.61</td></tr>
<tr>
<td>Spain</td><td>997,452.45</td><td>1,281,484.64</td></tr>
<tr>
<td>Sweden</td><td>382,240.92</td><td>541,220.06</td></tr>
</tbody>
</table>
World Bank, 2020.

Consumer spending and GDP have a strong positive correlation, and it is feasible to predict a country's GDP in view of consumer spending (CS). Using the formula for a [best fit line](/line-of-best-fit), this relationship can be approximated as:

>
> GDP = 1.3232 x CS + 10447
>

The units for both GDP and Consumer Spending are in millions of U.S. dollars.

This formula is exceptionally accurate for most purposes, yet it isn't perfect, due to the individual variations in every country's economy. The following chart compares the projected GDP of every country, in view of the formula above, and the genuine GDP as recorded by the World Bank.
<table>
<thead>
<tr>
<th colspan='AngleSharp.Dom.Attr'>Projected and Actual GDP Figures for EU Member States, and Residual Squares</th></tr>
</thead>
<tbody>
<tr>
<td>Country</td><td>Consumer Spending Most Recent Value (Millions)</td><td>GDP Most Recent Value (Millions)</td><td>Projected GDP (Based on Trendline)</td><td>Residual Square (Projected - Real)^2</td></tr>
<tr>
<td>Austria</td><td>309,018.88</td><td>433,258.47</td><td>419,340.782016</td><td>193,702,038.819978</td></tr>
<tr>
<td>Belgium</td><td>388,436.00</td><td>521,861.29</td><td>524,425.52</td><td>6,575,250.87631504</td></tr>
<tr>
<td>Bulgaria</td><td>54,647.31</td><td>69,889.35</td><td>82,756.320592</td><td>165,558,932.215393</td></tr>
<tr>
<td>Croatia</td><td>47,392.86</td><td>57,203.78</td><td>73,157.232352</td><td>254,512,641.947534</td></tr>
<tr>
<td>Cyprus</td><td>20,592.74</td><td>24,612.65</td><td>37,695.313568</td><td>171,156,086.033474</td></tr>
<tr>
<td>Czech Republic</td><td>164,933.47</td><td>245,349.49</td><td>228,686.967504</td><td>277,639,655.929706</td></tr>
<tr>
<td>Denmark</td><td>251,478.47</td><td>356,084.87</td><td>343,203.311504</td><td>165,934,549.28587</td></tr>
<tr>
<td>Estonia</td><td>21,776.00</td><td>30,650.29</td><td>39,261.00</td><td>74,144,381.8126542</td></tr>
<tr>
<td>Finland</td><td>203,731.24</td><td>269,751.31</td><td>280,024.176768</td><td>105,531,791.633079</td></tr>
<tr>
<td>France</td><td>2,057,126.03</td><td>2,630,317.73</td><td>2,732,436.162896</td><td>10,428,174,337.1349</td></tr>
<tr>
<td>Germany</td><td>2,812,718.45</td><td>3,846,413.93</td><td>3,732,236.05304</td><td>13,036,587,587.0929</td></tr>
<tr>
<td>Greece</td><td>174,893.21</td><td>188,835.20</td><td>241,865.695472</td><td>2,812,233,450.00581</td></tr>
<tr>
<td>Hungary</td><td>110,323.35</td><td>155,808.44</td><td>156,426.85672</td><td>382,439.239575558</td></tr>
<tr>
<td>Ireland</td><td>160,561.07</td><td>425,888.95</td><td>222,901.407824</td><td>41,203,942,278.6534</td></tr>
<tr>
<td>Italy</td><td>1,486,910.44</td><td>1,888,709.44</td><td>1,977,926.894208</td><td>7,959,754,135.35658</td></tr>
<tr>
<td>Latvia</td><td>25,776.74</td><td>33,707.32</td><td>44,554.782368</td><td>117,667,439.825176</td></tr>
<tr>
<td>Lithuania</td><td>43,679.20</td><td>56,546.96</td><td>68,243.32</td><td>136,804,777.364243</td></tr>
<tr>
<td>Luxembourg</td><td>35,953.29</td><td>73,353.13</td><td>58,020.393328</td><td>235,092,813.852894</td></tr>
<tr>
<td>Malta</td><td>9,808.76</td><td>14,647.38</td><td>23,425.951232</td><td>77,063,312.875298</td></tr>
<tr>
<td>Netherlands</td><td>620,050.30</td><td>913,865.40</td><td>830,897.56</td><td>6,883,662,978.71</td></tr>
<tr>
<td>Poland</td><td>453,186.14</td><td>596,624.36</td><td>610,102.900448</td><td>181,671,052.608372</td></tr>
<tr>
<td>Portugal</td><td>190,509.98</td><td>228,539.25</td><td>262,529.805536</td><td>1,155,357,865.6459</td></tr>
<tr>
<td>Romania</td><td>198,867.77</td><td>248,715.55</td><td>273,588.833264</td><td>618,680,220.331183</td></tr>
<tr>
<td>Slovak Republic</td><td>83,845.27</td><td>105,172.56</td><td>121,391.061264</td><td>263,039,783.25037</td></tr>
<tr>
<td>Slovenia</td><td>37,929.24</td><td>53,589.61</td><td>60,634.970368</td><td>49,637,102.7149851</td></tr>
<tr>
<td>Spain</td><td>997,452.45</td><td>1,281,484.64</td><td>1,330,276.08184</td><td>2,380,604,796.8261</td></tr>
<tr>
<td>Sweden</td><td>382,240.92</td><td>541,220.06</td><td>516,228.185344</td><td>624,593,798.821215</td></tr>
</tbody>
</table>
World Bank, 2020.

The column on the right indicates the residual squares-the squared difference between each projected value and its genuine value. The numbers appear large, however their sum is really lower than the RSS for any other conceivable trendline. Assuming a different line had a lower RSS for these data points, that line would be the best fit line.

## Features
- A value of zero means your model is a perfect fit.
- The RSS is involved by financial analysts in order to estimate the legitimacy of their econometric models.
- The residual sum of squares (RSS) measures the level of variance in the error term, or residuals, of a regression model.
- Statistical models are utilized by investors and portfolio managers to track an investment's price and utilize that data to predict future movements.
- The smaller the residual sum of squares, the better your model fits your data; the greater the residual sum of squares, the poorer your model fits your data.
## FAQ
### Is RSS the Same as the Sum of Squared Estimate of Errors (SSE)?
The residual sum of squares (RSS) is otherwise called the sum of squared estimate of errors (SSE).
### What Is the Difference Between the Residual Sum of Squares and Total Sum of Squares?
The total sum of squares (TSS) measures how much variation there is in the observed data, while the residual sum of squares measures the variation in the error between the observed data and modeled values. In statistics, the values for the residual sum of squares and the total sum of squares (TSS) are oftentimes compared to one another.
### Is the Residual Sum of Squares the Same as R-Squared?
The residual sum of squares (RSS) is the absolute amount of explained variation, whereas R-squared is the absolute amount of variation as a proportion of total variation.
### Can a Residual Sum of Squares Be Zero?
The residual sum of squares can be zero. The smaller the residual sum of squares, the better your model fits your data; the greater the residual sum of squares, the poorer your model fits your data. A value of zero means your model is a perfect fit.
