# Section 6 Source Verification Record

Explanation of verification method: doi.org all returned 302 redirects; the publisher pages of JAMA/NEJM/Elsevier/Wiley/ACP/RSNA/Nature returned 403 to WebFetch, and PubMed pages returned only cookie notices. Therefore the abstract texts were verified uniformly through the official Europe PMC REST interface (`<https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=DOI:<doi>&resultType=core&format=json`, which returns bibliographic records and abstractText from the same source as PubMed); in a few cases NCBI E-utilities efetch was used. The "actually opened URL" below is the address from which WebFetch successfully returned content during verification. All DOIs correspond one-to-one with the title/authors/year in the bibliographic records returned by Europe PMC.

## Item 1 Multivitamins

- Source A: Sesso HD et al. 2012 JAMA, DOI 10.1001/jama.2012.14805
  - Actually opened: Europe PMC REST (DOI query). Title matches "Multivitamins in the prevention of cardiovascular disease in men: the Physicians' Health Study II randomized controlled trial", 2012, JAMA. Confirmed.
  - Source of cited figures (abstract): "14,641 male US physicians"; "median follow-up 11.2 years"; "major cardiovascular events … HR, 1.01; 95% CI, 0.91-1.10; P = .91"; "total mortality … HR, 0.94; 95% CI, 0.88-1.02; P = .13"
- Source B: USPSTF 2022 JAMA, DOI 10.1001/jama.2022.8970
  - Actually opened: <https://jamanetwork.com/journals/jama/fullarticle/2793446> (the doi.org redirect target, scraped successfully). Title matches "Vitamin, Mineral, and Multivitamin Supplementation to Prevent Cardiovascular Disease and Cancer: US Preventive Services Task Force Recommendation Statement", 2022, JAMA 327(23). Confirmed.
  - Source of cited figures: "Multivitamin trials reviewed: 9 RCTs involving 51,550 participants showed no association between multivitamin supplementation and all-cause mortality"; multivitamin rating I; beta carotene/vitamin E rating D ("recommends against the use of beta carotene or vitamin E supplements for the prevention of cardiovascular disease or cancer"); beta carotene "Increased lung cancer risk (RR 1.18) in smokers/asbestos-exposed workers" (this section does not directly cite the figure 1.18).
- Counterpoint in the note: Gaziano JM et al. 2012 JAMA, DOI 10.1001/jama.2012.14641
  - Actually opened: <https://pubmed.ncbi.nlm.nih.gov/?term=10.1001%2Fjama.2012.14641> (this PubMed scrape successfully returned the abstract). Title matches "Multivitamins in the prevention of cancer in men: the Physicians' Health Study II randomized controlled trial". Confirmed.
  - Source of cited figures: "hazard ratio [HR], 0.92; 95% CI, 0.86-0.998; P=.04"; "HR, 0.88; 95% CI, 0.77-1.01; P=.07"

## Item 2 Fish oil

- Manson JE et al. 2019 NEJM, DOI 10.1056/NEJMoa1811403
  - Actually opened: Europe PMC REST (DOI query). Title matches "Marine n-3 Fatty Acids and Prevention of Cardiovascular Disease and Cancer", 2019, NEJM. Confirmed.
  - Source of cited figures: "25,871 participants"; "1 g/day"; "median follow-up of 5.3 years"; "major cardiovascular events … hazard ratio, 0.92; 95% CI, 0.80 to 1.06; P=0.24"; "Death from any cause … hazard ratio was 1.02 (95% CI, 0.90 to 1.15)"
- ASCEND Study Collaborative Group 2018 NEJM, DOI 10.1056/NEJMoa1804989
  - Actually opened: Europe PMC REST. Title matches "Effects of n-3 Fatty Acid Supplements in Diabetes Mellitus", 2018, NEJM. Confirmed.
  - Source of cited figures: "15,480 patients with diabetes without atherosclerotic cardiovascular disease"; "1-gram capsules daily"; "Mean 7.4 years"; "rate ratio, 0.97; 95% CI, 0.87 to 1.08; P=0.55"; "All-cause mortality: rate ratio, 0.95; 95% CI, 0.86 to 1.05"
