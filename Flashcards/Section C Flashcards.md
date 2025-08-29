**Describe the importance of product classification for statutory accounting.**
- Product classification determines:
	1. How a contract's revenue and costs are reported in the income statement
	2. Methodologies and assumptions used to determine policy reserves
	3. Statutory annual statement supporting information (exhibits, schedules, etc.)

**Describe four classifications under SSAP No. 50.**
1. Life contracts - provides financial assistance to beneficiary when insured dies
	- "Long coverage period underlying risk of death," which increases with age
	- Examples: WL, endowments, term, UL, VL, annuity contracts
2. Deposit-type contracts - no insurance risk
	- More like financial or investment instruments issued by banks
	- Examples: annuities certain, lottery payouts, policyholder dividend accumulations
3. A&H contracts - protection against economic loss resulting from a medical condition
4. P&C contracts - protection against physical/financial damage to property by an insured peril or damage/injury to the insured.

**Describe statutory accounting guidance provided by SSAP No. 51.**
- Income recognition and policy reserving for life contracts
	- Recognize premiums in revenue on a gross basis
		- Gross premium = amount charge to PH
		- Net premium = amount used in stat reserves
		- Loading = Gross prem - Net prem
	- Stat reserves must be established for all unmatured contracts
	- Policy reserves must comply with ASOPs promulgated by the ASB

