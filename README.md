# predict_atomic_charge
Predicting scalars with DP, in terms of atomic charge
If we want to predict the charge for a large system, it will be time-consuming to perform DFT (density functional theory) calculations, and we can save machine time if we use neural networks to predict the atomic charge. In the following we will implement this in the DP framework, but of course we can also implement the prediction for other atomic scalars.
