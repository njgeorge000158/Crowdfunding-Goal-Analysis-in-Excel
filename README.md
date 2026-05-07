![crowdfunding_goal_analysis1](https://github.com/njgeorge000158/Crowdfunding-Goal-Analysis-in-Excel/assets/137228821/748d13b8-fe17-4c3d-9f87-987078ea9a33)

----

# **Crowdfunding Campaign Analysis: *Trends, Insights, and Limitations***

----

## **Background and Approach**

Crowdfunding has grown into a widely adopted mechanism for launching products, validating ideas, and mobilizing public support since the late 2000s.  Despite its prominence, the factors that distinguish successful campaigns from unsuccessful ones remain poorly understood at a granular level.  This report addresses that gap by analyzing a sample of 1,000 campaigns drawn from a standardized dataset, examining outcomes across categories, timing, goal ranges, geographic markets, and backer distributions.

Where distributions are heavily skewed results are reported using medians rather than means.  This choice is not merely conventional because, in datasets where a small number of outliers can pull the average far from the typical value, the median is a more honest and informative summary of what a representative campaign actually experiences.

## Overall Outcomes

Of the 1,000 campaigns in the sample, 565 succeeded (56.5%), 364 failed (36.4%), 57 were canceled (5.7%), and 14 remained live at the time of analysis (1.4%).  Taken together, the failure and cancellation rates were a combined 42.1% and serve as a reminder that crowdfunding is far from a reliable funding mechanism for the average creator.  The overall success rate provides the baseline against which the report evaluates category, timing, and structural factors. rewrite and improve

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

One of the clearest patterns in the data is the divergence between campaign volume and success rate.  Specifically, the categories that attract the most campaigns are not the ones most likely to succeed. Technology (66.7%), Photography (61.9%), and Publishing (59.7%) lead at the primary category level, yet none ranks among the three most popular categories by volume.  Theater, Film & Video, and Music collectively account for nearly 70% of all campaigns in the sample while succeeding at rates of 54.4%, 57.3%, and 56.6%, respectively, at or below the 56.5% overall average.

The pattern holds at the subcategory level with a few exceptions.  The highest-performing subcategories — Web / Technology (70.6%), Translations / Publishing (66.7%), Television / Film & Video (64.7%), and Wearables / Technology (62.2%) — are all drawn from the same higher-performing primary categories, reinforcing the view that category selection is meaningful.  Yet, there are exceptions that are worth noting.  For instance, television sits within Film & Video, a mid-performing primary category, yet outperforms its peers substantially, suggesting that subcategory dynamics can diverge from the primary category trend.

From these observations, the practical implication is that a crowded category is not a proxy for a favorable one.  Creators who select a category based on its volume of activity may be entering precisely the fields where competition is highest and success rates are weakest.

## **Funding Rates: All Campaigns vs. Successful Ones**

Across all 1,000 campaigns, the median funding ratio - pledged contributions as a proportion of the stated goal - is 1.22x, meaning the typical campaign raises about 22% more than its goal.  The mean tells a very different story at 2.00x, inflated by a small number of exceptionally over-funded campaigns that pull the average well above what most creators actually experience.  This gap is wide enough to make the mean actively misleading as a summary statistic and establishes the median as the appropriate measure of central tendency in this analysis.

The picture shifts considerably when the analysis is restricted to successful campaigns alone, raising the median funding ratio to 2.12x, nearly double the stated goal on the typical campaign.  Food (3.29x) and Photography (2.55x) lead among primary categories, followed by Games (2.39x) and Publishing (2.28x).  Technology is the notable outlier at the bottom: despite posting the highest success rate of any primary category, it has the lowest median funding ratio among successful campaigns (2.00x).  This combination — high likelihood of success, modest over-funding — suggests that technology campaigns tend to be more precisely scoped, hitting their targets without generating the surplus that characterizes other categories such as Food or Photography.

The over-funding effect is most pronounced at the sub-category level in niche music genres.  Successful Metal campaigns reach a median of 4.4x their stated goal; successful Jazz campaigns reach 3.5x.  These figures are among the highest in the dataset and point to a dynamic that recurs across niche categories: when a tightly defined audience is genuinely engaged, it tends to drive exceptional outcomes relative to the campaign goal.

## Goal Size and Success

---

| Goal Range          | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|---------------------|:---------:|:------------:|:-------------:|:------------:|
| Under $5,000        | 285       | 77.5%        | 20.4%         | 1.1%         |
| $5,000 – $10,000    | 317       | 51.7%        | 39.7%         | 7.9%         |
| $10,000 – $15,000   | 9         | n/a †        | n/a †         | n/a †        |
| $15,000 – $35,000   | 38        | 92.1%        | 7.9%          | 0.0%         |
| $35,000 – $100,000  | 159       | 61.0%        | 32.7%         | 4.4%         |
| Over $100,000       | 192       | 22.9%        | 62.5%         | 11.5%        |

*† Only 9 campaigns in this range — insufficient for a reliable estimate.*

---

Goal size is among the strongest structural predictors of a campaign's outcome.  The data reveals a non-linear relationship in which success rates are high at low goal levels, compress in the mid-range, and collapse at the high end.  Campaigns with goals above $100,000 succeed at just 22.9%, well below the 56.6% overall average and roughly one-third the rate of campaigns under $5,000 (77.5%).  The $15,000–$35,000 band is an exception, posting a 92.1% success rate, but should be interpreted cautiously given its comparatively small sample of only 38 campaigns.

The goal-outcome relationship is reinforced by the median figures.  Successful campaigns set a median goal of $6,200 markedly lower than the $9,900 median for failed campaigns and dramatically lower than the $36,400 median for canceled ones.  The gradient across all three outcome groups is steep and consistent enough to suggest that disciplined, realistic goal-setting is not merely a byproduct of success but a contributing factor to it.  In other words, creators who calibrate their goals to what their audience can plausibly support are systematically more likely to reach them.

## Timing: Monthly and Day-of-Week Patterns

### Day of Week

Among the days of the week, Monday launches achieve the highest success rate at 65.8%, a noticeable 14.8 percentage points above Friday, which posts the lowest rate at 51.0%.  Sunday (58.6%) and Saturday (58.3%) occupy the middle ground near the overall average.  However, the pattern is not uniform across the remaining weekdays, which cluster between 54.9% and 56.4% and show little meaningful separation from one another.

These differences should not be overstated.  With 74–100 successful campaigns per weekday in the sample, the confidence intervals around each estimate are wide enough that some of the observed variation reflects sampling noise rather than genuine day-of-week effects, and this caveat applies most strongly to the mid-week days where differences are small.  Nevertheless, the Monday-Friday gap of 14.8 percentage points is large enough and consistent enough in direction to be actionable. Creators with flexibility over their launch date have a reasonable basis for preferring the start of the working week.

### Monthly Trends

Monthly success rates follow a broad seasonal arc in which those rates rise steadily from January (53.8%) through June (64.0%), remain elevated through September (61.6%), then decline toward year-end, reaching 51.9% in December.  There are two months that disrupt this pattern.  August drops sharply to 48.8% — a 13.6 percentage point decline from July — making it the weakest month despite falling within what should be the elevated mid-year window.  May dips to 54.8% after April's 59.7%, a smaller but still notable interruption to the otherwise steady spring rise.  

The August anomaly has a plausible explanation that reduced backer attention during the late summer likely suppresses engagement regardless of campaign quality.  The May dip is harder to account for and may simply reflect noise in a sample of this size: with an average of 82 campaigns per month, a single unusual cohort can shift a monthly rate by several percentage points. 

Taken together, the data suggests that June, July, and September represent the strongest windows for a campaign launch, each posting success rates between 61.6% and 64.0% and comfortably above the 56.5% average.  In contrast, August and December are the months to avoid where timing is discretionary, posting the two lowest rates in the dataset at 48.8% and 51.9% respectively.

## Year-on-Year Trends

Annual success rates ranged from 51.0% to 67.0% across the 2010–2019 period, with no monotonic upward or downward trajectory. Instead, rates oscillated considerably from year to year, peaking in 2017–2019 and troughing in 2015–2016. The two campaigns recorded for 2020 both failed, but this window is too narrow to interpret meaningfully.

The absence of a sustained directional trend suggests that aggregate crowdfunding success rates were relatively stable across the decade, with year-to-year variation more likely driven by compositional shifts in campaign types and broader cyclical conditions than by any underlying platform maturation effect. In other words, the platform did not appear to become systematically easier or harder to succeed on over time, at least not within this sample.

That conclusion should be held tentatively. With only 1,000 campaigns spread across ten years, annual sub-samples average roughly 100 campaigns each, which is sufficient to observe broad patterns but too thin to detect gradual trends with confidence. A substantially larger dataset, ideally covering tens of thousands of campaigns per year, would be needed to distinguish genuine long-run structural change from the noise inherent in a sample of this size.

---

## Geographic Patterns

The sample is heavily US-centric: 763 of the 1,000 campaigns (76.3%) originate from the United States. The remaining campaigns span six countries: Great Britain (48), Italy (48), Canada (44), Australia (43), Denmark (31), and Switzerland (23).

Success rates vary modestly across geographies. Great Britain leads at **58.3%**, followed by the US (57.1%), Australia (55.8%), and Denmark (54.8%). Canada has the lowest rate at 50.0%. These differences are relatively small and must be interpreted carefully given the limited non-US sample sizes — no country outside the US contributes more than 48 campaigns.

*Note: Because goals and pledges are denominated in local currencies (CAD, GBP, EUR, AUD, DKK, CHF, USD) with no currency conversion applied, direct cross-country comparisons of funding amounts are not meaningful without normalization.*

---

## Backer Distributions and Statistical Approach

Backer counts are highly skewed in both successful and unsuccessful campaigns. The mean and median diverge substantially across all outcome groups, confirming that averages are not a reliable measure of central tendency for this dataset.

| Outcome    | Median Backers | Mean Backers | Std Dev |
|------------|:--------------:|:------------:|:-------:|
| Successful | 201            | 851          | 1,267   |
| Failed     | 114            | 586          | 961     |
| Canceled   | 139            | 435          | 574     |

The contrast between median and mean is dramatic for successful campaigns (201 vs. 851), indicating that a small number of viral campaigns with thousands of backers are pulling the average upward. Using means as representative figures — as the original analysis does in several places — materially overstates what a typical campaign experiences. **All central tendency figures in this report use medians.**

Successful campaigns also exhibit considerably greater variance (std dev 1,267) than failed ones (961) or canceled ones (574). This asymmetry makes intuitive sense: failed campaigns tend to attract few or no backers, clustering the distribution near zero, while successful campaigns draw support across a broad spectrum — from modest community backing to large-scale viral mobilization.

---

## Standard Deviation: Goals vs. Pledges by Outcome

An informative structural anomaly appears in the standard deviations of goals and pledged amounts across outcome groups.

| Outcome    | Std Dev of Goal | Std Dev of Pledged |
|------------|:---------------:|:------------------:|
| Successful | $40,734         | $64,552            |
| Failed     | $69,884         | $45,775            |
| Canceled   | $70,557         | $35,632            |
| Live       | $76,831         | $52,170            |

For every outcome group except successful campaigns, **the standard deviation of goals exceeds the standard deviation of pledged amounts**. For successful campaigns, the relationship reverses: pledged amounts are more variable than the goals set. Furthermore, the standard deviation of goals is notably lower for successful campaigns ($40,734) than for failed ($69,884), canceled ($70,557), or live ($76,831) campaigns.

This pattern is consistent with two related interpretations. First, creators who succeed tend to set more disciplined, realistic goals, resulting in a tighter goal distribution. Second, once a campaign succeeds — having cleared its goal — the final pledged amount depends on how much additional support continues to flow in, producing a wide range of over-funding outcomes. *Campaigns that fail or get canceled, by contrast, tend to set aspirationally large goals while achieving highly variable (and often very low) pledged amounts.*

---

## Platform Promotion: Staff Pick and Spotlight

The dataset includes two binary promotion flags: `staff_pick` and `spotlight`. Examining their combined effect reveals a modest but meaningful pattern.

| Promotion Status  | Campaigns | Success Rate |
|-------------------|:---------:|:------------:|
| Neither           | 699       | 57.2%        |
| Spotlight Only    | 252       | 54.4%        |
| Staff Pick Only   | 33        | 54.5%        |
| Both Endorsements | 16        | 62.5%        |

Campaigns carrying either endorsement alone show **no meaningful lift** over un-promoted campaigns (54.4–54.5% vs. 57.2%). Only campaigns with both endorsements simultaneously achieve a higher rate (62.5%), though the sample of 16 such campaigns is too small to draw firm conclusions. The most likely interpretation is that both endorsements are awarded to the same high-quality campaigns — so the observed lift reflects underlying campaign quality rather than a causal effect of promotion.

---

## Campaign Duration

Median campaign duration is virtually identical across all outcome groups (12 days for both successful and failed campaigns), and the correlation between duration and percent funded is near zero (r ≈ −0.04). Longer campaigns do not outperform shorter ones. Creators should not treat an extended campaign window as a substitute for strong fundamentals.

---

## Conclusions

This analysis yields five principal conclusions:

1. **Popularity does not predict success.** Theater, Music, and Film & Video dominate by campaign volume but succeed at or below the overall average. Technology and Photography achieve materially higher success rates with a fraction of the campaign count.

2. **Goal size is a strong structural predictor.** Campaigns with goals above $100,000 succeed at just 22.9% — less than one-third the rate of campaigns under $5,000. Successful campaigns set goals that are systematically lower and less variable than those that fail.

3. **Timing matters.** June through September represents the strongest seasonal window. Monday outperforms Friday by roughly 13 percentage points as a launch day. August and December are the weakest months in this dataset.

4. **Backer volume drives outcomes more than donation size.** The correlation between backer count and total pledged is r = 0.87. Average donation size has minimal predictive value. Campaigns that win do so by mobilizing large numbers of backers, not by securing unusually large individual contributions.

5. **Successful campaigns are structurally different, not just luckier.** They set more disciplined goals, attract more backers, and generate highly variable over-funding outcomes — a profile that is consistent with deliberate planning rather than chance.

---

## Limitations and Recommendations

Two structural weaknesses limit the generalizability of these findings:

- **Sample size.** With 1,000 campaigns, several analyses rest on thin sub-samples — particularly at higher goal tiers, in smaller countries, and in less common sub-categories. A dataset one to two orders of magnitude larger would support substantially more robust conclusions.

- **Currency heterogeneity.** Goals and pledged amounts are denominated in seven currencies without normalization. Cross-country funding comparisons are therefore unreliable as presented.

- **Causal inference.** All findings are associational. The analysis cannot determine, for example, whether Monday launches cause higher success rates or whether the types of campaigns launched on Mondays differ systematically from those launched on Fridays.

Future analyses should address these constraints by expanding the dataset, applying currency conversion, and using median-based measures of central tendency throughout. With those adjustments, the analytical framework developed here could yield more reliable and actionable guidance for campaign creators.








-----------
----------
-----------

## **Timing and Monthly Trends**

A raw view of the Months by Outcomes worksheet offered little immediate insight, as absolute counts are difficult to interpret without normalization. Converting these figures into monthly success rates — in a dedicated Months by Outcomes (%) worksheet — revealed a clearer pattern. Success rates range from 49% to 64% across the calendar year, rising steadily from January through June, plateauing through September, then declining into year-end. Two notable exceptions disrupt this trend: success rates drop sharply in May and August, falling 5% and 13% from their respective prior months. These anomalies notwithstanding, the broader seasonal pattern suggests that campaign timing is a meaningful lever — one that creators can strategically exploit to improve their odds of success.



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
