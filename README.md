You can download the whole results consolidated ppt which was presented to the EuromIX team.
[Final_presentation_EuromIX.pdf](https://github.com/user-attachments/files/26658442/Final_presentation_EuromIX.pdf)

1. Core Objective

At its heart, the project is asking one question:

“What happens to our revenue if we adopt a competitor’s pricing model?”

What are we comparing:

Current pricing (pay-as-you-go + reduced tariff)
Competitor’s bundle-based packages (S, M, L)

And trying to figure out:

Will customers switch?
How much revenue do we lose or retain?
What should we do about it?
2. Data & Methodology
Data used

What did I worked with:

12 months of billing data
Customer tariff plans
Usage data (calls + data)
Data preparation

Key steps:

Merged all datasets into one final analysis file
Cleaned missing values:
Isolated blanks → treated as 0
Long gaps → treated as NULL (likely contract gaps)
Translated dataset from French → English

This matters because your conclusions depend heavily on how usage and billing were interpreted.

Analytical approach

You didn’t just compare prices—you layered multiple analyses:

Revenue breakdown
Customer switching behavior
Churn estimation
Competitor impact simulation
Strategic recommendations
3. Key Findings
A. Revenue is almost entirely driven by data

This is the biggest insight.

Total revenue ≈ €629K
~88% comes from data usage
Calls contribute only ~0.56%

Translation:
Calls barely matter. Data pricing is everything.

B. Reduced tariff dominates revenue
~57% of revenue comes from reduced tariff users

So “discounted” plan is actually the main money-maker.

C. Customer spending behavior
Median monthly bill ≈ €39.39
50% of users fall roughly between €33–€47

But here’s the twist:

Top 10% of users generate ~30% of total revenue
High bills go up to €565/month

This is a classic heavy-user dependency problem.

D. Customers will switch (almost all of them)

Under rational assumptions:

100% of customers would switch to competitor plans
98% would choose the competitor’s M package

Meaning:
Current pricing is not competitive at all.

E. Adopting competitor model = massive revenue loss
Current revenue: €629K
After adopting competitor pricing: ~€156K

That’s a ~75% drop in revenue

This is the most critical conclusion in the entire project.

4. Strategic Problem (What’s really going on)

Here’s the underlying tension:

Customers prefer cheap bundled plans
Your revenue depends on high data overages (especially from heavy users)

If you match competitors:
→ You lose high-margin usage revenue

If you don’t:
→ You lose customers

5. Proposed Strategic Alternatives

You explored 3 pricing strategies:

1. Bundles with extra data add-ons
Fixed plans + extra GB packs
2. Bundles with pay-as-you-go overages
Hybrid model (bundles + usage pricing)
3. Lower-priced pay-as-you-go (recommended)
Keep usage-based model
Reduce rates significantly
6. Key Insight from Simulations

Across S, M, and L comparisons:

Customers consistently prefer Pay-As-You-Go (if priced low enough)

This is interesting because:

Competitors push bundles
But users still respond to flexible pricing if it’s cheap
7. Final Recommendation

Lower the Pay-As-You-Go pricing instead of copying competitors

Why?

Keeps the differentiation (USP)
Simpler pricing structure
Encourages higher usage
Helps retain customers
Trade-off:
Revenue drops from €629K → ~€131K
Slightly worse than competitor model (~€156K)

BUT:

Better for customer retention
Better long-term positioning
8. What’s Missing / Assumptions

The model assumes:

Customers act 100% rationally
No brand loyalty
No switching friction

That’s a big simplification.

In reality:

Some customers would stay
Switching isn’t frictionless
Brand/value perception matters

So revenue loss is likely overestimated.

9. Suggested Future Work

Understand why customers stay (price vs quality vs reliability)
Study market growth potential
Analyze roaming usage patterns
10. Bottom Line

What this project really shows:

Current model is highly profitable but fragile
Competitor pricing is attractive but unsustainable
The real opportunity is rethinking pricing without killing margins
