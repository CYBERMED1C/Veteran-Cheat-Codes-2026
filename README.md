<img width="1024" height="1536" alt="0695c51c-64f4-4536-b49a-db5685b136fe" src="https://github.com/user-attachments/assets/913872b3-8721-462a-93a3-8f0c613160d6" />

# Veteran-Cheat-Codes-2026
Veteran-Cheat-Codes-2026


Research Framework and Draft README Book for a National VA and State Veteran Benefits Repository
Executive summary
A strong 2026 edition of this project should not simply extend the reference repository’s topic-by-topic federal guide. It should become a federal-plus-state benefits atlas: a root README.md that works as the public-facing landing page, plus state modules for all 50 states and the District of Columbia, each linked from the main README and built from official state veterans affairs sources. That recommendation follows directly from the current reference repository’s structure, which already organizes content by major federal benefit area and explicitly says that state-specific benefits are not included. Your new project’s biggest value-add is to fill that gap in a way that remains maintainable and source-verifiable. 

Because the current date is June 21, 2026, the repository should be branded and maintained as a 2026 edition, even if you preserve “2025 version” as an alias, tag, or branch name for continuity. VA itself is currently publishing 2026 disability compensation rates effective December 1, 2025, and at least some states, such as Florida, are already publishing 2026 state veterans benefits guides. 

Your user’s meaning of “CVA” is unspecified. The safest editorial approach is to define the abbreviation near the top of the README as an assumption and use a glossary note such as: “In this repository, ‘CVA’ is treated as combat-related or combat-affected veteran benefits unless a source uses the term differently.” That matters because there are real, official combat-related benefit tracks—especially Combat-Related Special Compensation, presumptive toxic-exposure pathways under the PACT Act, combat-veteran health-care eligibility, and certain award-based or disability-based state benefits. 

The most defensible content architecture is this: first, a federal section organized by eligibility tier and benefit family; second, a state index for all 50 states plus DC; third, one repeatable state template that forces the same fields for every jurisdiction: benefit category, eligibility, documents, forms, application path, contact point, deadlines, and source date. That is the only practical way to keep a national public repository accurate while using official sources as the backbone. NASDVA’s official directory confirms that every state and DC has an official veterans-affairs entry point, and NASDVA reports that states collectively contribute more than $6 billion annually in services to veterans and families. 

What the repository should cover
The federal benefits section should cover the families of benefits VA itself foregrounds: disability, health care, education and training, careers and employment, housing assistance, pensions, burial and memorials, and family-member benefits. VA’s own public framework, plus the reference repository’s existing topic layout, already supports that taxonomy. 

Within those families, the README should clearly distinguish basic veteran status benefits from service-connected disability benefits, severe-disability add-ons, and dependent/survivor programs. For example, some benefits depend mainly on qualifying service and discharge status, such as portions of VA health care, GI Bill eligibility, VA home loan eligibility, and burial eligibility. Other benefits begin only when VA assigns a disability rating, such as disability compensation starting at 10%, or tier upward based on severity, as with health-care priority groups, IU, dental care, CHAMPVA, and DEA eligibility. 

A national repository also needs a document-and-forms backbone, because that is what makes it actionable for veterans, dependents, advocates, and service officers. The core federal form stack is stable enough to build around, and the state sections can mirror the same document logic. 

Benefit family	Core form or tool	Primary use	Timing or deadline note	Official source
Disability compensation	VA Form 21-526EZ	Initial or increased disability compensation claim	Pair with Intent to File if evidence is still being gathered	
Health care	VA Form 10-10EZ	VA health care enrollment	VA says decisions are generally made in less than 1 week; hotline 877-222-8387	
Veterans Pension	VA Form 21P-527EZ	Wartime Veterans Pension	Intent to File can preserve effective date; pension intake center listed on VA page	
Aid and Attendance or Housebound	VA Form 21-2680 and sometimes 21-0779	Add-on to pension or survivor pension for care needs or housebound status	Nursing-home applicants also need 21-0779	
Education benefits	VA Form 22-1990	Post-9/11 GI Bill, MGIB, MGIB-SR	Dependent transferees use 22-1990e	
VR&E	VA Form 28-1900	Veteran Readiness and Employment	For veterans or service members with service-connected disability	
Home loan COE	VA Form 26-1880	Request Certificate of Eligibility	VA’s current goal is about 5 business days for COE contact/decision	
CHAMPVA	VA Form 10-10d	Dependents’ health coverage	Available to qualifying dependents and survivors who are not TRICARE-eligible	
DIC and Survivors Pension	VA Form 21P-534EZ	Survivor claims, including DIC, Survivors Pension, accrued benefits	Related income and medical-expense forms may be needed	
Supplemental Claim	VA Form 20-0995	Review with new and relevant evidence	Generally used within 1 year of the decision you disagree with	
Higher-Level Review	VA Form 20-0996	Review based on the same record, no new evidence	Must generally be requested within 1 year	
Board Appeal	VA Form 10182	Appeal to the Board of Veterans’ Appeals	Generally within 1 year; some contested claims use 60 days	

