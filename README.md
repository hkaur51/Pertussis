Secondary data analysis of Gill et. al cohort data of mother-infant pairs from Zambia with bi-monthly nasal swabs and PCR testing for pertussis DNA: 

# Estimating Symptom Severity and Age of First Pertussis Infection in Infancy: Parameters for the Pertussis Force of Infection Model

## Overview
This project estimates the proportion of pertussis infections that progress to mild, moderate, or severe disease in infants, stratified by vaccination status. These estimates serve as input parameters for the pertussis force-of-infection (FOI) model, which translates population-level infections into disease burden and mortality.
Most pertussis studies are hospital-based and capture only symptomatic cases, missing asymptomatic and subclinical infections. To obtain a true denominator of all infections, we conducted a secondary analysis of the **SAMIPS (South Africa Mother Infant Pertussis Study)** birth cohort — a prospective study of 1,320 infants with repeated nasopharyngeal sampling regardless of symptoms.

## Key Findings

- 34.4% of infants (454/1,320) had ≥1 positive molecular detection; 13.4% (177/1,320) had ≥3 positive detections (strong evidence of infection)
- Among strongly infected infants, ~24% were asymptomatic despite confirmed pertussis DNA detection across all vaccination strata
- The 1–2 month age period had the highest incidence of first infection (5.4%)
- The only severe case (MPS score of 18) occurred in an unvaccinated neonate
- Vaccination was associated with modestly lower incidence rates across comparable age groups

## Data Source
This analysis uses data from the SAMIPS cohort, originally described in:

Gill CJ et al. (2016). Incidence of Severe and Nonsevere Pertussis Among HIV-Exposed and -Unexposed Zambian Infants. Clin Infect Dis. 63, S154–S164.
Gill CJ et al. (2021). Asymptomatic Bordetella pertussis infections in a longitudinal cohort of young African infants and their mothers. eLife 10, e65663.


Note: The raw SAMIPS data is not included in this repository. Please visit the original study url to for data access.

## Methods Summary

- Infection classification: Infants classified by evidence of infection (EFI) — ≥1 or ≥3 positive molecular detections based on quantitative PCR cycle threshold (CT) values
- Vaccination status: Assigned as unvaccinated, recently vaccinated (1 dose, 14–28 days post), or vaccinated (1 dose, >28 days post) at time of first infection (or last visit for uninfected)
- Symptom severity: Worst symptoms during follow-up categorized as none, mild (cough/coryza), moderate (Modified Preziosi Scale), or severe (whooping/paroxysmal cough)
- Age groups: Neonates (0–28 days), 1–2 months (29–59 days), 2+ months (≥60 days)

## Limitations

- Symptom severity reflects worst symptoms during the entire study, not necessarily concurrent with the infection episode
- Age of first infection is estimated within a 7–21 day window due to biweekly sampling
- Symptomatic infants may have had more samples collected (illness visits), potentially inflating their representation among strongly infected cases
