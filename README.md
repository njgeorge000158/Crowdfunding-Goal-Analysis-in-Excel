![crowdfunding_goal_analysis1](https://github.com/njgeorge000158/Crowdfunding-Goal-Analysis-in-Excel/assets/137228821/748d13b8-fe17-4c3d-9f87-987078ea9a33)

----

# **Crowdfunding Campaign Analysis: *Trends, Insights, and Limitations***

----

## **Background**

Crowdfunding has emerged since the late 2000s as a widely adopted mechanism for product launches, idea validation, and public mobilization. Despite its growth and prominence, the determinants of campaign success are not fully understood. This report analyzes a sample of 1,000 campaigns drawn from a standardized dataset, with outcomes examined across five dimensions: category, timing, goal range, geographic market, and backer distribution.

## Overall Outcomes

Of the 1,000 campaigns in the sample, 565 succeeded (56.5%), 364 failed (36.4%), 57 were canceled (5.7%), and 14 were live (1.4%). The combined failure and cancellation rate of 42.1% is a reminder that crowdfunding is far from a reliable funding mechanism for the typical creator. Furthermore, throughout this report, the overall success rate provides the analytical baseline for assessing category-level, temporal, and structural variation.


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

Among the patterns that emerge consistently across both primary and subcategory levels, the divergence between campaign volume and success rate is among the most practically significant. Technology (66.7%), Photography (61.9%), and Publishing (59.7%) lead at the primary category level but do not rank among the three most popular categories by volume. That distinction belongs to Theater, Film & Video, and Music, which succeed at or below the overall average while together accounting for nearly 70% of all campaigns.

The subcategory results broadly reinforce this picture. The highest-performing subcategories — Web within Technology (70.6%), Translations within Publishing (66.7%), Television within Film and Video (64.7%), and Wearables within Technology (62.2%) — are drawn predominantly from primary categories that already rank towards the top of the success rate distribution, implying that primary category selection carries predictive weight at the subcategory level as well.

The more informative finding is where this inheritance breaks down. Television outperforms its parent category, Film and Video, by 7.4 percentage points despite Film and Video's mid-range standing overall. This divergence indicates that subcategory positioning is not only a reflection of primary category membership but also factors specific to its own competitive dynamics, audience, or project type. Television's outperformance may suggest clearer audience targeting, stronger backer familiarity with the format, or reduced competition. Simply stated, the subcategory data supports a two-level view of category selection in which the primary category establishes a baseline expectation for success, but subcategory choice can either reinforce or revise that expectation.

Collectively, these findings carry a direct and cautionary implication for campaign creators. High activity within a category is not evidence of favorable conditions. The most populated categories are systematically associated with lower success rates, meaning that volume and success rate move in opposite directions across this dataset. Thus, category selection based on observed volume may be counterproductive, directing creators towards the most competitive fields rather than the most viable ones.

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

Across all 1,000 campaigns, the median funding ratio — pledged contributions as a proportion of the stated goal — is 1.22x, indicating that the typical campaign raises about 22% more than its target.  The arithmetic mean of 2.00x deviates from this figure, inflated by a small number of outlying campaigns whose funding ratios are large enough to distort the average well beyond what is representative of the broader distribution.  This degree of divergence between mean and median is not a minor statistical consideration and reflects a sufficiently skewed distribution that renders the mean unreliable as a measure of central tendency.

Restricting the analysis to successful campaigns generates a materially higher median funding ratio of 2.12x, demonstrating that a successful campaign normally raises nearly double its goal.  Among primary categories, Food (3.29x) and Photography (2.55x) record the highest median ratios followed by Games (2.39x) and Publishing (2.28x). Technology is an anomaly with the lowest median funding ratio (1.99x) despite possessing the highest primary category success rate, insinuating that technology campaigns set goals with greater precision relative to audience capacity clearing targets efficiently rather than generating excessive surplus.

The overfunding effect is most pronounced at the subcategory level within niche music genres.  Successful Jazz campaigns post a median funding ratio of 3.46x; successful Metal campaigns post 3.16x; and both figures are substantially above the 2.12x median.  These results are consistent with tightly defined, highly engaged audience communities committing disproportionally large resources to these niche campaigns. Hence, for creators, modest, community-calibrated goals paired with strong audience engagement may generate higher funding ratios than broader campaigns targeting greater but less cohesive markets.

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

Goal size ranks among the strongest structural predictors of campaign outcome in this dataset.  The relationship between goal level and success rate is non-linear where rates increase at low goal levels, compress through the mid-range, and collapse at the high end.  Campaigns with goals above 100,000 succeed at 22.9%, substantially below the 56.5% overall average and roughly one-third the rate for campaigns under 5,000 (77.5%).  The 15,000–35,000 band is an exception at 92.1% but should be interpreted cautiously given its comparatively small size of only 38 campaigns.

The median goal figures reinforce the success rate analysis.  Successful campaigns maintain a median goal of 6,200, compared to 9,900 for failed campaigns and 36,400 for canceled ones — a monotonically increasing gradient across outcome groups that, given its magnitude and consistency, is difficult to attribute to sampling variation.  Instead, the pattern is plausibly understood as proof that goal discipline is a structural antecedent of success rather than a subsequent characteristic of it.  Thus, creators whose goals are calibrated to the realistic capacity of their target audience appear more likely to reach them; conversely, those campaigns whose goals exceed that capacity appear more likely to fall short or withdraw entirely.

## Timing: Monthly and Day-of-Week Patterns

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

Day-of-week launch timing produces a distinguishable but irregular pattern best described as a three-tier structure rather than a continuous gradient. Monday records the highest success rate at 65.8%, and Friday, the distribution's clearest outlier, records the lowest at 51.0%. Sunday (58.6%) and Saturday (58.3%) occupy an intermediate position modestly above the overall average of 57.3%, while Tuesday, Wednesday, and Thursday cluster narrowly between 54.9% and 56.4%. Also, with only 127 to 152 campaigns per weekday, the confidence intervals are sufficiently wide, and the range of success rates sufficiently compressed to treat midweek differences as statistical noise. Nevertheless, the Monday-Friday differential of 14.8 percentage points is large enough to remain directionally credible under reasonable sampling variability assumptions although the tiers between those poles are suggestive rather than definitive. In short, creators with discretion over launch timing should prefer Mondays, avoid Fridays, and treat the intervening days as effectively interchangeable.

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

Monthly success rates exhibit a broad seasonal trend punctuated by two anomalies.  Rates rise from 53.8% in January to 64.0% in June, remain elevated through September, and decline thereafter — a trajectory of strong backer engagement through the mid-year period and reduced engagement towards year-end.  However, two months deviate materially from this pattern.  Despite its position within the prosperous mid-year window, August records a success rate of 48.8%, a decline of 13.6 percentage points from the preceding month and the lowest rate observed across the full calendar year.  Interrupting a spring increase that had progressed steadily from January through April, May records a drop of 4.9 percentage points to 54.8%, without a comparable reversal in the preceding or following months.

The August deviation is consistent with the contraction in discretionary attention and spending that characterizes the late summer holiday period — a behavioral pattern that likely suppresses backer engagement independent of campaign quality or category composition.  On the other hand, the May aberration is less easily explained by any identifiable structural or behavioral mechanism.  Given an average monthly subsample of 82 campaigns, the confidence intervals surrounding individual monthly estimates are sufficiently wide to associate this deviation with sampling variation.  In the absence of a replicable pattern across a larger dataset, the May dip is more appropriately characterized as a sampling artifact than as proof of a legitimate seasonal effect.

The monthly success rate data identifies a mid-year window of relative strength and two periods of relative weakness.  June, July, and September each record success rates between 61.6% and 64.0%, uniformly above the 57.3% overall average.  August and December record the two lowest monthly rates at 48.8% and 51.9% respectively, both below the overall average and separated from the highest performing months by more than 12 percentage points.  In summary, these findings depict the mid-year window as the most favorable environment and the late summer and year-end periods as the least favorable.

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

Annual success rates across the 2010–2019 period ranged from 51.0% to 67.0% and reached their lowest levels during 2015–2016 and their highest during 2017–2019, exhibiting oscillatory rather than directional variation. The two campaigns recorded for 2020 both failed, but, with such a small subsample, the observation carries little statistical weight. This lack of an increasing or decreasing trend implies that the platform's underlying success dynamics neither systematically improved from platform maturation nor deteriorated from intensified competition.

The most defensible inference is that aggregate success rates are relatively stable across the decade, and the year-to-year variation likely reflects factors external to the platform — shifting campaign composition, changing backer behavior, broader economic conditions.  Essentially, the data supports a stable long-run mean model in which annual variation represents transient deviation rather than directional change.

Yet, this conclusion is subject to an inherent structural constraint rather than the previously described analytical ambiguity. With annual subsamples averaging 98 campaigns, the resolution of the year-on-year analysis is enough to identify broad shifts but insufficient to detect gradual trends.  Thus, a credible multi-year trend analysis would require, at minimum, observations an order of magnitude above those available here.

---

## Geographic Patterns

---

| Country         | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|-----------------|:---------:|:------------:|:------------:|:-------------:|
| Australia       | 42        | 57.1%        | 38.1%        | 4.8%          |
| Canada          | 43        | 51.2%        | 44.2%        | 4.7%          |
| Switzerland     | 22        | 54.5%        | 27.3%        | 18.2%         |
| Denmark         | 30        | 56.7%        | 40.0%        | 3.3%          |
| Great Britain   | 47        | 59.6%        | 38.3%        | 2.1%          |
| Italy           | 48        | 54.2%        | 39.6%        | 6.3%          |
| United States   | 754       | 57.8%        | 36.3%        | 5.8%          |
| **Grand Total** | **986**   | **57.3%**    | **36.9%**    | **5.8%**      |

---

The dataset's geographic distribution is heavily skewed towards the United States, which contributes 754 campaigns out of 986 with no other country accounting for more than 48. The remaining 232 observations are spread across six countries: Great Britain (47), Italy (48), Canada (43), Australia (42), Denmark (30), and Switzerland (22). Moreover, the cross-country success rates exhibit modest variation, ranging from 51.2% for Canada to 59.6% for Great Britain, with the United States (57.8%), Australia (57.1%), and Denmark (56.7%) occupying intermediate positions. The inferential weight of this range is limited by the confidence intervals surrounding individual country estimates, which are sufficiently wide to render cross-country differences statistically indistinguishable from sampling variation. Consequently, findings based on the US subsample carry reasonable evidential weight while those based on any non-US countries rest on subsamples too small to support reliable inference without significant qualification.

The dataset denominates goals and pledged amounts across seven currencies (CAD, GBP, EUR, AUD, DKK, CHF, and USD) without normalization to a common monetary unit.  In the absence of exchange rate conversion, numerical comparisons of cross-country funding amounts are not valid: observed differences may reflect currency denomination rather than actual variation in goal-setting behavior or backer generosity.  Therefore, cross-country funding comparisons should be interpreted cautiously, and any conclusions treated as provisional pending currency normalization.

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

The backer count distributions display positive skew of sufficient magnitude to produce tangible divergence between mean and median across all outcome groups.  The disparity is most pronounced for successful campaigns where the median of 201 backers noticeably differs from the mean of 851 — a fourfold difference attributable to a small number of high-visibility campaigns whose backer counts are an order of magnitude above the typical observation.  A mean that is over four times the median is not a reliable measure of central tendency and overstates backer mobilization by weighting the distributional influence of outliers over the representative campaign's experience.

Beyond this mean-median divergence, the backer count distribution manifests a secondary pattern of analytical interest.  Usually, failed and canceled campaigns generate low backer counts and a constrained range of backers representing campaigns that fail to mobilize sufficient audience support.  In contrast, successful campaigns exhibit a markedly different distributional profile with high backer counts spanning a full range from modest community support to large-scale viral mobilization.  This asymmetry is reflected in the standard deviations — 1,267 for successful campaigns, 961 for failed, and 574 for canceled — implying that failure is relatively homogeneous while success is heterogeneous, an important distinction.

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

An analysis of the standard deviations of goals and pledged amounts across outcome groups reveals a structural regularity with one notable exception.  For failed, canceled, and live campaigns, goal standard deviations normally exceed those of pledged amounts — 69,884 versus 45,775 for failed campaigns, 70,557 versus 35,632 for canceled, and 76,831 versus 52,170 for live — a pattern consistent with goal-setting behavior that is not anchored to realistic audience willingness and capacity.  Creators within these groups set objectives across a wide and variable range of ambition levels while audience responses converge within a comparatively narrow band producing a systematic excess of goal variance over pledge variance.

Conversely, successful campaigns exhibit the inverse relationship: the standard deviation of pledged amounts (64,552) exceeds that of goals (40,734) making them the only outcome group in which pledge dispersion surpasses goal dispersion.  There are two mechanisms that account for this phenomenon.  First, successful campaigns have the lowest standard deviation of goal at 40,734 compared to 69,884 for failed and 70,557 for canceled campaigns indicating more disciplined goal setting.   Second, pledged amounts for successful campaigns are structurally unbounded. Specifically, once pledged amounts clear the target, contributions continue to accumulate beyond it, generating a pledged amount distribution in which audience enthusiasm rather than campaign design determines the upper range.  This combination of compressed goal variance and unbounded pledge variance produces the observed reversal and distinguishes the distributional profile of successful campaigns.

These two distributional profiles stand in direct contrast: high goal variance and low pledge variance characterize failed and canceled campaigns while low goal variance and high pledge variance characterize successful campaigns. Considered jointly, the standard deviation figures across all outcome groups support an inference in which goal discipline functions as a structural antecedent of success rather than a mere correlate, a condition that precedes and enables favorable outcomes rather than simply accompanying them.

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

The dataset includes two binary promotion flags, staff_pick and spotlight, whose individual effects on campaign outcomes do not support the hypothesis that platform endorsement improves success rates.  Campaigns carrying a spotlight designation alone record a success rate of 54.4%; those carrying a staff pick alone record 54.5%.  Both figures fall below the 57.2% success rate observed for campaigns carrying neither endorsement.  This difference is stable across both endorsement types and represents one of the more counterintuitive patterns in the dataset: platform promotion appears to be associated with marginally lower rather than higher success rates.

The pattern reverses only for campaigns carrying both endorsements simultaneously.  This group records a success rate of 62.5% — 5.3 percentage points above the unpromoted baseline — and a failure rate of 25.0%, compared to 35.5% for campaigns with neither endorsement.  Both figures are consistent with a positive combined endorsement effect, but the both-endorsement subsample comprises only 16 campaigns, a figure insufficient to support reliable statistical inference.  Also, the confidence intervals surrounding these estimates are wide enough to encompass the null hypothesis of no promotion effect, reflecting sampling variation rather than a bona fide causal relationship.

The association between dual endorsement and elevated success rates is more aligned with selection than with treatment.  Crowdfunding platforms have the operational capacity and the institutional incentive to award promotional status to campaigns already demonstrating strong performance indicators — early backer momentum, pledge velocity, presentation quality — rather than distributing endorsements in a manner that would allow causal inference.  Under this interpretation, the higher success rate among doubly endorsed campaigns is the result of the platform's selection of high-quality campaigns for endorsement rather than any causal effect on campaign outcomes.  That is to say, the endorsements function as a signal of underlying quality rather than a source of it, and the observed lift should be ascribed accordingly.

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

Campaign duration is not statistically linked to outcome in this dataset. The median duration is identical across successful and failed campaigns at 12 days, and the Spearman correlation between duration and percent funded is r ≈ −0.02, a value incompatible with the idea that longer campaign windows improve funding prospects.

The duration brackets broadly reflect this situation although with two noteworthy features at the extremes. The 40–49 day bracket posts the highest success rate at 62.7%, but, with only 51 campaigns, it is too thinly populated to support analytical deductions. The 50–59 day bracket collapses to 36.4% — the lowest in the table and 20% below the overall average — while the failure rate rises to 54.5%. Thus, creators with the longest campaigns most likely are those who extended their windows in response to poor early traction skewing the reason for failure towards underperformance rather than long duration.

Collectively, there is little support for treating campaign duration as an option for improving outcomes. The time on platform does not compensate for weak underlying demand, and creators who extend their campaign windows due to poor early performance are unlikely to alter their trajectory. Hence, duration is not a legitimate predictor of success and should not be treated as a viable strategic variable.

---

## Conclusions

The data does not support the hypothesis that **category popularity is positively associated with campaign success**.  Theater, Music, and Film & Video collectively account for nearly 70% of campaigns in the sample while recording success rates of 54.4%, 56.6%, and 57.3% respectively — none materially above the 56.5% overall average.  Technology and Photography, representing a substantially smaller share of campaign volume, record success rates of 66.7% and 61.9%.  The inverse relationship between category volume and success rate is one of the more consistent findings in the dataset and carries a direct implication for category selection: high activity within a category reflects competitive intensity rather than favorable conditions, and creators who view volume as a proxy for viability may be systematically misdirecting their efforts.

**Goal size** is among the strongest structural predictors of campaign outcome in the dataset, with consistent evidence across multiple levels of analysis.  At the distributional level, campaigns with goals exceeding 100,000 record a success rate of 22.9% compared to 77.8% for campaigns under 5,000, a differential of 54.9 percentage points across the goal spectrum. When considering central tendency, the median goal for successful campaigns (6,200) is 37% below that of failed campaigns (9,900) and 83% below that of canceled campaigns (36,400). Therefore, the monotonic relationship between goal size and outcome probability, observed consistently across both distributional and central tendency measures, is unlikely to be attributable to sampling variation and is most reasonably explained as reflecting an authentic structural association between goal discipline and campaign success.

**Timing** represents a discretionary and empirically supported lever for campaign optimization. The seasonal analysis identifies June through September as the strongest launch window, with monthly success rates ranging from 61.6% to 63.2%, consistently above the 56.5% overall average.  The day-of-week analysis identifies Monday as the strongest individual launch day at 64.1%, a margin of 13.4 percentage points above Friday's 51.0% and the largest pairwise gap in the day-of-week data.  These findings collectively identify a set of timing preferences — mid-year launch, Monday start, avoidance of late summer and year-end windows — that are both empirically grounded and feasible at no incremental cost to the creator.

**Backer volume** is the strongest quantitative predictor of funding success identified in this analysis. The Spearman correlation between backer count and total pledged amount is r = 0.94, a relationship of sufficient magnitude to account for the preponderance of variation in funding outcomes and to substantially diminish the independent explanatory contribution of average donation size. The finding implies that campaign success is primarily a function of audience mobilization rather than individual generosity: campaigns succeed by attracting large numbers of backers rather than by securing disproportionately large contributions from a smaller donor base. Creator effort and resource allocation are therefore more productively directed towards strategies that maximize audience reach and early backer engagement than towards those designed to optimize individual contribution size.

The analytical validation is consistent across multiple independent measures that successful campaigns are structurally differentiated from unsuccessful ones in ways that reflect deliberate calibrations rather than favorable circumstances. Successful campaigns record lower and less variable goals than failed or canceled campaigns, a pattern consistent with more accurate audience assessment at the goal-setting stage. They attract greater backer volume, as demonstrated by higher median backer counts and the strong correlation between backer count and total pledged, and they produce pledge distributions whose variance exceeds that of their goals, the structural consequence of clearing a realistic threshold and subsequent unbounded support. The convergence of these patterns across goal-setting behavior, backer mobilization, and funding outcomes is most feasibly construed as proof that successful campaign performance is, to a discernible degree, the product of pre-launch decisions — audience understanding, goal calibration, and ambition scoping — rather than post-launch fortune.

---

## Limitations and Recommendations

Three structural features of the dataset constrain the generalizability of the findings presented in this report. These limitations do not invalidate the analytical conclusions in aggregate, but they impose material restrictions on the inferential weight that specific results — particularly those resting on thin sub-samples — can reliably bear, and they should be held in view when accepting any finding that ventures beyond the broad patterns supported by the full sample.

**Sample size.** The dataset of 1,000 campaigns is adequate for the identification of broad distributional patterns and aggregate relationships but is insufficient to support reliable inference at the subgroup level in several key areas of the analysis. High-goal campaign tiers, non-US country subsamples, and less common subcategories each present observation counts below 50, a threshold below which point estimates become unreliable and confidence intervals wide enough to encompass materially different conclusions. This constraint is not uniform in its effect: findings derived from the full sample or from subgroups of substantial size carry reasonable evidential weight and are unlikely to be overturned by additional data, while findings derived from thin subsamples should be regarded as provisional and directional. A dataset expanded by one to two orders of magnitude would resolve the subsample constraints that limit the current analysis and permit the analytical framework developed here to be applied with substantially greater confidence.

**Currency heterogeneity.** Goals and pledged amounts are recorded in seven local currency denominations (CAD, GBP, EUR, AUD, DKK, CHF, and USD) without application of exchange rate normalization.  In the absence of conversion to a common monetary unit, observed differences in funding amounts across countries are not likely to be genuine behavioral variation: a £10,000 goal and a $10,000 goal are numerically equivalent in the raw data but represent materially different real funding targets.  The magnitude of this distortion varies with prevailing exchange rates across the seven currencies and cannot be estimated or corrected without external rate data.  Cross-country comparisons of funding amounts should therefore be treated as unreliable as presented, and any conclusions drawn from them deferred until currency normalization has been applied.

**Causal inference.** The findings presented in this report are observational and associational in nature.  No analytical technique applied here can isolate causal effects from the confounding influences that observational data inevitably contains, and the findings should not be construed as establishing causal relationships between the examined variables.  The day-of-week association may reflect compositional differences in the campaigns launched on different days rather than any effect of launch timing per se.  The goal-outcome gradient may reflect an unmeasured common cause — creator experience, audience development, market knowledge — that simultaneously determines both goal-setting behavior and campaign success rather than a causal pathway running from goal size to outcome.  The staff pick association is most credibly attributable to platform selection of already-successful campaigns rather than platform promotion of campaigns that would otherwise have underperformed.  Translating these associations into applicable causal claims requires identification strategies — randomized assignment, regression discontinuity, difference-in-differences, or instrumental variable approaches — that the current dataset and analytical framework do not support.

Each of the three limitations identified above describes a specific and tractable remediation that would materially strengthen this report's analytical framework.  The sample size constraint is most directly addressed through dataset expansion: annual observation counts in the tens of thousands would reduce estimation uncertainty to levels compatible with reliable subgroup inference and multi-year trend detection. The currency heterogeneity constraint requires the application of exchange rate normalization as a preprocessing step prior to any cross-country funding analysis, converting all monetary figures to a common unit before drawing any conclusions. The causal inference constraint is the most methodologically demanding and requires the application of quasi-experimental identification strategies capable of isolating causal effects from confounding influences — regression discontinuity designs exploiting platform promotion thresholds, difference-in-differences approaches leveraging temporal variation in platform policy, or instrumental variable methods to identify valid instruments. Collectively, these refinements would advance the analysis from a descriptive characterization of crowdfunding patterns to an explanatory account of their underlying determinants, producing conclusions that are not merely accurate descriptions of what has occurred but reliable guides to what campaign creators can do to improve their outcomes.

----

## Copyright

Nicholas J. George © 2026. All Rights Reserved.
