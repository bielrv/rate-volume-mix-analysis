# Rate vs Volume Mix Analysis

It is common in business to analysis Month over Month (MoM) Key Performance Indicators (KPIs). These variations requiere, oftentimes, a deeper understanding other than the total change.

## Reasons of KPI variations

**Variation** =  Rate * Volume

where:

**Rate:** Depending on the KPI, the rate could be the CPA, Price, Approval Rate (AR) and basically any value per unit.

**Volume:** Depending on the KPI, the volume could be the number of sales, applications Through The Door (TTD),...

### Mix Variance

When several channels, products, rates or type of clients are involved a deeper analysis is desired in order to truly understand the reason a certain KPI varies. In those cases:

**Variation** = (Rate<sub>1</sub> x Volume<sub>1</sub>) + (Rate<sub>2</sub> x Volume<sub>2</sub>) + ...

 Here the each volume has a weight such that:

 **Weight**<sub>1</sub> = Volume<sub>1</sub> / Total Volume  
 **Contribution**<sub>1</sub> = Rate<sub>1</sub> x  Volume<sub>1</sub>

<img src="https://latex.codecogs.com/svg.latex?\text{Weight}_1 = \frac{\text{Volume}_1}{\text{Total Volume}}"/>   
<br>
<img src="https://latex.codecogs.com/svg.latex?\Medium&space;\text{Δ Weight}_1 = \text{Vol}_1@PM - \text{Vol}_1@CM"/>    
<br>
<img src="https://latex.codecogs.com/svg.latex?\Medium&space;\text{Δ Rate}_1 = \text{Rate}_1@PM - \text{Rate}_1@CM"/>  
<br>
<br>
*PM* – Previous Month  
*CM* – Current Month

Now we can finally calculate the **Rates variations** and the **Volumes variations** impact on a particular KPI. Thus being able to exactly quantify what is going on behind that single KPI value.

![Rate1](https://latex.codecogs.com/svg.latex?\Medium&space;\text{Rate}_1\text{ Impact} = \text{Δ Rate}_1 * \text{Avg Weight}_1)

<img src="https://latex.codecogs.com/svg.latex?\Medium&space;\text{Weight}_1\text{ Impact} = \text{Δ Weight}_1 * \text{Avg Rate}_1"/>
