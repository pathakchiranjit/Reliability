# Predictive Modelling of a repairable system using Data Analytics Tool


<img src="https://github.com/pathakchiranjit/Reliability/blob/main/pics/pic_1.jpg?raw=true" />


Photo by Jen Theodore on Unsplash

Many researchers have presented several estimation techniques for "Reliability" study of a system or product but it rarely gets acceptance in most of the implementations because of its highly esoteric nature and unavailability of user-friendly statistical tools. However, in recent past with the development of "RELIABILITY" python library it becomes simple and easy to execute in real world.

<img src="https://github.com/pathakchiranjit/Reliability/blob/main/pics/pic_2.jpg?raw=true"/>

Photo by JESHOOTS.COM on Unsplash

---

The most unique about repairable systems is its "Availability" (the percentage of time that the product or system is able to perform its required functions). When the required functions cannot be performed because a failure has occurred, the system must be repaired to restore the functionality. The faster the system can be repaired, the greater the availability. Besides "Availability" the other metric used to attribute repairable system is "Mean Time Between Failure (MTBF)" & "Rate of occurrence of failure (ROCOF) / Failure Rate".

<img src="https://github.com/pathakchiranjit/Reliability/blob/main/pics/figure1.png?raw=true"/>



Source: https://reliabilityweb.com


## Table of Contents

1. [Problem Statement](#section1)<br>

2. [Data Loading and Description](#section2)<br>

3. [Preprocessing](#section3)<br>
    - 3.1 [Importing packages](#section301)<br>
    - 3.2 [Label Encoding for Categorical data](#section302)<br>

4. [Goodness of fit of distribution](#section4)<br>
    - 4.1 [Train & Test split](#section401)<br>
    - 4.2 [Fitting distribution](#section402)<br>

5. [Estimation of the Dynamics](#section5)<br>
    - 5.1 [Survival Function](#section501)<br>
    - 5.2 [ROCOF / Failure rate](#section502)<br> 
    - 5.3 [Reliability growth curve](#section503)<br> 
  
6. [Mean Cumulative Function (MCF) estimation](#section6)<br>
    - 6.1 [Parametric model estimation](#section601)<br>
    - 6.2 [Prediction and Model validation](#section602)<br> 
    - 6.3 [Model Evaluation](#section603)<br> 
    
7. [Life expectancy chart](#section7)<br>

8. [Optimal replacement time estimation](#section8)<br>
	
9. [Conclusions](#section9)<br>

10. [Limitations of the study](#section10)<br>
