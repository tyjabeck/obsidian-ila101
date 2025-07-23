- RILAs offer less downside protection than FIAs, but this allows for higher caps on RILAs
- a RILA may be attractive to a PH who wants more upside potential and is willing to accept more downside risk (but still wants more downside protection than a VA would offer)

Reasons for RILA market share growth:
- Higher AV growth potential compared to FAs due to index-linked crediting
- Higher AV growth potential relative to FIAs (albeit more downside risk)
- More downside protection relative to VAs

Terminology:
- Cap - max amount of interest that can be credited in the crediting term
- Buffer - max amount of loss absorbed by the insurer if the index falls
- Floor - max amount of loss absorbed by the PH
- Crediting term - length of time over which the index performance is measured (usually 1-6 years)

Two most common crediting structures:
1. Cap with floor - the PH bears the loss up to a floor, after which the insurer bears all losses
	1. $$ \text{Credit} = \max \left[ \text{Floor}, \min \left[ \text{PartRate} \times \text{IndexReturn} \right] \right] $$
2. Cap with buffer - the insurer incurs losses up to a buffer, after which the PH bears all losses
	1. $$ \text{if IndexReturn} < 0, \text{Credit = } \min \left[ \text{Cap}, \min \left[ 0, \text{PartRate} \times \text{IndexReturn} + \text{Buffer}\right] \right] $$
	2. $$ \text{otherwise, Credit}= \min \left[ \text{Cap}, \text{PartRate} \times \text{IndexReturn} \right] $$
- For both designs, index returns are based on an external index
- Under the floor design, the PH's AV can never lose less than the floor
- Under the buffer design, the PH's AV will not begin losing value until the buffer is exhausted, after which the PH's AV will continue falling (no floor at all)

**Rate Setting and Hedging**
- Rating setting process
	- Caps and bufferse are declared once or twice a month in advance of new issues
	- example: 15% cap, 10% buffer, 1-yr term on the Nasdaq index
- Key rate drivers: fixed income yields and option costs
	- as fixed income yields increase, option budgets increase, which allows for higher caps and crediting rates
	- option costs vary with equity volatility, risk-free rates, dividend yields, and other factors
- rate sheet variable relationships
	- caps increase as term increase
	- buffer design: caps decrease as buffer increase
	- floor designs offer lower caps than buffer designs, all else equal
	- caps vary by index

**Comparison to FIA Rate Setting**
- The insurer invests FIA prem in bonds with an AA to BBB average credit rating and also purchases call spread options
- FIA Option Budget = Earned Rate - Credit Default Charge - Expenses - Profit Margin
	- Credit default charge = default losses on invested assets
	- Expenses: commissions, acquisition expenses, maintenance expenses
	- profit margin: based on the insurer's internal profit requirements and pricing guidelines
		- aka pricing spread or target spread

**RILA Crediting and Hedging Examples**

RILA Option Budget = FIA Option Budget + Put Option
- The insurer sells a put with a strike equal to the buffer or floor

**Buffer with Cap**
- Most common hedging strategy - invest in a derivative portfolio that replicates the contract's payoff
- buffers are usually 10-15% but can go up to 50%
	- smaller buffers allow for higher caps (PHs that bear more risk have more upside potential)
- buffer designs typically allow for higher caps than floor designs, all else equal
	- PHs bear more risk with buffer designs
- Buffer Design Option Cost = ATM Call - OTM Call - OTM Put
	- Buy ATM call struck at current index
	- Sell OTM call struc at cap
	- Sell OTM put struck at buffer

**Floor With Cap**
- Floor Design Option Cost = ATM Call - OTM Call + OTM Put - ATM Put
	- = Call Spread + Put Spread
	- Buy ATM call struck at current idnex
	- Sell OTM call struck at cap
	- Buy OTM put struck at floor
	- Sell ATM put struck at current index

**RILA Product Mechanics**

