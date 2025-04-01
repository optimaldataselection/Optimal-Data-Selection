# Optimal-Data-Selection

## To Reviewer CWYY
### Curse of dimensionality 

<div style="text-align: center;">
  <img src="augwad.png" alt="AugWAD Comparison" style="width: 60%;">
</div>

**Caption:** Data augmentation increases the dimensionality of raw data. We compare Wasserstein Distance (WD) calculations using: OTDD (blue line), augmented data (pink line), and augmented data without raw data sharing (green line, our method). The approximation error, introduced by the randomness of gamma, has a bounded error rate.

## To Reviewer rePU
### Robustness to different FL algorithms and hyper-parameters

<div style="display: flex; justify-content: space-between; margin-bottom: 20px;">
  <img src="fedavg_noniid_dots.png" alt="FL Algorithms Comparison 1" style="width: 32%;">
  <img src="fednova_noniid_dots.png" alt="FL Algorithms Comparison 2" style="width: 32%;">
  <img src="scaffold_noniid_dots.png" alt="FL Algorithms Comparison 3" style="width: 32%;">
</div>

<div style="display: flex; justify-content: space-between;">
  <img src="train_loss_comparison.png" alt="Training Loss Comparison" style="width: 48%;">
  <img src="val_accuracy_comparison.png" alt="Validation Accuracy Comparison" style="width: 48%;">
</div>

**Caption:** A comparison of Scaffold, FedNova, and FedAvg in a three-source setting reveals that federated learning (FL) models with lower training loss (indicating successful convergence) exhibit superior validation performance and a more distinct correlation between validation performance and combined Wasserstein Distance (combineWad).
