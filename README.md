# MPNet Motion Planning Experiments

This repository contains six Colab notebooks for evaluating MPNet-based motion planning and related baseline or hybrid methods.

## Contents

| Experiment | Notebook | Topic |
| --- | --- | --- |
| 1 | `notebooks/experiment-1-mpnet-vs-rrt.ipynb` | MPNet vs RRT/RRT* comparison |
| 2 | `notebooks/experiment-2-failure-case-analysis-baseline-mpnet.ipynb` | Failure case analysis of baseline MPNet |
| 3 | `notebooks/experiment-3-preliminary-improvement-hybrid-mpnet.ipynb` | Preliminary improvement attempts and Hybrid MPNet |
| 4 | `notebooks/experiment-4-parameter-sensitivity-analysis.ipynb` | Parameter sensitivity analysis |
| 5 | `notebooks/experiment-5-generalization-path-quality.ipynb` | Generalization and path quality evaluation |
| 6 | `notebooks/experiment-6-challenging-complex-environment-evaluation.ipynb` | Challenging and complex environment evaluation |

## How To Run

1. Open a notebook in Google Colab.
2. Use a GPU runtime when available.
3. Mount Google Drive when prompted by the first cells.
4. Make sure the required project and data files are available in `MyDrive`, especially:
   - `MPNet-master.zip`
   - `dataset.zip`
   - `cae_encoder.pkl`
   - `mlp_100_4000_PReLU_ae_dd_final.pkl`
5. Run cells from top to bottom.

## Notes

The notebooks were exported from Google Colab and may contain previous cell outputs. Some experiments save figures back to Google Drive. Paths inside the notebooks use the original Colab layout such as `/content/drive/MyDrive/...`.

Large model/data artifacts are not included in this repository. They should be stored separately in Google Drive or another approved course storage location.
