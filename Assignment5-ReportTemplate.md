**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       | 2 |
|-----------------|---|
| Student Names:  |   |
| Kyle Hasan      |   |
| Evyn Rissling   |   |
| John Abo        |   |
| Andres Caicedo  |   |

# Introduction
The purpose of this lab assignment is to familiarize with different reliability assessment tools. Two methods will be explored; Reliability growth testing will be done using CSFTRAT tool to analize failure data. Reliability demonstration chart will be done using an Excel macro. The tools will be examined, analized and compared.
# 

# Assessment Using Reliability Growth Testing 

# Assessment Using Reliability Demonstration Chart 
Assessing this hypothetical System Under Test we used the provided RDC excel spreadsheet. First, we substituted the demonstration data with the given data points, combining the time intervals in sets of two and accumulating the errors detected at that point. We could begin to define the minimum acceptable threshold for system errors giiven the acceptable ranges. 

The first point at which the system is acceptable is when a maximum amount of 81 errors are found through 200 number of input events []. Next we explore different MTTF by either increasing/decreasing the maximum acceptable errors or the input event intervals.  
# Lower MMTTF 
[]
# Higher MTTF
[]
# Middle MTTF
[]

What is evident in these plots is that as the acceptable number of failures increases, the program becomes more acceptable for use, and as the MTTF decreases, the program must be rejected for the amount of failures that occur during the runtime. This is reasonable considering that the MTTF is a measurement of the overall time that a system runs, divided by the number of failures or defects. 

In order to determine the minimum MTTF, we tested the failure data with different MTTF values until we arrived at a plot where the last failure data was just hardly crossing into the accepted plot range.

The advantage of using RDC to determine the reliability of an SUT is that it allows both the customer and developer to determine the acceptable failure rate for a system. With RDC, the failure data is easily visualized in comparison wih the acceptable and rejectable failure targets. Furthermore, once used to the tools, RDC is a very fast and cost-efficient way of determining the reliability of an SUT. However, one disadvantage noticed in this lab is that the MTFF minimum requires a little more good guess-work, but the visualization of the chart definitely assists in arriving at the assumed MTTF minimum, despite being tedious. It also shows reliability in terms of relativity and trend rather than providing a quantitative value.

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
