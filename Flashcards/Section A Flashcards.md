# Term Insurance

**Describe possible face amount and premium patterns for term insurance.**
- Face amount patterns - level, decreasing, increasing
- Premium patterns - level, modified, increasing
- Premium schedules - attained age, select, S&U

**Describe term product development challenges and possible solutions.**
- Attained age vs S&U scales
	- Attained age: simpler, but may not be competitive at all ages
	- S&U: more competitive, but mortality may worsen in the future
- Decreasing term may mean increasing *relative* premium
	- Offer limited-pay premiums
	- Decreasing premium scales
	- Floor DB
	- Use OYT prems

**List special types of term insurance.**
1. Par term
	1. Higher persistency, but expensive (not popular)
2. Indeterminate (non-guaranteed) premium term
	1. Allows for aggressive pricing but may cause anti-selection
3. Joint life term
4. Second-to-die term
5. Hybrid term
6. Deposit term

**Describe factors that cause variations in premiums.**
- size premiums per 1000 decrease as issue face increases
	- reflects decreasing average costs
- Risk class
	- higher prems for smokers than non-smokers
	- lower prems for select risks
- Gender M/F/U
- Lapse-supported design, higher actual lapse rates = higher profits
- cross-subsidization, price some cells more aggressively than others

**List and describe riders that can be added to term policies.**
- Term riders - base, spouse, child, OYT
- Non-term riders
	- Waiver of Premium (WOP) - waives prem on qualified disability
	- Return of Premium (ROP)
	- Accelerated DB (ADB) - accelerates DB on terminal illness
	- Guaranteed insurability - purchase more coverage without underwriting
	- Other ADB riders - triggered by the following:
		- chronic illness (6 ADLs)
		- critical illness - heart attack, stroke, cancer, and coronary bypass
	- disability - pays monthly income as a % of the original face
	- long-term care - pays LTC benefits independent of original DB

**Describe pricing considerations for term insurance.**
1. Mortality
	- Mortality decreases as policy size increases
	- Aggregate term mort < aggregate WL
	- High face term mort > high face WL
	- Other considerations: improvement, anti-selection, credibility at old ages
2. Persistency (lapse) (anti-selection, premium slope)
	- High early lapses affect acquisition costs recovery
	- Low ultimate lapses hurt lapse supported designs
3. Underwriting - shifting to AUW and predictive analytics
4. Compensation - varies a lot, can affect persistency
5. Expense and inflation - overhead allocation, high profit sensitivity
6. Legal and regulatory issues - STAT reserves, coverage length, marketing, ceritfications

**List and briefly describe at least 4 common term profit objectives.**
1. $\text{Profit Margin} = \frac{\text{PV(Profits)}}{\text{PV(Premiums)}}$
2. $\text{ROE} = \frac{\text{Net Income}}{\text{Equity}}$
3. IRR = disc. rate s.t. PV(Profts) = 0
4. $\text{Surplus strain} = \frac{\text{FY Income}}{\text{FY Premium}}$
5. Break-even year (BEY) = year when accumulated assets $\geq$ reserves

**List 3 ways that a company could charge for conversion options.**
1. Charge only PHs who exercise option
2. Charge only PHs who want the option available
3. Charge everyone

**List pricing assumptions for conversions.**
- Proportion of insureds expected to elect the option
- Percentage of coverage available to be exercised
- Lapse assumption (low following conversion)
- Mortality - usually high when election rate is low (also anti-selection)

**What is the formula for determining the extra mortality cost of conversions?**

$$ A_{x,r} = _rp_x \times e_{x,r} \times K_{x,r} \times v^r$$
where
$$ K_{x,r} = \sum_{t=1}^\inf (_{t-1}p_{x+r})(v^t)(q_{x+r+t-1}^C - q_{x+r+t-1}^S) \bar{AR}_{x+r+t}$$
$$ q^C = \text{mortality rate for converted WL policy} $$
$$ q^S = \text{mortality rate for standard WL policy} $$
$$ \bar{AR} = \text{amount at risk each year} $$
$$ e_{x,r} = \text{probability a policy converts in duration } r $$
$$ r = \text{duration since policy issue}$$
$$ t = \text{duration since conversion date}$$

