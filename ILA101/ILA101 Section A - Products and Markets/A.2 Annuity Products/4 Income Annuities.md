- An income annuity makes guaranteed periodic payments for a specified period of time (a certain period and/or life)
- Most are funded by a single prem
- Payments usually start immediately but are sometimes deferred

**Types of Income Annuities**
1. Payment Certain - guarantees payments for a fixed period. Provides fixed income for individuals, endowments, and funding agreements
2. Annuities Arising from "specialty markets"
	1. Structured settlements
	2. Lottery winnings
	3. Gift annuities
	4. Reverse mortgages
3. Life Contingent
	1. Life only - pays as long as annuitant is living
		1. used for retirement benefits
	2. Life with $n$ years certain
		1. Makes payments for $n$ years guaranteed, then continues as long as annuitant is living
	3. Unit refund - converts the initial cash value into a number of annuity units
		1. $\text{Unit balance at annuitization} = \frac{\text{Cash Value}}{\text{Unit Value at Issue}}$
		2. $\text{Units per payment} = \text{initial annuity payment} / \text{unit value}$
			1. unit value is constant for fixed income annuities, but can change period to period for variable income annuities
		3. over time, the unit balance falls
			1. $\text{Unit Balance}_t = \text{Unit Balance}_0 - t \times \text{Units Per Payment}$
		4. upon death of an annuitant, the beneficiary receives the value of the remaining unit balance
	4. Joint and survivor - based on 2 lives
		1. after the first death, the payment may change

**Fixed vs Variable Payments**
- fixed payments never change
- variable payments change monthly based on the investment return of the assets backing the annuity
	- $$ \text{Pmt}_0 = \frac{\text{Account Value}}{12\ddot{a}_x^{(12)}} $$
	- $$ \text{Pmt}_t = \text{Pmt}_{t-1} \times \frac{\text{NIF}_t}{(1+\text{AIR})^{1/12}} $$
- while variable payments provide the opportunity for increasing income, payments may fall
	- may be difficult for retirees
	- may be too psychologically undesirable

**Pricing Considerations for Income Annuities**

1. Interest rates - discount future liability cash flows using a spot rate curve
2. Mortality - reflect known and assumed characteristics of the annuitant population (gender, etc.)
	1. Assume mortality *improvement* for added conservatism (e.g. decrease 1% a year)
	2. substandard mortality methods:
		1. rated age mortality (most common)
		2. constant multiple mortality
		3. constant extra deaths - produces the highest mortality of all 3, but unlike the other 2, mortality grades down to stnadard over time
3. Premium taxes, expenses, and commissions
	1. Premium taxes and commissions are charged up front (since most products are single prem)
	2. Admin charges may be deducted from benefits
	3. Asset charges may be deduced from variable payout annuities
4. Surplus strain
	1. Initial reserve is likely to exceed prem paid
	2. Affects ROI and profitability