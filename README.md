# Use-Case-Grounded Simulated Evaluations

This is a tutorial on how to train **SimEvals**, as presented in "Use-Case-Grounded Simulations for Explanation Evaluation" (NeurIPS 2022) [[pdf]](https://arxiv.org/abs/2206.02256). 

SimEvals measure the predictiveness of information content choices for a downstream use case. When designing a user study, the researcher must identify candidate choices of information content (e.g. which explanation methods, hyperparameters, or other additional baseline information) to evaluate. 


<p align="center">
<img src="assets/overview.jpg" height="400" width="600">
</p>

Our framework trains a SimEval agent for each choice of information content that the researcher intends to evaluate for a downstream use case. The researcher can then interpret the test set accuracy of each SimEval agent as a measure of the predictiveness of that information content.


## Step 0: 


## Step 1


## Step 2






## Citing SimEval
If you run your own SimEvals, we encourage you to cite our paper:
```
@inproceedings{
chen2022usecasegrounded,
title={Use-Case-Grounded Simulations for Explanation Evaluation},
author={Valerie Chen and Nari Johnson and Nicholay Topin and Gregory Plumb and Ameet Talwalkar},
booktitle={Advances in Neural Information Processing Systems},
year={2022}
}
```