### Pricing Considerations for Term Insurance

---

## **Term Mortality**

The net amount at risk (NAR) for a term product is higher than permanent (term reserves are lower since they typically don't fund a cash value).

- $\text{NAR} = \text{Face} - \text{Reserve}$

In aggregate, term mortality is usually lower than permanent insurance mortality:

1. Term has a higher average size than permanent; overall mortality is usually lower on large policies.  
2. Term mortality exposure is weighted more to the select period (recently underwritten), when mortality is lower:  
   3. Term has higher ultimate lapse rates than permanent, so there's less exposure to higher ultimate mortality.  
4. Less healthy lives that choose to convert will shift worse mortality experience from term business to permanent.

---

### Results from Most Recent SOA **High Face Amount Mortality Study**

1. Changes to reserve requirements (VM-20) will cause product design to change, potentially affecting mortality experience.  
2. Large-face term experience was worse than large-face permanent experience.  
3. Mortality improvement varies by gender and smoker status:  
   - Males have higher mortality rates than females and smokers.  
4. Large policy mortality was more favorable than for "all amounts."  
5. Female experience was higher in aggregate for large-amount policies than for all policies.  
6. Experience varied by amount band, with the best experience in the $1M+ category—likely due to stricter underwriting.  

---

Healthy lives tend to lapse term policies when the need for insurance goes away:

- Creates a challenge for increasing premiums (e.g., ART).  
- Mortality can deteriorate quickly in the post-level period as healthy lives shock lapse, leaving only the highest mortality risks inforce.  
  - This can be modeled with the **Dukes-MacDonald selective lapsation model**, which is based on the **conservation of deaths** principle.  
  - Conservation of deaths assumes the weighted average of mortality across multiple groups equals the normal mortality.

---

## **Considerations for Older Ages**

- Lack of credibility in mortality experience for ages 85+.  
- Policy size is much larger, and underwriting is more extensive.  
- "Widow effect" – proportion of females tends to be higher since males die earlier.  
- Select period may wear off.  

---

## **Term Persistency (Lapse)**

Lapse rates are a critical pricing factor:

- Lapse rates can affect mortality (anti-selection).  
- High early lapses make it harder to recover acquisition costs.  
- High late lapses may erode expected profits.  

---

## **Underwriting**

- Similar to permanent insurance underwriting.  
- Substandard insurance is less available for term than for permanent products.  

---

## **Compensation**

- Typically lower than for permanent insurance since term premiums are lower.  
  - Also, lower renewal commissions.  
- "Recycling" commissions may be paid to agents at each policy renewal.  

---

## **Term Expense and Inflation Assumptions**

- Expenses are a large percentage of premium.  
- Term profitability is highly sensitive to expense allocation:  
  - More overhead allocated to term = lower profits.  
  - Profit as a % of first-year premium is high for ART plans, low for level/decreasing term.  
    - ART = Annually Renewable Term (early premiums are much lower).  
- High inflation can erode term profits:  
  - Term has minimal assets backing it, unlike permanent insurance.  
  - Permanent insurance assets (to fund CSV) help offset inflation.  

---

## **Reserving**

- Significant impact on profitability.  
- PBR VM-20 (adopted in 2017) should eliminate need for complex financing mechanisms to meet Regulation XXX reserves.  

---

## **Legal and Regulatory Issues**

- The term insurance market is regulated at the state level.  

---

## **Term Conversion Options**

**Conversion** = policy is converted from one type to another, normally with the same face amount.

- Most common: convert term to WL with same rating, no additional underwriting.  
- More common for level term than decreasing term (which is prone to anti-selection).  

---

### **Managing the Cost of Conversions**

- Policyholder’s cost can be reduced by using the terminal reserve to fund part of the premium:  
  - i.e., company applies reserve from original policy to the new premium.  
- Company’s cost can be offset by paying commission only on discounted premium.  

---

### **Benefits of Conversions**

- Helps increase sales by making the product more attractive.  
- Promotes persistency by keeping healthy lives with the company.  
- Permanent insurance is generally more profitable than term.  

---

## **Guaranteed Insurability Option (GIO)**

Gives PH the option to increase face amount without additional underwriting.

- Higher anti-selection risk than conversions.  
- GIO is usually only exercisable at specific times.  

---

## **Three Philosophical Approaches to Charging for Options**

1. Only policyholders who exercise the option bear the cost.  
2. All policyholders who want the option available pay a higher premium from the start.  
3. All policyholders pay a higher premium regardless of interest in the option.  

---

## **Assumptions Needed to Price for Options**

- Proportion of insureds expected to elect the option.  
- Percentage of coverage available to be exercised.  
- Lapse assumption – typically low after option exercise.  
- Mortality – usually high when election rate is low or when it's a "last chance" conversion.  
  - *"Last chance"* = conversion just before expiration of the option.  

---

## **Conversion Formulas from Appendix 1-I**

**PV at age $x$ of the extra mortality cost of a policy converted at year $r$:**

$$
A_{x,r} = {}_rp_x \times e_{x,r} \times K_{x,r} \times v^r
$$

Where:

$$
K_{x,r} = \sum_{t=1}^{\infty} \left( {}_{t-1}p_{x+r} \right) \left( v^t \right) \left( q^C_{x+r+t-1} - q^S_{x+r+t-1} \right) \bar{AR}_{x+r+t}
$$

- $q^C$ = mortality rate for converted policy  
- $q^S$ = mortality rate for standard policy  
- $\bar{AR}$ = amount at risk each year  
- $e_{x,r}$ = probability a policy converts in duration $r$  
- $r$ = duration since policy issue  
- $t$ = duration since conversion date  

---

## **Option Pricing Formulas from Appendix 1-II**

### Total cost of options at issue = sum of:

1. **Company’s cost of options elected for any single duration:**

$$
\text{Credits to Policyholders} + \left( \frac{\text{Option Handling Expense}}{\text{Avg Units Issued Per Policy}} \right) \left( \frac{\text{Units Electing Option}}{\text{Radix}} \right)
$$

2. **Cost associated with prior years:**

$$
\sum \left( \frac{\text{Units Electing Options}}{\text{Radix}} \times \text{Percent of Face Converted} \times \text{Option Charge} \right)
$$

- **Radix** = total number of units issued  

