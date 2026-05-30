---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Working Papers

**Foreign Lobbying as an Electoral Strategy: Electoral Cycles and Major-Power Engagement**, 
*Working Paper.*  

<details>
<summary>Abstract</summary>
<br>
Major powers frequently influence elections abroad, yet existing research focuses primarily on the supply side of intervention. This paper shifts attention to the demand side by examining how weaker states seek foreign electoral support during electoral competition. I argue that foreign support-seeking follows electoral cycles: As elections approach, incumbents intensify efforts to secure foreign support that can strengthen their electoral prospects. However, not all forms of support-seeking are equally responsive to electoral cycles. Because public-facing support, such as high-level visits and political endorsements, is less constrained by the prolonged bargaining and implementation timelines associated with resource-based support, such as aid, trade, and investment, electoral cycles should be especially pronounced in these forms of support-seeking. Using original data on foreign government lobbying in the United States from FARA disclosures, classified with large language models, I find evidence that as elections approach, incumbent governments increased their efforts to secure foreign support, particularly public-facing support, from the U.S. These findings recast foreign electoral intervention as a process actively solicited by incumbents facing electoral pressures, rather than one driven solely by major powers.
</details>

---

**The Signaling Dilemma of Coercion: Credibly Threatening and Reassuring at the Same Time**, 
*Working Paper.*  

<details>
<summary>Abstract</summary>
<br>
Successful coercion requires not only that targets believe a challenger is willing to carry out its threats, but also that they believe it will stop once compliance is achieved. Existing research recognizes the importance of both threat credibility and assurance credibility, yet largely treats intentions as a one-dimensional problem of resolve and leaves unclear how assurances are communicated in practice. I argue that targets draw inferences along two dimensions: resolve, a challenger’s willingness to fight if challenged, and restraint, its willingness to refrain from pursuing additional demands once the target complies. This distinction requires targets to differentiate among three types of challengers: unresolved, resolved and restrained, and resolved but unrestrained. Because coercive actions convey information about both dimensions simultaneously, coercers face a signaling dilemma. Measures that strengthen perceptions of resolve often raise concerns about restraint, while actions that reassure targets may weaken perceptions of resolve. Assurances, therefore, need not be communicated through explicit verbal commitments alone; they are often embedded in the strategic choice of coercive instruments themselves. Using a survey experiment, I show that military coercion increases perceived resolve but reduces perceived restraint, whereas nonmilitary coercion has the opposite effect. Combining the two instruments helps mitigate this trade-off, making challengers appear both more resolved and more restrained. The findings offer a new behavioral account of coercive credibility and expand conventional understandings of how assurances are communicated in international politics.
</details>

---

**The Limitations of Using Forced Choice in Electoral Conjoint Experiments**, with [Giancarlo Visconti](https://www.giancarlovisconti.com/).
*Under Review*  
[[Manuscript]](/files/Conjoint_Forced_Choice.pdf) 

<details>
<summary>Abstract</summary>
<br>
Electoral conjoint experiments typically require respondents to choose between two candidates, assuming full turnout and strict preference orderings, even though real-world voters may abstain or cast protest votes. We show that excluding these options is not trivial. In our preregistered experiment, more than half of respondents abstained or cast protest votes at least once when such options were available. While most AMCE estimates remain stable, a subset shifts in direction, magnitude, or significance—changes that are unpredictable ex ante and can mislead inferences about voter preferences. Marginal mean estimates diverge even sharply across designs. These shifts are systematic, shaped by respondent-level traits (e.g., turnout history and propensity) and task-level features such as rating differentials and contest appeal. Our findings show that forced-choice designs impose strong behavioral assumptions and risk obscuring meaningful variation in electoral behavior. Providing explicit opt-out options enhances validity and better captures the full range of voter preferences.

</details>

---


**Beyond Signaling: Inadvertences and Belief Updating in International Crises**, with [Roseanne McManus](https://sites.psu.edu/roseannemcmanus/).
*Working Paper*  

<details>
<summary>Abstract</summary>
<br>
Research on crisis bargaining has primarily focused on signaling as a means for states to convey resolve. Yet signals are not the only means of conveying information about resolve from one state to another. We focus on another information source, which we dub ``inadvertences.’’  Inadvertences are information transmissions that are \textit{at least plausibly} unintentional. Examples include apparently spontaneous emotional displays and information gained through intelligence. We predict that the extent to which observers update their estimates of a state's resolve based on inadvertences will depend upon how likely they think it is that the information was truly revealed unintentionally. We further theorize that this is a function of two features: image alignment and audience awareness. When an inadvertence conveys information that aligns with the imagine that the sender seeks to signal publicly and it is clear that the sender is aware of an audience, observers will be more likely to conclude that the sender had the incentive to unobservably manipulate the inadvertence and therefore discount its informational value. In contrast, inadvertences that convey information that contradicts the sender's public image or are conveyed in a context in which the sender is plausibly unaware or uncertain about having an audience are more likely to update beliefs. We find support for our theory in a survey experiment and case anecdotes.

</details>

---

## Software

### `DeepLearningCausal`: Causal Inference with Super Learner and Deep Neural Networks

An R package for estimating Conditional Average Treatment Effects (CATEs) 
from meta-learner models (S-, T-, X-, R-learner) and Population Average 
Treatment Effects on the Treated (PATT) in settings with treatment 
noncompliance. The package integrates Python's deep learning ecosystem 
(TensorFlow, Keras3) into R via `reticulate`, while also supporting weighted 
ensemble learning through the Super Learner approach.

[![CRAN](https://www.r-pkg.org/badges/version/DeepLearningCausal)](https://cran.r-project.org/package=DeepLearningCausal)
[![Downloads](https://cranlogs.r-pkg.org/badges/grand-total/DeepLearningCausal)](https://cran.r-project.org/package=DeepLearningCausal)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

📄 **Companion Paper**: [Khoi, Khoi Huynh](https://nguyenkhuynh.wordpress.com/), **Yang Yang**, and [Bumba Mukherjee](https://www.bumbamukherjee.net/). (2025). 
"DeepLearningCausal: An R Package for Estimating Treatment Effects Using 
Deep Neural Networks and Ensemble Learning." *The R Journal*, **forthcoming**.  

[[CRAN]](https://cran.r-project.org/package=DeepLearningCausal) 
[[GitHub]](https://github.com/hknd23/DeepLearningCausal) 
[[Tutorial]](https://github.com/hknd23/DeepLearningCausal/blob/main/tutorial.md)

<details>
<summary>▸ Description</summary>

`DeepLearningCausal` enables researchers to estimate causal effects from 
observational and experimental data using state-of-the-art deep learning 
and ensemble methods within the R environment. Key features include:

- **Meta-learner CATE estimation** via S-, T-, X-, and R-learner models 
  (Künzel et al., 2019; Nie and Wager, 2021)
- **PATT estimation under treatment noncompliance** based on the PATT-C 
  framework (Ottoboni and Poulous, 2020)
- **Flexible deep neural network architectures** with customizable 
  optimizers (Adam, SGD, AdaGrad, RMSprop), hyperparameter tuning, and 
  hidden layer configuration
- **Conformal prediction intervals** for individual treatment effects (ITEs)
- **Weighted ensemble learning** via Super Learner integrating XGBoost, 
  random forests, lasso, neural nets, and other base learners
- **Heterogeneous treatment effects visualization** across subgroups

The package is designed for applied researchers in political science, 
economics, public health, and the social sciences who seek to leverage 
deep learning for causal inference without leaving the R environment.

</details>