**What is the cost of conversions per unit issued?**
- Cost of conversions in year $t$ per unit issued is the **sum of**
	1. The cost of expected conversions in year $t$,
		1.  $= \text{Reserve Credits} + \left( \frac{\text{Option Handling Expense}}{\text{Avg Units Issued Per Policy}} \right) \left( \frac{\text{Units Electing Option}}{\text{Radix}} \right)$
	2. The cumulative cost for years prior to $t$,
		1. $= \sum \left( \frac{\text{Units Electing Options}}{\text{Radix}} \times \text{\% of Face Converted} \times \text{Option Charge} \right)$
		2. Radix = total number of units issued

# Whole Life

**Describe characteristics of WL insurance.**
- WL is a type of permanent life insurance.
	- Guarantees coverage for life if prems are paid
	- Offers tabular CSV
	- Can be participating (pays dividends)
		- Dividend options: cahs, apply to prems, PUAs/OYT
	- WL prem patterns:
		- Ordinary level prem payable for life (most common)
		- Indeterminate prem
		- Limited payment

**Describe pricing considerations for WL.**
- Mortality (significant risk)
	- Lack of premium flexibility + very long coverage periods
- Persistency/lapse
	- May affect other assumptions like mortality and expense
	- 2012 SOA WL persistency study:
		- Lapse rates have been declining
		- Lapses increase in poor economic conditions
		- Smaller policies lapse more in early years
		- Male lapses ~ female lapses
		- Stricter underwriting = lower early lapses
- Underwriting - trending toward AUW like term

# Universal Life

**List characteristics of UL.**
1. Cash value formula, $CV_t = (CV_{t-1} + \text{Prem}_t - \text{Charges}_t)(1+r)$
2. Credited rates - guaranteed minimum, portfolio vs. new money
	1. key risk - spread compression if interest rates fall
3. mortality charges - guaranteed max, attained age vs S&U
4. Surrender charges common
5. Expenses (FELs, fixed charges)
6. DB options (face or face+CV)
7. Face amount may be changed after issue
8. Prems can be flexible
9. PWDs allowed
10. Policy loans allowed (with lower credited rate)
11. Riders (similar to term)
12. Persistency bonuses

**With regard to UL with SGs, briefly describe 1) the two main designs 2) reserve implications.**
- Minimum no-lapse premium - most basic ULSG design
	- SG is based on whether cumulative minimum premiums have been paid
	- MNLP prems generate little or no CSV
- Shadow account design - policy will stay IF if the SA>0
	- Shadow account has its own set of charges/credits (SA $\neq$ CSV)
- Reserve implications: Model Regulation 830 ("XXX") and AG 38 ("AXXX")
	- AXXX greatly increased ULSG reserves
	- insurers needed reserve relief from financing (lead to AG 48)
	- VM-20 should replace XXX and AXXX and result in simpler ULSG designs

**Describe how index-based interest is typically credited on an IUL policy.**
- $\text{Index Crediting Rate} = \max \left[ \min \left( \text{Index Change} \times \text{Participation Rate }, \text{Cap} \right), \text{Floor} \right]$
- Common methods for calculating the $\text{Index Change}$:
	- Point-to-point - based on index change between two points
		- $$ \text{Index Change} = \frac{\text{Index at End of Segment}}{\text{Index at Beginning of Segment}} - 1 $$
	- Averaging - annual index change is based on average monthly index level
		- $$ \text{Index Change} = \frac{\frac{1}{12} \sum_{m=1}^{12} \text{Index}_m}{\text{BOY Index}} - 1 $$

**Describe the fixed premium UL product design.**
- aka "interest sensitive WL"
- premium is fixed like a permanent product
- $\text{CV} = \max \left( \text{Guaranteed CV}, \text{Net Accumulation Value} \right)$
- Vanishing premium design is most popular

**List advantages and disadvantages of fixed premium UL.**
- Advantages
	- More similar to WL
	- Pays higher commission to agents
	- Better persistency
- Disadvantages
	- Lack flexibility
	- Administrative complexity
	- Vanishing premiums don't always vanish

