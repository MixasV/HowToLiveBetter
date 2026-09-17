# Section 2 Source Verification Record

Verification method: all sources were opened via WebFetch as Europe PMC REST records (`<https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=DOI:<doi>&resultType=core&format=json>`, and in a few cases queried with `TITLE:` or `EXT_ID:<pmid> AND SRC:MED`); the records contain the title, authors, journal, year, DOI, PMID, and full abstract, and the cited figures are all in the abstracts. The PubMed web version returned a cookie interception page to WebFetch, and doi.org returned a 302 after which the publisher page (NEJM) returned 403, so the Europe PMC records were treated as authoritative. DOIs were entered uniformly according to the Europe PMC records (among them, the DOI for the Aune 2016 nuts paper is actually `10.1186/s12916-016-0730-3`; the `-0730-5` in my original memory was wrong, and that paper was ultimately not included in the main text).

## Item 1 Smoking cessation
- <https://doi.org/10.1056/NEJMsa1211128> — confirmed: Jha P et al., NEJM 2013, PMID 23343063. Abstract original text: "Life expectancy was shortened by more than 10 years among the current smokers"; "Adults who had quit smoking at 25 to 34, 35 to 44, or 45 to 54 years of age gained about 10, 9, and 6 years of life, respectively"; "Cessation before the age of 40 years reduces the risk of death associated with continued smoking by about 90%."
- <https://doi.org/10.1016/S0140-6736(15)00340-2> — confirmed: Chen Z et al., Lancet 2015, PMID 26466050. Abstract original text: urban men "RR 1·32 [95% CI 1·24-1·41] vs 1·65 [1·53-1·79]" (1990s vs 2010s), rural men "RR 1·13 [1·09-1·17] vs 1·22 [1·16-1·29]"; "Ex-smokers who had stopped by choice…had little smoking-attributed risk more than 10 years after stopping."
- <https://doi.org/10.1016/S0140-6736(10)61388-8> — confirmed: Oberg M et al., Lancet 2011, PMID 21112082. Abstract original text: "603,000 deaths were attributable to second-hand smoke in 2004, which was about 1·0% of worldwide mortality."

## Item 2 Sugar-sweetened beverages
- <https://doi.org/10.1161/CIRCULATIONAHA.118.037401> — confirmed: Malik VS et al., Circulation 2019, PMID 30882235. Abstract original text: categories "(<1/mo, 1-4/mo, 2-6/week, 1-<2/d, and ≥2/d) were 1.00 (reference), 1.01 (0.98, 1.04), 1.06 (1.03, 1.09), 1.14 (1.09, 1.19), and 1.21 (1.13, 1.28)"; 37,716 men and 80,647 women, "36 436 deaths". The abstract did not give the HR per serving/day, and the main text did not cite it.
- <https://doi.org/10.1001/jamainternmed.2019.2478> — confirmed: Mullee A et al., JAMA Intern Med 2019. Abstract original text: total soft drinks "HR, 1.17; 95% CI, 1.11-1.22"; sugar-sweetened "HR, 1.08; 95% CI, 1.01-1.16"; artificially sweetened "HR, 1.26; 95% CI, 1.16-1.35"; 451,743 participants.

## Item 3 Low-sodium salt
- <https://doi.org/10.1056/NEJMoa2105675> — confirmed: Neal B et al., NEJM 2021, PMID 34459569. Abstract original text: 20,995 participants, mean follow-up 4.74 years; stroke "rate ratio, 0.86"; major cardiovascular events "rate ratio, 0.87"; death "39.28 events vs. 44.61 events per 1000 person-years; rate ratio, 0.88"; hyperkalemia rate ratio 1.04, no significant difference.
- <https://doi.org/10.1056/NEJMoa1311889> — confirmed: O'Donnell M et al., NEJM 2014, PMID 25119607. Abstract original text: "≥ 7.00 g per day…odds ratio, 1.15; 95% CI, 1.02 to 1.30"; "below 3.00 g per day…odds ratio, 1.27; 95% CI, 1.12 to 1.44".

