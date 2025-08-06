**List the 6 steps to establish experience assumptions.**
"I DARDM"
1. Identify assumptions needed
2. Determine structure of each assumption
3. Analyze experience and trends
4. Review assumptions for reasonableness, consistency
5. Document assumptions
6. Monitor expreience and update assumptions

**Describe primary types of assumptions needed for an experience study.**
1. Obligation (liability) assumptions
	1. Mortality, lapse, expense, etc.
2. Asset assumptions
	1. Investment income rate, capital gains rate, defaults, etc.
3. Scenario assumptions
	1. Deterministic vs stochastic interest rates
	2. Sensitivity testing

**How do you determine the structure of each assumption in an experience study?**
- Determine experience classes
	- Groups of policies with same assumption
	- Similar type, structure, marketing objectives
- Key principles when deciding complexity
	- Reflect differences in actual experience
	- Use objective definitions
	- Be practical and cost effective

**List at least 4 considerations when analyzing experience and trends for an experience study.**
1. Evaluate credibility
	1. Quantity, homogeneity, reasonableness
2. Evaluate quality of data
	1. Alternative sources?
	2. Appropriate? Comprehensize enough
3. Actual vs similar experience
	1. Use actual if available and credible
4. Reflect trends
	1. Example: mortality improvement
5. Reflect company and external factors
	1. Underwriting, investment policy, etc.
6. Sensitivity test the assumptions

**Describe checks that can be performed to review assumptions for reasonableness and consistency in an experience study.**
- Consistency checks
	- Inflation consistent with investment earnings?
	- Mortality anti-selection and lapses
- Validation checks
	- Static (starting reserves)
	- Dynamic (projected reserves)

**How should assumptions be documented after an experience study?**
- Actual assumptions
	- Value, applicable class
- Data used
	- Source, values, any concerns about, adjustments reliance on others
- Methods used to develop assumptions
	- E.g. credibility method
- How to use assumption
	- Pricing vs CFT
	- Sensitivity testing
	- Regulatory requirements

**Describe the key steps to determine a mortality assumption from an experience study.**
1. Determine structure
	1. Example: S&U ALB table that varies by M/F. SM/NS
2. Analyze experience
	1. Do a mortality study (e.g. 5-year CY study)
	2. Develop expected mortality rates from study
	3. Assess credibility of expected assumption
	4. Adjust mortality rates
		1. Trends
		2. Anti-selection
		3. Blend w/ similar/industry experience if credibility low
		4. Adjust for differences in underwriting, dist-n, market, etc.
		5. Blend M/F rates into agg rates (if needed)
3. Monitor experience (A/E ratios)

**What is the structure of a mortality assumption?**
- Select and ultimate common
- Possible variations
	- Risk class
	- Selection process (type of underwriting)
	- Size of policy (bigger face $\rightarrow$ lower mort)
	- Market method (direct, agent, etc.)
- Mortality improvement
- ALB vs ANB
	- $q^{\text{ALB}}(x) = 0.5 \times \left[ q^{\text{ANB}}(x) + q^{\text{ANB}}(x+1) \right]$
	- $q^{\text{ANB}}(x) = 0.5 \times \left[ q^{\text{ALB}}(x) + q^{\text{ALB}}(x-1) \right]$

**How do you analyze mortality experience using confidence intervals?**
- Mean and variance for expected claims $E$:
	- $E = nq$
	- $\text{Var} \left( E \right) = npq$
- Confidence interval for expected claims and the expected mortality rate $q$:
	- 95% C.I. for $E$: $E \pm 1.96 \sqrt{\text{Var} \left( E\right)}$
	- 95% C.I. for $q$: $\frac{\text{95\% C.I. for E}}{n}$

**What are the 2 main types of mortality studies, and how are different risk classes handled?**
- Typically done on standard issues, with *separate* studies done for...
	1. Non-routine underwriting
	2. Conversions $\rightarrow$ usually higher mortality
	3. Sub-standards
	4. Non-forfeiture provisions (ETI, RPU)
	5. Multiple-life policies
