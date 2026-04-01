# Results for *Variational Quantum Algorithms for Image Classification*

This repository contains the **generated results** accompanying the paper:

**“Variational Quantum Algorithms for Image Classification”**

It serves as the results archive for the experiments reported in the manuscript and includes the main summaries, aggregated statistics, geometry outputs, and selected plots.

## Contents

The repository contains results for:

- **Quantum experiments**
  - cross-entropy (main experiment)
  - mean-squared-error (robustness experiment)
  - global Fisher-geometry analysis
  - local Fisher-geometry analysis

- **Classical baselines**
  - TinyFNN
  - TinyCNN
  - performance summaries
  - global Fisher-geometry analysis
  - local Fisher-geometry analysis

## Datasets

All reported results are based on:

- MNIST
- KMNIST
- FashionMNIST

In all experiments, classification is restricted to classes **0–7**.

## What is included

Depending on the subfolder, the repository contains:

- aggregated JSON summaries
- best evaluation accuracies
- mean / standard deviation / 95% confidence intervals
- local and global Fisher-geometry summaries
- effective-dimension results
- checkpoints and run logs
- selected training / evaluation plots

## Main summary files

Typical top-level summary files include:

- `summary_all_information_for_quantum_experiments_final.json`
- `summary_all_information.json` (classical baseline results)
- additional dataset- or experiment-specific summary JSON files

These files are intended to make it easy to recover the reported values used in the paper tables and discussion.

## Notes

- This repository contains the **results**, not just the source code.
- The corresponding code repository contains the scripts used to generate these outputs.
- The quantum geometry results reported in the paper correspond to the **cross-entropy** setting.
- The MSE results are included as a robustness check.

## Related paper

If you use or refer to these results, please cite:

**Andrej Sum-Shik and Peter Thoma**  
*Variational Quantum Algorithms for Image Classification*

## Contact

For questions about the results or reproduction details, please open an issue in the associated code repository.