## Item 4 Step count
- <https://doi.org/10.1016/S2468-2667(21)00302-9> — confirmed: Paluch AE et al., Lancet Public Health 2022, PMID 35247352. Abstract original text: "47 471 adults, among whom there were 3013 deaths"; "Quartile median steps per day were 3553 for quartile 1, 5801 for quartile 2, 7842 for quartile 3, and 10 901 for quartile 4"; "adjusted HR for all-cause mortality was 0·60 (95% CI 0·51-0·71) for quartile 2, 0·55 (0·49-0·62) for quartile 3, and 0·47 (0·39-0·57) for quartile 4"; ≥60 years "6000-8000 steps per day", <60 years "8000-10 000 steps per day".
- <https://doi.org/10.1093/eurjpc/zwad229> — confirmed: Banach M et al., Eur J Prev Cardiol 2023, PMID 37555441. Abstract original text: "A 1000-step increment was associated with a 15% decreased risk of all-cause mortality"; "the cut-off point of 3867 steps/day for all-cause mortality".

## Item 5 Adherence to antihypertensive/lipid-lowering medication
- <https://doi.org/10.1016/S0140-6736(15)01225-8> — confirmed: Ettehad D et al., Lancet 2016, PMID 26724178. Abstract original text: major cardiovascular events "RR 0·80, 95% CI 0·77-0·83"; stroke "0·73, 0·68-0·77"; heart failure "0·72, 0·67-0·78"; "13% reduction in all-cause mortality (0·87, 0·84-0·91)".
- <https://doi.org/10.1016/S0140-6736(10)61350-5> — confirmed: CTT Collaboration, Lancet 2010, PMID 21067804. Abstract original text: major vascular events "rate ratio [RR] 0·78, 95% CI 0·76–0·80"; "all-cause mortality was reduced by 10% per 1·0 mmol/L LDL reduction (RR 0·90, 95% CI 0·87–0·93)".
- <https://doi.org/10.1093/eurheartj/eht295> — confirmed: Chowdhury R et al., Eur Heart J 2013, PMID 23907142. Abstract original text: "Corresponding RRs of all-cause mortality were 0.55 (0.46-0.67) and 0.71 (0.64-0.78) for good adherence to statins and antihypertensive agents"; good vs poor (<80%) adherence.

## Item 6 Sleep
- <https://doi.org/10.1093/sleep/33.5.585> — confirmed: Cappuccio FP et al., Sleep 2010, PMID 20469800. Abstract original text: "16 studies…1,382,999 male and female participants…112,566 deaths"; short "RR: 1.12; 95% CI 1.06 to 1.18"; long "1.30; [1.22 to 1.38]". The abstract did not give the definitions of short/long hours, and the main text did not write specific thresholds.
- <https://doi.org/10.1161/JAHA.117.005947> — confirmed: Yin J et al., JAHA 2017, PMID 28889101. Abstract original text: <7 h "RR was 1.06 (95% CI, 1.04-1.07) per 1-hour reduction"; >7 h "RR was 1.13 (95% CI, 1.11-1.15) per 1-hour increment".
- <https://doi.org/10.1093/sleep/zsad253> — confirmed: Windred DP et al., Sleep 2024, PMID 37738616. Abstract original text: "60 977 UK Biobank participants"; "1859" deaths; "Higher sleep regularity was associated with a 20%-48% lower risk of all-cause mortality" (top four SRI quintiles vs least regular quintile); "Sleep regularity was a stronger predictor of all-cause mortality than sleep duration".

## Item 7 Moderate-intensity exercise
- <https://doi.org/10.1001/jamainternmed.2015.0533> — confirmed: Arem H et al., JAMA Intern Med 2015, PMID 25844730. Abstract original text: less than 7.5 MET-h/week "HR, 0.80 [95% CI, 0.78-0.82]"; 1 to 2 times "HR, 0.69 [95% CI, 0.67-0.70]"; 2 to 3 times "HR, 0.63"; 3 to 5 times "HR, 0.61 [95% CI, 0.59-0.62]"; 10 or more times "HR, 0.69 [95% CI, 0.59-0.78]".
- <https://doi.org/10.1136/bmj.l4570> — confirmed: Ekelund U et al., BMJ 2019, PMID 31434697. Abstract original text: MVPA quartile HR "1.00, 0.64 (0.55–0.74), 0.55 (0.40–0.74), and 0.52 (0.43–0.61)"; total PA highest quartile "0.27 (0.23 to 0.32)".

## Item 8 Strength training
- <https://doi.org/10.1136/bjsports-2021-105061> — confirmed: Momma H et al., Br J Sports Med 2022, PMID 35228201. Abstract original text: "Muscle-strengthening activities were associated with a 10-17% lower risk of all-cause mortality"; "J-shaped associations with the maximum risk reduction (approximately 10-20%) at approximately 30-60 min/week"; "Combined muscle-strengthening and aerobic activities (versus none) were associated with a lower risk of all-cause…mortality".

