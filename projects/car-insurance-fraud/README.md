# Car insurance fraud detection

**Area:** Applied machine learning  
**Format:** University team project

## Problem

An insurance company needs to decide, when a claim arrives, whether investigating it is worth the cost. The project framed fraud detection as a decision under a business cost matrix, rather than classification accuracy alone.

## Approach

- Integrated claim, customer, policy and vehicle tables.
- Constructed the fraud target from later review outcomes, keeping those outcomes out of model features.
- Used information available when the claim was filed and temporal validation to reduce information leakage.
- Compared classifiers and documented a five-seed Random Forest ensemble.
- Chose an investigation rate using the estimated cost of missed fraud and inspections.

The submitted report gives a holdout ROC AUC of **0.524** and PR AUC of **0.072**. These are reported academic results, not an independently reproduced model run. Economic savings are deliberately omitted because the source documents disagree on the inspection cost and one savings figure.

## Current status

The original report, slides, assignment and CSV files are retained in a separate private workspace. This public case study contains no customer records or dataset. The runnable notebook was not among the supplied files; code and reproduction steps will be added after review.