- Counterpoint: Bhatt DL et al. 2019 NEJM, DOI 10.1056/NEJMoa1812792
  - Actually opened: <https://eutils.ncbi.nlm.nih.gov/entrez/eutils/efetch.fcgi?db=pubmed&id=30415628&rettype=abstract&retmode=text> (the Europe PMC record had no abstractText, so NCBI efetch was used instead). Title matches "Cardiovascular Risk Reduction with Icosapent Ethyl for Hypertriglyceridemia", REDUCE-IT Investigators, NEJM 2019 (PMID 30415628). Confirmed.
  - Source of cited figures: "hazard ratio was 0.75 (95% CI, 0.68–0.83; P<0.001)"; "17.2% of the icosapent ethyl group versus 22.0% of the placebo group"; "2 g of icosapent ethyl twice daily (total daily dose, 4 g)"; "established cardiovascular disease or diabetes … statin therapy, fasting triglycerides of 135–499 mg/dL"; "8,179 patients"

## Item 3 Vitamin D

- Manson JE et al. 2019 NEJM, DOI 10.1056/NEJMoa1809944
  - Actually opened: Europe PMC REST. Title matches "Vitamin D Supplements and Prevention of Cancer and Cardiovascular Disease", 2019, NEJM. Confirmed.
  - Source of cited figures: "2000 IU daily"; "25,871"; "Median 5.3 years"; "Invasive cancer: hazard ratio, 0.96; 95% CI, 0.88 to 1.06; P=0.47"; "Major cardiovascular events: hazard ratio, 0.97; 95% CI, 0.85 to 1.12; P=0.69"; "Death from any cause: hazard ratio was 0.99 (95% CI, 0.87 to 1.12)"
- Neale RE et al. 2022 Lancet Diabetes Endocrinol, DOI 10.1016/S2213-8587(21)00345-4
  - Actually opened: Europe PMC REST (a query by DOI returned nothing, so a query by TITLE:"D-Health Trial" AND AUTH:Neale was used; the DOI field of the returned record was 10.1016/S2213-8587(21)00345-4, consistent with the DOI written). Title matches "The D-Health Trial: a randomised controlled trial of the effect of vitamin D on mortality", 2022. Confirmed.
  - Source of cited figures: "21 315 participants, including 10 662 to the vitamin D group and 10 653 to the placebo group"; "60 000 IU per month for 5 years"; "1100 deaths were recorded (placebo 538 [5·1%]; vitamin D 562 [5·3%])"; "HR … 1.04 [95% CI 0·93 to 1·18]; p=0·47"; "median follow-up 5·7 years"; "Australians 60 years or older who were recruited across the country via the Commonwealth electoral roll" (confirmed verbatim in a second retrieval; the main text accordingly writes "over 60 years old" and does not write a specific upper limit).

## Item 4 Antioxidant supplements

- Bjelakovic G et al. 2012 Cochrane, DOI 10.1002/14651858.CD007176.pub2
  - Actually opened: Europe PMC REST. Title matches "Antioxidant supplements for prevention of mortality in healthy participants and patients with various diseases", 2012, Cochrane Database Syst Rev. Confirmed.
  - Source of cited figures: "78 trials, 296,707 participants"; "RR 1.02, 95% CI 0.98 to 1.05 (random-effects)"; "Low risk of bias trials (56 trials, 244,056 participants): RR 1.04, 95% CI 1.01 to 1.07"; "Beta-carotene: RR 1.05, 95% CI 1.01 to 1.09"; "Vitamin E: RR 1.03, 95% CI 1.00 to 1.05"
- ATBC Study Group 1994 NEJM, DOI 10.1056/NEJM199404143301501
  - Actually opened: Europe PMC REST. Title matches "The effect of vitamin E and beta carotene on the incidence of lung cancer and other cancers in male smokers", 1994, NEJM. Confirmed.
  - Source of cited figures: "29,133 male smokers"; "20 mg per day"; "change in incidence, 18 percent; 95 percent confidence interval, 3 to 36 percent"; "8 percent higher (95 percent confidence interval, 1 to 16 percent)"
