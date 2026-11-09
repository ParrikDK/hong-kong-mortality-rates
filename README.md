# Hong Kong Mortality Rates (2000–2025): (1) Age-specific (2) Crude vs WHO Age-standardised 

Data: Hong Kong Census and Statistics Department (C&SD): [Table 110-01001 *Population by sex and age group*](https://www.censtatd.gov.hk/en/web_table.html?id=110-01001) (released 18 August 2026) and [Table 115-01022 *Deaths by sex and age group*](https://www.censtatd.gov.hk/en/web_table.html?id=115-01022) (released 2 October 2026). The xlsx files, should you choose to replicate this, are in `raw/`. [World Health Organization's (WHO) World Standard Population](https://seer.cancer.gov/stdpopulations/world.who.html).

Aim: To show my logic and how I clean messy data. I intentionally chose to download the '.xlsx' files to show how I deal with the spaces from the unmerged excel cells and tidy data.

Takeaway results: Hong Kong's 2025 crude death rate (about **686 per 100k**) is almost thrice its age-standardised rate (about **243 per 100k**), mostly because about **23.8%** of Hong Kong's population is **aged 65 or over**, compared to just **8.2%** under WHO's World Standard population. Reweighting adjusts for Hong Kong's older demographic structure.

*Data notes
- Deaths are counted by when they occurred not when it was registered.
- 'Both sexes' rows also include deaths of unknown sex.
- 'Unknown' age deaths are in the crude rate but cannot enter age-specific or age-standardised rates.
- Used the mid-year population counts, rather than end-year, to better approximate during that year.
- From WHO Age-standardisation, ages 85 and over were combined, to match the 18 age groups in Hong Kong datasets.