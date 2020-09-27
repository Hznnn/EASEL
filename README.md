# EASEL
The Code is created based on the method described in the following paper: Iterative Reconstruction for Low-Dose CT using Deep Gradient Priors of Generative Model. Zhuonan He, Yikun Zhang, Yu Guan, Shanzhou Niu, Yi Zhang,  Yang Chen, Qiegen Liu.

## Abstract
Dose reduction in computed tomography (CT) is essential for decreasing radiation risk in clinical applications. Iterative reconstruction is one of the most promising ways to compensate for the increased noise due to reduction of photon flux. Rather than most existing prior-driven algorithms that benefit from manually designed prior functions or supervised learning schemes, in this work we integrate the data-consistency as a conditional term into the iterative generative model for low-dose CT. At first, a score-based generative network is used for unsupervised distribution learning and the gradient of generative density prior is learned from normal-dose images. Then, the annealing Langevin dynamics is employed to update the trained priors with conditional scheme, i.e., the distance between the reconstructed image and the manifold is minimized along with data fidelity during reconstruction. Experimental comparisons demonstrated the noise reduction and detail preservation abilities of the proposed method. 


