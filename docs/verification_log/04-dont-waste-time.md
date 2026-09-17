# Section 4 Source Verification Record

Verification date: 2026-09-07. Publisher pages (Elsevier/Wiley/APA/Springer/T&F) generally returned 403 or CAPTCHAs to the scraping tool, so metadata was verified instead via the Crossref API, OpenAlex API, Semantic Scholar API, and PubMed E-utilities; abstracts are based on the original text returned by these APIs. Each item below lists the URLs actually opened, whether the title match was confirmed, and the original text source for the cited figures.

## Items 1, 2: Gollwitzer & Sheeran (2006)
- Opened: <https://doi.org/10.1016/S0065-2601(06)38002-1> (302 → linkinghub.elsevier.com, the article page returned only "Redirecting"); <https://api.semanticscholar.org/graph/v1/paper/DOI:10.1016/S0065-2601(06)38002-1>; <https://api.crossref.org/works/10.1016/S0065-2601(06)38002-1>
- Title match: yes. Crossref: Implementation Intentions and Goal Achievement: A Meta-analysis of Effects and Processes, Advances in Experimental Social Psychology vol. 38, pp. 69–119, 2006
- Figure source (Semantic Scholar abstract original text): "Findings from 94 independent tests showed that implementation intentions had a positive effect of medium-to-large magnitude (d = .65) on goal attainment. Implementation intentions were effective in promoting the initiation of goal striving, the shielding of ongoing goal pursuit from unwanted influences, disengagement from failing courses of action, and conservation of capability for future goal striving."

## Item 3: Arkes & Blumer (1985)
- Opened: <https://doi.org/10.1016/0749-5978(85)90049-4> (→ linkinghub returned only "Redirecting"); <https://api.openalex.org/works/doi:10.1016/0749-5978(85)90049-4> (title, authors, journal, year confirmed; abstract empty); <https://www.sciencedirect.com> (403/CAPTCHA); <https://r.jina.ai/https://www.semanticscholar.org/paper/e4564b88ca2349962a707b76be4c75076ad6bd43> (abstract); <https://pmc.ncbi.nlm.nih.gov/articles/PMC2796842/> (citation pages 35, 124–140)
- Title match: yes. The psychology of sunk cost, Organizational Behavior and Human Decision Processes, 1985
- Figure source: abstract original text "In a field study, customers who had initially paid more for a season subscription to a theater series attended more plays during the next 6 months, presumably because of their higher sunk cost in the season tickets". The specific number of plays in each group (e.g., 4.11 plays) was **not confirmed**, and the item is marked as pending verification with no figure written.

## Item 3: Roth, Robbert & Straus (2015)
- Opened: <https://api.semanticscholar.org/graph/v1/paper/DOI:10.1007/s40685-014-0014-8>; <https://api.crossref.org/works/10.1007/s40685-014-0014-8>
- Title match: yes. Business Research 8(1), 99–138
- Figure source (abstract original text): "a meta-analytic review of 98 effect sizes of the sunk-cost effect … the sunk-cost effect is attenuated by time in utilization decisions … older adults are less likely to fall prey to the sunk-cost effect than younger adults."

## Items 4, 8: Buehler, Griffin & Ross (1994)
- Opened: <https://doi.org/10.1037/0022-3514.67.3.366> (→ psycnet, 403); <https://api.openalex.org/works/doi:10.1037/0022-3514.67.3.366> (title, journal confirmed, includes abstract); full-text PDF <https://web.mit.edu/curhan/www/docs/Articles/biases/67_J_Personality_and_Social_Psychology_366,_1994.pdf> (extracted locally with pdftotext)
- Title match: yes. PDF first page: Journal of Personality and Social Psychology 1994, Vol. 67, No. 3, 366-381
- Figure source (main text Study 1): "respondents predicted, on average, that they would finish in 33.9 days, but they actually took 55.5 days … Fewer than one third of the respondents (29.7%) finished in the time they reported as their most accurate prediction."
- Figure source (main text Study 4): "…in the recall-relevant condition (60.0%) than in the recall and control conditions (38.1% and 29.3%, respectively)"; "Note, n = 41, 42, and 40 in the control, recall, and recall-relevant conditions"; abstract: "In Study 4, the bias was eliminated for participants instructed to connect past experiences with their predictions."
- Figure source (main text Study 2, item 8): "A subset of the subjects (n = 62) reported having external deadlines … a majority of these subjects (80.6%) finished the projects in time to meet their deadlines … only 38.7% of these subjects finished in the predicted time … their reported completion times were strongly associated with the deadlines (r = .82, p < .001)"; predictions and deadline only r = .23.

