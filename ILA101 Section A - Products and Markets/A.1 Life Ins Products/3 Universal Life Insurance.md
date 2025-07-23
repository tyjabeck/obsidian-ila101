## Characteristics of Flexible Premium UL

- DB options  
- PWDs  
- Policy loans  
- Common riders  
- Compare nonforfeiture with WL  
- Approaches for UL crediting rates  
- UL COI scales  
- Expense and surrender charges  

### Key Pricing Assumptions

- Mortality  
- Lapse  
- Expenses  
- Interest  

---

## **UL Cash Values**

$$ 
CV_t = \left( CV_{t-1} + \text{Prem}_t - \text{Charges}_t \right) \left( 1 + r \right) 
$$

Spread compression occurs if interest rates fall, squeezing the insurer's spread.

---

## **UL DB Options**

1. Face only  
2. Face + CV  

Tax laws require a minimum amount of insurance, so DBs may have to increase if the CV grows large enough:

- *"Corridor"* factors are prescribed by law  
- DBs cannot be less than $\text{Corridor Factor} \times \text{CV}$  

---

## **UL Policy Loans**

Unlike traditional products, UL policies allow loans against the CV.

- The full CV (gross of loan) continues to receive credited interest  
- The loaned portion usually receives a lower credited rate  

---

## **UL Riders**

- Waiver (waives COI or a stipulated payment)  
- Accidental death  
- Guaranteed insurability  
- Spouse or other insured rider  
- Child rider  

Like term, living benefit riders are increasingly being sold with UL.

---

## **UL Nonforfeiture Options**

- UL policies do not have the same explicit nonforfeiture options as WL  
- A UL policy behaves like extended term when the policyholder stops paying premium  
- A UL policy can resume paying premiums anytime, effectively reinstating the policy  

---

## **UL Interest Rates**

- Current rates are at the company's discretion (may be declared monthly)  
- Sometimes rates are guaranteed for 1 year  

**Approaches for declaring rate:**

1. **Portfolio rate** – All fund values on all policies get the same rate  
2. **New money rate** – The timing of premium payments determines which rate that portion of the fund receives  
   - Requires tracking the assets associated with each premium payment  

- The portfolio approach is the simplest to explain and administer  
- PHs favor:
  - Portfolio approach when interest rates are *falling*  
  - New money rate when rates are *rising*  
    - The portfolio rate falls more slowly since it’s influenced by past asset yields  

---

## **UL Mortality (COI) Charges**

- Guaranteed COI rates are based on attained age  
- Current COI rates can be attained age or S&U  
- Using attained age mortality for *select* risks increases early-year revenue  
  - Called a *reverse S&U scale*  
- S&U mortality is used to compete with term insurance (keeps early COI low)  

---

### **SGUL / ULSG**

**Secondary Guarantee** = Policy is guaranteed not to lapse if a minimum premium funding requirement is met.

#### Minimum No-Lapse Premium (MNLP) – Basic ULSG Design

- SG is based on whether cumulative minimum premiums have been paid  
- MNLP premiums generate little or no CSV  

#### Shadow Account Design

- Guarantees policy stays inforce if shadow account $> 0$  
- Shadow account behaves like a CV with separate charges/credits  
  - Not available as surrender value  
  - Can be positive while CSV is negative  
- Designs can be complex with multiple shadow accounts  
- May be lapse-supported  

---

## **Reserve Implications – Model Regulation 830 ("XXX") and AG 38 ("AXXX")**

- Pre-XXX/AXXX, ULSG statutory reserves were too low for regulators  
- AXXX increased reserves → insurers needed financing (e.g. captive reinsurance)  
- AG 48 created to standardize AXXX reserve relief  
- VM-20 should replace XXX/AXXX and simplify ULSG design  

---

## **ULSG and the Settlement/Investor-Owned Market**

- Investors may buy policies and pay only the minimum premiums until insured's death  

---

## **Indexed Universal Life (IUL)**

- Offers minimum guaranteed crediting rate (like UL) plus index-based interest (e.g. S&P 500)  
- Index interest is subject to a **participation rate**, **cap**, and **floor**  

$$
\text{Index Crediting Rate} = \max \left[ \min \left( \text{Index Change} \times \text{Participation Rate}, \text{Cap} \right), \text{Floor} \right]
$$

**Common Index Change Methods:**

1. **Point-to-point** – Based on index change between start and end of segment  

   $$
   \text{Index Change} = \frac{\text{Index at End of Segment}}{\text{Index at Beginning of Segment}} - 1
   $$

2. **Averaging** – Based on average of monthly values  

   $$
   \text{Index Change} = \frac{\frac{1}{12}\sum_{m=1}^{12}\text{Index}_m}{\text{BOY Index}} - 1
   $$

- AG 49 created to guide crediting rates in IUL sales illustrations  

---

## **Fixed Premium UL (FPUL)**

- Also called *interest-sensitive whole life*  
- Functionally like WL but credited rate can change  
- Premiums are fixed  
- Fund is typically credited interest annually  
- CSV is the greater of:  
  1. Minimum guaranteed CV  
  2. Accumulation account net of surrender charge  

### **Vanishing Premium FPUL**

- Most popular FPUL design  
- Premiums similar to par WL  
- Premiums stop when:  
  - Actual CV > minimum guarantee, or  
  - Actual CV > net single premium (based on current assumptions)  

---

## **Advantages of FPUL Over Flexible Premium UL**

1. From PH perspective – Contract offers more guarantees (like WL)  
2. From agent perspective – Higher commissions on fixed premiums  
3. From company perspective – Fixed premiums encourage persistency  

## **Disadvantages of FPUL Over Flexible Premium UL**

1. Lack of premium flexibility  
2. Administrative complexity of accepting extra premiums  
3. Vanishing premiums may not vanish under low interest rates  

---

## **Single Premium UL (SPUL)**

- PH pays a large lump sum upfront  
- Investment-oriented sale  
- Single-premium FPUL offers guaranteed CVs and DBs regardless of fund performance  
- “Net rate products” use high interest margins instead of explicit COI  
- 1980s tax legislation restricted large UL contributions  

---

## **Group UL (GUL)**

- Marketed to large employers/employees  
- Premiums often paid via payroll deduction  

### **Advantages of GUL Over Individual UL**

- Regulatory flexibility: can change expenses on group basis  
- Coverage in 30+ states via multiple employer trust  
- Group features: experience ratings, guaranteed issue underwriting  

---

## **Pricing Considerations for UL**

- Challenging due to flexibility (DBs, PWDs, changing interest rates)  
- Sensitivity testing: actuaries should test various scenarios  

---

## **UL Sources of Profit**

1. **Investment:**  
   $$
   \text{Interest Earned} - \text{Interest Credited}
   $$

2. **Mortality:**  
   $$\text{COI Charges} - \text{DBs Paid}$$

3. **Expenses:**  
   $$
   \text{Expense Charges} + \text{Surrender Charges} - \left( \text{Expenses} + \text{Commissions} \right)
   $$

---

## **UL Asset/Liability Analysis**

If rates rise, insurers may suffer capital losses (disintermediation risk):

- PHs may withdraw CVs and invest elsewhere  
- Market value of UL assets falls as rates rise  
