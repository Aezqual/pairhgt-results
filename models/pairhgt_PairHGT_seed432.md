# PairHGT — seed 432

[← all models](../README.md) · PairHGT notebook · ogbg-molpcba

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation AP | **0.3045** at epoch 48 |
| Best validation AP, EMA weights | 0.3118 at epoch 41 |
| Test AP | raw 0.2982 / ema 0.3119 (final) |
| Seed | 432 |
| Parameters | 9,751,972 |
| Minutes per epoch (last 5, incl. validation) | 5.2 |
| Training time so far | 8.6 h |
| Training time left | done |
| Sessions (start + resumes) | 2 |
| Hottest GPU reading | 89.0 °C |
| Last update | 2026-11-13 23:34 (18.5 h ago) |

![curves](pairhgt_PairHGT_seed432.png)

<details><summary>Settings of this run</summary>

| Setting | Value |
|---|---|
| Epochs (warm-up) | 100 (5) |
| Batch size | 512 |
| Learning rate, weight decay | 0.0005, 1e-05 |
| Layers × width, heads | 5 × 384, 4 |
| Dropout, attention dropout | 0.2, 0.5 |
| Pair channel | width 16, dropout 0.1, value gate True |
| Precision | fp32 (TF32 matrix products) |
| EMA decay | 0.9995 |
| Gradient clip | 1.0 |
| Protocol | v2_test_once |
| Notebook version, config hash | pairhgt-confirmatory-v2.0, 9171049c2c7acf57 |

</details>

## Final test (evaluated once)

| Weights | Epoch | Validation AP | Test AP |
|---|---|---|---|
| raw | 48 | 0.3045 | 0.2982 |
| ema | 41 | 0.3118 | 0.3119 |

## Every epoch (newest first)

