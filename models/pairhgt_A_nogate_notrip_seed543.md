# PairHGT, gate fixed at 1 (no gate) — seed 543

[← all models](../README.md) · PairHGT notebook · ogbg-molpcba

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation AP | **0.3020** at epoch 56 |
| Best validation AP, EMA weights | 0.3073 at epoch 53 |
| Test AP | raw 0.2907 / ema 0.2963 (final) |
| Seed | 543 |
| Parameters | 9,751,632 |
| Minutes per epoch (last 5, incl. validation) | 4.5 |
| Training time so far | 7.4 h |
| Training time left | done |
| Sessions (start + resumes) | 2 |
| Hottest GPU reading | 89.0 °C |
| Last update | 2026-11-18 05:25 (252.7 h ago) |

![curves](pairhgt_A_nogate_notrip_seed543.png)

<details><summary>Settings of this run</summary>

| Setting | Value |
|---|---|
| Epochs (warm-up) | 100 (5) |
| Batch size | 512 |
| Learning rate, weight decay | 0.0005, 1e-05 |
| Layers × width, heads | 5 × 384, 4 |
| Dropout, attention dropout | 0.2, 0.5 |
| Pair channel | width 16, dropout 0.1, value gate False |
| Precision | fp32 (TF32 matrix products) |
| EMA decay | 0.9995 |
| Gradient clip | 1.0 |
| Protocol | v2_test_once |
| Notebook version, config hash | pairhgt-confirmatory-v2.0, f924dd96f7aefd19 |

</details>

## Final test (evaluated once)

| Weights | Epoch | Validation AP | Test AP |
|---|---|---|---|
| raw | 56 | 0.3020 | 0.2907 |
| ema | 53 | 0.3073 | 0.2963 |

## Every epoch (newest first)

