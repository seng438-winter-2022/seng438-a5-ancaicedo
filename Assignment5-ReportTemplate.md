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

Below are the produced charts for the full failure data series:

## Full data range

### Failure Count
![image](https://user-images.githubusercontent.com/27434117/162321495-b4684e92-3ed9-4b44-acaf-74bf98121e0a.png)

### Failure Intensity
![image](https://user-images.githubusercontent.com/27434117/162321085-101a09da-f6a4-4dd7-9685-e35010da3629.png)
 
It can be seen from these two graphs that there seems to be a discrepency in the middle of the graph, possible where a change to the program was made. Due to this, we did seperate analysis for the first half and second half of the failure data.

## First half of data range
### Failure Count
![image](https://user-images.githubusercontent.com/27434117/162323521-c5a2c5ca-c93e-4b98-a63a-ba89ce1e0099.png)
### Failure Intensity
![image](https://user-images.githubusercontent.com/27434117/162323552-687a3d32-35b3-4c6e-bbc7-f17ff69095fb.png)


## Last half of data range
### Failure Count
![image](https://user-images.githubusercontent.com/27434117/162323613-580551eb-50d3-4491-8d8b-f514d12e319c.png)
### Failure Intensity
![image](https://user-images.githubusercontent.com/27434117/162323635-7cb9c797-5f8b-4c68-b84d-03b9c68e50c1.png)



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

One disadvantage of a RDC is that dealing with all the different what-if scenarios by testing different values can be somewhat time-consuming.
The RDC itself only shows the effects on the reliability of system caused by the trends of changes, it does not provide concrete quanititative values for reliability.
The advantages of using a RDC is that analyzing the RDC is straightforward as is inputting the values. Being able to see lots of different what if scenarios is also useful.

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
