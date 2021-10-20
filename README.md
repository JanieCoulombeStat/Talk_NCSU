# Talk_NCSU
Slides for my talk at the Department of Statistics, NCSU on Oct. 19, 2021

Abstract:
 
Data from electronic health records (EHR) and administrative databases are often observed irregularly across patients, and the frequency of observation may depend on patients’ comorbidities and other characteristics. We call this phenomenon “covariate-driven observation times”. Patients’ characteristics are also often predictive of the intervention that patients will receive from a range of possible treatments. The two features above are associated with imbalances in patients’ characteristics across treatment groups and across observed data and data that are not observed. When using EHR data to make causal inference, these imbalances should be considered, otherwise they can bias the estimation of the marginal effect of treatment on a longitudinal outcome.
 
Using causal diagrams, I will review how these imbalances in the data can affect the estimation of the marginal effect of treatment. I will mention different methods that were proposed to account for irregular or covariate-driven observation times and will introduce a methodology that we proposed for consistent estimation of the marginal effect of treatment under covariate-driven treatment and observation processes. I will briefly review a more complex setting in which the covariate process affecting observation times is endogenous, meaning that there is causal feedback between covariates and observation times. If time allows, I will present some related data examples and analyses conducted as part of my doctoral research.