## Item 9 Sedentary behavior
- <https://doi.org/10.7326/M17-0212> — confirmed: Diaz KM et al., Ann Intern Med 2017, PMID 28892811. Abstract original text: total sedentary time highest vs lowest quartile "HR, 2.63 [CI, 1.60 to 4.30]"; bout duration "HR, 1.96 [CI, 1.31 to 2.93]"; conclusion "both the total volume of sedentary time and its accrual in prolonged, uninterrupted bouts are associated with all-cause mortality". The abstract did not mention a 30-minute threshold, and the main text heading did not state a specific number of minutes.
- <https://doi.org/10.1016/S0140-6736(16)30370-1> — confirmed: Ekelund U et al., Lancet 2016, PMID 27475271. Abstract original text: referent "those sitting <4 h/day and in the most active quartile [>35·5 MET-h per week]"; lowest PA quartile + sitting >8 h/day "HR=1·59, 1·52-1·66"; most active + >8 h "HR=1·04; 95% CI 0·99-1·10"; "about 60-75 min per day…seem to eliminate the increased risk of death associated with high sitting time"; TV ≥5 h in most active "HR=1·16, 1·05-1·28".

## Item 10 Processed meat
- <https://doi.org/10.1093/aje/kwt261> — confirmed: Larsson SC, Orsini N, Am J Epidemiol 2014, PMID 24148709. Abstract original text (highest vs lowest): unprocessed red meat "1.10 (95% CI: 0.98, 1.22)"; processed meat "1.23 (95% CI: 1.17, 1.28)"; total red meat "1.29 (95% CI: 1.24, 1.35)".
- <https://doi.org/10.3945/ajcn.117.153148> — confirmed: Schwingshackl L et al., Am J Clin Nutr 2017, PMID 28446499. Abstract original text (per serving/day): whole grains "RR: 0.92; 95% CI: 0.89, 0.95"; red meat "RR: 1.10; 95% CI: 1.04, 1.18"; processed meat "RR: 1.23; 95% CI: 1.12, 1.36".
- <https://doi.org/10.7326/M19-1621> — confirmed: Johnston BC et al., Ann Intern Med 2019, PMID 31569235. Abstract original text: "continue current unprocessed red meat consumption (weak recommendation, low-certainty evidence)"; "continue current processed meat consumption (weak recommendation, low-certainty evidence)".

## Item 11 Alcohol
- <https://doi.org/10.1016/S0140-6736(18)30134-X> — confirmed: Wood AM et al., Lancet 2018, PMID 29676281. Abstract original text: "the minimum mortality risk around or below 100 g per week"; life expectancy at age 40: >100–≤200 g/week "approximately 6 months", >200–≤350 g/week "1–2 years", >350 g/week "4–5 years".
- <https://doi.org/10.1016/S0140-6736(18)31310-2> — confirmed: GBD 2016 Alcohol Collaborators, Lancet 2018. Abstract original text: "The level of alcohol consumption that minimised harm across health outcomes was zero (95% UI 0·0-0·8) standard drinks per week."
- <https://doi.org/10.1001/jamanetworkopen.2023.6185> — confirmed: Zhao J et al., JAMA Netw Open 2023, PMID 37000449. Abstract original text: "low-volume drinkers (1.3-24.0 g per day; RR, 0.93; P = .07) compared with lifetime nondrinkers"; "45 to 64 and 65 or more grams per day (RR, 1.19 and 1.35; P < .001)".
- <https://doi.org/10.1001/archinte.166.22.2437> — confirmed: Di Castelnuovo A et al., Arch Intern Med 2006, PMID 17159008. Abstract original text: "maximum protection being 18% in women (99% confidence interval, 13%-22%) and 17% in men"; "up to 4 drinks per day in men and 2 drinks per day in women, was inversely associated with total mortality".

## Item 12 Whole grains
- <https://doi.org/10.1136/bmj.i2716> — confirmed: Aune D et al., BMJ 2016, PMID 27301975. Abstract original text: per 90 g/day "0.83 (0.77 to 0.90; I(2)=83%, n=11) for all causes"; "Reductions in risk were observed up to an intake of 210-225 g/day".
- Schwingshackl 2017, same as item 10 (whole grains RR 0.92).

