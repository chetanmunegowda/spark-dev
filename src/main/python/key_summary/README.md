## key-summary

###For a given key calculates the following for the value: running total, average, count, min & max

**Files**  
1. key-summary.py: Python code  
2. key-summary.sh: Shell script wrapper for passing the arguments to key-summary.py  

**Assumptions**  
1. Tab separated records  
2. Tested with Python 2.7.6, Apache Spark 1.6.0, Hadoop 2.7.1  

**Example**  
*Data Fields*  
location, branch_name, branch_code, staff_strength  
*Data Sample*  
Kolkata\tChowringhee Road\tSBT000897\t233  
Kolkata\tBowbazar\tSBT000076\t198  

If we wish to investigation the *staff_strength* per *branch_name*, then **key=branch_name** and **value=staff_strength**.  
Check the code documentation for the comments.  

