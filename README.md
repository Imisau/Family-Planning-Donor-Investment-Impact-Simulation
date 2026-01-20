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

| Scenario	             |  Avg Cost per Client (USD)  |     Total Cost (USD)    | 	Avg Coverage Probability
:-----------------------:|:---------------------------:|:-----------------------:|:---------------------------:
Baseline	             |   $27.96	                   |      $93,813.77	     |       65.1%
Moderate Scale-Up 	     |   $28.15	                   |       $93,254.57	     |       65.2%
Aggressive Scale-Up      |	$28.08	                   |      $93,575.89	     |      64.9%

-	Cost per client increases slightly **(≈ $0.19)** under scale-up scenarios
-	Coverage gains remain statistically negligible **(< 0.2 percentage points)**
-	Aggressive Scale-Up does **not** outperform Moderate Scale-Up on cost efficiency

## Statistical Implication
The **incremental cost-effectiveness ratio (ICER)** between scenarios is weak, indicating **diminishing returns to scale.**

### The Value-for-Money (VFM) & Predictive Insights

This visuals also integrates **VFM scores,** cost, and service receipt.

**Observed Patterns**
- Higher cost does **not consistently predict higher VFM**
- VFM scores cluster between **~58 and ~69**
- Best-performing VFM cases occur under **Baseline and Moderate Scale-Up**

## Predictive Insight (Model-Based)
If current trends persist:
- A 10% increase in funding is predicted to yield **<2% increase in service uptake**
- Equity-adjusted returns decline sharply beyond baseline investment levels



# Coverage Outcomes – Service Uptake Performance

![](https://github.com/Imisau/Family-Planning-Donor-Investment-Impact-Simulation/blob/main/FPD4.png
)

This Visual focuses on actual service receipt rates, a more policy-relevant outcome than probability alone.
## Key Findings (Numerical)
- Baseline service receipt rate: **64.9%**
- Aggressive Scale-Up: **64.5%**
- Moderate Scale-Up: **63.7%**
Despite increased investment intensity:
- No scenario exceeds **65% service uptake**
- Aggressive Scale-Up underperforms Baseline by **0.4 percentage points**

## Donor Implication
Scaling financial inputs without addressing behavioral or system constraints yields **limited marginal gains in service uptake.**

# Equity Analysis – Rural vs Urban Distribution

![](https://github.com/Imisau/Family-Planning-Donor-Investment-Impact-Simulation/blob/main/FPD5.png)

This Visual disaggregates service receipt by settlement type, highlighting equity implications.

## Key Findings (Numerical)
|   Scenario	                    |   Rural Service Rate        |  Urban Service Rate|
:----------------------------------:|:---------------------------:|:---------------------------
|   Baseline	                    |    65.1%	                  |   64.6%
|   Moderate Scale-Up	            |    65.2%	                  |  61.8%
|   Aggressive Scale-Up	            |    64.5%	                  |   64.4%
	
Moderate Scale-Up improves rural reach but ***reduces urban coverage by ~3.4 pp**
- Baseline delivers the **most balanced equity profile**
- Aggressive Scale-Up shows **no equity advantage**

## Equity Implication
Targeted design matters more than funding intensity for equitable outcomes.
Poorly targeted scale-up can **shift inequities rather than reduce them.**

# Operational Feasibility Assessment

![](https://github.com/Imisau/Family-Planning-Donor-Investment-Impact-Simulation/blob/main/FPD6.png)
This Visual categorizes scenarios by implementation feasibility.

## Key Findings (Numerical)
- 100% of records across all scenarios are classified as “Low Feasibility”
  - Baseline: 3,355
  -	Moderate Scale-Up: 3,313
  - Aggressive Scale-Up: 3,332

### Interpretation
Scale-up scenarios were modeled **without commensurate system strengthening,** resulting in **uniform feasibility risk.**

## Donor Implication
Feasibility is a binding constraint.
Investment without parallel health system capacity building increases **implementation risk.**

# Statistical & MERL Implications
## Key Statistical Insights
- Variance across scenarios is low → outcomes are **structurally constrained**
- Coverage probability is not the primary limiting factor
- Service uptake likely driven by **non-financial determinants** (access, norms, delivery quality)

## MERL Learning
- Scenario analysis should be paired with:
  -	Behavioral insights
  -	Facility readiness assessments
  -	Demand-generation indicators

# Strategic Recommendations for Donors
1.	**Avoid blanket aggressive scale-up** without feasibility investments
2.	Prioritize **moderate, targeted expansion** with equity safeguards
3.	Invest in **system readiness and demand-side interventions**
4.	Use scenario modeling as a **learning and adaptive management tool**

# Conclusion
This analysis demonstrates that **more funding alone does not guarantee better FP outcomes.** 
Scenario-based analytics reveal that **balanced, feasibility-aware, and equity-focused strategies** outperform aggressive scale-up approaches in both value-for-money and sustainability.
The dashboard provides donors with a **transparent, auditable, and data-driven framework** for FP investment decisions.

Interact With The Dataset [Here](https://github.com/Imisau/Family-Planning-Donor-Investment-Impact-Simulation/blob/main/FP_Donor_Investment_Impact_Simulation_9States_10000.xlsx)

### Author
Emmanuel Kyauta

Monitoring, Evaluation, Research & Learning (MERL) | Strategic Health Data Analyst
Power BI • DAX • SQL • Python • Donor Decision Analytics





  



