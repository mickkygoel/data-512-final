# Role of Demographics in salaries of developers

***Mayank Goel***

***University of Washington***

## Abstract

### Motivation and problem statement
It would not be wrong to say that technology advancement is the leading factor for growth and development in the 21st century. Countries who lead in technical innovation are growing the fastest and people working within the tech industry are generally enjoying higher than average pay. This study would help to unearth the existing biases and inequality within the developer community. These biases and differences can be seen as a proxy of the developing world in general. Therefore, I believe that this study is deeply rooted as **human-centered**. 

### Datasets
The dataset that I plan to use for my analysis has been generated through the Stack Overflow Annual Developer Survey that was conducted by Stack Overflow from February 5 to February 28 in 2020. The data contains response of 65,000 professional and aspiring software developers, representing 186 countries around the world. The dataset and related information can be accessed from this link: https://insights.stackoverflow.com/survey/

Stack Overflow has allowed anyone to share, adapt, and create derivative works from the public 2020 Stack Overflow Developer Survey results as long as they attribute Stack Overflow. The dataset has been licensed under the Open Data Commons Open Database License (ODbL)

### Methodology
In my analysis, I plan to make use of the descriptive analysis, historical trends as well correaltion matrices. I will also plan to borrow concepts from inferential statistics, and apply them as applicable. I would also clearly state my assumptions whereever required before drawing any conclusions. Since the Stack Overflow survey results are available for multiple years, I have related them together and produce the historical trends for metrics of choice. Yet another  analysis that I would produced is regression. This analysis can help in establishing the relationship of  Compensation with education, experience, gender, sexuality, ethnicity etc. Thus it can provide a very wholesome picure of exactly what all biases go into determining your analysis, and how much powerful each of those biases are.

### Findings

**Descritive analysis** 

Through the first exploratory analysis, it can be found that there is a big skew in the distribution of the repsonsdents, as we can see there are about 8 time more men than women in the respondents, which highlight the underlying imbalance in the developer community. We can also see that there isn't any strong correlation between the various features in the dataset.

![alt text](https://github.com/mickkygoel/data-512-final/blob/main/Output/heatmap.png)

**Relation between money and happiness**

We can see that respondents who described their job as very dissatisfactory have indeed significantly higher mean salary than those who described their job as highly satisfactory. However, in the t-test conducted it can be seen that the results are not highly significant statistically. Therefore, it is hard to say with confidence if money really bring the happiness, but there is definitely some evidence againt it.

![alt text](https://github.com/mickkygoel/data-512-final/blob/main/Output/Salary%20vs%20satisfaction.png)

**Regression analysis** 

As we can see from the regression results below, there are several big biases present in the current developer community. Biggest of these biases arise from demographics including gender and race. Also, it can be seen from the results that biases due to sexuality are not statistically significant and hence not being included in the equation below.

**Historical analysis** 

We can see a small steady decrease in the gender gap over years,  however the rate is very low and it could take years to cover the gap. Therefore, it raise an important question regaring the strong measures that shoudl be taken now to resolve this universal issues.  We can see a big dip in 2017, however, this could be because of some of the anomaly in the underlying dataset, or how the survey results were measured.

## License
The project has been licenced under MIT, please read the [license file](https://github.com/mickkygoel/data-512-final/blob/main/LICENSE) for more details

## References
* DATA 512 Lectures, University of Washington
* Stack Overflow. (n.d.). Retrieved November 03, 2020, from https://insights.stackoverflow.com/survey/
* Stack Overflow Developer Survey 2020. (n.d.). Retrieved November 03, 2020, from https://insights.stackoverflow.com/survey/2020
* Quick Facts About the Gender Wage Gap. Retrieved November 03, 2020, from https://www.americanprogress.org/issues/women/reports/2020/03/24/482141/quick-facts-gender-wage-gap/
* Student's t-test. Retrieved November 03, 2020, from  https://en.wikipedia.org/wiki/Student%27s_t-test
