# Parameter-inference-for-ODEs

Ordinary differential equations (ODEs) are widely used in multiple sciences to model a vast range of phenomena. In this study, we are interested in imple- menting and comparing the performance of the Pseudo-Least Square (Liang and Wu 2008) method and the Least Square Finite Element (Krueger et al. 2017) method on the logistic growth ODE and the Lotka-Volterra coupled ODE system. We also aim to investigate the possibility of obtaining better performance from our methods by interfering with the data.

We implemented the methods and checked their robustness and the correctness of the models. Then, compare their performance on both models and proceed to improve their efficiency by decreasing the population at some point and estimating the parameters on the 2 data sets obtained by splitting the observations at that moment.

From the experiments we found that: 1) LSFE is indeed a very robust method that returns consistent results regardless of setting, 2) PsLS performs the best on small time scales, which can be beneficial when working with real- life data, as getting observation sets is not always easy, and 3) by interfering on data in the early stages of bacteria colony development, the estimation efficiency improves significantly for both methods.
