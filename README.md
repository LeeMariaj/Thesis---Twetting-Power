# Thesis - Tweeting Power:
Analyzing sentiment and rhetoric by Colombian Congressional Members

Author: María José Lee

Supervised: William Lowe

Institution: Hertie School

Program: Master in Data Science for Public Policy

Below you will a general collections of the results achieved for within thesis, to delve deeper into the methods, or other relevant information, visitors are encouraged to either go through the "Thesis Document - Submitted Version", which is the Thesis document as was submitted to the Hertie School, or to the "Thesis Document - Final Version", which has been updated to account for some gramatical and formatting errors in the submited version.

## General Statistics
The analysis is in general divided into three levels, i) for the Camara de Representantes as a whole, ii) by the gender of the members, and iii) by the political association of the party the members belong to. Table 1 then refers to the dataset in its most general terms. 

![Table 1](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/235d7d05-4715-4a58-9d5f-6d7405b39298)

Table 2, then, seeks to quantify the difference between members according to their gender. Here, one of the most noteworthy results is the fact that of the total number of tweets within the dataset, only around 27.44% were made by women. Also worth noting is that despite being less represented within Congress, and therefore the database, they still write more tweets on average than their male counterparts, despite both writing tweets of roughly the same length.

![Table 2](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/9144a530-e378-4a9d-895e-0a2d4e70e49b)

Lastly, congress members were divided according to the stated allegiance of their respective party, or the nature of the seat that they hold, which is in turn reflected in Table 3. Here we see that the database is largely dominated, both in terms of members and in terms of tweets, by parties associated with the government. This reflects the dominance that the political party currently in charge (Pacto Historico) had at the beginning of its period in terms of other political party allies (Galvis, 2022), as many traditionally right-leaning parties chose to ally themselves with the current administration.

![Table 3](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/2bc01e34-9235-458f-a388-16c9cf7eb1db)

Particularly interesting amongst this abundance of support for the current administration, is the significant number of tweets made by members of the opposition on average, compared to the same metric for either the Independent Association as well as the Peace Association, which while slightly smaller in terms of members are vastly surpassed in both the absolute number of tweets, but even more acutely, in the average number of tweets metric.

### Gender by Association

![Figure 1 3](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/ce9b29e1-5691-4db9-818f-dac96a9acdd8)

Figure 3, provides additional insights into the quite disparaging situation of gender representation within Congress. In general, the gender proportion of our sample is very close to the actual gender proportion within the Camara de Representantes, with the sample placing this number at 26.32%, as opposed to the actual number, which is 28.35%.

Worth noting is the considerably low proportion of women members of Camara that belong to the Opposition, though this number is significantly lower than the actual number, it remains the lowest proportion out of the sample. This statistic is further soured given that only the Independent association is made up of at least ⅓ of women, meaning that while parties may be indeed meeting the requirements provided by law, there is still significant work to be done in this respect.

### Use of Multimedia Resources by Association

![Figure 1 4](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/1beeaeb8-340b-4301-85c0-32b9a1987c4b)

The use of multimedia is understood here as making a tweet that is accompanied by either an image, a video, or a link to a news article. Additionally, the distinction between informative and other refers to an internal classification within the database. If the tweet was accompanied by either a news article or an image that contained text of informative character, then it would be considered “Informative”. On the other hand, images of congress members, political cartoons, images commemorating a particular date, videos, etc, are classified as “Other”.

	Overall, we see that the behavior regarding utilizing informative media seems to be pretty consistent amongst all 4 party associations. The only significant deviation seems to be within the Peace Association, which uses about double the amount of multimedia resources within their tweets, though this effect is largely dominated by the “other” category.

 ## Negative and Positive Speech

 ![Figure 1 5](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/314736ff-53d6-4de8-8604-085692b0bd46)

In general, we observe that in our overall sample, there is ample representation for the entire range of possible scores, however, there seems to be a preference for positive results. This is further emphasized by the fact that the overall proportion of tweets classified as positive (57.61%) more than doubles the proportion of tweets classified as negative (21.44%). This trend can be further confirmed by Figure 5.

### By Gender

![Figure 1 6](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/6f3aea42-52e3-462c-b623-fb2f45b1b000)