**List and describe the RBC ratio and the major categories of the RBC formula.**
- $$ \text{RBC Ratio} = \frac{\text{Total Adjusted Capital}}{\text{Life Insurer's RBC}} $$
- 5 major categories of risk addressed by the RBC formula:
	1. Asset risk - Affiliates (C-0) - default risk in affiliated investments
	2. Asset risk - Other (C-1) - default risk in debt instruments and market losses in equity instruments
	3. Insurance risk (C-2) - risk of losses due to adverse mortality/morbidity
	4. Interest rate risk, health risk, and market risk (C-3)
		- Risk of reinvestment rates < guaranteed interest rates
		- Risk of capital losses (sale price < cost)
		- Risk of losses on variable product guarantees due to changes in market returns
	5. General business risk (C-4) - fraud, mismanagement, other business risks

**Describe the net level premium reserve method.**
- Net prems are a constant % of gross prems
- $_tV_x^{NLP} = \text{PVFB}_t - \text{NP}_0 \times \ddot{a}_{x+t}$
- $\text{NP}_0 = \text{PB}_0 = \left( \frac{\text{PVFB}_0}{\ddot{a}_x} \right) = \text{NP for first PY}$
- $r_t^{GP} = \text{gross premium ratio} = \frac{\text{GP}_t}{\text{GP}_0}$
- $\ddot{a}_x = 1 + v _1p_x r_1^{GP}  + \cdots$
- $\ddot{a}_{x+t} = r_t^{GP} + v _1p_{x+t}r_{t+1}^{GP} + \cdots$
- $\text{NP}_t = \text{PB}_t = \text{PB}_0 \times r_t^{GP}$

**What is the full preliminary term reserve method?**
- FPT = Modified NLP method with a formulaic expense allowance
- $_tV_x^{FPT} = _tV_x^{NLP} - _tVE_x = \text{PVFB}_t - (\text{PVPB}_t + \text{PVPE}_t)$
- $_tVE_x = \text{PVPE}_t = \text{PE}_0 \times \ddot{a}_{x+t}$
- $PE_0 = \frac{EA_x}{\ddot{a}_x}$
- $EA_x = NP_1 - c_x = \left( \frac{\text{PVFB}_1}{\ddot{a}_{x+1}} \right) - c_x$
- $c_x = v q_xDB = \text{first-year cost of insurance}$
- $NP_0 = c_x$
- $NP_t = PB_t + PE_t = \frac{\text{PVFB}_1}{\ddot{a}_{x+1}}$

**What is the commissioner's reserve valuation method (CARVM)?**
- CRVM = a modified reserve where EA is the *smaller* of 
	1. EA under FPT for the contract
	2. EA under FPT assuming 20-pay contract
- Smallest reserves allowed by SVL
- $_tV_x^{CRVM} = _tV_x^{FPT}$ unless $m$ < 20 years

**What are the formulas for mean and mid-terminal reserves?**
- Mean Reserve - DPA = Mid-Terminal Reserve + UPL
	- $\text{InterpMeanV} = (1-h)(_{t-1}V_x + NP_t) + h(_tV_x)$
	- $\text{MeanV} = \frac{(_{t-1}V_x + NP_t) + _tV_x}{2}$ if assume h=0.5 (common)
	- $\text{DPA} = \sum\text{Modal BPs due between val date and next anniversary}$
	- $\text{InterpMidV} = (1-h)(_{t-1}V_x) + h(_t V_x)$
	- $\text{MidV} = \frac{_{t-1}V_x + _tV_x}{2}$ if assume h=0.5 (common)
	- $\text{UPL} = \frac{\text{\# of months until next premium}}{\text{\# months between premium payment}} \times \text{Modal NP}$
- DPA and UPL are held separately in the statutory financial statements

**What are the types of continuous reserves?**
1. Semicontinuous
	- DB paid at moment of death
	- Premiums paid BOY
2. Fully continuous
	- DB paid at moment of death
	- NP paid continuously throughout year
	- UPL for NPs paid beyond val date
3. Discontinued continuous
	- Semicontinuous
	- Assumes refund of unearned premium at death
	- Requires a DPA

**Describe the purpose and calculation of the immediate payment of claims reserve.**
- Required for any reserve method that assumes curtate death benefits
	- In reality, DBs are paid closer to time of death
		- $\text{IPCR}_t = \frac{i}{3}\text{PVFB}_{x+t}$ if DB paid without interest
		- $\text{IPCR}_t = \frac{i}{2}\text{PVFB}_{x+t}$ if DB is paid with interest
- Based on "death portion of the reserve"

**List problems with CRVM that can be addressed by a principles-based approach.**
- Assumptions are rules-based and highly conservative
	- Prescribed mortality and expense allowance
	- Interest rate based on a formula
	- No explicit lapse assumption
- Reserves don't vary with insurance risk
	- Example: same reserve for a super preferred and standard class policy
- CRVM hasn't changed in decades despite major product innovation
- Regulation XXX and AXXX resulted in excessive reserves for term and ULSG

**What are the overarching principles of principles-based reserves?**
1. Use conservatism that reflects
	- Unfavorable events if reasonable probability of occuring
	- Tail risk (if significant)
2. Consistency with company's risk management
3. Assumptions: prescribed and non-prescribed
	- Non-prescribed assumptions = blend of company and industry experience
4. Provide margins for uncertainty
	- Greater uncertainty = larger margin = larger reserve
- Also:
	1. Ensure solvency
	2. NOT be excessive
	3. Reflect contracts' risk

**List the Valuation Manual's objectives.**
1. Consolidate minimum reserve requirements into one document
2. Promote uniformity among state valuation requirements
3. Provide efficient, consistent, and timely process to update valuation requirements
4. Mandate/facilitate specific reporting requirements of experience data
5. Enhance industry compliance with the revisions to the SVL

**Describe the process of determining the VM-20 minimum reserve.**
1. Calculate net premium reserve floor (for all policies ALWAYS)
	1. Formulaic, using prescribed assumptions (similar to current CRVM)
2. Calculate PBRs: deterministic and/or stochastic (depends on exclusion tests)
	1. Use a cash flow projection model
	2. Assumptions = blend of company and industry experience
	3. Determine in aggregate or by policy group, then allocate to policy level
	4. Starting asset collar = 98% of final reserve to max(NPR, 102% of final reserve)
	5. Time period: point at which reserve no longer changes materially
3. Excess Reserve = max(deterministic, stochastic) - NPR
	1. For deterministic and stochastic, add $\pm$ allocated pre-tax IMR
	2. Floored at zero
4. Minimum Reserve = NPR + max(0, max(DR,SR) - (NPR-DPA))
	1. Always express in this format
5. Aggregate min reserve = sum of min reserve for each product group
	1. Term, ULSG, other life

**Describe the process for determining eligibility for exclusion tests.**
1. Classify policies into 3 groups: term, ULSG, and other life
2. Does the group use a clearly defined hedging strategy?
	1. If yes, ALWAYS do stochastic and deterministic (you're done here)
	2. Else, go to #3
3. Decide if want to perform stochastic exclusion test
	1. Any group: If pass this test, no stochastic reserve required
4. Other life only: decide if want to do deterministic exclusion test
	1. Only eligible if company did stochastic exclusion test first
	2. If pass, no deterministic reserve required
	3. Term and ULSG must ALWAYS calculate determinstic reserves

**Describe the net premium reserve methodology.**
- NPR = PV(Ben) - PV(Net Prem)
- Floored by the greater of:
	- COI through next paid-to date
	- CV floor
- Differences with CRVM
	- Different EA
	- Prescribed lapses for term and ULSG
	- Prescribed mortality can be adjusted
- Similarities with CRVM
	- Same mortality (2001 CSO)
	- Same interest rates
	- Same gross premiums

**What are formulaic net premium reserve's objectives?**
- Floor gives uniform baseline for the industry
- Easier to audit than the deterministic or stochastic reserve
- Only reserve required if company passes both exclusion test
- Can be used as an allocation basis for determinstic or stochastic results

**Describe the deterministic principles-based reserve methodology.**
- Determined in aggregate using an economic scenario
	1. PV of cash flow approach
		1. $\text{APV(Ben, Exp \& Related Amounts)} - \text{APV(Prems \& Related amounts)}$
			1. First APV - include exisiting PLs and SA AV
			2. Second APV - include PL, reinsurance, & derivative cash flows
		2. Discount rates vary by model segment (driven by assets in segment)
	2. Direct iteration approach
		1. Deterministic reserve = starting asset amount that matures all future benefits and expenses
		2. Project all cash flows iteratively until balance is found

**Describe the stochastic principles-based reserve methodology.**
- Determined in aggregate using same cash flows as deterministic
	1. Project the model segment CFs using stochastically generated scenarios
	2. PV negative of projected statement value of assets
		1. $\text{Discount rates} = 1.05 \times \text{1-year treasury scenario rates}$
	3. Sum the amounts in step (2) across all model segments at the end and beginning of each projection year
	4. Scenario reserve = sum of the starting assets across all model segments and the maximum of the values above
	5. Stochastic reserve = CTE70 of the scenario reserve distribution

**Describe the general assumption considerations for deterministic and stochastic principles-based reserves.**
- Most assumptions = blend of company and industry experience
	- Higher company data credibility = closer to company experience
	- "Prudent estimate"
- Prescribed assumptions are limited to
	- Interest rate movements (deterministic reserve only)
	- Equity performance (deterministic reserve only)
	- Spreads over treasuries on reinvestment of assets
	- Definition of industry mortality table and method used to grade to table
	- For ULSG: definition of industry lapse table
- Margins for adverse deviation and estimate error (non-stochastic assumptions)
	- Greater uncertainty = larger margin = larger reserve
	- Higher margin if credibility, data quality, assumption reliability are low

**Describe VM-20 mortality assumptions.**
- VM-20 prescribes company/industry blending table
	- Varies with credibility and "sufficient data period"
- VM-20 prescribed margins that vary by attained age
	- Company margins also vary with credibility
- Mortality improvement assumptions:
	- Between experience date and valuation date:
		- Improve company experience using supported company-specific factors
		- Improve industry experience using SOA-published rates
	- After valuation date (future mortality):
		- Use VM-20 prescribed mortality improvement rates

**Describe VM-20 policyholder behavior assumptions.**
- Policyholder behavior risk factors:
	- Premium payment patterns and premium persistency
	- Partial and full withdrawals (surrenders)
	- Allocation of funds between investment options
	- Other policyholder benefits options
- VM-20 requirements:
	- Use experience data from the same block being modeled; else similar block
	- Include margin: lower credibility = more conservative assumption
	- Dynamic assumptions should be consistent with economic scenario

**Describe VM-20 expense assumptions.**
- Same assumption for deterministic and stochastic (except inflation effects)
- Considerations:
	- Spread capital expenditures (IT, etc.)
	- Assume going concern
	- Exepense bias
		- Align with actual expense
		- Consistent between new and in-force policies
	- Reflect inflation
	- NO future expense improvements
	- NO taxes
	- Consistency with related assumptions
- Types of expenses to include:
	- Direct + indirect + overhead
	- Acquisition expenses
	- Any expected future non-recurring
	- Efficiencies from combinations and mergers
- Use FULLY allocated expenses
	- Consistent allocation across LOBs

**Compare reinsurance under a ruled-based vs. principles-based approach.**
- Rules-based methodology
	- Mirror-image reserves (usually)
	- Ceding company reserve credit = reinsurer's assumed reserve
- Principles-based methodology
	- Mirror-image reserves not required (or likely)
	- Ceding company and reinsurer use their own assumptions
	- Reinsurance Reserve Credit = Pre-Reinsurance-Ceded Minimum Reserve - Post-Reinsurance-Ceded Minimum Reserve
		- For pre-insurance run: follow VM-20 assuming reinsurance didn't exist
		- 98% to 102% collar for starting assets does NOT reply
	- Reinsurance features like stop-loss may require additional stochastic analysis
	- If YRT rates are non-guaranteed: reserve credit is based on pre-PBR approach

**Give an overview of the asset modeling framework under VM-20.**
- Exisiting assets = SA assets + PLs + Derivatives + GA assets
	- "Solve" for GA Asset balance so that toal = 98-102% of reported reserve
	- Will require iterations
- Reinvestment assets
	- VM-20 prescribes yield spread
	- Reflect investment policies of the company
		- Should not produce a lower reserve than "alternative investment strategy"
		- VM-20 prescribes 50/50 mix of A and AA public non-callable corporate bonds
- Reflect default costs on all modeled assets

**Describe how derivative programs are treated under VM-20.**
- Future derivative transactions can be reflected if part of a CDHS
	- Clearly Defined Hedging Strategy (CDHS) criteria