| Epoch | Train loss | Val AP | Val AP (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0181 | 0.2949 | 0.2950 | 0.3045 (ep 48) | 1.37e-07 | 5.2 |
| 99 | 0.0181 | 0.2948 | 0.2951 | 0.3045 (ep 48) | 5.47e-07 | 5.1 |
| 98 | 0.0181 | 0.2947 | 0.2951 | 0.3045 (ep 48) | 1.23e-06 | 5.2 |
| 97 | 0.0181 | 0.2951 | 0.2951 | 0.3045 (ep 48) | 2.18e-06 | 5.2 |
| 96 | 0.0182 | 0.2948 | 0.2952 | 0.3045 (ep 48) | 3.41e-06 | 5.1 |
| 95 | 0.0182 | 0.2953 | 0.2952 | 0.3045 (ep 48) | 4.91e-06 | 5.1 |
| 94 | 0.0182 | 0.2946 | 0.2951 | 0.3045 (ep 48) | 6.67e-06 | 5.1 |
| 93 | 0.0182 | 0.2947 | 0.2952 | 0.3045 (ep 48) | 8.70e-06 | 5.1 |
| 92 | 0.0182 | 0.2945 | 0.2953 | 0.3045 (ep 48) | 1.10e-05 | 5.2 |
| 91 | 0.0183 | 0.2944 | 0.2956 | 0.3045 (ep 48) | 1.35e-05 | 5.2 |
| 90 | 0.0183 | 0.2942 | 0.2957 | 0.3045 (ep 48) | 1.64e-05 | 5.1 |
| 89 | 0.0183 | 0.2951 | 0.2959 | 0.3045 (ep 48) | 1.94e-05 | 5.2 |
| 88 | 0.0184 | 0.2950 | 0.2959 | 0.3045 (ep 48) | 2.27e-05 | 5.2 |
| 87 | 0.0185 | 0.2950 | 0.2962 | 0.3045 (ep 48) | 2.63e-05 | 5.1 |
| 86 | 0.0185 | 0.2954 | 0.2961 | 0.3045 (ep 48) | 3.01e-05 | 5.1 |
| 85 | 0.0186 | 0.2953 | 0.2964 | 0.3045 (ep 48) | 3.42e-05 | 5.1 |
| 84 | 0.0186 | 0.2951 | 0.2967 | 0.3045 (ep 48) | 3.85e-05 | 5.2 |
| 83 | 0.0187 | 0.2950 | 0.2973 | 0.3045 (ep 48) | 4.30e-05 | 5.1 |
| 82 | 0.0188 | 0.2956 | 0.2976 | 0.3045 (ep 48) | 4.77e-05 | 5.1 |
| 81 | 0.0189 | 0.2968 | 0.2976 | 0.3045 (ep 48) | 5.27e-05 | 5.2 |
| 80 | 0.0190 | 0.2972 | 0.2977 | 0.3045 (ep 48) | 5.79e-05 | 5.2 |
| 79 | 0.0191 | 0.2955 | 0.2979 | 0.3045 (ep 48) | 6.33e-05 | 5.2 |
| 78 | 0.0192 | 0.2962 | 0.2981 | 0.3045 (ep 48) | 6.89e-05 | 5.2 |
| 77 | 0.0193 | 0.2952 | 0.2979 | 0.3045 (ep 48) | 7.47e-05 | 5.2 |
| 76 | 0.0194 | 0.2955 | 0.2987 | 0.3045 (ep 48) | 8.07e-05 | 5.1 |
| 75 | 0.0195 | 0.2953 | 0.2993 | 0.3045 (ep 48) | 8.69e-05 | 5.2 |
| 74 | 0.0197 | 0.2961 | 0.2995 | 0.3045 (ep 48) | 9.32e-05 | 5.1 |
| 73 | 0.0198 | 0.2959 | 0.3003 | 0.3045 (ep 48) | 9.97e-05 | 5.2 |
| 72 | 0.0199 | 0.2974 | 0.3006 | 0.3045 (ep 48) | 1.06e-04 | 5.2 |
| 71 | 0.0200 | 0.2976 | 0.3008 | 0.3045 (ep 48) | 1.13e-04 | 5.2 |
| 70 | 0.0202 | 0.2978 | 0.3008 | 0.3045 (ep 48) | 1.20e-04 | 5.1 |
| 69 | 0.0204 | 0.2960 | 0.3010 | 0.3045 (ep 48) | 1.27e-04 | 5.2 |
| 68 | 0.0205 | 0.2989 | 0.3015 | 0.3045 (ep 48) | 1.35e-04 | 5.2 |
| 67 | 0.0206 | 0.2984 | 0.3022 | 0.3045 (ep 48) | 1.42e-04 | 5.2 |
| 66 | 0.0208 | 0.2965 | 0.3024 | 0.3045 (ep 48) | 1.50e-04 | 5.2 |
| 65 | 0.0209 | 0.2984 | 0.3028 | 0.3045 (ep 48) | 1.57e-04 | 5.1 |
| 64 | 0.0211 | 0.2968 | 0.3035 | 0.3045 (ep 48) | 1.65e-04 | 5.1 |
| 63 | 0.0213 | 0.3008 | 0.3042 | 0.3045 (ep 48) | 1.73e-04 | 5.1 |
| 62 | 0.0215 | 0.2988 | 0.3042 | 0.3045 (ep 48) | 1.81e-04 | 5.1 |
| 61 | 0.0216 | 0.2976 | 0.3049 | 0.3045 (ep 48) | 1.89e-04 | 5.2 |
| 60 | 0.0218 | 0.3019 | 0.3051 | 0.3045 (ep 48) | 1.97e-04 | 5.2 |
| 59 | 0.0220 | 0.2999 | 0.3056 | 0.3045 (ep 48) | 2.05e-04 | 5.2 |
| 58 | 0.0222 | 0.3002 | 0.3059 | 0.3045 (ep 48) | 2.13e-04 | 5.2 |
| 57 | 0.0224 | 0.2986 | 0.3064 | 0.3045 (ep 48) | 2.21e-04 | 5.1 |
| 56 | 0.0226 | 0.2992 | 0.3066 | 0.3045 (ep 48) | 2.29e-04 | 5.2 |
| 55 | 0.0228 | 0.2992 | 0.3063 | 0.3045 (ep 48) | 2.38e-04 | 5.1 |
| 54 | 0.0230 | 0.3017 | 0.3076 | 0.3045 (ep 48) | 2.46e-04 | 5.1 |
| 53 | 0.0232 | 0.3007 | 0.3084 | 0.3045 (ep 48) | 2.54e-04 | 5.1 |
| 52 | 0.0234 | 0.3026 | 0.3094 | 0.3045 (ep 48) | 2.62e-04 | 5.1 |
| 51 | 0.0236 | 0.3037 | 0.3094 | 0.3045 (ep 48) | 2.71e-04 | 5.1 |
| 50 | 0.0238 | 0.3010 | 0.3103 | 0.3045 (ep 48) | 2.79e-04 | 5.1 |
| 49 | 0.0240 | 0.3024 | 0.3103 | 0.3045 (ep 48) | 2.87e-04 | 5.1 |
| 48 | 0.0242 | 0.3045 ⭐ | 0.3098 | 0.3045 (ep 48) | 2.95e-04 | 5.1 |
| 47 | 0.0244 | 0.2988 | 0.3096 | 0.3026 (ep 33) | 3.03e-04 | 5.2 |
| 46 | 0.0247 | 0.3015 | 0.3095 | 0.3026 (ep 33) | 3.11e-04 | 5.2 |
| 45 | 0.0249 | 0.2967 | 0.3103 | 0.3026 (ep 33) | 3.19e-04 | 5.1 |
| 44 | 0.0251 | 0.2990 | 0.3098 | 0.3026 (ep 33) | 3.27e-04 | 5.1 |
| 43 | 0.0254 | 0.3001 | 0.3109 | 0.3026 (ep 33) | 3.35e-04 | 5.2 |
| 42 | 0.0256 | 0.3020 | 0.3110 | 0.3026 (ep 33) | 3.43e-04 | 5.1 |
| 41 | 0.0259 | 0.3013 | 0.3118 | 0.3026 (ep 33) | 3.50e-04 | 5.2 |
| 40 | 0.0261 | 0.2997 | 0.3118 | 0.3026 (ep 33) | 3.58e-04 | 5.1 |
| 39 | 0.0262 | 0.3004 | 0.3110 | 0.3026 (ep 33) | 3.65e-04 | 5.1 |
| 38 | 0.0265 | 0.3024 | 0.3108 | 0.3026 (ep 33) | 3.73e-04 | 5.1 |
| 37 | 0.0268 | 0.3007 | 0.3111 | 0.3026 (ep 33) | 3.80e-04 | 5.1 |
| 36 | 0.0270 | 0.3006 | 0.3097 | 0.3026 (ep 33) | 3.87e-04 | 5.2 |
| 35 | 0.0273 | 0.3008 | 0.3095 | 0.3026 (ep 33) | 3.94e-04 | 5.1 |
| 34 | 0.0275 | 0.2967 | 0.3101 | 0.3026 (ep 33) | 4.00e-04 | 5.1 |
| 33 | 0.0279 | 0.3026 ⭐ | 0.3094 | 0.3026 (ep 33) | 4.07e-04 | 5.1 |
| 32 | 0.0282 | 0.2956 | 0.3097 | 0.3009 (ep 31) | 4.13e-04 | 5.2 |
| 31 | 0.0284 | 0.3009 ⭐ | 0.3082 | 0.3009 (ep 31) | 4.19e-04 | 5.2 |
| 30 | 0.0287 | 0.2979 ⭐ | 0.3070 | 0.2979 (ep 30) | 4.25e-04 | 5.1 |
| 29 | 0.0289 | 0.2941 | 0.3057 | 0.2972 (ep 28) | 4.31e-04 | 5.1 |
| 28 | 0.0292 | 0.2972 ⭐ | 0.3048 | 0.2972 (ep 28) | 4.37e-04 | 5.2 |
| 27 | 0.0295 | 0.2898 | 0.3022 | 0.2900 (ep 26) | 4.42e-04 | 5.1 |
| 26 | 0.0299 | 0.2900 ⭐ | 0.2992 | 0.2900 (ep 26) | 4.47e-04 | 5.1 |
| 25 | 0.0302 | 0.2868 | 0.2979 | 0.2874 (ep 24) | 4.52e-04 | 5.1 |
| 24 | 0.0305 | 0.2874 ⭐ | 0.2960 | 0.2874 (ep 24) | 4.57e-04 | 5.2 |
| 23 | 0.0309 | 0.2835 | 0.2935 | 0.2871 (ep 22) | 4.62e-04 | 5.1 |
| 22 | 0.0312 | 0.2871 ⭐ | 0.2911 | 0.2871 (ep 22) | 4.66e-04 | 5.2 |
| 21 | 0.0317 | 0.2803 ⭐ | 0.2896 | 0.2803 (ep 21) | 4.70e-04 | 5.2 |
| 20 | 0.0323 | 0.2780 ⭐ | 0.2861 | 0.2780 (ep 20) | 4.74e-04 | 5.2 |
| 19 | 0.0325 | 0.2719 ⭐ | 0.2800 | 0.2719 (ep 19) | 4.77e-04 | 5.1 |
| 18 | 0.0330 | 0.2685 ⭐ | 0.2758 | 0.2685 (ep 18) | 4.81e-04 | 5.2 |
| 17 | 0.0335 | 0.2632 ⭐ | 0.2720 | 0.2632 (ep 17) | 4.84e-04 | 5.1 |
| 16 | 0.0340 | 0.2512 | 0.2696 | 0.2563 (ep 15) | 4.86e-04 | 5.2 |
| 15 | 0.0346 | 0.2563 ⭐ | 0.2635 | 0.2563 (ep 15) | 4.89e-04 | 5.2 |
| 14 | 0.0352 | 0.2384 | 0.2582 | 0.2387 (ep 13) | 4.91e-04 | 5.1 |
| 13 | 0.0359 | 0.2387 ⭐ | 0.2533 | 0.2387 (ep 13) | 4.93e-04 | 5.2 |
| 12 | 0.0366 | 0.2368 ⭐ | 0.2468 | 0.2368 (ep 12) | 4.95e-04 | 5.1 |
| 11 | 0.0374 | 0.2275 ⭐ | 0.2367 | 0.2275 (ep 11) | 4.97e-04 | 5.2 |
| 10 | 0.0382 | 0.2144 ⭐ | 0.2265 | 0.2144 (ep 10) | 4.98e-04 | 5.1 |
| 9 | 0.0390 | 0.2071 ⭐ | 0.2145 | 0.2071 (ep 9) | 4.99e-04 | 5.1 |
| 8 | 0.0400 | 0.1947 ⭐ | 0.1987 | 0.1947 (ep 8) | 4.99e-04 | 5.2 |
| 7 | 0.0413 | 0.1774 ⭐ | 0.1811 | 0.1774 (ep 7) | 5.00e-04 | 5.1 |
| 6 | 0.0430 | 0.1605 ⭐ | 0.1594 | 0.1605 (ep 6) | 5.00e-04 | 5.1 |
| 5 | 0.0451 | 0.1398 ⭐ | 0.1325 | 0.1398 (ep 5) | 4.00e-04 | 5.2 |
| 4 | 0.0490 | 0.1133 ⭐ | 0.0999 | 0.1133 (ep 4) | 3.00e-04 | 5.2 |
| 3 | 0.0675 | 0.0721 ⭐ | 0.0658 | 0.0721 (ep 3) | 2.00e-04 | 5.2 |
| 2 | 0.3289 | 0.0422 ⭐ | 0.0405 | 0.0422 (ep 2) | 1.00e-04 | 5.1 |
| 1 | 0.6957 | 0.0249 ⭐ | 0.0249 | 0.0249 (ep 1) | 5.00e-10 | 5.2 |

## Last 80 log lines

_The log counts epochs from 0; the tables above count from 1._

```
RWSE loaded from cache
graphs: total 437,929 | train 350,343 | val 43,793 | test 43,793 | ready in 2s
steps/epoch: train 685, val 86, test 86
--- cell 6 ---
PairHGT: GPS + pair channel (pair bias + write-back, value gate) [arm PairHGT]: 9,751,972 parameters = baseline 9,744,860 + 7,112 (0.07%), of which the pair channel 7,112
parameter count matches the expected 9,751,972 for arm PairHGT
--- cell 7 ---
--- cell 9 ---
--- cell 10 ---
--- cell 12 ---
RUN_DEBUG_FIRST is False: smoke test skipped.
--- cell 14 ---
Restored 0 seed folder(s).
prereg.json checked: configuration identical (hash 9171049c2c7acf57); seeds [101, 202, 323, 432, 543]
[seed 432] RESUMED from epoch 68/100 (lr 1.27e-04, best val AP so far 0.3045)
[seed 432] epoch  69/100 | lr 1.27e-04 | train BCE 0.0204 | val AP 0.2960 | best val 0.3045 @ep48 | EMA val 0.3010 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.7h
[seed 432] epoch  70/100 | lr 1.20e-04 | train BCE 0.0202 | val AP 0.2978 | best val 0.3045 @ep48 | EMA val 0.3008 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.6h
[seed 432] epoch  71/100 | lr 1.13e-04 | train BCE 0.0200 | val AP 0.2976 | best val 0.3045 @ep48 | EMA val 0.3008 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 2.5h
[seed 432] epoch  72/100 | lr 1.06e-04 | train BCE 0.0199 | val AP 0.2974 | best val 0.3045 @ep48 | EMA val 0.3006 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.4h
[seed 432] epoch  73/100 | lr 9.97e-05 | train BCE 0.0198 | val AP 0.2959 | best val 0.3045 @ep48 | EMA val 0.3003 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 2.3h
[seed 432] epoch  74/100 | lr 9.32e-05 | train BCE 0.0197 | val AP 0.2961 | best val 0.3045 @ep48 | EMA val 0.2995 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.2h
[seed 432] epoch  75/100 | lr 8.69e-05 | train BCE 0.0195 | val AP 0.2953 | best val 0.3045 @ep48 | EMA val 0.2993 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 2.1h
[seed 432] epoch  76/100 | lr 8.07e-05 | train BCE 0.0194 | val AP 0.2955 | best val 0.3045 @ep48 | EMA val 0.2987 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.1h
[seed 432] epoch  77/100 | lr 7.47e-05 | train BCE 0.0193 | val AP 0.2952 | best val 0.3045 @ep48 | EMA val 0.2979 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.0h
[seed 432] epoch  78/100 | lr 6.89e-05 | train BCE 0.0192 | val AP 0.2962 | best val 0.3045 @ep48 | EMA val 0.2981 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.9h
[seed 432] epoch  79/100 | lr 6.33e-05 | train BCE 0.0191 | val AP 0.2955 | best val 0.3045 @ep48 | EMA val 0.2979 | 310s (train 276s, eval 34s) | GPU max 89C | ETA<= 1.8h
[seed 432] epoch  80/100 | lr 5.79e-05 | train BCE 0.0190 | val AP 0.2972 | best val 0.3045 @ep48 | EMA val 0.2977 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.7h
[seed 432] epoch  81/100 | lr 5.27e-05 | train BCE 0.0189 | val AP 0.2968 | best val 0.3045 @ep48 | EMA val 0.2976 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.6h
[seed 432] epoch  82/100 | lr 4.77e-05 | train BCE 0.0188 | val AP 0.2956 | best val 0.3045 @ep48 | EMA val 0.2976 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.5h
[seed 432] epoch  83/100 | lr 4.30e-05 | train BCE 0.0187 | val AP 0.2950 | best val 0.3045 @ep48 | EMA val 0.2973 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.5h
[seed 432] epoch  84/100 | lr 3.85e-05 | train BCE 0.0186 | val AP 0.2951 | best val 0.3045 @ep48 | EMA val 0.2967 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.4h
[seed 432] epoch  85/100 | lr 3.42e-05 | train BCE 0.0186 | val AP 0.2953 | best val 0.3045 @ep48 | EMA val 0.2964 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.3h
[seed 432] epoch  86/100 | lr 3.01e-05 | train BCE 0.0185 | val AP 0.2954 | best val 0.3045 @ep48 | EMA val 0.2961 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.2h
[seed 432] epoch  87/100 | lr 2.63e-05 | train BCE 0.0185 | val AP 0.2950 | best val 0.3045 @ep48 | EMA val 0.2962 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.1h
[seed 432] epoch  88/100 | lr 2.27e-05 | train BCE 0.0184 | val AP 0.2950 | best val 0.3045 @ep48 | EMA val 0.2959 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 1.0h
[seed 432] epoch  89/100 | lr 1.94e-05 | train BCE 0.0183 | val AP 0.2951 | best val 0.3045 @ep48 | EMA val 0.2959 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 0.9h
[seed 432] epoch  90/100 | lr 1.64e-05 | train BCE 0.0183 | val AP 0.2942 | best val 0.3045 @ep48 | EMA val 0.2957 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.9h
[seed 432] epoch  91/100 | lr 1.35e-05 | train BCE 0.0183 | val AP 0.2944 | best val 0.3045 @ep48 | EMA val 0.2956 | 310s (train 276s, eval 34s) | GPU max 89C | ETA<= 0.8h
[seed 432] epoch  92/100 | lr 1.10e-05 | train BCE 0.0182 | val AP 0.2945 | best val 0.3045 @ep48 | EMA val 0.2953 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.7h
[seed 432] epoch  93/100 | lr 8.70e-06 | train BCE 0.0182 | val AP 0.2947 | best val 0.3045 @ep48 | EMA val 0.2952 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.6h
[seed 432] epoch  94/100 | lr 6.67e-06 | train BCE 0.0182 | val AP 0.2946 | best val 0.3045 @ep48 | EMA val 0.2951 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.5h
[seed 432] epoch  95/100 | lr 4.91e-06 | train BCE 0.0182 | val AP 0.2953 | best val 0.3045 @ep48 | EMA val 0.2952 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.4h
[seed 432] epoch  96/100 | lr 3.41e-06 | train BCE 0.0182 | val AP 0.2948 | best val 0.3045 @ep48 | EMA val 0.2952 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.3h
[seed 432] epoch  97/100 | lr 2.18e-06 | train BCE 0.0181 | val AP 0.2951 | best val 0.3045 @ep48 | EMA val 0.2951 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.3h
[seed 432] epoch  98/100 | lr 1.23e-06 | train BCE 0.0181 | val AP 0.2947 | best val 0.3045 @ep48 | EMA val 0.2951 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.2h
[seed 432] epoch  99/100 | lr 5.47e-07 | train BCE 0.0181 | val AP 0.2948 | best val 0.3045 @ep48 | EMA val 0.2951 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.1h
[seed 432] epoch 100/100 | lr 1.37e-07 | train BCE 0.0181 | val AP 0.2949 | best val 0.3045 @ep48 | EMA val 0.2950 | 310s (train 276s, eval 34s) | GPU max 89C | ETA<= 0.0h
[seed 432] FINAL TEST (evaluated once): raw epoch 48 val 0.3045 test 0.2982 | EMA epoch 41 val 0.3118 test 0.3119
--- cell 16 ---
PairHGT: GPS + pair channel (pair bias + write-back, value gate) [arm PairHGT] | gps_conf_PairHGT_ep100_molpcba
 seed  epochs  raw_epoch  raw_val  raw_test  ema_epoch  ema_val  ema_test  hours  train_s_per_epoch  total_s_per_epoch
  101 100/100         39   0.3056    0.2943         40   0.3131    0.3043 8.6342           276.5795           310.8298
  202 100/100         62   0.3036    0.2963         48   0.3097    0.3062 8.5534           274.3556           307.9222
  323 100/100         50   0.3005    0.2967         45   0.3065    0.3050 8.5744           275.0306           308.6781
  432 100/100         48   0.3045    0.2982         41   0.3118    0.3119 8.5831           275.2999           308.9923
  543  68/100         39   0.3028       NaN         35   0.3090       NaN 5.8397           275.4424           309.1600
mean ± sample SD (ddof=1) over 4 seed(s): raw test 0.2964 ± 0.0016 | EMA test 0.3068 ± 0.0035
A mean ± SD over fewer than 3 seeds is only a description; do not call it a confidence interval.
run manifest: 10 row(s) -> /home/student/thesis/outputs/pairhgt/outputs/confirmatory/run_manifest.csv
    model              gpu  seeds  params  train_s_per_epoch  val_eval_s_per_epoch  total_s_per_epoch  hours_per_seed  time_vs_GPS+EMA
GPS + EMA NVIDIA RTX A4000      5 9744860             160.70                 15.83             176.55            4.90             1.00
  PairHGT NVIDIA RTX A4000      5 9751972             275.34                 33.75             309.12            8.04             1.75
train = training steps incl. EMA update; val_eval = validation of raw + EMA weights; no test pass inside an epoch (protocol v2). Do not compare with timings from the exploratory runs.
--- cell 18 ---
=== PairHGT  minus  GPS + EMA   (100 epochs, matched seeds) ===
 seed  raw_val  ema_val  raw_test  ema_test
  101   0.0013   0.0027    0.0043    0.0048
  202   0.0017   0.0012    0.0067    0.0115
  323   0.0021   0.0022    0.0019    0.0056
  432   0.0017   0.0035    0.0066    0.0120
  validation AP, raw    : mean +0.0017, sample SD 0.0004, per-seed [0.0013, 0.0017, 0.0021, 0.0017], all positive: True | 95% t-interval [+0.0011, +0.0023] (n=4, t=9.44)
  validation AP, EMA    : mean +0.0024, sample SD 0.0009, per-seed [0.0027, 0.0012, 0.0022, 0.0035], all positive: True | 95% t-interval [+0.0009, +0.0039] (n=4, t=5.08)
  test AP, raw vs raw   : mean +0.0049, sample SD 0.0023, per-seed [0.0043, 0.0067, 0.0019, 0.0066], all positive: True | 95% t-interval [+0.0013, +0.0085] (n=4, t=4.30)
  test AP, EMA vs EMA   : mean +0.0085, sample SD 0.0038, per-seed [0.0048, 0.0115, 0.0056, 0.012], all positive: True | 95% t-interval [+0.0024, +0.0146] (n=4, t=4.42)
  Reading: 4 matched seed(s). The claim is limited to whether the direction of the EMA-vs-EMA difference repeats; a significance claim needs many more seeds.
Planning table (80% power, alpha 0.05, two-sample t, test AP): smallest detectable true difference
  per-seed SD 0.003: n=3: 0.0092, n=5: 0.0061, n=10: 0.0040, n=20: 0.0027
  per-seed SD 0.0056: n=3: 0.0172, n=5: 0.0113, n=10: 0.0074, n=20: 0.0051
--- cell 20 ---
===== 2026-11-13 23:35:59 notebook turn ended (exit 0); executed notebook: /home/student/thesis/outputs/lab_runs/notebooks/pairhgt_PairHGT_seed432_20261113-2049.ipynb =====
```
