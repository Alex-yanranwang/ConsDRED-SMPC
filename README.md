<h1 align="center">Constrained RL using Distributional Representation for Trustworthy Quadrotor UAV Tracking Control</h1>
<p align="center">
    <a href="https://alex-yanranwang.github.io/">Yanran Wang</a><sup>*</sup></span>&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://profiles.imperial.ac.uk/david.boyle">David Boyle</a><sup></sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

<p align="center">
    <sup>*</sup>Corresponding Author&emsp;&emsp;&emsp;
</p>

<p align="center">
    Systems and Algorithms Lab, Imperial College London, United Kingdom.
</p>

<p align="center">
    IEEE Transactions on Automation Science and Engineering
</p>

<p align="center">
    <a href="https://arxiv.org/abs/2302.11694">arXiv</a> &nbsp;&nbsp;
    <a href="https://ieeexplore.ieee.org/document/10614102">Paper</a> &nbsp;&nbsp;
    <a href="https://youtu.be/Yciyalys6XY?si=kYDzHKMGlbNn3pf5">Video</a> &nbsp;&nbsp;
    <a href="https://alex-yanranwang.github.io/ConsDRED-SMPC.html">Project Page</a>
</p>

<p align="center">
  <img src="docs/RL_Control_framework.jpg" style="width:50%;">
</p>

## Practical Implementation of an autonomous aerial robot.
- [ ] 📣 Toturial (including the code and all the detailed configuration) of a real quadrotor has been released: [A-Framework-for-Robot-Autonomy](<https://github.com/Alex-yanranwang/A-Framework-for-Robot-Autonomy.git>)

## Abstract
<p align="justify">Simultaneously accurate and reliable tracking control for quadrotors in complex dynamic environments is challenging. The chaotic nature of aerodynamics, derived from drag forces and moment variations, makes precise identification difficult. Consequently, many existing quadrotor tracking systems treat these aerodynamic effects as simple `disturbances' in conventional control approaches. We propose a novel and interpretable trajectory tracker integrating a distributional Reinforcement Learning (RL) disturbance estimator for unknown aerodynamic effects with a Stochastic Model Predictive Controller (SMPC). Specifically, the proposed estimator `Constrained Distributional REinforced-Disturbance-estimator' (ConsDRED) effectively identifies uncertainties between the true and estimated values of aerodynamic effects. Control parameterization employs simplified affine disturbance feedback to ensure convexity, which is seamlessly integrated with the SMPC. We theoretically guarantee that ConsDRED achieves an optimal global convergence rate, and sublinear rates if constraints are violated with certain error decreases as neural network dimensions increase. To demonstrate practicality, we show convergent training, in simulation and real-world experiments, and empirically verify that ConsDRED is less sensitive to hyperparameter settings compared with canonical constrained RL. Our system substantially improves accumulative tracking errors by at least 70%, compared with the recent art. Importantly, the proposed ConsDRED-SMPC framework balances the trade-off between pursuing high performance and obeying conservative constraints for practical implementations.</p>

## Practical Implementation on a real quadrotor
<p align="center">
  <img src="docs/shortVideo.gif" width="600">
</p>


## BibTeX
<div class="container is-max-desktop content">
<pre><code>@article{wang2024constrained,
      title={Constrained Reinforcement Learning Using Distributional Representation for Trustworthy Quadrotor UAV Tracking Control},
      author={Wang, Yanran and Boyle, David},
      journal={IEEE Transactions on Automation Science and Engineering},
      year={2024},
      publisher={IEEE},
      pages={1-18},
      doi={10.1109/TASE.2024.3432405}
    }</code></pre>
</div>
If you find this repository helpful, please cite our paper and give us a star!

## Acknowledgements
<div class="container is-max-desktop content">
    This work was supported in part by the National Science Foundation (NSF)-UK Research and Innovation (UKRI) under Grant NE/T011467/1 and in part by the Engineering and Physical Sciences Research Council under Grant EP/X040518/1.
  </div>