A README-format book should also treat the following documents as recurring evidence objects across both federal and state sections: DD214 or equivalent separation document, VA rating decision letters, marriage certificates, divorce decrees, dependency records, medical nexus evidence, current diagnoses, direct-deposit information, and residency proof where a state benefit requires domicile. VA’s own health-care and disability pages, as well as state service-officer pages like Washington’s, repeatedly show those same records as the practical entry points for claims. 

Federal benefit tiers and rating logic
The federal section of the README should be written as a tiered decision tool, not just a long encyclopedia. That is more useful for advocates and service officers because it answers the question veterans actually ask: “What opens up at my service status or rating level?” The tiers below are a practical editorial model built from current VA eligibility and rates pages. 

Tier	What usually unlocks here	What to explain in README	Official source
Basic veteran status	Potential VA health care eligibility, GI Bill pathways, home loan COE eligibility, burial eligibility, federal hiring preference in qualifying cases	Service requirements, discharge standards, DD214, benefit family overview	
Service-connected 10% to 20%	Monthly tax-free disability compensation begins; health-care Priority Group 3 for 10% or 20%	Start of compensation, rates, evidence basics	
Service-connected 30% to 40%	Higher compensation; dependent add-ons begin at 30%; health-care Priority Group 2 at 30% or 40%	Dependency rules, spouse/child rates, evidence of dependents	
Service-connected 50% and up	Health-care Priority Group 1, generally no copays for covered care; significantly higher compensation	“No-copay” and priority-group explanation	
Service-connected 70% and up	Potential Individual Unemployability if work is not possible; potential PCAFC eligibility if personal care needs and other requirements are met	Explain IU rules separately from schedular 100%; explain personal-care criteria	
100% or paid at 100% through IU	Highest basic compensation tier; Class IV dental for 100% or IU; many states use 100% as a major threshold	Important distinction between schedular 100%, IU, and temporary ratings	
100% permanent and total	May unlock CHAMPVA for dependents and DEA Chapter 35 for eligible spouses/children	Explain “P&T” explicitly because it matters more than the raw number in many family programs	
Combat-related or special-condition tracks	CRSC, PACT Act presumptives, SMC, automobile allowance, clothing allowance, Aid and Attendance	Keep separate from ordinary rating tables so veterans do not miss parallel eligibility routes	

For a repository aimed at real-world use, the most important rating distinctions are not just monetary. They are threshold effects: dependents at 30%+, Priority Group 1 at 50%+, IU rules generally at 60% single or 70% combined with one disability at 40%, and family-health/family-education programs when VA has found the veteran permanent and total. If the README makes those thresholds visually obvious, it will be much more actionable than a plain narrative guide. 

Below is the recommended rating chart for the federal section. It uses current 2026 VA compensation figures for a veteran with no dependents. If the GitHub renderer in your target repo does not support xychart-beta, keep the fallback markdown table immediately below it. The figures themselves come from the current VA rate table. 

2026 VA disability compensation for a veteran alone
10
20
30
50
70
100
4000
3500
3000
2500
2000
1500
1000
500
0
Monthly USD


Show code
Disability rating	Monthly compensation for veteran alone
10%	$180.42
20%	$356.66
30%	$552.47
50%	$1,132.90
70%	$1,808.45
100%	$3,938.58

The federal combat-related lane should also be broken out explicitly if you plan to keep the user’s “CVA” label. The best official anchor for that is Combat-Related Special Compensation: it is a tax-free payment for retired veterans with combat-related disabilities, requires at least a 10% VA rating, is applied for through the uniformed service rather than VA, and carries a 6-year statute of limitations on full back-pay protection. That is an important distinction and a good reason to keep “combat-related benefits” as a separate lane in the book. 