## Item 4: Flyvbjerg (2006)
- Opened: <https://api.semanticscholar.org/graph/v1/paper/DOI:10.1177/875697280603700302>; <https://api.crossref.org/works/10.1177/875697280603700302>
- Title match: yes. Project Management Journal 37(3), 5–15
- Cited content (abstract original text): "reference class forecasting, which achieves accuracy by basing forecasts on actual performance in a reference class of comparable projects". The item does not cite its figures.

## Item 4: Halkjelsvik & Jørgensen (2012)
- Opened: <https://api.openalex.org/works/doi:10.1037/a0025996> (abstract); <https://api.crossref.org/works/10.1037/a0025996> (Psychological Bulletin 138(2), 238–271, 2012)
- Title match: yes
- Cited content: OpenAlex abstract "underestimation occurred more frequently than overestimation, though this pattern varied by study type" (tool paraphrase, not verbatim). The item uses only the qualitative conclusion.

## Item 5: Leach, Rogelberg, Warr & Burnfield (2009)
- Opened: <https://doi.org/10.1007/s10869-009-9092-6> (→ Springer idp redirect, could not read); <https://api.crossref.org/works/10.1007/s10869-009-9092-6> (J Bus Psychol 24(1), 65–76); <https://r.jina.ai/https://link.springer.com/article/10.1007/s10869-009-9092-6> (abstract)
- Title match: yes
- Figure source (abstract): "The aim of this investigation was to test hypotheses about meeting design characteristics (punctuality, chairperson, etc.) in relation to attendees' perceptions of meeting effectiveness"; two studies with samples of 958 and 292; "agenda use and quality of facilities" were significant predictors.

## Item 5: Bluedorn, Turban & Love (1999)
- Opened: <https://api.openalex.org/works/doi:10.1037/0021-9010.84.2.277>
- Title match: yes. Journal of Applied Psychology, 1999
- Figure source (abstract original text): "56 five-member groups that conducted meetings in a standing format with 55 five-member groups that conducted meetings in a seated format. Sit-down meetings were 34% longer than stand-up meetings, but they produced no better decisions"

## Item 6: Rogelberg, Leach, Warr & Burnfield (2006)
- Opened: <https://pubmed.ncbi.nlm.nih.gov/16435940/> (cookie page, no content); <https://eutils.ncbi.nlm.nih.gov/entrez/eutils/efetch.fcgi?db=pubmed&id=16435940,28739889,17201571&rettype=abstract&retmode=text>
- Title match: yes. "Not another meeting!" Are meeting time demands related to employee well-being? J Appl Psychol 2006; DOI 10.1037/0021-9010.91.1.83
- Figure source (abstract): Study 1 n = 676 (meetings in a typical week), Study 2 n = 304 (same-day meetings), employees working more than 35 hours per week; "the relationship between meeting time demands and JAWB was moderated by task interdependence, meeting experience quality, and accomplishment striving"

## Item 6: Luong & Rogelberg (2005)
- Opened: <https://api.openalex.org/works/doi:10.1037/1089-2699.9.1.58>
- Title match: yes. Group Dynamics: Theory, Research, and Practice, 2005
- Cited content (abstract): one-week diary study, HLM analysis, "statistically significant positive correlation between the quantity of meetings attended and daily fatigue, along with perceptions of subjective workload" (tool paraphrase). The item does not cite specific coefficients.

## Item 7: Kruger & Evans (2004)
- Opened: <https://api.crossref.org/works/10.1016/j.jesp.2003.11.001> (J Exp Soc Psychol 40(5), 586–598, 2004; no abstract); <https://api.openalex.org/works/doi:10.1016/j.jesp.2003.11.001> (no abstract); <https://r.jina.ai/https://www.sciencedirect.com/>... (CAPTCHA); <https://r.jina.ai/https://www.semanticscholar.org/paper/67aa82059dafc832f93ad73057fc061ba1487823> (abstract excerpt)
- Title match: yes
- Cited content (abstract original text): "People tend to underestimate how long it will take to complete tasks. We suggest that one reason people commit this planning fallacy is that they do not naturally 'unpack' multifaceted tasks (e.g., writing a manuscript) into subcomponents … when making predictions." The specific experimental percentages were **not confirmed**, and the item does not write figures.

