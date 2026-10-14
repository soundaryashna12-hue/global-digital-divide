Global Digital Divide: Internet Access, 2010 to 2023

Analysis of World Bank/ITU indicators across 217 countries to show how
the digital divide is changing.

Live dashboard:
https://public.tableau.com/app/profile/soundarya.chikka.adugodi.mahesh/viz/GlobalDigitalDivide_17919226981800/Dashboard1

Data
- Mobile cellular subscriptions (per 100 people), ITU
- Fixed broadband subscriptions (per 100 people), ITU
- Secure internet servers (per 1 million people), Netcraft / World Bank
- Source: World Bank Open Data, 2010 to 2023

Method
- Reshaped the World Bank wide-format files to one row per country per year
- Joined the three indicators with region and income group metadata
- Removed regional and income aggregates, leaving 217 countries
- Flagged countries missing 50% or more of years; used medians for group results

 Key findings
1. Mobile has narrowed the access gap between high- and low-income countries.
2. Fixed broadband is pulling apart: the gap grew while low-income countries stay near zero.
3. Secure server hosting is concentrated in a few regions and hubs.

Files
- `digital_divide_analysis.ipynb`: cleaning and analysis
- `cleaned_2010_2023.csv`: analysis-ready data
- `Digital_Divide_Stakeholder_Summary.docx`: one-page summary
