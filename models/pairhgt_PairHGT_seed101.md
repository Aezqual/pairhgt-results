# PairHGT — seed 101

[← all models](../README.md) · PairHGT notebook · ogbg-molpcba

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation AP | **0.3056** at epoch 39 |
| Best validation AP, EMA weights | 0.3131 at epoch 40 |
| Test AP | raw 0.2943 / ema 0.3043 (final) |
| Seed | 101 |
| Parameters | 9,751,972 |
| Minutes per epoch (last 5, incl. validation) | 5.2 |
| Training time so far | 8.6 h |
| Training time left | done |
| Sessions (start + resumes) | 2 |
| Hottest GPU reading | 89.0 °C |
| Last update | 2026-11-11 18:57 (71.2 h ago) |

![curves](pairhgt_PairHGT_seed101.png)

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
| raw | 39 | 0.3056 | 0.2943 |
| ema | 40 | 0.3131 | 0.3043 |

## Every epoch (newest first)

| Epoch | Train loss | Val AP | Val AP (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0175 | 0.2939 | 0.2939 | 0.3056 (ep 39) | 1.37e-07 | 5.1 |
| 99 | 0.0175 | 0.2937 | 0.2940 | 0.3056 (ep 39) | 5.47e-07 | 5.2 |
| 98 | 0.0175 | 0.2939 | 0.2942 | 0.3056 (ep 39) | 1.23e-06 | 5.2 |
| 97 | 0.0175 | 0.2936 | 0.2944 | 0.3056 (ep 39) | 2.18e-06 | 5.1 |
| 96 | 0.0175 | 0.2938 | 0.2944 | 0.3056 (ep 39) | 3.41e-06 | 5.1 |
| 95 | 0.0175 | 0.2931 | 0.2945 | 0.3056 (ep 39) | 4.91e-06 | 5.2 |
| 94 | 0.0175 | 0.2944 | 0.2945 | 0.3056 (ep 39) | 6.67e-06 | 5.1 |
| 93 | 0.0176 | 0.2942 | 0.2945 | 0.3056 (ep 39) | 8.70e-06 | 5.2 |
| 92 | 0.0176 | 0.2940 | 0.2944 | 0.3056 (ep 39) | 1.10e-05 | 5.1 |
| 91 | 0.0176 | 0.2944 | 0.2945 | 0.3056 (ep 39) | 1.35e-05 | 5.1 |
| 90 | 0.0177 | 0.2942 | 0.2946 | 0.3056 (ep 39) | 1.64e-05 | 5.1 |
| 89 | 0.0177 | 0.2944 | 0.2948 | 0.3056 (ep 39) | 1.94e-05 | 5.1 |
| 88 | 0.0178 | 0.2934 | 0.2949 | 0.3056 (ep 39) | 2.27e-05 | 5.1 |
| 87 | 0.0178 | 0.2946 | 0.2947 | 0.3056 (ep 39) | 2.63e-05 | 5.1 |
| 86 | 0.0179 | 0.2943 | 0.2949 | 0.3056 (ep 39) | 3.01e-05 | 5.1 |
| 85 | 0.0179 | 0.2931 | 0.2953 | 0.3056 (ep 39) | 3.42e-05 | 5.1 |
| 84 | 0.0180 | 0.2953 | 0.2956 | 0.3056 (ep 39) | 3.85e-05 | 5.1 |
| 83 | 0.0181 | 0.2947 | 0.2958 | 0.3056 (ep 39) | 4.30e-05 | 5.1 |
| 82 | 0.0182 | 0.2950 | 0.2957 | 0.3056 (ep 39) | 4.77e-05 | 5.1 |
| 81 | 0.0183 | 0.2942 | 0.2955 | 0.3056 (ep 39) | 5.27e-05 | 5.1 |
| 80 | 0.0184 | 0.2951 | 0.2953 | 0.3056 (ep 39) | 5.79e-05 | 5.1 |
| 79 | 0.0184 | 0.2945 | 0.2955 | 0.3056 (ep 39) | 6.33e-05 | 5.1 |
| 78 | 0.0186 | 0.2950 | 0.2956 | 0.3056 (ep 39) | 6.89e-05 | 5.1 |
| 77 | 0.0187 | 0.2949 | 0.2953 | 0.3056 (ep 39) | 7.47e-05 | 5.1 |
| 76 | 0.0188 | 0.2928 | 0.2955 | 0.3056 (ep 39) | 8.07e-05 | 5.1 |
| 75 | 0.0189 | 0.2915 | 0.2962 | 0.3056 (ep 39) | 8.69e-05 | 5.1 |
| 74 | 0.0190 | 0.2927 | 0.2970 | 0.3056 (ep 39) | 9.32e-05 | 5.1 |
| 73 | 0.0192 | 0.2944 | 0.2976 | 0.3056 (ep 39) | 9.97e-05 | 5.1 |
| 72 | 0.0193 | 0.2957 | 0.2982 | 0.3056 (ep 39) | 1.06e-04 | 5.1 |
| 71 | 0.0194 | 0.2953 | 0.2986 | 0.3056 (ep 39) | 1.13e-04 | 5.1 |
| 70 | 0.0196 | 0.2958 | 0.2997 | 0.3056 (ep 39) | 1.20e-04 | 5.1 |
| 69 | 0.0197 | 0.2969 | 0.3005 | 0.3056 (ep 39) | 1.27e-04 | 5.1 |
| 68 | 0.0199 | 0.2971 | 0.3010 | 0.3056 (ep 39) | 1.35e-04 | 5.1 |
| 67 | 0.0201 | 0.2962 | 0.3002 | 0.3056 (ep 39) | 1.42e-04 | 5.1 |
| 66 | 0.0202 | 0.2958 | 0.3007 | 0.3056 (ep 39) | 1.50e-04 | 5.1 |
| 65 | 0.0204 | 0.2973 | 0.3010 | 0.3056 (ep 39) | 1.57e-04 | 5.1 |
| 64 | 0.0206 | 0.2933 | 0.3014 | 0.3056 (ep 39) | 1.65e-04 | 5.2 |
| 63 | 0.0207 | 0.2993 | 0.3028 | 0.3056 (ep 39) | 1.73e-04 | 5.1 |
| 62 | 0.0209 | 0.2963 | 0.3029 | 0.3056 (ep 39) | 1.81e-04 | 5.2 |
| 61 | 0.0211 | 0.2970 | 0.3046 | 0.3056 (ep 39) | 1.89e-04 | 5.1 |
| 60 | 0.0213 | 0.2955 | 0.3049 | 0.3056 (ep 39) | 1.97e-04 | 5.1 |
| 59 | 0.0214 | 0.2976 | 0.3053 | 0.3056 (ep 39) | 2.05e-04 | 5.1 |
| 58 | 0.0216 | 0.2972 | 0.3060 | 0.3056 (ep 39) | 2.13e-04 | 5.1 |
| 57 | 0.0219 | 0.2997 | 0.3063 | 0.3056 (ep 39) | 2.21e-04 | 5.2 |
| 56 | 0.0221 | 0.2953 | 0.3075 | 0.3056 (ep 39) | 2.29e-04 | 5.1 |
| 55 | 0.0223 | 0.2982 | 0.3086 | 0.3056 (ep 39) | 2.38e-04 | 5.2 |
| 54 | 0.0225 | 0.3025 | 0.3088 | 0.3056 (ep 39) | 2.46e-04 | 5.2 |
| 53 | 0.0227 | 0.3032 | 0.3082 | 0.3056 (ep 39) | 2.54e-04 | 5.1 |
| 52 | 0.0229 | 0.3012 | 0.3079 | 0.3056 (ep 39) | 2.62e-04 | 5.1 |
| 51 | 0.0231 | 0.2999 | 0.3080 | 0.3056 (ep 39) | 2.71e-04 | 5.2 |
| 50 | 0.0234 | 0.2988 | 0.3083 | 0.3056 (ep 39) | 2.79e-04 | 5.2 |
| 49 | 0.0235 | 0.3003 | 0.3080 | 0.3056 (ep 39) | 2.87e-04 | 5.1 |
| 48 | 0.0238 | 0.3002 | 0.3083 | 0.3056 (ep 39) | 2.95e-04 | 5.1 |
| 47 | 0.0240 | 0.2985 | 0.3096 | 0.3056 (ep 39) | 3.03e-04 | 5.2 |
| 46 | 0.0242 | 0.2995 | 0.3111 | 0.3056 (ep 39) | 3.11e-04 | 5.2 |
| 45 | 0.0245 | 0.3023 | 0.3114 | 0.3056 (ep 39) | 3.19e-04 | 5.2 |
| 44 | 0.0247 | 0.3041 | 0.3120 | 0.3056 (ep 39) | 3.27e-04 | 5.1 |
| 43 | 0.0249 | 0.3005 | 0.3118 | 0.3056 (ep 39) | 3.35e-04 | 5.2 |
| 42 | 0.0252 | 0.3003 | 0.3123 | 0.3056 (ep 39) | 3.43e-04 | 5.2 |
| 41 | 0.0254 | 0.3029 | 0.3119 | 0.3056 (ep 39) | 3.50e-04 | 5.2 |
| 40 | 0.0257 | 0.2992 | 0.3131 | 0.3056 (ep 39) | 3.58e-04 | 5.2 |
| 39 | 0.0260 | 0.3056 ⭐ | 0.3125 | 0.3056 (ep 39) | 3.65e-04 | 5.3 |
| 38 | 0.0262 | 0.3000 | 0.3114 | 0.3004 (ep 34) | 3.73e-04 | 5.2 |
| 37 | 0.0264 | 0.2944 | 0.3107 | 0.3004 (ep 34) | 3.80e-04 | 5.2 |
| 36 | 0.0267 | 0.2961 | 0.3100 | 0.3004 (ep 34) | 3.87e-04 | 5.2 |
| 35 | 0.0269 | 0.2986 | 0.3112 | 0.3004 (ep 34) | 3.94e-04 | 5.3 |
| 34 | 0.0272 | 0.3004 ⭐ | 0.3109 | 0.3004 (ep 34) | 4.00e-04 | 5.2 |
| 33 | 0.0275 | 0.3000 ⭐ | 0.3098 | 0.3000 (ep 33) | 4.07e-04 | 5.2 |
| 32 | 0.0278 | 0.2926 | 0.3096 | 0.2946 (ep 27) | 4.13e-04 | 5.2 |
| 31 | 0.0281 | 0.2941 | 0.3082 | 0.2946 (ep 27) | 4.19e-04 | 5.2 |
| 30 | 0.0283 | 0.2934 | 0.3070 | 0.2946 (ep 27) | 4.25e-04 | 5.2 |
| 29 | 0.0286 | 0.2936 | 0.3056 | 0.2946 (ep 27) | 4.31e-04 | 5.2 |
| 28 | 0.0289 | 0.2922 | 0.3054 | 0.2946 (ep 27) | 4.37e-04 | 5.2 |
| 27 | 0.0293 | 0.2946 ⭐ | 0.3036 | 0.2946 (ep 27) | 4.42e-04 | 5.3 |
| 26 | 0.0296 | 0.2875 ⭐ | 0.3029 | 0.2875 (ep 26) | 4.47e-04 | 5.3 |
| 25 | 0.0299 | 0.2874 ⭐ | 0.3013 | 0.2874 (ep 25) | 4.52e-04 | 5.3 |
| 24 | 0.0303 | 0.2873 ⭐ | 0.2987 | 0.2873 (ep 24) | 4.57e-04 | 5.2 |
| 23 | 0.0307 | 0.2840 ⭐ | 0.2957 | 0.2840 (ep 23) | 4.62e-04 | 5.2 |
| 22 | 0.0310 | 0.2828 | 0.2924 | 0.2829 (ep 21) | 4.66e-04 | 5.3 |
| 21 | 0.0315 | 0.2829 ⭐ | 0.2908 | 0.2829 (ep 21) | 4.70e-04 | 5.2 |
| 20 | 0.0319 | 0.2706 | 0.2883 | 0.2715 (ep 19) | 4.74e-04 | 5.2 |
| 19 | 0.0324 | 0.2715 ⭐ | 0.2847 | 0.2715 (ep 19) | 4.77e-04 | 5.2 |
| 18 | 0.0328 | 0.2646 ⭐ | 0.2791 | 0.2646 (ep 18) | 4.81e-04 | 5.3 |
| 17 | 0.0333 | 0.2612 ⭐ | 0.2750 | 0.2612 (ep 17) | 4.84e-04 | 5.2 |
| 16 | 0.0338 | 0.2545 ⭐ | 0.2708 | 0.2545 (ep 16) | 4.86e-04 | 5.2 |
| 15 | 0.0345 | 0.2497 | 0.2655 | 0.2500 (ep 13) | 4.89e-04 | 5.2 |
| 14 | 0.0352 | 0.2417 | 0.2587 | 0.2500 (ep 13) | 4.91e-04 | 5.2 |
| 13 | 0.0358 | 0.2500 ⭐ | 0.2542 | 0.2500 (ep 13) | 4.93e-04 | 5.2 |
| 12 | 0.0365 | 0.2376 ⭐ | 0.2470 | 0.2376 (ep 12) | 4.95e-04 | 5.2 |
| 11 | 0.0373 | 0.2308 ⭐ | 0.2392 | 0.2308 (ep 11) | 4.97e-04 | 5.2 |
| 10 | 0.0380 | 0.2188 ⭐ | 0.2306 | 0.2188 (ep 10) | 4.98e-04 | 5.2 |
| 9 | 0.0389 | 0.2107 ⭐ | 0.2177 | 0.2107 (ep 9) | 4.99e-04 | 5.3 |
| 8 | 0.0399 | 0.1950 ⭐ | 0.2024 | 0.1950 (ep 8) | 4.99e-04 | 5.3 |
| 7 | 0.0412 | 0.1758 ⭐ | 0.1857 | 0.1758 (ep 7) | 5.00e-04 | 5.2 |
| 6 | 0.0428 | 0.1601 ⭐ | 0.1630 | 0.1601 (ep 6) | 5.00e-04 | 5.2 |
| 5 | 0.0448 | 0.1433 ⭐ | 0.1382 | 0.1433 (ep 5) | 4.00e-04 | 5.2 |
| 4 | 0.0483 | 0.1171 ⭐ | 0.1043 | 0.1171 (ep 4) | 3.00e-04 | 5.2 |
| 3 | 0.0684 | 0.0734 ⭐ | 0.0674 | 0.0734 (ep 3) | 2.00e-04 | 5.2 |
| 2 | 0.3427 | 0.0441 ⭐ | 0.0408 | 0.0441 (ep 2) | 1.00e-04 | 5.2 |
| 1 | 0.6966 | 0.0264 ⭐ | 0.0264 | 0.0264 (ep 1) | 5.00e-10 | 5.2 |

## Last 80 log lines

_The log counts epochs from 0; the tables above count from 1._

```
Thermal check: GPU at 75 C now | pause above 95 C, resume below 88 C
--- cell 5 ---
Dataset cache already present: /home/student/thesis/outputs/pairhgt/data/ogb/ogbg_molpcba
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
[seed 101] RESUMED from epoch 67/100 (lr 1.35e-04, best val AP so far 0.3056)
[seed 101] epoch  68/100 | lr 1.35e-04 | train BCE 0.0199 | val AP 0.2971 | best val 0.3056 @ep39 | EMA val 0.3010 | 308s (train 274s, eval 34s) | GPU max 88C | ETA<= 2.7h
[seed 101] epoch  69/100 | lr 1.27e-04 | train BCE 0.0197 | val AP 0.2969 | best val 0.3056 @ep39 | EMA val 0.3005 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.7h
[seed 101] epoch  70/100 | lr 1.20e-04 | train BCE 0.0196 | val AP 0.2958 | best val 0.3056 @ep39 | EMA val 0.2997 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.6h
[seed 101] epoch  71/100 | lr 1.13e-04 | train BCE 0.0194 | val AP 0.2953 | best val 0.3056 @ep39 | EMA val 0.2986 | 308s (train 274s, eval 34s) | GPU max 88C | ETA<= 2.5h
[seed 101] epoch  72/100 | lr 1.06e-04 | train BCE 0.0193 | val AP 0.2957 | best val 0.3056 @ep39 | EMA val 0.2982 | 308s (train 274s, eval 34s) | GPU max 88C | ETA<= 2.4h
[seed 101] epoch  73/100 | lr 9.97e-05 | train BCE 0.0192 | val AP 0.2944 | best val 0.3056 @ep39 | EMA val 0.2976 | 308s (train 275s, eval 34s) | GPU max 88C | ETA<= 2.3h
[seed 101] epoch  74/100 | lr 9.32e-05 | train BCE 0.0190 | val AP 0.2927 | best val 0.3056 @ep39 | EMA val 0.2970 | 308s (train 274s, eval 34s) | GPU max 88C | ETA<= 2.2h
[seed 101] epoch  75/100 | lr 8.69e-05 | train BCE 0.0189 | val AP 0.2915 | best val 0.3056 @ep39 | EMA val 0.2962 | 308s (train 275s, eval 34s) | GPU max 88C | ETA<= 2.1h
[seed 101] epoch  76/100 | lr 8.07e-05 | train BCE 0.0188 | val AP 0.2928 | best val 0.3056 @ep39 | EMA val 0.2955 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.1h
[seed 101] epoch  77/100 | lr 7.47e-05 | train BCE 0.0187 | val AP 0.2949 | best val 0.3056 @ep39 | EMA val 0.2953 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.0h
[seed 101] epoch  78/100 | lr 6.89e-05 | train BCE 0.0186 | val AP 0.2950 | best val 0.3056 @ep39 | EMA val 0.2956 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.9h
[seed 101] epoch  79/100 | lr 6.33e-05 | train BCE 0.0184 | val AP 0.2945 | best val 0.3056 @ep39 | EMA val 0.2955 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.8h
[seed 101] epoch  80/100 | lr 5.79e-05 | train BCE 0.0184 | val AP 0.2951 | best val 0.3056 @ep39 | EMA val 0.2953 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.7h
[seed 101] epoch  81/100 | lr 5.27e-05 | train BCE 0.0183 | val AP 0.2942 | best val 0.3056 @ep39 | EMA val 0.2955 | 308s (train 275s, eval 34s) | GPU max 88C | ETA<= 1.6h
[seed 101] epoch  82/100 | lr 4.77e-05 | train BCE 0.0182 | val AP 0.2950 | best val 0.3056 @ep39 | EMA val 0.2957 | 309s (train 275s, eval 34s) | GPU max 88C | ETA<= 1.5h
[seed 101] epoch  83/100 | lr 4.30e-05 | train BCE 0.0181 | val AP 0.2947 | best val 0.3056 @ep39 | EMA val 0.2958 | 308s (train 275s, eval 34s) | GPU max 88C | ETA<= 1.5h
[seed 101] epoch  84/100 | lr 3.85e-05 | train BCE 0.0180 | val AP 0.2953 | best val 0.3056 @ep39 | EMA val 0.2956 | 308s (train 274s, eval 34s) | GPU max 88C | ETA<= 1.4h
[seed 101] epoch  85/100 | lr 3.42e-05 | train BCE 0.0179 | val AP 0.2931 | best val 0.3056 @ep39 | EMA val 0.2953 | 308s (train 275s, eval 34s) | GPU max 88C | ETA<= 1.3h
[seed 101] epoch  86/100 | lr 3.01e-05 | train BCE 0.0179 | val AP 0.2943 | best val 0.3056 @ep39 | EMA val 0.2949 | 308s (train 274s, eval 34s) | GPU max 88C | ETA<= 1.2h
[seed 101] epoch  87/100 | lr 2.63e-05 | train BCE 0.0178 | val AP 0.2946 | best val 0.3056 @ep39 | EMA val 0.2947 | 308s (train 275s, eval 34s) | GPU max 88C | ETA<= 1.1h
[seed 101] epoch  88/100 | lr 2.27e-05 | train BCE 0.0178 | val AP 0.2934 | best val 0.3056 @ep39 | EMA val 0.2949 | 309s (train 275s, eval 34s) | GPU max 88C | ETA<= 1.0h
[seed 101] epoch  89/100 | lr 1.94e-05 | train BCE 0.0177 | val AP 0.2944 | best val 0.3056 @ep39 | EMA val 0.2948 | 308s (train 275s, eval 34s) | GPU max 88C | ETA<= 0.9h
[seed 101] epoch  90/100 | lr 1.64e-05 | train BCE 0.0177 | val AP 0.2942 | best val 0.3056 @ep39 | EMA val 0.2946 | 309s (train 275s, eval 34s) | GPU max 88C | ETA<= 0.9h
[seed 101] epoch  91/100 | lr 1.35e-05 | train BCE 0.0176 | val AP 0.2944 | best val 0.3056 @ep39 | EMA val 0.2945 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.8h
[seed 101] epoch  92/100 | lr 1.10e-05 | train BCE 0.0176 | val AP 0.2940 | best val 0.3056 @ep39 | EMA val 0.2944 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.7h
[seed 101] epoch  93/100 | lr 8.70e-06 | train BCE 0.0176 | val AP 0.2942 | best val 0.3056 @ep39 | EMA val 0.2945 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.6h
[seed 101] epoch  94/100 | lr 6.67e-06 | train BCE 0.0175 | val AP 0.2944 | best val 0.3056 @ep39 | EMA val 0.2945 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.5h
[seed 101] epoch  95/100 | lr 4.91e-06 | train BCE 0.0175 | val AP 0.2931 | best val 0.3056 @ep39 | EMA val 0.2945 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.4h
[seed 101] epoch  96/100 | lr 3.41e-06 | train BCE 0.0175 | val AP 0.2938 | best val 0.3056 @ep39 | EMA val 0.2944 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.3h
[seed 101] epoch  97/100 | lr 2.18e-06 | train BCE 0.0175 | val AP 0.2936 | best val 0.3056 @ep39 | EMA val 0.2944 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.3h
[seed 101] epoch  98/100 | lr 1.23e-06 | train BCE 0.0175 | val AP 0.2939 | best val 0.3056 @ep39 | EMA val 0.2942 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 0.2h
[seed 101] epoch  99/100 | lr 5.47e-07 | train BCE 0.0175 | val AP 0.2937 | best val 0.3056 @ep39 | EMA val 0.2940 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 0.1h
[seed 101] epoch 100/100 | lr 1.37e-07 | train BCE 0.0175 | val AP 0.2939 | best val 0.3056 @ep39 | EMA val 0.2939 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.0h
[seed 101] FINAL TEST (evaluated once): raw epoch 39 val 0.3056 test 0.2943 | EMA epoch 40 val 0.3131 test 0.3043
--- cell 16 ---
PairHGT: GPS + pair channel (pair bias + write-back, value gate) [arm PairHGT] | gps_conf_PairHGT_ep100_molpcba
 seed  epochs  raw_epoch  raw_val  raw_test  ema_epoch  ema_val  ema_test  hours  train_s_per_epoch  total_s_per_epoch
  101 100/100         39   0.3056    0.2943         40   0.3131    0.3043 8.6342           276.5795           310.8298
  202  68/100         62   0.3036       NaN         48   0.3097       NaN 5.8111           274.1168           307.6463
mean ± sample SD (ddof=1) over 1 seed(s): raw test 0.2943 ± nan | EMA test 0.3043 ± nan
A mean ± SD over fewer than 3 seeds is only a description; do not call it a confidence interval.
/tmp/ipykernel_200851/1726116603.py:55: UserWarning: No artists with labels found to put in legend.  Note that artists whose label start with an underscore are ignored when legend() is called with no argument.
  ax.set(title=f"seed {s} (circle = selected raw, square = selected EMA)", xlabel="epoch", ylabel="validation AP"); ax.grid(alpha=0.25); ax.legend(fontsize=7)
run manifest: 4 row(s) -> /home/student/thesis/outputs/pairhgt/outputs/confirmatory/run_manifest.csv
    model              gpu  seeds  params  train_s_per_epoch  val_eval_s_per_epoch  total_s_per_epoch  hours_per_seed  time_vs_GPS+EMA
GPS + EMA NVIDIA RTX A4000      2 9744860             160.78                 16.13             176.93            4.91             1.00
  PairHGT NVIDIA RTX A4000      2 9751972             275.35                 33.87             309.24            7.22             1.75
train = training steps incl. EMA update; val_eval = validation of raw + EMA weights; no test pass inside an epoch (protocol v2). Do not compare with timings from the exploratory runs.
--- cell 18 ---
=== PairHGT  minus  GPS + EMA   (100 epochs, matched seeds) ===
 seed  raw_val  ema_val  raw_test  ema_test
  101   0.0013   0.0027    0.0043    0.0048
  validation AP, raw    : mean +0.0013, sample SD nan, per-seed [0.0013], all positive: True | n=1: fewer than 3 matched seeds, direction only, no interval
  validation AP, EMA    : mean +0.0027, sample SD nan, per-seed [0.0027], all positive: True | n=1: fewer than 3 matched seeds, direction only, no interval
  test AP, raw vs raw   : mean +0.0043, sample SD nan, per-seed [0.0043], all positive: True | n=1: fewer than 3 matched seeds, direction only, no interval
  test AP, EMA vs EMA   : mean +0.0048, sample SD nan, per-seed [0.0048], all positive: True | n=1: fewer than 3 matched seeds, direction only, no interval
  Reading: 1 matched seed(s). The claim is limited to whether the direction of the EMA-vs-EMA difference repeats; a significance claim needs many more seeds.
Planning table (80% power, alpha 0.05, two-sample t, test AP): smallest detectable true difference
  per-seed SD 0.003: n=3: 0.0092, n=5: 0.0061, n=10: 0.0040, n=20: 0.0027
  per-seed SD 0.0056: n=3: 0.0172, n=5: 0.0113, n=10: 0.0074, n=20: 0.0051
--- cell 20 ---
===== 2026-11-11 18:58:20 notebook turn ended (exit 0); executed notebook: /home/student/thesis/outputs/lab_runs/notebooks/pairhgt_PairHGT_seed101_20261111-1607.ipynb =====
```
