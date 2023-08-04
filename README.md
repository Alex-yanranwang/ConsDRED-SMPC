# ConsDRED-SMPC
A novel and interpretable trajectory tracker integrating a Constrained Distributional Reinforced-disturbance-estimator (ConsDRED) for unknown aerodynamic effects into a Stochastic Model Predictive Controller (SMPC)

## Video for Practical Implementation 
Youtube: https://youtu.be/Yciyalys6XY

or Bilibili: https://www.bilibili.com/video/BV1w24y1n7mp/?spm_id_from=333.999.0.0&vd_source=dd110bcc02e945d8498193391788d2d6

## Abstract
Simultaneously accurate and reliable tracking control for quadrotors in complex dynamic environments is challenging. As aerodynamics derived from drag forces and moment variations are chaotic and difficult to precisely identify, most current quadrotor tracking systems treat them as simple 'disturbances' in conventional control approaches. We propose a novel, interpretable trajectory tracker integrating a Distributional Reinforcement Learning disturbance estimator for unknown aerodynamic effects with a Stochastic Model Predictive Controller (SMPC). The proposed estimator `Constrained Distributional Reinforced disturbance estimator' (ConsDRED) accurately identifies uncertainties between true and estimated values of aerodynamic effects. Simplified Affine Disturbance Feedback is used for control parameterization to guarantee convexity, which we integrate with a SMPC. We theoretically guarantee that ConsDRED achieves an optimal global convergence rate, and sublinear rates if constraints are violated with certain error decreases as neural network dimensions increase. To demonstrate practicality, we show convergent training in simulation and real-world experiments, and empirically verify that ConsDRED is less sensitive to hyperparameter settings compared with canonical constrained RL approaches. We demonstrate our system improves accumulative tracking errors by at least 62% compared with the recent art. Importantly, the proposed framework, ConsDRED-SMPC, balances the tradeoff between pursuing high performance and obeying conservative constraints for practical implementations.

## Reference
Yanran Wang, David Boyle

Trustworthy Reinforcement Learning for Quadrotor UAV Tracking Control Systems
Revised title as: Constrained Reinforcement Learning using Distributional Representation for Trustworthy Quadrotor UAV Tracking Control

ArXiv 2023

PDF: https://arxiv.org/abs/2302.11694

## Affiliations
Systems and Algorithms Laboratory (SysAL), Imperial College London, United Kingdom. https://www.imperial.ac.uk/systems-algorithms-design-lab/
