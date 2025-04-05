## Exam 7 High-Level Summaries 2025 Sitting

Rising Fellow

---

Copyright C 2024 by Rising Fellow LLC

All rights reserved. No part of this publication may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, withou the prior written permission of the publisher, except in the case of brief quotations embodied in critical reviews and certain other noncommercial uses permitted by copyright law. For permission requests, write to the publisher at the address below.

Published By:

Rising Fellow United States,TX, 78006 www.RisingFellow.com

Published in the United State

---

$\begin{aligned}
&\frac{\text{Table of Contents}}{} \\
&\text{Table of Contents} \\
&\text{Mack-Benktander} \\
&\text{Hürlimann} \\
&\text{Brosius} \\
&\text{Friedlanc} \\
&\text{Clark} \text{20}  \\
&\mathrm{Mack-Chain~Ladder} \\
&\text{Venter Factors} \text{29}  \\
&\text{Shapland} \\
&\text{Siewert} \\
&\text{Sahasrabuddhe} \text{48}  \\
&\text{Teng and Perkins} \\
&\text{Meyers} \\
&\text{Taylor} \\
&\text{Verrall} \\
&\text{Marshall} \\
&\frac1{\otimes\text{Rising Fellow}}\text{High-Level Summaries|i}
\end{aligned}$

---

---

## Credible Claims Reserves: The Benktander Method

## Overview

The Mack - Benktander paper is a calculation-heavy paper. Most importantly, you need to be able to estimate Benktander reserves a number of different ways based on how the problem is written.Another key concept to remember is that the Benktander ultimate loss estimate is a credibility-weighting of the chain ladder and expected loss ultimates.

### Benktander Method