Here we can see that both women and men have tweets raging through the entire range of possible scores, though still showing a slight preference for tweets that can be classified as positive. In general, both distributions seem fairly close to one another, with a mean and a median only slightly more positive for women than for men, and a slightly wider range for the middle 50% on the male distribution. This would seem to go against common beliefs regarding men being significantly more aggressive than women.

### By Political Association

![Figure 1 7](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/4c27a751-ba64-4482-9374-7eb1914f6d8a)

In contrast to the relative cohesion when analyzed by gender, we see significantly more variation at the Political Association level. According to Figure 7, though the members belonging to the Peace Association seem to be the ones that have the higher proportion of their tweets classified as positive, it is the members belonging to the Independent Association who, on average tend to have more tweets that can be classified as positive.

As for the differences between the scores for the tweets belonging to members grouped within the Opposition Association, as opposed to those of members grouped within the Government Association, we see both a higher proportion of their overall tweets being classified as negative, as well as lower average scores. 

It is, however, worth pointing out that, though considerable political turmoil was happening during this period, such as i) the end of a highly controversial presidency by Iván Duque, belonging to one of the parties of the current opposition, ii) the appointment of a new president, which not only is the first left-leaning politician to fill this place, but who was also involved within the guerrilla movement M-19, as well as other confounding factors, all parties have more than half of their tweets being classified as positive.  

## Use of Political Leaders

![Figure 1 8](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/89950b2d-9a5c-44b5-8d01-4d665588f15a)

In this section, a closer look is taken at those tweets that were detected to contain mentions of the four most recent presidents. In particular, Figure 8 helps us represent the distribution of the score, as well as the average score, for these types of tweets. Here we have that, excluding those associated with the Peace Association, the scores associated with these tweets expand through the entire possible range. Some key highlights from this graph include the fact that, true to their namesake, the Independent Association, despite seeming to feature mostly tweets with an associated positive score has an average score of close to zero. 

Also worth noting that, despite the Opposition Association featuring more negative scores than the Government Association, ultimately their average scores are very close. It is, of course, worth keeping in mind that being mentioned within an overall negative context does not necessarily imply that something negative is being said regarding that person, and the same should hold regarding being mentioned within an overall positive context. 

Additionally, it is also relevant to mention that both the Peace Association, as well as the Independent Association, have a considerably lower number of tweets mentioning any of these political leaders, and even some missing values, meaning that any distribution we might see from them, will ultimately be lead by a small number of tweets, which given the scarcity, seem in turn seem to be quite different from the rest of their respective Associations, and hence, hardly fit to adequately represent them. 

Because of this, the subsequent analysis will overlook these two associations, and instead concentrate on the differences between the Opposition Association and the Government Association, as both have a higher number of tweets compared to the other two, and a similar number of tweets amongst themselves.

### Gustavo Petro: From Opposite Sides of the Political Spectrum

![Figure 1 9](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/51170a2f-f0e3-4838-b952-c8b3db046b43)

As expected, Figure 9 shows the Opposition Association featuring a higher number of tweets associated with negative scores, while the Government Association features a higher number of tweets associated with positive scores. 

However, it is also worth noting that neither distribution seems particularly inclined towards either extreme, as shown by the fact that the average associated score for the Opposition Association is very close to being neutral, while the average associate score for the Government Association is still within the lower third of the positive distribution. 

Further research might be necessary, however, to understand if this is the actual distribution, or if given that this is specifically filtering for their name, it is therefore ignoring cases in which members of the Opposition Association might use nicknames or even insults to refer to him, hence explaining the seeming lack of significant negative scores.

### Alvaro Uribe: From Opposite Sides of the Political Spectrum

![Figure 1 10](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/70052038-3c5f-4db6-a2b5-552867b22d46)

Figure 10 again, seems to stay within the expectations for the Opposition, as it shows how almost ¾ of the tweets from them have a positive score associated, as well as a positive average associated score. More unexpected, however, is the distribution for the Government Association, not only do the associated scores cover the entire range, but more than half of the sample is positive, leading to an overall positive average score. 

As is the case for the above result, further research should be conducted to determine whether this is the actual distribution, or if given that this is specifically filtering for their name, it is therefore ignoring cases in which members of the Government Association might use nicknames or even insults to refer to him, hence explaining the seeming lack of significant negative scores.

