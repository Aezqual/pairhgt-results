# GPS + EMA — seed 202

[← all models](../README.md) · PairHGT notebook · ogbg-molpcba

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation AP | **0.3020** at epoch 51 |
| Best validation AP, EMA weights | 0.3085 at epoch 46 |
| Test AP | raw 0.2897 / ema 0.2947 (final) |
| Seed | 202 |
| Parameters | 9,744,860 |
| Minutes per epoch (last 5, incl. validation) | 2.9 |
| Training time so far | 4.9 h |
| Training time left | done |
| Sessions (start + resumes) | 1 |
| Hottest GPU reading | 89.0 °C |
| Last update | 2026-11-11 05:18 (84.8 h ago) |

![curves](pairhgt_GPS_ema_seed202.png)

<details><summary>Settings of this run</summary>

| Setting | Value |
|---|---|
| Epochs (warm-up) | 100 (5) |
| Batch size | 512 |
| Learning rate, weight decay | 0.0005, 1e-05 |
| Layers × width, heads | 5 × 384, 4 |
| Dropout, attention dropout | 0.2, 0.5 |
| Pair channel | no pair channel |
| Precision | fp32 (TF32 matrix products) |
| EMA decay | 0.9995 |
| Gradient clip | 1.0 |
| Protocol | v2_test_once |
| Notebook version, config hash | pairhgt-confirmatory-v2.0, 03eeeb0655c2d504 |

</details>

## Final test (evaluated once)

| Weights | Epoch | Validation AP | Test AP |
|---|---|---|---|
| raw | 51 | 0.3020 | 0.2897 |
| ema | 46 | 0.3085 | 0.2947 |

## Every epoch (newest first)

