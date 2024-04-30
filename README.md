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