State architecture and source backbone
The state side of the repository should not try to mimic the federal section one-for-one. State benefits vary in three different ways at once: eligibility thresholds, benefit types, and administrative pathways. A veteran may qualify for a state property-tax exemption only at 100% permanent and total, for tuition relief based on state residency and service history, for hunting/fishing or park benefits at 60%, or for claims help regardless of rating. Official state pages from Oklahoma, Virginia, Washington, and Texas show exactly that kind of variation. 

That means every state page in the book should follow the same fixed fields:

Field	Why it matters
Benefit category	Keeps cross-state comparison possible
Eligibility trigger	Rating, P&T, wartime service, residency, discharge, medal, dependent status
Required documents	DD214, VA award letter, residency proof, tax form, school proof, death certificate
Application path	Online, mail, county assessor, school aid office, state veterans service office
Required forms	State forms and any federal companion forms
Contact point	State agency, local county office, school certifying official, tax office
Deadlines	Filing dates, legislative effective dates, school term deadlines, annual renewals
Official source and last verified date	Essential for public-repo trustworthiness

The national source backbone is straightforward. NASDVA’s official resource page lists each state and D.C. official veterans-affairs entry point. That page should be the state index source in the national README, while each state subsection should then drill down into the state’s own official pages for the actual benefits and application instructions. 

Official jurisdiction coverage checklist
The directory below is the minimum state-coverage backbone your repository should include. Each jurisdiction listed here has an official state or district veterans-affairs portal linked from NASDVA’s official resource page. 

Jurisdiction	README coverage status
Alabama	Include dedicated state page
Alaska	Include dedicated state page
Arizona	Include dedicated state page
Arkansas	Include dedicated state page
California	Include dedicated state page
Colorado	Include dedicated state page
Connecticut	Include dedicated state page
Delaware	Include dedicated state page
District of Columbia	Include dedicated state page
Florida	Include dedicated state page
Georgia	Include dedicated state page
Hawaii	Include dedicated state page
Idaho	Include dedicated state page
Illinois	Include dedicated state page
Indiana	Include dedicated state page
Iowa	Include dedicated state page
Kansas	Include dedicated state page
Kentucky	Include dedicated state page
Louisiana	Include dedicated state page
Maine	Include dedicated state page
Maryland	Include dedicated state page
Massachusetts	Include dedicated state page
Michigan	Include dedicated state page
Minnesota	Include dedicated state page
Mississippi	Include dedicated state page
Missouri	Include dedicated state page

Jurisdiction	README coverage status
Montana	Include dedicated state page
Nebraska	Include dedicated state page
Nevada	Include dedicated state page
New Hampshire	Include dedicated state page
New Jersey	Include dedicated state page
New Mexico	Include dedicated state page
New York	Include dedicated state page
North Carolina	Include dedicated state page
North Dakota	Include dedicated state page
Ohio	Include dedicated state page
Oklahoma	Include dedicated state page
Oregon	Include dedicated state page
Pennsylvania	Include dedicated state page
Rhode Island	Include dedicated state page
South Carolina	Include dedicated state page
South Dakota	Include dedicated state page
Tennessee	Include dedicated state page
Texas	Include dedicated state page
Utah	Include dedicated state page
Vermont	Include dedicated state page
Virginia	Include dedicated state page
Washington	Include dedicated state page
West Virginia	Include dedicated state page
Wisconsin	Include dedicated state page
Wyoming	Include dedicated state page

Verified example-state comparison matrix
A good national README should include at least one comparison table that shows how much states diverge. The table below is a verified starter matrix built from official state sources.

