# **Strategic Finance Operating Model – High-Growth Fintech (36-Month Simulation)**



## **Project Overview**



This project is a fully integrated 36-month operating model built to simulate capital planning and strategic finance decision-making for a high-growth multi-product fintech.



The model integrates:



* Payments revenue (GMV + take rate)
* Subscription monetization
* Lending expansion (scenario-dependent activation)
* Customer acquisition and retention dynamics
* Venture debt facility
* Equity funding rounds
* Dilution and valuation sensitivity



The objective was to replicate real-world FP\&A capital trade-offs under realistic cost and growth assumptions.



## **Model Architecture**



##### **Time Horizon**



* 36-month monthly model



##### **Financial Statements**



* Integrated Income Statement
* Cash Flow Statement
* Balance Sheet (fully balanced)



##### **Operating Engines**



* Customer acquisition model (MoM growth + cap)
* Retention and churn logic
* CAC dynamic with MoM efficiency improvement and floor
* Lending penetration with scenario-based activation
* Working capital module (AR, AP, loan book)



##### **Capital Structure**



* Initial seed equity: 5m AED
* Series A raise: Month 6 (Base case)
* Venture debt facility: 4m AED @ 10% annual
* 1m draw at Month 6
* 1m draw at Month 9
* Dilution modeled via ARR multiple valuation



##### **Scenario Framework**



* Downside / Base / Upside
* Scenario-driven variation in acquisition, churn, and lending activation
* Capital sensitivity analysis (raise size vs runway)



##### **Executive Layer**



* Board-style dashboard
* Scenario comparison summary
* Valuation and dilution analysis



## Base Case Results (M6 Raise, 25m)



Revenue (Year 3): 29.3m AED

ARR (Month 36): 21.2m AED

Gross Margin: 81%

EBITDA Margin (Y3): -51.3%

LTV/CAC (M12): 5.31

Burn Multiple (M12): 26.8



##### **Capital Strategy:**



* Series A (Month 6): 25m AED
* Pre-Money Equity Value: 8.6m AED
* Post-Money Equity Value: 33.6m AED
* Dilution: 74.4%



Bridge funding assumed between insolvency (Month 4) and raise close.



## **Key Strategic Insights**



* Capital intensity dominates early-stage fintech expansion under realistic acquisition and marketing costs.
* Delaying capital raise does not materially reduce dilution, as capital requirements scale alongside burn.
* Ownership preservation is more sensitive to operational efficiency improvements (CAC reduction, margin expansion, lending economics) than to raise timing alone.
* Venture debt provides incremental runway support but does not materially alter dilution dynamics under high burn conditions.



## **Sensitivity Framework**



Capital sensitivity tested across:



* Raise month
* Raise size



Metrics analyzed:



* Runway post-raise
* Minimum cash pre-raise
* First negative cash month
* Dilution impact



Operating scenarios evaluated:



* Downside
* Base
* Upside



## **File Structure**



##### **Executive Layer**



* Executive Summary
* Dashboard
* Valuation
* KPIs



##### **Financial Statements**



* Income Statement
* Cash Flow Statement
* Balance Sheet



##### **Strategic \& Sensitivity**



* Capital Sensitivity
* Scenario
* Scenario Compare
* Timeline



##### **Inputs \& Assumptions**



* Assumptions rationale
* Unit Economics
* Growth inputs
* Cost inputs
* Funding inputs
* Lending assumptions



##### **Calculation Engines**



* Customer engine
* Revenue engine
* OPEX engine
* Loan book
* Working capital
* Capex \& depreciation



## **How to Use**



1. Change the Scenario toggle on the Dashboard.
2. Adjust raise timing or size in Funding Inputs.
3. Review impact on:
   	Runway
   	Dilution
   	Net debt
   	Burn multiple
4. Analyze scenario trade-offs in Scenario Compare.



## **Limitations**



* Synthetic operating assumptions
* No DCF valuation (ARR multiple used)
* Simplified working capital timing
* Equity + venture debt capital stack only
* No macroeconomic sensitivity



This model is designed to demonstrate structured financial thinking, capital planning rigor, and strategic trade-off analysis in a high-growth fintech context.

