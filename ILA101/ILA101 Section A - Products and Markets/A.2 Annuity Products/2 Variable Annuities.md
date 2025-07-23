## **Variable Annuities (VAs)**

- Can be SPDAs or FPDAs, but virtually all VAs sold today are the SPDA form.
- Prems are invested in separate account (SA) assets such as stocks, bonds, balanced funds, and money market funds  
  - SAs have fewer regulatory investment restrictions than general accounts (which back fixed DAs, life insurance, etc.)
- PH bears all investment and IR risk since AVs vary directly with SA performance  
  - A basic VA eliminates C-3 risk for an insurer (vs. fixed DA)
- VAs may generate higher PH returns in exchange for the added risk
- VAs often include a fixed account (backed by GA) alongside variable options backed by the SA  
  - PHs can transfer money between fixed/variable accounts (subject to insurer-specific restrictions)

---

## **Product Guarantees**

### **DB Guarantees**
- Basic VA has little mortality risk since it pays AV on death (waives SCs)
- Most VAs are sold with additional **GMDB** riders for an added fee  
- GMDB designs include:
  - **Step-up**:  
    - GMDB = highest AV on any past anniversary – any WDs since that anniversary
  - **Roll-up**:  
    - GMDB = prems accumulated at a specific IR (typically 4–6%) minus WDs  
    - $$ \text{GMDB}_t = \text{GMDB}_{t-1} \times (1+r) + \text{Prem}_t - \text{WDs}_t $$
    - Often capped at 200% of prems and stops at age 75 or 80
  - **Combo**:  
    - $$ \text{GMDB} = \max(\text{Step-up}, \text{Roll-up}) $$
  - **% of Contract Gain at Death** (less common)  
    - Intended to pay tax due at death

> Note: GMDBs were initially underpriced due to lack of technology and experience.

---

### **Guaranteed Living Benefits (GLBs)**

- GLBs were developed after GMDBs to further stimulate sales.

#### GMIB
- Converts guaranteed amount into a **fixed lifetime annuity** upon exercise  
- Based on roll-up design  
- Mitigants: long elimination period, conservative annuitization rates  
- Low uptake due to annuitization requirement (PH loses access to AV)

#### GMAB
- Does **not require annuitization** or surrender to exercise  
- If AV < GMAB on payout date, AV is increased to GMAB level

#### GMWB
- Guarantees **WDs** even if AV drops to 0  
- AV is still available for surrender  
- Designed to solve GMIB problem (access to funds)

#### GLWB (Most Popular)
- Guarantees **lifetime** WDs (typically 4–6% of AV at first WD)  
- Solves limitation of GMWB (finite benefit base)

---

## **VA Product Charges**

- May include FELs, SCs, and periodic fees  
  - Surrender charges are more common than FELs today
- Additional **asset-based charges** to cover:
  - Mortality & expense guarantees
  - Admin expenses
  - Profit
  - Riders (DBs or GLBs)

---

## **VA Product Mechanics**

- More administrative complexity than fixed annuities
- Participation in each fund is tracked in **units**

### Fund Value  
- $$ \text{FV} = \text{Units in Fund} \times \text{Unit Value} $$

### Unit Calculations
- $$ \text{Units}_t = \text{Units}_{t-1} + \text{Units Purchased}_t - \text{Units WDn}_t $$

### Example: FEL
- Prem = \$150, FEL = 5%, unit value = \$10  
  - $$ \text{Units Purchased} = \frac{150 \times 0.95}{10} = 14.25 $$

### Example: WD with SC
- PH wants \$100, SC = 8%, unit value = \$10  
  - $$ \text{Units WDn} = \frac{100 / (1 - 0.08)}{10} = 10.87 $$

### Unit Value Adjustments (Net Investment Factor, NIF)

#### Open-ended SA structure:
- $$ \text{NIF}_t = 1 + \frac{\text{InvInc}_t + \text{UCG}_t + \text{RCG}_{t-1} - \text{Exp}_t}{\text{AV}_{t-1} + \text{Annuity Rsvs}_{t-1}} - \text{Daily Asset Charges} $$

#### Unit Investment Trusts:
- $$ \text{NIF}_t = 1 + \frac{\text{Ending Value of Shares} - \text{Beginning Value of Shares}}{\text{AV}_{t-1} + \text{Annuity Reserves}_{t-1}} $$  
- In both cases:  
  - $$ \text{Unit Value}_t = \text{Unit Value}_{t-1} \times \text{NIF}_t $$

### Dividends
- Dividends increase unit count to keep unit value stable

---

### **VA Annuity Payouts**

- Upon annuitization:
  - Initial payment:  
    $$ \text{Pmt}_0 = \frac{\text{AV}}{12\ddot{a}_x^{(12)}} $$
  - Future payments:  
    $$ \text{Pmt}_t = \text{Pmt}_{t-1} \times \frac{\text{NIF}_t}{(1+\text{AIR})^{1/12}} $$

- **AIR** = Assumed Investment Return  
- Since PHs dislike volatile payments, insurers offer:
  - Annual resets (convert each year to fixed annuity)
  - Floors (e.g. 80% of initial payment)
  - Floor = 100% + interest-free loan tracking  
    - If actual < floor → insurer pays extra  
    - Excess is repaid when actual > floor  
    - Loan forgiven at death

---

## **Pricing Considerations for Variable Deferred Annuities**

1. **Lapses**
   - Asset charges depend on AV
   - ITM level of guarantees affects lapse behavior

2. **Premium Persistency**
   - Hard to model
   - Long break-even periods

3. **Average Size**
   - Higher prems = more profit (expenses relatively fixed)

4. **Expenses**
   - Higher maintenance than fixed annuities
   - Commissions < life insurance
   - Acquisition costs recovered via asset charges (exposed to equity risk)

5. **Guaranteed Benefits**
   - GMDBs and GLBs require **stochastic pricing**
   - Hedging costs priced separately and added as fixed expense

---

## **Pricing Minimum Guaranteed Benefit Reserves**

- Most VAs have a minimum guaranteed DB
- Riskier than fixed annuities since AV can fall below the guarantee
- Insurers must hold a reserve for future payouts

Key pricing assumptions:
- **Fund allocation behavior** by PH (stocks, bonds, balanced, MM)
- **Mean/variance** of return by fund type  
  - Some insurers restrict investments for GLBs
- **Mortality**:  
  - GMDBs  
  - Lifetime payouts for GLWBs
- **GLB utilization**  
  - % of PHs exercising  
  - Amount of benefit used
