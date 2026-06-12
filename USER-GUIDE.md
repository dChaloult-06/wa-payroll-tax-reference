# Washington State Payroll Tax Reference — User Guide

**Tool:** Washington State Payroll Tax Reference 2026  
**Author:** Dorothy Chaloult, CPP  
**Live Tool:** https://dchaloult-06.github.io/wa-payroll-tax-reference  
**Contact:** dorothy.chaloult@gmail.com · linkedin.com/in/dorothy-chaloult-cpp

---

## What This Tool Is

The Washington State Payroll Tax Reference is a free, publicly accessible reference tool for payroll professionals. It covers every 2026 payroll tax obligation in Washington State — rates, wage bases, statutory citations, agency guidance, nexus rules, and exemptions — with direct links to the primary sources so you can verify everything yourself. It also includes a dedicated tab for the Washington Individual Income Tax enacted by SB 6346, effective January 1, 2028.

It is not a subscription service. It does not require a login. It works in any browser on any device.

---

## Who It Is For

- Payroll professionals setting up or managing Washington payroll
- Payroll tax practitioners researching specific programs or rates
- HR professionals who need a quick reference for Washington obligations
- Payroll technology teams configuring state tax calculation logic
- Anyone who needs to know what Washington requires — and where to verify it

---

## What It Covers

The tool is organized into 11 sections, accessible from the navigation bar at the top of the page.

---

### Overview