| Epoch | Train loss | Val AP | Val AP (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0187 | 0.2959 | 0.2961 | 0.3020 (ep 56) | 1.37e-07 | 4.5 |
| 99 | 0.0187 | 0.2958 | 0.2960 | 0.3020 (ep 56) | 5.47e-07 | 4.5 |
| 98 | 0.0186 | 0.2962 | 0.2961 | 0.3020 (ep 56) | 1.23e-06 | 4.5 |
| 97 | 0.0187 | 0.2954 | 0.2960 | 0.3020 (ep 56) | 2.18e-06 | 4.5 |
| 96 | 0.0187 | 0.2958 | 0.2961 | 0.3020 (ep 56) | 3.41e-06 | 4.5 |
| 95 | 0.0187 | 0.2964 | 0.2961 | 0.3020 (ep 56) | 4.91e-06 | 4.4 |
| 94 | 0.0188 | 0.2962 | 0.2962 | 0.3020 (ep 56) | 6.67e-06 | 4.5 |
| 93 | 0.0187 | 0.2956 | 0.2964 | 0.3020 (ep 56) | 8.70e-06 | 4.5 |
| 92 | 0.0188 | 0.2952 | 0.2965 | 0.3020 (ep 56) | 1.10e-05 | 4.5 |
| 91 | 0.0188 | 0.2958 | 0.2967 | 0.3020 (ep 56) | 1.35e-05 | 4.5 |
| 90 | 0.0188 | 0.2958 | 0.2972 | 0.3020 (ep 56) | 1.64e-05 | 4.5 |
| 89 | 0.0189 | 0.2965 | 0.2971 | 0.3020 (ep 56) | 1.94e-05 | 4.5 |
| 88 | 0.0189 | 0.2968 | 0.2973 | 0.3020 (ep 56) | 2.27e-05 | 4.5 |
| 87 | 0.0190 | 0.2972 | 0.2974 | 0.3020 (ep 56) | 2.63e-05 | 4.5 |
| 86 | 0.0190 | 0.2962 | 0.2973 | 0.3020 (ep 56) | 3.01e-05 | 4.5 |
| 85 | 0.0191 | 0.2968 | 0.2973 | 0.3020 (ep 56) | 3.42e-05 | 4.4 |
| 84 | 0.0192 | 0.2955 | 0.2975 | 0.3020 (ep 56) | 3.85e-05 | 4.5 |
| 83 | 0.0192 | 0.2969 | 0.2978 | 0.3020 (ep 56) | 4.30e-05 | 4.5 |
| 82 | 0.0193 | 0.2976 | 0.2990 | 0.3020 (ep 56) | 4.77e-05 | 4.5 |
| 81 | 0.0194 | 0.2977 | 0.2993 | 0.3020 (ep 56) | 5.27e-05 | 4.5 |
| 80 | 0.0195 | 0.2976 | 0.2990 | 0.3020 (ep 56) | 5.79e-05 | 4.5 |
| 79 | 0.0196 | 0.2966 | 0.2994 | 0.3020 (ep 56) | 6.33e-05 | 4.5 |
| 78 | 0.0197 | 0.2973 | 0.2993 | 0.3020 (ep 56) | 6.89e-05 | 4.5 |
| 77 | 0.0198 | 0.2967 | 0.3008 | 0.3020 (ep 56) | 7.47e-05 | 4.4 |
| 76 | 0.0199 | 0.2978 | 0.3007 | 0.3020 (ep 56) | 8.07e-05 | 4.5 |
| 75 | 0.0200 | 0.2979 | 0.3009 | 0.3020 (ep 56) | 8.69e-05 | 4.4 |
| 74 | 0.0202 | 0.2978 | 0.3000 | 0.3020 (ep 56) | 9.32e-05 | 4.4 |
| 73 | 0.0203 | 0.2973 | 0.2996 | 0.3020 (ep 56) | 9.97e-05 | 4.4 |
| 72 | 0.0204 | 0.2979 | 0.2996 | 0.3020 (ep 56) | 1.06e-04 | 4.5 |
| 71 | 0.0206 | 0.2966 | 0.3005 | 0.3020 (ep 56) | 1.13e-04 | 4.5 |
| 70 | 0.0207 | 0.2953 | 0.3008 | 0.3020 (ep 56) | 1.20e-04 | 4.5 |
| 69 | 0.0208 | 0.2964 | 0.3018 | 0.3020 (ep 56) | 1.27e-04 | 4.5 |
| 68 | 0.0210 | 0.2967 | 0.3023 | 0.3020 (ep 56) | 1.35e-04 | 4.5 |
| 67 | 0.0212 | 0.2990 | 0.3021 | 0.3020 (ep 56) | 1.42e-04 | 4.5 |
| 66 | 0.0213 | 0.2980 | 0.3020 | 0.3020 (ep 56) | 1.50e-04 | 4.5 |
| 65 | 0.0215 | 0.2983 | 0.3031 | 0.3020 (ep 56) | 1.57e-04 | 4.5 |
| 64 | 0.0217 | 0.2968 | 0.3040 | 0.3020 (ep 56) | 1.65e-04 | 4.5 |
| 63 | 0.0218 | 0.2956 | 0.3043 | 0.3020 (ep 56) | 1.73e-04 | 4.5 |
| 62 | 0.0220 | 0.2980 | 0.3045 | 0.3020 (ep 56) | 1.81e-04 | 4.5 |
| 61 | 0.0222 | 0.2963 | 0.3051 | 0.3020 (ep 56) | 1.89e-04 | 4.5 |
| 60 | 0.0223 | 0.2983 | 0.3060 | 0.3020 (ep 56) | 1.97e-04 | 4.5 |
| 59 | 0.0226 | 0.2987 | 0.3069 | 0.3020 (ep 56) | 2.05e-04 | 4.5 |
| 58 | 0.0227 | 0.3001 | 0.3067 | 0.3020 (ep 56) | 2.13e-04 | 4.5 |
| 57 | 0.0229 | 0.2999 | 0.3069 | 0.3020 (ep 56) | 2.21e-04 | 4.4 |
| 56 | 0.0230 | 0.3020 ⭐ | 0.3072 | 0.3020 (ep 56) | 2.29e-04 | 4.5 |
| 55 | 0.0233 | 0.3000 | 0.3070 | 0.3012 (ep 51) | 2.38e-04 | 4.5 |
| 54 | 0.0235 | 0.2997 | 0.3068 | 0.3012 (ep 51) | 2.46e-04 | 4.5 |
| 53 | 0.0237 | 0.2972 | 0.3073 | 0.3012 (ep 51) | 2.54e-04 | 4.5 |
| 52 | 0.0239 | 0.3004 | 0.3072 | 0.3012 (ep 51) | 2.62e-04 | 4.5 |
| 51 | 0.0241 | 0.3012 ⭐ | 0.3064 | 0.3012 (ep 51) | 2.71e-04 | 4.5 |
| 50 | 0.0243 | 0.2995 | 0.3062 | 0.3002 (ep 49) | 2.79e-04 | 4.5 |
| 49 | 0.0245 | 0.3002 ⭐ | 0.3060 | 0.3002 (ep 49) | 2.87e-04 | 4.5 |
| 48 | 0.0247 | 0.2999 ⭐ | 0.3060 | 0.2999 (ep 48) | 2.95e-04 | 4.5 |
| 47 | 0.0250 | 0.2942 | 0.3066 | 0.2986 (ep 46) | 3.03e-04 | 4.5 |
| 46 | 0.0252 | 0.2986 ⭐ | 0.3062 | 0.2986 (ep 46) | 3.11e-04 | 4.5 |
| 45 | 0.0254 | 0.2949 | 0.3062 | 0.2980 (ep 37) | 3.19e-04 | 4.5 |
| 44 | 0.0256 | 0.2979 | 0.3059 | 0.2980 (ep 37) | 3.27e-04 | 4.5 |
| 43 | 0.0258 | 0.2978 | 0.3061 | 0.2980 (ep 37) | 3.35e-04 | 4.5 |
| 42 | 0.0261 | 0.2969 | 0.3061 | 0.2980 (ep 37) | 3.43e-04 | 4.5 |
| 41 | 0.0264 | 0.2942 | 0.3061 | 0.2980 (ep 37) | 3.50e-04 | 4.5 |
| 40 | 0.0266 | 0.2951 | 0.3066 | 0.2980 (ep 37) | 3.58e-04 | 4.4 |
| 39 | 0.0268 | 0.2978 | 0.3065 | 0.2980 (ep 37) | 3.65e-04 | 4.5 |
| 38 | 0.0270 | 0.2969 | 0.3059 | 0.2980 (ep 37) | 3.73e-04 | 4.5 |
| 37 | 0.0273 | 0.2980 ⭐ | 0.3047 | 0.2980 (ep 37) | 3.80e-04 | 4.5 |
| 36 | 0.0275 | 0.2958 ⭐ | 0.3038 | 0.2958 (ep 36) | 3.87e-04 | 4.5 |
| 35 | 0.0277 | 0.2956 ⭐ | 0.3028 | 0.2956 (ep 35) | 3.94e-04 | 4.5 |
| 34 | 0.0280 | 0.2898 | 0.3019 | 0.2907 (ep 31) | 4.00e-04 | 4.5 |
| 33 | 0.0283 | 0.2907 | 0.3004 | 0.2907 (ep 31) | 4.07e-04 | 4.5 |
| 32 | 0.0286 | 0.2900 | 0.3004 | 0.2907 (ep 31) | 4.13e-04 | 4.5 |
| 31 | 0.0288 | 0.2907 ⭐ | 0.2992 | 0.2907 (ep 31) | 4.19e-04 | 4.5 |
| 30 | 0.0291 | 0.2839 | 0.2983 | 0.2853 (ep 27) | 4.25e-04 | 4.4 |
| 29 | 0.0294 | 0.2847 | 0.2971 | 0.2853 (ep 27) | 4.31e-04 | 4.5 |
| 28 | 0.0297 | 0.2845 | 0.2952 | 0.2853 (ep 27) | 4.37e-04 | 4.4 |
| 27 | 0.0300 | 0.2853 ⭐ | 0.2942 | 0.2853 (ep 27) | 4.42e-04 | 4.4 |
| 26 | 0.0303 | 0.2850 ⭐ | 0.2933 | 0.2850 (ep 26) | 4.47e-04 | 4.4 |
| 25 | 0.0306 | 0.2811 | 0.2924 | 0.2812 (ep 24) | 4.52e-04 | 4.5 |
| 24 | 0.0309 | 0.2812 ⭐ | 0.2897 | 0.2812 (ep 24) | 4.57e-04 | 4.4 |
| 23 | 0.0314 | 0.2777 ⭐ | 0.2874 | 0.2777 (ep 23) | 4.62e-04 | 4.5 |
| 22 | 0.0316 | 0.2769 ⭐ | 0.2851 | 0.2769 (ep 22) | 4.66e-04 | 4.4 |
| 21 | 0.0320 | 0.2731 | 0.2825 | 0.2742 (ep 20) | 4.70e-04 | 4.4 |
| 20 | 0.0323 | 0.2742 ⭐ | 0.2798 | 0.2742 (ep 20) | 4.74e-04 | 4.4 |
| 19 | 0.0328 | 0.2607 | 0.2764 | 0.2678 (ep 18) | 4.77e-04 | 4.4 |
| 18 | 0.0332 | 0.2678 ⭐ | 0.2715 | 0.2678 (ep 18) | 4.81e-04 | 4.4 |
| 17 | 0.0337 | 0.2614 ⭐ | 0.2675 | 0.2614 (ep 17) | 4.84e-04 | 4.4 |
| 16 | 0.0342 | 0.2558 ⭐ | 0.2621 | 0.2558 (ep 16) | 4.86e-04 | 4.4 |
| 15 | 0.0347 | 0.2393 | 0.2585 | 0.2405 (ep 14) | 4.89e-04 | 4.5 |
| 14 | 0.0353 | 0.2405 ⭐ | 0.2538 | 0.2405 (ep 14) | 4.91e-04 | 4.4 |
| 13 | 0.0359 | 0.2292 ⭐ | 0.2469 | 0.2292 (ep 13) | 4.93e-04 | 4.5 |
| 12 | 0.0366 | 0.2272 | 0.2426 | 0.2286 (ep 11) | 4.95e-04 | 4.5 |
| 11 | 0.0373 | 0.2286 ⭐ | 0.2348 | 0.2286 (ep 11) | 4.97e-04 | 4.4 |
| 10 | 0.0381 | 0.2114 ⭐ | 0.2228 | 0.2114 (ep 10) | 4.98e-04 | 4.4 |
| 9 | 0.0390 | 0.1996 ⭐ | 0.2120 | 0.1996 (ep 9) | 4.99e-04 | 4.4 |
| 8 | 0.0400 | 0.1888 ⭐ | 0.1988 | 0.1888 (ep 8) | 4.99e-04 | 4.4 |
| 7 | 0.0413 | 0.1822 ⭐ | 0.1839 | 0.1822 (ep 7) | 5.00e-04 | 4.5 |
| 6 | 0.0430 | 0.1622 ⭐ | 0.1624 | 0.1622 (ep 6) | 5.00e-04 | 4.4 |
| 5 | 0.0451 | 0.1422 ⭐ | 0.1350 | 0.1422 (ep 5) | 4.00e-04 | 4.4 |
| 4 | 0.0488 | 0.1121 ⭐ | 0.1027 | 0.1121 (ep 4) | 3.00e-04 | 4.4 |
| 3 | 0.0685 | 0.0693 ⭐ | 0.0657 | 0.0693 (ep 3) | 2.00e-04 | 4.5 |
| 2 | 0.3361 | 0.0435 ⭐ | 0.0402 | 0.0435 (ep 2) | 1.00e-04 | 4.5 |
| 1 | 0.6984 | 0.0253 ⭐ | 0.0253 | 0.0253 (ep 1) | 5.00e-10 | 4.4 |

## Last 80 log lines

_The log counts epochs from 0; the tables above count from 1._

```
[seed 543] epoch  82/100 | lr 4.77e-05 | train BCE 0.0193 | val AP 0.2976 | best val 0.3020 @ep56 | EMA val 0.2990 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.3h
[seed 543] epoch  83/100 | lr 4.30e-05 | train BCE 0.0192 | val AP 0.2969 | best val 0.3020 @ep56 | EMA val 0.2978 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.3h
[seed 543] epoch  84/100 | lr 3.85e-05 | train BCE 0.0192 | val AP 0.2955 | best val 0.3020 @ep56 | EMA val 0.2975 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.2h
[seed 543] epoch  85/100 | lr 3.42e-05 | train BCE 0.0191 | val AP 0.2968 | best val 0.3020 @ep56 | EMA val 0.2973 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.1h
[seed 543] epoch  86/100 | lr 3.01e-05 | train BCE 0.0190 | val AP 0.2962 | best val 0.3020 @ep56 | EMA val 0.2973 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.0h
[seed 543] epoch  87/100 | lr 2.63e-05 | train BCE 0.0190 | val AP 0.2972 | best val 0.3020 @ep56 | EMA val 0.2974 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.0h
[seed 543] epoch  88/100 | lr 2.27e-05 | train BCE 0.0189 | val AP 0.2968 | best val 0.3020 @ep56 | EMA val 0.2973 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.9h
[seed 543] epoch  89/100 | lr 1.94e-05 | train BCE 0.0189 | val AP 0.2965 | best val 0.3020 @ep56 | EMA val 0.2971 | 268s (train 240s, eval 28s) | GPU max 89C | ETA<= 0.8h
[seed 543] epoch  90/100 | lr 1.64e-05 | train BCE 0.0188 | val AP 0.2958 | best val 0.3020 @ep56 | EMA val 0.2972 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.7h
[seed 543] epoch  91/100 | lr 1.35e-05 | train BCE 0.0188 | val AP 0.2958 | best val 0.3020 @ep56 | EMA val 0.2967 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.7h
[seed 543] epoch  92/100 | lr 1.10e-05 | train BCE 0.0188 | val AP 0.2952 | best val 0.3020 @ep56 | EMA val 0.2965 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.6h
[seed 543] epoch  93/100 | lr 8.70e-06 | train BCE 0.0187 | val AP 0.2956 | best val 0.3020 @ep56 | EMA val 0.2964 | 268s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.5h
[seed 543] epoch  94/100 | lr 6.67e-06 | train BCE 0.0188 | val AP 0.2962 | best val 0.3020 @ep56 | EMA val 0.2962 | 268s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.4h
[seed 543] epoch  95/100 | lr 4.91e-06 | train BCE 0.0187 | val AP 0.2964 | best val 0.3020 @ep56 | EMA val 0.2961 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.4h
[seed 543] epoch  96/100 | lr 3.41e-06 | train BCE 0.0187 | val AP 0.2958 | best val 0.3020 @ep56 | EMA val 0.2961 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.3h
[seed 543] epoch  97/100 | lr 2.18e-06 | train BCE 0.0187 | val AP 0.2954 | best val 0.3020 @ep56 | EMA val 0.2960 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.2h
[seed 543] epoch  98/100 | lr 1.23e-06 | train BCE 0.0186 | val AP 0.2962 | best val 0.3020 @ep56 | EMA val 0.2961 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.1h
[seed 543] epoch  99/100 | lr 5.47e-07 | train BCE 0.0187 | val AP 0.2958 | best val 0.3020 @ep56 | EMA val 0.2960 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.1h
[seed 543] epoch 100/100 | lr 1.37e-07 | train BCE 0.0187 | val AP 0.2959 | best val 0.3020 @ep56 | EMA val 0.2961 | 268s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.0h
[seed 543] FINAL TEST (evaluated once): raw epoch 56 val 0.3020 test 0.2907 | EMA epoch 53 val 0.3073 test 0.2963
--- cell 16 ---
PairHGT, gate fixed at 1 (no gate): GPS + pair channel (pair bias + write-back) [arm A_nogate_notrip] | gps_conf_A_nogate_notrip_ep100_molpcba
 seed  epochs  raw_epoch  raw_val  raw_test  ema_epoch  ema_val  ema_test  hours  train_s_per_epoch  total_s_per_epoch
  101 100/100         91   0.2973    0.2909         92   0.2970    0.2916 7.4298           239.2251           267.4726
  202 100/100         49   0.3003    0.2936         41   0.3078    0.3026 7.4248           239.0581           267.2913
  323 100/100         39   0.3064    0.2938         48   0.3117    0.3043 7.4250           239.0676           267.2989
  432 100/100         55   0.3036    0.2968         45   0.3100    0.3072 7.4226           238.9966           267.2132
  543 100/100         56   0.3020    0.2907         53   0.3073    0.2963 7.4210           238.9263           267.1564
mean ± sample SD (ddof=1) over 5 seed(s): raw test 0.2932 ± 0.0025 | EMA test 0.3004 ± 0.0063
A mean ± SD over fewer than 3 seeds is only a description; do not call it a confidence interval.
run manifest: 20 row(s) -> /home/student/thesis/outputs/pairhgt/outputs/confirmatory/run_manifest.csv
    model              gpu  seeds  params  train_s_per_epoch  val_eval_s_per_epoch  total_s_per_epoch  hours_per_seed  time_vs_GPS+EMA
GPS + EMA NVIDIA RTX A4000      5 9744860             160.70                 15.83             176.55            4.90             1.00
  PairHGT NVIDIA RTX A4000      5 9751972             275.33                 33.75             309.10            8.59             1.75
train = training steps incl. EMA update; val_eval = validation of raw + EMA weights; no test pass inside an epoch (protocol v2). Do not compare with timings from the exploratory runs.
--- cell 18 ---
=== PairHGT  minus  GPS + EMA   (100 epochs, matched seeds) ===
 seed  raw_val  ema_val  raw_test  ema_test
  101   0.0013   0.0027    0.0043    0.0048
  202   0.0017   0.0012    0.0067    0.0115
  323   0.0021   0.0022    0.0019    0.0056
  432   0.0017   0.0035    0.0066    0.0120
  543  -0.0012  -0.0008    0.0101    0.0068
  validation AP, raw    : mean +0.0011, sample SD 0.0013, per-seed [0.0013, 0.0017, 0.0021, 0.0017, -0.0012], all positive: False | 95% t-interval [-0.0006, +0.0028] (n=5, t=1.84)
  validation AP, EMA    : mean +0.0018, sample SD 0.0017, per-seed [0.0027, 0.0012, 0.0022, 0.0035, -0.0008], all positive: False | 95% t-interval [-0.0003, +0.0038] (n=5, t=2.38)
  test AP, raw vs raw   : mean +0.0059, sample SD 0.0031, per-seed [0.0043, 0.0067, 0.0019, 0.0066, 0.0101], all positive: True | 95% t-interval [+0.0021, +0.0097] (n=5, t=4.31)
  test AP, EMA vs EMA   : mean +0.0082, sample SD 0.0034, per-seed [0.0048, 0.0115, 0.0056, 0.012, 0.0068], all positive: True | 95% t-interval [+0.0039, +0.0124] (n=5, t=5.35)
  Reading: 5 matched seed(s). Interpret with the interval, not with a threshold.
=== PairHGT  minus  PairHGT, gate fixed at 1 (no gate)   (100 epochs, matched seeds) ===
 seed  raw_val  ema_val  raw_test  ema_test
  101   0.0083   0.0161    0.0033    0.0127
  202   0.0034   0.0018    0.0027    0.0036
  323  -0.0059  -0.0052    0.0029    0.0007
  432   0.0009   0.0018    0.0014    0.0047
  543   0.0008   0.0017    0.0055    0.0070
  validation AP, raw    : mean +0.0015, sample SD 0.0051, per-seed [0.0083, 0.0034, -0.0059, 0.0009, 0.0008], all positive: False | 95% t-interval [-0.0049, +0.0079] (n=5, t=0.65)
  validation AP, EMA    : mean +0.0032, sample SD 0.0078, per-seed [0.0161, 0.0018, -0.0052, 0.0018, 0.0017], all positive: False | 95% t-interval [-0.0064, +0.0129] (n=5, t=0.93)
  test AP, raw vs raw   : mean +0.0032, sample SD 0.0015, per-seed [0.0033, 0.0027, 0.0029, 0.0014, 0.0055], all positive: True | 95% t-interval [+0.0013, +0.0050] (n=5, t=4.79)
  test AP, EMA vs EMA   : mean +0.0057, sample SD 0.0045, per-seed [0.0127, 0.0036, 0.0007, 0.0047, 0.007], all positive: True | 95% t-interval [+0.0002, +0.0113] (n=5, t=2.86)
  Reading: 5 matched seed(s). Interpret with the interval, not with a threshold.
ABLATION RULE (PairHGT vs PairHGT, gate fixed at 1 (no gate), validation AP, margin 0.002): raw +0.0015, EMA +0.0032 -> component NOT shown to matter (lead < margin on at least one weight type)
  screening result on 1-3 seeds: it decides whether a full 100-epoch run is worth its cost, nothing more.
=== PairHGT  minus  PairHGT, gate only (no pair bias)   (100 epochs, matched seeds) ===
 seed  raw_val  ema_val  raw_test  ema_test
  101   0.0077   0.0067    0.0016    0.0028
  202   0.0018   0.0010    0.0049    0.0060
  323   0.0014  -0.0008    0.0050    0.0051
  432   0.0014   0.0021    0.0039    0.0089
  validation AP, raw    : mean +0.0031, sample SD 0.0031, per-seed [0.0077, 0.0018, 0.0014, 0.0014], all positive: True | 95% t-interval [-0.0018, +0.0080] (n=4, t=1.99)
  validation AP, EMA    : mean +0.0022, sample SD 0.0032, per-seed [0.0067, 0.001, -0.0008, 0.0021], all positive: False | 95% t-interval [-0.0028, +0.0073] (n=4, t=1.42)
  test AP, raw vs raw   : mean +0.0038, sample SD 0.0016, per-seed [0.0016, 0.0049, 0.005, 0.0039], all positive: True | 95% t-interval [+0.0013, +0.0064] (n=4, t=4.79)
  test AP, EMA vs EMA   : mean +0.0057, sample SD 0.0025, per-seed [0.0028, 0.006, 0.0051, 0.0089], all positive: True | 95% t-interval [+0.0017, +0.0097] (n=4, t=4.57)
  Reading: 4 matched seed(s). The claim is limited to whether the direction of the EMA-vs-EMA difference repeats; a significance claim needs many more seeds.
ABLATION RULE (PairHGT vs PairHGT, gate only (no pair bias), validation AP, margin 0.002): raw +0.0031, EMA +0.0022 -> component RETAINED (lead on both weight types)
  screening result on 1-3 seeds: it decides whether a full 100-epoch run is worth its cost, nothing more.
Planning table (80% power, alpha 0.05, two-sample t, test AP): smallest detectable true difference
  per-seed SD 0.003: n=3: 0.0092, n=5: 0.0061, n=10: 0.0040, n=20: 0.0027
  per-seed SD 0.0056: n=3: 0.0172, n=5: 0.0113, n=10: 0.0074, n=20: 0.0051
--- cell 20 ---
===== 2026-11-18 05:26:49 notebook turn ended (exit 0); executed notebook: /home/student/thesis/outputs/lab_runs/notebooks/pairhgt_A_nogate_notrip_seed543_20261118-0352.ipynb =====
```
