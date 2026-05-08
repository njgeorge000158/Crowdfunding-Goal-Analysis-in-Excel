![crowdfunding_goal_analysis1](https://github.com/njgeorge000158/Crowdfunding-Goal-Analysis-in-Excel/assets/137228821/748d13b8-fe17-4c3d-9f87-987078ea9a33)

----

# **Crowdfunding Campaign Analysis: *Trends, Insights, and Limitations***

----

## **Background**

Crowdfunding has emerged since the late 2000s as a widely adopted mechanism for product launches, idea validation, and public mobilization. Despite its growth and prominence, the determinants of campaign success remain incompletely understood, particularly at the level of granular, actionable factors. This report contributes to that understanding by analyzing a sample of 1,000 campaigns drawn from a standardized dataset, with outcomes examined across five dimensions: category, timing, goal range, geographic market, and backer distribution.

## Overall Outcomes

Of the 1,000 campaigns in the sample, 565 succeeded (56.5%), 364 failed (36.4%), 57 were canceled (5.7%), and 14 remained live at the time of analysis (1.4%).  Taken together, the failure and cancellation rates were a combined 42.1% and serve as a reminder that crowdfunding is far from a reliable funding mechanism for the average creator.  The overall success rate provides the baseline against which the report evaluates category, timing, and structural factors. rewrite and improve

## **Category Performance: Popularity vs. Success**

---

| Primary Category | Campaigns | Success Rate | Failure Rate | Canceled Rate |
|------------------|:---------:|:------------:|:------------:|:-------------:|
| Technology       | 96        | 66.7%        | 29.2%        | 2.1%          |
| Photography      | 42        | 61.9%        | 26.2%        | 9.5%          |
| Publishing       | 67        | 59.7%        | 35.8%        | 3.0%          |
| Film & Video     | 178       | 57.3%        | 33.7%        | 6.2%          |
| Music            | 175       | 56.6%        | 37.7%        | 5.7%          |
| Theater          | 344       | 54.4%        | 38.4%        | 6.7%          |
| Food             | 46        | 47.8%        | 43.5%        | 8.7%          |
| Games            | 48        | 43.8%        | 47.9%        | 2.1%          |
| Journalism       | 4         | 100% †       | 0% †         | 0% †          | 

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

### Day-of-Week Trends

Among the days of the week, Monday launches achieve the highest success rate at 65.8%, a noticeable 14.8 percentage points above Friday, which posts the lowest rate at 51.0%.  Sunday (58.6%) and Saturday (58.3%) occupy the middle ground near the overall average.  However, the pattern is not uniform across the remaining weekdays, which cluster between 54.9% and 56.4% and show little meaningful separation from one another.

These differences should not be overstated.  With 74–100 successful campaigns per weekday in the sample, the confidence intervals around each estimate are wide enough that some of the observed variation reflects sampling noise rather than genuine day-of-week effects, and this caveat applies most strongly to the mid-week days where differences are small.  Nevertheless, the Monday-Friday gap of 14.8 percentage points is large enough and consistent enough in direction to be actionable. Creators with flexibility over their launch date have a reasonable basis for preferring the start of the working week.

### Monthly Trends

Monthly success rates follow a broad seasonal arc in which those rates rise steadily from January (53.8%) through June (64.0%), remain elevated through September (61.6%), then decline toward year-end, reaching 51.9% in December.  There are two months that disrupt this pattern.  August drops sharply to 48.8% — a 13.6 percentage point decline from July — making it the weakest month despite falling within what should be the elevated mid-year window.  May dips to 54.8% after April's 59.7%, a smaller but still notable interruption to the otherwise steady spring rise.  

The August anomaly has a plausible explanation that reduced backer attention during the late summer likely suppresses engagement regardless of campaign quality.  The May dip is harder to account for and may simply reflect noise in a sample of this size: with an average of 82 campaigns per month, a single unusual cohort can shift a monthly rate by several percentage points. 

Taken together, the data suggests that June, July, and September represent the strongest windows for a campaign launch, each posting success rates between 61.6% and 64.0% and comfortably above the 56.5% average.  In contrast, August and December are the months to avoid where timing is discretionary, posting the two lowest rates in the dataset at 48.8% and 51.9% respectively.

### Year-on-Year Trends

Annual success rates ranged from 51.0% to 67.0% across the 2010–2019 period, with no sustained upward or downward trajectory.  Instead, rates oscillated considerably from year to year — peaking across 2017–2019 and troughing in 2015–2016 — suggesting the platform neither matured into a more favorable environment for creators nor deteriorated into a less forgiving one.  The two campaigns recorded for 2020 both failed, but, with such a small sample, the observation carries little analytical weight.

The most defensible interpretation is that aggregate crowdfunding success rates were relatively stable across the decade.  The year-to-year variation more likely reflects shifts in the composition of new campaigns and cyclical fluctuations in backer behavior than any structural change in the platform itself.  Essentially, the data is more consistent with a stable long-run mean around which success rates oscillate than with any narrative of improvement or decline.

However, a structural feature of the data rather than any ambiguity in the findings themselves constrains that interpretation.  With 1,000 campaigns spread across ten years, annual sub-samples average roughly 100 observations each, which is sufficient to identify broad patterns but too thin to detect gradual trends with confidence.  Thus, distinguishing a true structural shift from sampling noise at this resolution is not reliably possible.  Multi-year trend analysis that could reliably distinguish such structural changes from cyclical variations would require annual observations an order of magnitude or more above those available in this dataset.

---

## Geographic Patterns

Geographically, the sample is less a global survey than a US-dominated snapshot.  At 763 campaigns (76.3%), the United States alone accounts for more than three in four observations.  The remaining 237 are spread thinly across six countries: Great Britain and Italy (48 each), Canada (44), Australia (43), Denmark (31), and Switzerland (23) — with the largest non-US contributor representing less than 5% of the total.

Success rates vary modestly across geographies, ranging from 50.0% (Canada) to 58.3% (Great Britain), with the US (57.1%), Australia (55.8%), and Denmark (54.8%) occupying the middle. An 8.3 percentage point spread across seven countries is not large, and with no non-US country contributing more than 48 campaigns, none of the cross-country differences can be distinguished from sampling noise with any confidence.

It should be noted that goals and pledged amounts are recorded in local currencies across seven denominations (CAD, GBP, EUR, AUD, DKK, CHF, and USD) without normalization to a common unit. Cross-country comparisons of funding amounts are therefore not meaningful as presented and should be interpreted accordingly.

---

## Backer Distributions and Statistical Approach

---

| Outcome    | Median Backers | Mean Backers | Std Dev |
|------------|:--------------:|:------------:|:-------:|
| Successful | 201            | 851          | 1,267   |
| Failed     | 115            | 586          | 961     |
| Canceled   | 139            | 435          | 574     |
| Live       | 149            | 584          | 968     |

---

Backer count distributions exhibit substantial positive skew across all outcome groups, producing meaningful divergence between mean and median in every case. The disparity is sharpest for successful campaigns, where a median of 201 backers sits against a mean of 851 — a fourfold gap driven by a small number of high-visibility campaigns whose backer counts are an order of magnitude above the typical observation. A mean that is four times the median does not describe a minor statistical inconvenience; it describes a summary statistic that misrepresents the experience of the overwhelming majority of campaigns in the dataset. Therefore, the median is the only defensible measure of central tendency in this analysis.

The outcome distributions reveal a second, related pattern. Failed and canceled campaigns are tightly clustered at low backer counts, most attract negligible support, and range of charateristics is narrow. In contrast, successful campaigns span the full range from modest community support to large-scale viral mobilization. Standard deviations of 1,267 for successful campaigns against 961 for failed and 574 for canceled capture this asymmetry, but the underlying point is more intuitive: success comes in far more sizes than failure does. In this dataset, failure is relatively uniform; success is not.

---

## Standard Deviation: Goals vs. Pledges by Outcome

---

| Outcome    | Std Dev of Goal | Std Dev of Pledged |
|------------|:---------------:|:------------------:|
| Successful | $40,734         | $64,552            |
| Failed     | $69,884         | $45,775            |
| Canceled   | $70,557         | $35,632            |
| Live       | $76,831         | $52,170            |

---

A structural anomaly in the standard deviations of goals and pledged amounts across outcomes uncovers one of the more important patterns in the dataset.  For every outcome except successful campaigns, the standard deviation of goals exceeds that of pledged amounts, sometimes, substantially.  For failed campaigns, the figures are $69,884 versus $45,775; for canceled campaigns, $70,557 versus $35,632; for live campaigns, $76,831 versus $52,170.  In these cases, creators are setting goals across a wider range than the pledged amounts they ultimately receive: an example of aspirational goal-setting detached from what audiences are willing to support.

Conversely, successful campaigns invert this relationship entirely.  Their standard deviation of pledged amounts ($64,552) exceeds that of goals ($40,734).  There are two forces that produce this reversal. First, successful creators set more disciplined, realistic goals, compressing the goal standard deviation relative to other outcome groups: $40,734 against $69,884 for failed and $70,557 for canceled campaigns.  Second, once a campaign clears its goal, the final pledged amount is no longer bounded because it depends on how much additional support appears after the threshold is crossed.  And, this additonal support creates a wide and unpredictable range of overfunding that inflates the variance of pledged amounts.

The two distributional patterns stand in direct contrast.  Failed and canceled campaigns are characterized by wide goal dispersion and narrow pledge dispersion, consistent with aspirational goal-setting that audiences do not validate.  Successful campaigns exhibit the opposite relationship, low goal variance and high pledge variance, consistent with disciplined goals and expansive pledging.  Thus, the standard deviation figures, read together, suggest that goal discipline is not merely correlated with success but structurally implicated in it.

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

The dataset includes two binary promotion flags — staff_pick and spotlight — whose combined effect produces one of the more counterintuitive findings in the analysis. Campaigns carrying either endorsement alone have about the same success rate that is noticeably lower than unpromoted campaigns: success rates of 54.4% for spotlight-only and 54.5% for staff-pick-only campaigns compared to a 57.2% rate for neither endorsement. Apparently, being singled out by the platform appears to confer no advantage whatsoever.

The picture shifts only when both endorsements are held simultaneously. Campaigns with both flags post a 62.5% success rate, 5.3 percentage points above the unpromoted baseline and the highest of any promotion group. The failure rate for this group is also lower at 25.0%, against 35.5% for unpromoted campaigns. These results would be pertinent, but the group contains only 16 campaigns, making it impossible to distinguish a genuine promotion effect from the idiosyncrasies of a small and potentially unrepresentative sample.

The more plausible interpretation is that both endorsements are not causing success but tracking it. Platforms are more likely to award staff pick and spotlight status to campaigns that are already performing well, which implies that the observed lift is more likely a reflection of underlying campaign quality than promotional effects. In the end, the endorsements are a signal of quality rather than a source of it.

---

## Campaign Duration

Campaign duration exhibits no statistically meaningful association with outcome. Median duration is 12 days across both successful and failed campaigns, and the correlation between duration and percent funded is negligible at r ≈ −0.04. These figures are inconsistent with the hypothesis that extended campaign windows improve funding prospects and suggest that duration is not an option available to creators seeking to improve their odds of success.

---

## Conclusions

Popularity does not predict success. Theater, Music, and Film & Video collectively account for nearly 70% of all campaigns in the sample yet succeed at or below the overall average. Technology and Photography achieve materially higher success rates with a fraction of the campaign count. Therefore, crowded categories do not favor a successful outcome.

Goal size is among the strongest structural predictors of outcome. Campaigns with goals above $100,000 succeed at just 22.9% — less than one-third the rate of campaigns under $5,000 (77.8%). The median goal for successful campaigns ($6,200) is less than half that of failed ones ($9,900) and less than one-sixth that of canceled ones ($36,400). The gradient is steep, consistent, and difficult to explain away as coincidence.

Timing is a meaningful but overlooked lever. June through September represents the strongest seasonal window, with success rates ranging from 61.6% to 63.2%. Monday outperforms Friday by 13.4 percentage points — the largest day-of-week gap in the dataset. August and December are the weakest windows, posting the two lowest monthly rates at 48.2% and 50.0% respectively. For creators with flexibility over their launch date, the data provide a reasonable basis for preference.

Backer volume is the primary engine of funding success. The correlation between backer count and total pledged is r = 0.87 — among the strongest relationships in the dataset. Average donation size, by contrast, has minimal predictive value. Campaigns that succeed do so by mobilizing large numbers of backers, not by securing unusually large individual contributions. The practical implication is that creator effort is better directed toward audience breadth than donor depth.

Successful campaigns are structurally different, not just luckier. They set lower and less variable goals, attract more backers, and generate highly variable over-funding outcomes — a combination that points to deliberate calibration rather than chance. The standard deviation figures, the median goal comparisons, and the backer distribution data all converge on the same profile: successful creators appear to know their audiences and scope their ambitions accordingly, and their audiences respond by exceeding what was asked.

---

## Limitations and Recommendations

Three structural limitations constrain the generalizability of these findings and should be held in view when interpreting any specific result.

**Sample size.** At 1,000 campaigns, the dataset is adequate for identifying broad patterns but insufficient for the finer-grained analyses the data invite. Several key sub-samples — campaigns with goals above $100,000, non-US countries, and less common sub-categories — contain fewer than 50 observations, placing them well below the threshold at which estimates become reliable. The problem is not uniform across the report: findings based on the full sample or large sub-groups carry reasonable evidential weight, while those resting on thin sub-samples should be treated as directional at best. A dataset one to two orders of magnitude larger would resolve most of these constraints and allow the analytical framework developed here to be applied with substantially greater confidence.

**Currency heterogeneity.** Goals and pledged amounts are recorded in seven local currencies — CAD, GBP, EUR, AUD, DKK, CHF, and USD — with no exchange rate normalization applied. Any cross-country comparison of funding amounts in this report is therefore unreliable as presented: a £10,000 goal and a $10,000 goal are treated as equivalent in the raw data, which they are not. Until currency conversion is applied, geographic funding comparisons should be interpreted as indicative at most and set aside where precision is required.

**Causal inference.** Every finding in this report is associational. The analysis identifies patterns — Monday launches correlate with higher success rates, lower goals correlate with better outcomes, staff pick endorsements correlate with quality — but cannot determine whether these relationships are causal or whether they are produced by confounding factors that the data do not capture. Monday campaigns may succeed more often not because of the day itself but because of systematic differences in the types of campaigns launched on Mondays. Lower goals may predict success not because restraint causes audiences to respond but because both reflect an underlying characteristic — creator experience, market knowledge, audience size — that drives both goal-setting behavior and campaign outcomes simultaneously. These distinctions matter for anyone seeking to act on the findings rather than simply describe them.

Addressing these limitations directly would substantially strengthen any follow-on analysis. Expanding the dataset to tens of thousands of campaigns per year, applying currency normalization before conducting any cross-country comparison, and supplementing associational analysis with quasi-experimental methods where possible — regression discontinuity around platform thresholds, for instance, or difference-in-differences around policy changes — would move the analytical framework from descriptive to explanatory and make its conclusions considerably more actionable for campaign creators.

----

## Copyright

Nicholas J. George © 2026. All Rights Reserved.