### Iván Duque: From Opposite Sides of the Political Spectrum

![Figure 1 11](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/f95631b8-7daf-4de4-a54f-ea72f8c04ec2)

The figure of Ivan Duque, both within his party, as well as outside it, is a very complicated and controversial one. This is in large part due to his quite problematic presidential term, in which he was often ridiculed within social media for statements he made, as well as heavily critiqued inside and outside his party, over the decisions he took. 

It is then no surprise that quite a large proportion of the score range is contained by the middle 50% of the data, both for the Opposition Association as well as for the Government Association. It is considered additionally telling that both the averages for the associated score for the Opposition and the Government seem to be close to one another, and in turn, close to zero, though naturally the first is on the positive side of the spectrum, while the latter is on the negative one.

### Juan Manuel: From Opposite Sides of the Political Spectrum

![Figure 1 12](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/5af9792c-f94a-4d35-a99c-41839cad0ad7)

Lastly, there is the figure of Juan Manuel Santos, who had a quite complicated history during his two terms as President. After being the head of the Defense Ministry during the presidency of former President Alvaro Uribe, and being nominated by him to run as his successor, he decided near the end of this first term to break away from him by announcing he had been secretly negotiating what would later be known as the Peace Treaty of 2016 between the Colombian government and the guerrilla organization FARC-EP. These peace talks, were in turn, immediately condemned by former President Alvaro Uribe, and caused a political rift between the two figures.

Given this context, it is unsurprising that Figure 12 shows just a little under ¾ of the entire set of tweets from the opposition having a negative score associated with them, as well as the biggest average associated score in absolute terms, well into the negatives. More surprising though, is how the tweets within the Government Association are in turn mostly contained within the positive range of the possible associated scores, as well as, very moderate, positive average associated score.

## Public Response In terms of Score

The following plots and regressions seek to further add to the study of the score associated with each tweet, with the closest metric we have to evaluate viewer support, the number of likes. This analysis ultimately showed, after controlling for extreme values within the likes variable, as well as for possible inaccuracies within the score variable, a negative relationship between the score associated with each tweet, and the number of likes, which would suggest a preference for negative over positive content. 

Additionally, these results held, both in the case of analyzing the entire range for the associated score, as well as when analyzing the negative and the positive sub-sections. Ultimately, though not every coefficient was classified as statistically significant, all those that were, agreed with this particular trend.

### By Gender

![Figure 1 13](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/e5808235-a999-4a23-aadf-7aec9937d93a)

Figure 13 shows a scatterplot, mapping each point according to its associated score and the number of likes it received, additionally, points have been colored either pink for women or blue for men. Finally, a linear regression was run with the overall data, as well as with the data segregated by gender. 

For the General Regression, the **General Coefficient was -58.61**, with an **intercept of  135.98** and a **p-value of 2.40e-50**. This means that for our overall sample, there was a negative relation between the Score and the number of likes, which was statistically significant. Additionally, for women, the **Coefficient was -203.74**, considerably higher than the general one, with an **intercept of 217.67** and a of **p-value of  0.003**. Finally, the results for men show a **Coefficient of -49.21**, with an **intercept of 99.70** and a **p-value of 0.017**.

### By Political Association

![Figure 1 14](https://github.com/LeeMariaj/Thesis---Twetting-Power/assets/92488913/f3ab395b-c10c-4a9f-962f-67e9f8dc3a39)

Similar to Figure 14, Figure 15 shows the relationship between the number of likes and the associated score of each tweet, separated by the political association of the author responsible for each tweet. For the Political Associations, we find that: 

- The Coefficient for Government is: Slope: -53.86, Intercept: 142.59, p-value: 0.0000
- The Coefficient for Independent is: Slope: 10.07, Intercept: 29.25, p-value: 0.0107
- The Coefficient for Opposition is: Slope: -94.93, Intercept: 169.01, p-value: 0.0000
- The Coefficient for Peace is: Slope: 2.34, Intercept: 7.84, p-value: 0.0138

In general, these results seemed to indicate two conflicting effects, for parties contained within either the Government Association or the Opposition Association, there is a negative relation between the number of likes and the associated score for a particular tweet, meanwhile, parties contained within the Peace Association or Independent Association there is a positive effect between the number of likes and the associated score for a particular tweet. 