A summary of all 2026 Washington payroll tax obligations at a glance. Includes a "What Changed for 2026" section highlighting every rate change, legislative update, and new program effective this year — including a notice of SB 6346 (the Washington Millionaires' Tax, effective January 1, 2028). Start here if you need a quick orientation to the Washington payroll tax landscape.

Program summary cards cover every major obligation including both Seattle local taxes — JumpStart and the Social Housing Tax.

---

### State Taxes

Detailed reference cards for each Washington state program. Each card identifies the **program classification** (tax type, payer structure) before presenting rates, to prevent blending of distinct obligation types.

**State Unemployment Insurance (SUI)**  
Experience-rated employer tax. 2026 rate range: 0.27%–6.03% on a $78,200 wage base. The card explicitly separates the formula components:

- *Experience Rate Range:* 0.00%–5.40% across 40 statutory rate classes
- *Graduated Social Cost Factor:* variable, capped at 0.60% for standard employers
- *Employment Administration Fund (EAF):* 0.03% flat add-on, same wage base

Combined rate range (including EAF): 0.27%–6.03% (Rate Class 1 = 0.27%; Rate Class 40 = 6.03%).

**Delinquent / Penalty Rate:** Employers with missing quarterly returns or unresolved tax balances are assigned a penalty rate ceiling of 8.15% per RCW 50.29.025(2)(d), calculated as: 5.40% (RC40 base) + 2.00% (delinquency surcharge) + 0.75% (delinquent social cost cap). With EAF stacked: 8.18% all-in.

New employers default to 115% of their industry average rate.

**Employment Administration Fund (EAF)**  
A separate ~0.03% employer assessment appearing as its own line on the ESD annual tax rate determination notice. Shares the $78,200 SUI wage base. Covered as a distinct card because it is frequently overlooked in standard rate lookups.

**Paid Family & Medical Leave (PFML)**  
Tax type: Insurance Premium / Shared Contribution. 1.13% total premium in 2026 (up from 0.92% in 2025), on wages up to $184,500 (strictly tied to the Social Security wage base). Split 71.43% employee / 28.57% employer for employers with 50 or more employees. Employers with fewer than 50 employees are not required to pay the employer share, but collection and remittance of the employee portion remains mandatory.

Includes detail on the June 11, 2026 HB 2345 effective date — which reallocates the internal split between family and medical leave premium components for IRS FICA compliance. Total premium and EE/ER split are unchanged; payroll systems tracking family vs. medical components separately should review deduction logic before that date.

Note: The Legislature retains authority to adjust the PFML premium rate annually. ESD publishes the updated rate each October.

**WA Cares Fund**  
Tax type: Insurance Premium / Employee-Only. 0.58% employee-only deduction on all gross wages — no wage cap. Applies to salary, bonuses, RSU vests, PTO payouts, and severance. Benefits available statewide July 1, 2026. Includes 2026 SB 5291 exemption updates (automatic exemption for temporary visa holders, opt-in rights for previously exempt employees, out-of-state coverage continuation).

Note: The 0.58% rate is set by statute; future modifications require legislative action.

**Workers' Compensation (L&I)**  
Hour-based premiums set by risk class and experience. Employer and employee shares covered separately. The Supplemental Pension Fund (SPF) rate for 2026 is $0.1912/hour, split equally between employer ($0.0956) and employee ($0.0956). Links to the official L&I Rates for Workers' Compensation portal for class-specific rate lookup.

---

### Local Taxes

Washington does not impose traditional local income tax withholding. However, Seattle employers may be subject to the following employer-expense taxes. No employee withholding is required for either program.

**JumpStart Payroll Expense Tax (SMC 5.38)**  
Tax type: Municipal Business Excise Tax. Effective January 1, 2026. Thresholds are CPI-adjusted annually by Seattle City Finance under SMC 5.38 — not amended by discrete ordinance. Verify the current-year threshold directly with Seattle City Finance before filing.

*Dual-threshold requirement:* Both conditions must be met independently —
- Business's prior-year macro-payroll ≥ **$9,074,409** (2026 published value)
- Individual employee compensation ≥ **$194,452**

*2026 Full Rate Matrix (3 macro-payroll tiers × 2 compensation bands):*

| Macro Payroll Tier | $194,452 – $518,537 | ≥ $518,538 |
|--------------------|---------------------|------------|
| Below $129,634,413 | 0.746% | 1.811% |
| $129,634,413 – $1,296,344,132 | 0.746% | 2.024% |
| ≥ $1,296,344,132 | 1.492% | 2.557% |

The $518,538 compensation band threshold is the figure published by Seattle City Finance. The $518,537.99 upper bound of the prior tier is a derived system boundary — not explicitly published — and is how payroll systems implement the closed interval logic.

*Employee assignment methods:* Tax liability is sourced via either the **Primarily Assigned Method** (≥ 50% of an employee's service performed within Seattle city limits) or the **Hours Worked Method** (exact proration of compensation based on hours worked inside Seattle). Mobile or remote workforces require system-level work-location tracking to apply the hours method.

**Seattle Social Housing Tax (SMC 5.37 / Proposition 1A)**  
Tax type: Municipal Excise Tax. Voter-approved February 11, 2025; effective January 1, 2025. 5% flat tax on individual employee compensation exceeding $1,000,000 paid in Seattle.

Key distinction from JumpStart: there is **no minimum business payroll threshold**. A business with a single Seattle employee earning over $1M is subject regardless of total company payroll size.

*Filing cadence:* 2025 liability is due as an annual return by January 31, 2026. Beginning in 2026, the tax transitions to **quarterly installment filing**. This cadence is established by City Finance implementation guidance (administrative guidance, implementation phase); it has not yet been fully codified in SMC text. Verify current filing requirements directly with Seattle City Finance.

*Combined exposure:* Businesses subject to both taxes face up to 2.557% JumpStart on compensation up to $1M, plus 5% Social Housing Tax on the portion above $1M — a combined rate of up to 7.557% on high-earner compensation in Seattle.

The same employee assignment methods (Primarily Assigned / Hours Worked) apply to the Social Housing Tax as to JumpStart.

**System Implementation Metadata**  
The bottom of the Local Taxes tab includes a static technical reference block covering: authority level for each tax, the collection agent (Seattle City Finance — filed separately from ESD and L&I), preemption status (Washington does not preempt local payroll excise structures), and the PFML multi-employer wage cap interaction (the $184,500 cap is per-employer and does not aggregate across independent employers).

---

### Miscellaneous Taxes

Additional Washington tax programs relevant to payroll context:

- **Capital Gains Tax (7%)** — not a payroll withholding obligation, but relevant for employees with equity compensation. Threshold: $270,000 in long-term capital gains. Does not apply to RSU vests (taxed as ordinary income); WA Cares (0.58%, no cap) does apply to RSU vests.
- **Business & Occupation (B&O) Tax** — employer gross receipts tax; not payroll-withheld but may be triggered by payroll registration. See the Nexus & Registration tab for the important connection between voluntary payroll registration and B&O exposure.

---

### Nexus & Registration

A decision table answering: *Does Washington payroll nexus apply to my situation?* Covers remote employees, temporary workers, border-state scenarios, and Seattle-specific thresholds.

Also covers what additional obligations activate when you register — including the important note that PFML, WA Cares, and SUI all share the same ESD quarterly reporting system, meaning registering for SUI effectively activates all three.

**Important:** Voluntarily registering for Washington payroll taxes when not required may create nexus that triggers additional Washington business tax obligations (including B&O). Consult a qualified tax advisor before registering in a new state.

---

### Reciprocity

Washington currently has no personal income tax and therefore no formal income tax reciprocity agreements with other states. This section explains what that means practically for:

- Washington residents working in Oregon or Idaho
- Oregon and Idaho residents working in Washington
- Employees who split time across state lines

Also covers the federal four-part localization test used to determine which state has SUI and PFML jurisdiction for multi-state employees.

**SB 6346 — New Reciprocity Authority (Effective January 1, 2028):** The Washington Millionaires' Tax creates Washington's first individual income tax and grants DOR explicit authority to negotiate income tax reciprocity agreements with other states. Sec. 203(2) of the bill authorizes DOR to enter agreements where, if another state exempts WA residents from tax on personal services income earned there, Washington will provide a reciprocal exemption for that state's residents on personal services income earned in Washington. No agreements have been established as of this writing. The Individual Income Tax (2028) tab provides full detail.

---

### Deadlines

Key 2026 filing and deposit deadlines for all Washington programs and applicable federal requirements. Notable dates include:

- **January 31** — Q4 2025 ESD report; W-2 furnishing; Form 940; Seattle Social Housing Tax 2025 annual return
- **April 30** — Q1 2026 ESD report (first filing at 2026 rates)
- **June 11** — PFML HB 2345 effective (internal premium reallocation)
- **July 1** — WA Cares Fund benefits available statewide
- **September 30** — ESD employer size snapshot date (determines whether PFML employer share applies in 2027)
- **October** — ESD announces 2027 PFML premium rate

---

### Glossary

Definitions of key terms as they apply in Washington payroll tax compliance contexts, including:

- Wage Base, Experience Rating, Premium vs. Tax, Nexus, Reciprocity Agreement
- Four-Part Localization Test, EAF, Voluntary Contribution, SOC Code, SPF
- JumpStart Payroll Expense Tax, WA Cares Fund, B&O Tax
- **Delinquent SUI Rate** — penalty rate ceiling of 8.15% (8.18% with EAF) per RCW 50.29.025(2)(d)
- **Social Housing Tax** — 5% municipal excise tax on compensation exceeding $1M per Seattle employee

---

### Sources

A curated directory of official sources organized by category:

- Washington State agencies (ESD, L&I, DOR)
- Washington statutes (specific RCW section citations, including RCW 50.29.025(2)(d) for SUI delinquent rate authority)
- Seattle local tax administration (JumpStart and Social Housing Tax, plus the City Finance business taxes hub)
- Federal sources (IRS Pub 15, SSA wage base, Form 940, BLS SOC)

Every agency badge throughout the tool links directly to its corresponding official source.

Note: The L&I Workers' Compensation links throughout the tool point to the official **L&I Rates for Workers' Compensation** portal (`lni.wa.gov/insurance/rates-risk-classes/rates-for-workers-compensation/`) for direct rate lookup by risk class.

---

### Individual Income Tax (2028)

**Not yet in effect.** This tab covers Washington's first individual income tax — enacted by SB 6346 (Chapter 238, Laws of 2026; codified as Title 82A RCW), signed by Governor Ferguson on March 30, 2026, and effective January 1, 2028. The tab is focused on what payroll professionals and employers need to know, not a full taxpayer guide.

**Tax structure:**
- Rate: 9.90% flat on Washington taxable income
- Standard deduction: $1,000,000 per individual (or $1,000,000 combined for married/domestic partners, regardless of filing status) — subtracted before applying the rate; this is the statutory standard deduction, not an exemption threshold or rate trigger; CPI-indexed biennially beginning October 2029
- Administered by WA Department of Revenue (DOR) — not ESD or L&I
- Residents taxed on all income; nonresidents taxed on WA-source income only

**Filing and estimated payments:**
- First tax year: 2028; first returns due April 2029 (mirrors federal due date)
- Estimated payments required if liability exceeds $5,000
- Estimated payments are not required before July 1, 2029 (Sec. 501(6)) — first tax year liability settles at annual filing

**Employer obligations — current status (2026–2027):**
No withholding, registration, or reporting is required now. DOR is directed by Sec. 501(5) to adopt rules for making estimated tax payments on wages subject to federal income tax withholding — these rules do not yet exist and could create employer withholding obligations before 2028. DOR must file an initial implementation report with the Legislature by December 15, 2026 and a final rules report by December 15, 2027.

**Nonresident de minimis rule (Sec. 401(3)):** Nonresidents who perform services in Washington five or fewer days cumulatively in a calendar year have no Washington-source income allocated under this tax. Exceptions apply for professional athletes, student athletes, and entertainers.

**Constitutional challenge:** SB 6346 is expected to face constitutional litigation before its effective date. The Washington Constitution has historically been interpreted to prohibit a graduated income tax; the bill's drafters framed it as an excise tax on the receipt of income — the same approach upheld for the WA Capital Gains Tax in *Quinn v. State* (2023). The tab includes a callout explaining the anticipated challenge and advising employers to avoid irreversible system configuration changes until legal status is resolved.

**Reciprocity authority:** The bill grants DOR authority to negotiate reciprocity agreements with other states for personal services income (Sec. 203(2)). No agreements exist as of this writing. See also the Reciprocity tab.

**Implementation timeline:** The tab includes a visual timeline of key dates: June 11, 2026 (statutory effective date); July 1, 2026 (DOR advisory group begins); December 15, 2026 (DOR initial report); December 15, 2027 (DOR final rules report); January 1, 2028 (tax effective date); April 2029 (first returns due); July 1, 2029 (estimated payments first required).

---

### About

Background on the tool and contact information. The About tab presents a focused description of the tool's purpose and origin, including its development through detailed analysis of Washington's payroll tax framework and the implementation of Seattle's local tax programs.

---

## How to Use the Employer Size Toggle

The **Employer** dropdown in the top-right header (50+ Employees / Under 50 Employees) adjusts the PFML employer share display throughout the tool:

- **50+ Employees:** Employer share shown as 28.57% (≈0.323% of gross wages up to $184,500)
- **Under 50 Employees:** Employer share shown as 0% — with a note that collection and remittance of the employee portion (71.43%) remains mandatory regardless of employer size

---

## How to Use the Agency Badges

Throughout the tool, small colored badges appear on each card:

| Badge Color | Source Type | Example |
|-------------|-------------|---------|
| Blue — ESD | WA Employment Security Dept. | PFML, SUI, WA Cares |
| Pink — L&I | WA Dept. of Labor & Industries | Workers' Comp |
| Amber — Seattle | Seattle City Finance | JumpStart, Social Housing |
| Teal — RCW | WA Revised Code statute | Specific section citations |
| Sage — DOR | WA Dept. of Revenue | B&O, Capital Gains, SB 6346 |
| Green — IRS | Internal Revenue Service | Federal programs |
| Purple — SSA | Social Security Administration | SS wage base |

Click any badge to go directly to the official source. All links open in a new tab.

---

## Important Notes

**SB 6346 — Washington Individual Income Tax (2028):** This tax is not yet in effect. It is presented in a separate tab specifically to avoid confusion with current 2026 obligations. Employer withholding rules have not yet been issued by DOR. Legal challenges are anticipated. No employer action is required for 2026 or 2027; monitor DOR rulemaking and court proceedings before configuring payroll systems.

**Verify before filing.** This tool is updated to reflect 2026 rates and legislative changes as of May 2026. Rates, thresholds, and program rules are subject to change. Always verify current requirements at official sources before making compliance decisions.

**JumpStart thresholds are CPI-adjusted annually.** The $9,074,409 business payroll threshold and related compensation band thresholds are published by Seattle City Finance each year — not codified via discrete ordinance amendment. The values in this tool are the 2026 published figures. Confirm current-year thresholds directly with Seattle City Finance before filing.

**Social Housing Tax filing cadence.** The 2026+ quarterly filing requirement is based on City Finance implementation guidance (administrative phase). Verify current requirements with Seattle City Finance, and monitor for codification in Seattle Director's Rules (5-37 / 5-38 series).

**Not legal or tax advice.** This tool does not constitute legal, tax, or accounting advice. Consult a qualified advisor for guidance specific to your organization.

**Primary sources are always authoritative.** This tool is designed to help you find the primary sources — the RCW sections, agency employer guides, and official rate announcements. Those sources are the source of truth, not this tool.

---

## Coming Next

The Washington edition is the first in a planned series. Pennsylvania, Kentucky, and Ohio — states with complex local income tax structures — are next. Cross-state comparison guides on PFML programs, SUI wage bases, and reciprocity agreements are also in development.

---

## Contact

**Dorothy Chaloult, CPP**  
dorothy.chaloult@gmail.com  
linkedin.com/in/dorothy-chaloult-cpp

Feedback, corrections, and questions are welcome.

---

*© 2026 Dorothy Chaloult, CPP. Licensed under CC BY-NC 4.0.  
Free to share with attribution. Commercial use requires written permission.*
