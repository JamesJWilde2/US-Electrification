# Which locations in the United States are the best candidates for electrification?

**Background**

This is a short analysis I completed for a thought exercise that asked me to use a handful of metrics to determine which counties or census-incorporated places in the United States were the best candidates for electrification. 

**What is electrification?**
- In this context, electrification just refers to the replacement of technologies that run on fossil fuels with technologies that run on electricity.
- Electrification is pretty crucial for reducing greenhouse gas emissions and improving air quality, driving energy efficiency and cost savings, and also fostering innovations and job creation.

For the analysis, I used R to merge two datasets, transform multiple variables, and then create a relatively simple composite index value. Check out the notebook file for the full analysis.

The final product:
#
<img width="984" alt="Screenshot 2024-07-16 at 8 52 40 PM" src="https://github.com/user-attachments/assets/a824bc81-9670-4044-a4bd-9a6edf061f73">
[Link here.](https://public.tableau.com/views/Testindex/Dashboard1?:showVizHome=no)

#
**How did I determine which counties would benefit the most from electrification?**
The short version is that I combined four measures (see data readme file for details on these):
1. HVAC energy consumption
2. Remaining solar generation potential
3. Household income spent on energy bills
4. Households using delivered fuel for heating

#
**The big takeaway?**
#
**Los Angeles County is possibly the best candidate for electrification efforts!**

(Further analysis, of course, could take into account many additional variables and factors.)