State	Education benefit examples	Tax or fee benefit examples	Recreation or license examples	Claims/help infrastructure	Official source
Texas	Hazlewood Act provides up to 150 hours of tuition exemption at public institutions for qualifying veterans, spouses, and dependents; schools have their own deadlines, and TVC notes a 60-day deferment option if verification paperwork is delayed	Not the best row for state tax detail in the source reviewed; use Hazlewood page plus Texas state tax sources in final state file	Not central on the source reviewed	School aid office plus Texas Veterans Commission education workflow	
Oklahoma	ODVA benefits browser and state application form; strong claims-help orientation	Full homestead property-tax exemption for qualifying 100% permanent service-connected veterans; sales-tax exemption at the 100% rate; retirement benefit tax treatment	Free admission to state parks and museums for honorably discharged Oklahoma-resident veterans; hunting/fishing perks at 60%+ disability and some fee exemptions at 100%	ODVA offices in Oklahoma City and Muskogee; toll-free 888-655-2838	
Virginia	Education pages include GI Bill support, a state approving agency, MEWI, and VMSDEP	Military retirement subtraction; real-estate tax exemption for 100% service-connected, permanent and total veterans and some surviving spouses; one-vehicle property-tax exemption for qualifying 100% P&T veterans	Hunting and fishing license page exists in DVS benefits structure	38 benefit service offices and free claims help through DVS	
Washington	State site includes education and training pages in the benefits tree	“Free or Reduced Rate Passes & Tax Exemptions” are built into the state benefits taxonomy	Veterans benefits tree includes passes, tax exemptions, veteran ID and related assistance	WDVA service officers help with disability, pension, Aid and Attendance, health care, and other federal/state/county benefits; statewide contact 1-800-562-2308	

This matrix points to an important editorial lesson: a national repository should compare states by benefit family and threshold, not by trying to force every state into identical statutory language. Texas is unusually strong in state tuition relief; Oklahoma’s pages highlight parks, licenses, and tax exemptions; Virginia’s official pages show how a state can combine tax relief with dense service-office infrastructure; Washington’s official site emphasizes service officers, claims assistance, spouse/family benefits, and a wide state-benefit menu. 

A useful pattern for annual maintenance is visible in Florida. FDVA publishes a 2026 Florida Veterans’ Benefits Guide, which is exactly the kind of annual release cycle your repo should mirror with tagged updates and dated source checks. 

Draft README outline and sample content
The best way to build this for GitHub is to keep the root README readable, searchable, and navigable, while pushing state detail into predictable subsections or linked child markdown files. The sample below is not meant to be the entire finished book; it is a production-ready outline and starter content pattern.

md
Copy
# Veteran Benefits Atlas
> 2026 edition of a public GitHub reference for U.S. federal VA benefits and state-level veteran benefits in all 50 states and the District of Columbia.

