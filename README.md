# PairHGT: confirmatory runs

**Last updated: 2026-11-28 18:07** (Dhaka time). Updates every 15 minutes; if this is more than 30 minutes old, the training PC is probably off.

Notebook `ConfirmatoryPhase-Arm-PairHGT` (protocol v2, "test once"): arms GPS + EMA (control) and PairHGT, 100 epochs, fresh seeds 101, 202, 323, 432, 543, on one NVIDIA RTX A4000. Generalization notebooks `PairHGT_<dataset>` (same protocol and model; the published GraphGPS recipe of each dataset): Peptides-func, Peptides-struct, ogbg-molhiv.

Training now: none of these runs.

## ogbg-molpcba: runs (AP)

| Run | Seed | State | Epoch | Best val AP raw (epoch) | Best val AP EMA (epoch) | Test AP raw / EMA | Min/epoch | Trained | Time left |
|---|---|---|---|---|---|---|---|---|---|
| [GPS + EMA](models/pairhgt_GPS_ema_seed101.md) | 101 | finished | 100/100 | 0.3044 (56) | 0.3103 (50) | 0.2900 / 0.2995 | 3.0 | 4.9 h | done |
| [PairHGT](models/pairhgt_PairHGT_seed101.md) | 101 | finished | 100/100 | 0.3056 (39) | 0.3131 (40) | 0.2943 / 0.3043 | 5.2 | 8.6 h | done |
| [PairHGT, gate only (no pair bias)](models/pairhgt_A_gateonly_nobias_seed101.md) | 101 | finished | 100/100 | 0.2979 (42) | 0.3064 (37) | 0.2927 / 0.3014 | 4.5 | 7.4 h | done |
| [PairHGT, gate fixed at 1 (no gate)](models/pairhgt_A_nogate_notrip_seed101.md) | 101 | finished | 100/100 | 0.2973 (91) | 0.2970 (92) | 0.2909 / 0.2916 | 4.5 | 7.4 h | done |
| [GPS + EMA](models/pairhgt_GPS_ema_seed202.md) | 202 | finished | 100/100 | 0.3020 (51) | 0.3085 (46) | 0.2897 / 0.2947 | 2.9 | 4.9 h | done |
| [PairHGT](models/pairhgt_PairHGT_seed202.md) | 202 | finished | 100/100 | 0.3036 (62) | 0.3097 (48) | 0.2963 / 0.3062 | 5.1 | 8.6 h | done |
| [PairHGT, gate only (no pair bias)](models/pairhgt_A_gateonly_nobias_seed202.md) | 202 | finished | 100/100 | 0.3018 (46) | 0.3087 (44) | 0.2914 / 0.3002 | 4.5 | 7.5 h | done |
| [PairHGT, gate fixed at 1 (no gate)](models/pairhgt_A_nogate_notrip_seed202.md) | 202 | finished | 100/100 | 0.3003 (49) | 0.3078 (41) | 0.2936 / 0.3026 | 4.5 | 7.4 h | done |
| [GPS + EMA](models/pairhgt_GPS_ema_seed323.md) | 323 | finished | 100/100 | 0.2984 (53) | 0.3043 (37) | 0.2948 / 0.2994 | 2.9 | 4.9 h | done |
| [PairHGT](models/pairhgt_PairHGT_seed323.md) | 323 | finished | 100/100 | 0.3005 (50) | 0.3065 (45) | 0.2967 / 0.3050 | 5.1 | 8.6 h | done |
| [PairHGT, gate only (no pair bias)](models/pairhgt_A_gateonly_nobias_seed323.md) | 323 | finished | 100/100 | 0.2991 (37) | 0.3073 (44) | 0.2917 / 0.2999 | 4.5 | 7.5 h | done |
| [PairHGT, gate fixed at 1 (no gate)](models/pairhgt_A_nogate_notrip_seed323.md) | 323 | finished | 100/100 | 0.3064 (39) | 0.3117 (48) | 0.2938 / 0.3043 | 4.4 | 7.4 h | done |
| [GPS + EMA](models/pairhgt_GPS_ema_seed432.md) | 432 | finished | 100/100 | 0.3028 (51) | 0.3083 (50) | 0.2916 / 0.2998 | 2.9 | 4.9 h | done |
| [PairHGT](models/pairhgt_PairHGT_seed432.md) | 432 | finished | 100/100 | 0.3045 (48) | 0.3118 (41) | 0.2982 / 0.3119 | 5.2 | 8.6 h | done |
| [PairHGT, gate only (no pair bias)](models/pairhgt_A_gateonly_nobias_seed432.md) | 432 | finished | 100/100 | 0.3032 (50) | 0.3097 (38) | 0.2943 / 0.3030 | 4.5 | 7.5 h | done |
| [PairHGT, gate fixed at 1 (no gate)](models/pairhgt_A_nogate_notrip_seed432.md) | 432 | finished | 100/100 | 0.3036 (55) | 0.3100 (45) | 0.2968 / 0.3072 | 4.5 | 7.4 h | done |
| [GPS + EMA](models/pairhgt_GPS_ema_seed543.md) | 543 | finished | 100/100 | 0.3040 (51) | 0.3098 (48) | 0.2861 / 0.2964 | 2.9 | 4.9 h | done |
| [PairHGT](models/pairhgt_PairHGT_seed543.md) | 543 | finished | 100/100 | 0.3028 (39) | 0.3090 (35) | 0.2962 / 0.3033 | 5.1 | 8.6 h | done |
| [PairHGT, gate only (no pair bias)](models/pairhgt_A_gateonly_nobias_seed543.md) | 543 | finished | 100/100 | 0.3011 (36) | 0.3084 (37) | 0.2921 / 0.2992 | 4.5 | 7.5 h | done |
| [PairHGT, gate fixed at 1 (no gate)](models/pairhgt_A_nogate_notrip_seed543.md) | 543 | finished | 100/100 | 0.3020 (56) | 0.3073 (53) | 0.2907 / 0.2963 | 4.5 | 7.4 h | done |

