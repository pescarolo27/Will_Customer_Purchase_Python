# Will This Customer Purchase Your Product (Python)

**Background:** Online shopping decisions rely on how consumers engage with online store content. As part of a new startup company that has just launched a new online shopping website, the marketing team has asked for a reviewal of a dataset pertaining to online shoppers' purchasing intentions gathered over the last year. Specifically, the team wants you to generate some insights into customer browsing behaviors in November and December, the busiest months for shoppers. You have decided to identify two groups of customers: those with a low purchase rate and returning customers. After identifying these groups, you want to determine the probability that any of these customers will make a purchase in a new marketing campaign to help gauge potential success for next year's sales. These insights will help the marketing team understand customer engagement on the website.

**The Data:** A dataset is provided containing several variables about each shopping session. Each shopping session corresponded to a single user.

**Purpose:** The marketing team asked you to analyze the behavior of online customers during November and December, the busiest months for shoppers. Their specific questions include:
- What are the purchase rates for online shopping sessions by customer type for November and December?
- What is the strongest correlation in total time spent among page types by returning customers in November and December?
- A new campaign for the returning customers will boost the purchase rate by 15%. What is the likelihood of achieving at least 100 sales out of 500 online shopping sessions for the returning customers?

This project was done in October, 2025.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Brief Summary
This project utilizes quantitative & statistical analyses plus probability calculations to analyze & estimate the behavior of online customers. The marketing team is particularly interested in activity during November & December which are two of the busiest months of the year when it comes to online commerce.  
Analyses were conducted to analyze differences between returning & new customers & how they spent their time across the various pages of the company's website. In addition, probability calculations were built to help project levels of success that the new campaign might have.

Before such analyses were performed, the dataset was examined to look for inconsistencies & other invalid data points that might prove obstructive.  
Of the 12,055 sessions, there were only a couple of problems in the data all of which were fortunately contained in the same record. In the last record, the session registered a month labeled "N" (possibly a typo for November). Additionally, it failed to register the customer type & whether a purchase was made or not. Given that this record accounted for the only inconsistencies in the fairly sizable dataset, this record was dropped.  
The only other validation steps that were taken involved converting a couple of data types.

#### Analysis I - Purchase Rates by Customer Type
To get an assessment as to how returning & new customers contributed to sales during the busiest months of the year (November & December), their purchase rates were examined. During this period, 4,450 total online sessions were registered which account for approximately 37% of the sessions seen across the year.

In these two months, returning customers registered 3,722 sessions whereas new customers registered only 728. Nevertheless, new customers made a purchase in about 27% of their sessions whereas returning customers only made a purchase in about 20%, indicating that new customers were arguably more valuable on a per-customer basis during these months.  
Both groups of customers contributed in major ways to the company during the last two months of the year. While returning customers generated more business outright, new customers were somewhat more valuable in terms of purchase rate.

With this in mind, returning customers should continue to be relied upon as the primary source of revenue; however, new customers can potentially bring a tremendous amount of value particularly during these last two months of the year. Assuming that the most engagement from new customers on the website occurs in November & December, additional marketing could be employed for this group leading up to & during these two months to further incentivize them to make purchases.  
Outside of these months, the returning customer base should be the primary target when it comes to marketing given that they are more reliable in terms of sales. Marketing could still be done for non-returning customers, but less investment should be put into them outside of the November-December timeframe given that they are generally more volatile & less reliable in terms of their purchasing behavior.  Additional analyses could be done to explore engagement & purchasing patterns of these two groups over the course of the year. Such insights can reveal additional opportunities in which marketing strategies could be deployed.


#### Analysis II - Time Spent by Page Type of Returning Customers
In evaluating how returning customers spent their time across the three page types during the busiest months of the year (November & December), it was revealed that there were either negligible or slightly positive relationships between these variables. More specifically, correlation coefficients were calculated to evaluate the significance of such relationships.

In this timeframe, in which returning customers logged 3,722 sessions, the strongest relationship in the time spent by these customers across the three page types was between that of product-related & administrative pages. With a correlation of about 0.42, it signifies that the more time that returning customers spent on product-related pages, the more time they tended to spend on administrative pages.

When interpreting these findings, multiple assumptions were made regarding the functionality & purpose of the three page types. Ultimately, it was inferred that customers who spend more time on product-related pages are more likely to make a purchase because the other two page types don't directly interact or overlap with products & purchases. Given this, the correlation of 0.42 between the time customers spent on product-related pages & administrative pages may be an indication that customers who were more likely to make a purchase spent more time on administrative pages than on informational pages. As such, it can be said that administrative pages are more informative in the context of customers making purchases than informational pages.

Without more information as to the purpose & functionality of these three page types, it is not productive to make final conclusions or recommendations about them. Regardless, these findings could be indicative that there are features or aspects of the informational pages that fail to contribute to customers' browsing & shopping as meaningfully as administrative pages appear to do. On another note, the fairly weak correlations between time spent on both administrative & informational pages & that of product-related pages (about 0.42 & 0.37 respectively) may signify that more could be done to entice customers towards browsing the company's products, & therein, persuading them to make purchases.


#### Analysis III - Sales Estimate for New Campaign
In an attempt to bolster the purchase rate of returning customers, the company has assembled a new campaign that is projected to boost this rate by 15 percent. To assess the effectiveness of this new campaign, a probability estimate was performed. Specifically, given this boosted purchase rate, what is the likelihood of achieving at least 100 sales out of 500 online shopping sessions for returning customers.  
Such a calculation can produce an estimate as to how many sales returning customers might generate during this new campaign. As a result, it can inform the company as to how successful this new campaign might be & whether the differences are worth it being enacted permanently.

Over the last year, 1,441 sessions of the 10,386 logged by returning customers saw a purchase, which is roughly 13.9%. With the new campaign, this purchase rate will be expected to be almost 29%. Using a binomial distribution with this purchase likelihood, the probability of achieving at least 100 sales in 500 shopping sessions of returning customers is about 99.9998%. In other words, in 500 sessions of returning customers, this purchase rate would correspond to 499.999 sessions that see at least 100 purchases. If this were extrapolated to one million sessions, only two sessions will fail to generate at least 100 purchases.

Assuming that the 15% jump in purchase rate of returning customers will stick, it is safe to say that this campaign will more than likely generate at least 100 sales in every 500 shopping sessions. To determine the ultimate profit that can be achieved through this, various methods & projections could be employed.  
As an example, this new purchase rate would theoretically total 100 new purchases in just under two weeks & 500 sessions at just over two weeks. Similar examples demonstrating the effects of this new campaign can be referenced in the project.
