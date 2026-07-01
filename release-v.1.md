# Manuscript Data Tables

This repository contains data tables used in the revised manuscript.

The repository contains input data, intermediate matrices, result summaries, perturbation outputs, sensitivity summaries, audit files, and run metadata.

The repository  contains MATLAB source code.

## Folder Structure

```text
README.md
results/
  run_metadata.json
  paper_ready_results.csv
  inputs/
  trace/
  main_tables/
  sensitivity/
  perturbation/
  audit/
```

## Metadata

| File | Content |
|---|---|
| `results/run_metadata.json` | Random seed, default parameters, perturbation levels, repetitions, and sensitivity grids. |
| `results/paper_ready_results.csv` | Index of manuscript table data and source files. |

## Input Data

| File | Content |
|---|---|
| `results/inputs/case1_input_tensor.csv` | CASE1 input tensor. |
| `results/inputs/case3_raw_ivff_terms.csv` | CASE3 original IVFF linguistic terms. |
| `results/inputs/case3_converted_tensor.csv` | CASE3 converted tensor. |
| `results/inputs/case3_input_tensor.csv` | CASE3 input tensor used in the result files. |

## Intermediate Matrices

| File | Content |
|---|---|
| `results/trace/case1_W.csv` | CASE1 weight matrix. |
| `results/trace/case1_AC.csv` | CASE1 alternative-criterion matrix. |
| `results/trace/case1_Pcond.csv` | CASE1 conditional preference matrix. |
| `results/trace/case1_S0rob.csv` | CASE1 regularized conditional preference matrix. |
| `results/trace/case1_T.csv` | CASE1 FJ interaction matrix. |
| `results/trace/case1_Zeq.csv` | CASE1 FJ equilibrium matrix. |
| `results/trace/case1_G.csv` | CASE1 final group score vector. |
| `results/trace/case3_W.csv` | CASE3 weight matrix. |
| `results/trace/case3_AC.csv` | CASE3 alternative-criterion matrix. |
| `results/trace/case3_Pcond.csv` | CASE3 conditional preference matrix. |
| `results/trace/case3_S0rob.csv` | CASE3 regularized conditional preference matrix. |
| `results/trace/case3_T.csv` | CASE3 FJ interaction matrix. |
| `results/trace/case3_Zeq.csv` | CASE3 FJ equilibrium matrix. |
| `results/trace/case3_G.csv` | CASE3 final group score vector. |

## Main Result Tables

| File | Content |
|---|---|
| `results/main_tables/case1_main_summary.csv` | CASE1 clean-input, ablation, and baseline summary. |
| `results/main_tables/case3_main_summary.csv` | CASE3 clean-input, ablation, and baseline summary. |
| `results/main_tables/case1_paired_vs_M0.csv` | CASE1 paired comparison against M0. |
| `results/main_tables/case3_paired_vs_M0.csv` | CASE3 paired comparison against M0. |
| `results/main_tables/case1_ranking_stability_summary.csv` | CASE1 ranking stability summary. |
| `results/main_tables/case3_ranking_stability_summary.csv` | CASE3 ranking stability summary. |
| `results/main_tables/case3_bridge_sensitivity.csv` | CASE3 bridge-rule sensitivity summary. |

## Sensitivity Tables

| File | Content |
|---|---|
| `results/sensitivity/case1_alpha_sensitivity.csv` | CASE1 alpha sensitivity summary. |
| `results/sensitivity/case1_tau_sensitivity.csv` | CASE1 tau sensitivity summary. |
| `results/sensitivity/case1_lambda_sensitivity.csv` | CASE1 lambda sensitivity summary. |
| `results/sensitivity/case1_specification_sensitivity.csv` | CASE1 specification sensitivity summary. |
| `results/sensitivity/case3_alpha_sensitivity.csv` | CASE3 alpha sensitivity summary. |
| `results/sensitivity/case3_tau_sensitivity.csv` | CASE3 tau sensitivity summary. |
| `results/sensitivity/case3_lambda_sensitivity.csv` | CASE3 lambda sensitivity summary. |
| `results/sensitivity/case3_specification_sensitivity.csv` | CASE3 specification sensitivity summary. |

## Perturbation Tables

| File | Content |
|---|---|
| `results/perturbation/case1_robustness_trials.csv` | CASE1 perturbation trial-level results. |
| `results/perturbation/case1_robustness_summary.csv` | CASE1 perturbation summary. |
| `results/perturbation/case3_robustness_trials.csv` | CASE3 perturbation trial-level results. |
| `results/perturbation/case3_robustness_summary.csv` | CASE3 perturbation summary. |

## Audit Tables

| File | Content |
|---|---|
| `results/audit/case1_winsor_audit.csv` | CASE1 winsorization audit table. |
| `results/audit/case3_winsor_audit.csv` | CASE3 winsorization audit table. |
| `results/audit/case1_trust_diagnostics.csv` | CASE1 FJ matrix diagnostic table. |
| `results/audit/case3_trust_diagnostics.csv` | CASE3 FJ matrix diagnostic table. |

