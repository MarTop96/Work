## Thursday, 2 February 2023

Doing my study thing for intro to the company. Learning objectives. Who we are, What we do etc.

**[CNHi Purpose](CNHi%20Purpose.md)** of 1. BREAKING NEW GROUND, centres on innovation, sustainability and productivity. (MAIN PURPOSE)

**[CNHi Challenges](CNHi%20Challenges.md)** (number is commitment level, lower is better, closer to 0):

**(2) Zero Hunger, end hunger:** achieve food security and improved nutrition and promote sustainable agriculture

**(3) Good Health and Well-being:** ensure healthy lives and promote well-being for all at all ages.

**(8) Decent work and economic growth:** Optimal working conditions, preventative/protective workplace measures minimizing risk of injury.

**(10) Reduced Inequalities:** Consciously supports projects and activities that encourage economic, social and cultural development of local communities. Socially responsible manner, respecting culture/tradition. Advocating socially and environmentally responsible behaviour across entire supply chain.

**(12) Responsible Consumption and Production:** Environmentally/Socially responsible use of resources, efficient and reduced impact on environment.

**(13) Climate Action:** Actively engaged in reducing CO2 and other air emissions.

Got given the task of making sure that the SalesForce/SAP entities names align with whats on the invoice, ABN check, and that the entity name on ABN lookup matches. If they don’t match, then have to mark it as System Update Required, and Invoice Update Required.

Example:
![775x140](Vendor%20Alignment%20Task.png)


**Process**:
1. Basically open up an invoice for entity
2. input the ABN into ABN IN INVOICE column
3. input the supplier name in NEXT column
4. BSB -Acc. No.
5. Then ABN Lookup and make sure its valid
6. Make sure the entity name matches the First Column Name
7. If not Mark the column Either Yes or No
8. If No, Update with new Entity Name
9. Check if SalesForce (first column) and MASTER SAP (worksheet 2) have corresponding entity name.
10. If no, mark the system update requirement correspondingly.
11. Mark Invoice as needing update if needed.


**Diary Addition:** 
First 4 hours, had nothing to do, teams were super busy and had to wait for allocation.

Did [onboarding modules](Severely%20out%20of%20Date.md). Finding other recommended modules pointless. Why would I do them? I dont really get anyting from them, theres no incentive, not required and not even marked or given feedback.

After lunch got given my first task. Reconcile suppliers, fix the previous persons mistakes.
1. Check invoice for Entity Name, ABN
2. ABN Lookup if entity name matches ABN lookup cool. If not check SF and SAP for match.
3. If no match update either/both.
4. Update Invoice if needed.

Tedious process. [Faster Ways?](Efficiency.md)