### GPS + EMA vs PairHGT, seed by seed (AP)

Raw weights are compared with raw, EMA with EMA (values: raw / EMA). Validation AP is the best epoch's; test AP is evaluated once, after a run has finished. Δ = PairHGT − GPS + EMA.

| Seed | GPS + EMA val | PairHGT val | Δ val | GPS + EMA test | PairHGT test | Δ test |
|---|---|---|---|---|---|---|
| 101 | 0.3044 / 0.3103 | 0.3056 / 0.3131 | +0.0013 / +0.0027 | 0.2900 / 0.2995 | 0.2943 / 0.3043 | +0.0043 / +0.0048 |
| 202 | 0.3020 / 0.3085 | 0.3036 / 0.3097 | +0.0017 / +0.0012 | 0.2897 / 0.2947 | 0.2963 / 0.3062 | +0.0067 / +0.0115 |
| 323 | 0.2984 / 0.3043 | 0.3005 / 0.3065 | +0.0021 / +0.0022 | 0.2948 / 0.2994 | 0.2967 / 0.3050 | +0.0019 / +0.0056 |
| 432 | 0.3028 / 0.3083 | 0.3045 / 0.3118 | +0.0017 / +0.0035 | 0.2916 / 0.2998 | 0.2982 / 0.3119 | +0.0066 / +0.0120 |
| 543 | 0.3040 / 0.3098 | 0.3028 / 0.3090 | -0.0012 / -0.0008 | 0.2861 / 0.2964 | 0.2962 / 0.3033 | +0.0101 / +0.0068 |

Mean ± sample SD of the differences over seeds where both runs have finished:

| | raw | EMA |
|---|---|---|
| Δ validation AP | +0.0011 ± 0.0013 (n=5) | +0.0018 ± 0.0017 (n=5) |
| Δ test AP | +0.0059 ± 0.0031 (n=5) | +0.0082 ± 0.0034 (n=5) |

## Peptides-func: runs (AP)