**Interim Value and Lock Features**
- If the PH dies, surrenders, annuitizes, or makes a WD within the index term, the PH value is based on interim value
- Interim values are affected by various economic factors (e.g. index movements and volatility)

Two main methods for deriving a daily interim value:
1. Market value approach - replicating portfolio of options that match the crediting method
	1. Inputs = index return, interest rates, equity volatility, and dividend
	2. Pros:
		1. Stronger match minimizes balance sheet volatility and PH behavior risk
		2. Easier to explain to regulators
	3. Cons:
		1. Significantly more complex
		2. Harder to explain to advisors and PHs
2. Pro-rata approach - simple formula based on index return and time elapsed
	1. Pro: easier to explain to advisors and PHs
	2. Con: weaker match results in more balance sheet volatility and PH behavior risk

Some RILAs give the PH an additional optio to loc in interim values to lock in gains or limit losses.
- Manual lock - PH can lock on any day's interim value other than on anniversary
	- The AV stays locked in for the remainder of the index term
	- Will be reduced only for WDs
- Automatic lock - allows the PH to provide a target value to lock in
	- If the interim value hits the target, it is locked in and can't be undone
	- Target values can be modified until a lock takes place

**RILA Riders**
- ROP on death ("ROP DB") is the most common rider
	- guarantees a DB at least equal to prems paid less WDs
- GLWB riders have become more popular in recent years
	- Traiditional benefit base: $\text{income benefits} = \text{WD\%} \times \text{benefit base}$
		- benefit base = nominal amount that grows at a specified rate independent of the AV until the 1st WD
		- WD% is based on the age when WDs start
		- WDing more than the guaranteed amount reduces the future guaranteed WDs
	- Non-traditional: no benefit base
		- initial income payment = % of AV

**Risk Management**

Hedging Risk
- Hedging with options - major considerations:
	1. Transaction size - trading cost is lowets when notional $\geq$ $1M
		1. Some insurers restrict index term start dates to 2-4 times a month to increase trade sizes
	2. Counterparty risk - the use of options introduces counterparty risk
	3. Liquidity - put options sold require collateral
		1. provides security to the other counterparty in the event the market falls
		2. Collateral calls are typically met with cash or treasuries
	4. Decrements - hedge positions should be updated to reflect deaths, surrenders, and WDs
- Hedging with VA GMxBs instead of options
	- Some insurers with large VA portfolios combine their RILA and VA GMxB hedging
	- VA GMxBs typically have the opposite equity market exposure as RILAs
	- Offsetting VA GMxB and RILA exposures may be a cheaper and lower risk alternative to usign options (less cost and counterparty risk)

Other Risks
- Rate setting risk - risk due to declaring rates before contract purchase
	- profit decreases as option prices increase after rate declaration
	- can be mitigated with more frequent rate adjustments (crucial during economic shifts)
- investment risk - market and default risk on fixed income assets
	- mitigation strategies:
		- investing in higher quality assets
		- appropriately pricing for defaults in declared rates
- liquidity risk - PH behavior uncertainty and the potential for losses in contract value due to index performance
	- PH behavior: if surrenders are higher than expected, the insurer may have to sell assets to pay surrender values
	- if the index falls enough, the insurer may have to sell assets to meet collateral requirements on short puts
- operational risk
	- RILAs are sophisticated and require significant expertise in hedging, investments, ALM, and contract design
	- higher sophistication = higher risk of improper operational execution

Additional Considerations
- General vs separate account management
	- FA and FIA assets are typically held in the GA, while VA assets reside in the SA
	- GA assets are intermingled and not always allocated to a specific LOB
	- SA assets are more often allocated to a specific product/contract
	- RILA assets are held in both the GA and SA, and the approach is still emerging
- Reserves and regulations
	- RILAs follow VM-21 for US stat reserves
	- RILA RBC reqs follow thoes for VAs
	- The NAIC is developing a nonforfeiture standard for RILAs
	- Under US GAAP, the base RILA contract follows ASC 815, while any riders on RILAs are classified as MRBs under ASC 944