# MADDPG with policy ensemble
reference from https://github.com/xuehy/pytorch-maddpg, and this repository add polciy ensemble.
About how use, please go to https://github.com/xuehy/pytorch-maddpg.
please modify k for number of sub-policy. 
And for details, we use the following settings in paper:
> We choose K= 3 sub-policies for the keep-away and cooperative navigation environments, and K= 2 for predator-prey. To improve convergence speed, we enforce that the cooperative agents should have the same policies at each episode, and similarly for the adversaries.
