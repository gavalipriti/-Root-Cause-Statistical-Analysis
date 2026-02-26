# -Root-Cause-Statistical-Analysis
Critical Thinking Questions Answered
# 1. Are defects random or systematic?
- Not random: Structural defects consistently dominate across products and time periods.
- Weekly and monthly patterns show spikes at specific times (e.g., weeks 17–20, January peak), suggesting systematic drivers rather than random noise.

# 2. Is one shift consistently underperforming?
- Friday–Sunday shifts show the highest defect counts.
- ANOVA on repair costs across shifts indicates statistically significant differences (p-value < 0.05), meaning defect severity/costs vary by day.
- End-of-week shifts are underperforming compared to mid-week.

# 3. Is one machine producing high severity defects?
- Cross-tab analysis shows certain product IDs (machines) repeatedly linked with critical defects.
- Example: Product IDs in the top 5 defect counts also show a higher share of critical severity.
- These machines are high-risk and should be prioritized for maintenance or process review.

# Clear Interpretation (not just plots):
- Defects are systematic, not random.
- End-of-week shifts are consistently worse.
- A small set of machines drive most critical defects.
- Structural + functional defects together explain ~80% of issues.