- Two types of studies:
	1. Calendar year
		- Look at activity for a single CY
		- Must account for new policies, WDs, and deaths
	2. Anniversary-to-anniversary
		- Simpler because study year coincides with PY
		- Done on an IY/duration basis

**Explain how to determine CY mortality exposure.**
- $A+N=W+D+B$
- ![[Pasted image 20250806094815.png]]

**Explain how to determine the mortality rate from a mortality study.**
- Balducci assumption:
	- $$q(x) = \frac{\text{Deaths}}{\text{Total Exposure}} = \frac{D}{A + (1-r)N - (1-s)W}$$
- Can be done at policy level or in aggregate
	- Policy level data
		- Sum up individual exposures
	- Aggregate data (i.e. you just have the totals)
		- Assume new issues and WDs occur mid-year ($s = r= 0.5$)
			- $$ q(x) = \frac{\Sigma D}{\Sigma A + 0.5 \Sigma N - 0.5 \Sigma W} $$

**Describe how the credibility of a mortality study can be enhanced and how to develop confidence intervals for A/E ratios.**
- Credibility considerations
	1. Multi-year studies have higher credibility
		- Problem: too many years may hide trends (5 years is good)
	2. Credibility is usually lower for amount-based studies
	3. A/E ratios are useful for assessing credibility and tracking trends
- Actual-to-expected (A/E) ratios
	- By count
		- $E = \Sigma q(i)$
		- $\text{Var} = \Sigma q(i) \left[ 1- q(i) \right]$
	- By amount
		- $E = \Sigma A(i)q(i)$
		- $\text{Var} = \Sigma \left[ A(i) \right]^2 q(i) \left[ 1 - q(i) \right]$
	- 95% C.I. for claims (CIC): $E \pm 1.96 \sqrt{\text{Var}(E)}$
	- 95% C.I. for A/E ratio: $\frac{\text{CIC}}{E}$ 

**Describe the conservation of deaths principle.**
- $(1) = w^{\text{AS}} q_{[x+r]+t-r}$
- $(2) = (1-w^{\text{AS}})q^{\text{AS}}_{[x]+t}$
- $q_{[x]+t} = (1) + (2)$
- Total mortality = weighted average of:
	1. Mortality of the "select" lives that lapse in duration $r$
	2. Mortality of the lives that stay with the original policy
- **Key pricing concept:** if you don't account for selective lapsation, you will under-price the insurance product

**Describe at least 4 variations in lapse assumption structure (i.e. ways that lapses vary).**
1. Product design
	- Term: High (shock) lapses when ART period begins
	- Annuities: High (shock) lapses after SC period
	- Permanent insurance: high 1st-year lapses
2. Distribution channel
	- Brokerage: Higher lapses
	- Agency: Higher lapses if agent quality is poor
3. Policy size
	- Small policies: high early lapses
	- Large policies: high later lapses
4. Premium mode
	- Lapses generally occur on premium due dates
	- Flexible premium: assume uniform monthly
5. Product type
	- Deferred annuities: more sensitive to lapse rates than life insurance
6. Conservation program effectiveness

**Show how to determine the exposure for a lapse study and the credibility of a lapse assumption.**
- Lapse experience credibility (confidence interval)
	- $E \pm 1.96 \sqrt{\text{Var}(E)}$
- Lapse studies
	- $w(x) = \frac{W}{A+(1-r)N-(1-s)D}$
	- Mechanically the same as a mortality study - death and lapse trade places
	- Lapses get a full year of exposure

**List specific types of lapses.**
1. Termination on:
	- Failure to pay a premium (term)
	- Full cash surrender
	- Partial cash surrender
	- Policy loan > CSV
2. Nonforfeiture transfers - ETI, RPU
3. Term conversions
4. Premium persistency - actual premium as a % of target premium (UL)

**Describe the following aspects of intereset rate assumption structure: deterministic vs. stochastic, policy loans**
- Investment assets
	- Deterministic
		1. Portfolio average
		2. Investment generation
	- Stochastic
		- Useful for more important risks
		- Rates can vary with time, asset class, quality, and credit risk
- Policy loans
	- Can be modeled as assets or negative liabilities
	- Net of policy loan expenses
	- Utilization rate

