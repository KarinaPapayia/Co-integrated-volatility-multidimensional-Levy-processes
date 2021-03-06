# Estimation-of-co-integrated-volatility-for-multidimensional-L\'evy-processes

Code for the paper "Minimax rates for the covariance estimation in case of a two-dimensional L\'evy process with high frequency data".

The two_dim_jump_diffusion(ts, N, stable, DB_T) simulates the increments of a two-dimensional jump diffusion process in a high frequency setting. The BrownianIncrements(C, N) simulates the brownian increments of the diffusion process with sample size N and covariance matrix C. The stableIncrements(N) simulates the increments of a two a-stable levy process. The file    MC_spectral_estimator_FV_jumps computes the spectral estimator $ C_{n}^{12}(U_n)$ for a two-dimensional jump diffusion process with Finite variation jumps. MC_spectral_estimator_IV_jumps computes the spectral estimator $ C_{n}^{12}(U_n)$ for a two-dimensional jump diffusion process with Infinite variation jumps. 

The TRC_estimator_FV, TRC_estimator_IV simulate the truncated realised covariance $\widehat{IC}_{T}}$ for a two-dimensional jump diffusion with finite variation and infinite variation jumps respectively. 

Finally, RMSEs plots the root mean squared error for the monte carlo estimate against differents choises of the sample size N.
