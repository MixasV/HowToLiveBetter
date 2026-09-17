# Addendum: Eye Stroke, Pulmonary Embolism, Chronic Subdural Hematoma, and Painless Hematuria · Verification Record (2026-09-08)

Task source: after the previous round (posterior circulation stroke, aortic dissection, thunderclap headache, heatstroke rehydration), the author specifically named the remaining four recognition-type gaps to be filled: transient amaurosis / monocular blindness, unilateral calf swelling and pain with sudden shortness of breath, chronic subdural hematoma in the elderly that only manifests weeks after a fall, and painless gross hematuria.

Existing coverage: searching the whole book for "amaurosis", "retina", "transient ischemic attack", "pulmonary embolism", "deep vein", "subdural", and "hematuria" returned zero hits. Section 1, item 13 has fall prevention for the elderly, but only up to "don't fall", with no landing point for delayed symptoms weeks after a fall.

Placement: Section 13 adds 3 items — item 4 (eye stroke and transient amaurosis, inserted after the two stroke items), item 8 (chronic subdural hematoma, inserted after thunderclap headache), item 9 (deep vein thrombosis and pulmonary embolism); Section 1 adds item 27 at the end (painless gross hematuria), and the sentence at the beginning of the section, "this section only collects external-cause deaths and a few vaccines and screenings with the strongest evidence", is changed to "this section only collects external-cause deaths, a few vaccines and screenings with the strongest evidence, and body signals that should be checked once they appear".

Section 13 goes from 33 to 36 items: the original items 4 to 6 shift to 5 to 7, and the original items 7 to 33 shift to 10 to 36. References changed accordingly: in book/01 item 26 and docs/home-emergency-kit.md, tourniquet item 7 is changed to item 10; in the equipment list, burn item 9 is changed to item 12, epinephrine item 10 to item 13, and fire item 21 to item 24; in book/19 item 11, chemical item 16 is changed to item 19; within Section 13, in the accidental ingestion item "see item 14 for carbon monoxide, see item 9 for burns" is changed to items 17 and 12, in the chemical burn item "see item 15 for accidental ingestion" is changed to item 18, and in the wild animal item "for dog bites follow item 8" is changed to item 11. The item lists for Sections 1 and 13 in README and CLAUDE.md are supplemented with the corresponding words, and the whole-book count in README and index.html is changed from 404 to 408 (A 255, B 105, C 48; cost-effectiveness extremely high 72, high 206, average 130; disputed 42 and TODO 36 unchanged, and two old figures in the README, "checked evidence level A … 236 items" and "extremely high … 70 items", are also corrected).

## Section 13, item 4 (transient amaurosis and central retinal artery occlusion)

| Literature | Rechecked | Original figures |
|---|---|---|
| Mac Grory B, Schrag M, Biousse V, et al. (2021). Management of Central Retinal Artery Occlusion: A Scientific Statement From the American Heart Association. Stroke, 52(6), e282-e294. <https://doi.org/10.1161/STR.0000000000000366> (PMID 33677974) | Yes (Europe PMC abstract verbatim) | "Acute CRAO is a medical emergency. Systems of care should evolve to prioritize early recognition and triage of CRAO to emergency medical attention." The duration of ischemia is inversely proportional to the surviving retinal tissue |
| Rothwell PM, Giles MF, Chandratheva A, et al. (2007). Effect of urgent treatment of transient ischaemic attack and minor stroke on early recurrent stroke (EXPRESS study). Lancet, 370(9596), 1432-1442. <https://doi.org/10.1016/S0140-6736(07)61448-2> (PMID 17928046) | Yes (Europe PMC abstract verbatim) | "the 90-day risk of recurrent stroke in the patients referred to the study clinic was 10.3% (32/310 patients) in phase 1 and 2.1% (6/281 patients) in phase 2" |

Set at B rather than A: EXPRESS is a sequential comparison of two phases in the same population, not a randomized trial, and the effect size contains a time-trend component, as stated in the remark. Benefit magnitude "large" (approach mortality/disability), cost 0 yuan plus half a day, cost-effectiveness tier high.

## Section 13, item 8 (chronic subdural hematoma)

