---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Working Papers

**Foreign Lobbying as an Electoral Strategy: Electoral Cycles and Major-Power Engagement** (Job Market Paper), 
*Under Review.*  

[[Manuscript]](/files/YYang_Demand_Support.pdf) 

<details>
<summary>Abstract</summary>
<br>
Major powers frequently influence elections abroad, yet existing research focuses primarily on the supply side of intervention. This paper shifts attention to the demand side by examining how weaker states seek foreign electoral support during electoral competition. I argue that foreign support-seeking follows electoral cycles: As elections approach, incumbents intensify efforts to secure foreign support that can strengthen their electoral prospects. More specifically, electoral cycles should be more pronounced in efforts to secure public-facing support than resource-based support. While both can be electorally valuable, public-facing support––such as high-level visits and political endorsements––can be delivered much more quickly than resource-based support––such as aid, trade, and investment, which typically requires prolonged bargaining and implementation. Using original data on foreign government lobbying in the United States from FARA disclosures, classified with large language models, I find that incumbents intensify their efforts to seek foreign electoral support as elections approach, and that this pattern is driven primarily by efforts to secure public-facing support from the United States rather than resource-based support. These findings recast foreign electoral intervention as a process actively solicited by incumbents facing electoral pressures, rather than one driven solely by major powers.
</details>

---

**The Signaling Dilemma of Coercion: Credibly Threatening and Reassuring at the Same Time**, 
*Working Paper.*  

<details>
<summary>Abstract</summary>
<br>
Successful coercion requires convincing targets both that a challenger is willing to carry out its threats and that it will stop once compliance is achieved. Existing research recognizes the importance of both forms of credibility while highlighting the tension between them. However, it remains unclear how states can credibly threaten and reassure at the same time. I develop a theoretical framework that reconceptualizes this challenge as a signaling problem. I argue that coercive actions simultaneously convey information about two distinct latent intentions of the coercer: resolve—the willingness to use force if demands are resisted—and restraint—the willingness to limit objectives and halt punishment once compliance is achieved. Targets infer resolve from a coercer’s readiness for escalation and restraint from its patience with diplomacy. Because costly military and non-military coercive actions convey different information about these underlying intentions, each strengthens one dimension of credibility while weakening the other. Specifically, costly military signals communicate readiness for escalation, increasing perceived resolve but reducing perceived restraint, whereas costly non-military signals communicate patience with diplomacy, producing the opposite pattern. I further argue that strategically combining costly military and non-military signals enables coercers to communicate both resolve and restraint, thereby mitigating the signaling dilemma. A survey experiment provides support for these predictions. This paper addresses two related puzzles in costly signaling: how states can communicate both resolve and restraint, and why we often see states pursue a mixed signaling strategy.
</details>

---

**The Limitations of Using Forced Choice in Electoral Conjoint Experiments**, with [Giancarlo Visconti](https://www.giancarlovisconti.com/){:target="_blank" rel="noopener noreferrer"}.
*Under Review*  

[[Manuscript]](/files/Conjoint_Forced_Choice.pdf) 

<details>
<summary>Abstract</summary>
<br>
Electoral conjoint experiments typically require respondents to choose between two candidates, assuming full turnout and strict preference orderings, even though real-world voters may abstain or cast protest votes. We show that excluding these options is not trivial. In our preregistered experiment, more than half of respondents abstained or cast protest votes at least once when such options were available. While most AMCE estimates remain stable, a subset shifts in direction, magnitude, or significance—changes that are unpredictable ex ante and can mislead inferences about voter preferences. Marginal mean estimates diverge even sharply across designs. These shifts are systematic, shaped by respondent-level traits (e.g., turnout history and propensity) and task-level features such as rating differentials and contest appeal. Our findings show that forced-choice designs impose strong behavioral assumptions and risk obscuring meaningful variation in electoral behavior. Providing explicit opt-out options enhances validity and better captures the full range of voter preferences.

</details>

---


**Beyond Signaling: Inadvertences and Belief Updating in International Crises**, with [Roseanne McManus](https://sites.psu.edu/roseannemcmanus/){:target="_blank" rel="noopener noreferrer"}.
*Working Paper*  

<details>
<summary>Abstract</summary>
<br>
Research on crisis bargaining has primarily focused on signaling as a means for states to convey resolve. Yet signals are not the only means of conveying information about resolve from one state to another. We focus on another information source, which we dub "inadvertences."  Inadvertences are information transmissions that are at least plausibly unintentional. Examples include apparently spontaneous emotional displays and information gained through intelligence. We predict that the extent to which observers update their estimates of a state's resolve based on inadvertences will depend upon how likely they think it is that the information was truly revealed unintentionally. We further theorize that this is a function of two features: image alignment and audience awareness. When an inadvertence conveys information that aligns with the imagine that the sender seeks to signal publicly and it is clear that the sender is aware of an audience, observers will be more likely to conclude that the sender had the incentive to unobservably manipulate the inadvertence and therefore discount its informational value. In contrast, inadvertences that convey information that contradicts the sender's public image or are conveyed in a context in which the sender is plausibly unaware or uncertain about having an audience are more likely to update beliefs. We find support for our theory in a survey experiment and case anecdotes.

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

📄 **Companion Paper**: [Khoi, Khoi Huynh](https://nguyenkhuynh.wordpress.com/){:target="_blank" rel="noopener noreferrer"}, **Yang Yang**, and [Bumba Mukherjee](https://www.bumbamukherjee.net/){:target="_blank" rel="noopener noreferrer"}. (2025). 
"DeepLearningCausal: An R Package for Estimating Treatment Effects Using 
Deep Neural Networks and Ensemble Learning." *The R Journal*, 18(2), 2026. DOI: 10.32614/RJ-2026-035.  

[[CRAN]](https://cran.r-project.org/package=DeepLearningCausal) 
[[GitHub]](https://github.com/hknd23/DeepLearningCausal) 
[[Tutorial]](https://github.com/hknd23/DeepLearningCausal/blob/main/tutorial.md)

<details markdown="1">
<summary>Description</summary>

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