![Coverage](https://img.shields.io/badge/Coverage-50%20States%20%2B%20DC-blue)
![Sources](https://img.shields.io/badge/Sources-Official%20VA%20and%20State%20Agencies-green)
![Last Verified](https://img.shields.io/badge/Last%20Verified-2026--06--21-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## Executive Summary

This repository helps veterans, dependents, survivors, advocates, and service officers find benefits by:
- federal benefit family,
- disability rating tier,
- family status,
- combat-related eligibility track,
- and state of residence.

> **Assumption note on "CVA":** This repository treats "CVA" as shorthand for combat-related or combat-affected veteran benefits unless an official source uses the abbreviation differently.

## Table of Contents

- [How to Use This Repository](#how-to-use-this-repository)
- [Federal Benefits](#federal-benefits)
  - [Eligibility Tiers](#eligibility-tiers)
  - [Compensation and Pension](#compensation-and-pension)
  - [Health Care](#health-care)
  - [Education and Training](#education-and-training)
  - [Housing and Home Loans](#housing-and-home-loans)
  - [Employment and Transition](#employment-and-transition)
  - [Dependents and Survivors](#dependents-and-survivors)
  - [Burial and Memorial Benefits](#burial-and-memorial-benefits)
  - [Appeals and Review Options](#appeals-and-review-options)
- [State Benefits](#state-benefits)
  - [State Index](#state-index)
  - [Comparison Tables](#comparison-tables)
- [Templates and Checklists](#templates-and-checklists)
- [Maintenance Notes](#maintenance-notes)
- [Sources](#sources)

## How to Use This Repository

1. Start with your **status**:
   - Veteran
   - Service member in transition
   - Dependent
   - Survivor
   - Caregiver

2. Then find your **federal tier**:
   - Qualifying service only
   - Service-connected 10%–20%
   - Service-connected 30%–40%
   - Service-connected 50%+
   - Service-connected 70%+
   - 100% / IU / Permanent & Total
   - Combat-related / special compensation track

3. Then open your **state page**.

## Federal Benefits

### Eligibility Tiers

| Tier | Common unlocks | Typical evidence |
|---|---|---|
| Qualifying service | VA health care, GI Bill pathways, home loan COE, burial benefits | DD214, service history |
| 10%–20% | Monthly disability compensation | Rating decision |
| 30%–40% | Dependent add-ons start | Dependency records |
| 50%+ | Priority Group 1 health care, no copays for covered care | Rating decision |
| 70%+ | Potential IU; possible caregiver-pathway relevance | Rating decision, work limits, care needs evidence |
| 100% / IU | Highest payment tier, broad dental eligibility | Rating decision |
| 100% P&T | CHAMPVA, DEA, many state tax/property triggers | P&T award letter |

### Disability Compensation Rate Snapshot

```mermaid
xychart-beta
    title "2026 VA disability compensation for a veteran alone"
    x-axis [10, 20, 30, 50, 70, 100]
    y-axis "Monthly USD" 0 --> 4200
    bar [180.42, 356.66, 552.47, 1132.90, 1808.45, 3938.58]
Rating	Monthly compensation
10%	$180.42
20%	$356.66
30%	$552.47
50%	$1,132.90
70%	$1,808.45
100%	$3,938.58

Core Federal Applications
Benefit	Form	Apply
Disability compensation	VA Form 21-526EZ	Official VA form page
VA health care	VA Form 10-10EZ	Official VA form page
Pension	VA Form 21P-527EZ	Official VA form page
GI Bill / education	VA Form 22-1990	Official VA form page
VR&E	VA Form 28-1900	Official VA form page
Home loan COE	VA Form 26-1880	Official VA form page
CHAMPVA	VA Form 10-10d	Official VA form page
DIC / Survivors Pension	VA Form 21P-534EZ	Official VA form page

Appeals and Review Options
Disability

Health care

Pension

Education

CHAMPVA

Yes

Need review on same record

Have new and relevant evidence

Want Veterans Law Judge review

Gather evidence and documents

Which benefit?

File VA Form 21-526EZ

File VA Form 10-10EZ

File VA Form 21P-527EZ

File VA Form 22-1990

File VA Form 10-10d

VA review and exams if needed

Enrollment decision

Certificate or award processing

Eligibility review

Agree with decision?

Use and manage benefit

Higher-Level Review VA Form 20-0996

Supplemental Claim VA Form 20-0995

Board Appeal VA Form 10182



Show code
State Benefits
State Index
Alabama
Alaska
Arizona
...
Wisconsin
Wyoming
District of Columbia
Comparison Tables
State	Tuition / fee relief	Property tax relief	Vehicle / plate benefits	Parks / recreation	State veterans homes / cemeteries	Dependent-specific benefit
Texas	Yes	Verify in state file	Yes	Verify in state file	Yes	Yes
Oklahoma	Verify in state file	Yes	Yes	Yes	Verify in state file	Yes
Virginia	Yes	Yes	Yes	Yes	Yes	Yes
Washington	Yes	Verify in state file	Yes	Yes	Yes	Yes

Sample State Section Template
Texas
Official agency: Texas Veterans Commission
Best entry point: State education and veteran benefits portal
Who this page is for: Texas veterans, spouses, dependents, survivors, and school certifying officials

Education
Hazlewood Act
Up to 150 credit hours of tuition exemption at Texas public institutions for qualifying veterans
Can also apply to certain spouses and dependent children
Important: school-specific deadlines apply
If verification paperwork is delayed, ask the school about the 60-day deferment option
Federal claims help
Veterans can work with accredited representatives and state service officers for federal claims assistance.
Documents to gather
DD214
Certificate of Eligibility or ineligibility for federal education benefits
State residency proof if required
School admission or enrollment records
Application path
Apply to a Texas public institution
Gather DD214 and federal education eligibility letter
Complete the Hazlewood application
Submit the packet to the school financial aid office
Notes
Do not assume one school’s deadline applies statewide.
Check whether Chapter 33 or Chapter 31 usage affects the practical value of Hazlewood in your term.
Templates and Checklists
Sample decision review cover letter
text
Copy
[Your Name]
[Address]
[Phone]
[Email]
[Date]

Department of Veterans Affairs
[Benefit Office Address]

RE: Request for Decision Review
Benefit Type: [Compensation / Pension / Health Care / Other]
Decision Date: [YYYY-MM-DD]
VA File Number / Claim Number: [Number]

I respectfully request review of the VA decision dated [date].

Issue(s) for review:
1. [Issue]
2. [Issue]

Why review is requested:
- [Factual error]
- [Legal or policy error]
- [New and relevant evidence, if filing a Supplemental Claim]

Attached:
- [Medical opinion]
- [Lay statement]
- [Service records]
- [Dependency records]
- [Other]

I certify that the information provided is true and correct to the best of my knowledge.

Signature:
[Your Name]
Sample claim packet checklist
text
Copy
GENERAL CLAIM CHECKLIST
[ ] DD214 or other separation papers
[ ] Government ID
[ ] Current mailing address
[ ] Direct deposit information
[ ] Marriage certificate / divorce decrees if applicable
[ ] Birth certificates or dependent school records if applicable
[ ] Current VA rating decision letters
[ ] Medical diagnosis records
[ ] Nexus opinion or service treatment evidence
[ ] Buddy / lay statements
[ ] Proof of state residency for state-specific benefits
[ ] Death certificate if survivor claim
[ ] Tax assessor or school forms if state program requires them
Maintenance Notes
Verify federal rates after each annual VA rate update.
Verify GI Bill rates each academic-rate year.
Review each state page after legislative sessions or when the state veterans agency updates its benefits guide.
Add a Last Verified line to every state page.
Keep a changelog for laws, rate changes, and broken links.
Sources
Official VA.gov benefit pages
Official state veterans affairs pages
State tax and education agency pages
Federal statutes, regulations, and agency guidance
Reputable nonprofit references only when primary sources are unavailable
sql
Copy

The federal forms, review lanes, rating thresholds, and chart values in that sample are grounded in current official VA pages for disability compensation, health care, education, CHAMPVA, pension, home loans, and decision reviews. citeturn24view0turn30search1turn8search3turn8search0turn8search4turn18search1turn18search4turn11view0

For the state side, the sample Texas section is grounded in the Texas Veterans Commission’s Hazlewood page, which confirms the **150-hour** exemption, spouse/dependent pathways, school-specific timing, and the availability of a **60-day deferment** when paperwork is delayed. citeturn21search0

## Maintenance and verification rules

A public GitHub repository on benefits lives or dies on **update discipline**. The main federal refresh points are predictable. VA’s disability compensation and SMC rate tables are tied to annual COLA changes and are currently published as **2026 rates effective December 1, 2025**. VA’s clothing allowance page currently states an **August 1, 2026** application deadline for the 2026 year. Post-9/11 GI Bill rates run on an **August 1, 2025 to July 31, 2026** schedule, while DEA Chapter 35 rates run on an **October 1, 2025 to September 30, 2026** schedule. citeturn24view0turn23search1turn7search0turn7search1

Your appeals section also needs date discipline. VA’s current review system makes the time limits explicit: a **Higher-Level Review** generally must be requested within **1 year** of the initial or supplemental decision; a **Board Appeal** is generally due within **1 year**, while certain contested claims use **60 days**. Those deadlines should be repeated in the README and tagged in every form template. citeturn11view0turn9search8

For state content, the right maintenance rule is **“verify after legislative session, annual guide release, or agency-page change”** rather than a generic monthly sweep. Florida’s 2026 annual guide is a good model for release-based state updates; Virginia’s tax pages show why year-specific legal updates matter, including a 2025 line-of-duty terminology update and tax subtraction amounts keyed to specific tax years; Oklahoma’s benefits page includes state program details like an **October 1** application timing note for certain special plates. citeturn20search8turn20search10turn27view1turn27view4turn29view0

The safest repo governance pattern is therefore:

| Maintenance task | Minimum cadence | Why |
|---|---|---|
| Federal compensation, SMC, and special allowances | Annual, after VA rate publication | Rates and annual deadlines change | 
| GI Bill and DEA rates | At each official rate-year reset | Education rates follow separate calendars |
| Appeals forms and instructions | Quarterly or when VA updates form pages | Procedural pages change and forms are revised |
| State benefit pages | After each state legislative session or guide release | State thresholds and tax rules are the most volatile |
| Source validation | Continuous via “Last verified” metadata | Public repos need visible freshness controls |

Those maintenance rules are not just editorial preferences. They are the practical response to how these programs are actually published and updated by VA and the states. citeturn24view0turn23search1turn7search0turn7search1turn10search2turn10search8turn20search8turn27view1

The bottom line is that the strongest version of this project is a **source-driven, modular, annualized benefits atlas**: rooted in official VA and state agency pages, organized by federal tiers and repeated state templates, and designed so that California and later San Diego variants can be forked cleanly from the same structure without rewriting the national logic. That approach matches both the gaps in the current reference repository and the way official benefits information is actually administered across federal and state systems. citeturn2view0turn17view0turn3search1
