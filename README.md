# Family-Planning-Donor-Investment-Impact-Simulation
![](https://github.com/Imisau/Family-Planning-Donor-Investment-Impact-Simulation/blob/main/FPD1.png)

# Project Overview
This project applies **scenario-based analytics** to evaluate potential **Family Planning (FP) expansion strategies** across geographic units. Using simulated scale-up scenarios, the analysis assesses **trade-offs between cost, coverage, equity, and operational feasibility,** enabling donors and policymakers to make informed investment decisions.
The Power BI dashboard translates complex programmatic data into **clear, donor-ready insights and visuals** that support strategic planning, prioritization, and resource allocation for FP scale-up.

# Analytical Purpose
Family Planning investments require balancing multiple, often competing objectives:
•	Expanding coverage efficiently
•	Ensuring equitable access across populations
•	Managing program costs
•	Maintaining operational feasibility within health systems
This project addresses the need for a **decision-support tool** that allows stakeholders to **compare alternative FP expansion scenarios** and understand the implications of each option before committing resources.

# Project Objectives
-	Simulate multiple FP expansion scenarios across regions
- Quantify **cost, coverage, equity, and feasibility outcomes** for each scenario
-	Compare scenarios using standardized metrics
-	Highlight trade-offs and opportunity costs
-	Produce **donor-ready summaries and interactive visuals** to support scale-up decisions

# Data Inputs (Simulated & Assumed)
The analysis is based on simulated or modeled datasets typically used in FP planning, including:
-	Baseline FP service coverage
-	Target population estimates
-	Unit costs of FP service delivery
-	Health system and operational readiness indicators
-	Geographic and demographic attributes

⚠️ _Data used for this project is assumed to be aggregated, anonymized, and simulated for strategic planning rather than individual-level analysis._

# Data Processing & Transformation
Using **Power Query, SQL, Python and Excel** the following steps were applied:
-	Harmonization of indicators across regions
-	Standardization of units (costs, percentages, population counts)
-	Creation of scenario-specific variables
-	Normalization of indicators to enable cross-scenario comparison
-	Validation checks for internal consistency

# Executive Overview – Scenario Performance Summary

![](https://github.com/Imisau/Family-Planning-Donor-Investment-Impact-Simulation/blob/main/FPD2.png)

## What the Visual Shows
This slide presents **headline KPIs comparing three FP expansion scenarios** across 9 states and 10,000 youth clients:
-	Baseline
-	Moderate Scale-Up
-	Aggressive Scale-Up
## Key Findings (Numerical)
-	Total simulated clients: **10,000**
-	States covered: **9**
- Scenario distribution:
  -	Baseline: **3,355 clients**
	- Moderate Scale-Up: **3,313 clients**
	- Aggressive Scale-Up: **3,332 clients**

Across all scenarios:
-	Average service receipt rate ranges narrowly between **63.7% and 64.9%**
-	Average coverage probability is stable at approximately **65%**

## Donor Implication
Early results indicate **marginal performance differences across scale-up scenarios,** suggesting that **scale alone does not guarantee improved outcomes.**

# Cost Efficiency – Cost vs Coverage Trade-Off

![](https://github.com/Imisau/Family-Planning-Donor-Investment-Impact-Simulation/blob/main/FPD3.png)

### This Visual compares:
-	Average cost per client
-	Total program cost
-	Coverage probability by scenario
  
## Key Findings (Numerical)

### Scenario	            Avg Cost per Client (USD)	       Total Cost (USD)     	Avg Coverage Probability
:-----------------------:|:---------------------------:|:-----------------------:|:---------------------------:
Baseline	             |   $27.96	                   |      $93,813.77	     |       65.1%
Moderate Scale-Up 	     |   $28.15	                   |       $93,254.57	     |       65.2%
Aggressive Scale-Up      |	$28.08	                   |      $93,575.89	     |      64.9%

-	Cost per client increases slightly **(≈ $0.19)** under scale-up scenarios
-	Coverage gains remain statistically negligible **(< 0.2 percentage points)**
-	Aggressive Scale-Up does **not** outperform Moderate Scale-Up on cost efficiency

## Statistical Implication
The **incremental cost-effectiveness ratio (ICER)** between scenarios is weak, indicating **diminishing returns to scale.**


  