## Item 7: Steel (2007)
- Opened: the efetch URL above; <https://eutils.ncbi.nlm.nih.gov/entrez/eutils/efetch.fcgi?db=pubmed&id=17201571&rettype=abstract&retmode=text>
- Title match: yes. The nature of procrastination: a meta-analytic and theoretical review of quintessential self-regulatory failure. Psychological Bulletin 2007; DOI 10.1037/0033-2909.133.1.65
- Figure source (abstract): "691 correlations"; "Strong and consistent predictors of procrastination were task aversiveness, task delay, self-efficacy, and impulsiveness, as well as conscientiousness and its facets". The frequently cited "80%–95% of college students procrastinate" is not in the abstract, and the item does not use it.

## Item 9: Whillans et al. (2017)
- Opened: <https://doi.org/10.1073/pnas.1706541114> (→ pnas.org, 403); the efetch URL above (PMID 28739889)
- Title match: yes. Buying time promotes happiness. PNAS 2017
- Figure source (abstract): "diverse samples (n=6,271) from four countries … individuals who spend money on time-saving services report greater life satisfaction … working adults report greater happiness after spending money on a time-saving purchase than on a material purchase"

## Items 9, 10, 13: National Bureau of Statistics, Third National Time Use Survey Bulletin (2024-10-31)
- Opened: <https://www.stats.gov.cn/sj/zxfb/202410/t20241031_1957216.html> (No. 2); <https://www.stats.gov.cn/sj/zxfb/202410/t20241031_1957215.html> (No. 3); <https://www.stats.gov.cn/sj/zxfb/202410/t20241031_1957217.html> (No. 1)
- Title match: yes
- Figure source (No. 2 original text): "互联网使用居民每日平均时间为5小时37分钟，参与者每日平均时间为6小时3分钟，活动参与率为92.9%。" ("For internet use, residents spent an average of 5 hours 37 minutes per day, participants spent an average of 6 hours 3 minutes per day, and the activity participation rate was 92.9%.") "交通活动领域，居民每日平均时间为50分钟，占全天的3.5%；参与者每日平均时间为1小时2分钟，活动参与率为80.5%。" ("In the transportation activity domain, residents spent an average of 50 minutes per day, accounting for 3.5% of the whole day; participants spent an average of 1 hour 2 minutes per day, and the activity participation rate was 80.5%.") "家务劳动活动居民每日平均时间为1小时17分钟，参与者每日平均时间为1小时59分钟，活动参与率为64.9%。" ("For housework activities, residents spent an average of 1 hour 17 minutes per day, participants spent an average of 1 hour 59 minutes per day, and the activity participation rate was 64.9%.")
- Sample (No. 1 original text): "全国共调查3.85万户家庭、10.7万人" ("A total of 38,500 households and 107,000 people were surveyed nationwide")
- The No. 2 page does not contain the characters "2018"; the comparison with 2018 was made by me against the 2018 bulletin.

## Items 10, 11: National Bureau of Statistics, 2018 National Time Use Survey Bulletin (2019-01-25)
- Opened: <https://www.stats.gov.cn/sj/zxfb/202302/t20230203_1900224.html>
- Title match: yes
- Figure source (original text): "居民看电视的平均时间为1小时40分钟" ("Residents spent an average of 1 hour 40 minutes watching TV"); "居民使用互联网的平均时间为2小时42分钟" ("Residents spent an average of 2 hours 42 minutes using the internet"); sample "共抽样调查20226户48580人" ("a total of 20,226 households and 48,580 people were sampled"); "按10岁为组距分组，75-84岁居民看电视的平均时间最长，为3小时16分钟；15-24岁居民时间最短，为42分钟。" ("Grouped in 10-year intervals, residents aged 75-84 spent the longest average time watching TV, 3 hours 16 minutes; residents aged 15-24 spent the shortest, 42 minutes.") (confirmed verbatim in a second retrieval)

