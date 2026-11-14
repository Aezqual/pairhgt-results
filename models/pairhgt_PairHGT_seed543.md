# PairHGT — seed 543

[← all models](../README.md) · PairHGT notebook · ogbg-molpcba

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation AP | **0.3028** at epoch 39 |
| Best validation AP, EMA weights | 0.3090 at epoch 35 |
| Test AP | raw 0.2962 / ema 0.3033 (final) |
| Seed | 543 |
| Parameters | 9,751,972 |
| Minutes per epoch (last 5, incl. validation) | 5.1 |
| Training time so far | 8.6 h |
| Training time left | done |
| Sessions (start + resumes) | 2 |
| Hottest GPU reading | 89.0 °C |
| Last update | 2026-11-14 08:14 (9.9 h ago) |

![curves](pairhgt_PairHGT_seed543.png)

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
| raw | 39 | 0.3028 | 0.2962 |
| ema | 35 | 0.3090 | 0.3033 |

## Every epoch (newest first)

| Epoch | Train loss | Val AP | Val AP (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0173 | 0.2893 | 0.2895 | 0.3028 (ep 39) | 1.37e-07 | 5.1 |
| 99 | 0.0173 | 0.2898 | 0.2895 | 0.3028 (ep 39) | 5.47e-07 | 5.1 |
| 98 | 0.0173 | 0.2895 | 0.2897 | 0.3028 (ep 39) | 1.23e-06 | 5.1 |
| 97 | 0.0173 | 0.2900 | 0.2897 | 0.3028 (ep 39) | 2.18e-06 | 5.1 |
| 96 | 0.0174 | 0.2893 | 0.2897 | 0.3028 (ep 39) | 3.41e-06 | 5.2 |
| 95 | 0.0174 | 0.2897 | 0.2897 | 0.3028 (ep 39) | 4.91e-06 | 5.1 |
| 94 | 0.0174 | 0.2897 | 0.2897 | 0.3028 (ep 39) | 6.67e-06 | 5.1 |
| 93 | 0.0174 | 0.2899 | 0.2900 | 0.3028 (ep 39) | 8.70e-06 | 5.1 |
| 92 | 0.0174 | 0.2899 | 0.2902 | 0.3028 (ep 39) | 1.10e-05 | 5.1 |
| 91 | 0.0175 | 0.2891 | 0.2902 | 0.3028 (ep 39) | 1.35e-05 | 5.2 |
| 90 | 0.0175 | 0.2894 | 0.2903 | 0.3028 (ep 39) | 1.64e-05 | 5.1 |
| 89 | 0.0176 | 0.2890 | 0.2905 | 0.3028 (ep 39) | 1.94e-05 | 5.1 |
| 88 | 0.0176 | 0.2894 | 0.2908 | 0.3028 (ep 39) | 2.27e-05 | 5.2 |
| 87 | 0.0177 | 0.2892 | 0.2913 | 0.3028 (ep 39) | 2.63e-05 | 5.1 |
| 86 | 0.0178 | 0.2895 | 0.2921 | 0.3028 (ep 39) | 3.01e-05 | 5.2 |
| 85 | 0.0178 | 0.2908 | 0.2924 | 0.3028 (ep 39) | 3.42e-05 | 5.1 |
| 84 | 0.0179 | 0.2913 | 0.2926 | 0.3028 (ep 39) | 3.85e-05 | 5.1 |
| 83 | 0.0180 | 0.2911 | 0.2930 | 0.3028 (ep 39) | 4.30e-05 | 5.1 |
| 82 | 0.0180 | 0.2908 | 0.2932 | 0.3028 (ep 39) | 4.77e-05 | 5.1 |
| 81 | 0.0181 | 0.2912 | 0.2934 | 0.3028 (ep 39) | 5.27e-05 | 5.1 |
| 80 | 0.0182 | 0.2924 | 0.2930 | 0.3028 (ep 39) | 5.79e-05 | 5.2 |
| 79 | 0.0183 | 0.2917 | 0.2935 | 0.3028 (ep 39) | 6.33e-05 | 5.1 |
| 78 | 0.0185 | 0.2920 | 0.2939 | 0.3028 (ep 39) | 6.89e-05 | 5.1 |
| 77 | 0.0185 | 0.2882 | 0.2942 | 0.3028 (ep 39) | 7.47e-05 | 5.2 |
| 76 | 0.0187 | 0.2930 | 0.2946 | 0.3028 (ep 39) | 8.07e-05 | 5.2 |
| 75 | 0.0188 | 0.2936 | 0.2948 | 0.3028 (ep 39) | 8.69e-05 | 5.2 |
| 74 | 0.0189 | 0.2921 | 0.2950 | 0.3028 (ep 39) | 9.32e-05 | 5.2 |
| 73 | 0.0191 | 0.2928 | 0.2954 | 0.3028 (ep 39) | 9.97e-05 | 5.1 |
| 72 | 0.0192 | 0.2919 | 0.2962 | 0.3028 (ep 39) | 1.06e-04 | 5.1 |
| 71 | 0.0194 | 0.2919 | 0.2970 | 0.3028 (ep 39) | 1.13e-04 | 5.1 |
| 70 | 0.0195 | 0.2944 | 0.2968 | 0.3028 (ep 39) | 1.20e-04 | 5.1 |
| 69 | 0.0197 | 0.2932 | 0.2972 | 0.3028 (ep 39) | 1.27e-04 | 5.1 |
| 68 | 0.0198 | 0.2944 | 0.2975 | 0.3028 (ep 39) | 1.35e-04 | 5.1 |
| 67 | 0.0200 | 0.2947 | 0.2979 | 0.3028 (ep 39) | 1.42e-04 | 5.1 |
| 66 | 0.0202 | 0.2936 | 0.2978 | 0.3028 (ep 39) | 1.50e-04 | 5.2 |
| 65 | 0.0204 | 0.2921 | 0.2986 | 0.3028 (ep 39) | 1.57e-04 | 5.1 |
| 64 | 0.0205 | 0.2938 | 0.2989 | 0.3028 (ep 39) | 1.65e-04 | 5.1 |
| 63 | 0.0207 | 0.2931 | 0.2993 | 0.3028 (ep 39) | 1.73e-04 | 5.1 |
| 62 | 0.0209 | 0.2931 | 0.2997 | 0.3028 (ep 39) | 1.81e-04 | 5.2 |
| 61 | 0.0211 | 0.2942 | 0.3001 | 0.3028 (ep 39) | 1.89e-04 | 5.2 |
| 60 | 0.0213 | 0.2974 | 0.3000 | 0.3028 (ep 39) | 1.97e-04 | 5.2 |
| 59 | 0.0215 | 0.2942 | 0.3009 | 0.3028 (ep 39) | 2.05e-04 | 5.1 |
| 58 | 0.0217 | 0.2968 | 0.3018 | 0.3028 (ep 39) | 2.13e-04 | 5.2 |
| 57 | 0.0219 | 0.2925 | 0.3029 | 0.3028 (ep 39) | 2.21e-04 | 5.2 |
| 56 | 0.0221 | 0.2934 | 0.3037 | 0.3028 (ep 39) | 2.29e-04 | 5.2 |
| 55 | 0.0223 | 0.2966 | 0.3040 | 0.3028 (ep 39) | 2.38e-04 | 5.2 |
| 54 | 0.0225 | 0.2978 | 0.3041 | 0.3028 (ep 39) | 2.46e-04 | 5.2 |
| 53 | 0.0228 | 0.2956 | 0.3042 | 0.3028 (ep 39) | 2.54e-04 | 5.2 |
| 52 | 0.0230 | 0.2971 | 0.3047 | 0.3028 (ep 39) | 2.62e-04 | 5.1 |
| 51 | 0.0232 | 0.2970 | 0.3049 | 0.3028 (ep 39) | 2.71e-04 | 5.2 |
| 50 | 0.0234 | 0.3020 | 0.3055 | 0.3028 (ep 39) | 2.79e-04 | 5.1 |
| 49 | 0.0237 | 0.2976 | 0.3060 | 0.3028 (ep 39) | 2.87e-04 | 5.2 |
| 48 | 0.0239 | 0.2949 | 0.3071 | 0.3028 (ep 39) | 2.95e-04 | 5.2 |
| 47 | 0.0241 | 0.2987 | 0.3075 | 0.3028 (ep 39) | 3.03e-04 | 5.2 |
| 46 | 0.0244 | 0.2975 | 0.3082 | 0.3028 (ep 39) | 3.11e-04 | 5.1 |
| 45 | 0.0246 | 0.2968 | 0.3082 | 0.3028 (ep 39) | 3.19e-04 | 5.2 |
| 44 | 0.0249 | 0.2986 | 0.3088 | 0.3028 (ep 39) | 3.27e-04 | 5.2 |
| 43 | 0.0251 | 0.2987 | 0.3082 | 0.3028 (ep 39) | 3.35e-04 | 5.2 |
| 42 | 0.0253 | 0.2996 | 0.3081 | 0.3028 (ep 39) | 3.43e-04 | 5.1 |
| 41 | 0.0256 | 0.2968 | 0.3079 | 0.3028 (ep 39) | 3.50e-04 | 5.2 |
| 40 | 0.0258 | 0.2944 | 0.3078 | 0.3028 (ep 39) | 3.58e-04 | 5.1 |
| 39 | 0.0261 | 0.3028 ⭐ | 0.3075 | 0.3028 (ep 39) | 3.65e-04 | 5.1 |
| 38 | 0.0263 | 0.2915 | 0.3075 | 0.2992 (ep 33) | 3.73e-04 | 5.2 |
| 37 | 0.0266 | 0.2939 | 0.3073 | 0.2992 (ep 33) | 3.80e-04 | 5.2 |
| 36 | 0.0268 | 0.2924 | 0.3079 | 0.2992 (ep 33) | 3.87e-04 | 5.1 |
| 35 | 0.0270 | 0.2963 | 0.3090 | 0.2992 (ep 33) | 3.94e-04 | 5.2 |
| 34 | 0.0274 | 0.2971 | 0.3083 | 0.2992 (ep 33) | 4.00e-04 | 5.2 |
| 33 | 0.0276 | 0.2992 ⭐ | 0.3071 | 0.2992 (ep 33) | 4.07e-04 | 5.1 |
| 32 | 0.0279 | 0.2986 ⭐ | 0.3065 | 0.2986 (ep 32) | 4.13e-04 | 5.2 |
| 31 | 0.0282 | 0.2955 ⭐ | 0.3055 | 0.2955 (ep 31) | 4.19e-04 | 5.2 |
| 30 | 0.0285 | 0.2932 ⭐ | 0.3053 | 0.2932 (ep 30) | 4.25e-04 | 5.1 |
| 29 | 0.0288 | 0.2905 | 0.3042 | 0.2928 (ep 27) | 4.31e-04 | 5.1 |
| 28 | 0.0290 | 0.2902 | 0.3037 | 0.2928 (ep 27) | 4.37e-04 | 5.1 |
| 27 | 0.0293 | 0.2928 ⭐ | 0.3019 | 0.2928 (ep 27) | 4.42e-04 | 5.2 |
| 26 | 0.0297 | 0.2924 ⭐ | 0.2987 | 0.2924 (ep 26) | 4.47e-04 | 5.2 |
| 25 | 0.0301 | 0.2873 ⭐ | 0.2968 | 0.2873 (ep 25) | 4.52e-04 | 5.2 |
| 24 | 0.0305 | 0.2860 ⭐ | 0.2950 | 0.2860 (ep 24) | 4.57e-04 | 5.1 |
| 23 | 0.0310 | 0.2858 ⭐ | 0.2940 | 0.2858 (ep 23) | 4.62e-04 | 5.2 |
| 22 | 0.0311 | 0.2834 ⭐ | 0.2934 | 0.2834 (ep 22) | 4.66e-04 | 5.2 |
| 21 | 0.0314 | 0.2779 | 0.2905 | 0.2794 (ep 20) | 4.70e-04 | 5.2 |
| 20 | 0.0319 | 0.2794 ⭐ | 0.2877 | 0.2794 (ep 20) | 4.74e-04 | 5.1 |
| 19 | 0.0323 | 0.2736 ⭐ | 0.2819 | 0.2736 (ep 19) | 4.77e-04 | 5.2 |
| 18 | 0.0328 | 0.2608 | 0.2781 | 0.2679 (ep 17) | 4.81e-04 | 5.2 |
| 17 | 0.0333 | 0.2679 ⭐ | 0.2743 | 0.2679 (ep 17) | 4.84e-04 | 5.2 |
| 16 | 0.0339 | 0.2587 ⭐ | 0.2681 | 0.2587 (ep 16) | 4.86e-04 | 5.2 |
| 15 | 0.0346 | 0.2544 ⭐ | 0.2631 | 0.2544 (ep 15) | 4.89e-04 | 5.2 |
| 14 | 0.0351 | 0.2451 ⭐ | 0.2602 | 0.2451 (ep 14) | 4.91e-04 | 5.2 |
| 13 | 0.0357 | 0.2400 ⭐ | 0.2536 | 0.2400 (ep 13) | 4.93e-04 | 5.2 |
| 12 | 0.0365 | 0.2279 | 0.2458 | 0.2291 (ep 11) | 4.95e-04 | 5.2 |
| 11 | 0.0372 | 0.2291 ⭐ | 0.2371 | 0.2291 (ep 11) | 4.97e-04 | 5.1 |
| 10 | 0.0380 | 0.2183 ⭐ | 0.2285 | 0.2183 (ep 10) | 4.98e-04 | 5.2 |
| 9 | 0.0389 | 0.2015 ⭐ | 0.2164 | 0.2015 (ep 9) | 4.99e-04 | 5.2 |
| 8 | 0.0399 | 0.1846 ⭐ | 0.2029 | 0.1846 (ep 8) | 4.99e-04 | 5.2 |
| 7 | 0.0412 | 0.1823 ⭐ | 0.1860 | 0.1823 (ep 7) | 5.00e-04 | 5.2 |
| 6 | 0.0429 | 0.1658 ⭐ | 0.1622 | 0.1658 (ep 6) | 5.00e-04 | 5.2 |
| 5 | 0.0449 | 0.1413 ⭐ | 0.1356 | 0.1413 (ep 5) | 4.00e-04 | 5.2 |
| 4 | 0.0487 | 0.1132 ⭐ | 0.1046 | 0.1132 (ep 4) | 3.00e-04 | 5.2 |
| 3 | 0.0679 | 0.0732 ⭐ | 0.0672 | 0.0732 (ep 3) | 2.00e-04 | 5.2 |
| 2 | 0.3316 | 0.0387 ⭐ | 0.0406 | 0.0387 (ep 2) | 1.00e-04 | 5.2 |
| 1 | 0.6985 | 0.0252 ⭐ | 0.0252 | 0.0252 (ep 1) | 5.00e-10 | 5.1 |

## Last 80 log lines

_The log counts epochs from 0; the tables above count from 1._

```
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
[seed 543] RESUMED from epoch 68/100 (lr 1.27e-04, best val AP so far 0.3028)
[seed 543] epoch  69/100 | lr 1.27e-04 | train BCE 0.0197 | val AP 0.2932 | best val 0.3028 @ep39 | EMA val 0.2972 | 309s (train 274s, eval 34s) | GPU max 89C | ETA<= 2.7h
[seed 543] epoch  70/100 | lr 1.20e-04 | train BCE 0.0195 | val AP 0.2944 | best val 0.3028 @ep39 | EMA val 0.2968 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.6h
[seed 543] epoch  71/100 | lr 1.13e-04 | train BCE 0.0194 | val AP 0.2919 | best val 0.3028 @ep39 | EMA val 0.2970 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.5h
[seed 543] epoch  72/100 | lr 1.06e-04 | train BCE 0.0192 | val AP 0.2919 | best val 0.3028 @ep39 | EMA val 0.2962 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.4h
[seed 543] epoch  73/100 | lr 9.97e-05 | train BCE 0.0191 | val AP 0.2928 | best val 0.3028 @ep39 | EMA val 0.2954 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.3h
[seed 543] epoch  74/100 | lr 9.32e-05 | train BCE 0.0189 | val AP 0.2921 | best val 0.3028 @ep39 | EMA val 0.2950 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.2h
[seed 543] epoch  75/100 | lr 8.69e-05 | train BCE 0.0188 | val AP 0.2936 | best val 0.3028 @ep39 | EMA val 0.2948 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.1h
[seed 543] epoch  76/100 | lr 8.07e-05 | train BCE 0.0187 | val AP 0.2930 | best val 0.3028 @ep39 | EMA val 0.2946 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.1h
[seed 543] epoch  77/100 | lr 7.47e-05 | train BCE 0.0185 | val AP 0.2882 | best val 0.3028 @ep39 | EMA val 0.2942 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 2.0h
[seed 543] epoch  78/100 | lr 6.89e-05 | train BCE 0.0185 | val AP 0.2920 | best val 0.3028 @ep39 | EMA val 0.2939 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.9h
[seed 543] epoch  79/100 | lr 6.33e-05 | train BCE 0.0183 | val AP 0.2917 | best val 0.3028 @ep39 | EMA val 0.2935 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.8h
[seed 543] epoch  80/100 | lr 5.79e-05 | train BCE 0.0182 | val AP 0.2924 | best val 0.3028 @ep39 | EMA val 0.2930 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 1.7h
[seed 543] epoch  81/100 | lr 5.27e-05 | train BCE 0.0181 | val AP 0.2912 | best val 0.3028 @ep39 | EMA val 0.2934 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.6h
[seed 543] epoch  82/100 | lr 4.77e-05 | train BCE 0.0180 | val AP 0.2908 | best val 0.3028 @ep39 | EMA val 0.2932 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.5h
[seed 543] epoch  83/100 | lr 4.30e-05 | train BCE 0.0180 | val AP 0.2911 | best val 0.3028 @ep39 | EMA val 0.2930 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.5h
[seed 543] epoch  84/100 | lr 3.85e-05 | train BCE 0.0179 | val AP 0.2913 | best val 0.3028 @ep39 | EMA val 0.2926 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.4h
[seed 543] epoch  85/100 | lr 3.42e-05 | train BCE 0.0178 | val AP 0.2908 | best val 0.3028 @ep39 | EMA val 0.2924 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.3h
[seed 543] epoch  86/100 | lr 3.01e-05 | train BCE 0.0178 | val AP 0.2895 | best val 0.3028 @ep39 | EMA val 0.2921 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.2h
[seed 543] epoch  87/100 | lr 2.63e-05 | train BCE 0.0177 | val AP 0.2892 | best val 0.3028 @ep39 | EMA val 0.2913 | 308s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.1h
[seed 543] epoch  88/100 | lr 2.27e-05 | train BCE 0.0176 | val AP 0.2894 | best val 0.3028 @ep39 | EMA val 0.2908 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 1.0h
[seed 543] epoch  89/100 | lr 1.94e-05 | train BCE 0.0176 | val AP 0.2890 | best val 0.3028 @ep39 | EMA val 0.2905 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.9h
[seed 543] epoch  90/100 | lr 1.64e-05 | train BCE 0.0175 | val AP 0.2894 | best val 0.3028 @ep39 | EMA val 0.2903 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.9h
[seed 543] epoch  91/100 | lr 1.35e-05 | train BCE 0.0175 | val AP 0.2891 | best val 0.3028 @ep39 | EMA val 0.2902 | 309s (train 276s, eval 34s) | GPU max 89C | ETA<= 0.8h
[seed 543] epoch  92/100 | lr 1.10e-05 | train BCE 0.0174 | val AP 0.2899 | best val 0.3028 @ep39 | EMA val 0.2902 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.7h
[seed 543] epoch  93/100 | lr 8.70e-06 | train BCE 0.0174 | val AP 0.2899 | best val 0.3028 @ep39 | EMA val 0.2900 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.6h
[seed 543] epoch  94/100 | lr 6.67e-06 | train BCE 0.0174 | val AP 0.2897 | best val 0.3028 @ep39 | EMA val 0.2897 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.5h
[seed 543] epoch  95/100 | lr 4.91e-06 | train BCE 0.0174 | val AP 0.2897 | best val 0.3028 @ep39 | EMA val 0.2897 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.4h
[seed 543] epoch  96/100 | lr 3.41e-06 | train BCE 0.0174 | val AP 0.2893 | best val 0.3028 @ep39 | EMA val 0.2897 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.3h
[seed 543] epoch  97/100 | lr 2.18e-06 | train BCE 0.0173 | val AP 0.2900 | best val 0.3028 @ep39 | EMA val 0.2897 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.3h
[seed 543] epoch  98/100 | lr 1.23e-06 | train BCE 0.0173 | val AP 0.2895 | best val 0.3028 @ep39 | EMA val 0.2897 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.2h
[seed 543] epoch  99/100 | lr 5.47e-07 | train BCE 0.0173 | val AP 0.2898 | best val 0.3028 @ep39 | EMA val 0.2895 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.1h
[seed 543] epoch 100/100 | lr 1.37e-07 | train BCE 0.0173 | val AP 0.2893 | best val 0.3028 @ep39 | EMA val 0.2895 | 309s (train 275s, eval 34s) | GPU max 89C | ETA<= 0.0h
[seed 543] FINAL TEST (evaluated once): raw epoch 39 val 0.3028 test 0.2962 | EMA epoch 35 val 0.3090 test 0.3033
--- cell 16 ---
PairHGT: GPS + pair channel (pair bias + write-back, value gate) [arm PairHGT] | gps_conf_PairHGT_ep100_molpcba
 seed  epochs  raw_epoch  raw_val  raw_test  ema_epoch  ema_val  ema_test  hours  train_s_per_epoch  total_s_per_epoch
  101 100/100         39   0.3056    0.2943         40   0.3131    0.3043 8.6342           276.5795           310.8298
  202 100/100         62   0.3036    0.2963         48   0.3097    0.3062 8.5534           274.3556           307.9222
  323 100/100         50   0.3005    0.2967         45   0.3065    0.3050 8.5744           275.0306           308.6781
  432 100/100         48   0.3045    0.2982         41   0.3118    0.3119 8.5831           275.2999           308.9923
  543 100/100         39   0.3028    0.2962         35   0.3090    0.3033 8.5852           275.3636           309.0687
mean ± sample SD (ddof=1) over 5 seed(s): raw test 0.2963 ± 0.0014 | EMA test 0.3061 ± 0.0034
A mean ± SD over fewer than 3 seeds is only a description; do not call it a confidence interval.
run manifest: 11 row(s) -> /home/student/thesis/outputs/pairhgt/outputs/confirmatory/run_manifest.csv
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
  no matched finished seeds with a final test result yet
ablation A_nogate_notrip: no matched finished seeds yet
Planning table (80% power, alpha 0.05, two-sample t, test AP): smallest detectable true difference
  per-seed SD 0.003: n=3: 0.0092, n=5: 0.0061, n=10: 0.0040, n=20: 0.0027
  per-seed SD 0.0056: n=3: 0.0172, n=5: 0.0113, n=10: 0.0074, n=20: 0.0051
--- cell 20 ---
===== 2026-11-14 08:15:26 notebook turn ended (exit 0); executed notebook: /home/student/thesis/outputs/lab_runs/notebooks/pairhgt_PairHGT_seed543_20261114-0529.ipynb =====
```