| Epoch | Train loss | Val AP | Val AP (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0193 | 0.2944 | 0.2951 | 0.3020 (ep 51) | 1.37e-07 | 2.9 |
| 99 | 0.0193 | 0.2952 | 0.2951 | 0.3020 (ep 51) | 5.47e-07 | 2.9 |
| 98 | 0.0193 | 0.2951 | 0.2951 | 0.3020 (ep 51) | 1.23e-06 | 2.9 |
| 97 | 0.0193 | 0.2948 | 0.2950 | 0.3020 (ep 51) | 2.18e-06 | 2.9 |
| 96 | 0.0193 | 0.2949 | 0.2950 | 0.3020 (ep 51) | 3.41e-06 | 2.9 |
| 95 | 0.0193 | 0.2953 | 0.2950 | 0.3020 (ep 51) | 4.91e-06 | 2.9 |
| 94 | 0.0194 | 0.2947 | 0.2951 | 0.3020 (ep 51) | 6.67e-06 | 2.9 |
| 93 | 0.0194 | 0.2948 | 0.2948 | 0.3020 (ep 51) | 8.70e-06 | 2.9 |
| 92 | 0.0194 | 0.2944 | 0.2947 | 0.3020 (ep 51) | 1.10e-05 | 2.9 |
| 91 | 0.0194 | 0.2945 | 0.2949 | 0.3020 (ep 51) | 1.35e-05 | 2.9 |
| 90 | 0.0195 | 0.2937 | 0.2951 | 0.3020 (ep 51) | 1.64e-05 | 2.9 |
| 89 | 0.0195 | 0.2923 | 0.2958 | 0.3020 (ep 51) | 1.94e-05 | 2.9 |
| 88 | 0.0196 | 0.2940 | 0.2961 | 0.3020 (ep 51) | 2.27e-05 | 2.9 |
| 87 | 0.0196 | 0.2944 | 0.2965 | 0.3020 (ep 51) | 2.63e-05 | 2.9 |
| 86 | 0.0197 | 0.2959 | 0.2966 | 0.3020 (ep 51) | 3.01e-05 | 2.9 |
| 85 | 0.0198 | 0.2950 | 0.2968 | 0.3020 (ep 51) | 3.42e-05 | 2.9 |
| 84 | 0.0198 | 0.2965 | 0.2972 | 0.3020 (ep 51) | 3.85e-05 | 2.9 |
| 83 | 0.0199 | 0.2957 | 0.2972 | 0.3020 (ep 51) | 4.30e-05 | 2.9 |
| 82 | 0.0200 | 0.2959 | 0.2975 | 0.3020 (ep 51) | 4.77e-05 | 2.9 |
| 81 | 0.0201 | 0.2963 | 0.2975 | 0.3020 (ep 51) | 5.27e-05 | 2.9 |
| 80 | 0.0202 | 0.2967 | 0.2980 | 0.3020 (ep 51) | 5.79e-05 | 2.9 |
| 79 | 0.0202 | 0.2961 | 0.2984 | 0.3020 (ep 51) | 6.33e-05 | 2.9 |
| 78 | 0.0203 | 0.2962 | 0.2987 | 0.3020 (ep 51) | 6.89e-05 | 2.9 |
| 77 | 0.0204 | 0.2963 | 0.2988 | 0.3020 (ep 51) | 7.47e-05 | 2.9 |
| 76 | 0.0205 | 0.2971 | 0.2987 | 0.3020 (ep 51) | 8.07e-05 | 2.9 |
| 75 | 0.0206 | 0.2963 | 0.2998 | 0.3020 (ep 51) | 8.69e-05 | 2.9 |
| 74 | 0.0207 | 0.2981 | 0.3002 | 0.3020 (ep 51) | 9.32e-05 | 2.9 |
| 73 | 0.0209 | 0.2976 | 0.3000 | 0.3020 (ep 51) | 9.97e-05 | 2.9 |
| 72 | 0.0210 | 0.2973 | 0.3008 | 0.3020 (ep 51) | 1.06e-04 | 2.9 |
| 71 | 0.0212 | 0.2991 | 0.3011 | 0.3020 (ep 51) | 1.13e-04 | 2.9 |
| 70 | 0.0213 | 0.2952 | 0.3013 | 0.3020 (ep 51) | 1.20e-04 | 2.9 |
| 69 | 0.0214 | 0.2975 | 0.3009 | 0.3020 (ep 51) | 1.27e-04 | 2.9 |
| 68 | 0.0216 | 0.2990 | 0.3014 | 0.3020 (ep 51) | 1.35e-04 | 2.9 |
| 67 | 0.0217 | 0.2979 | 0.3022 | 0.3020 (ep 51) | 1.42e-04 | 2.9 |
| 66 | 0.0219 | 0.2960 | 0.3028 | 0.3020 (ep 51) | 1.50e-04 | 2.9 |
| 65 | 0.0220 | 0.2973 | 0.3027 | 0.3020 (ep 51) | 1.57e-04 | 2.9 |
| 64 | 0.0222 | 0.2977 | 0.3033 | 0.3020 (ep 51) | 1.65e-04 | 2.9 |
| 63 | 0.0224 | 0.2976 | 0.3030 | 0.3020 (ep 51) | 1.73e-04 | 2.9 |
| 62 | 0.0225 | 0.2977 | 0.3032 | 0.3020 (ep 51) | 1.81e-04 | 2.9 |
| 61 | 0.0227 | 0.2991 | 0.3036 | 0.3020 (ep 51) | 1.89e-04 | 2.9 |
| 60 | 0.0230 | 0.2973 | 0.3033 | 0.3020 (ep 51) | 1.97e-04 | 2.9 |
| 59 | 0.0231 | 0.2941 | 0.3045 | 0.3020 (ep 51) | 2.05e-04 | 2.9 |
| 58 | 0.0232 | 0.2948 | 0.3052 | 0.3020 (ep 51) | 2.13e-04 | 2.9 |
| 57 | 0.0234 | 0.2973 | 0.3051 | 0.3020 (ep 51) | 2.21e-04 | 2.9 |
| 56 | 0.0236 | 0.2963 | 0.3058 | 0.3020 (ep 51) | 2.29e-04 | 2.9 |
| 55 | 0.0239 | 0.2947 | 0.3062 | 0.3020 (ep 51) | 2.38e-04 | 2.9 |
| 54 | 0.0240 | 0.2981 | 0.3068 | 0.3020 (ep 51) | 2.46e-04 | 2.9 |
| 53 | 0.0243 | 0.2978 | 0.3068 | 0.3020 (ep 51) | 2.54e-04 | 2.9 |
| 52 | 0.0244 | 0.2996 | 0.3074 | 0.3020 (ep 51) | 2.62e-04 | 2.9 |
| 51 | 0.0246 | 0.3020 ⭐ | 0.3076 | 0.3020 (ep 51) | 2.71e-04 | 2.9 |
| 50 | 0.0248 | 0.2998 | 0.3071 | 0.3001 (ep 48) | 2.79e-04 | 2.9 |
| 49 | 0.0251 | 0.2970 | 0.3075 | 0.3001 (ep 48) | 2.87e-04 | 2.9 |
| 48 | 0.0253 | 0.3001 ⭐ | 0.3076 | 0.3001 (ep 48) | 2.95e-04 | 3.0 |
| 47 | 0.0255 | 0.2972 | 0.3076 | 0.2993 (ep 42) | 3.03e-04 | 2.9 |
| 46 | 0.0257 | 0.2948 | 0.3085 | 0.2993 (ep 42) | 3.11e-04 | 2.9 |
| 45 | 0.0260 | 0.2978 | 0.3083 | 0.2993 (ep 42) | 3.19e-04 | 2.9 |
| 44 | 0.0263 | 0.2989 | 0.3067 | 0.2993 (ep 42) | 3.27e-04 | 2.9 |
| 43 | 0.0264 | 0.2908 | 0.3053 | 0.2993 (ep 42) | 3.35e-04 | 2.9 |
| 42 | 0.0266 | 0.2993 ⭐ | 0.3054 | 0.2993 (ep 42) | 3.43e-04 | 2.9 |
| 41 | 0.0268 | 0.2949 | 0.3045 | 0.2965 (ep 35) | 3.50e-04 | 2.9 |
| 40 | 0.0271 | 0.2946 | 0.3032 | 0.2965 (ep 35) | 3.58e-04 | 2.9 |
| 39 | 0.0273 | 0.2882 | 0.3033 | 0.2965 (ep 35) | 3.65e-04 | 2.9 |
| 38 | 0.0275 | 0.2921 | 0.3031 | 0.2965 (ep 35) | 3.73e-04 | 2.9 |
| 37 | 0.0277 | 0.2889 | 0.3027 | 0.2965 (ep 35) | 3.80e-04 | 2.9 |
| 36 | 0.0280 | 0.2901 | 0.3027 | 0.2965 (ep 35) | 3.87e-04 | 2.9 |
| 35 | 0.0283 | 0.2965 ⭐ | 0.3018 | 0.2965 (ep 35) | 3.94e-04 | 2.9 |
| 34 | 0.0285 | 0.2860 | 0.3009 | 0.2895 (ep 32) | 4.00e-04 | 2.9 |
| 33 | 0.0288 | 0.2808 | 0.3002 | 0.2895 (ep 32) | 4.07e-04 | 2.9 |
| 32 | 0.0293 | 0.2895 ⭐ | 0.2980 | 0.2895 (ep 32) | 4.13e-04 | 2.9 |
| 31 | 0.0292 | 0.2875 | 0.2977 | 0.2883 (ep 30) | 4.19e-04 | 2.9 |
| 30 | 0.0296 | 0.2883 ⭐ | 0.2965 | 0.2883 (ep 30) | 4.25e-04 | 2.9 |
| 29 | 0.0299 | 0.2840 | 0.2946 | 0.2853 (ep 28) | 4.31e-04 | 3.0 |
| 28 | 0.0301 | 0.2853 ⭐ | 0.2936 | 0.2853 (ep 28) | 4.37e-04 | 2.9 |
| 27 | 0.0304 | 0.2850 ⭐ | 0.2917 | 0.2850 (ep 27) | 4.42e-04 | 2.9 |
| 26 | 0.0307 | 0.2811 | 0.2903 | 0.2819 (ep 24) | 4.47e-04 | 2.9 |
| 25 | 0.0310 | 0.2811 | 0.2881 | 0.2819 (ep 24) | 4.52e-04 | 2.9 |
| 24 | 0.0314 | 0.2819 ⭐ | 0.2859 | 0.2819 (ep 24) | 4.57e-04 | 3.0 |
| 23 | 0.0318 | 0.2716 | 0.2841 | 0.2735 (ep 21) | 4.62e-04 | 2.9 |
| 22 | 0.0320 | 0.2731 | 0.2824 | 0.2735 (ep 21) | 4.66e-04 | 2.9 |
| 21 | 0.0323 | 0.2735 ⭐ | 0.2801 | 0.2735 (ep 21) | 4.70e-04 | 3.0 |
| 20 | 0.0327 | 0.2683 ⭐ | 0.2778 | 0.2683 (ep 20) | 4.74e-04 | 2.9 |
| 19 | 0.0332 | 0.2663 ⭐ | 0.2753 | 0.2663 (ep 19) | 4.77e-04 | 2.9 |
| 18 | 0.0336 | 0.2647 ⭐ | 0.2700 | 0.2647 (ep 18) | 4.81e-04 | 2.9 |
| 17 | 0.0340 | 0.2572 ⭐ | 0.2653 | 0.2572 (ep 17) | 4.84e-04 | 2.9 |
| 16 | 0.0346 | 0.2522 ⭐ | 0.2602 | 0.2522 (ep 16) | 4.86e-04 | 2.9 |
| 15 | 0.0351 | 0.2451 ⭐ | 0.2548 | 0.2451 (ep 15) | 4.89e-04 | 2.9 |
| 14 | 0.0357 | 0.2346 ⭐ | 0.2494 | 0.2346 (ep 14) | 4.91e-04 | 2.9 |
| 13 | 0.0363 | 0.2276 ⭐ | 0.2429 | 0.2276 (ep 13) | 4.93e-04 | 2.9 |
| 12 | 0.0370 | 0.2247 ⭐ | 0.2363 | 0.2247 (ep 12) | 4.95e-04 | 2.9 |
| 11 | 0.0376 | 0.2200 ⭐ | 0.2297 | 0.2200 (ep 11) | 4.97e-04 | 2.9 |
| 10 | 0.0384 | 0.2051 ⭐ | 0.2210 | 0.2051 (ep 10) | 4.98e-04 | 3.0 |
| 9 | 0.0393 | 0.1995 ⭐ | 0.2119 | 0.1995 (ep 9) | 4.99e-04 | 2.9 |
| 8 | 0.0403 | 0.1813 ⭐ | 0.1991 | 0.1813 (ep 8) | 4.99e-04 | 2.9 |
| 7 | 0.0416 | 0.1783 ⭐ | 0.1818 | 0.1783 (ep 7) | 5.00e-04 | 2.9 |
| 6 | 0.0433 | 0.1559 ⭐ | 0.1593 | 0.1559 (ep 6) | 5.00e-04 | 2.9 |
| 5 | 0.0453 | 0.1350 ⭐ | 0.1319 | 0.1350 (ep 5) | 4.00e-04 | 3.0 |
| 4 | 0.0488 | 0.1106 ⭐ | 0.1012 | 0.1106 (ep 4) | 3.00e-04 | 2.9 |
| 3 | 0.0699 | 0.0785 ⭐ | 0.0683 | 0.0785 (ep 3) | 2.00e-04 | 3.0 |
| 2 | 0.3368 | 0.0413 ⭐ | 0.0399 | 0.0413 (ep 2) | 1.00e-04 | 2.9 |
| 1 | 0.6976 | 0.0256 ⭐ | 0.0256 | 0.0256 (ep 1) | 5.00e-10 | 2.9 |

## Last 80 log lines

_The log counts epochs from 0; the tables above count from 1._

```
[seed 202] epoch  44/100 | lr 3.27e-04 | train BCE 0.0263 | val AP 0.2989 | best val 0.2993 @ep42 | EMA val 0.3067 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.7h
[seed 202] epoch  45/100 | lr 3.19e-04 | train BCE 0.0260 | val AP 0.2978 | best val 0.2993 @ep42 | EMA val 0.3083 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.7h
[seed 202] epoch  46/100 | lr 3.11e-04 | train BCE 0.0257 | val AP 0.2948 | best val 0.2993 @ep42 | EMA val 0.3085 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.6h
[seed 202] epoch  47/100 | lr 3.03e-04 | train BCE 0.0255 | val AP 0.2972 | best val 0.2993 @ep42 | EMA val 0.3076 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.6h
[seed 202] epoch  48/100 | lr 2.95e-04 | train BCE 0.0253 | val AP 0.3001 | best val 0.3001 @ep48 | EMA val 0.3076 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.6h
[seed 202] epoch  49/100 | lr 2.87e-04 | train BCE 0.0251 | val AP 0.2970 | best val 0.3001 @ep48 | EMA val 0.3075 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.5h
[seed 202] epoch  50/100 | lr 2.79e-04 | train BCE 0.0248 | val AP 0.2998 | best val 0.3001 @ep48 | EMA val 0.3071 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.5h
[seed 202] epoch  51/100 | lr 2.71e-04 | train BCE 0.0246 | val AP 0.3020 | best val 0.3020 @ep51 | EMA val 0.3076 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.4h
[seed 202] epoch  52/100 | lr 2.62e-04 | train BCE 0.0244 | val AP 0.2996 | best val 0.3020 @ep51 | EMA val 0.3074 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.3h
[seed 202] epoch  53/100 | lr 2.54e-04 | train BCE 0.0243 | val AP 0.2978 | best val 0.3020 @ep51 | EMA val 0.3068 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.3h
[seed 202] epoch  54/100 | lr 2.46e-04 | train BCE 0.0240 | val AP 0.2981 | best val 0.3020 @ep51 | EMA val 0.3068 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.3h
[seed 202] epoch  55/100 | lr 2.38e-04 | train BCE 0.0239 | val AP 0.2947 | best val 0.3020 @ep51 | EMA val 0.3062 | 175s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.2h
[seed 202] epoch  56/100 | lr 2.29e-04 | train BCE 0.0236 | val AP 0.2963 | best val 0.3020 @ep51 | EMA val 0.3058 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.1h
[seed 202] epoch  57/100 | lr 2.21e-04 | train BCE 0.0234 | val AP 0.2973 | best val 0.3020 @ep51 | EMA val 0.3051 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.1h
[seed 202] epoch  58/100 | lr 2.13e-04 | train BCE 0.0232 | val AP 0.2948 | best val 0.3020 @ep51 | EMA val 0.3052 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.1h
[seed 202] epoch  59/100 | lr 2.05e-04 | train BCE 0.0231 | val AP 0.2941 | best val 0.3020 @ep51 | EMA val 0.3045 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.0h
[seed 202] epoch  60/100 | lr 1.97e-04 | train BCE 0.0230 | val AP 0.2973 | best val 0.3020 @ep51 | EMA val 0.3033 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.0h
[seed 202] epoch  61/100 | lr 1.89e-04 | train BCE 0.0227 | val AP 0.2991 | best val 0.3020 @ep51 | EMA val 0.3036 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.9h
[seed 202] epoch  62/100 | lr 1.81e-04 | train BCE 0.0225 | val AP 0.2977 | best val 0.3020 @ep51 | EMA val 0.3032 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.9h
[seed 202] epoch  63/100 | lr 1.73e-04 | train BCE 0.0224 | val AP 0.2976 | best val 0.3020 @ep51 | EMA val 0.3030 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.8h
[seed 202] epoch  64/100 | lr 1.65e-04 | train BCE 0.0222 | val AP 0.2977 | best val 0.3020 @ep51 | EMA val 0.3033 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.8h
[seed 202] epoch  65/100 | lr 1.57e-04 | train BCE 0.0220 | val AP 0.2973 | best val 0.3020 @ep51 | EMA val 0.3027 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.7h
[seed 202] epoch  66/100 | lr 1.50e-04 | train BCE 0.0219 | val AP 0.2960 | best val 0.3020 @ep51 | EMA val 0.3028 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.7h
[seed 202] epoch  67/100 | lr 1.42e-04 | train BCE 0.0217 | val AP 0.2979 | best val 0.3020 @ep51 | EMA val 0.3022 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.6h
[seed 202] epoch  68/100 | lr 1.35e-04 | train BCE 0.0216 | val AP 0.2990 | best val 0.3020 @ep51 | EMA val 0.3014 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.6h
[seed 202] epoch  69/100 | lr 1.27e-04 | train BCE 0.0214 | val AP 0.2975 | best val 0.3020 @ep51 | EMA val 0.3009 | 175s (train 159s, eval 16s) | GPU max 89C | ETA<= 1.5h
[seed 202] epoch  70/100 | lr 1.20e-04 | train BCE 0.0213 | val AP 0.2952 | best val 0.3020 @ep51 | EMA val 0.3013 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.5h
[seed 202] epoch  71/100 | lr 1.13e-04 | train BCE 0.0212 | val AP 0.2991 | best val 0.3020 @ep51 | EMA val 0.3011 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.4h
[seed 202] epoch  72/100 | lr 1.06e-04 | train BCE 0.0210 | val AP 0.2973 | best val 0.3020 @ep51 | EMA val 0.3008 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.4h
[seed 202] epoch  73/100 | lr 9.97e-05 | train BCE 0.0209 | val AP 0.2976 | best val 0.3020 @ep51 | EMA val 0.3000 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.3h
[seed 202] epoch  74/100 | lr 9.32e-05 | train BCE 0.0207 | val AP 0.2981 | best val 0.3020 @ep51 | EMA val 0.3002 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.3h
[seed 202] epoch  75/100 | lr 8.69e-05 | train BCE 0.0206 | val AP 0.2963 | best val 0.3020 @ep51 | EMA val 0.2998 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.2h
[seed 202] epoch  76/100 | lr 8.07e-05 | train BCE 0.0205 | val AP 0.2971 | best val 0.3020 @ep51 | EMA val 0.2987 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.2h
[seed 202] epoch  77/100 | lr 7.47e-05 | train BCE 0.0204 | val AP 0.2963 | best val 0.3020 @ep51 | EMA val 0.2988 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.1h
[seed 202] epoch  78/100 | lr 6.89e-05 | train BCE 0.0203 | val AP 0.2962 | best val 0.3020 @ep51 | EMA val 0.2987 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.1h
[seed 202] epoch  79/100 | lr 6.33e-05 | train BCE 0.0202 | val AP 0.2961 | best val 0.3020 @ep51 | EMA val 0.2984 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.0h
[seed 202] epoch  80/100 | lr 5.79e-05 | train BCE 0.0202 | val AP 0.2967 | best val 0.3020 @ep51 | EMA val 0.2980 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.0h
[seed 202] epoch  81/100 | lr 5.27e-05 | train BCE 0.0201 | val AP 0.2963 | best val 0.3020 @ep51 | EMA val 0.2975 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.9h
[seed 202] epoch  82/100 | lr 4.77e-05 | train BCE 0.0200 | val AP 0.2959 | best val 0.3020 @ep51 | EMA val 0.2975 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.9h
[seed 202] epoch  83/100 | lr 4.30e-05 | train BCE 0.0199 | val AP 0.2957 | best val 0.3020 @ep51 | EMA val 0.2972 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.8h
[seed 202] epoch  84/100 | lr 3.85e-05 | train BCE 0.0198 | val AP 0.2965 | best val 0.3020 @ep51 | EMA val 0.2972 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.8h
[seed 202] epoch  85/100 | lr 3.42e-05 | train BCE 0.0198 | val AP 0.2950 | best val 0.3020 @ep51 | EMA val 0.2968 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.7h
[seed 202] epoch  86/100 | lr 3.01e-05 | train BCE 0.0197 | val AP 0.2959 | best val 0.3020 @ep51 | EMA val 0.2966 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.7h
[seed 202] epoch  87/100 | lr 2.63e-05 | train BCE 0.0196 | val AP 0.2944 | best val 0.3020 @ep51 | EMA val 0.2965 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.6h
[seed 202] epoch  88/100 | lr 2.27e-05 | train BCE 0.0196 | val AP 0.2940 | best val 0.3020 @ep51 | EMA val 0.2961 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.6h
[seed 202] epoch  89/100 | lr 1.94e-05 | train BCE 0.0195 | val AP 0.2923 | best val 0.3020 @ep51 | EMA val 0.2958 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.5h
[seed 202] epoch  90/100 | lr 1.64e-05 | train BCE 0.0195 | val AP 0.2937 | best val 0.3020 @ep51 | EMA val 0.2951 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.5h
[seed 202] epoch  91/100 | lr 1.35e-05 | train BCE 0.0194 | val AP 0.2945 | best val 0.3020 @ep51 | EMA val 0.2949 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.4h
[seed 202] epoch  92/100 | lr 1.10e-05 | train BCE 0.0194 | val AP 0.2944 | best val 0.3020 @ep51 | EMA val 0.2947 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.4h
[seed 202] epoch  93/100 | lr 8.70e-06 | train BCE 0.0194 | val AP 0.2948 | best val 0.3020 @ep51 | EMA val 0.2948 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.3h
[seed 202] epoch  94/100 | lr 6.67e-06 | train BCE 0.0194 | val AP 0.2947 | best val 0.3020 @ep51 | EMA val 0.2951 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.3h
[seed 202] epoch  95/100 | lr 4.91e-06 | train BCE 0.0193 | val AP 0.2953 | best val 0.3020 @ep51 | EMA val 0.2950 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.2h
[seed 202] epoch  96/100 | lr 3.41e-06 | train BCE 0.0193 | val AP 0.2949 | best val 0.3020 @ep51 | EMA val 0.2950 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.2h
[seed 202] epoch  97/100 | lr 2.18e-06 | train BCE 0.0193 | val AP 0.2948 | best val 0.3020 @ep51 | EMA val 0.2950 | 175s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.1h
[seed 202] epoch  98/100 | lr 1.23e-06 | train BCE 0.0193 | val AP 0.2951 | best val 0.3020 @ep51 | EMA val 0.2951 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.1h
[seed 202] epoch  99/100 | lr 5.47e-07 | train BCE 0.0193 | val AP 0.2952 | best val 0.3020 @ep51 | EMA val 0.2951 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.0h
[seed 202] epoch 100/100 | lr 1.37e-07 | train BCE 0.0193 | val AP 0.2944 | best val 0.3020 @ep51 | EMA val 0.2951 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.0h
[seed 202] FINAL TEST (evaluated once): raw epoch 51 val 0.3020 test 0.2897 | EMA epoch 46 val 0.3085 test 0.2947
--- cell 16 ---
GPS (plain) + EMA [arm GPS_ema] | gps_conf_GPS_ema_ep100_molpcba
 seed  epochs  raw_epoch  raw_val  raw_test  ema_epoch  ema_val  ema_test  hours  train_s_per_epoch  total_s_per_epoch
  101 100/100         56   0.3044    0.2900         50   0.3103    0.2995 4.9304           160.8465           177.4936
  202 100/100         51   0.3020    0.2897         46   0.3085    0.2947 4.8991           160.7075           176.3669
mean ± sample SD (ddof=1) over 2 seed(s): raw test 0.2898 ± 0.0002 | EMA test 0.2971 ± 0.0034
A mean ± SD over fewer than 3 seeds is only a description; do not call it a confidence interval.
/tmp/ipykernel_89596/1726116603.py:55: UserWarning: No artists with labels found to put in legend.  Note that artists whose label start with an underscore are ignored when legend() is called with no argument.
  ax.set(title=f"seed {s} (circle = selected raw, square = selected EMA)", xlabel="epoch", ylabel="validation AP"); ax.grid(alpha=0.25); ax.legend(fontsize=7)
run manifest: 3 row(s) -> /home/student/thesis/outputs/pairhgt/outputs/confirmatory/run_manifest.csv
    model              gpu  seeds  params  train_s_per_epoch  val_eval_s_per_epoch  total_s_per_epoch  hours_per_seed  time_vs_GPS+EMA
GPS + EMA NVIDIA RTX A4000      2 9744860             160.78                 16.13             176.93            4.91             1.00
  PairHGT NVIDIA RTX A4000      1 9751972             277.44                 34.54             312.00            5.81             1.76
train = training steps incl. EMA update; val_eval = validation of raw + EMA weights; no test pass inside an epoch (protocol v2). Do not compare with timings from the exploratory runs.
--- cell 18 ---
=== PairHGT  minus  GPS + EMA   (100 epochs, matched seeds) ===
  no matched finished seeds with a final test result yet
Planning table (80% power, alpha 0.05, two-sample t, test AP): smallest detectable true difference
  per-seed SD 0.003: n=3: 0.0092, n=5: 0.0061, n=10: 0.0040, n=20: 0.0027
  per-seed SD 0.0056: n=3: 0.0172, n=5: 0.0113, n=10: 0.0074, n=20: 0.0051
--- cell 20 ---
===== 2026-11-11 05:18:54 notebook turn ended (exit 0); executed notebook: /home/student/thesis/outputs/lab_runs/notebooks/pairhgt_GPS_ema_seed202_20261111-0023.ipynb =====
```
