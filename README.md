![crowdfunding_goal_analysis1](https://github.com/njgeorge000158/Crowdfunding-Goal-Analysis-in-Excel/assets/137228821/748d13b8-fe17-4c3d-9f87-987078ea9a33)

----

# **Crowdfunding Campaign Analysis: *Trends, Insights, and Limitations***

----

## **Background**

---

Crowdfunding has emerged since the late 2000s as a widely adopted mechanism for product launches, idea validation, and public mobilization. Despite its growth and prominence, the determinants of campaign success are not fully understood. This report analyzes a sample of 1,000 campaigns drawn from a standardized dataset with outcomes examined across five dimensions: category, timing, goal range, geographic market, and backer distribution.

---

## Overall Outcomes

---

Of the 1,000 campaigns in the sample, 565 succeed, 364 fail, 57 are canceled, and 14 are live. The combined failure and cancellation rate of 42.1% is a reminder that crowdfunding is far from a dependable funding mechanism for the typical creator. Moreover, throughout this report, the overall success rate of 56.5% provides the analytical baseline for assessing category-level, temporal, and structural variation.

---

## **Category Performance: Popularity vs. Success**

---

| Primary Category | Campaigns | Success Rate | Failure Rate | Canceled Rate | Live Rate |
|------------------|:---------:|:------------:|:------------:|:-------------:|:---------:|
| Technology       | 96        | 66.7%        | 29.2%        | 2.1%          | 2.0%      |
| Photography      | 42        | 61.9%        | 26.2%        | 9.5%          | 2.4%      |
| Publishing       | 67        | 59.7%        | 35.8%        | 3.0%          | 1.5%      |
| Film & Video     | 178       | 57.3%        | 33.7%        | 6.2%          | 2.8%      |
| Music            | 175       | 56.6%        | 37.7%        | 5.7%          | 0.0%      |
| Theater          | 344       | 54.4%        | 38.4%        | 6.7%          | 0.6%      |
| Food             | 46        | 47.8%        | 43.5%        | 8.7%          | 0.0%      |
| Games            | 48        | 43.8%        | 47.9%        | 2.1%          | 6.2%      |
| Journalism       | n/a †     | n/a †        | n/a †        | n/a †         | n/a †     | 
| **Grand Total**  | **996**   | **56.3%**    | **36.5%**    | **5.7%**      | **1.4%**  | 

*† Journalism contains only 4 campaigns — too small a sample to draw reliable conclusions.*

---

Across both primary and subcategory levels, the divergence between campaign volume and success rate is among the most important. Technology, Photography, and Publishing lead in success rates at the primary category level but do not rank as the top three categories by volume. That distinction belongs to Theater, Film & Video, and Music, which succeed at or below the overall average while collectively accounting for nearly 70% of all campaigns.

The subcategory success rates generally support this picture. The highest-performing subcategories — Web within Technology, Translations within Publishing, Television within Film and Video, and Wearables within Technology — predominantly come from primary categories that place towards the top of the success rate distribution, implying that primary category selection carries predictive weight at the subcategory level as well.

An exception to this pattern of inheritance is the Television subcategory. Specifically, Television outperforms its parent category, Film and Video, by 7.4 percentage points, despite its parent's mid-range ranking for success. This anomaly suggests that subcategory positioning is not only a result of primary category membership but also specific factors related to its competitive dynamics, audience, and project type. Accordingly, Television's high performance may signify clearer audience targeting, stronger backer familiarity, or reduced competition. Simply stated, the subcategory outcomes support a two-level view of category selection where the primary category establishes a baseline expectation for success, and subcategory choice either strengthens or revises that prospect.

Altogether, these findings offer a preventative implication for campaign creators: high activity is not proof of favorable conditions. In fact, the most populated categories are systematically associated with lower success rates, meaning that volume and success rate tend to move in opposite directions. Consequently, category selection based on observed volume may be counterproductive, directing creators towards the most competitive fields rather than the most viable ones.

---

## **Funding Rates: All Campaigns vs. Successful Ones**

---

| Category          | Successful | Canceled | Failed   | Live     | Grand Total |
|-------------------|:----------:|:--------:|:--------:|:--------:|:-----------:|
| **FILM & VIDEO**  | **2.07**   | **0.39** | **0.52** | **0.58** | **1.23**    |
| animation         | 1.93       | 0.35     | 0.46     | 0.75     | 1.39        |
| documentary       | 2.03       | 0.67     | 0.54     | 0.21     | 1.26        |
| drama             | 1.82       | 0.11     | 0.57     | 0.56     | 1.40        |
| science fiction   | 1.99       |          | 0.45     |          | 0.58        |
| shorts            | 3.29       | 0.24     | 0.88     | 0.58     | 1.78        |
| television        | 1.89       | 0.39     | 0.59     |          | 1.56        |
| **FOOD**          | **3.29**   | **0.60** | **0.59** |          | **0.97**    |
| food trucks       | 3.29       | 0.60     | 0.59     |          | 0.97        |
| **GAMES**         | **2.39**   | **0.27** | **0.50** | **0.36** | **0.96**    |
| mobile games      | 1.81       |          | 0.44     | 0.36     | 0.55        |
| video games       | 3.10       | 0.27     | 0.50     | 0.59     | 0.97        |
| **JOURNALISM**    | **n/a †**  |          |          |          | **n/a †**   |
| audio             | n/a †      |          |          |          | n/a †       |
| **MUSIC**         | **2.08**   | **0.38** | **0.45** |          | **1.23**    |
| electric music    | 2.09       |          | 0.41     |          | 1.46        |
| indie rock        | 1.76       | 0.11     | 0.57     |          | 1.04        |
| jazz              | 3.46       | 0.19     | 0.19     |          | 1.77        |
| metal             | 3.16       |          | 0.37     |          | 1.22        |
| rock              | 2.13       | 0.57     | 0.45     |          | 1.25        |
| world music       | 1.76       |          |          |          | 1.76        |
| **PHOTOGRAPHY**   | **2.55**   | **0.60** | **0.36** | **0.01** | **1.44**    |
| photography books | 2.55       | 0.60     | 0.36     | 0.01     | 1.44        |
| **PUBLISHING**    | **2.28**   | **0.36** | **0.42** | **0.02** | **1.26**    |
| fiction           | 1.50       | 0.39     | 0.64     |          | 1.10        |
| nonfiction        | 2.32       | 0.33     | 0.41     | 0.02     | 1.46        |
| radio & podcasts  | 1.74       |          | 0.33     |          | 1.01        |
| translations      | 2.41       |          | 0.41     |          | 1.58        |
| **TECHNOLOGY**    | **1.99**   | **0.64** | **0.62** | **0.61** | **1.32**    |
| wearables         | 2.21       |          | 0.59     | 0.59     | 1.44        |
| web               | 1.88       | 0.64     | 0.63     | 0.62     | 1.28        |
| **THEATER**       | **2.02**   | **0.48** | **0.51** | **0.31** | **1.13**    |
| plays             | 2.02       | 0.48     | 0.51     | 0.31     | 1.13        |
| **GRAND TOTAL**   | **2.12**   | **0.43** | **0.51** | **0.50** | **1.22**    |

*† Journalism contains only 4 campaigns — too small a sample to draw reliable conclusions.*

---

Across all 1,000 campaigns, the median funding ratio — pledged contributions as a proportion of the stated goal — is 1.22x indicating that the typical campaign raises about 22% more than its target. The arithmetic mean funding ratio of 2.00x deviates from this figure, inflated by a small number of outlying campaigns whose unusually high funding ratios distort the average far beyond what is illustrative of the broader distribution. This degree of divergence between mean and median reflects a sufficiently skewed distribution that renders the mean unreliable as a measure of central tendency.

In addition, successful campaigns produce a materially higher median funding ratio of 2.12x demonstrating that successful campaigns normally raise slightly over twice their goals. Among primary categories, Food and Photography record the highest median ratios followed by Games and Publishing. Technology is an outlier with the lowest median ratio despite possessing the highest primary category success rate. Thus, Technology campaigns set precise goals relative to audience capacity clearing targets efficiently rather than generating excessive surplus.

The overfunding effect is most obvious at the subcategory level within niche music genres. Successful Jazz and Metal campaigns post significantly high median ratios of 3.46x and 3.16x respectively. These outcomes are consistent with tightly defined, highly engaged audience communities committing disproportionally large resources. That’s why, modest community-calibrated goals paired with strong audience engagement may generate higher median funding ratios than broader campaigns targeting greater but less cohesive markets.

---

## Goal Size and Success

---

| Goal Range          | Campaigns | Success Rate | Failure Rate  | Canceled Rate | Live Rate |
|---------------------|:---------:|:------------:|:-------------:|:-------------:|:---------:|
| Under 5,000         | 285       | 77.5%        | 20.4%         | 1.1%          | 1.0%      |
| 5,000 – 10,000      | 317       | 51.7%        | 39.7%         | 7.9%          | 0.7%      |
| 10,000 – 15,000     | n/a †     | n/a †        | n/a †         | n/a †         | n/a †     |
| 15,000 – 35,000     | 38        | 92.1%        | 7.9%          | 0.0%          | 0.0%      |
| 35,000 – 100,000    | 159       | 61.0%        | 32.7%         | 4.4%          | 1.9%      |
| Over 100,000        | 192       | 22.9%        | 62.5%         | 11.5%         | 3.1%      |
| **Grand Total**     | **991**   | **62.5%**    | **22.9%**     | **11.5%**     | **3.1%**  |

*† 10,000 – 15,000 contains only 9 campaigns —  too small a sample to draw reliable conclusions.*

---

Goal size is a strong structural predictor of campaign outcome in this dataset. The relationship between goal level and success rate is non-linear where rates increase at low levels, compress through the mid-range, and collapse at the high end. Campaigns with goals above 100,000 succeed at 22.9%, substantially below the 56.5% overall average and roughly one-third the rate for campaigns under 5,000. The 15,000–35,000 band is an exception at 92.1% but should be regarded cautiously given its comparatively small size of only 38 campaigns.

Successful campaigns maintain a median goal of 6,200 compared to 9,900 for failed campaigns and 36,400 for canceled ones — a monotonically increasing gradient across outcome groups that, given its magnitude and stability, is difficult to attribute to sampling variation. Instead, the pattern is reasonably understood as evidence that goal discipline is a structural antecedent of success rather than a subsequent characteristic of it. Thus, creators whose goals are calibrated to the realistic capacity of their target audience appear more likely to reach them; conversely, those campaigns whose goals exceed that capacity appear more likely to fall short or withdraw entirely.

---

## Timing: Day-of-Week, Month, and Year

---

### Day-of-Week Trends

---

| Day of Week     | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|-----------------|:---------:|:------------:|:------------:|:-------------:|
| Sunday          | 133       | 58.6%        | 35.3%        | 6.0%          |
| Monday          | 152       | 65.8%        | 30.3%        | 3.9%          |
| Tuesday         | 149       | 56.4%        | 38.9%        | 4.7%          |
| Wednesday       | 136       | 55.9%        | 37.5%        | 6.6%          |
| Thursday        | 142       | 54.9%        | 37.3%        | 7.7%          |
| Friday          | 147       | 51.0%        | 43.5%        | 5.4%          |
| Saturday        | 127       | 58.3%        | 35.4%        | 6.3%          |
| **Grand Total** | **986**   | **57.3%**    | **36.9%**    | **5.8%**      |

---

Day-of-week launch timing produces a distinguishable but irregular pattern best described as a three-tier system rather than a continuous gradient. Monday returns the highest success rate at 65.8%, and Friday, the distribution's clearest outlier, records the lowest at 51.0%. Sunday and Saturday occupy intermediate positions modestly above the overall average of 57.3% while Tuesday, Wednesday, and Thursday cluster between 54.9% and 56.4%. 

The implications of these findings vary extensively. With only 127 to 152 campaigns per weekday, the confidence intervals of these samples are adequately wide, and the range of success rates sufficiently compressed, to treat midweek differences as statistical noise. Nevertheless, the Monday-Friday differential of 14.8 percentage points is directionally plausible under reasonable sampling variability assumptions although the intermediate tiers are suggestive rather than definitive. In short, creators with discretion over launch timing should prefer Mondays, avoid Fridays, and treat the intervening days as effectively interchangeable.

---

### Monthly Trends

---

| Month           | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|-----------------|:---------:|:------------:|:------------:|:-------------:|
| January         | 91        | 53.8%        | 39.6%        | 6.6%          |
| February        | 79        | 55.7%        | 35.4%        | 8.9%          |
| March           | 86        | 57.0%        | 38.4%        | 4.7%          |
| April           | 77        | 59.7%        | 39.0%        | 1.3%          |
| May             | 84        | 54.8%        | 41.7%        | 3.6%          |
| June            | 86        | 64.0%        | 32.6%        | 3.5%          |
| July            | 93        | 62.4%        | 33.3%        | 4.3%          |
| August          | 84        | 48.8%        | 41.7%        | 9.5%          |
| September       | 73        | 61.6%        | 31.5%        | 6.8%          |
| October         | 77        | 58.4%        | 33.8%        | 7.8%          |
| November        | 75        | 60.0%        | 36.0%        | 4.0%          |
| December        | 81        | 51.9%        | 39.5%        | 8.6%          |
| **Grand Total** | **986**   | **57.3%**    | **36.9%**    | **5.8%**      |

---

Monthly success rates exhibit an expansive seasonal pattern interspersed with two incongruities. Those rates rise from 53.8% in January to 64.0% in June, remain elevated through September, and decline thereafter — a trajectory of robust backer engagement through the mid-year period that diminishes towards year-end. Conversely, despite its position within the flourishing mid-year window, August posts the lowest rate across the calendar year and a decline of 13.6 percentage points. Also, interrupting a steady increase from January to June, May drops 4.9 percentage points without a comparable departure in the preceding or following months from the predominant trend.

The August deviation is most likely caused by the contraction in discretionary attention and spending that characterizes the late summer holiday period — a behavioral pattern that suppresses backer engagement independent of campaign quality or category composition. On the other hand, the May aberration is less easily explained by any identifiable structural or behavioral mechanism. With only 77 to 91 campaigns per month, the confidence intervals surrounding individual monthly estimates are sufficiently wide to associate this deviation with sampling variation, which also exists in the day-of-week analysis. In the absence of a replicable pattern across a larger dataset, the May decline is more appropriately characterized as a sampling artifact than as evidence of a legitimate seasonal effect.

As a final point, the monthly success analysis identifies a mid-year window of relative strength and two periods of relative weakness. Uniformly above the 57.3% overall average, June, July, and September record success rates between 61.6% and 64.0%. At the other extreme, August and December post the two lowest rates at 48.8% and 51.9% respectively. In other words, these outcomes depict the mid-year window as the most favorable environment and the late summer and year-end periods as the least.

---

### Year-on-Year Trends

---

| Year            | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|-----------------|:---------:|:------------:|:------------:|:-------------:|
| 2010            | 107       | 54.2%        | 32.7%        | 13.1%         |
| 2011            | 102       | 54.9%        | 39.2%        | 5.9%          |
| 2012            | 81        | 55.6%        | 39.5%        | 4.9%          |
| 2013            | 87        | 55.2%        | 40.2%        | 4.6%          |
| 2014            | 101       | 59.4%        | 36.6%        | 4.0%          |
| 2015            | 103       | 52.4%        | 40.8%        | 6.8%          |
| 2016            | 96        | 51.0%        | 43.8%        | 5.2%          |
| 2017            | 100       | 67.0%        | 28.0%        | 5.0%          |
| 2018            | 100       | 61.0%        | 35.0%        | 4.0%          |
| 2019            | 107       | 62.6%        | 33.6%        | 3.7%          |
| 2020            | n/a †     | n/a †        | n/a †        | n/a †         |
| **Grand Total** | **984**   | **57.4%**    | **36.8%**    | **5.8%**      |

*† 2020 contains only 2 campaigns —  too small a sample to draw reliable conclusions.*

---

The annual success rates displayed oscillatory rather than directional variation implying that underlying success dynamics neither methodically improved from platform maturation nor deteriorated from intensified competition. Ranging from 51.0% to 67.0%, success rates in the 2010–2019 period varied little during 2010-2014, reached their lowest levels during 2015–2016, and achieved their highest during 2017–2019. For 2020, the report considers the small subsample of two failed campaigns as statistically irrelevant and excludes it from the analysis.

The most defensible inference from these observations is that annual success rates are relatively stable across the decade with year-to-year variation likely due to external factors such as shifting campaign composition, changing backer behavior, and broader economic conditions. As such, the data supports a stable long-run mean model in which annual variation represents transient deviation rather than directional change. However, with annual subsamples from 81 to 107 campaigns, the resolution of the year-on-year analysis is sufficient to identify broad shifts but insufficient to detect gradual changes accurately. Thus, a tenable multi-year analysis would require, at minimum, observations an order of magnitude greater than those available here.

---

## Geographic Patterns

---

| Country         | Currency | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|-----------------|:--------:|:---------:|:------------:|:------------:|:-------------:|
| Australia       | AUD      | 42        | 57.1%        | 38.1%        | 4.8%          |
| Canada          | CAD      | 43        | 51.2%        | 44.2%        | 4.7%          |
| Switzerland     | CHF      | 22        | 54.5%        | 27.3%        | 18.2%         |
| Denmark         | DKK      | 30        | 56.7%        | 40.0%        | 3.3%          |
| Great Britain   | GBP      | 47        | 59.6%        | 38.3%        | 2.1%          |
| Italy           | EUR      | 48        | 54.2%        | 39.6%        | 6.3%          |
| United States   | USD      | 754       | 57.8%        | 36.3%        | 5.8%          |
| **Grand Total** | n/a      | **986**   | **57.3%**    | **36.9%**    | **5.8%**      |

---

The dataset's geographic distribution is heavily skewed in favor of the United States, which contributes 754 out of 986 campaigns with no other country accounting for more than 48. The remaining 232 observations are spread across six countries: Great Britain, Italy, Canada, Australia, Denmark, and Switzerland. Moreover, the cross-country success rates exhibit modest variation ranging from 51.2% for Canada to 59.6% for Great Britain. As in other analyses, the confidence intervals surrounding individual country estimates are sufficiently wide to render cross-country differences statistically indistinguishable from sampling variation. Consequently, findings based on the US subsample carry reasonable statistical weight while those based on any non-US countries rest on subsamples too small to support a convincing inference without significant qualification.

What's more, the dataset posts goals and pledged amounts using seven currencies without normalization to a common monetary unit. Without exchange rate conversions, comparisons of cross-country funding amounts are suspect because observed differences may stem from currency denomination rather than actual variation in goal-setting behavior or backer generosity. Therefore, cross-country funding comparisons should be interpreted cautiously, and any conclusions treated as tentative.

---

## Backer Distributions

---

| Outcome    | Median Backers | Mean Backers | Std Dev |
|------------|:--------------:|:------------:|:-------:|
| Successful | 201            | 851          | 1,267   |
| Failed     | 115            | 586          | 961     |
| Canceled   | 139            | 435          | 574     |
| Live       | 149            | 584          | 968     |

---

The backer count distribution displays a positive skew of appropriate magnitude to produce tangible divergence between mean and median across all outcome groups. The disparity is most pronounced for successful campaigns — a median of 201 compared to a mean of 851, an over fourfold difference attributable to a small number of high-visibility campaigns with unusually high backer counts. In effect, these unusual campaigns overstate backer mobilization by weighting the influence of outliers over the representative campaign experience.

Beyond the mean-median deviation, the backer count distribution manifests a secondary pattern of analytical interest. Usually, failed and canceled campaigns have low backer counts and a constrained range of backers, which demonstrates an inability to mobilize necessary audience support. In contrast, successful campaigns reveal a noticeably different distributional profile with high backer counts spanning a full range from modest community support to large-scale viral mobilization. Thus, the findings suppose an idiosyncrasy of relatively homogeneous failure and heterogeneous success. 

---

## Standard Deviation: Goals vs. Pledges by Outcome

---

| Outcome    | Std Dev of Goal | Std Dev of Pledged |
|------------|:---------------:|:------------------:|
| Successful | 40,734          | 64,552             |
| Failed     | 69,884          | 45,775             |
| Canceled   | 70,557          | 35,632             |
| Live       | 76,831          | 52,170             |

---

An examination of goal and pledged amount standard deviations across outcome groups reveals a structural regularity. For failed, canceled, and live campaigns, goals vary more than pledged amounts, suggesting that targets are often set without consideration of realistic audience capacity. In these groups, creators set a wide range of goals while audience responses cluster within a narrow band, producing systematically higher variance in goals than in pledges.

Conversely, successful campaigns display the opposite relationship where the standard deviation of pledged amounts exceeds that of goals. There are two mechanisms that account for this phenomenon. First, successful campaigns have the lowest standard deviation of goal among all outcome groups suggesting a more disciplined approach to setting targets. Second, pledged amounts for successful campaigns are structurally unbounded. Specifically, after the total pledged amount clears the target, contributions continue to accumulate beyond it, generating a distribution in which audience enthusiasm rather than campaign design establishes the upper range. This combination of compressed goal variance and unbounded pledge variance produces the observed reversal and distinguishes the distributional profile of successful campaigns.

Overall, high goal variance and low pledge variance define failed and canceled campaigns while low goal variance and high pledge variance characterize successful campaigns. Accordingly, goal discipline functions as an antecedent of success rather than a correlate, a condition that precedes and enables favorable outcomes rather than simply accompanying them.

---

## Platform Promotion: Staff Pick and Spotlight

---

| Promotion Status  | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|-------------------|:---------:|:------------:|:------------:|:-------------:|
| Neither           | 699       | 57.2%        | 35.5%        | 5.7%          |
| Spotlight Only    | 252       | 54.4%        | 39.3%        | 5.2%          |
| Staff Pick Only   | 33        | 54.5%        | 39.4%        | 6.1%          |
| Both Endorsements | 16        | 62.5%        | 25.0%        | 12.5%         |

---

The dataset includes two binary promotion flags, staff pick and spotlight, whose individual effects on campaign outcomes do not support the hypothesis that platform endorsement improves success rates. Campaigns carrying a spotlight designation alone have a success rate of 54.4%; those carrying a staff pick alone record 54.5%; and both figures fall below the 57.2% success rate for campaigns with neither endorsement. This observation represents the counterintuitive idea that platform promotion appears to be associated with marginally lower rather than higher success rates.

This pattern reverses for campaigns carrying both endorsements with a success rate 5.3 percentage points above the unpromoted baseline and a failure rate 10.5 percentage points below it. Of course, both figures convey a positive combined endorsement effect, but the both-endorsement subsample has only 16 campaigns — a figure insufficient to support reliable statistical inference. Also, as in previous analyses, the corresponding confidence interval is wide enough to associate this difference with sampling variation rather than a bona fide causal relationship.

In conclusion, crowdfunding platforms have the operational capacity and the institutional incentive to award promotional status to campaigns already demonstrating strong performance indicators — early backer momentum, pledge velocity, presentation quality — instead of distributing endorsements to improve outcomes. Under this interpretation, the higher success rate among doubly endorsed campaigns stems from the platform's backing of high-quality campaigns rather than any causal effect. In other words, the endorsements function as a signal of underlying quality rather than a source of it, and the observed growth in success rates should be ascribed accordingly.

---

## Campaign Duration

---

| Duration (days) | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|-----------------|:---------:|:------------:|:------------:|:-------------:|
| 0-9             | 437       | 57.2%        | 37.3%        | 5.5%          |
| 10-19           | 245       | 58.4%        | 35.1%        | 6.5%          |
| 20-29           | 155       | 54.8%        | 37.4%        | 7.7%          |
| 30-39           | 76        | 61.8%        | 35.5%        | 2.6%          |
| 40-49           | 51        | 62.7%        | 35.3%        | 2.0%          |
| 50-59           | 22        | 36.4%        | 54.5%        | 9.1%          |
| **Grand Total** | **986**   | **57.3%**    | **36.9%**    | **5.8%**      |

---

Campaign duration is not statistically linked to outcome in this dataset. The median duration is identical across successful and failed campaigns at 12 days, and the Spearman correlation between duration and percent funded is negligible at −0.02, contradicting the idea that longer campaign windows improve funding prospects.

The duration brackets broadly reflect this situation although with two noteworthy exceptions at the extreme. The 40–49 day bracket posts the highest success rate but has only 51 campaigns, too low to support statistical inference. Also, the 50–59 day bracket has the lowest success rate, 20% below the overall average, while its failure rate is the highest. Thus, creators with the longest campaigns most likely extended their windows in response to poor early traction skewing the reason for failure towards underperformance instead of long duration.

There is little support for treating campaign duration as an option for improving outcomes. The time on platform does not compensate for weak underlying demand, and creators with poor early performance who extend their campaign windows are unlikely to alter that trajectory. Ultimately, duration is not a legitimate predictor of success and should not be treated as a viable strategic variable.

---

## Conclusions

---

**Category popularity is not positively associated with campaign success**. In fact, one of the clearest patterns in the dataset is that category volume and success rate move in opposite directions. Theater, Music, and Film & Video account for nearly 70% of campaigns, yet their success rates sit at or below the overall average. By contrast, Technology and Photography represent a much smaller share of campaign volume but have considerably higher success. Therefore, high activity comes from competitive intensity rather than favorable conditions, and creators who treat category volume as a proxy for viability may be misdirecting their efforts towards the most crowded fields instead of the most promising ones.

**Goal size** is consistently one of the strongest predictors of campaign outcome. From a distributional perspective, campaigns seeking more than 100,000 succeed only 22.9% of the time, compared with 77.8% for campaigns under 5,000, a differential of 54.9 percentage points across the goal spectrum. Measures of central tendency point in the same direction: the median goal for successful campaigns is 6,200, versus 9,900 for failed campaigns and 36,400 for canceled campaigns. Hence, this monotonic gradient is unlikely to be sampling noise and is most reasonably regarded as an authentic structural association between high goal discipline and campaign success.

**Timing** is a practical option for campaign optimization. Seasonally, June, July, and September are the most favorable launch windows with success rates consistently above the overall average. By day of week, Monday is the best performer with a success rate 13.4 percentage points above the worst, Friday. Altogether, these observations identify a set of optimal timing preferences: launch mid-year, start on a Monday, and avoid late summer and year-end windows.

**Backer volume** is the clearest quantitative predictor of funding success in this analysis. The Spearman correlation between backer count and total pledged amount is 0.94, indicating that variation in funding outcomes is driven more by the number of campaign supporters than by the size of individual contributions. In other words, campaigns tend to succeed by mobilizing a large audience, not by relying on unusually generous backers. As a result, creators should focus their time and resources on expanding reach and building early engagement instead of trying to increase average contribution size.

In closing, multiple independent indicators point to the conclusion that successful campaigns differ from unsuccessful ones in systematic ways that display deliberate calibration rather than favorable circumstances. They use stronger audience assessment during planning to set lower, less variable goals and attract more backers as demonstrated by higher median backer counts and a strong correlation between backer count and total pledged. Thus, pre-launch choices such as understanding the audience, setting a realistic goal, and appropriately scoping ambition, rather than by post-launch fortune, drive successful campaigns.

---

## Limitations and Recommendations

---

Three structural features of the dataset limit how broadly this report's findings can be generalized. Although these constraints do not undercut the report’s overall conclusions, they do diminish the inferential strength of observations from small subsamples. Accordingly, conclusions drawn from findings that extend beyond broad patterns should be viewed with caution.

**Sample size.** The 1,000-campaign dataset is sufficient to identify general patterns and aggregate relationships but insufficient to support reliable subgroup inference in several parts of the analysis. High-goal tiers, non-US country samples, and less common subcategories each contain fewer than 50 observations, a range in which estimates become unstable and confidence intervals widen enough to allow materially different interpretations. Consequently, findings based on the full sample or on larger subgroups carry reasonable evidentiary weight whereas results drawn from small subsamples should be treated as provisional. In the future, expanding the dataset by one to two orders of magnitude would substantially reduce these limitations and allow the same analytical framework to be applied with much greater confidence.

**Currency heterogeneity.** The goals and pledged amounts are denominated in seven currencies (CAD, GBP, EUR, AUD, DKK, CHF, and USD), rendering raw cross-country comparisons of funding amounts as ambiguous. Because of the differences in these several currencies, an external exchange-rate data source would need to be referenced to resolve the distortion. Thus, cross-country comparisons of goals or pledged amounts should be treated as unreliable until those currencies have been normalized to a common monetary unit.

**Causal inference.** The findings in this report are observational and associational, not causal. The analytical methods used here cannot separate causal effects from the confounding influences inherent in the observations, so reported relationships should not be considered as proof of causation. For example, the day-of-week pattern may reflect differences in the kinds of campaigns launched on different days rather than an effect of timing itself. The goal-outcome gradient may be driven by unobserved factors — creator experience, audience development, market knowledge — that shape both goal setting and campaign performance. Indeed, the staff-pick association is better explained by platform selection of already-promising campaigns than by any independent effect of promotion. Ultimately, establishing causal claims would require several absent identification strategies such as randomized assignment, regression discontinuity, difference-in-differences, or instrumental variables.

Each of the three identified limitations has a practical remedy that would substantively strengthen the analysis. The sample size limitation should be addressed by expanding the dataset: annual observation counts in the tens of thousands would reduce uncertainty and support reliable subgroup inference and multi-year trend analysis. The currency heterogeneity limitation requires exchange-rate normalization before any cross-country funding analysis, so all monetary values share a common unit. The causal inference limitation is more demanding methodologically and involves quasi-experimental designs capable of separating causal effects from confounding influences. Altogether, these improvements would move the report beyond description toward explanation, yielding conclusions that are not only accurate summaries of past patterns but also reliable guides to improving campaign outcomes.

----

## Copyright

Nicholas J. George © 2026. All Rights Reserved.