**What are the formulas for determining interest rates on a book value vs market value basis?**
- Book value basis:
	- $I = Ai + (B - A - I)\left( \frac{i}{2}\right) \rightarrow i = \frac{2I}{A+B-I}$
	- All values on a BV basis
- Market value basis:
	- $r = \frac{B-A-C}{A+\frac{C}{2}}$
	- All values on a MV basis. If done daily, cet $C=0$

**What are the formulas for time-weighted vs dollar-weighted rates?**
- Time-weighted return: $r = \left[ (1+r_1) (1+r_2) \cdots (1+r_n)\right]^{1/n} - 1$
- Dollar-weighted return: $\text{Value}_t = CF_{t-1}(1+r) + CF_{t-2}(1+r)^2 + \cdots + CF_{t-n}(1+r)^n$

**Distinguish between direct and indirect expenses.**
- Direct (vary with sales)
	- Commissions
	- Premium taxes
	- Underwriting
- Indirect (express as per policy, % of premium, or per unit)
	- Overhead
- Direct or indirect
	- Maintenance expenses
	- Acqusition expenses
	- Entering new LOB

**Describe how exposure is determined in an expense study.**
- Key concepts
	1. Goal: develop a policy count base for per policy expenses
	2. How: count the number of policy years that start in the study's CY
		- BOYs "crossed" in CY $= A + N - W/2$
		- Mid-years "crossed" in CY $= A + N/2 - W/2$
			- Exposure count = 
				- $\frac{A+B+N}{2}$ for beginning of year expenses
				- $\frac{A+B}{2}$ for mid-year expenses
- Assumes WDs and new issues occur mid-year

**List methods for allocating expenses.**
1. Transaction count (e.g. number of premium payments)
2. Transfer costs (employee benefit cost per employee)
3. Employee time spent on activities
4. Index-based allocation (policy count or premium)

**Define the following:**
- Study period - period of time covered
- Study population - insureds, employees, etc.
- Cell - combinations of data dimensioned by issue age, sex, smoker/nonsmoker, PY, etc.
- Experience rates - mortality rates, lapse rates, etc. for each cell
- Rate type
	- Decrement rates = probabilities from 0 to 1 
		- Mortality, morbidity, lapse, etc.
	- Utilization rates = *not* probabilities (can exceed 1)
		- WD rates, option election rates, etc.

**Calculate $E_X$ that reflects WD rates using the Balducci Hypothesis, under the following situations: for individual calculations, for grouped calculations.**
- For individual calculations, 
	- $E_X = l_x - \sum_{i=1}^{w_x}(1-t_i) = (l_x - w_x) + \sum_{i=1}^w t_i$
- For grouped calculations,
	- $E_X = l_x - \frac{1}{2}w_x$

**Define the exposure-weighted average mortality rate over an $N$-year period starting at age $x$.**
- $$q = \frac{\sum_{t=0}^N E_{x+t}q_{x+t}}{\sum_{t=0}^N E_{x+t}} = \frac{\sum_{t=0}^N d_{x+t}}{\sum_{t=0}^N E_{x+t}}$$

**Describe amount-weighted studies, for individual amount weights.**
- Individual amount weights
	- Multiply each life year exposure by the policy's DB
	- Sum amount exposures and calculate $q_x$'s in the usual way

**Describe amount-weighted studies, for grouped amount weights.**
- The $l_x$ terms become $l_x \times \text{Average DB Inforce}$
- The $d_x$ terms become $d_x \times \text{Average DB paid on death}$
- The $w_x$ terms become $w_x \times \text{Average DB on WDn policies}$
- Sum amount exposures and calculate $q_x$'s in the usual way

**Describe the relationship between amount-weighted $q$ and life-weighted $q$.**
- Amounted-weighted $q$ will be > life-weighted $q$ if average DB paid on death > average DB inforce

**Define the A/E ratio, at an individual level.**
- The A/E ratio at each age $x$ is:
	- $$(A/E)_x = \frac{d_x}{d^e_x} = \frac{q_xE_x}{q_x^eE_x} = \frac{q_x}{q_x^e}$$
	- where $e$ denotes expected values, and the others are actuals.

