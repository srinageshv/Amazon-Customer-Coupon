# Amazon-Customer-Coupon
Checking the Python and data analysis/cleaning/decision techniques using Pandas and Seaborn visualization concepts.


3 Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.
# ==========Analytical Insights & Comparison

In the In-Vehicle Coupon Recommendation dataset, comparing these two segments reveals a strong behavioral divide:

    Frequent Bar Goers (> 3 times/month): Have an acceptance rate of approximately 76.8%. Customers who regularly visit bars are significantly more responsive to bar coupon promotions.

    Infrequent/Non-Bar Goers (≤ 3 times/month): Have an acceptance rate of approximately 37.1%.

    Key Finding: Customers who visit bars more than 3 times a month are more than twice as likely to accept a bar coupon compared to those who visit 3 or fewer times a month. Prior habit and product context drive coupon conversion much more than the promotional discount alone.

4.     Comparison & Findings

    Drivers who visit bars > 1/month AND are over 25: Acceptance rate is approximately 69.5%.

    All other drivers: Acceptance rate is approximately 33.5%.

Is there a difference?

Yes, there is a substantial difference. Drivers who visit a bar more than once a month and are over the age of 25 are more than twice as likely to accept a bar coupon compared to all other drivers in the dataset—a positive difference of over 35 percentage points.

This demonstrates that combining behavioral frequency (visiting bars regularly) with demographic age filters (over 25) creates a highly responsive target segment for bar promotions.

5 Comparison & Key Takeaway

    Target Segment (Bar > 1/mo + Adult/Partner Passenger + Non-Farming/Forestry Occupation): Acceptance rate is approximately 71.3%.

    All Other Drivers: Acceptance rate is approximately 37.7%.

Summary

Yes, there is a substantial difference. Drivers carrying adult passengers or partners who regularly visit bars accept bar coupons at nearly double the rate (~33.6 percentage points higher) compared to all other driver profiles. Having adult companions in the vehicle acts as a strong social catalyst for accepting impulse bar recommendations.

6 
Target Combination Segment: Shows an overall acceptance rate of approximately 58.8% to 62.2% (depending on exact missing-value imputation strategy).

All Others: Shows an acceptance rate of approximately 29.5% to 31.0%.

Takeaway: Broadening the criteria by combining frequent bar goers (with peers or younger drivers) alongside budget-conscious frequent diners (< $50K income) captures a much larger target segment (~60–70% of total bar coupon recipients) while still maintaining a significantly higher conversion rate (~30 percentage points higher) compared to the remaining population.

7
1. Habitual Behavior is the Strongest Predictor

    Hypothesis: Prior habits heavily outweigh the promotional offer itself.

    Evidence: Drivers who already visit bars more than 3 times a month accepted coupons at an overwhelming rate (~76.8%), compared to just ~37.1% for those visiting 3 or fewer times. A coupon rarely creates new habits, but it acts as a strong incentive for existing behaviors.

2. Social Context & Companion Dynamics Act as Catalysts

    Hypothesis: Drivers traveling with adult companions (friends or partners) are far more open to spontaneous bar detours than solo drivers or those with children.

    Evidence: Drivers visiting bars regularly with non-child passengers achieved a ~71.3% acceptance rate. The presence of peers creates a social setting where accepting a bar recommendation aligns with group activity, whereas traveling with kids naturally acts as a barrier.

3. Age & Lifestyle Maturity Drive Conversion

    Hypothesis: Drivers over 25 who already frequent bars represent a prime high-converting demographic due to greater financial independence and established social routines.

    Evidence: The combination of regular bar visits and being over age 25 yielded a ~69.5% acceptance rate (compared to ~33.5% for all other drivers).

4. Value-Sensitivity among Young/Budget Drivers Broadens Reach

    Hypothesis: While frequent high-income bar goers drive top conversion, younger drivers (<30) and budget-conscious, frequent value-diners (<$50K income) form a second, highly responsive audience seeking promotional savings.

    Evidence: Combining frequent bar goers, younger drivers, and frequent low-income diners captured a much broader pool of drivers while still maintaining a ~59–62% acceptance rate (~30 percentage points higher than the baseline remnant group).

Key Strategic Takeaway

Targeting Efficiency over Broad Reach: Bar coupons sent indiscriminately yield near-random conversion (~50% overall), but routing coupons specifically to drivers with a history of bar visits, traveling with peers, or fitting a young/social demographic boosts conversion rates to 70%+.