**List pricing considerations for UL.**
- Flexibility creates challenges (changing DBs, PWDs, etc.)
- Scenario testing is important
- UL sources of profit
	- Interest earned - interest credited
	- COI charges - DBs paid
	- Expenses: Expense Charges + Surr Charges - (Expenses + Commissions)
- Asset/liability analysis (interest rate risk)

# Variable Life Insurance

**How does variable UL compare to UL?**
- similarities
	- Premiums can be flexible or fixed
	- DB types: face only or face+CV
	- Changes in DB allowed
	- Similar monthly charges (mort, riders)
	- Similar commissions
	- Treatment of policy loans
- different
	- Premiums invested in SA asset
	- CSVs vary with SA performance
	- No guaranteed CVs 
	- Sales loads more limited by regulation

**How does fixed premium variable life differ from WL?**
- CSVs are uncertain, vary with SA
- No guaranteed minimum
- DBs vary by intervals (monthly or yearly)

**Describe the equitable design.**
- Most popular in U.S.
- Gross prems are fixed
- Excess/negative performance to buys positive/negative PUAs
- As long as SA outperforms AIR, DB will continue rising

# Survivorsip Insurance

**What are characteristics of survivorship insurance?**
1. Joint and survivor - pays benefit on last insured's death
2. Used for wealth preservation
3. High face amounts
4. Par WL design is common - dividends buy PUA/term

**List competitive measures in the survivorship market.**
1. Rate of return on death at specified duration
2. Minimum premium payable to fund benefits
3. Minimum premium to vanish in specified number of years
4. Minimum CV needed to vanish premiums
5. PHs value DBs more than CSVs

**List and describe types of survivorship insurance riders.**
- PUAs and term insurance riders (very common)
- Policy split rider
	- Allows joint policy to be split in the future
	- Few sold but very valuable to some
- Estate preservation rider
	- Increases DB to cover estate taxes
- First-to-die term rider (estate planning)
	- Pays a benefit when first person dies
	- Uses
		- Pay-up the policy after first death
		- Pay estate taxes on first death
		- Recover prems paid before first death

**What's the difference between single and dual status?**
- Single status
	- Status - blend of a "one-alive and two-alive" status
	- Smoother CSVs and reserves
- Dual status
	- 3 possibilites:
		- X and Y both alive
		- Only X alive
		- Only Y alive
	- CSVs and reserves jump after first death

**List factors affecting decision to use single or dual status.**
- Perceieved marketability
- Administrative feasibility
- Regulators' attitudes
- Perceived risk profile
- Implications of increased dual-status term rider costs

**Describe 3 methods for calculating dual-life statuses.**
1. Exact age
	1. first principles using mortality of exact ages
	2. cumbersome: calculation, storing, validating
2. Joint equal age
	1. Example (55,52)~(53,53)
3. Equivalent single age
	1. Equates 2 ages to a single age
	2. Overcharges in early years, then undercharges later

**Describe 3 substandard rating methods.**
1. Age rateup
	1. Assigns a higher age to a substandard insured
2. Extra premium
	1. Increase premium for substandards
3. COI multiple
	1. Increase UL COI by a multiple

**List requirements for uninsurable lives.**
1. Must not be terminally ill
2. Must undergo standalone underwriting
3. Must have life expectancy of at least 1-2 years
4. Must not increase contagion factors
5. Must not be highly rated (Table D max)

**What are pricing considerations for survivorship insurance?**
- Mortality
	- Single life mortality of joint PHs $\neq$ single life market
	- Underwriting - concessions, medical
	- Contagion risk
	- Socio-economic class of insured lives
	- Impact of very low lapses
- Persistency
	- Very low lapse rates common
- Expenses
	- Usually higher than single life business
- Reinsurance
	- Very important in pricing
	- Retention rates may be higher than other policies

# Extra Premiums for Substandard Lives

**List and describe methods for determining extra mortality for substandard lives.**
- 2 approaches for increasing premium
	- Flat extra - extra amount per 1000
	- Table rating - multiple of standard mortality