**Define the A/E ratio, at an aggregate level.**
$$ q^e = \frac{\sum E_x q_x^e}{E_x} = \frac{\sum d_x^e}{\sum E_x}$$
$$ (A/E) = \frac{d}{d^e} = \frac{\sum d_x}{\sum d_x^e} = \frac{q}{q^e} $$

**Describe the uses of an A/E analysis.**
- Compare actual mortality or lapse experience to expected amounts
- Develop best estimate assumptions as a multiple of expected amounts
	- $\text{Best Estimate Rate for Age }x = (A/E) \times q_x^e$
- Can be used for valuation, risk management, financial planning, etc.

**Define the formulas for frequency and severity.**
$$ f_x = \frac{n_x}{E_x} = \text{average claim frequency}$$
$$ s_x = \frac{C_x}{n_x} = \text{average claim amount} $$
- $n_x = \text{number of claims incurred at age }x$
- $C_x = \text{total claim amount incurred at age }x$
- $E_x = \text{central exposure (or intitial)}$

**Define the loss ratio formula.**
- Loss ratio = cost of claims as a % of premiums paid ($P_x$)
	- $LR_x = \frac{C_x}{P_x}$

**Assume the following: $M_x = \text{max WD allowed}, W_x = \text{total actual WD amount}, n_x = \text{\# of contracts who took a WD}$. Define the formulas for the following:**
1. $\text{count-based exposure (excl. deaths and lapses)} = E_x = l_x - d_x - w_x$
2. $\text{withdrawal frequency} = f_x = \frac{n_x}{E_x}$
3. $\text{average size (severity of WDs taken)} = s_x = \frac{W_x}{n_x}$
4. $\text{average WD taken as a \% of the max WD} = u_x = \frac{s_x}{M_x}$
- Note: $w$ is still a lapse rate here; $W$ is what we're studying!

**Describe distortions that can be caused by amount-weighted calculations.**
1. One or a few large amounts can distort the numerator
	- Not easy to fix after the fact (cap max amount allowed in study)
2. Risks or behaviors can differ signficantly by amount
	- Small policies may have less commitment
	- Large policies may be used to defraud
	- Solution: add a size band to cells

**List the advantages of multi-year studies.**
- Higher credibility
- Less distortion caused by reporting lags
- Can populate many more cells
- Allows study of trends if a study-year or CY variable is included

**List 4 examples of reporting lags.**
- Death claims are often not reported for months after death.
- LTCI claims not reported until after elimination period.
- "Shoe boxing" - lag between direct insurers and reinsurers
- Life annuities sometimes continue paying after death

**List 2 possible solutions of reporting lags.**
- Wait a few months after the study period before gathering data
- Develop IBNR claims estimates from previous studies

**List 3 examples of non-uniform events.**
- Lapses often vary by month (e.g. PLT period)
- Prorated mortality rates tend to underestimate deaths early in the year at old ages
- LTCI claims immediately following claim

**List 3 ways to compensate for non-uniform distributions.**
1. Use a shorter interval of time
2. Apply adjustment factors
3. Use a constant force mortality assumption for old ages.

**List the considerations for the inclusion of partial PYs in a decrement study.**
- OK when the event is evenly distributed over the year
	- Common for biologically-driven rates (mortality, morbidity, etc.)
	- Allocating PYs between CYs is also common
- Otherwise, partial PYs will distort results
	- Behavioral rates are usually not evenly distributed
		- Lapse, WD, option election, etc.
	- Do not allocate PYs between CYs

**Describe the annual exposure method.**
- Annual exposure method - consistent with the Balducci Hypothesis
	- Exposes decrements to end of next anniversary (even if beyond study period)
	- Disadvantage: overstates rates in the first partial year; understates rates in final partial
	- Why exposure is extended beyond study period:
		- The rate is based on a probability
		- Captures the exposure missed by the initial partial year
			- Also true of the distributed exposure method

**Describe the distributed exposure method.**
- Assumes the decrement is uniformly distributed
	- Allocates exposure and decrements by both PY and CY
	- More accurate when underlying rates are increasing, otherwise less accurate
	- Produces same total PY exposure as the annual method, but CY allocation differs

notecard 44/112