## Item 13 Fruits and vegetables
- <https://doi.org/10.1093/ije/dyw319> — confirmed: Aune D et al., Int J Epidemiol 2017, PMID 28338764. Abstract original text: "the summary RR per 200 g/day was…0.90 (95% CI: 0.87-0.93…for all-cause mortality"; "Reductions in risk were observed up to 800 g/day for all outcomes except cancer (600 g/day)".
- <https://doi.org/10.1161/CIRCULATIONAHA.120.048996> — confirmed: Wang DD et al., Circulation 2021, PMID 33641343. Abstract original text: "daily intake of 5 servings of fruit and vegetables was associated with hazard ratios (95% CI) of 0.87 (0.85-0.90) for total mortality" (versus 2 servings/day); "≈5 servings per day of fruit and vegetables, or 2 servings of fruit and 3 servings of vegetables, was associated with the lowest mortality".

## Item 14 Ultra-processed foods
- <https://doi.org/10.1136/bmj-2023-077310> — confirmed: Lane MM et al., BMJ 2024, PMID 38418082. Abstract original text: "all cause mortality (risk ratio 1.21, 1.15 to 1.27; low)" class II highly suggestive; "cardiovascular disease related mortality (risk ratio 1.50, 95% confidence interval 1.37 to 1.63; GRADE=very low)" class I convincing.

## Item 15 Indoor combustion / PM2.5
- <https://doi.org/10.1001/jama.2018.2151> — confirmed: Yu K et al., JAMA 2018, PMID 29614179. Abstract original text: 271,217 adults; cooking solid fuel all-cause "HR, 1.11 [95% CI, 1.03-1.20]"; heating "HR, 1.14 [95% CI, 1.03-1.26]"; switched (cooking) "HR, 0.87 [95% CI, 0.79-0.95]"; switched (heating) "HR, 0.67 [95% CI, 0.57-0.79]".
- <https://doi.org/10.1016/j.envint.2020.105974> — confirmed: Chen J, Hoek G, Environ Int 2020, PMID 32703584. Abstract original text: "The combined Risk Ratio (RR) for PM₂.₅ and natural-cause mortality was 1.08 (95%CI 1.06, 1.09) per 10 µg/m³", 104 cohort studies.

## Item 16 Body weight
- <https://doi.org/10.1016/S0140-6736(16)30175-1> — confirmed: Global BMI Mortality Collaboration, Lancet 2016, PMID 27423262. Abstract original text: "All-cause mortality was minimal at 20·0-25·0 kg/m(2)"; 25.0-27.5 "1·07, 1·07-1·08"; 27.5-30.0 "1·20, 1·18-1·22"; 30.0-35.0 "1·45, 95% CI 1·41-1·48"; 35.0-40.0 "1·94, 1·87-2·01"; 40.0-60.0 "2·76, 2·60-2·92"; East Asia per 5 kg/m² "1·39 (1·34-1·44)"; analysis restricted to "never-smokers without chronic diseases at recruitment who survived 5 years".
- <https://doi.org/10.1001/jama.2012.113905> — confirmed: Flegal KM et al., JAMA 2013, PMID 23280227. Abstract original text: "The summary HRs were 0.94 (95% CI, 0.91-0.96) for overweight, 1.18 (95% CI, 1.12-1.25) for obesity (all grades combined), 0.95 (95% CI, 0.88-1.01) for grade 1 obesity, and 1.29 (95% CI, 1.18-1.41) for grades 2 and 3 obesity."

## Verified but not included in the main text
- Aune D et al. (2016) nuts, BMC Medicine, <https://doi.org/10.1186/s12916-016-0730-3>, PMID 27916000: per 28 g/day ACM "0.78 (95% CI: 0.72-0.84)". The effect size was suspected of being amplified by confounding and it costs money every day; it was not included in order to keep the number of items under control (16-item limit).
- Sofi F et al. (2010) Mediterranean diet, Am J Clin Nutr, <https://doi.org/10.3945/ajcn.2010.29673>, PMID 20810976: 2-point increase "RR = 0.92; 95% CI: 0.90, 0.94". Overlaps with items 10, 12, and 13; not included.
- Holt-Lunstad J et al. (2010) PLoS Med, <https://doi.org/10.1371/journal.pmed.1000316>, PMID 20668659: "OR = 1.50 (95% CI 1.42 to 1.59)"; Holt-Lunstad J et al. (2015) Perspect Psychol Sci, <https://doi.org/10.1177/1745691614568352>, PMID 25910392: "social isolation odds ratio (OR) = 1.29, loneliness OR = 1.26, and living alone OR = 1.32". The social isolation effect is large, but reverse causation is heavy and there is no intervention evidence; it was not included in order to keep the number of items under control; if needed, it can be added directly as item 17.

## Unconfirmed items
- None. All figures in the main text come from the records opened above. The "cost" column in the main text (price, time) consists of the author's estimates and does not cite literature.