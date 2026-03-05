![crowdfunding_goal_analysis1](https://github.com/njgeorge000158/Crowdfunding-Goal-Analysis-in-Excel/assets/137228821/748d13b8-fe17-4c3d-9f87-987078ea9a33)

---

**Crowdfunding Campaign Analysis: Trends, Insights, and Limitations**

**Background and Approach**

Since the late 2000s, crowdfunding has grown into a widely adopted mechanism for launching new products, validating ideas, and generating public interest. To better understand the dynamics driving campaign success, I analyzed a database of 1,000 sample crowdfunding campaigns. Using spreadsheet-based tools, I constructed six analytical worksheets — Crowdfunding, Primary Category by Outcomes, Sub-Category by Outcomes, Months by Outcomes, Campaign Summary, and Statistical Analysis (Goals) — and derived additional tables and visualizations to explore trends across categories, timing, funding levels, and backer distributions.

**Category Performance: Popularity vs. Success**

Merging pivot tables from the Primary Category and Sub-Category worksheets, and excluding any category with fewer than five campaigns due to insufficient sample size, I calculated the likelihood of success by category. Overall, crowdfunding campaigns succeed at a rate of 56%, whether measured at the primary or sub-category level. Among primary categories, Technology, Photography, and Publishing lead in success rate. At the sub-category level, Web (Technology), Translations (Publishing), and Television (Film & Video) rank highest.

Volume tells a different story. Theater, Film & Video, and Music dominate in sheer campaign numbers, with Plays, Rock, and Documentary being the most pursued sub-categories. This divergence between popularity and success rate points to one of the analysis's central conclusions: the categories that attract the most campaigns are not necessarily the ones most likely to succeed.

**Funding Rates: All Campaigns vs. Successful Ones**

To go beyond outcome counts, I constructed a pivot table comparing campaign goals against pledged contributions across categories. For all campaigns regardless of outcome, the overall funding rate — pledged contributions as a percentage of stated goals — is 97%. Technology, Music, and Theater lead among primary categories, while Metal (Music), Wearables (Technology), and Jazz (Music) top the sub-category rankings.

The picture shifts considerably when the analysis is restricted to successful campaigns alone. Here, the overall funding rate rises to 191%, meaning successful campaigns receive nearly double their stated goals on average. Food and Games stand out among primary categories, with successful campaigns in those fields receiving 2.3 and 2.1 times their goals, respectively. At the sub-category level, the results are even more pronounced: successful Metal (Music) campaigns receive 4.4 times their goals, and successful Jazz (Music) campaigns receive 3.5 times — suggesting that niche audiences, when engaged, can drive exceptional funding outcomes.

**Timing and Monthly Trends**

A raw view of the Months by Outcomes worksheet offered little immediate insight, as absolute counts are difficult to interpret without normalization. Converting these figures into monthly success rates — in a dedicated Months by Outcomes (%) worksheet — revealed a clearer pattern. Success rates range from 49% to 64% across the calendar year, rising steadily from January through June, plateauing through September, then declining into year-end. Two notable exceptions disrupt this trend: success rates drop sharply in May and August, falling 5% and 13% from their respective prior months. These anomalies notwithstanding, the broader seasonal pattern suggests that campaign timing is a meaningful lever — one that creators can strategically exploit to improve their odds of success.

**Goal Ranges and Sample Size Constraints**

The Campaign Summary worksheet examines success rates across ranges of campaign goals. The line chart shows success rates increasing as goals rise from $0 to $15,000, leveling off between $15,000 and $34,999, and declining from $35,000 onward. However, this pattern must be interpreted with caution. The three lowest goal ranges account for the vast majority of campaigns — two categories contain hundreds of projects each, and one contains roughly fifty — while every category at or above $10,000 comprises fewer than 15 campaigns. These thin sample sizes at higher goal thresholds render the observed trends statistically unreliable. This data sparsity problem is not isolated to the Campaign Summary; it recurs elsewhere in the dataset and meaningfully constrains the conclusions that can be drawn.

**Statistical Distributions and the Case for the Median**

The Statistical Analysis (Goals) worksheet presents distributions of backer counts for successful and unsuccessful campaigns. Both distributions exhibit wide ranges between minimum and maximum values, large variances, and substantial divergence between mean and median values. When the mean and median diverge as significantly as they do here, it signals that outliers are distorting the average, pulling it away from the typical value. In such cases, the median is the more appropriate and informative measure of central tendency. Unfortunately, the existing calculations rely on averages throughout — a methodological choice that undermines the accuracy of the reported figures.

Beyond the measure-of-center issue, the variance analysis reveals an asymmetry between outcomes: successful campaigns exhibit considerably greater variance in backer counts than unsuccessful ones. This makes intuitive sense. Unsuccessful campaigns tend to attract few or no backers, clustering the distribution near zero. Successful campaigns, by contrast, draw backers across a wide spectrum — from modest community support to viral audience mobilization — producing a far more dispersed distribution.

**Additional Analyses Worth Pursuing**

Three supplementary analyses could meaningfully deepen this investigation. First, a table comparing countries against the percentage of successful campaigns would reveal whether geography is a determinant of crowdfunding success. Second, charting the percentage of successful campaigns by year would clarify whether the phenomenon is growing, plateauing, or following a cyclical pattern. Third, examining the standard deviations of goals and pledged contributions by outcome category surfaces an intriguing anomaly: in every outcome except successful campaigns, the standard deviation of goals exceeds that of pledged contributions. For successful campaigns, the relationship reverses. Moreover, the standard deviation of campaign goals is notably lower for successful campaigns than for all other outcomes — a departure that warrants further investigation and may reflect more disciplined goal-setting among campaigns that ultimately succeed.

**Conclusions**

This analysis yields three principal conclusions:

- **Popularity does not predict success.** The most active crowdfunding categories by campaign volume are not the most likely to succeed. Creators should not interpret a crowded category as validation of strong success prospects.

- **Timing matters.** Monthly success rates follow a discernible seasonal pattern. Campaigns launched in strategic windows — particularly the summer plateau period — may benefit from more favorable conditions.

- **Successful campaigns are more variable than unsuccessful ones.** The backer distributions for successful campaigns are broadly dispersed, while those for unsuccessful campaigns are tightly clustered near zero. Both distributions are heavily skewed, making the median a far more appropriate summary statistic than the mean — a distinction this dataset, regrettably, does not honor.

**Limitations and Recommendations**

The utility of this analysis is constrained by two structural weaknesses: the inappropriate use of averages in place of medians, and insufficient sample sizes in several key categories. Together, these factors introduce uncertainty into the findings and limit their generalizability.

Future analyses should address these shortcomings directly. A dataset one to two orders of magnitude larger would provide the statistical depth needed to support more robust conclusions. All central tendency calculations should employ medians rather than means, given the skewed nature of the underlying distributions. With those adjustments in place, the analytical framework developed here could yield significantly more reliable and actionable insights.

----

## Copyright

Nicholas J. George © 2023. All Rights Reserved.