- Omenn GS et al. 1996 NEJM, DOI 10.1056/NEJM199605023341802
  - Actually opened: Europe PMC REST. Title matches "Effects of a combination of beta carotene and vitamin A on lung cancer and cardiovascular disease", 1996, NEJM. Confirmed.
  - Source of cited figures: "18,314 smokers, former smokers, and asbestos-exposed workers"; "relative risk of lung cancer of 1.28 (95 percent confidence interval, 1.04 to 1.57; P=0.02)"; "relative risk of death from any cause was 1.17 (95 percent confidence interval, 1.03 to 1.33)"
- USPSTF grade D in the note: same as item 1 source B, confirmed.

## Item 5 Glucosamine/chondroitin

- Clegg DO et al. 2006 NEJM, DOI 10.1056/NEJMoa052771
  - Actually opened: Europe PMC REST. Title matches "Glucosamine, chondroitin sulfate, and the two in combination for painful knee osteoarthritis", 2006, NEJM. Confirmed.
  - Source of cited figures: "1,583 patients"; "placebo (60.1%)"; "Glucosamine: 3.9 percentage points higher (P=0.30)"; "Chondroitin sulfate: 5.3 percentage points higher (P=0.17)"; "Combined treatment: 6.5 percentage points higher (P=0.09)"; "Celecoxib: 10.0 percentage points higher (P=0.008)"; "moderate-to-severe pain at baseline … 79.2 percent vs. 54.3 percent, P=0.002"; a second retrieval confirmed verbatim "… or placebo for 24 weeks" and "Exploratory analyses suggest that the combination of glucosamine and chondroitin sulfate may be effective in the subgroup of patients with moderate-to-severe knee pain".

## Item 6 Vitamin C

- Hemilä H, Chalker E 2013 Cochrane, DOI 10.1002/14651858.CD000980.pub4
  - Actually opened: Europe PMC REST. Title matches "Vitamin C for preventing and treating the common cold", 2013. Confirmed.
  - Source of cited figures: "pooled RR was 0.97 (95% confidence interval (CI) 0.94 to 1.00)"; "29 trial comparisons with 11,306 participants"; "In adults, colds shortened by 8% (3% to 12%); in children by 14% (7% to 21%)"; "No consistent effect of vitamin C was seen on the duration or severity of colds in the therapeutic trials". The figure for the extreme-physical-stress population in the note comes from a sentence confirmed verbatim in a second retrieval: "Five trials involving a total of 598 marathon runners, skiers and soldiers on subarctic exercises yielded a pooled RR of 0.48 (95% CI 0.35 to 0.64)".

## Item 7 Whole-body PET-CT / tumor markers

- USPSTF 2018 JAMA, DOI 10.1001/jama.2017.21926
  - Actually opened: <https://pubmed.ncbi.nlm.nih.gov/29450531/> (this retrieval returned successfully). Title matches "Screening for Ovarian Cancer: US Preventive Services Task Force Recommendation Statement", 2018, JAMA, DOI 10.1001/jama.2017.21926. Confirmed. (The DOI I initially recorded, 10.1001/jama.2018.0938, was wrong; I used WebSearch to find the correct DOI and verified it.)
  - Actually opened: <https://www.uspreventiveservicestaskforce.org/uspstf/recommendation/ovarian-cancer-screening>. Confirmed.
  - Source of cited figures (verbatim from the official page): "No difference was found in ovarian cancer mortality … with 0.34% in the screening group and 0.29% in the usual care group (relative risk, 1.18 [95% CI, 0.82 to 1.71])"; "Surgery to investigate positive screening test results among women who ultimately did not have ovarian cancer occurred in 0.2% of participants in the UK Pilot CA-125 group, 0.97% … 3.25% of participants in the UKCTOCS ultrasound group, and 3.17% of participants in the PLCO CA-125 plus ultrasound group"; "Up to 15% of these women had major surgical complications"
