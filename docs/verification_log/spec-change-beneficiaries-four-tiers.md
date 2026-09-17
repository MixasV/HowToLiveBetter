# Specification Change: Beneficiaries Divided into Four Tiers · Record (2026-09-09)

Task source: after Section 13, item 38 (witnessing a fight) was written, the reader asked, "That person on the ground has zero relationship to me and zero impact on my life, why should I care?" The question points to the book's own specification: the book claims that "each item answers what it costs and what it gives back", with the reader as the default subject, but a batch of items in Section 13 wrote the "benefit" column actually as the survival rate of the rescued person, so the subject was switched. Based on this, the author set the beneficiary specification.

## New rule

Beneficiaries are divided into four tiers, from high to low according to "the expectation that this benefit will return to the reader in the future": ① the reader themselves; ② spouse and direct relatives (parents, children, grandparents, grandchildren); ③ friends, colleagues, and other relatives — reciprocal relationships, and what is helped out may come back in the future; ④ strangers — the lowest tier but not zero: the probability of return is small, and one does not know the other person's character, plus there is the side of being extorted, being bitten back, and being retaliated against. Different tiers are not combined in calculation, and when writing about tier ④ the risk side must be written together with the benefit. The beneficiary tier does not change the benefit magnitude (the magnitude is still mechanically applied from the "benefit" column), and only affects whether this item is worth spending that cost, written in the remarks. The rule was also written into CLAUDE.md (a new section "Who the benefit is counted for (beneficiary specification)", including a three-step writing method for items involving others) and README (the two paragraphs after "How to Read"), and two places in the search page index.html were synchronized: the `<noscript>` fallback block (visible only with JS off and to crawlers) and the actually visible doc-head subtitle. The first time only the noscript place was changed, and the author feedback was "on the page I only see 'each item answers two questions'", so the doc-head was also changed. The doc-head sentence, by convention, does not carry numbers.

The first version was written as "only count yourself and direct relatives; friends, colleagues, and strangers are all not counted", which was a misreading of the author's exact words, and it was changed to the four-tier version above on the same day. The traces of the misreading have been cleared from CLAUDE.md, README, index.html, and the introduction to Section 13 and the remarks of items 2 and 15; the title of item 38 had "call 110" removed during the misreading period, and this round it was restored to "if you want to call the police, retreat to a safe distance and call 110", and the sentence in the remarks "what is protected is the person on the ground, not you" was rewritten as "this belongs to the lowest tier of beneficiaries; whether you are willing to spend this time is for you to weigh yourself".

## Whole-book review results

Using "someone|others|other people|stranger|bystander|passerby|the other party|colleague|friend|neighbor|acting courageously for justice|rescue|people around" to scan all 471 item titles, 37 hits were found, and after reading them item by item, only 9 needed changes:

- The vast majority of hit items were already purely self-interested accounts, with the main line being to avoid the reader being punished or defrauded (do not secretly photograph, do not lend an ID card, do not carry things for strangers, do not accept candy from strangers, do not run programs on someone else's machine, leave when someone hands something to you in a venue, etc.), and not a word was changed.
- Children's items (safety seats, window limiters, children near water) and the beneficiaries of the elderly care, child-rearing, and pregnancy sections are children and parents, which already fall in the second tier, and were not changed.
- Section 13, item 40 (money after being injured while acting courageously for justice) is about how the reader gets money back after being injured themselves, which is a self-interested item, and was not changed.

The 9 changes:

| Location | Change |
|---|---|
| Introduction to Section 13 | Added a sentence on the beneficiary specification: the main line is yourself and your spouse and direct relatives, then friends and colleagues, and for strangers it is not zero benefit but the lowest tier, and also carries the side of being extorted and being drawn into a case |
| Section 13, item 1 (CPR) | The plain-language opening was changed to "the person you are most likely to press on is your own family member", and the benefit column was supplemented with the proportion occurring at home |
| Section 13, item 2 (someone collapses, an elderly person falls) | The remarks state that this set of judgments is first for your own elderly family members, and for strangers what remains is the exemption clause and "don't move them carelessly" |
| Section 13, item 15 (convulsions) | The remarks state that the main line is people with epilepsy at home, and doing the same actions for strangers lowers the benefit by one tier but still does not create liability |
| Section 13, item 16 (hypoglycemia) | The remarks state that the default target is yourself or a diabetic family member |
| Section 13, item 17 (electric shock) | The remarks point out that "cut the power before touching the person" is a purely self-interested rule |
| Section 13, item 26 (drowning) | The remarks point out that "don't go into the water" is a self-interested rule, and that the person you really need to save is most likely your own child |
| Section 13, item 27 (choking) | The remarks point out that it most often happens at your own dinner table |
| Section 13, item 38 (witnessing a fight) | The title was changed to "retreat and walk away …; if you want to call the police, retreat to a safe distance and call 110", the main text writes calling the police as optional and leaves it to the reader to weigh, and the remarks state that the benefit of calling the police falls in the lowest tier |
| Section 8, item 13 (someone around you threatens) | The remarks state that what is counted is the spouse, parents, and children living together, and that the legal right to send someone for treatment is given only to close relatives |

## New verification

The proportion of cardiac arrests occurring at home is taken from the same paper already cited, and the figures were retrieved this round: Zheng J, et al. (2023), BASIC-OHCA registry, The Lancet Public Health, <https://doi.org/10.1016/S2468-2667(23)00173-1> — among 38,227 cases of non-traumatic out-of-hospital cardiac arrest, "30 282 (79.2%) had a cardiac arrest at home", and in the same paper "7121 (20.3%) received bystander cardiopulmonary resuscitation" and "441 (1.2%) of 38 227 survived". The PubMed page returned only a cookie notice this time, and the figures were checked against the abstractText returned by the Europe PMC REST interface.

## What was not done

No filterable dimension of "beneficiary" was added to the items (that would require changing the cost tag format and index.html's parsing and filtering panel), and no item was deleted: even the lowest of the four tiers is not zero benefit, and there is no basis for deleting items. The item count and all statistics are unchanged, still 471 items, A 299 / B 123 / C 49, and cost-effectiveness extremely high 83 / high 236 / average 152.