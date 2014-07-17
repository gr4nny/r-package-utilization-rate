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
