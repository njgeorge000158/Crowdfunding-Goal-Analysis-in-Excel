![crowdfunding_goal_analysis1](https://github.com/njgeorge000158/Crowdfunding-Goal-Analysis-in-Excel/assets/137228821/748d13b8-fe17-4c3d-9f87-987078ea9a33)

----

# **Crowdfunding Campaign Analysis: *Trends, Insights, and Limitations***

----

## **Background and Approach**

Since the late 2000s, crowdfunding has grown into a widely adopted mechanism for launching products, validating ideas, and mobilizing public support. To better understand the factors driving campaign success, this report analyzes a sample of 1,000 crowdfunding campaigns drawn from a standardized dataset. The analysis uses spreadsheet-based tools and covers outcomes across categories, timing, goal ranges, geographic markets, and backer distributions. Where the data permits, results are presented using medians rather than means, given the heavily skewed nature of most distributions.  

## Overall Outcomes

Of the 1,000 campaigns in the sample, 565 (56.5%) were successful, 364 (36.4%) failed, 57 (5.7%) were canceled, and 14 (1.4%) remained live. The overall success rate provides the baseline against which the report evaluates category, timing, and structural factors.


## **Category Performance: Popularity vs. Success**

---

| Primary Category | Campaigns | Success Rate |
|------------------|:---------:|:------------:|
| Technology       | 96        | 66.7%        |
| Photography      | 42        | 61.9%        |
| Publishing       | 67        | 59.7%        |
| Film & Video     | 178       | 57.3%        |
| Music            | 175       | 56.6%        |
| Theater          | 344       | 54.4%        |
| Food             | 46        | 47.8%        |
| Games            | 48        | 43.8%        |
| Journalism       | 4         | 100% †       |

*† Journalism contains only 4 campaigns — too small a sample to draw reliable conclusions.*

---

One of the clearest patterns in the data is the divergence between campaign volume and success rate. At the primary category level, Technology, Photography, and Publishing are the most successful categories, yet Theater, Film & Video, and Music are all near or below the average (56.0%) despite being the three most popular categories by volume and accounting for nearly 70% of all campaigns. In the sub-categories, the highest-performing segments are Web / Technology (70.6%), Translations / Publishing (66.7%), Television / Film & Video (64.7%), and Wearables / Technology (62.2%). Naturally, the subcategories also follow the same trend with a few exceptions. Thus, creators should not interpret a crowded category or subcategory as a signal of strong success prospects.

## **Funding Rates: All Campaigns vs. Successful Ones**

Across all 1,000 campaigns, the median funding ratio — pledged contributions as a proportion of the stated goal — is 1.22x (i.e., campaigns raise about 22% more than their median goal), which, due to a small number of exceptionally over-funded campaigns, is substantially lower than the mean funding ratio, 2.00x. The significant divergence between mean and median endorses the median as the preferred method for measuring central tendency.

The picture shifts considerably when the analysis is restricted to successful campaigns alone, increasing its median to 2.12x. Food (3.29x) and Photography (2.55x) lead among primary categories, followed by Games (2.39x) and Publishing (2.28x). Technology, despite its high success rate, has the lowest median funding ratio among successful campaigns (2.00x), suggesting that technology campaigns tend to hit their targets more precisely rather than dramatically exceeding them. 

At the sub-category level, the over-funding effect is particularly pronounced in niche music genres. Successful Metal campaigns reach a median of 4.4x their goal and successful Jazz campaigns reach 3.5x, indicating that highly engaged niche audiences can drive exceptional outcomes.

## Goal Size and Success

Goal size is among the strongest structural predictors of campaign outcome. The data reveal a non-linear relationship: success rates are high at both low and moderate goal levels, but drop sharply at high goals.

| Goal Range          | Campaigns | Success Rate |
|---------------------|:---------:|:------------:|
| Under $5,000        | 293       | 77.8%        |
| $5,000 – $10,000    | 316       | 50.3%        |
| $10,000 – $15,000   | 2         | n/a †        |
| $15,000 – $35,000   | 39        | 92.3%        |
| $35,000 – $100,000  | 158       | 60.8%        |
| Over $100,000       | 192       | 22.9%        |

*† Only 2 campaigns in this range — insufficient for a reliable estimate.*

The most striking finding is at the extremes. Campaigns with goals above $100,000 succeed at just **22.9%** — well below the overall average and roughly one-third the rate of campaigns under $5,000. The high success rate in the $15,000–$35,000 band should be interpreted cautiously given the small sample (39 campaigns).

Consistent with this pattern, the median goal for successful campaigns ($6,200) is markedly lower than for failed campaigns ($9,900) and dramatically lower than for canceled campaigns ($36,400). **More disciplined, realistic goal-setting appears to be a characteristic of campaigns that succeed**, rather than simply a byproduct of it.

## **Timing and Monthly Trends**

A raw view of the Months by Outcomes worksheet offered little immediate insight, as absolute counts are difficult to interpret without normalization. Converting these figures into monthly success rates — in a dedicated Months by Outcomes (%) worksheet — revealed a clearer pattern. Success rates range from 49% to 64% across the calendar year, rising steadily from January through June, plateauing through September, then declining into year-end. Two notable exceptions disrupt this trend: success rates drop sharply in May and August, falling 5% and 13% from their respective prior months. These anomalies notwithstanding, the broader seasonal pattern suggests that campaign timing is a meaningful lever — one that creators can strategically exploit to improve their odds of success.

## **Goal Ranges and Sample Size Constraints**

The Campaign Summary worksheet examines success rates across ranges of campaign goals. The line chart shows success rates increasing as goals rise from $0 to $15,000, leveling off between $15,000 and $34,999, and declining from $35,000 onward. However, this pattern must be interpreted with caution. The three lowest goal ranges account for the vast majority of campaigns — two categories contain hundreds of projects each, and one contains roughly fifty — while every category at or above $10,000 comprises fewer than 15 campaigns. These thin sample sizes at higher goal thresholds render the observed trends statistically unreliable. This data sparsity problem is not isolated to the Campaign Summary; it recurs elsewhere in the dataset and meaningfully constrains the conclusions that can be drawn.

## **Statistical Distributions and the Case for the Median**

The Statistical Analysis (Goals) worksheet presents distributions of backer counts for successful and unsuccessful campaigns. Both distributions exhibit wide ranges between minimum and maximum values, large variances, and substantial divergence between mean and median values. When the mean and median diverge as significantly as they do here, it signals that outliers are distorting the average, pulling it away from the typical value. In such cases, the median is the more appropriate and informative measure of central tendency. Unfortunately, the existing calculations rely on averages throughout — a methodological choice that undermines the accuracy of the reported figures.

Beyond the measure-of-center issue, the variance analysis reveals an asymmetry between outcomes: successful campaigns exhibit considerably greater variance in backer counts than unsuccessful ones. This makes intuitive sense. Unsuccessful campaigns tend to attract few or no backers, clustering the distribution near zero. Successful campaigns, by contrast, draw backers across a wide spectrum — from modest community support to viral audience mobilization — producing a far more dispersed distribution.

## **Additional Analyses Worth Pursuing**

Three supplementary analyses could meaningfully deepen this investigation. First, a table comparing countries against the percentage of successful campaigns would reveal whether geography is a determinant of crowdfunding success. Second, charting the percentage of successful campaigns by year would clarify whether the phenomenon is growing, plateauing, or following a cyclical pattern. Third, examining the standard deviations of goals and pledged contributions by outcome category surfaces an intriguing anomaly: in every outcome except successful campaigns, the standard deviation of goals exceeds that of pledged contributions. For successful campaigns, the relationship reverses. Moreover, the standard deviation of campaign goals is notably lower for successful campaigns than for all other outcomes — a departure that warrants further investigation and may reflect more disciplined goal-setting among campaigns that ultimately succeed.

## **Conclusions**

This analysis yields three principal conclusions:

- **Popularity does not predict success.** The most active crowdfunding categories by campaign volume are not the most likely to succeed. Creators should not interpret a crowded category as validation of strong success prospects.

- **Timing matters.** Monthly success rates follow a discernible seasonal pattern. Campaigns launched in strategic windows — particularly the summer plateau period — may benefit from more favorable conditions.

- **Successful campaigns are more variable than unsuccessful ones.** The backer distributions for successful campaigns are broadly dispersed, while those for unsuccessful campaigns are tightly clustered near zero. Both distributions are heavily skewed, making the median a far more appropriate summary statistic than the mean — a distinction this dataset, regrettably, does not honor.

## **Limitations and Recommendations**

The utility of this analysis is constrained by two structural weaknesses: the inappropriate use of averages in place of medians, and insufficient sample sizes in several key categories. Together, these factors introduce uncertainty into the findings and limit their generalizability.

Future analyses should address these shortcomings directly. A dataset one to two orders of magnitude larger would provide the statistical depth needed to support more robust conclusions. All central tendency calculations should employ medians rather than means, given the skewed nature of the underlying distributions. With those adjustments in place, the analytical framework developed here could yield significantly more reliable and actionable insights.

----

## Copyright

Nicholas J. George © 2023. All Rights Reserved.