- Methods for determining extra mortality
	- Numerical rating system (sum of credits and debits)
		- Arbirary, may not properly evaluate risk
	- Advance in age
	- Lien method (increasing DB)
	- ROPs
	- Charge extra prems *and* have different nonforfeiture values
- Methods for UL
	- Charge higher prem
	- Reduce coverage

**How can companies subdivide substandard business?**
1. Male/female (e.g. setback)
2. Smoker/non-smoker (e.g. "forgive" classes for non-smoker)
3. By plan
	1. If substandard/standard ratio high => higher lapse, NT rates
	2. Steeper slope => higher sales

**Describe considerations for substandard business expenses.**
- Allocation approaches
	- Allocate across all business
	- Allocate only to substandard
	- Some combination of 1 and 2 (most common)
- Prem taxes and commissions
	- Allocate directly to substandard
- Acquisition expenses
	- Higher than standard
- Maintenance expenses
	- Similar to standard

**Describe the following with respect to substandard pricing.**
- Not-taken and lapse rates
- Prem paying period
- Ratings expiration
- CV level compared to standard business
- How to assess profitability

**What is the formula for calculating the extra substandard gross premium?**
1. Calculate a standard gross premium:
	1. $$ GP = NP(1+\text{ClaimCost\%}) + \frac{\text{AcqExp}}{\ddot{a}_{x:n}}  + \text{OtherMaintExp} + GP(\text{\% Prem Exp})$$
2. Calculate the substandard GP using the same formula, use substandard (rated) mortality and expense assumptions
3. Extra substandard gross prem: $GP_R - GP$

# Acceleration Riders

**Describe how acceleration riders work and events that trigger benefit payments.**
- "Acceleration" means the insurer pays some portion of the face before death
	- These are "living benefits"
	- PH must meet specific criteria for acceleration (trigger)
- Events that trigger accelerated benefits
	- Terminal illness -> life expectancy is less than 1 or 2 years
	- Chronic illness -> unable to perform 2+ ADLs without assistance
	- Critical illness -> meet criteria for a critical illness

**Describe 3 common chronic illness benefit designs.**
1. Actuarial discounting of the face amount
	1. Acceleration benefit = actuarial PV of accelerated portion of face
2. Lien method
	1. Lien = acceleration benefit paid to the PH
	2. PH continues to pay prem for full face amount
	3. DB = Face - Lien
3. Chronic illness rider
	1. PH pays an explicit additional prem for the rider
- chronic illness riders are designed to qualify for favorable tax treatment, goal: keep benefits tax-free to PHs

**Identify ways of controlling risk for chronic illness acceleration riders.**
1. Supplemental underwriting (screen for ADL loss, over-insureds)
2. Limit issue ages
3. Use a lien to actuarial discounting approach
4. Limit acceleration amount (annual and max)
5. Require certification for ADLs (licensed health care practicioner)
6. Exclude temporary losses of ADLs
7. List explicit exclusions in trigger criteria
8. Limit to maximum table rating
9. Contestability rights should follow base policy
10. Limit max benefit to LESS than 100% of base DB

**Describe reinsurance participation for acceleration riders.**
- Terminal illness rider reinsurance participation
	- Proportional to base policy participation
- Chronic illness rider reinsurance participation
	- Permanent products
		- High probability of ultimate claim
		- If chronically ill, lapse rate = ~0%
		- Reinsurer participation may be:
			- Full
			- Limited to a one-time payment
			- Non at all
	- Term products
		- Much more uncertainty and risk
		- A lot fewer ultimate death claims
		- Life expectancy may be > term
		- Term conversions: additional risk

# Fixed Deferred Annuities

**Describe basic deferred annuity product design in terms of tax treatment, premium structure, charges, interest guarantees**
- Tax treatment - can be qual or non-qual
- SPDAs may have minimum required prems
- Charges: FELs, periodic fees, surrender charges
- FPDAs may have surrender charges based on prems paid
- Interest rates and guarantee periods
	- SPDAs - guarantee rate for 1-7 years
	- FPDAs - lower minimum guaranteed rates

**List and describe 4 specific types of deferred annuities**
1. CD annuities
	1. SCs work like CDs
	2. Penalty-free WDs 30-60 days after interest rate guarantee period (high lapses)
	3. Pay low commissions
