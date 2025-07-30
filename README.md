# Internal Audit Compliance Dashboard

A Tableau dashboard designed to monitor internal audit performance across multiple sites. It highlights key metrics like control test outcomes, cash discrepancies, and audit reviewer loads—enabling stakeholders to spot compliance risks and operational weaknesses quickly.

## 📊 Interactive Dashboard (Tableau Public)

**[🔗 View the full dashboard here](https://public.tableau.com/views/auditandcomp/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

This dashboard provides a bird’s-eye view of audit compliance using visual summaries and breakdowns by site, country, reviewer, and control type.

![Dashboard Preview](<img width="1199" height="1396" alt="internal audit dashboard" src="https://github.com/user-attachments/assets/bee88ec2-b35e-418d-b1e8-85e703fbd184" />
)

## 📁 About the Dataset

The dataset includes control testing results from an internal audit process. It contains details such as:

- Reviewer names
- Site locations (with country-level mapping)
- Control test IDs and outcomes (Pass, Fail, Incomplete)
- Cash discrepancies per transaction
- Risk ratings assigned per control

The data was anonymized and cleaned to protect confidentiality.

## 🧮 Key Metrics & Dimensions

**Metrics:**
- % of Control Tests Passed
- % of High-Risk Control Tests
- % of Transactions with Cash Differences
- No. of Incomplete Audit Records
- Total Amount of Cash Discrepancies

**Dimensions:**
- Site Name
- Reviewer Name
- Control ID
- Audit Period
- Country
- Risk Rating
- Control Type
- Outcome (Compliant, With Issues, Not Yet Started)

## 📌 Summary of Insights

Here are the key takeaways derived from the dashboard:

1. **Overall Control Test Pass Rate:** 64.36%  
   Indicates the general level of compliance across all audit controls.

2. **Most Common Risk Rating:** HIGH  
   Helps prioritize audit efforts and focus areas.

3. **Site with the Highest Cash Discrepancy (By Amount):** Tyr with USD -27,980.00  
   Flagging financial control breakdowns.

4. **Reviewer with Highest Audit Load:** Frank Hayashi with 41,119 tests  
   May suggest workload imbalances.

5. **Control Most Often Failed:** CTMRR.DOCQ with 86,967 WITH ISSUES outcomes  
   Highlights critical control points for review or redesign.

## 💡 Why This Matters to the Client

This dashboard empowers internal audit teams and leadership with:

- **Improved Risk Visibility:** Quickly identify high-risk areas across geographies.
- **Audit Resource Management:** Understand reviewer workloads and spot potential overloads.
- **Targeted Interventions:** Focus on sites, reviewers, or control types needing improvement.
- **Better Decision-Making:** Data-driven insights for prioritizing follow-up actions.

## ✅ Recommendations & Next Steps

- Investigate sites with large cash discrepancies, even if few in number.
- Review control types with frequent failures for potential process improvements.
- Balance audit reviewer workloads for consistency and effectiveness.
- Consider implementing automated monitoring for high-risk countries or reviewers.

## 🛠 Tools Used

- **Excel** – Data cleaning and preparation  
- **Tableau** – Data visualization and dashboard building  
- **GitHub** – Version control and portfolio hosting

---

