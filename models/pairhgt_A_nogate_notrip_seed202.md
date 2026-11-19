# PairHGT, gate fixed at 1 (no gate) — seed 202

[← all models](../README.md) · PairHGT notebook · ogbg-molpcba

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation AP | **0.3003** at epoch 49 |
| Best validation AP, EMA weights | 0.3078 at epoch 41 |
| Test AP | raw 0.2936 / ema 0.3026 (final) |
| Seed | 202 |
| Parameters | 9,751,632 |
| Minutes per epoch (last 5, incl. validation) | 4.5 |
| Training time so far | 7.4 h |
| Training time left | done |
| Sessions (start + resumes) | 2 |
| Hottest GPU reading | 89.0 °C |
| Last update | 2026-11-15 17:40 (96.7 h ago) |

![curves](pairhgt_A_nogate_notrip_seed202.png)

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
| raw | 49 | 0.3003 | 0.2936 |
| ema | 41 | 0.3078 | 0.3026 |

## Every epoch (newest first)

| Epoch | Train loss | Val AP | Val AP (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0184 | 0.2927 | 0.2934 | 0.3003 (ep 49) | 1.37e-07 | 4.4 |
| 99 | 0.0184 | 0.2924 | 0.2934 | 0.3003 (ep 49) | 5.47e-07 | 4.5 |
| 98 | 0.0184 | 0.2926 | 0.2934 | 0.3003 (ep 49) | 1.23e-06 | 4.5 |
| 97 | 0.0184 | 0.2929 | 0.2933 | 0.3003 (ep 49) | 2.18e-06 | 4.4 |
| 96 | 0.0185 | 0.2931 | 0.2934 | 0.3003 (ep 49) | 3.41e-06 | 4.5 |
| 95 | 0.0185 | 0.2928 | 0.2935 | 0.3003 (ep 49) | 4.91e-06 | 4.5 |
| 94 | 0.0185 | 0.2939 | 0.2935 | 0.3003 (ep 49) | 6.67e-06 | 4.4 |
| 93 | 0.0185 | 0.2934 | 0.2935 | 0.3003 (ep 49) | 8.70e-06 | 4.4 |
| 92 | 0.0185 | 0.2930 | 0.2936 | 0.3003 (ep 49) | 1.10e-05 | 4.5 |
| 91 | 0.0186 | 0.2930 | 0.2940 | 0.3003 (ep 49) | 1.35e-05 | 4.5 |
| 90 | 0.0186 | 0.2935 | 0.2937 | 0.3003 (ep 49) | 1.64e-05 | 4.5 |
| 89 | 0.0187 | 0.2926 | 0.2936 | 0.3003 (ep 49) | 1.94e-05 | 4.4 |
| 88 | 0.0187 | 0.2932 | 0.2936 | 0.3003 (ep 49) | 2.27e-05 | 4.5 |
| 87 | 0.0187 | 0.2931 | 0.2938 | 0.3003 (ep 49) | 2.63e-05 | 4.4 |
| 86 | 0.0188 | 0.2923 | 0.2942 | 0.3003 (ep 49) | 3.01e-05 | 4.5 |
| 85 | 0.0189 | 0.2936 | 0.2945 | 0.3003 (ep 49) | 3.42e-05 | 4.5 |
| 84 | 0.0190 | 0.2939 | 0.2947 | 0.3003 (ep 49) | 3.85e-05 | 4.5 |
| 83 | 0.0190 | 0.2937 | 0.2946 | 0.3003 (ep 49) | 4.30e-05 | 4.5 |
| 82 | 0.0191 | 0.2934 | 0.2947 | 0.3003 (ep 49) | 4.77e-05 | 4.5 |
| 81 | 0.0192 | 0.2939 | 0.2948 | 0.3003 (ep 49) | 5.27e-05 | 4.5 |
| 80 | 0.0193 | 0.2922 | 0.2957 | 0.3003 (ep 49) | 5.79e-05 | 4.4 |
| 79 | 0.0194 | 0.2919 | 0.2961 | 0.3003 (ep 49) | 6.33e-05 | 4.5 |
| 78 | 0.0195 | 0.2928 | 0.2969 | 0.3003 (ep 49) | 6.89e-05 | 4.5 |
| 77 | 0.0196 | 0.2946 | 0.2974 | 0.3003 (ep 49) | 7.47e-05 | 4.5 |
| 76 | 0.0197 | 0.2941 | 0.2970 | 0.3003 (ep 49) | 8.07e-05 | 4.5 |
| 75 | 0.0198 | 0.2939 | 0.2974 | 0.3003 (ep 49) | 8.69e-05 | 4.5 |
| 74 | 0.0199 | 0.2945 | 0.2977 | 0.3003 (ep 49) | 9.32e-05 | 4.5 |
| 73 | 0.0201 | 0.2948 | 0.2980 | 0.3003 (ep 49) | 9.97e-05 | 4.5 |
| 72 | 0.0202 | 0.2955 | 0.2981 | 0.3003 (ep 49) | 1.06e-04 | 4.5 |
| 71 | 0.0203 | 0.2933 | 0.2984 | 0.3003 (ep 49) | 1.13e-04 | 4.5 |
| 70 | 0.0205 | 0.2966 | 0.2998 | 0.3003 (ep 49) | 1.20e-04 | 4.5 |
| 69 | 0.0206 | 0.2950 | 0.3001 | 0.3003 (ep 49) | 1.27e-04 | 4.5 |
| 68 | 0.0208 | 0.2956 | 0.3004 | 0.3003 (ep 49) | 1.35e-04 | 4.5 |
| 67 | 0.0209 | 0.2953 | 0.3008 | 0.3003 (ep 49) | 1.42e-04 | 4.5 |
| 66 | 0.0211 | 0.2958 | 0.3013 | 0.3003 (ep 49) | 1.50e-04 | 4.5 |
| 65 | 0.0213 | 0.2964 | 0.3019 | 0.3003 (ep 49) | 1.57e-04 | 4.5 |
| 64 | 0.0214 | 0.2983 | 0.3017 | 0.3003 (ep 49) | 1.65e-04 | 4.5 |
| 63 | 0.0216 | 0.2943 | 0.3026 | 0.3003 (ep 49) | 1.73e-04 | 4.5 |
| 62 | 0.0217 | 0.2962 | 0.3034 | 0.3003 (ep 49) | 1.81e-04 | 4.5 |
| 61 | 0.0219 | 0.2984 | 0.3043 | 0.3003 (ep 49) | 1.89e-04 | 4.5 |
| 60 | 0.0221 | 0.2964 | 0.3047 | 0.3003 (ep 49) | 1.97e-04 | 4.5 |
| 59 | 0.0223 | 0.2981 | 0.3051 | 0.3003 (ep 49) | 2.05e-04 | 4.5 |
| 58 | 0.0225 | 0.2967 | 0.3051 | 0.3003 (ep 49) | 2.13e-04 | 4.5 |
| 57 | 0.0227 | 0.2986 | 0.3058 | 0.3003 (ep 49) | 2.21e-04 | 4.5 |
| 56 | 0.0229 | 0.2992 | 0.3055 | 0.3003 (ep 49) | 2.29e-04 | 4.5 |
| 55 | 0.0231 | 0.2990 | 0.3050 | 0.3003 (ep 49) | 2.38e-04 | 4.4 |
| 54 | 0.0233 | 0.2994 | 0.3047 | 0.3003 (ep 49) | 2.46e-04 | 4.5 |
| 53 | 0.0235 | 0.2972 | 0.3057 | 0.3003 (ep 49) | 2.54e-04 | 4.5 |
| 52 | 0.0237 | 0.2996 | 0.3064 | 0.3003 (ep 49) | 2.62e-04 | 4.5 |
| 51 | 0.0239 | 0.2990 | 0.3062 | 0.3003 (ep 49) | 2.71e-04 | 4.5 |
| 50 | 0.0241 | 0.2994 | 0.3055 | 0.3003 (ep 49) | 2.79e-04 | 4.5 |
| 49 | 0.0243 | 0.3003 ⭐ | 0.3055 | 0.3003 (ep 49) | 2.87e-04 | 4.5 |
| 48 | 0.0246 | 0.2949 | 0.3051 | 0.2996 (ep 40) | 2.95e-04 | 4.5 |
| 47 | 0.0248 | 0.2970 | 0.3052 | 0.2996 (ep 40) | 3.03e-04 | 4.4 |
| 46 | 0.0250 | 0.2937 | 0.3054 | 0.2996 (ep 40) | 3.11e-04 | 4.5 |
| 45 | 0.0252 | 0.2990 | 0.3059 | 0.2996 (ep 40) | 3.19e-04 | 4.4 |
| 44 | 0.0254 | 0.2966 | 0.3061 | 0.2996 (ep 40) | 3.27e-04 | 4.5 |
| 43 | 0.0257 | 0.2967 | 0.3068 | 0.2996 (ep 40) | 3.35e-04 | 4.4 |
| 42 | 0.0259 | 0.2964 | 0.3065 | 0.2996 (ep 40) | 3.43e-04 | 4.4 |
| 41 | 0.0262 | 0.2974 | 0.3078 | 0.2996 (ep 40) | 3.50e-04 | 4.5 |
| 40 | 0.0264 | 0.2996 ⭐ | 0.3054 | 0.2996 (ep 40) | 3.58e-04 | 4.5 |
| 39 | 0.0267 | 0.2951 ⭐ | 0.3048 | 0.2951 (ep 39) | 3.65e-04 | 4.5 |
| 38 | 0.0269 | 0.2909 | 0.3049 | 0.2936 (ep 36) | 3.73e-04 | 4.5 |
| 37 | 0.0272 | 0.2925 | 0.3050 | 0.2936 (ep 36) | 3.80e-04 | 4.5 |
| 36 | 0.0274 | 0.2936 ⭐ | 0.3053 | 0.2936 (ep 36) | 3.87e-04 | 4.5 |
| 35 | 0.0277 | 0.2920 | 0.3041 | 0.2931 (ep 29) | 3.94e-04 | 4.5 |
| 34 | 0.0279 | 0.2921 | 0.3033 | 0.2931 (ep 29) | 4.00e-04 | 4.4 |
| 33 | 0.0282 | 0.2902 | 0.3029 | 0.2931 (ep 29) | 4.07e-04 | 4.5 |
| 32 | 0.0284 | 0.2914 | 0.3021 | 0.2931 (ep 29) | 4.13e-04 | 4.5 |
| 31 | 0.0287 | 0.2874 | 0.3010 | 0.2931 (ep 29) | 4.19e-04 | 4.5 |
| 30 | 0.0290 | 0.2877 | 0.3004 | 0.2931 (ep 29) | 4.25e-04 | 4.5 |
| 29 | 0.0293 | 0.2931 ⭐ | 0.2994 | 0.2931 (ep 29) | 4.31e-04 | 4.4 |
| 28 | 0.0296 | 0.2894 ⭐ | 0.2978 | 0.2894 (ep 28) | 4.37e-04 | 4.5 |
| 27 | 0.0299 | 0.2823 | 0.2967 | 0.2852 (ep 24) | 4.42e-04 | 4.5 |
| 26 | 0.0301 | 0.2837 | 0.2940 | 0.2852 (ep 24) | 4.47e-04 | 4.5 |
| 25 | 0.0305 | 0.2819 | 0.2924 | 0.2852 (ep 24) | 4.52e-04 | 4.5 |
| 24 | 0.0310 | 0.2852 ⭐ | 0.2910 | 0.2852 (ep 24) | 4.57e-04 | 4.5 |
| 23 | 0.0312 | 0.2790 ⭐ | 0.2888 | 0.2790 (ep 23) | 4.62e-04 | 4.5 |
| 22 | 0.0317 | 0.2719 | 0.2851 | 0.2774 (ep 21) | 4.66e-04 | 4.5 |
| 21 | 0.0319 | 0.2774 ⭐ | 0.2821 | 0.2774 (ep 21) | 4.70e-04 | 4.5 |
| 20 | 0.0323 | 0.2734 ⭐ | 0.2781 | 0.2734 (ep 20) | 4.74e-04 | 4.5 |
| 19 | 0.0330 | 0.2660 | 0.2750 | 0.2660 (ep 17) | 4.77e-04 | 4.5 |
| 18 | 0.0332 | 0.2605 | 0.2738 | 0.2660 (ep 17) | 4.81e-04 | 4.4 |
| 17 | 0.0337 | 0.2660 ⭐ | 0.2710 | 0.2660 (ep 17) | 4.84e-04 | 4.5 |
| 16 | 0.0342 | 0.2602 ⭐ | 0.2671 | 0.2602 (ep 16) | 4.86e-04 | 4.5 |
| 15 | 0.0347 | 0.2513 ⭐ | 0.2618 | 0.2513 (ep 15) | 4.89e-04 | 4.5 |
| 14 | 0.0353 | 0.2430 ⭐ | 0.2574 | 0.2430 (ep 14) | 4.91e-04 | 4.5 |
| 13 | 0.0359 | 0.2370 ⭐ | 0.2508 | 0.2370 (ep 13) | 4.93e-04 | 4.5 |
| 12 | 0.0365 | 0.2220 | 0.2446 | 0.2313 (ep 11) | 4.95e-04 | 4.5 |
| 11 | 0.0372 | 0.2313 ⭐ | 0.2374 | 0.2313 (ep 11) | 4.97e-04 | 4.5 |
| 10 | 0.0380 | 0.2178 ⭐ | 0.2272 | 0.2178 (ep 10) | 4.98e-04 | 4.5 |
| 9 | 0.0389 | 0.2057 ⭐ | 0.2170 | 0.2057 (ep 9) | 4.99e-04 | 4.5 |
| 8 | 0.0400 | 0.1913 ⭐ | 0.2029 | 0.1913 (ep 8) | 4.99e-04 | 4.5 |
| 7 | 0.0412 | 0.1835 ⭐ | 0.1851 | 0.1835 (ep 7) | 5.00e-04 | 4.5 |
| 6 | 0.0429 | 0.1647 ⭐ | 0.1624 | 0.1647 (ep 6) | 5.00e-04 | 4.5 |
| 5 | 0.0451 | 0.1408 ⭐ | 0.1347 | 0.1408 (ep 5) | 4.00e-04 | 4.5 |
| 4 | 0.0492 | 0.1118 ⭐ | 0.1039 | 0.1118 (ep 4) | 3.00e-04 | 4.5 |
| 3 | 0.0661 | 0.0770 ⭐ | 0.0689 | 0.0770 (ep 3) | 2.00e-04 | 4.5 |
| 2 | 0.3340 | 0.0417 ⭐ | 0.0402 | 0.0417 (ep 2) | 1.00e-04 | 4.5 |
| 1 | 0.6961 | 0.0259 ⭐ | 0.0258 | 0.0259 (ep 1) | 5.00e-10 | 4.4 |

## Last 80 log lines

_The log counts epochs from 0; the tables above count from 1._

```
RUN_DEBUG_FIRST is False: smoke test skipped.
--- cell 14 ---
Restored 0 seed folder(s).
prereg.json checked: configuration identical (hash f924dd96f7aefd19); seeds [101, 202, 323, 432, 543]
[seed 202] RESUMED from epoch 79/100 (lr 5.79e-05, best val AP so far 0.3003)
[seed 202] epoch  80/100 | lr 5.79e-05 | train BCE 0.0193 | val AP 0.2922 | best val 0.3003 @ep49 | EMA val 0.2957 | 267s (train 238s, eval 28s) | GPU max 89C | ETA<= 1.5h
[seed 202] epoch  81/100 | lr 5.27e-05 | train BCE 0.0192 | val AP 0.2939 | best val 0.3003 @ep49 | EMA val 0.2948 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.4h
[seed 202] epoch  82/100 | lr 4.77e-05 | train BCE 0.0191 | val AP 0.2934 | best val 0.3003 @ep49 | EMA val 0.2947 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.3h
[seed 202] epoch  83/100 | lr 4.30e-05 | train BCE 0.0190 | val AP 0.2937 | best val 0.3003 @ep49 | EMA val 0.2946 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.3h
[seed 202] epoch  84/100 | lr 3.85e-05 | train BCE 0.0190 | val AP 0.2939 | best val 0.3003 @ep49 | EMA val 0.2947 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.2h
[seed 202] epoch  85/100 | lr 3.42e-05 | train BCE 0.0189 | val AP 0.2936 | best val 0.3003 @ep49 | EMA val 0.2945 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.1h
[seed 202] epoch  86/100 | lr 3.01e-05 | train BCE 0.0188 | val AP 0.2923 | best val 0.3003 @ep49 | EMA val 0.2942 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.0h
[seed 202] epoch  87/100 | lr 2.63e-05 | train BCE 0.0187 | val AP 0.2931 | best val 0.3003 @ep49 | EMA val 0.2938 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 1.0h
[seed 202] epoch  88/100 | lr 2.27e-05 | train BCE 0.0187 | val AP 0.2932 | best val 0.3003 @ep49 | EMA val 0.2936 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.9h
[seed 202] epoch  89/100 | lr 1.94e-05 | train BCE 0.0187 | val AP 0.2926 | best val 0.3003 @ep49 | EMA val 0.2936 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.8h
[seed 202] epoch  90/100 | lr 1.64e-05 | train BCE 0.0186 | val AP 0.2935 | best val 0.3003 @ep49 | EMA val 0.2937 | 268s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.7h
[seed 202] epoch  91/100 | lr 1.35e-05 | train BCE 0.0186 | val AP 0.2930 | best val 0.3003 @ep49 | EMA val 0.2940 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.7h
[seed 202] epoch  92/100 | lr 1.10e-05 | train BCE 0.0185 | val AP 0.2930 | best val 0.3003 @ep49 | EMA val 0.2936 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.6h
[seed 202] epoch  93/100 | lr 8.70e-06 | train BCE 0.0185 | val AP 0.2934 | best val 0.3003 @ep49 | EMA val 0.2935 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.5h
[seed 202] epoch  94/100 | lr 6.67e-06 | train BCE 0.0185 | val AP 0.2939 | best val 0.3003 @ep49 | EMA val 0.2935 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.4h
[seed 202] epoch  95/100 | lr 4.91e-06 | train BCE 0.0185 | val AP 0.2928 | best val 0.3003 @ep49 | EMA val 0.2935 | 268s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.4h
[seed 202] epoch  96/100 | lr 3.41e-06 | train BCE 0.0185 | val AP 0.2931 | best val 0.3003 @ep49 | EMA val 0.2934 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.3h
[seed 202] epoch  97/100 | lr 2.18e-06 | train BCE 0.0184 | val AP 0.2929 | best val 0.3003 @ep49 | EMA val 0.2933 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.2h
[seed 202] epoch  98/100 | lr 1.23e-06 | train BCE 0.0184 | val AP 0.2926 | best val 0.3003 @ep49 | EMA val 0.2934 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.1h
[seed 202] epoch  99/100 | lr 5.47e-07 | train BCE 0.0184 | val AP 0.2924 | best val 0.3003 @ep49 | EMA val 0.2934 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.1h
[seed 202] epoch 100/100 | lr 1.37e-07 | train BCE 0.0184 | val AP 0.2927 | best val 0.3003 @ep49 | EMA val 0.2934 | 267s (train 239s, eval 28s) | GPU max 89C | ETA<= 0.0h
[seed 202] FINAL TEST (evaluated once): raw epoch 49 val 0.3003 test 0.2936 | EMA epoch 41 val 0.3078 test 0.3026
--- cell 16 ---
PairHGT, gate fixed at 1 (no gate): GPS + pair channel (pair bias + write-back) [arm A_nogate_notrip] | gps_conf_A_nogate_notrip_ep100_molpcba
 seed  epochs  raw_epoch  raw_val  raw_test  ema_epoch  ema_val  ema_test  hours  train_s_per_epoch  total_s_per_epoch
  101 100/100         91   0.2973    0.2909         92   0.2970    0.2916 7.4298           239.2251           267.4726
  202 100/100         49   0.3003    0.2936         41   0.3078    0.3026 7.4248           239.0581           267.2913
mean ± sample SD (ddof=1) over 2 seed(s): raw test 0.2923 ± 0.0019 | EMA test 0.2971 ± 0.0078
A mean ± SD over fewer than 3 seeds is only a description; do not call it a confidence interval.
/tmp/ipykernel_893674/1726116603.py:55: UserWarning: No artists with labels found to put in legend.  Note that artists whose label start with an underscore are ignored when legend() is called with no argument.
  ax.set(title=f"seed {s} (circle = selected raw, square = selected EMA)", xlabel="epoch", ylabel="validation AP"); ax.grid(alpha=0.25); ax.legend(fontsize=7)
run manifest: 14 row(s) -> /home/student/thesis/outputs/pairhgt/outputs/confirmatory/run_manifest.csv
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
  validation AP, raw    : mean +0.0058, sample SD 0.0035, per-seed [0.0083, 0.0034], all positive: True | n=2: fewer than 3 matched seeds, direction only, no interval
  validation AP, EMA    : mean +0.0090, sample SD 0.0101, per-seed [0.0161, 0.0018], all positive: True | n=2: fewer than 3 matched seeds, direction only, no interval
  test AP, raw vs raw   : mean +0.0030, sample SD 0.0004, per-seed [0.0033, 0.0027], all positive: True | n=2: fewer than 3 matched seeds, direction only, no interval
  test AP, EMA vs EMA   : mean +0.0081, sample SD 0.0064, per-seed [0.0127, 0.0036], all positive: True | n=2: fewer than 3 matched seeds, direction only, no interval
  Reading: 2 matched seed(s). The claim is limited to whether the direction of the EMA-vs-EMA difference repeats; a significance claim needs many more seeds.
ABLATION RULE (PairHGT vs PairHGT, gate fixed at 1 (no gate), validation AP, margin 0.002): raw +0.0058, EMA +0.0090 -> component RETAINED (lead on both weight types)
  screening result on 1-3 seeds: it decides whether a full 100-epoch run is worth its cost, nothing more.
=== PairHGT  minus  PairHGT, gate only (no pair bias)   (100 epochs, matched seeds) ===
 seed  raw_val  ema_val  raw_test  ema_test
  101   0.0077   0.0067    0.0016    0.0028
  validation AP, raw    : mean +0.0077, sample SD nan, per-seed [0.0077], all positive: True | n=1: fewer than 3 matched seeds, direction only, no interval
  validation AP, EMA    : mean +0.0067, sample SD nan, per-seed [0.0067], all positive: True | n=1: fewer than 3 matched seeds, direction only, no interval
  test AP, raw vs raw   : mean +0.0016, sample SD nan, per-seed [0.0016], all positive: True | n=1: fewer than 3 matched seeds, direction only, no interval
  test AP, EMA vs EMA   : mean +0.0028, sample SD nan, per-seed [0.0028], all positive: True | n=1: fewer than 3 matched seeds, direction only, no interval
  Reading: 1 matched seed(s). The claim is limited to whether the direction of the EMA-vs-EMA difference repeats; a significance claim needs many more seeds.
ABLATION RULE (PairHGT vs PairHGT, gate only (no pair bias), validation AP, margin 0.002): raw +0.0077, EMA +0.0067 -> component RETAINED (lead on both weight types)
  screening result on 1-3 seeds: it decides whether a full 100-epoch run is worth its cost, nothing more.
Planning table (80% power, alpha 0.05, two-sample t, test AP): smallest detectable true difference
  per-seed SD 0.003: n=3: 0.0092, n=5: 0.0061, n=10: 0.0040, n=20: 0.0027
  per-seed SD 0.0056: n=3: 0.0172, n=5: 0.0113, n=10: 0.0074, n=20: 0.0051
--- cell 20 ---
===== 2026-11-15 17:41:05 notebook turn ended (exit 0); executed notebook: /home/student/thesis/outputs/lab_runs/notebooks/pairhgt_A_nogate_notrip_seed202_20261115-1606.ipynb =====
```
