# [Review] Sobol’ sensitivity analysis of a complex environmental model
•	Authors: Jiri Nossent, Pieter Elsen, et al.
•	Journal/Conference: Environmental Modelling & Software (2011)
•	DOI/Link: https://doi.org/10.1016/j.envsoft.2011.08.010
•	Review Date: 2026-01-22
---
## [Summary]
•	Purpose to read: understanding about Sobol method, Write about Sobol method, how they present the sobol results.
•	Paper objectives: Sobol sensitivity analysis for flow simulation. To get the first order, second order and total sensitivity effects.
•	What is the gap they try to solve? 
-	Limitations of the qualitative results of the LH-OAT method: qualitative and not-quantitative. Cannot provide extra information on the model process or make it possible to verify underlying model assumptions
•	Why do they use Sobol?
-	It has the ability to incorporate parameter interactions and a relatively straightforward interpretation.
•	What is the remaining gap from this research?
-	It seems a few parameters were selected (26 parameters) for water quality.
•	How do they show the results?
-	Calcluate NSE simulation-observation of daily data
-	Graphical representation: scatterplots: sample-NSE
-	P graphs of 1-d slices: global sensitivity to a specific parameter
-	Points are random: does not influence the model output
-	Clear pattern: parameter influences the model output or interaction exist
-	1. They show the basic outcome: first order and total sensitivity index: Plot X(set number)-Y(Index value) : 
---
## [Sentences for citation]
-	A sensitivity analysis method that is very popular in many fields, is the variance-based Sobol’ method (Sobol’, 1990). In general, variance-based sensitivity analysis methods aim to quantify the amount of variance that each parameter contributes to the unconditional variance of the model output
-	Despite its high computational demands, this powerful SA technique has recently become more popular in environmental modeling because of its ability to incorporate parameter interactions and the relatively straightforward interpretation.
-	The method of Sobol’ (Sobol’, 1990) is a global and model independent sensitivity analysis method that is based on variance decomposition. It can handle nonlinear and non-monotonic functions and models.
