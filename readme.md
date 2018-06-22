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
<br><br>
![Weight](https://latex.codecogs.com/svg.latex?\text{Weight}_1%20=%20\frac{\text{Volume}_1}{\text{Total%20Volume}})
<br><br>
![Delta Weight](https://latex.codecogs.com/svg.latex?\Medium&space;\text{%CE%94%20Weight}_1%20=%20\text{Vol}_1@PM%20-%20\text{Vol}_1@CM)    
<br>
![Delta Rate](https://latex.codecogs.com/svg.latex?\Medium&space;\text{%CE%94%20Rate}_1%20=%20\text{Rate}_1@PM%20-%20\text{Rate}_1@CM)  
<br>
*PM* – Previous Month
<br>
*CM* – Current Month
<br><br>
Now we can finally calculate the **Rates variations** and the **Volumes variations** impact on a particular KPI. Thus being able to exactly quantify what is going on behind that single KPI value.

![Rate Impact](https://latex.codecogs.com/svg.latex?\Medium&space;\text{Rate}_1\text{%20Impact}%20=%20\text{%CE%94%20Rate}_1%20*%20\text{Avg%20Weight}_1)
<br>
![Weight Impact](https://latex.codecogs.com/svg.latex?\Medium&space;\text{Weight}_1\text{%20Impact}%20=%20\text{%CE%94%20Weight}_1%20*%20\text{Avg%20Rate}_1)
