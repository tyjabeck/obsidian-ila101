When mortality is worse than the standard class, extra charges and/or premiums are needed. Two approaches:

1. **Flat extra** – Additional premium per $100  
   - May be temporary  
   - May be used to cover hazardous situations or occupations  
2. **Table rating** – An additional percentage of standard mortality (most common)

## **Methods for Determining the Level of Extra Mortality**

1. **Numerical rating system** – Assigns credits and debits for various underwriting factors. The net sum of all credits and debits determines the level of extra mortality required (after applying judgment to ensure it's reasonable)  
   - **Criticisms** – Too arbitrary; debits and credits may not properly evaluate risk  
2. **Advance in age** – Issue a policy at a higher age  
3. **Lien method** – Death benefit starts as a fraction of the face amount and increases over time  
4. **Return of premiums (ROP)** – Death benefit = ROPs if death occurs in the first $n$ years  
5. **Charge extra premiums and have different nonforfeiture values** – Only suitable for companies with sufficient experience to justify

## **Substandard Rating Classes**

Must first decide on the number of classes and the mortality range for each class. After establishing mortality ranges, the actuary can calculate the gross premiums for each class.

## **Substandard Mortality Considerations**

Start with the tables used for the company’s standard business. Reflect the number of classes and the distribution within each class. Modify the mortality table to reflect that the ratio of substandard to standard mortality is not constant across all ages (constant multiples tend to overstate mortality at higher ages).

## **Subdividing Standard Business**

Since substandard business is a small percentage of total business, creating subdivisions for gender, smoking status, etc., may not make sense (credibility too low).

1. **By male/female**  
   - Female rates can be created from male rates using a setback period  
   - Evidence suggests the gender differential is smaller for survivorship than for single life (e.g., a 3–5 year setback may be more appropriate than the usual 6–8 years)  
2. **By smoker/non-smoker**  
   - The company may develop a schedule of smoker premiums, then "forgive" 1–2 classes for non-smokers  
3. **By plan**  
   - The higher the substandard rates are relative to standard rates, the higher the lapse and not-taken rates  
   - Steeply sloped substandard scales will result in higher sales (since initial premiums are lower)

![[Pasted image 20250716103320.png]]

## **Methods for UL:**

1. Charge higher premium  
2. Reduce coverage

## **Methods for Single Premium Life:**

1. Increase percentage limit for standard to absorb first few substandard classes  
2. Reduce coverage

## **Expenses for Substandard Business**

**Approaches for allocating extra expenses on substandard business:**

1. Allocate across all business (standard and substandard)  
2. Allocate only to substandard  
3. Some combination of 1 and 2 (most common)

**Types of expenses:**

- **Premium taxes and commissions**  
   - Allocate directly to substandard since these are a percent of premium  
- **Acquisition expenses**  
   - Substandard business generally requires more underwriting, and the expense increases with issue age  
- **Maintenance expenses**  
   - Generally the same as standard business  
   - Additional expenses may be incurred for frequent requests to reduce/remove ratings

## **Substandard Not-Taken and Lapse Rates**

- Not-taken and lapse rates are higher for substandard policies  
- The higher the ratio of substandard to standard premiums, the higher the not-taken rate  
- Some companies reflect the higher not-taken rates by allocating those expenses directly to substandard policies (though this increases the premiums, making not-taken rates even higher)  
- Higher lapses are generally unfavorable if they occur early but may be favorable if they occur later

## **Extra Cost of Extended Term and Reduced Paid-Up Insurance**

Extended term and reduced paid-up are nonforfeiture options on traditional (WL) policies:

- **Extended term** – Stop paying premium, but preserve the death benefit; policy stays in force as long as cash value can support the death benefit (unlike a UL where the policyholder is not paying any premium)  
- **Reduced paid-up** – Stop paying premium and reduce the death benefit until current CSV = single premium for new DB (results in a smaller paid-up policy)

Extended term experiences the highest anti-selection (insureds in poor health will prefer the higher death benefit):

- Therefore, this option may not be offered for highly substandard risks  
- If offered, the insurer may use a higher mortality assumption for the extended term period (CSV will erode more quickly)

## **Substandard Premium Paying Period**

For public relations, it can be helpful to limit the substandard premium period to age 65 or 20 years, whichever is longer, so that the total premiums paid don't exceed the face value of the policy. For hazardous activities, it makes sense to remove the rating after a period of years.

## **Substandard Gross Premium Calculations**

The extra gross premium charged to substandard insureds is the difference between the rated GP and the standard GP:  
$$GP_R - GP$$  
where both GPs are calculated as:  
$$
GP = NP(1 + \text{ClaimCost\%}) + \frac{\text{AcqExp}}{\ddot{a}_{x:n}} + \text{OtherMaintExp} + \text{GP(\% Prem Exp)}
$$  
using the rated and standard versions of each term when calculating the respective GPs (e.g., higher mortality and expenses used for rated GP)

$$ \text{NP = net annual prem for future DBs only} = \frac{1000A_x}{\ddot{a}_{x:n}} $$  
$$ n = \text{prem-paying period (if not for life)} $$  
$$ \text{ClaimCost\% = per policy cost to process death claims} $$  
$$ \text{OtherMaintExp = recurring dollar expenses to administer the policy} $$  
$$ \text{\%PremExp = recurring maintenance expenses that are a \% of prem (prem tax, commissions)} $$  
$$ \frac{\text{AcqExp}}{\ddot{a}_{x:n}} = \text{upfront acquisition expenses converted to level prem (increase policyholder prem to recover acquisition costs)} $$

## **Substandard Cash Values**

Substandard cash values are only slightly higher than standard:

- Prevents the premium from being any higher than necessary to cover the substandard mortality cost

To further reduce the CV of substandard policies, a company can reduce substandard premiums.

## **Substandard Asset Share Tests**

Asset share = assets accumulated by a policy at a given duration. Essentially a profit measure because asset share is higher for policies where cumulative premium inflows exceed cumulative outflows.

**Tests:**

- Evaluate product provisions (e.g., nonforfeiture)  
- Modify premiums to produce desired surplus/profit goals  
   - E.g., target having asset share $\geq$ CSV by EOY 20  
- Fit premiums to target surplus objectives at various ages  
- Check premiums for accuracy and reasonableness

## **Other Considerations**

- Supplementary benefits (e.g., waiver) may be offered to moderately substandard risks, but not highly substandard risks  
   - Typically charge a multiple of the basic charge  
- Some companies allow ratings to be removed in the future if the insured qualifies with evidence of insurability  
   - This means you should assume insureds with improved mortality will exit the substandard pool in the future, leaving only the worst substandard risks
