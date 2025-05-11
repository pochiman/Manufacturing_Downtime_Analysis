# Manufacturing Downtime Analysis

## The Situation
You work as a Production Manager for Wolf Cola, a soft drink company that handles all its manufacturing operations in Philadelphia. 

## The Assignment
Frank, the former manager, kicked off a productivity improvement project for the bottling production line and left an Excel file with the data he collected.
Your task is to analyze the productivity and downtime data he left and find ways to work with the operating staff to improve the line's efficiency.

## The Objectives
1. Calculate line efficiency
2. Identify main downtime factors
3. Calculate downtime by operator and factor

## The Data Set

#### Manufacturing Downtime
Productivity & downtime data for a soda bottling production line, including information on the operator, product, start & end times, and downtime factors for each batch.

#### Recommended Analysis
1. What's the current line efficiency? (total time / min time)
2. Are any operators underperforming?
3. What are the leading factors for downtime?
4. Do any operators struggle with particular types of operator error?

#### Objective 1: Calculate line efficiency
Your first objective is to calculate the efficiency for a production line and break it down by operator.

* Create a new "Batch time" column in the "Line Productivity" tab that calculates the minutes between the "Start time" and "End time".
* Create a new "Min batch time" column by looking up the value from the "Products" tab.
* Calculate the "Efficiency" (sum of "Min batch time" / sum of "Batch time") for each operator.
* Visualize the data using a bar chart.
* Use the chart title and formatting to make a recommendation.

#### Objective 2: Identify main downtime factors
Your second objective is to use a Pareto chart to identify the main factors for downtime in the production line.

* Create a "Downtime" column in the "Downtime factors" tab that sums the downtime for each factor from the "Line downtime" tab.
* Sort the factors in descending order by downtime.
* Create a "Pareto" column that calculates the % running total of downtime for each factor.
* Create a Pareto chart for the downtime factors.
* Use the chart title and formatting to make a recommendation.

#### Objective 3: Calculate downtime by operator & factor
Your final objective is to use a matrix to calculate the total downtime by operator for each of the main factors you identified.

* Create a matrix with the operators as the rows and the main downtime factors as the columns.
* Add an "Operator" column to the "Line downtime tab" and look up the values for each batch.
* Calculate the total downtime for each operator by factor.
* Apply conditional formatting to highlight main downtime factors by operator.
* Use the chart title and formatting to make a recommendation.

#### [Project Link]()