2. Market Value Adjusted (MVA) annuities
	1. Protects company from interest rate risk
	2. Decreases AV as interest rates rise
	3. Increases AV as interest rates fall
3. Two-tiered annuities
	1. 2 AVs
	2. Annuitization account rate > surrender account rate
4. Non-surrenderable annuities ("Personal GICS")

**Give a formula for market value adjustments and describe each term as well as how it is used.**
$$ \text{MVA}_t = \left( \frac{1+a}{1+b+c} \right)^{n-t} $$
where
- $n = \text{length in years of current guarantee period}$
- $t = \text{years since beginning of current guarantee period}$
- $a = \text{current guaranteed rate}$
- $b = \text{current rate being offered on similar product}$
- $c = \text{constant factor from 0.000 to 0.005}$
If there is a SC:
$$ \text{Final CSV}_t = \text{AV}_t \times \text{MVA}_t \times (1-\text{SC\%}_t)$$

**List the primary features of deferred annuities**
1. Bailout provisions
2. Penalty-free WD provision
	1. Waivers SC on portion of AV
	2. May be a constant % or % of prems paid
	3. May be tied to persistency
3. Return of principal guarantee provisions
4. Death benefits (usually DB=AV)
5. Waiver of SC on annuitization
6. Guaranteed settlement rates
7. AV enhancement bonuses
	1. Annuitization
	2. Persistency
	3. Large AV
	4. Higher credited rate FY

**Describe bailout provisions for a deferred annuity.**
- No SCs if credited rate < bailout rate
- Medical bailouts (popular with age 50+ market)
- Total cost of bailout = cost of the option + additional surplus
- $\text{Option Cost} = \text{Avg Lost SC} \times \text{Excess Lapse Rate} \times \text{Probabilty of Trigger}$
- Higher reserves and capital

**What are interest rate considerations for deferred annuities?**
- Interest rate risk (C-3)
- Interest Spread = Investment Earned Rate - Credited Rate
- Target Spread Components
	- Expenses (e.g. maintenance, commissions)
	- Product features (e.g. bailouts)
	- Risk charges (e.g. disintermediation)
	- Expected profit
- Crediting strategies
	- Ignore competition (use a fixed spread)
	- use a competitor's rate as a cap or floor
	- use weighted average of #1 and competitor's rate

**What are deferred annuity pricing assumptions?**
1. WD (really important)
	1. Affected by SCs, credited rates, distribution system, guarantees, PH characteristics
2. PWD provisions
3. Mortality (less important)
4. Commissions and marketing expenses
	1. % of prem
	2. affected by competitive pressures
	3. examples: SPDA 3-10%, FPDA 7% then 3%
5. Expenses (lower than life insurance)

**List deferred annuity profit and pricing considerations.**
- FY strain sources: commissions, reserves, and required capital
- Pricing should consider multiple IR scenarios
- Profit objectives: profit margin, IRR, break-even year, GAAP ROE
	- Make decisions considering all 3 together
	- Low IRR and high profit margin = surplus strain
- Pricing horizon usually 10-20 years

# Variable Annuities

**Describe the basic characteristics of variable annuities.**
- Nearly all are SPDAs
- Passes C-3 risk to PH
- No guaranteed minimum CSV on SA funds
- Basic VA DB = full AV (waive SCs)
- Product charges
	- Similar to FAs: FELs, SCs, periodic fees
	- % of asset charges: mortality, expense, profit, guarantee riders
- VA GMDBs and GLBs add substantial risk

**Describe common VA guarantees.**
1. GMDBs
	1. Step-up: GMDB = highest AV at any past anniversary - $\sum \text{WDs since anniversary with highest AV}$
	2. Roll-up: $\text{GMDB}_t = \text{GMDB}_{t-1} \times (1+r) + \text{Premiums}_t - \text{Withdrawals}_t$
2. GLBs - PH must be alive to exercise
	1. GMIB, GMAB, GMWB, GLWB

**Give formulas and methods for calculating VA unit fund values.**
$\text{Fund Value} = \text{Units} \times \text{Unit Value}$
$\text{Units}+t$