- Furtado CD et al. 2005 Radiology, DOI 10.1148/radiol.2372041741
  - Actually opened: Europe PMC REST. Title matches "Whole-body CT screening: spectrum of findings and recommendations in 1192 patients", 2005, Radiology. Confirmed.
  - Source of cited figures: "1030 (86%) of 1192 subjects had at least one abnormal finding"; "Four hundred forty-five (37%) patients received at least one recommendation for additional evaluation"; "most findings were benign by description and required no further evaluation"

## Item 8 Smart bracelets

- Jakicic JM et al. 2016 JAMA, DOI 10.1001/jama.2016.12858
  - Actually opened: Europe PMC REST. Title matches "Effect of Wearable Technology Combined With a Lifestyle Intervention on Long-term Weight Loss: The IDEA Randomized Clinical Trial", 2016, JAMA. Confirmed.
  - Source of cited figures: "estimated mean weight loss, 3.5 kg [95% CI, 2.6-4.5] in the enhanced intervention group and 5.9 kg [95% CI, 5.0-6.8] in the standard intervention group; difference, 2.4 kg [95% CI, 1.0-3.7]; P = .002"; "471 randomized participants"

## Item 9 Organic food

- Smith-Spangler C et al. 2012 Ann Intern Med, DOI 10.7326/0003-4819-157-5-201209040-00007
  - Actually opened: Europe PMC REST. Title matches "Are organic foods safer or healthier than conventional alternatives?: a systematic review", 2012, Annals of Internal Medicine. Confirmed.
  - Source of cited figures: "17 studies in humans and 223 studies of nutrient and contaminant levels in foods met inclusion criteria"; "The published literature lacks strong evidence that organic foods are significantly more nutritious than conventional foods"; "risk difference, 30%" (pesticide residues); "Only 3 human studies examined clinical outcomes, finding no significant differences … for allergic outcomes or symptomatic infection". The abstract also has "antibiotic-resistant … risk difference, 33%", which this section does not cite. "Detection does not equal exceeding the standard" is my wording; the abstract original text is the risk difference for residue detection and does not mention the proportion exceeding the standard.

## Item 10 Health supplements

- State Administration for Market Regulation press conference page
  - Actually opened: <https://www.samr.gov.cn/tssps/sjdt/tpxw/art/2023/art_4b658b824b1b4b0ba57c09a56cc93aad.html>. Page title "市场监管总局就《保健食品标注警示用语指南》和《保健食品原料目录与保健功能目录管理办法》有关情况举办专题新闻发布会" ("SAMR holds a special press conference on the situation regarding the 'Guidelines for Warning Wording on Health Food Labels' and the 'Measures for the Administration of the Catalogue of Health Food Raw Materials and the Catalogue of Health Functions'"), press conference of August 20, 2019, samr.gov.cn official website. Confirmed.
  - Source of cited text: "保健食品不是药物，不能代替药物治疗疾病" ("Health food is not medicine and cannot replace medicine in treating disease"); "警示区面积不少于其所在版面的20%" ("The warning area shall be no less than 20% of the page on which it appears"); "补充膳食营养物质、维持改善机体健康状态或者降低疾病发生风险因素" ("Supplement dietary nutrients, maintain or improve the body's health status, or reduce risk factors for disease")
  - Unconfirmed: the original announcement page <https://gkml.samr.gov.cn/nsjg/tssps/201908/t20190820_306116.html> returned "Socket is closed" on four consecutive WebFetch attempts, and the gov.cn repost page returned 404, so the source only lists the successfully opened samr.gov.cn press conference page.

## Item 11 Probiotics

