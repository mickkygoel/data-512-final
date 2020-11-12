# Final project for Data 512

### Motivation and problem statement
It would not be wrong to say that technology advancement is the leading factor for growth and development in the 21st century. Countries who lead in technical innovation are growing the fastest and people working within the tech industry are generally enjoying higher than average pay. Therefore, I wanted to understand the demographics of the building blocks of this technology industry, i.e. the developers. Analyzing the demographics of the developers around the world would help me draw conclusions about overall diversity and inclusion within this booming sector. For example, is technology advancement reaching every corner of the world, or is it clustered around a few pockets of the world? Is technology accessible and reachable to all genders and all races equally or does certain sections of the society still enjoy undue privileges? I would also like to examine how this social-economic trend evolving with time.

This study would help to unearth the existing biases and inequality within the developer community. These biases and differences can be seen as a proxy of the developing world in general. Therefore, I believe that this study is deeply rooted as human-centered. Since our cohort is also a part of this community, I am hopeful that the analysis would help us realize our own prejudices and make us more aware of them as we go into the workforce. The study would help us to amend our behavior, make the required changes in our process and set new targets to improve the diversity, respect and inclusion within the developer community.

### Datasets
The dataset that I plan to use for my analysis has been generated through the Stack Overflow Annual Developer Survey that was conducted by Stack Overflow from February 5 to February 28 in 2020. The data contains response of 65,000 professional and aspiring software developers, representing 186 countries around the world. The dataset contains information about the demographics of the respondents such as gender, nationality, ethnicity, years of experience, education, compensation, etc. The survey was anonymous and does not contain any personally identifiable information.

I plan to use this dataset as this provides very valuable data points that can directly answers the hypothesis that I plan to evaluate. Stack Overflow is used across the globe by all developers, therefore, I believe the dataset comes closest to the actual representation of the developers around the world.

The dataset and related information can be accessed from this link: https://insights.stackoverflow.com/survey/

Stack Overflow has allowed anyone to share, adapt, and create derivative works from the public 2020 Stack Overflow Developer Survey results as long as they attribute Stack Overflow. The dataset has been licensed under the Open Data Commons Open Database License (ODbL)

Since the survey was done in February 2020, it is safe to assume that the dataset is free from the biases due to Covid-19 pandemic. However, since the dataset is generated through a voluntary survey, there is a risk of selection bias. It is likely that a particular section of society is more likely or less likely to participate in a survey, and hence the dataset may not provide proportional representation for that particular section of society.

### Background and related work
It is no surprise that there are several discriminating biases against people from certain ethnicities, genders and sexualities. It is also well known that tech industry which is one of the most influential factors of development and growth is also rigged with such biases. This [Wikipedia article](https://en.wikipedia.org/wiki/Sexism_in_the_technology_industry#:~:text=Women%20in%20technology%20earn%20less,level%20women%20in%20Silicon%20Valley.) estimates that only about 17.6% of the undergraduate degrees were awarded to the women in 2011. It further states that the share of women employees in big tech firm is only about 30%. This ratio get even worse when we speak about senior executives. Therefore, it is important to study how this trend has shifted since 2015 in the tech industry. Are we moving in the right direction and at the right pace?

However in addition to biases based on demographics, I was also interested in understanding the role of money in job satisfaction. The Glassdoor also conducted a [study](https://www.glassdoor.com/research/does-money-buy-happiness-the-link-between-salary-and-employee-satisfaction/#:~:text=Salary%20vs.&text=%5B1%5D%20At%20first%20glance%2C,less%20than%20%2430%2C000%20per%20year) in 2015 which highlights the importance of other factors such as culture, growth, leadership etc in job satisfaction. However, it concludes that money is still one of the most important factor in most job. Through this analysis, I will try to restablish the connection between compensation and job satisfaction based on 2020 dataset.

### Research questions and hypothesis
In this project, I aim to answer and explore the following questions and hypothesis based on the above dataset:

1. Does money really bring job satisfcation? How does having higher compensation correlate with job satisfaction ? By exploring this question, I wish to comment on the motivating factors that work for humans. I assume that one does not necessarily has to rely completely on money for happiness, instead as a human one is looking for respect, work-life balance, joy and other such attributes in the job. This exploration would help us to corroborate above hypothesis.

2. Do people from certain ethnicities, genders and sexualities more likely to get a promotion relative to others? It is well recognized that certain sections of the society are exposed to low compensation despite the same work as others, however does this pay gap gets bigger as the person moves up the ladder, and does it affect the likelihood of person getting promoted? How is this trend changing with time.

3. Keeping the education level and years of experience same, do people from certain ethnicities, genders and sexualities exert more influence on what technologies their companies purchase? This question would shed light on the prevailing bias in the society based on demographics.

### Methodology
In my analysis, I plan to make use of the descriptive analysis, historical trends as well correaltion matrices. I will also plan to borrow concepts from inferential statistics, and apply them as applicable. I would also clearly state my assumptions whereever required before drawing any conclusions.

1. **Descritive analysis** - Before I dive deep into the data, I would provide overall summary of the data and perform some descriptive analsyis. This descriptive analysis would help us to udnerstand the overview of the data and how does the situation looks today. This would provide us with aggragated measures usch as % of women in tech work force, compensation by gender, nationality etc.

2. **Historical analysis** - Since the Stack Overflow survey results are available for multiple years, I will try to related them together and produce the historical trends for metrics of choice. This kind of analysis would involve appending all the survey resutls files together and plotting metrics against the year. the anslysis would answer questions such as how has pay gap between gender change over time, how has influence based on ethnicities change over time etc.

3. **Regression analysis** - Yet another correlation analysis that I would like to produce is regression. This analysis can help in establishing the relationship of  Compensation with education, experience, gender, sexuality, ethnicity etc. Thus it can provide a very wholesome picure of exactly what all biases go into determining your analysis, and how much powerful each of those biases are.

### Sources
Stack Overflow. (n.d.). Retrieved November 03, 2020, from https://insights.stackoverflow.com/survey/
Stack Overflow Developer Survey 2020. (n.d.). Retrieved November 03, 2020, from https://insights.stackoverflow.com/survey/2020