| Run | Seed | State | Epoch | Best val AP raw (epoch) | Best val AP EMA (epoch) | Test AP raw / EMA | Min/epoch | Trained | Time left |
|---|---|---|---|---|---|---|---|---|---|
| [GPS + EMA · Peptides-func (AP)](models/pairhgt_peptides_func_GPS_ema_seed101.md) | 101 | finished | 200/200 | 0.6627 (133) | 0.6687 (98) | 0.6561 / 0.6682 | 0.2 | 37 min | done |
| [PairHGT · Peptides-func (AP)](models/pairhgt_peptides_func_PairHGT_seed101.md) | 101 | finished | 200/200 | 0.6845 (168) | 0.6850 (115) | 0.6709 / 0.6661 | 2.8 | 9.4 h | done |
| [GPS + EMA · Peptides-func (AP)](models/pairhgt_peptides_func_GPS_ema_seed202.md) | 202 | finished | 200/200 | 0.6560 (147) | 0.6608 (106) | 0.6497 / 0.6540 | 0.2 | 38 min | done |
| [PairHGT · Peptides-func (AP)](models/pairhgt_peptides_func_PairHGT_seed202.md) | 202 | finished | 200/200 | 0.6814 (144) | 0.6859 (100) | 0.6818 / 0.6793 | 2.8 | 9.3 h | done |
| [GPS + EMA · Peptides-func (AP)](models/pairhgt_peptides_func_GPS_ema_seed323.md) | 323 | finished | 200/200 | 0.6588 (132) | 0.6632 (79) | 0.6690 / 0.6637 | 0.2 | 38 min | done |
| [PairHGT · Peptides-func (AP)](models/pairhgt_peptides_func_PairHGT_seed323.md) | 323 | finished | 200/200 | 0.6821 (133) | 0.6836 (85) | 0.6864 / 0.6760 | 2.8 | 9.4 h | done |
| [GPS + EMA · Peptides-func (AP)](models/pairhgt_peptides_func_GPS_ema_seed432.md) | 432 | finished | 200/200 | 0.6687 (165) | 0.6765 (76) | 0.6569 / 0.6518 | 0.2 | 38 min | done |
| [PairHGT · Peptides-func (AP)](models/pairhgt_peptides_func_PairHGT_seed432.md) | 432 | finished | 200/200 | 0.7005 (124) | 0.7051 (102) | 0.6853 / 0.6822 | 2.8 | 9.3 h | done |
| [GPS + EMA · Peptides-func (AP)](models/pairhgt_peptides_func_GPS_ema_seed543.md) | 543 | finished | 200/200 | 0.6737 (149) | 0.6762 (109) | 0.6502 / 0.6537 | 0.2 | 38 min | done |
| [PairHGT · Peptides-func (AP)](models/pairhgt_peptides_func_PairHGT_seed543.md) | 543 | finished | 200/200 | 0.6833 (121) | 0.6851 (126) | 0.6876 / 0.6944 | 2.8 | 9.3 h | done |

### GPS + EMA vs PairHGT, seed by seed (AP)

Raw weights are compared with raw, EMA with EMA (values: raw / EMA). Validation AP is the best epoch's; test AP is evaluated once, after a run has finished. Δ = PairHGT − GPS + EMA.

| Seed | GPS + EMA val | PairHGT val | Δ val | GPS + EMA test | PairHGT test | Δ test |
|---|---|---|---|---|---|---|
| 101 | 0.6627 / 0.6687 | 0.6845 / 0.6850 | +0.0218 / +0.0163 | 0.6561 / 0.6682 | 0.6709 / 0.6661 | +0.0148 / -0.0020 |
| 202 | 0.6560 / 0.6608 | 0.6814 / 0.6859 | +0.0254 / +0.0252 | 0.6497 / 0.6540 | 0.6818 / 0.6793 | +0.0322 / +0.0252 |
| 323 | 0.6588 / 0.6632 | 0.6821 / 0.6836 | +0.0233 / +0.0205 | 0.6690 / 0.6637 | 0.6864 / 0.6760 | +0.0173 / +0.0123 |
| 432 | 0.6687 / 0.6765 | 0.7005 / 0.7051 | +0.0318 / +0.0286 | 0.6569 / 0.6518 | 0.6853 / 0.6822 | +0.0284 / +0.0304 |
| 543 | 0.6737 / 0.6762 | 0.6833 / 0.6851 | +0.0096 / +0.0089 | 0.6502 / 0.6537 | 0.6876 / 0.6944 | +0.0373 / +0.0407 |

Mean ± sample SD of the differences over seeds where both runs have finished:

| | raw | EMA |
|---|---|---|
| Δ validation AP | +0.0224 ± 0.0081 (n=5) | +0.0199 ± 0.0077 (n=5) |
| Δ test AP | +0.0260 ± 0.0097 (n=5) | +0.0213 ± 0.0166 (n=5) |

## Peptides-struct: runs (MAE, lower is better)

