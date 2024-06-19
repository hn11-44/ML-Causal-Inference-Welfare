# ML-Causal-Inference-Welfare

The analysis is on a data set is of a randomized controlled trial, with records of individuals’ opinion on government spending on the social safety net. In this setting we have two groups where each group was asked about government spending using different wordings:

Treatment Group (wi=1
), “Do you think the government spends too much on welfare”
Control Group (wi=0
), “Do you think the government spends too much on assitance to the poor”
In this particular case we are interested how the questions are worded impact the participants perspective on government spending. Thus our outcome is represented by y
 with:

y=1, which corresponds to a positive answer. This means that respondents think that government spends too much.

y=0, otherwise. 

This represents whether the respondents do not think that the government spends too much.
We are controlling for the demographics characteristics of participants by using the following covariates:

* age,
* polviews,
* income,
* education,
* martial and
* sex.

  1) We compute the simple difference-in-mean between the treatment and the control groups
  2) We worked in the observational setting, where the condition of the potential outcome being indpendent of the assigment of treatment or control is violated. 