## Item 11: BLS American Time Use Survey — 2025 Results
- Opened: <https://www.bls.gov/news.release/atus.nr0.htm> (twice)
- Title match: yes. "American Time Use Survey Summary", "For release 10:00 a.m. (ET) Thursday, June 25, 2026"
- Figure source (original text): "Watching TV was the leisure and sports activity that occupied the most time (2.6 hours per day), accounting for half of all leisure time, on average (5.2 hours)."

## Item 12: Lane, Napier, Peres & Sándor (2005)
- Opened: <https://doi.org/10.1207/s15327590ijhc1802_1> (→ tandfonline, 403); <https://api.semanticscholar.org/graph/v1/paper/DOI:10.1207/s15327590ijhc1802_1>; <https://api.openalex.org/works/doi:10.1207/s15327590ijhc1802_1>; <https://r.jina.ai/https://www.tandfonline.com/doi/abs/10.1207/s15327590ijhc1802_1> (full abstract)
- Title match: yes. International Journal of Human–Computer Interaction, 2005
- Figure source (abstract original text): "251 experienced users of Microsoft Word were given a questionnaire … most experienced users rarely used the efficient keyboard shortcuts, favoring the use of icon toolbars instead … Six participants performed common commands using menu selection, icon toolbars, and keyboard shortcuts. The keyboard shortcuts were, as expected, the most efficient."

## Item 13: Stutzer & Frey (2008)
- Opened: <https://doi.org/10.1111/j.1467-9442.2008.00542.x> (→ Wiley, 403/CAPTCHA); <https://api.semanticscholar.org/graph/v1/paper/DOI:10.1111/j.1467-9442.2008.00542.x> (abstract); <https://api.openalex.org/works/doi:10.1111/j.1467-9442.2008.00542.x> (Scandinavian Journal of Economics 110(2): 339–366)
- Title match: yes. Stress that Doesn't Pay: The Commuting Paradox
- Cited content (abstract original text): "we find that people with longer commuting time report systematically lower subjective well-being. Additional empirical analyses do not find institutional explanations of the empirical results that commuters systematically incur losses." The often-repeated "a one-hour one-way commute requires a 40% raise to compensate" is not in the abstract, and the item does not use it.

## Item 13: Chatterjee et al. (2020)
- Opened: <https://api.semanticscholar.org/graph/v1/paper/DOI:10.1080/01441647.2019.1649317> (full abstract); <https://api.crossref.org/works/10.1080/01441647.2019.1649317> (Transport Reviews 40(1), 5–34, online 2019, print 2020)
- Title match: yes
- Cited content (abstract original text): "Satisfaction decreases with duration of commute, regardless of mode used … However, a consistent link between commuting and life satisfaction overall has not been established. The evidence suggests that commuters are generally successful in trading off the drawbacks of longer and more arduous commute journeys against the benefits they bring"

## Unconfirmed: CNNIC 55th / 56th "Statistical Report on China's Internet Development"
- Opened: <https://www.cnnic.net.cn/NMediaFile/2025/0220/MAIN1740036167004CKE0DITFO1.pdf> and <https://www.cnnic.net.cn/NMediaFile/2025/0730/MAIN1753846666507QEK67ZS9DH.pdf> (PDFs downloaded successfully, but the fonts have no ToUnicode mapping, so pdftotext could not extract any Chinese, and no OCR tool is available locally); <https://www.cnnic.net.cn/n4/2025/0117/c88-11229.html> and <https://www.cnnic.net.cn/n4/2025/0721/c88-11328.html> (the release pages contain only the internet user scale of 1.108 billion/1.123 billion, penetration rates of 78.6%/79.7%, and 662 million micro-drama users, but no weekly online hours or short-video user scale); <https://www.cnnic.net.cn/6/132/> (only a directory)
- Conclusion: **unconfirmed**. The figures appearing in search results, "average 28.7 hours online per person per week (2024-12)" and "short-video users 1.068 billion, 95.1% of internet users (2025-06)", both come from secondhand reposts; item 10's source column is marked TODO, and these figures are not written.

## Other pages opened but not used
- <https://api.unpaywall.org/v2/>... (422, no OA copy obtained)
- Kahneman & Tversky (1979) Intuitive prediction: Biases and corrective procedures, TIMS Studies in Management Science 12, 313–327: the search found no DOI or official full text, so item 4 used Buehler 1994 and Flyvbjerg 2006 as the original literature for reference class forecasting instead, and did not cite it directly.