| Run | Seed | State | Epoch | Best val MAE raw (epoch) | Best val MAE EMA (epoch) | Test MAE raw / EMA | Min/epoch | Trained | Time left |
|---|---|---|---|---|---|---|---|---|---|
| [GPS + EMA · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_GPS_ema_seed101.md) | 101 | finished | 200/200 | 0.2477 (110) | 0.2438 (94) | 0.2506 / 0.2461 | 0.2 | 38 min | done |
| [PairHGT · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_PairHGT_seed101.md) | 101 | finished | 200/200 | 0.2447 (159) | 0.2413 (98) | 0.2470 / 0.2459 | 2.4 | 7.9 h | done |
| [GPS + EMA · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_GPS_ema_seed202.md) | 202 | finished | 200/200 | 0.2463 (116) | 0.2437 (98) | 0.2508 / 0.2475 | 0.2 | 38 min | done |
| [PairHGT · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_PairHGT_seed202.md) | 202 | finished | 200/200 | 0.2430 (113) | 0.2410 (101) | 0.2464 / 0.2423 | 2.4 | 7.9 h | done |
| [GPS + EMA · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_GPS_ema_seed323.md) | 323 | finished | 200/200 | 0.2471 (134) | 0.2446 (88) | 0.2486 / 0.2481 | 0.2 | 38 min | done |
| [PairHGT · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_PairHGT_seed323.md) | 323 | finished | 200/200 | 0.2450 (103) | 0.2423 (88) | 0.2496 / 0.2459 | 2.4 | 7.9 h | done |
| [GPS + EMA · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_GPS_ema_seed432.md) | 432 | finished | 200/200 | 0.2428 (138) | 0.2426 (127) | 0.2475 / 0.2476 | 0.2 | 38 min | done |
| [PairHGT · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_PairHGT_seed432.md) | 432 | finished | 200/200 | 0.2432 (199) | 0.2410 (108) | 0.2463 / 0.2445 | 2.4 | 7.9 h | done |
| [GPS + EMA · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_GPS_ema_seed543.md) | 543 | finished | 200/200 | 0.2449 (134) | 0.2432 (105) | 0.2510 / 0.2487 | 0.2 | 38 min | done |
| [PairHGT · Peptides-struct (MAE, lower is better)](models/pairhgt_peptides_struct_PairHGT_seed543.md) | 543 | finished | 200/200 | 0.2418 (119) | 0.2408 (113) | 0.2470 / 0.2458 | 2.4 | 7.9 h | done |

### GPS + EMA vs PairHGT, seed by seed (MAE, lower is better)

Raw weights are compared with raw, EMA with EMA (values: raw / EMA). Validation MAE is the best epoch's; test MAE is evaluated once, after a run has finished. Δ = PairHGT − GPS + EMA (negative favours PairHGT).

| Seed | GPS + EMA val | PairHGT val | Δ val | GPS + EMA test | PairHGT test | Δ test |
|---|---|---|---|---|---|---|
| 101 | 0.2477 / 0.2438 | 0.2447 / 0.2413 | -0.0029 / -0.0025 | 0.2506 / 0.2461 | 0.2470 / 0.2459 | -0.0035 / -0.0002 |
| 202 | 0.2463 / 0.2437 | 0.2430 / 0.2410 | -0.0033 / -0.0026 | 0.2508 / 0.2475 | 0.2464 / 0.2423 | -0.0044 / -0.0052 |
| 323 | 0.2471 / 0.2446 | 0.2450 / 0.2423 | -0.0022 / -0.0023 | 0.2486 / 0.2481 | 0.2496 / 0.2459 | +0.0010 / -0.0022 |
| 432 | 0.2428 / 0.2426 | 0.2432 / 0.2410 | +0.0004 / -0.0016 | 0.2475 / 0.2476 | 0.2463 / 0.2445 | -0.0012 / -0.0031 |
| 543 | 0.2449 / 0.2432 | 0.2418 / 0.2408 | -0.0031 / -0.0023 | 0.2510 / 0.2487 | 0.2470 / 0.2458 | -0.0040 / -0.0030 |

Mean ± sample SD of the differences over seeds where both runs have finished:

| | raw | EMA |
|---|---|---|
| Δ validation MAE | -0.0022 ± 0.0015 (n=5) | -0.0023 ± 0.0004 (n=5) |
| Δ test MAE | -0.0024 ± 0.0023 (n=5) | -0.0027 ± 0.0018 (n=5) |

## ogbg-molhiv: runs (ROC-AUC)

