# PairHGT on ogbg-molpcba: confirmatory runs

**Last updated: 2026-11-19 18:22** (Dhaka time). Updates every 15 minutes; if this is more than 30 minutes old, the training PC is probably off.

Notebook `ConfirmatoryPhase-Arm-PairHGT` (protocol v2, "test once"): arms GPS + EMA (control) and PairHGT, 100 epochs, fresh seeds 101, 202, 323, 432, 543, on one NVIDIA RTX A4000.

Training now: none of these runs.

## Runs

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

## GPS + EMA vs PairHGT, seed by seed

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

## Files

`data/` holds each run's `progress.json` (full history, selected epochs, final test, settings) and each arm's `prereg.json`, copied unchanged.
