r-package-utilization-rate
==========================

This is going to be a package for the evaluation of utilization rates.

The basic premis of this package will be to evaluate how changes to the utilization rate of an indpendant variable effect the value of a dependent variable over time. At the end of each period the significance of the change will be evaluated. 


### Inputs

1. Source of Data
  * This will be columnar data including at least: date, independant variable, dependant variable
  * An optional column will allow grouping of data
2. Period of oberservation
  * The period of observation will determine how the time is divided 
  * Initial options will be day, week, month
3. P Value
  * Default value will be 0.05
  
#### During exection of the routine the following inputs will be requested

1. Select Baseline from list of all values in indepent variable column
2. Select Variable of Interest from list of all values in indepent variable column
3. Utilization as % of all data or baseline only
4. Check significance of change against original baseline period or current period
5. Generate table or graph
  * if graph, select type


### Outputs
There will be two main output categories: tables and graphs

1. Tables
  1. Summary of Entire Dataset
  2. Summary of Group Data
  3. Periodic Changes in Dependent Variable 
    * P-Values marked
2. Graphs
  1. % Utilization and Dependent Variable by Period 
    * P-Values marked
  2.  % Utilization or Dependent Variable and Groups by Period 
    * P-Values marked
  



```
Not sure where to put these ideas:
Calculation of number of days to reach significance
Best to Worst perfomers on siginicance of utilization
```

##### Sample dataset summary
This is a summary of the sample dataset to feed into the routine to test how it works.

| Sites | Number of Days | Independent Vars | Dependent Vars | Notes|
|----|----|----|----|----|
|Miami |180 days| Home / Restarant | Cost of 3 meals per day| No eating out in the first 30 days |
|Charleston | 270 days | Home / Resturant / Farm Coop| Cost of 3 meals per day| Restaurant at 30 days, Farms at 60 |


<<<<<<< HEAD
=======




  
>>>>>>> parent of 957932c... Update README.md