| Literature | Rechecked | Original figures |
|---|---|---|
| Zhang J, et al. (2021). Expert consensus on drug treatment of chronic subdural hematoma. Chinese Neurosurgical Journal, 7(1), 47. <https://doi.org/10.1186/s41016-021-00263-z> (PMID 34809712, Chinese Medical Association Neurosurgery Branch, etc.) | Yes (Europe PMC abstract verbatim) | "a chronic space-occupying lesion formed by blood accumulation between arachnoid and dura mater, which is usually formed in the third week after traumatic brain injury"; postoperative recurrence rate "up to 33%"; mortality "up to 32%"; "The overall good prognosis rate of patients aged more than 90 years is 24%" |
| Dziho A, et al. (2025). Global prevalence and incidence of chronic subdural hematoma: A systematic review. Brain and Spine, 5, 105893. <https://doi.org/10.1016/j.bas.2025.105893> (PMID 41439175) | Yes (Europe PMC abstract verbatim) | Incidence 3.39–39.1/100,000/year; "Incidence increases with age and may be up to three times higher among patients over 80"; "The most common aetiology was trauma and falls. Other contributing factors were chronic alcohol abuse, anticoagulation, and violence" |
| Mathon B, Shotar E (2026). Diagnostic and therapeutic management of chronic subdural hematoma in elderly patients. Gériatrie et Psychologie Neuropsychiatrie du Vieillissement, 24(1), 30-41. <https://doi.org/10.1684/pnv.2026.1274> (PMID 42112639) | Yes (Europe PMC abstract verbatim) | Clinical presentation "typically including confusion, cognitive decline, gait disturbances, or somnolence, which may mimic other geriatric syndromes" |

Set at B: all three are verbatim-checkable, but there is no effect size for "how much mortality is reduced by early recognition", only incidence, recurrence rate, and mortality. Benefit magnitude "large" (operable, and irreversible if misjudged as dementia).

Figure not written into the main text: "what proportion of patients completely cannot recall hitting their head". A search of Europe PMC found only individual case descriptions, with no citable epidemiological proportion, so the main text writes "may completely fail to recall having hit the head" without a figure.

## Section 13, item 9 (deep vein thrombosis and pulmonary embolism)

| Literature | Rechecked | Original figures |
|---|---|---|
| Goldhaber SZ, Visani L, De Rosa M (1999). Acute pulmonary embolism: clinical outcomes in the International Cooperative Pulmonary Embolism Registry (ICOPER). Lancet, 353(9162), 1386-1389. <https://doi.org/10.1016/S0140-6736(98)07534-5> (PMID 10227218) | Yes (Europe PMC abstract verbatim) | 2,454 consecutively enrolled cases of acute pulmonary embolism from 52 hospitals in 7 countries; 3-month all-cause mortality 17.4% (426/2454), and 15.3% after excluding 61 cases found at autopsy |
| WHO (2007). Study results released on travel and blood clots. <https://www.who.int/news/item/29-06-2007-study-results-released-on-travel-and-blood-clots> | Yes (original page verbatim) | "the risk of developing venous thromboembolism (VTE) approximately doubles after travel lasting four hours or more"; "the absolute risk of developing VTE, if seated and immobile for more than four hours, remains relatively low at about 1 in 6000" |

Set at B: ICOPER is an observed value from a registry study, and the WHO item is an official project release; neither has an effect size for "early recognition changes the outcome". Benefit magnitude "large". The remark states that 17.4% is the mortality of confirmed cases, not the risk of someone with a swollen leg, to prevent misreading.

Literature not used: Barritt DW, Jordan SC (1960). Anticoagulant drugs in the treatment of pulmonary embolism. A controlled trial. Lancet, 1(7138), 1309-1312 (DOI 10.1016/s0140-6736(60)92299-6). This is the classic controlled trial of anticoagulation for pulmonary embolism, and the DOI and source were verified, but Europe PMC has no abstract and no verbatim-checkable death figures were obtained this time, so its figures are not cited.

## Section 1, item 27 (painless gross hematuria)

| Literature | Rechecked | Original figures |
|---|---|---|
| Price SJ, Shephard EA, Stapley SA, Barraclough K, Hamilton WT (2014). Non-visible versus visible haematuria and bladder cancer risk: a study of electronic records in primary care. British Journal of General Practice, 64(626), e584-e589. <https://doi.org/10.3399/bjgp14X681409> (PMID 25179073) | Yes (Europe PMC abstract verbatim) | 4,915 bladder cancer cases (≥40 years) versus 21,718 controls; positive predictive value of gross hematuria ≥60 years "2.8% (95% CI = 2.5 to 3.1)", 40–59 years "1.2% (95% CI = 0.6 to 2.3)"; non-gross hematuria ≥60 years 1.6% (1.2–2.1), 40–59 years 0.8% (0.1–5.6), odds ratio "20 (95% CI = 12 to 33)" |

Set at B: a single case-control study, and it is a UK primary care population, so the detection rate in China may not be the same. The benefit magnitude is recorded as "small" according to the book's mechanical approach — there is only the detection rate as a surrogate endpoint, with no relative mortality reduction, and the cost is several hundred yuan, so the cost-effectiveness tier falls in "average". The main text writes this into the remark, so that readers do not think that being labeled "small" means it is not worth checking.

Placed in Section 1 rather than Section 13: it is not an emergency of "what to do first", but a signal of "don't delay once it appears", and it belongs to the same early-detection block as the screening items in Section 1, so it is placed at the end of Section 1 and the scope description at the beginning of the section was changed.