The Benktander method can be calculated as a second iteration of the BF procedure or as a credibility weighting of the Chain Ladder and Expected Loss ultimates (see the“Mack-Benktander -Benktander Method" recipe).d

## Benktander as a second iteration of the BF procedure.

Iteration 1 - Bornhuetter-Ferguson

$$Ult_{_{BF}}=Loss+(1-\%Paid)\times Prem\times ELR$$

Iteration 2-Benktander
$$\boxed{U_{_{GB}}=C_{_k}+q_{_k}U_{_{BF}}}$$

$$U_{_{GB}}=Loss+(1-\%Paid)\times Ult_{_{BF}}$$

Benktander as a credibility-weighting of the Chain Ladder and Expected Loss Ultimates.

Chain Ladder Ultimate:

$$Ult_{cL}=Loss\times CDF$$

C Uca Pk

Benktander:

$q_{k}^{*}=1-\frac{1}{CDF}$

$U_{GB}=\left(1-q_{k}^{*}\right)^{2}U_{CL}+q_{k}^{*2}U_{0}$

Benktander as a credibility-weighting of the Chain Ladder and BF Reserves

$R_{GE} = (1 - q_s) R_{CE} + q_s R_F$

### Advantages of the Benktander Method

.Outperforms the BF and Chain Ladder methods in many circumstances ·The MSE of the Benktander reserve is almost as small as that of the optimal credibility reserve

---

### Iterated BF Method

The Benktander method is a second iteration ofthe BF procedure.Thisis how the iteration works

1.Start with an ultimate loss estimate, $U^{(\mathrm{m})}$ .For $U^{(0)}$ , use the expected loss estimate. 2.Apply theBFprocedure to get a new loss reserve estimate:

![](https://storage.simpletex.cn/view/fImhLRSAUr226YAVU8tYM0RRvHBgd3VzW)

3.Get a new ultimate loss estimate by adding thelosses-to-date to the reserve.This is the starting ultimate for the next iteration:

![](https://storage.simpletex.cn/view/fmIlLBvguAnQazhhS0O74LsCuii0si4Pm)

The ultimate loss estimate $(\mathbf{U}^{(\mathrm{m})})$ can be rearranged as a credibility weighting of the Chain Ladder ultimate $(\mathrm{U}_{\mathrm{CL}})$ and expected loss ultimate $(\mathrm{U}_{0})$ .Also, the loss reserve estimate $(\mathbf{R}^{(\mathrm{m})})$ can be rearranged as a credibility weighting of the ChainLadder reserve $(\mathbf{R}_{\mathrm{CL}}$ ) and the BF reserve $\mathrm{R}_{\mathrm{BF},}$

![](https://storage.simpletex.cn/view/fisnayqF3FgBXFaGCzBeLfsSHd4Zodyho)

As the number of iterations increases,the weight on the chain ladder method increases until it converges to the chain ladder method entirely (as $m\rightarrow\infty$ ).

## Recipes for Calculation Problems

Benktander Method

---

## Credible Loss Ratio Claims Reserves

# Overview

The reserve estimate method in Hurlimannis a credibility-weighted method that's very similar to the Mack (2000) method. The key difference is that Huirlimann uses expected incremental loss ratios $(m_k)$ to specify the payment pattern instead of using LDFs calculated directly from thelosses.

Hurlimann uses two new reserving methods based on the loss ratio payout factors,p

Individual Loss Ratio Reserve $(R^{ind})-$ Similar to the chain ladder method

·Collective Loss Ratio Reserve $R^{\text{cod}\prime\prime}$ Similar to the Bornhuetter-Ferguson (BF) method

The key idea from Hurlimann is that $R^{ind}$ and $R^{\mathrm{coll}}$ represent extremes of credibility on the actual loss experience and we can calculate a credibility-weighted estimate that minimizes theMSE of the reserve estimate.

## Credible Loss Ratio Claims Reserve

Individual Loss Ratio Claims Reserve (Rn

$$R^{ind}=\frac{\%Unpaid_{AY}\cdot Loss_{AY}}{\%Paid_{AY}}$$

![](https://storage.simpletex.cn/view/fLczcXNhgoagVNCKImWsc18LE8TFfVk6F)

$R^{ind}-100\%$ credibility on losses-to-date

### Collective Loss Ratio Claims Reserve R

$$\boxed{R^{call}=q_{i}\cdot Prem\cdot ELR}\quad R^{call}=96Unpaid_{AY}\cdot Premium_{AY}\cdot ELR$$

$R^{\mathrm{cod}\prime}-0\%$ credibility on losses-to-date

### Credibility-Weiqhted Reserve Estimate

We can calculate a new, credibility-weighted estimate,based on $R^{ind}$ and $R^{\mathrm{rob}}$ that minimizes the mean squared error (MSE) and variance of the loss reserve estimate.

$$\boxed{R_i=Z_i\cdot R_i^{ind}+(1-Z_i)\cdot R_i^{coll}}$$

Hurlimann uses three different credibility methods:

![](https://storage.simpletex.cn/view/fLZZG2tq9M61hxgT5frk65pmTRLzVEEdP)

Benktander (also in Mack (2000)

:Neuhaus

Optimal credibility weighting (minimizes MSE)

---

Straightforward calculation of the optimal credibility weight ·Different actuaries get the same result using the collective loss ratio claims reserve with the same premiums (BF method requires an ELR assumption)

### Advantage of the optimal credibility weiqht reserve (Rp

·Minimizes MSE andvariance of theloss reserve estimate ONote: the MSE from Benktander and Neuhaus are close to the optimal credibilityMSE

## Optimal Credibility Weights

Hurlimann derives the optimal credibility weights in sections 4-6.Many of the formulas are intermediary formulas in the derivation.For the exam,I would focus primarily on the final, simplified optimal credibility weight as well as the generalized optimal credibility formula (see the Optimal Credibility Weights" recipe).

If we assume that the variance of the ultimate loss is the same as the variance of the burning cost ultimate loss estimate, $\operatorname{Var}(U_{i})=\operatorname{Var}(U_{i}^{BC})$ , we get the simplified optimal credibility weight formula. If we make a different assumption, then you need to use the generalized version of the formula

You should definitely know the simplified optimal credibility weight formula.A potential twist to a question would be to use a different assumption, such as $\operatorname{Var}(U_{i})=2\times\operatorname{Var}(U_{i}^{BC})$ ，and then use the generalized formula to calculate the optimal credibility weight.

## Application to Standard Approaches

Hiurlimann derived the optimal credibility weight formula for the loss ratio claims reserve approach. It can also be used with a more traditional approach, using LDFs to calculate the payout pattern $(p_{i}^{CL})$ .With the LDF-based payout pattern, you can then calculate the reserve estimate as a credibility-weighting of the Chain Ladder and Cape Cod (or BF) reserve estimates using the Benktander, Neuhaus or optimal credibility weights.

Credibility-Weighted Cape Cod Approach

·Use LDFs to calculate the payout pattern $(p_{i}^{CL})$ ·Calculate the ELR using the Cape Cod method

Credibility-Weiqhted Bornhuetter Ferquson Approach

·Use LDFs to calculate the payout pattern $(p_{i}^{CL})$ ·The ELR is an assumption

## Recipes for Calculation Problems

·Credible Loss Ratio Claims Reserve Optimal Credibility Weights

---

## Loss Development Using Credibility

## Overview

Brosius introduces the Least Squares method for estimating loss reserves and compares this method to the traditional Chain Ladder and the Budgeted Loss (Expected Loss) methods. The key theme of this paper is that the Least Squares method is a credibility weighting of the Link Ratio (Chain Ladder) and Budgeted Loss methods.

### Least Squares Method

The Least Squares method fits a regression line through the data to estimate developed losses ( $\hat{y}$ )

![](https://storage.simpletex.cn/view/fh6k4wTwSwb5S8zDnWpbbfKO4q1SgMKSk)

See the Brosius Least Squares" recipe.

### Comparison of Methods

![](https://storage.simpletex.cn/view/fUinwOpMC3U10kCFghRA4DTENQQclPKGS)

## Least Squares as Credibility Weighting

The Least Squares method is a credibility weighting of the Link Ratio and Budgeted Loss methods. The Link Ratio and Budgeted Loss methods represent the extremes:

Link Ratio: Places $100\%$ credibility on loss experience and $0\%$ on expected losses ·Budgeted Loss: Places 096 credibility on loss experience and $100\%$ on expected losses

## Least Squares Credibility Formula

The Least Squares method is flexible and places more (or less) credibility on the loss experience as appropriate.

---

Below are the key formulas for calculating the credibility on the link ratio method.The factor $\mathbf{C}$ is just the LDF for the link ratiomethod.The credibility is the ratio of $b$ to the LDF.The closer $b$ is to the LDF, the higher the credibility weighting the least squares method places on the link ratio method

CLDP-—

Credibility-weighted formula

j=Zx+(1-Z)xE[y]
$$\hat{y}=Z\times LDF\times x+(1-Z)\times\mathrm{E}\Big[\:y\:\Big]$$

### Special Cases

If the regression line fits through the origin,then $\mathbf{a}=0$ ,resulting in the Chain Ladder method where $\hat{y}=bx$

If $X$ and y are completely uncorrelated, then $b=0$ ,resulting in the Budgeted Loss method where $\hat{y}=a$ . The Bornhuetter-Ferguson method is a special case of Least Squares where $b=1$ .The BF method can be problematic if negative loss development is expected. The Least Squares method would allow b to adapt to the observed data.

Potential Problems (and Fixes) with Least Squares.

The intercept is negative $(a<0$,

This causes the estimate of developed losses ( $\hat{y}$ ) to be negative for small values of $X.$ Solution: Use the link ratio method instead

## The slope is negative $(b<0)$

This causes the estimate of $y$ to decrease as $X$ increases ·Solution:Use the budgeted loss method instead

### Key Assumptions for Least Squares

Least Squares assumes a steady distribution of random variables X and Y

·Least Squares is inappropriate if there's a systematic shift in the book of business

### Advantages of Least Squares

·Least Squares is more flexible than the link ratio, budgeted loss, and BF methods. ·Least Squares is a credibility weighting of the link ratio and budgeted loss estimates. It gives more (or less)credibility to the loss experience $(x)$ as appropriate.

---

Least Squares produces more reasonable results when the data has severe random, year-to-year fluctuations (e.g. a small book of business or thin data)

### Adjustments to the data when using Least Squares

·When using incurred loss data, the data should be adjusted for inflation so that all accident years are on a constant-dollarbasis.

If there is significant growth in the book of business, you should divide the data by an exposure basis.

# Hugh White's Question

If reported losses $(x)$ come in higher than expected, the different methods will estimate different changes to the outstanding loss reserve:

·Budgeted LossMethod (fixed prior case)-Theultimate loss estimate is fixed,so we decrease the loss reserve estimateby the same amount as the unexpected increase in reported losses. This method treats the increased loss as losses coming in faster than expected

BF Method-The ultimate loss estimate increases by the amount losses were greater than expected The Ioss reserve is unchanged. The BF method treats the unexpected increased loss as a random fluctuation (e.g. a large loss).

Link Ratio Method (fixed reporting case) - The ultimate loss estimate increases in proportion to the excess losses by applying the LDF, so we increase the loss reserve estimate. This method assumes that a fixed percentage of ultimate losses is reported, so if reported losses increases, the ultimate loss estimate will increase proportionally.

## Theoretical Models - Testing Least Squares

The purpose of this section is to test the least squares model against a few different theoretical loss models. With a theoretical model,we can use Bayes'Theorem to calculate the“correct”loss model and then see whether theleast squares,budgeted loss orlink ratio modelshave the same form as the Bayesian approach

| Model               | Form            | Model Constraints |
| ------------------- | --------------- | ----------------- |
| Least Squares       | $\\hat{y}=a+bx$ | $a=0$             |
| Link Ratio          | $\\hat{y}=ax$   | $b=0$             |
| Budgeted Loss       | $\\hat{y}=a$    |                   |
| Bornhutter-Ferguson | $\\hat{y}=a+x$  | $b=1$             |

### Simple Model

The number of ultimate claims incurred (Y) is either O or 1 with equal probability

·If there is a claim (Y=1) ,there is a $50\%$ chance it's reported by year end (X)

Using BayesTheorem,the best estimate of ultimate claims given $x$ is $\hat{y}=\frac{1}{3}+\frac{2}{3}x$ .This is the form $\hat{y}=a+bx$ , so only the Least Squares method is compatible

---

Poisson -Binomial Model

·The number of ultimate claims incurred (Y) is Poisson with mean $\mu$ ·Any given claim has probability $d$ of being reported by year end

Using Bayes'Theorem, the best estimate of ultimate claims is $\hat{y} = x+ \mu ( 1- d)$ . This is the same form as both the Least Squares method and BF method, since $b=1$

### Negative Binomial -Binomial Model

·The number of ultimate claims incurred (Y) is Negative Binomial with parameters $(r,p)$

·Any given claimhas probability $d$ of beingreported by year end

This model also has a Baysian estimate with the same form as the Least Squares method, but the other methods will be incorrect

Linear Approximation (Bayesian Credibility Approach)

We can only calculate the true Bayesian estimate by assuming a distribution for Y and $X|Y$ but that's not practical. Instead, we're going to find the best linear approximation to the Bayesian estimate of ultimate losses with Bayesian credibility, $L(x)$

$$L(x)=\begin{pmatrix}x-\operatorname{E}[X]\end{pmatrix}\frac{\operatorname{Cov}(X,Y)}{\operatorname{Var}(X)}+\operatorname{E}[Y]$$

Below is how a large reported loss (increasing x) can change the loss reserves, corresponding with the three different answers to Hugh White's question. For $x>$E$[X]$

$\operatorname{Cov}(X,Y)<\operatorname{Var}(X)$ loss reserve decreases · $\operatorname{Cov}(X,Y)=\operatorname{Var}(X)$ loss reserve unaffected (ultimate loss increases by the increase to x) · $\operatorname{Cov}(X,Y)>\operatorname{Var}(X)$ loss reserve increases

Using loss data, we can estimate $\operatorname{Cov}(X,Y)$ ， $Var(X)$ , and E[Y], which gets us right back to the Least Squares method

$$L(x)=\hat{y}=(x-\overline{x})\frac{\overline{xy}-\overline{x}\cdot\overline{y}}{\overline{x^{2}}-\overline{x}^{2}}+\overline{y}$$

The key point is that the least squares method is thebest linear approximation to theBayesian estimate, although there will be sampling error in the parameter estimates of $a$ and $b.$

Using simulated data from the Poisson-Binomial model, the Least Squares method fits the data better than thelinkratiomethod and has a lowerMSE

---

# Bayesian Credibility

If the book of business changes significantly, we can't use the regular Least Squares method. But, if we make a few assumptions about the expected ultimate losses (Y) and the percent reported $(\frac{X}{Y})$ , then we can calculate a Bayesian credibility estimate of ultimate losses (See the Brosius Bayesian Credibility" recipe)

## Caseload Effect

The regular Bayesian credibility formula assumes that the expected percent of losses reported is the same no matter how large ultimate loss (Y) is. The caseload effect says that if ultimate loss is higher, then we would expect a lower percent of losses to be reported at time x (See the “Brosius - Caseload Effect” recipe).

Bayesian credibility still works,but the Bayesian credibility formula needs to be modified. Instead of using a fixed percent reported, the expected percent reported is lower if ultimate losses (Y) are higher.Below is a graphical view of the caseload effect and how the caseload effect estimate compares to the unmodified chain ladder estimate.

·I $\mathbf{f}_{\mathbf{x}}>\mathbf{E}[\mathbf{X}]$ ,the caseload estimate will be higherthan the unmodified chain ladder estimate

· If x< E[ X] ,the caseload estimate willbelower than the unmodified chain ladder estimate.

![](https://storage.simpletex.cn/view/fSyoXRuRQtPeWhAu9CaUsNdKo90Yq6RES)

## Recipes for Calculation Problems

·Least Squares Method Bayesian Credibility .Caseload Effect

---

## Reserving for Reinsurance

## Overview

Below are some of the key topics to understand from the Friedland paper:

·The types and functions of reinsurance ·Differences in data and reserving between reinsurers and primary insurers ·The comparison of the volatility in development factors and patterns between reinsurance, primary insurance, and more ·How different reinsurance contracts interact and how to calculate ceded loss reserves

Appropriate reserving for reinsurance is important for the following reinsurer stakeholders:.

Internal Management - Sound reserves affect all areas of reinsurer operations (pricing, underwriting, strategic planning, financial decision-making, ...). Investors -Appropriately stated reserves are essential so that investors can properly evaluate the reinsurer's balance sheets and income statements for their decision-making Insurance Regulators -Regulators rely on the financial statements of reinsurers to properly supervise the reinsurance market. Rating Agencies -If a reinsurer reports significant adverse reserve developments over time that reduce capital leaving the reinsurer in a weakened position, it could face a rating downgrade.

## Functions of Reinsurance

·Promote Stability -Helps a ceding company stabilize loss experience over time and protect the ceding company from large unforeseeable losses. This can decrease the probability of ruin. Increase Capacity - By ceding a portion of all policies or its larger policies, a ceding company can increase its capacity to write more business,particularly at higher policy limits Protect against Catastrophes Reinsurance can protect ceding companies from catastrophic loss events as well as protect against casualty loss occurrences with multiple insureds (like terrorism) ·Manage Capital and Solvency MarginoReinsurance can help a ceding company pass the risk of large losses to the reinsurer which frees up capital since less capital will be required to support the policies written. OThe ceded commission acts as a transfer of statutory surplus from the reinsurer to the cedent, which can manage financial results OPremium ceded also reduces the cedent's net premium-to-surplus ratio (solvency margin) which allows the cedent to write more business.

---

Access Technical Expertise Reinsurers have technical expertise in underwriting, marketing claims, loss prevention, pricing, and entering new lines/regions that can help small insurers.

Other Functions - Reinsurance can help a ceding company withdraw from a line of business, geographic area, or production source

## Types of Reinsurance

Reinsurance is categorized as Treaty or Facultative and Proportional or Non-Proportional

## Treaty Reinsurance

The ceding company cedes all business arising from the lines of business that fall within the terms of the treaty subject to treaty limits. ·There is no underwriting by the reinsurer of individual risks within the treaty terms The cedent has an obligation to cede a risk under the treaty terms and the reinsurer has an obligation to automatically accept it.

### Facultative Reinsurance

Both the ceding company and reinsurer have the option (faculty) to accept or reject individual submissions and an individual reinsurance agreement is negotiated for each policy ceded

·Primarily used to increase capacity, typically for high-value and hazardous commercial risks.

### Proportional Reinsurance

·Increases capacity and manages capital and solvency margins to provide surplus relief

Both premiums and losses are shared between the cedent and reinsurer based on the cession percentage. The reinsurer pays a ceding commission to reimburse the cedent for expenses underlying the policy

## Types of Proportional Reinsurance

·Quota Share -The ceding company cedes an agreed percentage of each risk (premiums and losses) to the reinsurer for the lines of business in the contract, typically a treaty

Surplus Share - The cedent cedes the surplus amount of a risk above the retained line subject to a maximum ceded percentage and limit. The proportion ceded is different for different insured policies according to the underlying policy limits and acts like a variable quota share.

Policy Limit - Retained Line Proportion Ceded = Policy Limit

### Non-Proportional Reinsurance (Excess of Loss)

·Provides stability by protecting losses above a limit for risks ceded ·Loss ceded is based on the size of loss and the premium is not proportional to the coverage limits

---

·Excess per Risk -Excess-of-loss reinsurance above a retention for each risk 0Primarily to protect property exposures (e.g. 7M excess 3M on property policies with 10M policy limits) OAllows ceding companies to write larger risks (increase capacity)

Excess per Occurrence and Catastrophe -For a loss occurrence,the ceding company retains the retention and cedes the loss excess the retention to the reinsurer up to the reinsurance limit.

OExcess per Occurrence -Protects a cedent from the accumulation of losses in a single loss occurrence. OCatastrophe Reinsurance -Form of Excess per Occurrence for a single catastrophio event or series of events.Most allow for reinstatement after afull limit loss.

Annual Aggregate Excess of Loss (stop-loss)- Guarantees a ceding company's losses won't exceed a predetermined threshold (percent of premium or fixed dollar amount)

OThe reinsurer indemnifies for losses above the aggregate value OProtects net results (other reinsurance inures to the benefit of the Agg. Excess of Loss) OThe best option to protect capital but can be very expensive or unavailable

Clash - Casualty reinsurance contract that attaches above all other policy limits.It protects a ceding company when there are multiple claims from multiple insureds for the same catastrophe and its reinsurance policy doesn’t fully reimburse the insurer.

oComponents of a clash event Loss must have multiple policies by one insured or similar policies held by multiple insureds The losses are traceable to and the direct consequence of a specific event ·The event must take place within a specific timeframe

## Finite Risk Reinsurancee

This type of reinsurance takes the time value of money into account. Features include

·Risk transfer and risk financing in a multi-year contract ·Incorporates the time value of money and investment income ·Limited assumption of risk by the reinsurer ·Reinsurer and ceding company share results

Includes run-off solutions, which transfer reserve development risk to the reinsurer. Reasons for run-off include corporate restructuring, mergers 8 acquisitions, discontinuation of lines of business, erratic changes in the valuation/cost of a liability,.

### Loss Portfolio Transfers

·Transfers all (or a portion) of liability for future loss payments on losses already incurred

---

Relieves cedent of uncertainty in loss reserves and relieves capital

### Adverse Development Cover

Ceding company is reimbursed for losses excess a retention,but there's no transfer of the loss reserves to the reinsurer Often used for Mergers & Acquisitions to transfer the risks of timing and adverse reserve development

## Reinsurance Concepts and Contract Provisions

## Inure to theBenefit of

The concept of “inuring to the benefit of” specifies whether a treaty takes effect to the benefit of the reinsurer or the reinsured

For a reinsurance Treaty A:

●If other reinsurances apply first to reduce the loss subject to Treaty A, then the other reinsurance contracts inure to the benefit of the reinsurer of Treaty A. If other reinsurances are ignored with respect to Treaty A (they don't lower the loss subject to Treaty A),then the other reinsurance contracts inure to the benefit of the ceding company.

### Losses-Occurrinq Durinq vs Risks-Attaching

·Losses-Occurring During - Reinsurance coverage for all losses that occur between the inception and expiration of the reinsurance contract, regardless of when the underlying policy was issued. ·Risks-Attaching - Reinsurance coverage for losses on underlying policies with inception dates during the reinsurance contract's effective period. The underlying policies "attach" to the contract.

## Subscription Percentage

A subscription policy is a reinsurance policy where risk is shared by multiple reinsurers. Each reinsurer has a subscription percentage to the contract.

Reasons for this approach include:

·When coverage is more than one reinsurer is willing to assume ·Allows the cedent to diversify credit risk（the risk that a reinsurer can't pay reinsurance recoveries)

## Commutation Clause

A commutation is the cancellation of a reinsurance contract. The reinsurer pays the present value of reinsurance recoveries not yet due for the termination of the contract and all future obligations.

Both reinsurers and ceding companies have reasons for commutations

---

### For a Reinsurer

## For a CedingCompany

To exit a line of business or region To manage reserves for transfer or sale To avoid credit risk of a reinsurer To better manage claims and claims-related expenses

To terminate a relationshipwith a ceding company To protect itself from the insolvency of a ceding company To avoid disputes with the cedent about future loss development

### Sufficient and Reliable Data

# Sufficiency

Data are sufficient if they included all information needed for the actuarial work.

For the development method:

Reinsurance data may not be appropriate for the underlying development method assumptions because of its manuscript nature (custom-written) and due to operational changes at ceding companies,the reinsurer or both Changes at the ceding company level can violate the assumption of consistency in mix of business, attachment points, limits, claims processing, etc.

## Reliability

Data are reliable if they are sufficiently complete, consistent, and accurate for the purposes of the work

Data should be validated: Reviewed for consistency, completeness, and accuracy.

Reliability challenges for reinsurers vs. primary insurers:

Each ceding company/broker has different IT systems, terminology, etc :Bordereau reporting can differ (types of data, labeling, frequency) Reporting lags OClaims are reported first to ceding company before being reported to the reinsurer oLong-tailed nature of certain reinsurance like excess per risk and catastrophe reinsurance OBordereau reporting: losses are only reported quarterly or more infrequent schedule Gaps in reporting of critical claims and claims expense information by the ceding company :Manuscript nature of reinsurance policies

## Homogeneity and Credibility of Data

Homogeneity

Homogeneous Risk Group (HRG) - Set of (re)insurance obligations with similar risk characteristics to allow for reliable valuation of unpaid losses or technical provisions.

---

Data should be segmented into groups with similar characteristics of loss experience such as consistency of coverage, similar reporting/payment patterns, ability to develop appropriate case outstanding for claims, severity, and volume of losses in the group.

### Credibility

Credibility-Ameasure of the predictivevaluefor a set of data.

Credibility for a homogeneous risk group increases with:

·Increasing homogeneity of the data within a group

·Increasing the volume of data in a group

If groups are too granularly defined, the volume of data in each group may be too low for a reliable analysis.

Important Variables for Partitioning the Reinsurance Portfolio

Line of business (property, casualty ...) Type of contract (facultative, treaty, ...) .Type of reinsurance cover (quota share, excess per-occurrence, CAT, ...) ·Primary line ofbusiness -for casualty Attachment point - for casualty Contract terms (flat-rated, retro-rated, claims-made,... ·Type of cedent (small, large,..) :Intermediary

# Organization of Data by Experience Period

Accident Year Aggregation

Losses are grouped by date of occurrence and calendar year earned premium is used to approximately match accident year losses.

# Advantages

### Disadvantages

Potential mismatch of losses and premiums

Easy to achieve and understand Losses over shorter timeframe than underwriting year so losses can be reliably estimated sooner Industry benchmarks are based on AY Valuable when there are economic/regulator changes or major loss events

---

### Underwriting Year Aggregation

Losses are grouped by the year in which the reinsurance policy became effective (inception date).

### Advantages

Disadvantagese Extended timeframe for losses tied to UW year Difficult to isolate the effect of a single large loss event

True match of losses and premiums Valuable when underwriting or pricing. changes occur

# Types of Data

ULAE - Usually excluded from reinsurance coverage.

ALAE - Generally three possible reinsurance treatments:

·Included with claim amount to determine excess of loss coverage ·Included on a pro-rata basis ( $\%$ of reinsured loss/total loss) ·Not included in coverage

Multiple currencies -Loss data may be in different currencies.There are two approaches:

Separate data by currency,then combine the data after translating to a common currency using the exchange rate at a single point in time ·Aggregate losses are based on the ceding company's currency of origin

Large losses -Exclude large losses from initial projections and then add in case-specific projections of the reported portion for large losses and a smoothed provision for the IBNR portion of the large losses.

Recoveries (deductibles, salvage & subrogation) - Generally recoveries are applied before reinsurance.

## Data Challenges for Reinsurers

·Influence of Change in Operations and Environment

OOperational changes for ceding insurers and reinsurers OChanges in the legal/economic environment of ceding companies that impact losses

Other Experience Typically Excluded OActuary may exclude discontinued business (run-off) from the data analysis ·Reporting Lags OLosses first reported to ceding company before they're reported to the reinsurer 0 Losses may not be reported to the reinsurer until a claim hits a certain threshold .Heterogeneity of Contract Wording oThe "manuscript nature" of reinsurance contracts means contract wording can be different by contract making it more difficult to aggregate similar data

---

External Sources of Data

Actuaries at smaller reinsurers often use external data sources to help analyze development or tail factors trend rates,expected loss ratios,etc.Below are some external sources of data

Reinsurance Association of America (RAA) :Best's Aggregates & Averages ·Reports from global brokers or reinsurers Other internet searches

External data may be misleading or irrelevant due to differences in:

Manuscript wording/term of reinsurance contractse Mix of assumed business (differences in industry, region, attachment points, policy limits) .Types of reinsurance (treaty vs. facultative, proportional vs. non-proportional) Underwriting processes Claims management differences ·Coding and IT system differences

## Methods Used

### Development Method

·Assumes future development is like prior years' development and losses to date are predictive of losses yet to be observed Assumes consistency across experience period of claims processing, mix of business, policy limits, reinsurance coverage, etc.

### Expected Method

Applies an expected loss ratio to earned premium to estimate expected losses

Often used when:

·Entering a new line of business or region ·When historical losses are irrelevant to project future losses due to changes in strategy,operations, or environment When the development method isn't appropriate for immature periods because development factors are too highly leveraged When data are unavailable for other methods

### Bornhuetter-Ferquson Methoc

·Assumes unreported (or unpaid) loss will developbased on expected loss.

---

·Relies on both a selected loss development pattern and expected loss estimate

Differences in Method Assumptions for Reinsurance vs Primary Insurance

·For a similar line: LDFs at immature ages are often higher (more leveraged) for reinsurance due to reporting lags ·Loss trend factors are often higher for excess ofloss reinsurance than primary insurance ·Less precision in premium on-level factors for rate changes for reinsurance vs. primary insurance ·Limited use of adjustment factors for tort/product reform for reinsurance vs primary insurance

Effect of Changes in Currency Exchange Rates

Many global reinsurers review triangles at the prevailing exchange rates

This prevents distortions in age-to-age factors due to fluctuating exchange rates year-to-year

Comparisons of Development Factors and Patterns

Reinsurance vs.Primary Insurance (Similar Type of Business)

More volatility in age-to-age factors at earlier maturities for:

Reinsurance compared to primary insurance ·Paid losses compared to reported losses

Greater volatility means more uncertainty in age-to-age factor selection and projected ultimate losses

Longer reporting/payment patterns for reinsurance due to lags in reporting to the reinsurer

Proportional vs. Non-Proportional Reinsurance (Same Line of Business)

For the same line of business

Significantly more volatility in age-to-age factors for non-proportional treaty and facultative reinsurance than for proportional treaty reinsurancee CDFs are greater for non-proportional treaty and facultative reinsurance (longer dev. patterns Also - More volatility in ratios of paid-to-reported losses for non-proportional and facultative

A key difference is that proportional reinsurance is ground-up and non-proportional is excess of loss

Takeaway: The greater volatility in age-to-age factors and diagnostics results in greater uncertainty in projected ultimate loss from the development method.

Property Reinsurance excl.Catastrophe vs.Property Reinsurance Catastrophe

Reinsurer carried reserves for catastrophe losses are usually based on ground-up exposure-based assessments using info from ceding companies by contract (NOT the development method)

---

The impact of catastrophe events at different times of the year impacts development and age-to age factors for different years ODevelopment method assumptions may not be appropriate .Volatility is much higher for catastrophe vs. ex-catastrophe property reinsurance.

Takeaway: Methods using age-to-age factors are often not appropriate for property catastrophe

## Implications of Volatility in Loss Development

Greater volatility in age-to-age factors can lead to greater uncertainty in projections of ultimate loss (and therefore unpaid loss)because ODevelopment methods and other methods rely on the age-to-age factors that have greater volatility (B-F method does and the expected method often does to set ELRs) OGreater volatility in indicated ultimate loss ratios is often used to select ELRs for the expected and B-Fmethods

Takeaway: Greater volatility in projected ultimate loss results in a greater range in indicated IBNR and Total Unpaid for:

:Reinsurance compared to primary insurance Non-proportional treaty and facultative compared to proportional treaty reinsurance Catastrophe reinsurance compared to excluding catastrophe reinsurance for property

## Quota Share and Stop Loss Reinsurance Examples.

### Quota Share Reinsurance

Apply the %ceded (or 1 - %retained) to gross ultimate loss, case reserves, paid loss, and IBNR to get the ceded values. ·The %ceded may change over time, so calculations are applied by year

## Stop-Loss Reinsurancee

Stop-Loss reinsurance applies after all other reinsurance and protects the net result of a ceding company Once a ceding company breaches stop-loss coverage, the reinsurer will often increase the price or the attachment point (or both

---

## LDF Curve-Fitting and Stochastic Reserving

### Overview

Clark is a calculation-heavy paper and you should be able to do the Variance of Reserve calculations effortlessly by the time of the exam, a problem which comes up regularly.You should also be prepared fon questions about model assumptions, diagnostic graphs and how to evaluate results for reasonableness.

The focus of Clark is to create develop a loss reserving model that estimates a central loss reserve estimate (with the LDF or Cape Cod method) and can calculate the variance of the reserve estimate

### Goals of a loss reserving model

Mathematically describe loss emergence to estimate loss reserves

·Estimate the reserve range around the expected reserve,due to variance from:

OProcess variance - uncertainty due to randomness OParameter variance - uncertainty in expected value

## Expected Loss Emergence

Instead of using LDFs directly,we're going to fit a curve, $G(x)$, to incremental losses using MLE in order to get the best-fitting parameters. Then, we'll use this curve to estimate the payment pattern (from 096 to $100\%$ )as an accident year matures.

Clark uses two different curves,the Loglogistic and Weibull curve.The Weibull curve has a lighter tail

![](https://storage.simpletex.cn/view/fabGlAWtl0na5V88igFIrQ1VUqA4sZ1fX)

![](https://storage.simpletex.cn/view/f9mKGVc5mle0EEWQG81Q5mopsgGuIFma8)

$X$ -average age ofloss occurrence.

Advantages of using a parameterized curve for the loss emergence pattern

·Estimating unpaid losses is simplified (only need 2 parameters)

Can alsouse data that's notfrom a trianglewith evenly spaced evaluation dates

Payout pattern, $G(x)$, is a smooth curve and doesn't overfit like age-to-age factors might

## Advantage of using data in a tabular format.

·Can use data at irregular evaluation periods or when you only don't have the full triangle

---

### Process Variance

Process variance is the variance due to randomness in the insurance process

## Loss Model Assumptions

Assume incremental losses have a constant variance/mean ratio, $\sigma^{2}$ Assume incremental losses follow an over-dispersed Poisson model

### Fittinq the loss emerqence curve

We find the best-fitting curve using the maximum likelihood method. For a given set of parameters, we calculate the expected incremental losses, $\mu_{i}$ ，for each cell of the loss triangle. Then, we compare the likelihood that the actual incremental losses came from an over-dispersed Poisson distribution with the parameters $\mu_{i}$ and $\sigma^{2}$

The goal is to find the set of parameters that maximize the log-likelihood function.See the “Finding BestFit Parameters with MLE" recipe for an example of how to do this.

Advantages of usinq an over-dispersed Poisson distribution to model incremental losses

·Using a scaling factor, $\sigma^{2}$ , allows us to match the $1^{\mathrm{st}}$ and $2^{\mathrm{nd}}$ moments of other distributions ·TheMaximum Likelihood Estimate reproduces LDF and Cape Cod loss reserve estimates

### Parameter Variance

Parameter variance is the variance in the estimate of the parameters.It's calculated based on the RaoCramer lower-bound approximation, using the second derivative information matrix. The information matrix is used to calculate the covariance matrix,which is used to calculate the parameter variance. The actual calculation of theparameter variance is too complexfor the exam

## Key Model Assumptions

### .Incremental losses are iid

OIndependent - One period doesn't impact surrounding periods (this assumption fails if there are calendar year effects such as inflation) OIdentically distributed - Assume the same emergence pattern, $G(x)$ ,for all accident years (this assumption fails if the mix of business or claims handling changes)

:Variance/Mean Scale parameter, $\sigma^2$ ,is fixed and known

oWe ignore the variance of $\sigma^{2}$

.Variance estimates use approximation to the Rao-Cramer lower bound

Themodel assumptionsmean there's a potential thatfuture losseshave higher variance than what the model indicates.

---

## LDF Method

A problem with the LDF method is that there is a parameter for each accident year for the current LossAy See the “Variance of Reserves (LDF Method)” recipe for how to calculate reserve variance.

# CapeCod Method

The Cape Cod method uses additional information, an exposure base. Clark recommends on-level earned premium, but another exposure base can be used as long as it's proportional to ultimate expected losses by accident year.

Premium must be on-leveled so that we can assume a constant ELR across all accident years. We could also adjust for loss trend net of exposure trend so that all accident years are at the same cost level.

### LDF Method vs.Cape Cod Method

LDF method over-parameterizes the model, fits to the noise" in the data

OFor a 10-yr triangle, there are 12 parameters to estimate and only 55 data points

·Cape Cod has lower parameter variance because there arefewer parameters to estimate and it uses more information (on-level premium)

### Variance of Loss Reserves

Once you have the loss reserve estimate, the scale parameter and the parameter variance,you can calculate the variance around theloss reserve estimate

$$ProcessVar=\sigma^{2}\cdot Resv$$

TotalVariance = ProcessVariance+ ParameterVariance

## Diagnostics

ELR for Cape Cod

The Cape Cod method assumes a constant ELR across all accident years. Test this assumption by graphing the estimated ultimate loss ratios by accident year.

The estimated ultimate loss ratios should be random around the ELR with no patterns or trends.If there is a pattern, then the assumption of a constant ELR isn't reasonable and the Cape Cod reserve estimate could be biased.

![](https://storage.simpletex.cn/view/fqvsNkgO2U0zuAVMgf5GIqCNP4UQpFmA2)

## Residual Graphs

![](https://storage.simpletex.cn/view/f3Gq6KCFdS8nEstDSb2LTgrOULgsiv2bp)

$r_{Y,k} = \frac{InCloss_{Y,k}}{\sqrt{\sigma^2 + \mu_{Y,k}}}$

---

Residual graphs are an important diagnostic to test the underlying assumptions.Below are the graphs Clark specifically mentions and what assumptions they test:

·Normalized Residuals vs. Increment Age OTests how well the loss emergence curve fits incremental losses at different development periods. :Normalized Residuals vs. Expected Incremental Loss ( $\mu_{i}$ ) OTests the variance/mean ratio $\sigma^{2}\colon$ If the variance/mean ratio is not constant, we should see residuals clustered closer to zero at either high or low expected incremental losses Normalized Residuals vs. Calendar Year OTests whether there are diagonal effects (e.g. high inflation in a calendar year)

For all the graphs, the residuals should be random around zero with no patterns or autocorrelations. If this isn't the case,then some assumptions of the model areincorrect

### Process vs.Parameter Variance

We should see that parameter variance is greater than process variance. This is because most of the uncertainty is due to the inability to estimate the expected reserve (parameter variance)rather than uncertainty due to random events (process variance)

The reason for this is that there are so few data points in a loss triangle to estimate the parameters.The Cape Cod method lowers the parameter variance by including the exposure data

### Other Calculations

## Variance of Prospective Losses

The regular Clark method calculates reserve variance for past accident years. This same approach can be used to calculate variability around prospective losses for the prospective accident year (period). See the "Variance of Prospective Losses" recipe for this calculation.

### Calendar Year Development

Instead of estimating the total unpaid loss reserve, we can calculate the unpaid losses that we expect will be paid over the next calendar year and create a range around that.

The advantage of this type of calculation is that the model can be tested in a relatively short period of time. After one year, the actual 12-month loss development can be compared to the original forecasted range to test whether the actual development falls within the range.See the“Variance of Calendar Year Development" recipe for this calculation.

## Variance of Discounted Reserves

The discounted paid loss reserve is calculated by discounting the future payments at the half-year mark.For the exam a calculation problem doesn't seem testable

---

Onekey point is that the CV of the discounted loss reserve is smaller than the CV of the undiscounted loss reserve.This is because the tail of the payout curve has the greatest parameter variance,but is discounted the most.

## Adjustments for Other Exposure Periods

The formula for $G(x)$ is only valid on an accident year basis where the first development period is at 12 months. If the first development period is shorter than 12 months or policy year is used, then you need to make some adjustments.

Percent of ultimate loss as of time $t$, with annualization

$$G(t)=expos(t)\cdot G(x)\quad\mathrm{where}\quad x=AvgAge(t)$$

|           | Accident Year                                                                 | Policy Year                                                                                                                                                                    |
| --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| expos(t)  | $\\begin{cases} \\frac{t}{12}, & t \\leq 12 \\\\ 1, & t > 12 \\end{cases}$    | $\\begin{cases} \\frac{1}{2}\\left(\\frac{t}{12}\\right)^2, & t \\leq 12 \\\\ 1-\\frac{1}{2}\\left(2-\\frac{t}{12}\\right)^2, & 12 < t \\leq 24 \\\\ 1, & t > 24 \\end{cases}$ |
| AvgAge(t) | $\\begin{cases} \\frac{t}{2}, & t \\leq 12 \\\\ t - 6, & t > 12 \\end{cases}$ | $\\begin{cases} \\frac{t}{3}, & t \\leq 12 \\\\ \\frac{(t-12)+\\frac{1}{2}(24-t)(1-expos(t))}{expos(t)}, & 12 < t \\leq 24 \\\\ t-12, & t > 24 \\end{cases}$                   |

I would know all the formulas for accident year.For policy year, I would make sure to know the special cases where $t=12$ months and where $t=24$

| Policy Year | expos(t) | AvgAge(t) |
| ----------- | -------- | --------- |
| t = 12      | 50%      | 4         |
| t = 24      | 100%     | 12        |

## Recipes for Calculation Problems

Variance of Reserves (LDF Method) Variance of Reserves (Cape Cod Method) Normalized Residuals Variance of Prospective Losses :Variance of Calendar Year Development Finding Best-Fit Parameters with MLE

---

## Measuring the Variability of Chain Ladder Reserve Estimates

## Key Ideas

The goal of this paper is to use the chain ladder method to create a confidence interval around the ultimate loss and estimatedloss reserve

Mack-Chain Ladder focuses on two main ideas:

1.Three main assumptions underly the chain ladder method.For a loss triangle,we should look at different diagnostic graphs and tests to see whether the chain ladder method is appropriate or not.

2.Based on the three assumptions,we can calculate the estimated loss reserve and the standard error of the estimated loss reserve for each accident year and for all years combined with the chain ladder method. Then, after making an assumption about the distribution of the loss reserve (e.g. lognormal) we can calculate loss reserve confidence intervals.

## Mack Assumptions

1.Expected losses in the next development period are proportional to losses-to-date

$$\mathrm{E}\Big[C_{i,k+1}\:|\:C_{i,1},\cdots,C_{i,k}\Big]=C_{i,k}\cdot LDF$$

·The chain ladder method uses the same LDF for each accident year

Uses most recent losses-to-date to project losses, ignoring losses as of earlier development periods

2. Losses are independent between accident years.

3. Variance of losses in the next development period is proportional to losses-to-date with proportionality constant $\alpha_{k}^{2}$ that varies by age.
   $$\mathrm{Var}\Big[C_{i,k+1}\:|\:C_{i,1},\cdots,C_{i,k}\Big]=C_{i,k}\cdot\alpha_{k}^{2}$$

## Alternative Variance Assumptions (Weighted LDFs)

The chain ladder method in Mack - Chain Ladder uses volume-weighted LDFs. This implies that variance of losses in the next development period $(L_{oss_{k+1}})$ is proportional to losses-to-date $(Loss_{k})$ Assumption 3.

If we calculate the LDFs a different way, such as the simple average of the age-to-age factors or age-to-age factors weighted by $Loss_k^2$ ,then we're making a different variance assumption Variance Assumptions

| Var$(C_{i,k}) \propto$ | LDF calc.   | LDF              |
| ---------------------- | ----------- | ---------------- |
| 1                      | $C^2_{i,k}$ | $C^2_{i,k}$ -wtd |
| $C_{i,k}$              | $C_{i,k}$   | Vol-weighted     |
| $C^2_{i,k}$            | 1           | Simple Avg       |

---

### Variance of Reserves

Using the three chain ladder assumptions, we can calculate the variance of the reserve estimate with Mack's formula for the standard error of the reserve. We get the estimated reserve and the standard error of the estimate by accident year and for the overall reserve

One disadvantage of the Mack method (compared to the bootstrap method) is that it doesn't tell us about the shape of the loss reserve distribution. It only gives us the mean and standard deviation. To create confidence intervals,we need to make an assumption about the distribution.

### Reserve Confidence Intervals

Once we've done all the calculations, we have an expected loss reserve estimate (the loss reserve estimate from the standard chain ladder method) and the standard error (standard deviation) of the loss reserve estimate.Besides these values, the method doesn't tell us anything else about the distribution of the loss reserve estimate

So, we're going to assume a distribution and use the mean and standard deviation of the loss reserve that we calculated. Mack looks at two distributions: Normal and Lognormal

Normal Distribution

Lognormal Distributior

![](https://storage.simpletex.cn/view/fMXxRe4VXrUsiC18VIoVlunkRQ2RqfzDC)

![](https://storage.simpletex.cn/view/f7Isbf4yYS4RIGqADqGaCHkYzFyRfC49v)

If min of C.I. is negative OR s.e. $R)>50\%$ of $R$ use Lognormal

## Checking the Chain Ladder Assumptions.

The three Mack assumptions have significant implications, so we should take a look at some different tests and diagnostics to see how well the assumptions hold up.

### Plot of Cumulative Losses from Adjacent Periods

This plot tests assumption 1. We want to see if losses at the next period are proportional to losses-to-date with no intercept.

## If the assumption holds, you should see:

Linear relationship between. $Loss_{k+1}$ and Loss, through the origin (no intercept)

![](https://storage.simpletex.cn/view/fnuOFAuKbTbrVVWYPlPkDagz8QvhbGDX5)

·Line should go through the data points

## If the assumption is violated,you might see

·The data points show that there should be anintercept term in the regression line .The relationship isn't linear

---

### Plot of Weighted Residuals

This plot primarily tests assumption 3, the variance assumption

![](https://storage.simpletex.cn/view/fgMvNrsPbtdppGmfLT4qX0P3hht2IHHHS)
010,00Doss20,000 30,000

## If the assumption holds, you should see:

Residuals should be random around zero with no significant trends or patterns.

## If the assumptionis violated, you might see：

·Variance of residuals is higher at one end of the graph than at the other Residuals show an increasing (or decreasing trend)

If the residuals for a few development periods aren't random, we can graph the residual plots using the LDFs for the alternative variance assumptions: $\operatorname{Var}(C_{k+1})\propto C_{k}^{2}$ and Var$(C_{k+1})\propto1$ If the residual plots for one of the alternative assumptions is more random, then we could replace the volume-weighted LDF with the alternative LDF( $f_{\mathrm{ko}}$ or $f_{\text{k}2}$ ）.

### Testing Assumption 2- Independence between accident years (Calendar Year Test

The assumption ofindependence between accident years implies that there are no calendar year effects that impact losses from multiple accident years (causing a dependence between accident years)

We test the null hypothesis that there are no calendar year effects with Mack's calendar year test (see the Mack - Chain Ladder Calendar Year Test" recipe). If there are significant calendar year effects, then assumption 2 is violated.

Examples of calendar year effects:

·Major changes in claims handling practices ·Major changes in setting case reserves ·Unexpectedly high (or low) inflation ·Significant changes due to court decisions

### Testing for Correlation Between Adjacent LDFs (Assumption 1)

The first assumption implies that subsequent development factors are uncorrelated (e.g. high development from ages 12 to 24 gives no information about how losses develop from age 24 to 36)

In the chain ladder method, we always use the same LDF from ages 24 to 36 no matter how losses developed from ages 12 to 24. For instance, if the overall LDF from ages 12 to 24 is 3.5 and a particular AY developed from 1,000 to 5,500 (age-to-age factor of 5.5), we still expect the same 96 development from 24 to 36.

Example: If a book of business typically shows a smaller-than-average increase $Loss_{k+1}/Loss_{k}<LDF_{k}$ , after a larger-than-average increase, $Loss_{k}/Loss_{k-1}>LDF_{k-1}$ ,then the chain ladder method would not be appropriate

---

Mack-ChainLadder uses Spearman’s rank correlation to test for correlation between LDFs(See the "Mack - Chain Ladder - Correlation of Adjacent LDFs" recipe)

The Mack Correlation of Adjacent LDFs test looks at the triangle as a whole, not at each column-pair separately. This is because it's more important to know if correlation between LDFs prevails throughout the triangle

Advantages of using Spearman’s rank:

The test is distribution-free (doesn't assume LDFs are from a normal distribution ·Differences in variances of LDFs between development periods is less important because it uses ranks

## Reviewing Results for Reasonableness

·MSE of the total reserve is greater than the sum of the MSE from the reserve for individual accident years. OBecause the same LDFs are used for all accident years, the loss reserve estimates are positively correlated between accident years, increasing the total MSE Higher standard error percentage for the oldest accident years OThe absolute standard error should be lowest for the oldest accidentyears,but since the size of the loss reserve is so small, the standard error percentage will be higher. ·Higher standard error percentage for the most recent accident year (or two) OUncertainty in forecasting future losses is highest for the most recent accident years because losses are immature, so the standard error percentage will be higher.

### Weaknesses of the Chain Ladder method

·Estimators of thelast 2 or3LDFsrely on very few observations Doesn't work well for the most recent accident year where losses-to-date provide a very uncertain base to project ultimate losses OAnother method, such as the least squares method would put less credibility on the immature losses.

## Recipes for Calculation Problems

Residual Test Calendar Year Test Reserye Confidence Interyal MSE Calculation Correlation of Adjacent LDFs Overall MSE Calculation

---

## Testing the Assumptions of Age-to-Age Factors

## Overview

Think of Venter Factors as an extension of the Mack (1994) paper. Venter takes a look at the three key Mack assumptions underlying the chain ladder method and identifies six ways to test those assumptions.If those tests fail for a loss triangle,Venter points out a few alternative loss reserving methods to use instead.

As you go through Venter Factors, think about how it ties together with Mack (1994) to give a more complete picture of the chain ladder method and how to use the chain ladder method to create reserve ranges.

## MackAssumptions-Restated

If the assumptions below hold, then the chain ladder method gives the minimum variance unbiased linear estimator of future loss emergence.

Assumption 1

Expected incremental loss emergence is proportional to cumulative losses-to-date

$$\mathrm{E}\Big[\:IncLoss_{AY,k+1}\:|\:data\Big]=\Big(LDF_{k}-1\Big)\cdot Loss_{AY,k}$$

Assumption 2

Losses are independent between accident years

Assumption 3

Variance of the next incremental loss is a function of age and cumulative losses-to-date.

$$\mathrm{Var}\Big[IncLoss_{AY,k+1}\:|\:data\Big]=function\Big(k,Loss_{AY,k}\Big)$$

We can't directly test these assumptions, but there are six testable implications that fall out of these assumptions that we can test.If the tests for any of the implications fails, then the three Mack assumptions don't hold up, meaning that the chain ladder method doesn't give the minimum variance unbiased linear estimate of future losses.

---

## Testable Implication 1 -Significance of development factors

Tests Assumption 1: Linear loss emergence proportional to loss-to-date

Assumption 1 assumes incremental losses are proportional to losses-to-date with a development factor. If that's the case, the development factor shouldbe statistically significant.

Later in the paper, Venter shows the regression including a constant, $\hat{y} = a+ bx$ . This tests the alternative linear with constant (least squares) model compared to the chain ladder model and also indirectly tests for implication 1. Excluding the constant term in the regression will give a more direct test of implication 1.

One last point: You can't just do a regression of $L_{oss_{k+1}}$ vs.Loss. This is because what we really want to predict is the incrementa/loss from one period to the next.If we use $Loss_{k+1}$, then comparing the coefficient $b$ to the standard deviation directly will overstate the significance of thefactor.

## Testable Implication 2 - Superiority to alternative loss emergence patterns

Tests Assumption 1: Linear loss emergence proportional to loss-to-date

If assumption 1 is correct, then the chain ladder model should predict incremental losses better than alternative loss emergence patterns. We can use a goodness-of-fit test to compare the alternative models to the chain ladder method.

Different Loss Emergence Patterns

| Expected Incremental Loss is...                 | Model                          |
| ----------------------------------------------- | ------------------------------ |
| ...proportional to loss-to-date                 | Chain Ladder                   |
| ...proportional to loss-to-date with a constant | Least Squares                  |
| ...percentage of ultimate loss                  | Bornhuetter-Ferguson: f(d)h(w) |

Alternative Pattern 1 - Linear with a constant (least squares method).

$$\mathop{\mathrm{E}}\Big[IncLoss_{d}\Big]=f(d)\cdot Loss_{k}+g(d)\\\mathop{\mathrm{factor}}_{\mathrm{constant}}$$

Including a constant term is often significant in the first development period or two, especially for highly variable and long-tail lines

Test this alternative pattern by running a linear regression of $IncLoss_{k+I}$ Vs. $Loss_k$ to get the factors of the development formula $\hat{y}=a+bx$ If the constant is statistically significant, this loss emergence pattern is more strongly supported than the chainladder method

### Alternative Pattern 2-Factor times parameter (parameterized BF model)

If expected incremental loss is modeled as a percent of ultimate, we can use the parameterized BF model

![](https://storage.simpletex.cn/view/fF8RKSoTaD4T6iNERyvWGXTV8xOviEksK)

---

We need to solve for the f(d) and h(w) factors iteratively.Note that the final f(d) factors won’t necessarily sum to 1. Likewise, the h(w) factors aren't equivalent to estimated ultimate loss. Instead, f(d) and h(w) are used together to estimate future incremental losses.

Compare the parameterized BF model to the chain ladder model by doing a goodness-of-fit test. If the parameterized BF model has a lower test statistic, then the loss emergence in the loss triangle is better described by the parameterizedBF model.

The parameterized BF model has twice as many parameters (2n-2) as the chain ladder model. So,it's often over-parameterized, resulting in a higher adjusted SSE. We can improve the performance by reducing the number of parameters (which will increase SSE, but hopefully decrease Adjusted SSE))

The parameterized Cape Cod method uses one h parameter for all accident years. If the ultimate loss for each accident year is roughly the same, then this model might be an improvement over the fully parameterized BF

This is a bit different than the normal Cape Cod model that uses the same expected loss ratio for all accident years. A possible improvement is to use a loss ratio triangle with the Cape Cod method, because a constant ultimate loss ratio over all accident years is more reasonable

## Disadvantages of the Cape Cod method:

·Requires relatively stable level of loss exposure over accident years

·Need to adjust for known exposure and price level differences between accident years

## Testable Implication 3 - Linearity of the model: Residuals vs. Lossk.

Tests Assumption 1: Linear loss emergence proportional to loss-to-date

Assumption 1 assumes incremental loss emergence is linearly proportional to loss-to-date.

If residuals show a non-linear pattern (e.g. positive - negative - positive), then incremental loss emergence is a non-linear function of loss-to-date

## Testable Implication 4 - Stability of development factors: Residuals vs. time

Tests Assumption 1: Linear loss emergence proportional to loss-to-date

Assumption 1 uses the same development factor for all accident years, so we would expect that the appropriate development factor is stable over time.

A pattern of high/low residuals when plotted against time indicates instability and is evidence against using the same development factor for all AYs.

If the age-to-age factors appear stable, we should use all accident years when calculating the LDFs (to minimize variance). But, if it looks like the average level of the age-to-age factors is shifting over time, we could use a weighted average of the LDFs over the last n-years (e.g. 5-year weighted average LDFs)

---

### Testable Implication 5 - Correlation of development factors

Tests Assumption 2: Independence between Accident Years \*

If there is significant correlation between development factors at different ages, then this is evidence against the chain ladder method.

### \*Confliction with Mack (1994):

There's some overlap between Mack assumptions 1 and 2 as they're discussed in the two papers:

●In Mack (1994) (pg. 109), Mack states that the linearity assumption (assumption 1) implies that "subsequent development factors... are uncorrelated." In Venter Factors (pg.832-833), Venter says that the correlation test is to check for dependencies in the triangle,which is a test on theindependence assumption (assumption 2)

Just note that there's some disagreement between Venter and Mack regarding the assumption tested by correlation of development columns

## Testable Implication 6 - Significantly high or low diagonals (calendar year effects)

Tests Assumption 2: Independence between Accident Years

Run a regression of incremental losses against cumulative losses at the prior development periods and include a dummy variable for each diagonal.

If any of the dummy variables are statistically significant, then this indicates calendar year effects.

## Recipes for Calculation Problems

Correlation of Development Factors

: Parameterined Br: $f(d)h(w)-$Var c$f(d)h(w)$ $oc$ sta ce

Testing for Significantly High/Low Diagonals Goodness of Fit Test

---

Using the ODP Bootstrap Model

### Overview

The goal of the bootstrap model is to create a full distribution of possible loss reserve outcomes, not just a point estimate or the mean and variance like in the Mack (1994) approach.It does this by sampling residuals from the original loss triangle to create simulated loss triangles, one for each iteration in the simulation. Then, an estimated loss reserve is calculated for each iteration.

## GLM Bootstrap Model

The recipes in the Exam 7 Cookbook show the different types of problems you might be asked from the bootstrap model. Below is a high-level overview of how the basic GLM bootstrap model works.

### GLM Setup

1)Shapland uses a GLMwith a log-link function and over-dispersed Poisson error distribution

Variance of Incremental Losses

$$\mathrm{Var}\Big[q(w,d)\Big]=\phi\cdot m_{\omega,d}^{z}$$

Expected Incremental Losses

$$
\begin{aligned}
&\operatorname{E}\Bigl[q(w,d)\Bigr]\:=\:m_{_{\infty,d}} \\
&\ln\left(m_{_{\omega,d}}\right)=\eta_{_{\omega,d}} \\
&\eta_{\omega,d}=\alpha_{\omega}+\sum_{d=2}\beta_{d}
\end{aligned}
$$

2)Next, set up the design matrix and the parameters for the model. The basic ODP bootstrap has a parameter for each accident year and development period. The GLM framework is flexible, so we can group some of those parameters together or add parameters for diagonal effects.

Y -Vector of the log-link triangle X -Design Matrix to solve the specified model A -Vector of the $\alpha$ and $\beta$ model parameters

Y = X \times A

$\begin{bmatrix}
\ln(g(1,1)) \\
\ln(g(2,1)) \\
\ln(g(3,1)) \\
\ln(g(1,2)) \\
\ln(g(2,2)) \\
\ln(g(1,3))
\end{bmatrix}
=
\begin{bmatrix}
1 & - & - & - \\

- & 1 & - & - \\
- & - & 1 & - \\
  1 & - & - & 1 \\
- & 1 & - & 1 \\
  1 & - & 1 & 1
  \end{bmatrix}
  \times
  \begin{bmatrix}
  \alpha_1 \\
  \alpha_2 \\
  \alpha_3 \\
  \beta_1 \\
  \beta_2 \\
  \beta_3
  \end{bmatrix}$

Solution Matrix = X \times A

$\begin{bmatrix}
\ln(m*{1,1}) \\
\ln(m*{2,1}) \\
\ln(m*{3,1}) \\
\ln(m*{1,2}) \\
\ln(m*{2,2}) \\
\ln(m*{1,3})
\end{bmatrix}
=
\begin{bmatrix}
1 & - & - & - \\

- & 1 & - & - \\
- & - & 1 & - \\
  1 & - & - & 1 \\
- & 1 & - & 1 \\
  1 & - & 1 & 1
  \end{bmatrix}
  \times
  \begin{bmatrix}
  \alpha_1 \\
  \alpha_2 \\
  \alpha_3 \\
  \beta_1 \\
  \beta_2 \\
  \beta_3
  \end{bmatrix}$

---

3)Once the model is all set up, fit the model to the triangle of incremental losses using iterated least squares or maximum likelihood. This gives us the best-fitting parameters.

4)Using the best-fitting parameters, calculate the fitted incremental loss triangle.

$$\ln\bigl(m_{\omega,d}\bigr)=\eta_{\omega,d}=\alpha_{\omega}+\sum_{d=2}\beta_{d}\quad m_{\omega,d}=e^{n_{\omega,d}}$$

5)Now, calculate the unscaled Pearson residuals between the original triangle of actual incremental losses and the triangle of fitted incremental losses.

$$r_{\omega,d}=\frac{q(w,d)-m_{\omega,d}}{\sqrt{m_{\omega,d}^{z}}}$$

6. Use the unscaledPearson residuals to calculate the scale parameter.

$$\phi=\frac{\sum r_{\omega,d}^{2}}{N-p}\quad\begin{array}{c}N\to\#\text{incremental values}\\p\to\#\text{parameters}(\alpha's,\beta's,\text{hetero-adj parameters})\end{array}$$

7)Calculate the standardized Pearson residuals by applying the Hat Matrix adjustment factor to the unscaled Pearson residuals,

$$r_{w,d}^{H}=r_{w,d}\cdot f_{w,d}^{H}\quad\mathrm{where}\quad f_{w,d}^{H}=\sqrt{\frac{1}{1-\mathbf{H}_{w,d}}}$$

## Running the Bootstrap Model

8)For each iteration, sample with replacement from the standardized Pearson residuals and calculate the sampled loss triangle.
$$q^{*}(w,d)=r^{*}\cdot\sqrt{m_{\omega,d}^{*}}+m_{\omega,d}$$

9）For each iteration, refit the GLM to the incremental losses to get new parameters, specific to this iteration's sampled loss triangle.

10. Use the new parameters to calculate the projected unpaid incremental losses.

$$\ln\left(m_{\omega,d}^{iter}\right)=\alpha_{\omega}^{iter}+\sum_{d=2}\beta_{d}^{iter}$$

11. Add process variance to the projected unpaid incremental losses with the Gamma distribution.

$$q^{im}(w,d)\sim\mathrm{Gamma}\Big(\mathrm{mean}=m_{w,d}^{iter},\mathrm{var}=\phi\cdot m_{w,d}^{iter}\Big)$$

### Shapland Bootstrap Excel Files

Ihighly recommend thatyou spend some time to see how theExcelfiles referenced in the syllabus that accompany the Shapland paper work.It will give you a much clearer idea of how the bootstrap model works. I particularly recommend looking at the “GLM Framework 6.xlsm” file.

### Advantages of the GLM Eramework

·Can tailor the model to the statistical features of the data (e.g. can add a diagonal parameter, $\gamma_{k}$ )

---

Can use fewer parameters to avoid over-parameterization (e.g. fewer AY parameters.

Can model data that's not in a loss triangle (e.g. missing data for the first few diagonals)

Disadvantages of the GLM Framework

Simulation is slower because the GLM must be solved for in each iteration

·Can't directly explain the model using LDFs

## ODP Bootstrap Model (Simplified GLM)

The simplified GLM approach can be used if the GLM bootstrap model has a parameter for each accident year and development period and uses an over-dispersed Poisson error distribution.

Instead ofusing the GLM to calculate the parameters,use the all-years volume-weighted LDFs to calculate expected incremental losses, $m_{w,d\bullet}$ After creating the sample loss triangles using resampled residuals, calculate new LDFs and use them to calculate the projected unpaid incremental losses. Process variance is incorporated the same way with the Gamma distribution.

### Advantages of the ODP Bootstrap (Simplified GLM

·Can use the simpler LDF method and the model will still be based on the GLM framework ·Using LDFs makes the model more easily explainable to others ·The GLM uses a log-link and may not work with negative incrementals, but the simplified GLM will still get a solution

### Disadvantages of the ODP Bootstrap (Simplified GLM)

Unable to adjust for calendar-year effects ·Requires many parameters and can over-fit the data

## Practical Issues

Negative Incremental Values

Because a log-link is used, the GLM framework requires incremental losses to be greater than zero

Adjustment 1:Sum of column ofincremental losses is positive

Calculate the log-link triangle but adjust the calculation for negative incremental losses to $-\ln\left[abs(IncLoss)\right]$

Adjustment 2: Sum of column of incremental losses is negative

Shift allthe incremental losses $up$ by the size of the largest negative incremental ·Run themodel Shift all the fitted incremental losses back down

---

## Negative values during simulation of process variance: An issue that can ariseis if the model simulates negative incremental losses, $m_{w,d}.$ This is a problem because

the process variance step can't handle negative incremental losses because the variance of the Gamma distribution would be negative.

Shapland shows two possible ways to adjust themodel to handle negative $m_{w,d}$ values during simulation on Pg. 21-22.For both options, a value is simulated from a modified version of the Gamma distribution, using the absolute value of the negative expected loss $m_{w,d}$ .Both options transform the distribution so that the simulated value has an expected value equal to the negative incremental loss $m_{w,d}$

Below is a graphical view of how these two adjustments work:

Distribution based on the absolute value of $m_{\omega,d}$
$$\mathrm{Gamma}\Big(\mathrm{mean}=\Big|m_{\omega,d}\Big|,\mathrm{var}=\phi\cdot\Big|m_{\omega,d}\Big|\Big)$$

![](https://storage.simpletex.cn/view/fn71mTIbQv0ui5uhrvgKOOFcx8NGRMD9V)

Option 1: Change the sign of the simulated value $-{\mathrm{Gamma}\left(\mathrm{mean}=\left|m_{\omega,d}\right|,\mathrm{var}=\phi\cdot\left|m_{\omega,d}\right|\right)}$

![](https://storage.simpletex.cn/view/fHVFmGAaP93tlgXbXDGCpMkMSGOHul4Nt)

Option 2: Shift the entire distribution to have a mean of $m_{\omega,d}$

![](https://storage.simpletex.cn/view/f0VkRxsMxoKAet2PelpKdt72fLyrPlZKd)

---

### Options to handle extreme outcomes caused by negative incremental losses:

1.Identify and remove extreme iterations from results 2.Recalibrate the model to correct the source of negative incremental losses (e.g.model salvage and subrogation separately) 3.Limit incremental losses to a minimum of zero

Non-Zero Sum of Residuals

If we desire an average residual of zero, then we can shift all the residuals up (or down) by a constant so that the sum of the shifted residualsis zero.Then, sample from the shiftedresiduals

## Using N-Year Weighted Average

GLM Bootstrap Model:

·Only use the most recent $N_{4}1$ diagonals to parameterize the model

## ODP Bootstrap Model:

: Calculate $N$ year LDFs and use to calculate residuals for the most recent $N+1$ diagonals

·Resample residuals for the whole triangle (because we need to calculate cumulative losses)

·For each sample triangle,calculate new $N$ year LDFs and use to project future incremental losses

Missing Values

## GLM Bootstrap Model:

·Missing data simply reduces the number of observations in the data.

## ODP Bootstrap Model:

Estimate the missing value from surrounding values, OR ·Modify LDFs to exclude missing values

### Outliers in the Original Data

Can remove the value and treat like a missing value, OR Identify and exclude outliers from the LDF calculation and residual calculations,but re-sample the corresponding incremental loss for the sampled triangles.

### Heteroscedasticity

# Stratified sampling:

Only sample residuals from within the heteroscedasticity group

Disadvantage -Some groups may have few residuals.This limits the variability possible in the model.

---

### Hetero-adjustment factors based on standard deviation of residuals:.

The hetero-adjustment factor adjusts the standardized Pearson residuals to the average residual standard. deviation for the triangle as a whole. With all the residuals at the same level of variability, the bootstrap model can sample residuals from the entire triangle.

Hetero-adjustment factors based on different scale parameters

Instead of using standard deviations of residuals, use the ratio of the square roots of the overall scale parameter and the scale parameter for the groups based on age. Then, the hetero-adjustment factors are used the same way as above during simulation.

## Heteroecthesious Data

## Partial first development period data:

·Reduce future incremental losses for the latest accident year to correspond to the earned exposure.

## Partial last calendar period data:

a)Annualize exposures in the last diagonal so they're consistent with the rest of the triangle b)Calculate the fitted triangle and residuals. c)During the ODP bootstrap simulation, calculate and interpolate LDFs from the fully annualized sample triangles. d)The last diagonal of the sample triangle should be adjusted to de-annualize incrementals on the latest diagonal. e)Project future values by multiplying the interpolated LDFs with the new cumulative values. f)Reduce thefuture incremental values for the latest accident year to remove future exposure (because this is a partial first development period)

## Exposure Adjustment

If there is rapid growth or a book is put in runoff, the exposure level can change significantly year-to-year.

a)Divide all loss data by exposures for each accident year to get pure premium. b)Run the model based on pure premium. c)At the end,multiply results by the exposure level to get the total value.

Advantage In the GLM framework, with the exposure adjustment, we can use fewer AY parameters

# Tail Factors

Instead of using a deterministic tail factor, we can assign a distribution to the tail factor parameter. This makes the tail factor stochastic within the bootstrap model.

### Parametric Bootstrap

If there is a lack of extreme residuals,we can fit a distribution to the residuals.Instead of sampling with replacement directly from the residuals, we sample residuals from the parameterized residual distribution.. This will allow for more extreme residuals in the sampled triangles

---

## Diagnostics

You should understand the different diagnostics used to assess the model reasonableness. You should be able to read graphs and output and draw conclusions about the model. Make sure you know what to expect from each diagnostic.Definitelyreview the graphs and tables in the Shapland appendices.

## Purpose of diagnostics:

·Test model assumptions ·Gauge how well the model fits the data ·Help guide adjustments of model parameters

### Residual Graphs

Residuals should be random around zero.You should look at the following types of residual graphs:

Residuals vs.Calendar Year Residuals vs. Development Period (look for heteroscedasticity) Residuals ys. Accident Year Residuals vs.Fitted Incremental Loss

### Normality Test

This test compares the residuals to the normal distribution.Normality isn't required, but Shapland does mention this as a diagnostic to review. If residuals are close to normal, you should see:

·Normality plot with residuals in line with the diagonal line (normally distributed) ·High $\mathbb{R}^{2}$ value and p-value greater than $5\%$

AIC and BIC can be used to compare different models to see which modelis closest to Normal while penalizing for extra parameters (a lower value is better):

$$\mathrm{AIC}=2\:p+n\Bigg[\ln\Bigg(\frac{2\pi\times\mathrm{RSS}}{n}\Bigg)+1\Bigg]\quad\mathrm{BIC}=n\times\ln\Bigg(\frac{\mathrm{RSS}}{n}\Bigg)+p\times\ln(n)$$

## Outliers

Use a box-whisker plot to help identify outliers. It's important to be careful about removing outliers. If outliers represent scenarios that can't be expected to ever happen again, then it may make sense to remove them. But, "outliers" may simply be extreme, but realistic, values. If this is the case, then the "outlier" should stay in the data.

### Parameter Adjustment

The GLM Bootstrap model is more flexible, so we can look at the residual graphs and adjust the parameters in the model by adding or removing additional parameters.For instance,if there is a trend in the average residuals by calendar year,then we might add a calendar year parameter to the model.

---

### Model Results

You should see the following trends in the estimated unpaid model results by accident year:

### Standard Error:

·Standard error should increase from older to more recent years ·Total standard error should be larger than the standard error for any individual year

### Coefficient of Variation

·CoV should decrease from older to more recent years ·Total CoV should be less than any individual year ·CoV could rise in the most recent years due to: OParameter uncertainty in the most recent years could overpower process uncertainty OThe model could be overestimating uncertainty (might use the BF method instead

## Multiple Models

Model risk is the risk that the model doesn't reflect the “true” loss-generating process for future losses Weighing together multiple reasonable models helps address model risk

## Correlation

### Location Mapping

For each iteration:

a)Sample residuals for segment 1 b)Track the location in the residual triangle where each sampled residual was taken c)For all other segments, sample the residuals from their residual triangles using the same locations

## Advantages:

·The method is easily implemented .Doesn't require an estimated correlation matrix

## Disadvantages:

·Requires all business segments to have the same size data triangles with no missing data Correlation of original residuals is used, can't test other correlation assumptions

### Re-sorting

Uses algorithms such as a copula to add correlation

# Advantages:

·Data triangles can be different shapes/sizes by segment

---

Can use different correlation assumptions

Different correlation assumptions may have other beneficial impacts on the aggregate distribution oEx. Can use a copula with a heavy tail distribution to strengthen the correlation between segments in the tails,which is important for risk-based capital modeling

# Recipes for Calculation Problems

Over-Dispersed Poisson GLM Setup Expected Incremental Losses from GLM

Standardized Pearson Residuals

ODP Bootstrap Model

Negative Incremental Values

Heteroscedasticity Fix: Standard Deviation

Heteroscedasticity Fix: Scale Parameter Multiple Models: Same Random Variables

Multiple Models: Independent Variables

---

## A Model for Reserving Workers Compensation High Deductibles

### Overview

The typical loss reserve methods are appropriate for ground-up losses. Siewert focuses on different methods that can be used to estimate unpaid loss reserves for different layers of losses, such as limited losses or losses above a high deductible. One of the main challenges Siewert addresses is how to calculate LDFs that are consistent between unlimited, limited and excess layers.

## Excess Loss Reserving Methods

Loss Ratio Method

Siewert applies the loss ratio method by account to reflect differences in account characteristics.There are two components to the expected excess losses:

:Per Occurrence Charge - Expected losses above the per-occurrence deductible. ·Aggregate Loss Charge -Expected losses in the deductible layer (below the per-occurrence limit) that are above the aggregate limit

## Advantages:

Useful for immature accident years when loss data is thin

Loss ratio estimates can be consistent with pricing

## Disadvantages:

Ignores actual loss experience, not that useful after several years development

May not reflect account characteristics properly if development emerges differently due to written exposures

## Implied Development

The ultimate excess loss estimate is the difference between the unlimited and limited ultimate loss estimates (calculated using the unlimited and limited losses and LDFs)

![](https://storage.simpletex.cn/view/f114VsAoBm3qAWCC8VTXiBNdOB19gB6H8)

The limited LDFs used to calculate $UIt^{limited}$ need to reflect indexed limits adjusted forinflation over time. This is because using a constant deductible for all accident years implies increasing excess losses.

## Advantages:

Can estimate excess loss for early maturities,even if no excess losses have emerged yet ·Limited LDFs are more stable than excess LDFs used for direct development

---

### Disadvantages

·Misplaced focus -we would like to explicitly recognize excess loss development

## Direct Development

Apply the XSLDF to excess loss to estimate ultimate excess loss. The XSLDF should be consistent with the limited and unlimited LDFs

# Advantages:

·Focuses explicitly on excess loss development

## Disadvantages:

XSLDFs are often highly leveraged and volatile, especially for immature periods ·Direct development doesn't produce an estimate if no excess loss has emerged yet

### Credibility Weighting (Bornhuetter-Ferquson

Excess ultimate loss estimate is a credibility weighting of the actual experience and the expected losses (loss ratio method)

# Advantages:

·Can tie to thepricing estimate forimmature periods whenlosses haven't emerged ·More stable estimate over time

# Disadvantages:

·Ignores actual loss experience to the extent of the complement of credibility

## Development Model

The first way we can get LDFs for different limits is to calculate them directly using full coverage loss experience. This way,we can directly create loss triangles with losses limited at different limits.

# Indexed Limits

Before calculating the limited LDFs from a limited loss triangle, we need to index the limits for prior accident years.This is important so that the proportion of limited-to-excess loss around the limit is consistent from year to year.

To do this,Siewert fits an exponential curve to loss severity by accident year to calculate the annual severity trend.Then,he uses the selected severity trend to trend theloss limit backwards.Once wehave the indexed limits,we can create a loss triangle with losses limited at the appropriate indexed limits and calculate the limited LDFs.

See the examplebelow about how to calculateindexed limits:

---

# Example 1

Given:

·Annual loss severity trend is $10\%$

·Deductible for an account is \$250.00C

Calculate the indexed limits to use for a five-year limited loss triangle.

## Solution

First, set the limit for the most recent accident year to the stated limit,\$250k. Then,trend the limits backward for each prior accident year

| Accident Year | Indexed Limit |
| ------------- | ------------- |
| 2012          | 170,753       |
| 2013          | 187,828       |
| 2014          | 206,612       |
| 2015          | 227,272       |
| 2016          | 250,000       |

\\(=250,000 = \\frac{1}{1.10}\\)

### Tail Factors

Siewert uses the inverse power curve to get consistent tail factors by limit. First, he fits an inverse power curve to the unlimited LDFs and select an appropriate stopping point beyond which there's no further development (e.g. 40 years). He selects the stopping point so that the inverse power curve tail factor is consistent with a tail factor based on an extended loss triangle.

To get the tail factors for the other limits, he fits the inverse power curve to the limited LDFs at each limit up to the stopping point and compound the age-to-age factors from the fitted curves.

Relationships between unlimited/limited/excess LDFs and severity relativities

There is a relationshipbetween limited/excess LDFs and unlimited LDFs using loss severity relativities

R_t^L = \\begin{cases} Severity Limited to limit L at age t \\\\ Unlimited Severity at age t \\end{cases}

Severity relativities should have the following relationships

:Severity relativity should decrease as age increases OThis is because more losses are capped at the per-occurrence limit as age increases :Severity relativity should be higher for a larger limit 0This is because a higher limit means less of the loss is capped, so the relativity is higher

You can see these relationships in the following graph of severity relativities by age and limit

---

![](https://storage.simpletex.cn/view/f9uEStS4PxH7LTetwiTe5YvSzYwCb74Nt)

Below are the key relationships:

![](https://storage.simpletex.cn/view/f02b7W9ElzbfGNE42pc6EaRavHcgpqMPT)

The unlimited LDF is a weighted average of the limited and excess LDFs.With this relationship, we can split the unlimited loss development consistently between development below and excess the limit.

![](https://storage.simpletex.cn/view/fZ1el2LGmup6gZU2bL0pmBM2DOvA4lIyn)

By using the severity relativities alone to adjust the LDF,we implicitly assume no further claim count development.e

## Distribution Model

If we use the loss data directly,we'll find instances where limited development sometimes is greater than the unlimited development. This will happen if the limited severity relativity increases from one age to the next (remember, the severity relativity should decrease as age increases)

Instead of using the data directly,we can fit a separate severity distribution to losses at each age (the severity distribution for losses at 12 months will be different than the ultimate severity distribution). Then,we can calculate the severity relativities at each age for any limit we're interested in.

Siewert calculates the unlimited LDFs directly from the fitted severity relativities.Then, using the fitted severity relativities and these unlimited LDFs, we can then calculate consistent LDFs at any other limit.

## Fitting the Model

Siewert uses a Weibull distribution and estimates the parameter by minimizing the chi-square error between the actual and expected severity relativities.Also,Siewert constrains the model so that the unlimited expected severity is equal to the actual unlimited severity at that development age

### Claim Count Development Assumption

In the development model, we started with selected unlimited LDFs based on unlimited loss data. A key difference here is that we're calculating the LDFs directly from the modeled severities.By using the severity relativities alone to calculate the LDFs, we implicitly assume no further claim count development. Because of this,an important assumption is that there's no further claim count development

---

In Siewert (see pg. 232), he discusses how we can use the modeled severities to calculate the LDFs, but specifies that if there is claim count development for the earlier maturities,it needs tobe reflected.

### Partitioninq Loss Development above and below the deductible

Because the unlimited LDF is a credibility weighting of the limited and excess LDFs, we can partition expected future development between development above and below the deductible.

As age increases, a larger portion of the expected development will be due to excess development above the limit.

%Unpaid =1-LDE - LDF-1 R-,(LDF -1)+(1-R)(XSLDF -1)\_ R (LDF\* -1) (1- R5)-(XSLDF -1) Development belowDevelopment above the deductible the deductible

Example 2

At 48 months development,below are the paid LDFs around the $250k$ deductible:

XSLDF Limited LDF Unlimited LDF 2.1521.9593.148 The 250k severity relativity at 48 months is 0.838

Partition the expected future paid development above and below the 250k deductible

### Solution

$$
\begin{aligned}
96Unpaid& =1-\frac{1}{2.152}=53.5\% \\
&=\frac{.838\cdot\left(1.959-1\right)}{2.152}+\frac{\left(1-.838\right)\cdot\left(3.148-1\right)}{2.152}=37.3\%+16.2\%
\end{aligned}
$$

The expected development of $53.5\%$ is made up of $37.3\%$ of development below the deductible and $16.2\%$ of development above the deductible.Put another way, $69.7\%$ =.373/.535) of expected future development is below the deductible and $30.3\%$ is above the deductible

### Aggregate Excess of Loss Estimate

An aggregate limit caps losses in the deductible layer that the insured is responsible for.We can't calculate development factors for losses excess the aggregate limit because the data needed to do this is thin and not likely to be credible.

Instead, Siewert recommends using a collective risk model or Table M to estimate liabilities under an aggregate limit.

---

## Collective Risk Model

Siewert uses the fitted Weibull model for the severity distribution and a Poisson claim count distribution for frequency in the collective risk model. The collective risk model provides expected aggregate excess loss in the deductible layer at each age and at ultimate (using the different fitted Weibull models for each age) Then, the expected excess losses are used to calculate the aggregate excess of loss LDFs.

Because losses excess the aggregate are so volatile,Siewert recommends using the BF method

These are the key relationships you should notice:

. Aggregate excess loss development drops off faster for smaller per-occurrence deductible limit

OBecause later development is more likely for larger claims that already are over the deductible (so they don't impact the aggregate limit)

Higher aggregate limits have more leveraged LDFs OBecause there are fewer losses excess the aggregate limit when the aggregate limit is high, especially at earlier periods

## Table M Approach

An aggregate limit is similar to a maximum premium limit used in retrospective rating plans with Table M. This is covered in Exam 8,soIwouldnt expect a significant question on the exam about this approach,but Siewert does show an example calculation in the appendix

An advantage of this approach compared to the collective risk model approach is that it can be more practical.

### Service Revenue

In a high deductible program, the insured is responsible for the deductible losses that are below the aggregate limit, but the insurer still services those claims

·Service Revenue -Reflects the costs the insurer charges the insured for servicing those claims. Service Revenue Asset -The expected ultimate service revenue minus the recoveries for service revenue to-date.

## Recipes for Calculation Problems

Loss Ratio Method

.Implied Development Method Direct Development Method Credibility Weighted Method Unlimited/Limited/Excess LDF Relationships .Distributional Model ·Aggregate Excess of Loss Ultimate ·Aggregate Excess of Loss Ultimate: Table M ·Service Revenue Asset

---

Claims Development by Layer

### Overview

The goal of this paper is to show the relationship between loss trend, a claim size (severity) model and cumulative loss development factors. With this relationship, we can adjust CDFs from a base" layer to another layer and from one cost level to another.

### Trend

The loss trend factors we use are for the ground-up unlimited loss layer and apply to cumulative loss, not incremental loss. We create a trend table of the cost level indices. This way, we can reflect trends that act in different directions such as an accident year trend or a calendar year trend

### Claim Size (Severity) Model

The loss severity distribution is used to calculate limited expected values (LEVs) at different limits, which are used to adjust CDFs from one layer to another.

We start with a severity distribution at the current cost level for each development period with different parameters for each age. This is similar to how Siewert uses a different Weibull severity distribution for each age.Then, using the trend, we can find the appropriate parameters (unlimited expected claim size) for the severity distributions at the prior accident year cost levels by trending backwards.

## Loss Development

Loss development factors are calculated as volume-weighted LDFs and CDFs using the chain ladder method

## Relationship Between Layers

Remember, the goal of this paper is to use the relationship between trend, a claim size model and loss development to calculate appropriate CDFsfor any other layer and cost level

For instance, we might have a triangle of ground-up loss data limited to \$1,00o,000 and a loss triangle from a book of business with a \$50o,000 high deductible. We can use the relationship between these three components with the method below to calculate the appropriate CDFs that we can apply to the latest diagonal to estimate ultimate excess loss for the book of business.

## Getting CDFs ata basiclimit

Normally, we calculate the LDFs directly from an unadjusted loss triangle and use them to develop losses to ultimate for all accident years. BUT, this is only appropriate if

·The loss triangle is ground-up unlimited AND ·Trend onlyacts in the accident-year direction

---

Often this isn't the case,so we first adjust the loss triangle to get data to the same cost level and to a basic per-occurrence limit where we believe the data is credible for estimating LDFs.

To do this, we first calculate the unlimited expected claim size at each age trended backwards. Then, we can calculate the LEVs to adjust the loss data.We need the LEVs at the limit of the data and accident year cost level (where the loss data is now). We also need the LEVs at the basic limit and the most recent accident year cost level.

With the LEVs, we can adjust the loss data so that the whole triangle is now at the basic limit and current accident year cost level. There are two adjustments going on at the same time:

LossLimit -Adjustfrom theloss limit of the original data to thebasiclimit ·Cost Level- Adjust from the separate accident year cost levels to a common cost level

$$\boxed{C_{AY,k}^{\prime}=C_{AY,k}\cdot\frac{\mathrm{LEV}\left[B\mid\theta_{n,k}\right]}{\mathrm{LEV}\left[L\mid\theta_{AY,k}\right]}}\quad Adjusted\:Loss_{AY,k}=Loss_{AY,k}\cdot\frac{\mathrm{LEV}\left[B_{Latot,AY,k}\right]}{\mathrm{LEV}\left[L_{AY,k}\right]}$$

Then, we calculate the LDFs and CDFs from the adjusted loss triangle. Now we have a development pattern that's at the basic limit and a common cost level.

### Getting CDFs at any other layer and accident year cost leve

Once we've got the development pattern at a basic limit and common cost level, we can use the LEVs from the claim size model to adjust the development pattern to any other limit and cost level. Most importantly, we can get the CDFs that we can apply to the most recent loss diagonal to develop losses.

The formula below uses the relationship between trend, claim size model and CDFs to calculate the adjusted CDFs:

![](https://storage.simpletex.cn/view/fYDlQGUqK7tdT154FCRn5rZmgdPWlaR5d)

Again, there are two adjustments going on in this formula:

·Adjust CDFs from the basic limit to layer X ·Adjust CDFs from the common cost level to separate accident year cost levels along the diagonal

Now, we can use these adjusted CDFs with a loss reserving method to estimate loss reserves for a loss triangle at the new layer, layer X.

## Simplified Model

A disadvantage of this method is that it requires a claim size model at each development age.We might only know the severity distribution and the expected unlimited severity atultimate

In this case, we can use a simplified model (below) to adjust the basic limit CDFs to the new layer for the most recent diagonal:

---

$F_{A,k}^X = \frac{LEV[X|\theta_{A,k}]}{LEV[B|\theta_{A,k}]}R_k$

Wheei $R_{\varepsilon}=\frac{\mathrm{LEV}\left[X\mid\theta_{AY,k}\right]}{\mathrm{LEV}\left[B\mid\theta_{AY,k}\right]}$

In this model, $R_{j}$ is the ratio between the limited severities at layer X and layer B. This is similar to the severity relativity in the Siewert paper, but remember Siewert always looks at the severity relativity of limited-to-unlimited loss. Here, we're looking at the severity relativity between limited losses at two different limits.

Besides using a ratio for the denominator,note that this simplified variation doesn't do the adjustment from one cost level to another.This method makes the assumption that the differences in cost level areimmaterial to the ratios of the LEVs by layer.

If the new layer, X,is lower than the basic limit, then $R_{j}<1$ and Sahasrabuddhe points out that should see the following properties:

## ·R,decreases as age increases.

OAt earlier maturities,most of the development will be in the lower layer below X, so $R_{,}$ will be close to 1. OAt later development periods,there will be more development in the layer between limits X and B. This means $R_{j}$ will decrease for later development periods.

## $R_{j}>\mathbf{U}=\lim R_{j}$ at ultimate, calculated as the ratio of LEVs at ultimate between layer X and B

oThis follows from the bullet above. $R_{j}$ monotonically decreases as maturity increases until losses are at ultimate and the ratio $R_{j}$ is at its minimum, U OAlso,Sahasrabuddhe points out that U can be calculated as

$$U=R_{j}\cdot\frac{CDF^{x}}{CDF^{^B}}$$

oIn this formula, the ratio of CDFs develops both the numerator and denominator of $R_{j}$ to ultimate, giving the ultimate ratio $U.$

## ·If the base layer CDFs are ground-up unlimited,then the upper limit of $R_{j}$ is $\max(Rj)=\mathbf{U}\times\mathbf{CDF}$

OIn this case,the Basic Limit,B,is Ground-Up Unlimited. 0For any maturity jbefore ultimate,the maximum of what the ratio $R_{j}$ can be is when losses limited at X are fully developed as of time j and all future development after $j$ is in the layer excess limit X. This would mean $\mathrm{CDF}_{\mathrm{Layer~X}}=1.0$C OIn this case, the ratio at ultimate can be calculated as the following by plugging into the formula from above:

$$U=R_{_{j,\max}}\cdot\frac{1.00}{CDF^B}$$

ORearranging this and since layer $B$ is ground-up unlimited, we have:

$$R_{_{j,\max}}=U\cdot CDF$$

---

## Assumptions

·Actuary must select the basic limit ·Requires a claim size model (but with the simplified model we only need it at ultimate) ·Loss trianglemust be adjusted to basic limit and a common cost level

### More difficult assumptions

Claim size models at earliermaturities aren't usually available OThe simplified version only uses the ratio of LEVs at earlier maturities which could be easier to estimate ·Must calculate trend indices appropriate for cumulative losses,which may be difficult because: oTrend typically impacts incremental losses OTrend on reported losses and the timing of trend on case reserves is difficult to get at

## Interpreting Results

We can see how this approach impacts the development pattern if we take a limited loss triangle at limit L and compare the CDFs calculated directly from the triangle to the CDFs calculated from the method above (first adjusting to a basic limit and common cost level, then adjusting back to limit L and the cost level for the latest diagonal).

Examples 1 and 2 in the paper appendix shows this comparison. Both examples use the same data but Example 2 uses a severity model with larger claim sizes. Example 2 shows greater differences between the calculated CDFs with the Sahasrabuddhe method and the unadjusted CDFs (from the original loss triangle).

### Key relationships

Differences are greater for larger expected unlimited claim size which increases the expected loss in the layer between the basic limit and the new limit. Differences are greater where trend and/or loss development act over longer time periods (longtailed lines) or when the loss trend is higher.

The differences are smaller for short-tail lines, low trend rates and limits above the working layer (limits significantly higher than the average severity)

## Recipes for Calculation Problems

·Determine LDFs at Basic Limits Calculate Layer LDFs from Basic Limit LDFs ●Calculate Layer LDFs from Basic Limit LDFs:Simplified Model

---

## Estimating the Premium Asset on Retrospectively Rated Policies.

### Overview

Teng and Perkins is a calculation-heavy paper focused on how to estimate the premium asset for retrospectively rated policies. The key to this method is the relationship between loss development and premium development (the PDLD ratios).

Make sure to thoroughly review the exhibits at the end of the paper. They show all of the steps in the calculation of the final premium asset from the original premium and loss triangles.

### Retro Rated Policies

Reasons why Retro Rated Policies are Popular

·Premium is returned to the insured for good loss experience Cash flow advantage - The insured can pay premium as losses are reported or paid, instead of upfront ●More risk is shifted to the insured -Final premium varies with loss experience (good for insurer)

## Retro Premium Formula

The premium for a retro policy at the $n^\mathrm{th}$ adjustment is givenby the following formula:

$$Prem_{n}=\left(\begin{matrix}Basic&Prem+Capped&Loss_{n}\cdot Loss&Conversion&Factor\end{matrix}\right)\cdot TaxMultiplier$$

Basic Premium (BP) - Covers company expenses, the insurance charge for the max/min premium, and the excess loss charge for a per-accident loss limit Capped Losses $\mathrm{'CL}_{\mathrm{n.}}$ )-Losses that contribute to additional premium 0Losses are capped to a min/max corresponding with a min/max premium for the policy and individual claims may be capped as well. Loss Conversion Factor (LCF) Covers loss adjustment expenses ·Tax Multiplier (TM)-Covers state premium taxes and other state assessments

## Fitzgibbon Method

The idea of the Fitzgibbon method is that the retro formula is essentially a linear equation and instead of matching the individual policy retro rating parameters to the individual loss experience, we can run a linear regression to get the average retro rating parameters for the linear equation.

---

The Fitzgibbon method, the way Feldblum shows it,uses this approach

![](https://storage.simpletex.cn/view/fQh49Yh36TlMurZcySLUaeKGT0XnhHnc2)
$B=$ Premium Responsiveness

Fitzgibbon estimates the parameters for the model, A and B, using a linear regression of retrospective adjustments for mature policies against the standard loss ratios for those policies

### Reasons why the slope ( doesnt equal 1

Losses over theloss limit or beyond the max premium don't increase the retrospective premium

·The minimum premium is greater than the basic premium for some plans ·The loss conversion factor (LCF) and tax multiplier (TM) change the slope

### Disadvantages of the Fitzqibbon method

Instead of looking at future premium adjustments for expected future losses (which is what the PDLD method does),Fitzgibbon calculates the ultimate premium estimate based off of cumulative loss-to-date.This is a problem if the premium-to-date is less than what's expected based on current losses-to-date. Because of the loss limits and max/min retrospective premiums,we expect premium sensitivity (the slope, $B)$ to decrease formore mature losses and higher overall loss ratios,but the Fitzgibbor method has a constant slope

## Example 1

A=1,000 Losses at 36 months are 1,000 ·B=1.2 ·Expected Ultimate Loss is 5,000

Calculate the future premium based on the following values of retrospective premium as of 36 months

· $\mathrm{Prem}_{36}=2,200$ (Expected retro premium for $\mathrm{Loss}_{36}=1,000]$ . $\mathrm{Prem}_{36}=1,500$

# Solution

$$EstUltPrem=1,000+1.2\times5,000=7,000$$

| Retro Premium       | Premium at 36 Months | Est. Ult Premium | Future Premium |
| ------------------- | -------------------- | ---------------- | -------------- |
| Expected            | 2,200                | 7,000            | 4,800          |
| Lower-than-Expected | 1,500                | 7,000            | 5,500          |

Using the Fitzgibbon method, the estimated ultimate premium only depends on the overall ultimate loss estimate. If the premium responsiveness is less-than-expected for losses-to-date (the second situation), the estimated future premium will increase so that the overall estimated ultimate premium stays the same

---

## Teng and Perkins PDLD Method

The PDLD method is a bit like the BF method. It focuses on future premiums based on future expected losses, independent of prior experience

## Advantages of the PDLD Method

It's directly modeled on the retrospective rating formula, so it's easily explainable ·Its focus on premium sensitivity is similar to how loss sensitive contracts are handled under Risk Based Capital ●May be useful when changes to retro rating parameters distorts indications from other methods

### Reasons to use the PDLD Method Instead of the Chain Ladder Method

·Timeliness -We can estimate ultimate loss sooner than we can estimate retrospective premiums. Also, we can update the premium asset estimate quarterly with the PDLD method. Retrospective premiums depend on incurred losses

### Teng and Perkins PDLD Assumptions

Premium responsiveness for future adjustments is independent of premium responsiveness of past adjustments.

The slope of the line segment (premium responsiveness for an adjustment period) is independent of the beginning loss ratio and or the beginning retro premium ratio.

### Reasons It's Difficult to Use Retro Rating Parameters from Pricinq

Different insureds have policies with different retro rating parameters (e.g. a policy for a small insured may have a lower max premium than a large insured Premium taxes differ between states Basic premium may vary over time

## General Rule for Premium Responsiveness

·Premium responsiveness decreases as a book of business matures. (larger $0\%$ of losses are excluded due to loss limits and max premium Premium responsiveness decreases for higher overall loss ratios. (policies are more likely to have hit max premium)

---

## Premium Development to Loss Development (PDLD) Ratios

Method 1-PDLD Ratios based on the Retro Formula

Advantages of the RetroFormula Method Disadvantages of the Retro Formula Method ·Responds to changes in the retro rating·Must select retro rating parameters, which can parameters for sold policies be difficult because parameters will vary between policies sold (Teng recommends using the average of the sold parameters)

If the retro rating parameters change significantly over time, PDLD ratios from the retro formula method should be given more weight than PDLD ratios based on historical data.The retro formula can directly reflect those changes.

### Method 2-PDLD Ratios based on Historical Data

For this method, we use booked premium and reported loss development to calculate the PDLD ratios. Data should be partitioned to homogenous groups based on account size and type of rating plan. Policies are grouped by effective date, so data is based on policy effective quarter (not accident year).

Premium for a retro-rated policy is evaluated at each“retro adjustment period." The first retro adjustment typically uses losses at 18 months development. Then, retro adjustments occur every 12 months after that. Premiums are assumed to be booked 3 to 9 months after the losses used to calculate the premium for the retro adjustment.

### Reviewing PDLD Ratios

·Look for trends in the historical PDLD ratios by policy quarter.An upward trend could indicate

0More “liberal"” rating parameters that increase the capped losses and therefore increase premium (e.g. higher maximum premium or per-accident limit). OBetter loss experience, causing more of the losses to be within the capped limits.

Historical PDLD ratios may be volatile after the first retro adjustment because incremental premium development may reflect incremental loss development on only a small number of policies.

It's possible to see negative incremental historical PDLD ratios when loss development is positive.

OThere could be upward development on a claim that already passed the per-accident limit (no change in premium) while other losses within the limits fall (causing premium to fall).

Compare the average of many quarters of the historical PDLD ratios toPDLD ratios from the retroformula to select aPDLD ratio.

PDLD ratios for the first adjustment are typically greater than 1 because of theBasicPremium and because few losses are capped.

---

PDLD ratios should generally fall for more mature retro adjustments because more losses will be capped.

### Reasons Historical PDLD Ratios may differ from the Retro Formula PDLD Ratios

Worse (or better) than expected loss experience can cause more (or less) losses to be capped resulting in historical PDLD ratios that are smaller (or larger) than the retro formula PDLD ratios. ·Average retro rating parameters may change over time.

### Loss Capping Ratios

The loss capping ratio typically decreases as losses mature since more losses are outside the loss limits (aggregate limits for min/max premium and per-accident limits).

For the exam, it's important to know the difference between incremental and cumulative loss capping ratios. The retro formula uses incrementa/loss capping ratios so if the problem gives you cumulative loss capping ratios,you need to adjust them to incremental ones first.Ifit'sunclear,make sure to state your assumption

Incremental Loss Capping Ratios

Cumulative Loss Capping Ratios

$$\frac{CL_n}{L_n}=\frac{Capped\:Loss_n}{Loss_n}\frac{\Delta CL_n}{\Delta L_n}=\frac{Capped\:Loss_n-Capped\:Loss_{n-1}}{Loss_n-Loss_{n-1}}$$

If you're given cumulative loss capping ratios, you can convert to incremental loss capping ratios. The formula is shown in section 5,which is off the syllabus,but also shows up in exhibit 5 in the appendices.I think it still could be testable and a few past CAS problems are conflicting regarding incremental vs. cumulative loss capping ratios, so it's a good idea to be prepared for it.

![](https://storage.simpletex.cn/view/fQViXlBUPGO6RrzHuoTvLSu2GWw0tVqZp)

## Cumulative Premium Development to Loss Development (CPDLD) Ratios

Remember that CPDLDratios relate toPDLD ratios the same way that CDFsrelate toLDFs for the chain ladder method

The goal of the CPDLD ratios is to estimate the total expected future premium development for a policy effective year by multiplying the CPDLD by the expected future loss.

### Premium Asset

It's important to remember that the premium asset is calculated as the difference between ultimate premium and current bookedpremium,NOT premium booked at the prior adjustment.This is because there willbe some differences between the booked premium at the evaluation date of the analysis and the premium booked at the prior adjustment period.

---

We should also consider the collectability of the premium asset (similar to recovery risk in Marshall) due to the possibility that the insured won’t pay future premium development.

## Enhanced PDLD Method - PDLD with a constant

$\mathrm{CPDLD}_{1}$ in the Teng and Perkins PDLD method includes both the impact of losses on the retro premium and the basic premium. One of the advantages of the Fitzgibbon method is that the basic premium portion was broken out and reflected as a fixed amount.

Feldblum proposes an enhancement to the PDLD method by removing the basic premium portion from the $\mathrm{CPDLD}_{1}$ This way, the adjusted CPDL$D_{1}$ only reflects future premium development due to future loss development and the basic premium is added afterwards as a fixed amount.

## Recipes for Calculation Problems

PDLD Ratios - Retro Formula PDLD Ratios -Empirical ·Premium Asset Cumulative to Incremental Loss Capping Ratios Fitzgibbon Method Premium Asset -PDLD Method Enhancement

---

## Stochastic Loss Reserving Using Bayesian MCMC Models

### Overview

The main goal of this paper is to retrospectively test out different Bayesian MCMC models and see which models perform best.

For each model (e.g. Mack Model), Meyers takes 200 historical loss triangles that have already developed to ultimate (or rather, to the end of the 10-year development window).For each loss triangle,Meyers uses the model to calculate a predicted distribution of ultimate losses. Then, he looks at the percentile of where the actua/ultimate loss falls within the predicted distribution.This is done for each of the 200 historical loss triangles.

Meyers tries to validate the different models by seeing if the percentiles of the actual observations on the model distributions are consistent with those expected.The model is validated if the observed percentiles appear to be uniformly distributed.

## Tests to Validate Models

We can test the validity of a model by seeing if the percentiles of the actual outcomes within the predicted distributions are uniform for a large number of datasets (Meyers uses 200). To do this, use a combination of the following three tests to see if the percentiles are reasonably uniform

## Histogram and p-p Plot of Outcome Percentiles.

If the model validates and the percentiles are uniformly distributed,we should see:

·Histogram -Bars of equal height

· $P-P$ Plot - Sorted predicted percentiles (percentile of actual outcome within the predicted distribution) should follow the expected percentiles along a $45^{\circ}$ line

### Kolmogoroy-Smirnoy Test

The K-S test compares the maximum distance between the predicted percentiles and the expected percentiles (the K-S statistic) to a threshold. If the K-S statistic is greater than the threshold, then the test fails and we reject the null hypothesis that the percentiles are uniformly distributed.

Visually, the K-S bands (indicating the threshold) can be plotted on a $p-p$ plot and if any of the points fall outside the bands,then the test fails.

## Non-Bayesian Model Results

## Mack Model (Incurred Losses)

Histogram shows more high/low percentiles than expected . $p-p$ plot shows a slanted “S" curve and the K-S test fails at the $5\%$ level for allines combined

---

Conclusion: The Mack model is too light in the tails (it underestimates the variability of ultimate loss estimates)

### Mack Model (Paid Losses

·Histogram and $p^{-}p$ plot shows more low percentiles than expected ·K-S test fails at the 596 level for all lines combined

Conclusion:The Mack model on paid losses is biased high(expected loss estimates are too high）

### Bootstrap ODP Model (Paid Losses

·Histogram and $P-p$ plot show more low percentiles than expected ·K-S test fails at the 596 level for all lines combined

Conclusion: The ODP Bootstrap model is biased high (expected loss estimates are too high)

## Bayesian Incurred Loss Models

Ways to improve the recognition of variability in the predictive distributior

·The Mack model multiplies LDFs by a fixedlevel parameter, the cumulative loss on the diagonal OWe can increase model variability by treating the level of the accident year as random The Mack model assumes independence between accident years OIncrease model variability by allowing correlation between accident years (CCL model)

Leveled Chain Ladder (LCL)

### Key improvement over Mack LCL uses random level parameters for each accident year (the Mack model uses fixed losses-to-date)

$$\begin{aligned}&\mu_{\omega,d}=\alpha_{\omega}+\beta_{d}\\&Loss_{\omega,d}^{sim}\sim\mathrm{lognormal}\left(\mu_{\omega,d},\sigma_{d}\right)\end{aligned}$$

Correlated Chain Ladder (CCL)

### Key improvement over LCL: CCL allows for correlation between accident years.

$$
\begin{aligned}
&\mu_{1,d}=\alpha_{1}+\beta_{d} \\
&\mu_{\omega,d}=\alpha_{\omega}+\beta_{d}+\rho\Big(\ln\Big(C_{\omega-1,d}\Big)-\mu_{\omega-1,d}\Big)\quad\mathrm{for}\:w>1 \\
&Loss_{\omega,d}^{sin}\sim\mathrm{lognormal}(\mu_{\omega,d},\sigma_{d})
\end{aligned}
$$

For both the CCL and LCL models, we can incorporate expert opinion by setting more restrictive prior distributions for $\alpha_{w}$ and logelr , similarly to how expert opinion is incorporated in Verrall.

---

Results

BothLCL and CCL models produce higher standard deviations of predicted outputs thanMack

### LCL Model

Histogram and $p-p$ plot shows more high/low percentiles than expected ·K-S test fails at the 596 level for all lines combined ·Conclusion: The LCL model is too light in the tails (but is better than Mack)

### CCL Model

.Correlation parameter, $\rho$ ,is generally positive, resulting in higher prediction variance than LCL Histogram and $p-p$ plot shows slightly more high/low percentiles than expected ·K-S test passes at the $5\%$ level for all lines combined Conclusion: The CCL model is validated (but has mildly thin tails)

### Bayesian Paid Loss Models

Correlated Incremental Trend (CIT)

### Key improvement:

CIT includes a calendar-year trend for incremental paid losses CIT allows for correlationbetween accident vears (similar to CCL）

$$
\begin{aligned}
&\mu_{\omega,d}=\alpha_{\omega}+\beta_{d}+\tau(w+d-1) \\
&Z_{_{w,d}}\sim\mathrm{lognormal}(\mu_{_{w,d}},\sigma_{_d}) \\
&IncLoss_{1,d}^{sim}\sim\mathrm{normal}\big(Z_{1,d},\delta\big) \\
&IncLoss_{\omega,d}^{sim}\sim\mathrm{normal}\Big(Z_{\omega,d}+\rho\cdot\Big(IncLoss_{\omega-1,d}^{sim}-Z_{\omega-1,d}\Big)\cdot e^{\tau},\delta\Big)& \mathrm{for}\:w>1
\end{aligned}
$$

### Differences from the CCL model:.

· $\sigma_{d}$ oCCL model is for cumulative losses, so $\sigma_{d}$ decreases for older development periods. oCIT model is for incremental losses, so $\sigma_{d}$ increases.

Autocorrelation oCCL:Autocorrelation is between the log of cumulative losses oCIT: Autocorrelation is in the process variance step, not in calculation of log mean, $\mu_{w,d}$ because of the potential for negative incremental losses. .Trend

---

oCCL:No trend oCIT: Trend factor is included in the calculation of the log mean, $\mu_{w,d}$ , and also included in the autocorrelation piece

### Changing Settlement Rate (CsR

## Key improvement:

CSRparameter reflects changes to the claims settlement rate (faster payment pattern)

·Note: There's no autocorrelation or trend terms

$$
\begin{aligned}
&\mu_{\omega,d}=\alpha_{\omega}+\beta_{d}\cdot\left(1-\gamma\right)^{\omega-1} \\
&Loss_{_{w,d}}^{sim}\sim\mathrm{lognormal}(\mu_{_{w,d}},\sigma_{_d})
\end{aligned}
$$

### Results

### CCL Model

·Histogram and $p-p$ plot shows more low percentiles than expected ·K-S test fails at the 596 level for allines combined ·Conclusion: The CCL model is biased high on paid losses (expected loss estimates are too high)

### CIT Model

.Correlation parameter, $\rho$ ,is generally close to zero :Trend parameter, $\tau$ , is predominantly negative, mostly offset by increases to $\alpha_{\mathrm{u}}$ and $\beta_{d}$ ·Histogram and $p-p$ plot shows more low percentiles than expected ·K-S test fails at the 596 level for all lines combined ·Conclusion: The CIT model is biased high on paid losses (expected loss estimates are too high)

LIT Model (same as CIT model, but correlation parameter set to zero)

Histogram and $p-p$ plot shows more low percentiles than expected ·K-S test fails at the 596 level for all lines combined ·Conclusion: The LIT model is biased high on paid losses (expected loss estimates are too high)

### CSR Model

Settlement rate parameter, Y , is generally positive, reflecting a speedup in the payment pattern Histogram and $p-p$ plot shows that the CSR model corrects the bias in the other models ·K-S test passes at the $5\%$ level for all lines combined Conclusion: The CSR model is validated

---

## Process Risk, Parameter Risk and Model Risk

$$\mathrm{Var}(X)=\mathrm{E}_{\theta}\Big[\mathrm{Var}\Big[X\:|\:\theta\Big]\Big]+\mathrm{Var}_{\theta}\Big[\mathrm{E}\Big[X\:|\:\theta\Big]\Big]\quad Total\:Risk=Process\:Risk+Paramet$$

Process Risk - Average variance of outcomes from the expected result

Parameter Risk - Variance due to the uncertainty in the parameters, reflected in the posterior distributions of the parameters

Model Risk - Risk that we didn't select the "correct" model (not explored directly in Meyers)

### Important observations:

The results in Meyers show that the parameter risk represents the overwhelming majority of the total risk for the loss datasets.

Model risk can be addressed by weighing together multiple reasonable models where the weights are additional parameters (Verrall reflects model risk by weighing together reasonable models

## Summary of Model Results

### Incurred Data

Mack model understates the variability of ultimate losses, particularly because it assumes independence between accident years, CCL predicts reasonable distributions of outcomes

## Paid Data

·Bootstrap ODP, Mack and CCL models predict ultimate losses that are biased high.

·LIT and CIT allow for a calendar year trend (and correlation in CIT), but are also biased high

CSR model corrects for the bias and predicts reasonable distributions of outcomes

## Summary of Model Results

·p-p Plots & Histogram Interpret p-p Plots

Kolmogorov -Smirnov (K-S) Test Correlated Chain-Ladder (CCL) Model Changing Settlement Rate (CSR Model

---

## Stochastic Loss Reserving Using GLMs

# Key Points

The Taylor paper ties in closely with the Mack (1994), Venter Factors and Shapland papers. I think the most testableinformation comes from the Chapter 3.Iwould particularly focus on the Mack and CrossClassified models,Taylor's three theorems relating the models to the chain ladder method and the GLM representation of the ODP Mack and ODP Cross-Classified models. Chapter 2 also seems fairly testable for a question about GLMs in general, model validation or some of the various formulas.

## Exponential Dispersion Family (EDF)

GLMs assume observations Ycome from the exponential dispersion family. The Tweedie sub-family (and more specifically the Over-Dispersed Poisson sub-family) are the most important ones for this paper

### Tweedie Sub-Family

The Tweedie distribution is defined as an EDF with the following expected value and variance. The table includes the most important forms of the Tweedie sub-family that you should be familiar with:

| Distribution     | $p$ | $\mu$                      |
| ---------------- | --- | -------------------------- |
| Normal           | 0   | $\theta$                   |
| ODP              | 1   | $e^{\theta}$               |
| Gamma            | 2   | $\frac{1}{\theta}$         |
| Inverse Gaussian | 3   | $(-2\theta)^{\frac{1}{2}}$ |

$$\begin{aligned}&V(\mu)=\mu^{p}\quad p\leq0\quad\mathrm{or}\quad p\geq1\\&\boxed{\operatorname{E}[Y]=\mu=\left[\left(1-p\right)\theta\right]^{\frac{1}{1-p}}}\quad\mathrm{for}\:p\neq1\\&\boxed{\operatorname{Var}[Y]=\phi\cdot\mu^{p}}\end{aligned}$$
ODP Distribution
![](https://storage.simpletex.cn/view/f1M2STs4uwoH0TXtAuICdsH8wYp8rFB1O)

## GLMs

Definition

To specify a GLM, you need to select

·Error distribution (one of the EDF distributions),including index p Explanatory variables, xs Link function he.g. identity link log-link

The GLM is a regression model and using the specification of the model and the data (observations and explanatory variables), the GLM will find the MLE of the $\beta$ parameters

---

$$\begin{aligned}&\bullet Y_{i}\sim EDF\left(\mu_{i},\phi_{i}\right)\\&\bullet\:b(\mu_{i})=x_{i}^{T}\beta=x_{i1}\beta_{1}+\cdots+x_{in}\beta_{n}\quad or\quad\mu=b^{-1}(X\cdot\beta)\\&\bullet\phi_{i}=\frac{\phi}{w_{i}}\quad w_{i}=weight_{i}\end{aligned}$$

### Covariates: Covariates are the set of predictors or variables and can be continuous or categorical.

·Development year should be used as a categoricalvariate

# Goodness of fit and Deviance

$$\begin{aligned}\mathrm{of}\:\mu:&\hat{Y}=b^{-1}\left(X\hat{\beta}\right)\\&D^{*}\left(Y,\hat{Y}\right)=2\left(loglikelibood_{Saturated}-loglikelibood_{Model}\right)\end{aligned}$$
Deviance

The saturated modelhas a parameterfor each observation so the modelcompletely fits the observations

Residuals and Model Validation

### Standardized Pearson residuals:

$R^p = \frac{Y - Y'}{\dot{\sigma}_t}$

### Model Validation

Check different residual plots against each variable (e.g. driver age or development period) to validate the model assumptions.

Standardized Pearson residuals should be random around zero (unbiased) and have uniform dispersion (homoscedasticity)

### Standardized Deviance residuals,

$$R_{i}^{D}=\mathrm{sgn}\Big(Y_{i}-\hat{Y}_{i}\Big)\cdot\sqrt{\frac{d_{i}}{\hat{\phi}}}\quad d_{i}\to\mathrm{Contribution~of~observation~}Y_{i}\mathrm{~to~deviance~}D^{*}\Big(Y,\hat{Y}\Big)\\\mathrm{sgn}(x)\to\mathrm{sign~function~takes~values~-1,~0,~or~1}$$

Standardized Pearson residuals will reproduce any non-normality from the original data (e.g. skewed loss data). The standardized Deviance residuals should be normally distributed, so they're more useful for mode! assessment.

## Outliers and Weights.

## Weights: Variance weights can be used to correct heteroscedasticity. This is similar to how the Shapland Scale

parameter adjustment works.

---

### Outliers: Observations with very large residuals can skew the results towards the outlier.An outlier can be excluded

by setting its weight to zero. Careful consideration should be taken to ensure that it's truly an outlier because removing outliers will limit the variability in the model.

### Mack Models

Non-Parametric Mack Model

### Assumptions:

Accident years are stochastically independent ·For each accident year $k$ the cumulative losses $X_{k,j}$ form a Markov chain ·For each accident year $k$ and development periodj
$$\circ\quad\mathrm{E}\Big[X_{k,j+1}\:|\:X_{k,j}\Big]=f_{j}X_{k,j}\\\circ\quad\mathrm{Var}\Big[X_{k,j+1}\mid X_{k,j}\Big]=\sigma_{j}^{2}X_{k,j}$$

Note that these are essentially the same assumptions as the normal Mack model assumptions. This model is:

Stochastic - Because it considers both the expected value and variance of observations

Non-Parametric - It doesn't consider the distribution (e.g. Gamma) of the observations

### Results of theMackModel

1.The conventional chain ladder LDF estimators, $\hat{f}_{j}$ ,are a.Unbiased b.Minimum variance among estimators that are unbiased linear combinations of the triangle's age-to-age factors, $\hat{f}_{k,j}$ 2. The conventional chain ladder reserve estimator, $\hat{R}_{k}$ , is unbiased

### Parametric Mack Model

### Changed assumptions from above：

$$Y_{_{k,j+1}}\mid X_{_{k,j}}\sim EDF\left(\theta_{_{k,j}},\phi_{_{k,j}};a,b,c\right)$$
·Variance assumption is removed -Variance is driven by the selected EDF distribution

---

### Theorem 1

For losses in an nxn triangle with observations subject to the EDF Mack model assumptions:

a.If the original Mack variance assumption also holds, then the MLEs of the $f_{j}$ parameters are the conventional chain ladder LDF estimators, $\hat{f}_{j}$ , and these are unbiased estimators.

b.If the model is restricted to the ODP Mack model and if the dispersion parameters are just column dependent, $\phi_{k,j}=\phi_{j}$ , then the weighted average chain ladder LDFs, $\hat{f}_{j}$ , are minimum variance unbiased estimators (MVUEs) c.For the same conditions as (b), the cumulative loss estimates, $\hat{X}_{k,j}$ , and reserve estimates, $\hat{R}_k$ , are also MVUEs.

### Implication of Theorem 1: This theorem means that the conventional chain ladder estimates and forecasts are optimal estimators (both

MLE and MVUEs). This is a stronger implication than the original Mack model since it shows that the conventional chain ladder LDF estimators, $\hat{f}_{j}$ , are minimum variance for all unbiased estimators, not just of the linear combinations of the age-to-age factors.

### Cross-Classified Models

Cross-Classified Model

### Assumptions:

·The random variables $Y_{k,j}$ are stochastically independent

·For each accident year $k$ and development period 。$Y_{k,j}\sim EDF\big(\theta_{k,j},\phi_{k,j};a,b,c\big)$ 。$\operatorname{E}\biggl[Y_{k,j}\biggr]=\alpha_{k}\beta_{j}$ o∑β,=1

## Theorem 2

For losses in an nxn triangle with observations subject to the ODP Cross-Classified model assumptions and the following assumptions:

· $Y_{k,j}$ is restricted to an ODP distribution

·The dispersion parameters are identical for all cells: $\phi_{k,j}=\phi$

Then the MLE fitted values $\hat{Y}_{k,j}$ are the same as those from the conventional chain ladder method.

### Theorem 3

If the Theorem 2 assumptions hold and the fitted values $\hat{Y}_{k,j}$ and reserve estimates $\hat{R}_k$ are corrected for bias, then they are MVUEs of $Y_{k,j}$ and $R_{k}$

---

These two theorems are similar to Theorem1 about the ODP Mack model and mean that:

1.Forecasts from the ODP Mack and ODP Cross-Classified models are identical and the same as those from the chain ladder method despite the different formulations.

2.We can get forecasts for the ODP Cross-Classified model without considering the model directly and working as if the model was an ODP Mack model.

### GLM Representation of Chain Ladder Models

ODP Mack Model GLM

To represent the ODP Mack Model as a GLM, we model the triangle's age-to-age factors, $\hat{f}_{k,j}$

$$age-to-age_{k,j}=\frac{CumLoss_{AY,d+1}}{CumLoss_{AY,d}}$$

![](https://storage.simpletex.cn/view/fC4epcxy02dADDdSpcULn7WExt4qAriHE)

$$\mathbf{X}=\left(\begin{array}{ccc}1&0&0\\\\0&1&0\\\\0&0&1\\\\1&0&0\\\\0&1&0\\\\1&0&0\end{array}\right)\quad\beta=\left[\begin{array}{c}f_1-1\\\\f_2-1\\\\f_3-1\end{array}\right]$$

$$
\begin{aligned}
&\boxed{w_{k,j}=X_{k,j}} \\
&weight_{AY,dev}=CumLoss_{AY,dev}
\end{aligned}
$$

中$\hat{f}_{2,1}-1$ $\hat{f}_{1,3}-1$ $\hat{f}_{1,2}-1$
$$\mu=h^{-1}(\mathrm{X}\beta)$$
$b=$ identity function

$$\hat{f}_{k,j}-1\mid X_{k,j}\sim ODP\Bigg(f_{j}-1,\frac{\phi_{j}}{X_{k,j}}\Bigg)$$

The output of the GLM will be the best-fit parameter estimates of the development factors, $f_{j}-1$

---

### ODP Cross-Classified Model GLM

![](https://storage.simpletex.cn/view/ff5D5HKboxhzmWNyPiHYP81e0ODgfi0OH)

$$
\begin{aligned}
&\mu_{k,j}=\exp\Bigl(\ln\alpha_{k}+\ln\beta_{j}\Bigr) \\
&b=\log\operatorname*{lim}\mathrm{function} \\
&Y_{k,j}\sim ODP\big(\mu_{k,j},\phi\big)
\end{aligned}
$$

Reliance on Recent Experience Years

Like normal reserving, we may only want to use the latest m experience years in the model. To do this, we simply set the weight of the observations before the latest $m$ experience years to zero in the model.

## Recipes for Calculation Problems

ODP Cross-Classified Model Parameters GLM Representation of Chain Ladder Modelg Re-Normalizing ODP Cross-Classified Parameter

---

## Predictive Distributions for Reserves which Incorporate Expert Opinion

### Overview

In traditional loss reserving with deterministic methods, it's common to select LDFs or select an expected loss ratio for theBF method.These are ways to incorporate expert opinion.However,if we want to calculate a reserve range using a traditional bootstrap model or Mack model, making LDF selections may compromise some of the model assumptions.

A key benefit of using a Bayesian approach (compared to a Mack or bootstrap model) is that we can naturally incorporate expert opinion within a stochastic model and get a reserve range without compromising the underlying assumptions.

Examples of when to incorporate expert knowledge or opinion.

·Change in payment pattern due to a change in company policy

Change in benefits due to newlaws,requiring adjustment to LDFs

### Areas where expert knowledge might be used

Selecting LDFs for the chain ladder method OOverriding LDFs in a particular row (accident year) OUsing only n-years to estimate the LDFs

·Selecting expected loss for the BF method

## Different Stochastic Models for Chain Ladder.

Each of the models below give the same reserve result as the chain ladder method,but they differ in form and may have different variances.

### Mack Model

$\mathbb{E}\left[D_{i,j}\right]=\lambda_j\cdot D_{i,j-1}$

$\text{Var}\left(D_{i,j}\right)=\sigma^2_j\cdot D_{i,j-1}$

$$
\begin{gathered}
\operatorname{E}\bigg[\:Loss_{AY,k}\bigg]\:=\:LDF_{k}\cdot Loss_{AY,k-1} \\
\mathrm{Var}\left(Loss_{AY,k}\right)=\sigma_{j}^{2}\cdot Loss_{AY,k-1}
\end{gathered}
$$

## Advantages:

·Easy to implement - Parameter estimates and prediction errors can be calculated in a spreadsheet.

### Disadvantages

There is no predictive distribution, because a distribution isn't specified.

---

·Need to estimate separate parameters, $\sigma_{j}^{2}$ , for the variance apart from the LDFs.

### Over-Dispersed Poisson Models

## GLM approach(similar to Shapland GLM Bootstrap)

$\mathbb{E}\left[C_{i,j,t}\right]=m_{ij}=e^{\epsilon\alpha_i\alpha_j}$

$$\mathrm{E}\Big[IncLoss_{_{AY,k}}\Big]=e^{c+\alpha_{i}+\beta_{j}}$$

### Row-Column Form:

and $\sum y_{j}=1$

$E[C_{ij}] = x,y$

E[IncLossg= Row FactoryCol Factor

$X_i-$ Expected ultimate loss for accident year $i$up to thelast development period of the triangle $y_{j}-96$ % 96 of ultimate loss emerging in development period

## Advantages:

·Doesn’t necessarily break down if there are some negative incremental values.

·It gives the same reserve estimate as the chain ladder method

·It's more stable than the log-normal model of Kremer.

## Disadvantages:

Connection to the chain ladder method is not immediately apparent.

### Over-Dispersed Negative Binomia

This model differs in form from the ODP model, but produces the same predictive distribution

$\mathbb{E}\left[C_{i,j}\right]=\left(\lambda_j-1\right)D_{i,j-1}$

$\operatorname{Var}\left(C_{i,j}\right)=\varphi\cdot\lambda_j\cdot\left(\lambda_j-1\right)\cdot D_{i,j-1}$

## Advantages:

Doesn't necessarilybreak down if there are some negative incremental values (but the sum of the column needs to be positive)

·It gives the same reserve estimate and has the same form as the chain laddermethod

## Disadvantages:

Column sums of incremental losses must be positive (or variance would be negative)

### Normal Distribution

$E[C_{i,j}] = (\lambda_j - 1)D_{j,i-1}$
$$\text{Var}(C_{i,j}) = \varphi_j D_{j,i-1}$$
$$\mathrm{E}\Big[IncLoss_{_{AY,k}}\Big]=\Big(LDF_{_k}-1\Big)\cdot Loss_{_{AY,k-1}}$$

$$\mathrm{Var}\Big(IncLoss_{AY,k}\Big)=dispersion_{k}\cdot Loss_{AY,k-1}$$

---

## Advantages:

:Can handle negative incremental losses

### Disadvantages:

·Need to estimate separate parameters, $\varphi_{j}$ , for the variance apart from the LDFs.

## Prediction Error

Given loss data,we can use one of the models above to create a distribution of future losses.The expected value of the distribution is our prediction, the central estimate. The root mean square error (RMSEP) is the prediction error, incorporating both process variance and parameter (estimation) variance.

$$\boxed{prediction\:variance=process\:variance+estimation\:variance}$$

### Prediction Error vs.Standard Error

Prediction error accounts for uncertainty in the parameter estimation (estimation variance) and the variability of future losses (process variance). Standard error only accounts for estimation variance.

$$predictionerror=\sqrt{process\:variance+estimation\:variance}standard\:error=\sqrt{estimation\:variance}$$

## Incorporating Expert Opinion in Chain Ladder.

The over-dispersed negative binomial model can allow for a separate LDF parameter for each accident year and development period. This flexibility allows us to incorporate expert opinion in selecting LDFs.

### Incorporating Expert Opinion to Override Specific LDFs

·For each LDF parameter that is selected, specify the prior distribution of $\lambda_{i,j}$
$$\mathrm{E}\Big[\lambda_{i,j}\Big]=LDF^{selection}\quad\mathrm{Var}\Big(\lambda_{i,j}\Big)-\mathrm{set~to~be~relatively~small}$$

·Group the other LDF parameters by development period to reflect the chain ladder method,by setting $\lambda_{i,j}=\lambda_{j}$ and using a large variance for the prior distribution.

### Incorporating Expert Opinion to Use n-year LDFs

for the mostrecent n calendar year diagonals
$$\lambda_{i,j}=\lambda_{j}\\\lambda_{i,j}=\lambda_{j}^{*}$$
for all diagonals prior to the latest ndiagonals

Set the prior distributions of the LDF estimates $\lambda_{j}$ and $\lambda_{j}^{*}$ with large variances so that they're estimated from the data.

### How Variance of the Prior Distribution Impacts the Model Result

·“Vague” priors (large variance)-Result is close to what the data estimates (chain ladder method) “Strong”priors (small variance)-Result is drawn toward the mean of the prior distribution

---

## Bayesian Model for Bornhuetter-Ferguson

The Bayesian model of the BF method isbased on the over-dispersed Poisson distribution (row-col form) For the BFmodel, select the expected ultimate loss by accident year by setting a prior distribution for each of the row parameters, $X_{i}.$

![](https://storage.simpletex.cn/view/fTGQhStTqCsMVGQlslxgXFS5L9GWixKeE)

Credibility-Weighted Bayesian Model for the BF Method

TheBayesian model is a credibility model between the chain ladder and Bornhuetter-Ferguson methods. We can adjust the credibility by changing $\beta_{i}$

:Increasing $\beta_{i}$ causes the variance of the prior distribution to decrease (indicating higher confidence in the selected ultimate loss) This causes $Z_{i,j}$ to decrease placing more weight on the BF method

$$
\begin{gathered}
\operatorname{E}\left[C_{i,j}^{cL}\right]=\left(\lambda_{j}-1\right)\cdot D_{i,j-1} \operatorname{E}\bigg[C_{i,j}^{BF}\bigg]\:=\:M_{i}\cdot96IncPaid_{j} \\
Z_{i,j}=\frac{p_{j-1}}{\beta_{i}\cdot\varphi+p_{j-1}} \\
\operatorname{E}\bigg[C_{i,j}^{\sigma\alpha d}\bigg]=Z_{i,j}\cdot\operatorname{E}\bigg[C_{i,j}^{CL}\bigg]+(1-Z_{i,j})\cdot\operatorname{E}\bigg[C_{i,j}^{BF}\bigg]
\end{gathered}
$$

Fully Stochastic Bayesian Model for the BF Method

The model above is stochastic in the row parameters, $X_{j}$, but uses the fixed LDFs directly

The fully stochastic model uses an improper gamma prior distribution for the column parameters and the prior distribution shown above for the row parameters, $X_{i}.$ The goal here is to have a model that is fully stochastic in both row and column parameters.

### How Variance of the Prior Distribution Impacts the Model Results

Vaguepriors for $X_{j}$ (large variance)-Result is close to the chain ladder method "Strong" priors for $X_{i}$ (small variance) - Result is close to the Bornhuetter-Ferguson method

The flexibility of the fully stochastic modelmeans we can replicate the chain ladder method,the BFmethod or a weighting between the two methods by adjusting the variance of the prior distributions of the row parameters.

### Advantage of a Stochastic Approach

We can produce thefull predictive distribution of the reserve,not just the point estimate or the mean and standard deviation

---

## Recipes for Calculation Problems

Incorporating Expert Opinion: Chain Ladder Bayesian Moade fortheBE Methode Estimated Reserve from Fully Stochastic BF

---

## A Framework for Assessing Risk Margins

### Overview

The main goal of the Marshall paper is to answer the question of how to set an appropriate risk margin for insurance liabilities.For this paper, make sure to focus on the sources of uncertainty (independent risk and internal/external systemic risk). Also, make sure you thoroughly understand the risk margin calculation and the different types of additional analyses.

# Preparing the Claims Portfolio

Splitting the Claims Portfolio to Valuation Classes

It's preferable to split the claims portfoliointo the same valuation classes that are used in the reserve analysis to determine central estimates.

Splitting Valuations Classes to Claims Groups

There should be homogeneity within a claims group and different behavior between claims groups (e.g. split the Home portfoliobetween CAT and non-CAT claims)

## Sources of Uncertainty

Independent Risk - Risks arising from randomness inherent in the insurance process

Systemic Risk -Risks that are potentially common across valuation classes or claims groups

:Internal Systemic Risk - Uncertainty because the valuation models are imperfect representations of the insurance process. These are risks internal to the liability valuation process. ·External Systemic Risk -Risks external to the liability valuation process

### Sources of Independent Risk

·Random component of parameter risk -Uncertainty in selecting appropriate parameters due to the randomness of insurance. Random component of process risk-Pure effect of randomness due to the insurance process

Sources of Internal Systemic Risk

Specification Error -Error from the inability to make a model that fully represents the insurance process

Parameter Selection Error - Error that we can't adequately measure all the predictors (parameters) of claim cost outcomes and their trends

Data Error -Error due to poor or unavailable data that's needed for the reserve analysis

### Sources of External Systemic Risk

Economic and Social Risks -Normal inflation and social/environmental trends

---

Legislative, Political and Claims Inflation Risk - Changes to the legislative or political environment affecting claims valuation portfolios and changes to claims settlement levels Claim Management Process Change Risk-Changes in the claims department that impact reporting/payment patterns or the estimating of case reserves Expense Risk - Uncertainty in expenses for managing the liabilities Event Risk (Catastrophes) - Uncertainty from losses due to natural or man-made catastrophes ·Latent Claim Risk - Uncertainty from losses that may arise in the future from a source that's not considered covered (e.g. asbestos) Recovery Risk - Uncertainty in reinsurance (or non-reinsurance) recoveries

### Quantitative vs.Qualitative Analysis

Quantitative analysis can only reflect uncertainty in historical experience and can't adequately reflect all possible sources of future uncertainty ·We also need qualitative analysis (judgment) to make sure we reflect all sources of uncertainty

Quantitative modeling work best to analyze sources of independent risk and past episodes of external systemic risk. Quantitative modeling needs to be supplemented with other quantitative and qualitative analyses to reflect internal systemic risk and future external systemic risk that differs from the past

### Correlation Effects

Correlation for Independent Risks

Independent risks are uncorrelated with other sources of uncertainty both within and between valuation classes.

### Correlation for Internal Systemic Risks

Uncorrelated with independent risk and external systemic risk sources ·Correlated between classes or between outstanding claim and premium liabilities due to: OSame actuary effect - Effect of common valuation approaches for different valuation classes OLink between premium liability methodology and outcomes from outstanding claim. valuation

Correlation for External Systemic Risks

Uncorrelated with independent, internal systemic risk and generally uncorrelated with other. external systemic risk categories (e.g. event risk is uncorrelated with economic/social risk) Correlated between classes or between outstanding claim and premium liabilities in the same risk category “It is possible that external systemic risk categories may be partially correlated either within or between valuation classes

---

### Quantitative Methods for Assessing Correlation

Quantitative techniques are complex and require lots of data - time and effort outweigh benefits Correlations would be driven by past correlations, but correlations for external systemic risk sources may be different than past episodes. ·It's difficult to separate past correlations between independent and systemic risks. Internal systemic risk can't be modeled with standard correlation techniques ·Results are unlikely to be aligned with the framework (split between independent and internal/external systemic risk

## Risk Margin Calculation.

To calculate the risk margin,we calculate the CoVs separately for independent risk,internal systemic risk and external systemic risk. Then, we consolidate the CoVs assuming independence between the sources of risk and calculate the risk margin (assuming the normal or lognormal distribution)

## Additional Analysis

Sensitivity Testing

Goal:

Gain insights about the sensitivity of the final risk margin to key assumptions.

Do this by varying each key assumption (the CoVs and correlations) and monitor the impact on the risk margin.Review key assumptions that have significant impact on the risk margin.

## Scenario Testing

Goal:

Tie the risk margin to a set of valuation outcomes. We adjust the assumptions used for the central estimate in order to align the central estimate with the assessed provisions including the risk margin

Scenario testing asks the question: What scenario (e.g.higher frequency or severity) would result in the central estimate increasing to the current central estimate plus the risk margin?

### Internal Benchmarking

Goal: Compare the proposed CoVs to one another to check for internal consistency and reasonableness.

### Independent Risk CoV Selection:

Portfolio size: Larger portfolios have lower Co Vs due to lower volatility from random effects ·Length of Claim Runoff: Longer tailed lines have higher CoVs due to more time for random effects to have an impact

Implications:

Long-tailed portfolios: Premium Liability CoV should be higher than Outstanding Claim CoV

---

## Internal Systemic Risk CoV Selection:

·If template models are used for similar valuation classes,we would expect similar CoVs ·If similar valuation methodology is used on both short and long-tail classes, then we would expect a higher CoV for the long-tail class.

### External Systemic Risk CoV Selection

CoVs should be higher for long-tail portfolios,except for event risk for Property and liability risk forHome

### External Benchmarkinc

Goal:

Compare thereasonableness of CoVs and risk margins to those from external sources

Shouldn't be relied on instead of analysis,but may be useful when there is little information available for analysis, especially for independent risk.

## Hindsight Analysis.

Goal: Compare the past reserve estimates of liabilities against the latest view of the same liabilities to review the

actual volatility in thepast

## Mechanical Hindsight Analysis

3.Apply the chain ladder method to data as of the valuation date to calculate a current unpaic estimate. 4.Iteratively, remove a diagonal of data and apply the same method to calculate unpaid estimates for prior valuation dates. 5.Compare the past estimates to the current estimate for the same accident years.The relevant payments made between the past valuation dates and the current valuation date should be added to the current unpaid estimate.

## Independent Risk Assessment

The goal of the independent risk assessment is to use a model to“fit away” past systemic episodes in order to analyze the residual volatility in order to get the CoVs for independent risk.

### Methods to Analyze Independent Risk

·Mack method (Mack 1994 paper) Bootstrapping (Shapland paper Stochastic Chain Ladder ·GLM techniques

---

:Bayesian techniques (Meyers paper)

## Balanced Scorecard (Internal Systemic Risk Assessment

Goal:Assess the adequacy of the modeling infrastructure and its ability to reflect and predict the underlying insurance process.

## Potential Risk Indicators

Page 33 in the paper has a full list of the potential risk indicators.Below are a few examples

## Specification Error:

·Number of independent models used

·Range of results produced by the models

·Checks made on reasonableness of results

### Parameter Selection Error:

Best predictors have been identified

·Best predictors are stable over time (or change due to process changes) .Value of the predictors used (predictors used are close to the best predictors)

### Data Error

Good knowledge of past processes affecting predictors Extent, timeliness, consistency and reliability of information from business ·There are appropriate reconciliations and quality control for the data

## Reviewing the CoV Scale.

Minimum CoV for best practice is unlikely to be less than $5\%$ Maximum CoV for worst practice could be greater than $20\%$ (e.g. single, aggregated model with limited data) Scale should norbe linear -Model improvements show diminishing returns OImprovement from a poor to fair model is greater than from a fair to good model CoVs for long-tail lines are higher than short-tail CoVs for the same score 0It's more difficult to model the underlying process of a long-tail line and predictors are less stable ·It's reasonable to use the same scale for outstanding claim liabilities and premium liabilities

## Types of External Systemic Risk

We can identify key potential sources of systemic risk through discussions with business experts as part of the valuation process. These discussions should consider:

---

Underwriting and risk selection Pricing Claims Management Expense Management Emerging portfolio trends ·The environment in which the portfolio operates

CoVs for each external systemic risk category should be selected using a mix of quantitative analysis and qualitative judgment

Economicand Social Risk

Includes normal inflation (CPI) and economic conditions (unemployment, GDP growth, ...)

Legislative, Political and Claims Inflation Risk

These risks are likely to be more significant for long-tail lines. Some examples include

·Impact of recent legislation or changes in court interpretation Potential future legislation that impacts losses retrospectively ·Precedent setting in courts ·Changes in medical technology costs or legal costs ·Systemic shifts in large claim frequency or severity

### Claim Management Process Change Risk

Changes can impact all valuation classes, but are more relevant for outstanding claims liabilities than premium liabilities. It's important to discuss current and future process changes with claims management and how changes could impact reporting/payment patterns, closing and reopening rates, and case reserves.

### Expense Risk

Expense risk is generally a small contributor to total external systemic risk

### Event Risk Catastrophes

Catastrophes have the most significant impact on property lines of business.

Sources to help quantify the impact of event risk for premium liabilities:

·Past experience from event risk losses ·CAT models Reinsurance intermediaries

---

## Latent Claim Risk

Latent claim risk may be material for workers compensation and liability classes,but is negligible for most valuation classes. This risk has low probability, but high potential severity (e.g. asbestos). Discussions with underwriters can help to identify sources of risk

### Recovery Risk

Likely to be insignificant for most valuation classes, except potentially for third party recoveries for Auto. Reinsurance recovery risk could be driven by catastrophes.

## Recipes for Calculation Problems

Risk Margin Calculation Internal Risk Balanced Scorecard
