# What certificates are needed to build a platform: comparison table and decision-making table for server selection

Corresponds to README section 26.Here are only two tables and a few paragraphs of easy-to-make instructions. The text and source of the entry are in the README.See Section 12 for how to register a company and how to file taxes, and see Section 11 for the red lines for employing technical personnel.

## 1. First determine what kind of business you are doing

A site often falls into several categories at the same time, and the certificates are superimposed, not one or the other.

| What you are doing | Corresponding business category | What you want | Main basis |
|---|---|---|---|
| Free information sites, personal blogs, company official websites | Non-commercial Internet information services | ICP filing | Article 4 of the Internet Information Services Management Measures |
| Memberships, value-added services, and paid content that charge users | Commercial Internet information services | Value-added telecommunications business license (information service business) | Same as Articles 3, 4, and 7 above |
| Matching buyers and sellers, processing transactions and orders | Online data processing and transaction processing business | Value-added telecommunications business license (B21) | Telecommunications business classification directory (2015 edition) B21 |
| Live broadcasts and game live broadcasts by anchors | Online performances | Internet culture business license, the business scope includes online performances | Article 4 of the Measures for the Management of Online Performance Business Activities |
| Make or integrate video programs, and provide services for others to upload audio-visual programs | Internet audio-visual program services | Information network dissemination of audio-visual program licenses | Articles 7 and 8 of the Internet Audio-visual Program Service Management Regulations |
| Selling goods during live broadcasts | Online live broadcast marketing | Based on the above certificates, perform verification and preservation obligations | Article 8 of the Online Live Broadcast Marketing Management Measures (Trial) |
| Make news and information | Internet news information services | Internet news information service license | Article 5 of the Internet Live Broadcast Service Management Regulations |
| Self-built computer rooms sell hosts and bandwidth | Internet data center business, Internet access service business | Value-added telecommunications business license (B11, B14) | Telecommunications business classification directory (2015 version) B11, B14 |

Regarding the correspondence between the three certificates, the 2021 guidance from the seven departments is the most straightforward: "Live broadcast platforms that carry out commercial online performance activities must hold an "Internet Cultural Business License" and conduct ICP filing; live broadcast platforms that carry out online audio-visual program services must hold an "Information Network Broadcast Audiovisual Program License" (or complete registration in the National Online Audio-Visual Platform Information Registration Management System) and conduct ICP filing; live broadcast platforms that carry out Internet news information services must hold an "Internet News Information Service License."

### Three easy mistakes

**Individuals cannot apply for a value-added telecommunications license.** The first condition is that "the operator is a company established in accordance with the law." The registered capital for operations within the province is not less than 1 million yuan, and for cross-provincial operations is not less than 10 million yuan. The review period is 60 days, and the certificate is valid for 5 years.If you want to do fee-based business, you must first have a company. This step is in Section 12.

**It is basically impossible for private companies to obtain a certificate for audio-visual programs.** The application conditions are "Have legal person qualifications and be a wholly state-owned or state-controlled unit."Therefore, the path of making long videos and self-made programs is closed to individual entrepreneurs; making live broadcasts requires an Internet culture business license.

**There is no official document stating that "e-commerce platforms must handle EDI."** The service guide of the Ministry of Industry and Information Technology only states that "apply for the corresponding telecommunications business operating license according to the business definition", and also answers that "online ride-hailing platforms only need to do website registration" and "equity and commodity trading platforms only need to do website registration."Therefore, this book only writes the original definition of B21. The judgment is left to you and your local communications bureau. Please ask the local communications bureau before applying.

## 2. The platform’s own daily obligations

After getting the permit, you only need to open the door. The following things must be done every day. The fines are all listed in Section 26.

| Obligations | Hard indicators | Source |
|---|---|---|
| Verification and registration of operators on the platform | Verification and update at least every six months | Article 24 of the Measures for the Supervision and Administration of Online Transactions |
| Submit identity information | Report to the market supervision department in January and July every year | Same as above Article 25 |
| Submit tax-related information | Report to the tax authorities within the month after the end of the quarter | Article 4 of the Regulations on Submission of Tax-related Information for Internet Platform Enterprises |
| Save transaction information | Not less than three years from the date of completion of the transaction | Article 31 of the E-Commerce Law |
| Save live broadcast content and logs | Sixty Days | Article 16 of the Regulations on the Management of Internet Live Broadcast Services |
| Save online performance videos | Not less than sixty days | Article 13 of the Measures for the Management of Online Performance Business Activities |
| Save network logs | Not less than six months | Article 23, Item 3 of the Cybersecurity Law |
| Handling of infringement notices | Resumption will be resumed if there is no response within fifteen days after forwarding the statement | Article 43 of the E-Commerce Law |
| Entrance for complaints and reports | Prominent location and convenience | Article 16 of the Regulations on Ecological Governance of Network Information Content |

There are four different retention periods: three years for transactions, 60 days for live broadcasts, six months for logs, and three years for the identity information of operators within the platform since they exit the platform.Store according to the longest design, not the shortest.

## 3. Choose a server: How to choose the third level?

Answer three questions first and then look at the price.

| Question | If the answer is | Then |
|---|---|---|
| Can you tolerate one day of downtime? | Can | The cheapest VPS is enough |
| Are there user registrations, transactions, and uploads | Yes | Cloud hosts from mainstream cloud vendors must be able to take snapshots and elastically expand |
| Is there anyone dedicated to operation and maintenance | No | Don’t touch independent server hosting |
| Is bandwidth or hardware cost the main expense | Yes, and it is operated and maintained by someone | Then consider independent server hosting |

**It’s not that small service providers cannot be used, but they need to be verified first.** Computer room hosting and access services themselves are value-added telecommunications services that require a license. Go to the Ministry of Industry and Information Technology's Telecommunications Business Market Integrated Management Information System tsm.miit.gov.cn and check the company's full name. Those without a license will be directly excluded.The price is half the price, but the risks are usually overbooking, running away, and upstream being blocked. When these three things happen, you can still complain to the Communications Administration Bureau for service providers that have a certificate, but you don’t even have a target to appeal to if you don’t have a certificate.

**Domestic or overseas.** Servers must be registered when placed within the country, and access providers are not allowed to provide access to sites that have not been registered.Putting it overseas can avoid filing, but if your users are in China and your money is in China, you will not miss any of the obligations in Articles 5 to 10 of Section 26. There is also an additional layer of compliance costs for data export: transferring the personal information of domestic users to overseas machines is an export, and you must meet one of the four conditions in Article 38 of the Personal Information Protection Law and obtain the individual's separate consent.The number of people threshold is calculated based on the "accumulation since January 1 of the current year". Those with less than 100,000 people are exempted from taking three paths. Those with 100,000 to 1 million people must sign a standard contract or undergo certification, and those with more than 1 million people must apply for a safety assessment.

**Backup.** Store backups in at least two places, and not both in the same area of ​​the same service provider.This article has no legal basis, it is based on experience.

## 4. Boundaries of this material

- All terms are subject to the source column in Section 26 of the README of this book, where there are document numbers, bar numbers and links.
- Regulations are updated quickly, with this section verified in September 2026.Please open the original text page again before quoting, especially the Internet Security Law (the regulations will be adjusted from January 1, 2026) and the rules for minors in live streaming rewards (changed to age-based categories in April 2026).
- Several points that have not been obtained from the original text have been listed in [Verification Record] (Verification Record/Addition-Section 26 Platform.md), including the official text on whether e-commerce platforms must handle EDI, and the judicial interpretation that directly classifies operating Internet culture or audio-visual services without a license as an illegal business crime.