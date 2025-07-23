- FIAs are not VAs - FIAs are fixed deferred annuities with minimum nonforfeiture values just like the fixed DAs covered in ILA Ch 1
- Just like IUL, FIAs are backed by the insurer's GA, not the SA

**Characteristics of IAs**
- FIAs offer the potential for credited interest based on an index (commonly an equity index like the S&P 500)
- The index-based interest is also floored at zero
- therefore, FIAs appeal to policyholders who want the potential upside offered by a VA with downside protection similar to a fixed DA
- most are SPDAs but FPDAs exist

**Common methods for determining index growth**
- annual index growth is typically determined by one of the following:
	1. Point-to-point (PTP) - based on % change in index during PY
		1. $\text{IndexGrowth}_t = \frac{\text{Index}_t}{\text{Index}_{t-1}}-1$
	2. Average monthly sum - sums each of the 12 monthly index % changes during the year
		1. $\text{IndexGrowth}_t = \sum_{i=1}^{12} \frac{\text{Index}_{t_i} - \text{Index}_{t_{i-1}}}{\text{Index}_{t_{i-1}}}$

**Adjustments Commonly Made to Index growth**
- these adjustments reduce the amount of index growth available to PH and thereby manage the cost of options needed to fund index credits
- Listed from most common to least common:
	1. Cap - max index return shared with the PH (very common)
	2. Participation rate - % of index return shared with the PH
	3. Fee - % of AV fee declared and deducted annually from the indexed FV, which would have a 100% participation
- all 3 can be used with PTP or monthly sum, but the fee approach is rarely used for monthly sum
- Index growth is typically floored at 0, but the floor could be set above or below 0
- **Monthly sum cap** is very common: apply cap to each monthly index growth before summing
	- $\text{IndexGrowth}_t = \sum_{i=1}^{12} \min \left[ \text{Cap}, \frac{\text{Index}_{t_i} - \text{Index}_{t_{i-1}}}{\text{Index}_{t_{i-1}}}\right]$

**Comparisons**
- PTP: highest PH returns occur under:
	- cap for moderate index returns
	- participation or fee when index returns are high
- PTP vs monthly averaging:
	- Monthly averaging exceeds PTP when the index increases steadily over the year
	- volatility hurts monthly averaging more because there is no monthly floor

- Index-based interest is funded with call options or dynamic hedging (explained later)
- a cap is funded by a bull call spread strategy using the amount that would be credited in interest if the policy were a FA to buy a call option with a zero strike
- the lower the cap, the higher the value of the sold call option (and lower effective payoff since more of the upside is sold)
- $\text{Participation Rate} = \frac{\text{Amount of Interest Available}}{\text{Cost of a Zero Strike Option}}$

**Innovative Return Methods (Exotic Product Designs)**
- Binary returns - based on either/or logic
	- example - if the index growth > 0, index credit = 5%, else there is no credit
- high water - based on the highest index level (e.g. on any past anniversary)
	- $$\text{IndexGrowth} = \frac{\text{Max Index Level}}{\text{Initial Index Level}}$$
- index choice - allows the PH to chose their index (this is common now)
- fixed interest - allows PH to have a fixed account option in addition to the index-based account
- fund-transfer - allows PH to transfer funds between funds (but only on anniversary usually)
- inducements to purchase - some FIAs pay upfront bonuses or offer higher participation or caps in the FY
- GMAB - some FIAs offer a guaranteed minimum value above the minimum req by standard nonforfeiture law

Many FIAs also offer GMWBs similar to VAs, but with the following differences:
- However, since GMWBs on FIAs cost less because of the return floor, most insurers do not hedge the GMWB

**Pricing and Design Considerations**

Funding the FIA as a spread product (short-term guarantee)
- for the insurer to earn a profit, the investment earned rate must cover the pricing spread and hedging budget (aka option budget)
	- $$ \text{Spread} = \text{Net Earned Rate} - \text{Pricing Spread} - \text{Hedging Budget}$$
	- where
		- pricing spread covers anticipated expenses and profit
		- hedging budget = cost of options as a % of FV
			- options are purchased based on the option cost $\times$ a notional amount
- caps, participation rates, etc. are adjusted to ensure the option cost fits within the hedging budget

Factors that affect ability to fund index-based interest:
- Falling reinvestment rates - will lower the net earned rate
- high index credits - could lead to higher future indexed AVs, which may exceed the notional value in the options purchased
- higher actual option costs in the future, which can be caused by:
	- higher future equity volatility
	- higher future risk-free rates
	- anything else that increases option costs

**Funding Index-Based Interest (hedging)**
1. Static hedging - involves purchasing over-the-counter call spread options
		1. call spread option involves 2 transactions:
			1. purchase a call option struck at the current index level
			2. sell a call option struck at the cap
		2. $\text{Call spread price} = \text{Call struck at current index} - \text{Call struck at cap}$
			1. $\text{Payoff}_t = \max \left[ 0, \text{Index}_t - \text{Lower Strike} \right] - \max \left[ 0, \text{Index}_t - \text{Upper Strike}\right]$
		3. Funding ratio = % of indexed AV hedged by the options
			1. Often will be <100% because some PH will lapse
			2. If actual lapses > expected, the unneeded options can be sold or held as a speculative investment
			3. If actual lapses < expected, the insurer will need to fund any additional index interest from the pricing spread
2. Dynamic (delta) hedging - involves holding a portfolio that replicates the call spread option
	1. **delta** = expected change in option value per unit change in underlying security (i.e. the index)
	2. main goal: hold Delta $\times$ notional amount of index
	3. must be rebalanced on a regular bases because Delta changes as the index value and other market variables change
	4. Disadvantages of dynamic hedging:
		1. involves buying high and selling low
			1. hedging cost = sum of the small losses, including transaction costs
			2. hedging costs increases with volatility
		2. does not provide downside protection like an actual call option (if index goes down, the hedge portfolio goes down too)
			1. creates a mismatch with the FIA, which does guarantee downside protection.

**Funding the GMAV**

The GMAV provided by a FIA is funded by a fixed interest rate bond, which will have exposure to default risk and interest rate risk. If the MV of the bonds backing the GMAV is less than the GMAV, the insurer will incur losses if surrenders are higher than expected.

**Regulatory Considerations (Reserving)**
- Statutory reserving for FIAs is governed by several Actuarial Guidelines:
	- **AG 33** - prescribes CARVM, which is the basic statutory reserve method for fixed deferred annuities
		- $\text{Reserve} = \text{largest projected future CSV on a PV basis}$
	- **AG 35** - prescribes 4 methods for calculating reserves specificially for FIAs in a way that is consistent with AG 33 (CARVM)
		- There is one "Type 1" AG 35 method and three "Type 2" AG 35 methods:
			- Type 1: Enhanced Discounted Intrinsic Method (EDIM)
				- Simplest method with most stable reserves: based on the book value of the hedging instrument
				- Hedged as Required (HaR) criteria must be met to use EDUM
					- Ensures that the options purchased by the insurer will hedge the index interest regardless of market conditions
			- Type 2 methods do not require HaR to be met but require more market value calculations (more work) and may result in more volatile reserves
				- CARVM with Updated Market Values (CARVM-UMV)
				- Market Value Reserve Method (MVRM)
				- MVRM with Black Scholes Projection Method (MVRM-BSPM)