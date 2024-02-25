# CSL : Harvard - Adapted for the IIE
## ⚠️ Disclaimer
>This repository is **NOT** an official product / resource made available by the IIE.
\
>This repository is created by a **USER** of this referencing style.
\
>**ALWAYS** double check your citation and referencing format and **NEVER** blindly rely on software or automation without oversight.
\
>The creators and / or contributors of this repository or any copy thereof takes **NO** responsibility for any citation or referencing erros caused by the use, directly or indirectly, of it.
## About
This repository contains a citation style language (CSL) file that can be imported into MOST referencing managers like [Zotero](https://www.zotero.org/), [EndNote](https://endnote.com/), [Mendeley](https://www.mendeley.com/) etc.

The CSL is based on the 2022 referencing handbook provided by The IIE's [Varsity College](https://www.varsitycollege.co.za/) titled "*Harvard Style Reference Guide – Adapted for The IIE*"

This style is built on top of the style called [Cite Them Right 12th edition - Harvard](https://www.citethemrightonline.com/) by **Patrick O'Brien**

## Known limitations / issues
- First citation of multi authors must be manually changed from et al. et al is then used throughout so it takes precedence.
- Paraphrasing in text requires you to change '&' to 'and'. For example "According to John and Jane (2022)" as opposed to "... (John & Jane, 2022).". However, the latter is used more often and takes precedence when creating this style
- Edition numbers' ordinals default to 'th' as it covers the widest array of numbers. This is done to auto superscript the editions ordinal which requires a static value. For editions containing the numbers 1,2 or 3, the ordinals must be manually adjusted to 'st', 'nd' or 'rd' respectively.
- Blog posts have not been altered to match webpages. Change the type in the referencing manager to web page instead
- The CSL cannot auto enable links in the editor. Change the editor preferences. For Word see https://www.officetodo.com/public/how-to-activate-multiple-hyperlinks-simultaneously-word-365/

## Examples 
The same source is used in each example for each style with NO manual changes

### Website
Cite Them Right 12th edition - Harvard:
>DeClute, D. (2022) Top 11 benefits of cloud computing | TechTarget, Cloud Computing. Available at: https://www.techtarget.com/searchcloudcomputing/tip/Top-11-benefits-of-cloud-computing (Accessed: 22 February 2024).

Harvard - Adapted for the IIE:
>DeClute, D. 2022. Top 11 benefits of cloud computing | techtarget, 14 November 2022. [Online]. Available at: https://www.techtarget.com/searchcloudcomputing/tip/Top-11-benefits-of-cloud-computing [Accessed 22 February 2024].

### Website (website as author)
Cite Them Right 12th edition - Harvard:
>Canva (2023) Canva: Visual Suite for Everyone, Canva. Available at: https://www.canva.com (Accessed: 26 September 2023).

Harvard - Adapted for the IIE:
>Canva. 2023. Canva: visual suite for everyone, 2023. [Online]. Available at: https://www.canva.com [Accessed 26 September 2023].

### Book (multi author, no location)
Cite Them Right 12th edition - Harvard:
>West, J. and White, C. (2022) Data communication and computer networks: A business user’s approach. 9th edn. Cengage Learning.

Harvard - Adapted for the IIE:
>West, J. and White, C. 2022. Data communication and computer networks: a business user’s approach. 9th ed. Cengage Learning.

### Book (multi author, location, fake date)
Cite Them Right 12th edition - Harvard:
>Serpanos, D. and Wolf, T. (2011) Architecture of network systems. Burlington: Elsevier, Inc.

Harvard - Adapted for the IIE:
>Serpanos, D. and Wolf, T. 2011. Architecture of network systems. Burlington: Elsevier, Inc.


### Journal Article
Cite Them Right 12th edition - Harvard:
>Han, S. et al. (2022) ‘Aligning artificial intelligence with human values: reflections from a phenomenological perspective’, AI & SOCIETY, 37(4), pp. 1383–1395. Available at: https://doi.org/10.1007/s00146-021-01247-4.

Harvard - Adapted for the IIE:
>Han, S., Kelly, E., Nikou, S. and Svee, E.-O. 2022. Aligning artificial intelligence with human values: reflections from a phenomenological perspective. AI & SOCIETY, 37(4): 1383–1395. [Online].  DOI: 10.1007/s00146-021-01247-4 [Accessed 1 December 2022].

### Conference Paper
Cite Them Right 12th edition - Harvard:
>Estrada, D. (2018) ‘Value Alignment, Fair Play, and the Rights of Service Robots’, in Proceedings of the 2018 AAAI/ACM Conference on AI, Ethics, and Society. AIES ’18: AAAI/ACM Conference on AI, Ethics, and Society, New Orleans LA USA: ACM, pp. 102–107. Available at: https://doi.org/10.1145/3278721.3278730.

Harvard - Adapted for the IIE:
>Estrada, D. 2018. Value alignment, fair play, and the rights of service robots. AIES ’18: aaai/acm conference on ai, ethics, and society. 2 February 2018. New Orleans LA USA: ACM, 102–107. [Online]. Available at: DOI: 10.1145/3278721.3278730 [Accessed 2 February 2018].

## Install Instructions
#### Zotero
1. Go to *Edit* > *Preferences*
2. Click *Cite*
3. Click the *+* underneath the style list
4. Find and select the CSL download from this repository

#### Mendeley
1. Go to *View* > *Citation Style*
2. Click *More Styles*
3. Drag the CSL downloaded from this repository onto the style list

#### Others
Google "How to import custom CSL for <referencing managers name here>"

## Contributing
Anyone is welcome to submit a pull request for this repository.

If you are not a student of [The IIE's Varsity College](https://www.varsitycollege.co.za/), please submit a formal request to them to gain access to the referencing handbook used to define this style.

## Issues
Anyone is welcome to report an issue on this repository.
Please ensure all issue reports include:
1. A full description of the issue
2. The CSL JSON of the source (Google 'How to export CSL JSON in <referencing manager>'')
3. The resulting citation / reference
4. The correct citation / reference
5. If possible, 2 or 3 additional sources to test with

## References
Citation Style Language project. 2024. Citation style language, 19 February 2024. [Online]. Available at: https://citationstyles.org/ [Accessed 25 February 2024].

Corporation for Digital Scholarship. 2024. Zotero | your personal research assistant, 2024. [Online]. Available at: https://www.zotero.org/ [Accessed 25 February 2024].

O’Brien, P. 2022. Cite them right 12th edition - harvard, 27 June 2022. [Online]. Available at: http://www.citethemrightonline.com/ctrcol/ [Accessed 25 February 2024].
