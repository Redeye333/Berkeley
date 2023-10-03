# Berkeley - Module 5

**Useful Links**
You can find the primary GitHub link to this assignment [here](https://github.com/Redeye333/Berkeley/tree/4de62bd849eb8da2f7afb7f70cb47d0d52eea87b/Module5).
Or you can go directly to the notebook file [here](https://github.com/Redeye333/Berkeley/blob/4de62bd849eb8da2f7afb7f70cb47d0d52eea87b/Module5/Daly%20Module%205%20Practice.ipynb)

**Findings**

Upon assessing the dataset I looked at a number of variables to try and identify both the types of coupons that should be used (if any) and to what type of user arttributes they would be most relevant and used by.  While there were many variables to use, I chose to leverage a subset of them for my analysis. I'm sure if more time was invested I could come up with other fundings for the many variables in the dataset.

Overall summary of findings:

**Some coupons are used much more than others**
The 2 most used coupons, as a percentage, were for Carry Away coupons (74% accepted) and less expensive restaurants which are catagorized as less than $20 (71%).  The next closest catagory was for coffeehouses and that was only at 50%, while expensive restaurants came in at 44% and bars at the lowest of 41%.

**Occupation matters, but moreso for some coupons vs others**
When assessing occupation against the types of coupons we have some interesting findings.  When we look at the expensive restaurants, we find that retired people only accept 25% of the coupons, unemployed only accept 36% and people that work in Business & Financial industry only accept 36%.  I thought the latter metric was very interesting as I initially assumed it would be about income and cost, but another factor is likely at play here.  People that work in business & financial may be the most busy as they don't work set hours many times, and may simply not have time to go to a nice restaurant at a moments notice.  However, even the higest acceptance rate for expensive restaurants was only at 62% and 66% for Office Admins and Healthcare Workers.  While it's more than double the lowest occupation, it was still rather low.

When we looked at Carry Away, we found a much different picture.  Retired and unemployed (who were at 25% and 36% for expensive restaurant coupons), came in at a whopping 75% and 71%.  Business and FInancial, who were also at 36%, came in at 82%!  We also saw the overall acceptance rate being much higher with carry away.

**Bar Coupons used by those that frequent bars**
We found that people who went to bars more than 3 times a month accepted the coupon for a bar 78% of the time, while people that went less than 3 times accepted it 31% of the time.  The overall findings when assessing age, passengers and frequency showed that the user characteristics of how often then went to a bar, greatly influenced the acceptance rate.


**Conculsions & Recommendations:**

1) Focus on sending coupons for Carry Away & less expensive restaurants as those are the most accepted
2) When sending coupons for expensive restaurants, send them to Office Admin & Healthcare workers as they are most likely to accept them.
3) Bar Coupons are used more than double by those that go to a bar more than 1 time a month vs those that go less.  Bar coupons should be targeted to those users who frequent bars more odten, regardless of age.

Overall I do believe Amazon should continue with the coupon program and continue to refine the targeted audience based on various characteristics of the users.  As users leverage the coupons, it will provide even more insightful data that can be used on specific brands, establishments, etc. to further tailor the targeted marketing.
