---
layout: research
---

## Working Papers


["Identification and Estimation of Market Size in Discrete Choice Demand Models"](https://zhanglinqi.github.io/assets/pdf/market_size_Linqi_Zhang.pdf) [[SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4545848)].   
Presentations: BC, BU-BC Econometrics Workshop, IIOC, CEA, EARIE, Microeconometrics Class of 2024 Conference   
<details>
<summary><u>Abstract</u></summary> 
<p> Within the framework of Berry (1994) and Berry, Levinsohn, and Pakes (1995), the existing empirical industrial organization literature often assumes that market size is observed. However, the presence of an unobservable outside option is a common source of mismeasurement. Measurement errors in market size lead to inconsistent estimates of elasticities, diversion ratios, and counterfactual simulations. I explicitly model the market size, and prove point identification of the market size model along with all demand parameters in a random coefficients logit (BLP) model. No additional data beyond what is needed to estimate standard BLP models is required. Identification comes from the exogenous variation in product characteristics across markets and the nonlinearity of the demand system. I apply the method to a merger simulation in the carbonated soft drinks (CSD) market in the US, and find that assuming a market size larger than the true estimated size would underestimate merger price increases.
</p>
</details>


["Who is Most Affected by Soda Taxes? Evidence from Purchases At-Home and Away-From-Home"](https://zhanglinqi.github.io/assets/pdf/soda_tax_Linqi_Zhang.pdf) [[SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4953476)], with [Xirong Lin](http://www.xirong-lin.com).   
Presentations: SEHO, BC
<details>
<summary><u>Abstract</u></summary> 
<p> Using a novel dataset that includes at-home and away-from-home food purchases, we study who is affected by soda taxes. We nonparametrically estimate a random coefficient nested logit model to exploit the rich heterogeneity in preferences and price elasticities across households, including SNAP participants and non-SNAP-participant poor. By simulating its impacts, we find that soda taxes are less effective away-from-home while more effective at-home, especially by targeting the total sugar intake of the poor, those with high total dietary sugar, and households without children. Our results suggest that ignoring either segment can lead to biased policy implications.
</p>
</details>

["Instrument-free estimation of triangular equation systems with the trigmm command",](https://drive.google.com/file/d/1ssduVrNYEQ9bbyhdq8nTTbKCnfGndskI/view) with Heejun Lee, [Arthur Lewbel](https://sites.google.com/bc.edu/arthur-lewbel) and [Susanne M. Schennach](https://sites.google.com/a/brown.edu/smschenn/).   
Revision requested at *Stata Journal*.
<details>
<summary><u>Abstract</u></summary> 
<p> In this article, we introduce the Stata package trigmm. The trigmm command performs an estimation for the parameters of a triangular two equation system without instruments and reports standard errors. The method is based on Lewbel, Schennach, and Zhang
(Journal of Business & Economic Statistics, forthcoming), who have proposed sufficient
conditions for identification and derived associated moment conditions. The estimation is conducted by casting the moment conditions into the built-in Stata command gmm. The usage of package trigmm is illustrated with simulated data and sample commands.
</p>
</details>

["Identifying Models With Mismeasured Endogenous Regressors Without Instruments: an Application to Monopsony in Academic Labor Markets",](https://zhanglinqi.github.io/assets/pdf/noside_error_monopsony_LZ_ZY.pdf) with [Zhanhan Yu](https://yuzhanhan.github.io/personal-website/).
<details>
<summary><u>Abstract</u></summary> 
<p> We extend the linear triangular structural model considered in Lewbel, Schennach, and Zhang (2024) to allow for measurement errors in the endogenous regressor. We show identification of the causal effect and distributions of unobservables using higher-order moments of variables when instrumental variables or repeated measurements are not available. We apply this approach to study monopsony power in the labor market for university professors at public research universities within the University System of Georgia, addressing endogeneity and measurement error concerns related to faculty salaries in the absence of suitable instruments. We find evidence of monopsony, with the exploitation rate -- a common measure of monopsony power -- robustly estimated at 36%. Our analysis shows that ignoring measurement error would significantly underestimate monopsony power.
</p>
</details>

---

## Publications

["Assessing Sensitivity to Unconfoundedness: Estimation and Inference"](https://arxiv.org/abs/2012.15716) [[Replication files](https://dl.dropboxusercontent.com/s/rj6nxlh6howhzvg/Replication%20Code.zip?dl=0)], with [Matthew A. Masten](https://mattmasten.github.io) and [Alexandre Poirier](https://sites.google.com/site/alexpoirierecon/).      
*Journal of Business & Economic Statistics*, 2024, 42(1), pp. 1-13.

*   To install the companion Stata module, type `ssc install tesensitivity` from within Stata.

<details>
<summary><u>Abstract</u></summary> 
<p> This paper provides a set of methods for quantifying the robustness of treatment effects estimated using the unconfoundedness assumption (also known as selection on observables or conditional independence). Specifically, we estimate and do inference on bounds on various treatment effect parameters, like the average treatment effect (ATE) and the average effect of treatment on the treated (ATT), under nonparametric relaxations of the unconfoundedness assumption indexed by a scalar sensitivity parameter c. These relaxations allow for limited selection on unobservables, depending on the value of c. For large enough c, these bounds equal the no assumptions bounds. Using a non-standard bootstrap method, we show how to construct confidence bands for these bound functions which are uniform over all values of c. We illustrate these methods with an empirical application to effects of the National Supported Work Demonstration program. We implement these methods in a companion Stata module for easy use in practice.
</p>
</details>

["Identification of a Triangular Two Equation System Without Instruments",](https://drive.google.com/file/d/1XRAr9GDSg4ErfNVKHLHHbVtAsoKILQBI/view) with [Arthur Lewbel](https://sites.google.com/bc.edu/arthur-lewbel) and [Susanne M. Schennach](https://sites.google.com/a/brown.edu/smschenn/).   
*Journal of Business & Economic Statistics*, 2024, 42(1), pp. 14-25.
<details>
<summary><u>Abstract</u></summary> 
<p> We show that a standard linear triangular two equation system can be point identified, without the use of instruments or any other side information. We find that the only case where the model is not point identified is when a latent variable that causes endogeneity is normally distributed. In this non-identified case, we derive the sharp identified set. We apply our results to Acemoglu and Johnson’s (2007) model of life expectancy and GDP, obtaining point identification and comparable estimates to theirs, without using their (or any other) instrument.
</p>
</details>


---

## In Progress Projects

"Buying in Small Quantities", with Yuzhi Yao. 
<details>
<summary><u>Abstract</u></summary> 
<p> Dollar stores feature products sold in small sizes, which are not necessarily cheaper in terms of unit price. The behavior of purchasing in smaller quantities, especially among low-income consumers, is puzzling given the quantity discount associated with bulk-buying. To unravel this phenomenon, we develop a structural model to disentangle potential explanations: limited access due to lack of transportation, liquidity constraints, and storage costs. </p>
</details>

<!--	<p style="margin: 0px 0px 30px;">-->

"Identification of Discrete-Continuous Models with Large Choice Sets and Complementarity".

<!--"Marijuana Tax and Product Variety".-->


<!--[back](./)-->
