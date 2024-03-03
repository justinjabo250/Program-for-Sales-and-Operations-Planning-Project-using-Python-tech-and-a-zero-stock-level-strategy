# Program-for-Sales-and-Operations-Planning-Project-using-Python-tech-and-a-zero-stock-level-strategy


### In order to meet the business needs and improve decision-making based on data analytics, the project I work on will involve developing a sales and operations planning software program using a zero-stock level strategy and Python technology. Ultimately, the program will be able to ask the user to enter information based on the business criteria and the insightful information we want to gain and collect from the data:


------------------


**I've included all of the business requirements here so that we can create software that will meet the intended business needs and be viewed favorably by managers and stakeholders who will be using the data to extract insightful information and patterns from it.**


**I've added the useful data that the user will be required to provide for this software here:**


**- An initial stock level for a product**

**- The number of month(s) to plan**

**- The planned sales quantity for each month**

**Based on this data, calculate the required production quantity as follows:**

**- If the sales quantity is smaller than the stock level of the previous month, the production quantity is 0**

**- If the sales quantity is larger than the stock level of the previous month, the production quantity is this difference.**


------------------  

**An example of how the software we will be building is run is shown below.**


**Here is a visual of an input.**



**>>> Please enter an initial stock level: 500**

**>>> Please enter the number of months to plan: 5**

**>>> Please enter the planned sales quantity for month 1: 300**

**>>> Please enter the planned sales quantity  for month 2: 250**

**>>> Please enter the planned sales quantity  for month 3: 200**

**>>> Please enter the planned sales quantity  for month 4: 400**

**>>> Please enter the planned sales quantity  for month 5: 100**


**This is the result(outcome) of the program after it has been run(executed).**


**`The resulting production quantities are:`**


**>>> Production quantity month 1 - 0**


**>>> Production quantity month 2 - 50**


**>>> Production quantity month 3 - 200**


**>>> Production quantity month 4 - 400**


**>>> Production quantity month 5 - 100**


------------------------


**Why are those production quantities calculated?**


**The initial stock level is 500.**

**In the first month 300 pieces are sold.**


**Therefore, nothing needs to be produced and the resulting stock is 200 (= 500 - 300).** 


**In the second month 250 pieces are sold.** 


**The stock level after the previous month is 200.**


**Therefore 50 pieces need to be produced. The resulting stock level is 0 (= 200 + 50 - 250).**


**In the third month 200 pieces are sold. The stock level after the previous month is 0.**


**Therefore 200 pieces need to be produced. The resulting stock level is 0 (= 200 - 200).**