- Khalesi S et al. 2019 Eur J Clin Nutr, DOI 10.1038/s41430-018-0135-9
  - Actually opened: Europe PMC REST. Title matches "A review of probiotic supplementation in healthy adults: helpful or hype?", 2019, European Journal of Clinical Nutrition. Confirmed.
  - Source of cited text: "45" studies; "this review failed to support the ability of probiotics to cause persistent changes in gut microbiota, or improve lipid profile in healthy adults"; microbiota changes "transient"; indicators with small improvements "stool consistency, bowel movement, and vaginal lactobacilli concentration"

## Item 12 Cold showers

- Buijze GA et al. 2016 PLOS ONE, DOI 10.1371/journal.pone.0161749
  - Actually opened: <https://journals.plos.org/plosone/doi?id=10.1371/journal.pone.0161749>. Title matches "The Effect of Cold Showering on Health and Work: A Randomized Controlled Trial", 2016. Confirmed.
  - Source of cited figures: "3,018 individuals"; "30, 60, or 90 seconds"; "29% reduction … (IRR: 0.71, P = 0.003)"; "For illness days there was no significant group effect"; "no clinically relevant differences in quality of life, work productivity, anxiety"
- Cain T et al. 2025 PLOS ONE, DOI 10.1371/journal.pone.0317615
  - Actually opened: <https://journals.plos.org/plosone/doi?id=10.1371/journal.pone.0317615>. Title matches "Effects of cold-water immersion on health and wellbeing: A systematic review and meta-analysis", 2025. Confirmed.
  - Source of cited text: "Eleven randomized controlled trials encompassing 3,177 total participants"; "significant increases in inflammation immediately…and 1 hour post CWI"; "no meaningful immediate or delayed immune changes"; "a significant reduction in stress…12 hours post-CWI"; "current evidence base is constrained by few RCTs, small sample sizes"

## Item 13 Detox/alkaline

- Klein AV, Kiat H 2015 J Hum Nutr Diet, DOI 10.1111/jhn.12286
  - Actually opened: Europe PMC REST. Title matches "Detox diets for toxin elimination and weight management: a critical review of the evidence", 2015. Confirmed.
  - Source of cited text: "Although the detox industry is booming, there is very little clinical evidence to support the use of these diets"; "no randomised controlled trials have been conducted to assess the effectiveness of commercial detox diets in humans"
- Fenton TR, Huang T 2016 BMJ Open, DOI 10.1136/bmjopen-2015-010438
  - Actually opened: Europe PMC REST (DOI query). Title matches "Systematic review of the association between dietary acid load, alkaline water and cancer", 2016, BMJ Open. Confirmed. (The DOI I initially recorded, 10.1136/bmjopen-2016-010438, was wrong; doi.org returned 404; both WebSearch and Europe PMC gave 2015-010438, and it has been corrected accordingly.)
  - Source of cited text: "8278 citations were identified, and 252 abstracts were reviewed; 1 study met the inclusion criteria"; "no association between the diet acid load with bladder cancer (OR=1.15: 95% CI 0.86 to 1.55, p=0.36)"; "Promotion of alkaline diet and alkaline water to the public for cancer prevention or treatment is not justified"

## Item 14 Eight glasses of water a day

- Valtin H 2002 Am J Physiol Regul Integr Comp Physiol, DOI 10.1152/ajpregu.00365.2002
  - Actually opened: Europe PMC REST (journals.physiology.org returned 403). Title matches ""Drink at least eight glasses of water a day." Really? Is there scientific evidence for "8 x 8"?", Heinz Valtin, 2002. Confirmed.
  - Source of cited text: "No scientific studies were found in support of 8 x 8. Rather, surveys of food and fluid intake on thousands of adults…strongly suggest that such large amounts are not needed"

## Candidates considered but not included

- Oral collagen: existing meta-analyses are mostly small-sample and industry-funded, with a positive direction, which does not fit this section's criterion of "evidence shows ineffective", so it was not included.
- Air purifiers/water purifiers: not verified, and no hard-outcome evidence was found, so not included.
- Waking up early itself: difficult to separate from sleep regularity, and no direct controlled evidence was found, so not included.
- Multitasking/Pomodoro: no direct evidence, and per the requirements, not included.