| Run | Seed | State | Epoch | Best val ROC-AUC raw (epoch) | Best val ROC-AUC EMA (epoch) | Test ROC-AUC raw / EMA | Min/epoch | Trained | Time left |
|---|---|---|---|---|---|---|---|---|---|
| [GPS + EMA · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_GPS_ema_seed101.md) | 101 | finished | 100/100 | 0.8225 (30) | 0.8111 (38) | 0.7840 / 0.7927 | 0.8 | 1.3 h | done |
| [PairHGT · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_PairHGT_seed101.md) | 101 | finished | 100/100 | 0.8125 (72) | 0.8080 (87) | 0.7892 / 0.7894 | 1.8 | 3.0 h | done |
| [GPS + EMA · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_GPS_ema_seed202.md) | 202 | finished | 100/100 | 0.8166 (15) | 0.8085 (16) | 0.7669 / 0.7774 | 0.8 | 1.3 h | done |
| [PairHGT · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_PairHGT_seed202.md) | 202 | finished | 100/100 | 0.8287 (29) | 0.8198 (26) | 0.7701 / 0.7943 | 1.8 | 3.0 h | done |
| [GPS + EMA · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_GPS_ema_seed323.md) | 323 | finished | 100/100 | 0.8175 (24) | 0.7994 (21) | 0.7644 / 0.7783 | 0.8 | 1.4 h | done |
| [PairHGT · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_PairHGT_seed323.md) | 323 | finished | 100/100 | 0.8082 (84) | 0.7977 (89) | 0.7982 / 0.7982 | 1.8 | 3.0 h | done |
| [GPS + EMA · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_GPS_ema_seed432.md) | 432 | finished | 100/100 | 0.8146 (40) | 0.7987 (49) | 0.7984 / 0.8011 | 0.8 | 1.4 h | done |
| [PairHGT · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_PairHGT_seed432.md) | 432 | finished | 100/100 | 0.8436 (22) | 0.8378 (23) | 0.7739 / 0.8088 | 1.8 | 3.0 h | done |
| [GPS + EMA · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_GPS_ema_seed543.md) | 543 | finished | 100/100 | 0.8255 (14) | 0.8219 (20) | 0.7734 / 0.7782 | 0.8 | 1.4 h | done |
| [PairHGT · ogbg-molhiv (ROC-AUC)](models/pairhgt_molhiv_PairHGT_seed543.md) | 543 | finished | 100/100 | 0.8126 (46) | 0.7998 (58) | 0.7899 / 0.7921 | 1.8 | 3.0 h | done |

### GPS + EMA vs PairHGT, seed by seed (ROC-AUC)

Raw weights are compared with raw, EMA with EMA (values: raw / EMA). Validation ROC-AUC is the best epoch's; test ROC-AUC is evaluated once, after a run has finished. Δ = PairHGT − GPS + EMA.

| Seed | GPS + EMA val | PairHGT val | Δ val | GPS + EMA test | PairHGT test | Δ test |
|---|---|---|---|---|---|---|
| 101 | 0.8225 / 0.8111 | 0.8125 / 0.8080 | -0.0099 / -0.0031 | 0.7840 / 0.7927 | 0.7892 / 0.7894 | +0.0052 / -0.0033 |
| 202 | 0.8166 / 0.8085 | 0.8287 / 0.8198 | +0.0121 / +0.0114 | 0.7669 / 0.7774 | 0.7701 / 0.7943 | +0.0032 / +0.0169 |
| 323 | 0.8175 / 0.7994 | 0.8082 / 0.7977 | -0.0093 / -0.0017 | 0.7644 / 0.7783 | 0.7982 / 0.7982 | +0.0338 / +0.0199 |
| 432 | 0.8146 / 0.7987 | 0.8436 / 0.8378 | +0.0290 / +0.0391 | 0.7984 / 0.8011 | 0.7739 / 0.8088 | -0.0245 / +0.0077 |
| 543 | 0.8255 / 0.8219 | 0.8126 / 0.7998 | -0.0129 / -0.0222 | 0.7734 / 0.7782 | 0.7899 / 0.7921 | +0.0164 / +0.0139 |

Mean ± sample SD of the differences over seeds where both runs have finished:

| | raw | EMA |
|---|---|---|
| Δ validation ROC-AUC | +0.0018 ± 0.0182 (n=5) | +0.0047 ± 0.0226 (n=5) |
| Δ test ROC-AUC | +0.0068 ± 0.0213 (n=5) | +0.0110 ± 0.0092 (n=5) |

## Files

`data/` holds each run's `progress.json` (full history, selected epochs, final test, settings) and each arm's `prereg.json`, copied unchanged.
