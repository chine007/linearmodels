Module Plans
------------
The plan for this modules is to add some key missing linear models.  This plan is intentionally
limited since there is no intention to replicate estimators available in statsmodels.

Univariate
==========

*  OLS - :class:`statsmodels.regression.linear_model.OLS`
*  WLS - :class:`statsmodels.regression.linear_model.WLS`
*  GLS - :class:`statsmodels.regression.linear_model.GLS`
* 2SLS - :class:`linearmodels.iv.model.IV2SLS`
* LIML/k-class - :class:`linearmodels.iv.model.IVLIML`
* GMM IV Estimation - :class:`linearmodels.iv.model.IVGMM`
* GMM-CUE Estimation - :class:`linearmodels.iv.model.IVGMMCUE`

Panel
=====

Least Squares Estimators
************************

* Fixed Effects - :class:`linearmodels.panel.model.PanelOLS`
* Random Effects - :class:`linearmodels.panel.model.RandomEffects`
* Pooled - :class:`linearmodels.panel.model.PooledOLS`
* Between - :class:`linearmodels.panel.model.BetweenOLS`
* First Difference - :class:`linearmodels.panel.model.FirstDifferenceOLS`
* Fama-MacBeth - :class:`linearmodels.panel.model.FamaMacBeth`


Asset Pricing
*************
* 2-step Linear Asset Pricing Model Estimation - :class:`linearmodels.asset_pricing.model.LinearFactorModel`
* GMM Linear Asset Pricing Model Estimation - :class:`linearmodels.asset_pricing.model.LinearFactorModelGMM`
* Linear Asset Pricing Model Estimation for Traded Factors - :class:`linearmodels.asset_pricing.model.TradedFactorModel`


Dynamic Panel Data Models
*************************
Planned but not implemented

Panel Instrumental Variable Estimators
**************************************
Planned but not implemented


System Estimation
=================
* Seemingly Unrelated Regression (SUR) Estimator - :class:`linearmodels.system.SUR`

Instrumental Variable Estimators
********************************
* Three-stage LEast Squares (3SLS) Estimator - :class:`linearmodels.system.IV3SLS`
* GMM Estimation - planned but not implemented
