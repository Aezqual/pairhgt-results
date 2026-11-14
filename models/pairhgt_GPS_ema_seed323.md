# GPS + EMA — seed 323

[← all models](../README.md) · PairHGT notebook · ogbg-molpcba

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation AP | **0.2984** at epoch 53 |
| Best validation AP, EMA weights | 0.3043 at epoch 37 |
| Test AP | raw 0.2948 / ema 0.2994 (final) |
| Seed | 323 |
| Parameters | 9,744,860 |
| Minutes per epoch (last 5, incl. validation) | 2.9 |
| Training time so far | 4.9 h |
| Training time left | done |
| Sessions (start + resumes) | 1 |
| Hottest GPU reading | 89.0 °C |
| Last update | 2026-11-11 23:53 (66.2 h ago) |

![curves](pairhgt_GPS_ema_seed323.png)

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
| raw | 53 | 0.2984 | 0.2948 |
| ema | 37 | 0.3043 | 0.2994 |

## Every epoch (newest first)

| Epoch | Train loss | Val AP | Val AP (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0191 | 0.2884 | 0.2883 | 0.2984 (ep 53) | 1.37e-07 | 2.9 |
| 99 | 0.0191 | 0.2880 | 0.2884 | 0.2984 (ep 53) | 5.47e-07 | 2.9 |
| 98 | 0.0191 | 0.2879 | 0.2884 | 0.2984 (ep 53) | 1.23e-06 | 2.9 |
| 97 | 0.0191 | 0.2879 | 0.2885 | 0.2984 (ep 53) | 2.18e-06 | 3.0 |
| 96 | 0.0191 | 0.2889 | 0.2886 | 0.2984 (ep 53) | 3.41e-06 | 2.9 |
| 95 | 0.0192 | 0.2884 | 0.2887 | 0.2984 (ep 53) | 4.91e-06 | 2.9 |
| 94 | 0.0191 | 0.2883 | 0.2887 | 0.2984 (ep 53) | 6.67e-06 | 2.9 |
| 93 | 0.0192 | 0.2879 | 0.2889 | 0.2984 (ep 53) | 8.70e-06 | 2.9 |
| 92 | 0.0192 | 0.2885 | 0.2890 | 0.2984 (ep 53) | 1.10e-05 | 2.9 |
| 91 | 0.0193 | 0.2882 | 0.2892 | 0.2984 (ep 53) | 1.35e-05 | 2.9 |
| 90 | 0.0193 | 0.2887 | 0.2894 | 0.2984 (ep 53) | 1.64e-05 | 2.9 |
| 89 | 0.0194 | 0.2888 | 0.2895 | 0.2984 (ep 53) | 1.94e-05 | 2.9 |
| 88 | 0.0194 | 0.2891 | 0.2897 | 0.2984 (ep 53) | 2.27e-05 | 2.9 |
| 87 | 0.0194 | 0.2895 | 0.2900 | 0.2984 (ep 53) | 2.63e-05 | 2.9 |
| 86 | 0.0195 | 0.2895 | 0.2898 | 0.2984 (ep 53) | 3.01e-05 | 2.9 |
| 85 | 0.0196 | 0.2892 | 0.2899 | 0.2984 (ep 53) | 3.42e-05 | 2.9 |
| 84 | 0.0197 | 0.2899 | 0.2900 | 0.2984 (ep 53) | 3.85e-05 | 2.9 |
| 83 | 0.0197 | 0.2897 | 0.2903 | 0.2984 (ep 53) | 4.30e-05 | 2.9 |
| 82 | 0.0197 | 0.2896 | 0.2904 | 0.2984 (ep 53) | 4.77e-05 | 2.9 |
| 81 | 0.0198 | 0.2892 | 0.2907 | 0.2984 (ep 53) | 5.27e-05 | 2.9 |
| 80 | 0.0200 | 0.2889 | 0.2905 | 0.2984 (ep 53) | 5.79e-05 | 2.9 |
| 79 | 0.0200 | 0.2886 | 0.2906 | 0.2984 (ep 53) | 6.33e-05 | 3.0 |
| 78 | 0.0202 | 0.2873 | 0.2911 | 0.2984 (ep 53) | 6.89e-05 | 2.9 |
| 77 | 0.0203 | 0.2880 | 0.2916 | 0.2984 (ep 53) | 7.47e-05 | 3.0 |
| 76 | 0.0204 | 0.2892 | 0.2919 | 0.2984 (ep 53) | 8.07e-05 | 2.9 |
| 75 | 0.0205 | 0.2900 | 0.2926 | 0.2984 (ep 53) | 8.69e-05 | 2.9 |
| 74 | 0.0206 | 0.2883 | 0.2929 | 0.2984 (ep 53) | 9.32e-05 | 2.9 |
| 73 | 0.0207 | 0.2871 | 0.2935 | 0.2984 (ep 53) | 9.97e-05 | 2.9 |
| 72 | 0.0209 | 0.2881 | 0.2942 | 0.2984 (ep 53) | 1.06e-04 | 2.9 |
| 71 | 0.0210 | 0.2886 | 0.2945 | 0.2984 (ep 53) | 1.13e-04 | 2.9 |
| 70 | 0.0211 | 0.2901 | 0.2960 | 0.2984 (ep 53) | 1.20e-04 | 2.9 |
| 69 | 0.0213 | 0.2887 | 0.2969 | 0.2984 (ep 53) | 1.27e-04 | 2.9 |
| 68 | 0.0214 | 0.2896 | 0.2976 | 0.2984 (ep 53) | 1.35e-04 | 2.9 |
| 67 | 0.0216 | 0.2905 | 0.2977 | 0.2984 (ep 53) | 1.42e-04 | 2.9 |
| 66 | 0.0217 | 0.2925 | 0.2982 | 0.2984 (ep 53) | 1.50e-04 | 2.9 |
| 65 | 0.0219 | 0.2897 | 0.2980 | 0.2984 (ep 53) | 1.57e-04 | 3.0 |
| 64 | 0.0220 | 0.2919 | 0.2979 | 0.2984 (ep 53) | 1.65e-04 | 2.9 |
| 63 | 0.0222 | 0.2954 | 0.2982 | 0.2984 (ep 53) | 1.73e-04 | 3.0 |
| 62 | 0.0224 | 0.2910 | 0.2982 | 0.2984 (ep 53) | 1.81e-04 | 2.9 |
| 61 | 0.0226 | 0.2942 | 0.2981 | 0.2984 (ep 53) | 1.89e-04 | 2.9 |
| 60 | 0.0227 | 0.2933 | 0.2982 | 0.2984 (ep 53) | 1.97e-04 | 2.9 |
| 59 | 0.0229 | 0.2932 | 0.2986 | 0.2984 (ep 53) | 2.05e-04 | 3.0 |
| 58 | 0.0231 | 0.2889 | 0.2999 | 0.2984 (ep 53) | 2.13e-04 | 2.9 |
| 57 | 0.0233 | 0.2895 | 0.3007 | 0.2984 (ep 53) | 2.21e-04 | 2.9 |
| 56 | 0.0235 | 0.2905 | 0.3019 | 0.2984 (ep 53) | 2.29e-04 | 2.9 |
| 55 | 0.0237 | 0.2920 | 0.3021 | 0.2984 (ep 53) | 2.38e-04 | 2.9 |
| 54 | 0.0239 | 0.2916 | 0.3022 | 0.2984 (ep 53) | 2.46e-04 | 2.9 |
| 53 | 0.0241 | 0.2984 ⭐ | 0.3020 | 0.2984 (ep 53) | 2.54e-04 | 3.0 |
| 52 | 0.0243 | 0.2944 | 0.3031 | 0.2976 (ep 47) | 2.62e-04 | 2.9 |
| 51 | 0.0245 | 0.2950 | 0.3024 | 0.2976 (ep 47) | 2.71e-04 | 2.9 |
| 50 | 0.0247 | 0.2948 | 0.3027 | 0.2976 (ep 47) | 2.79e-04 | 2.9 |
| 49 | 0.0249 | 0.2940 | 0.3018 | 0.2976 (ep 47) | 2.87e-04 | 3.0 |
| 48 | 0.0251 | 0.2947 | 0.3023 | 0.2976 (ep 47) | 2.95e-04 | 2.9 |
| 47 | 0.0253 | 0.2976 ⭐ | 0.3023 | 0.2976 (ep 47) | 3.03e-04 | 2.9 |
| 46 | 0.0255 | 0.2950 | 0.3027 | 0.2953 (ep 41) | 3.11e-04 | 2.9 |
| 45 | 0.0257 | 0.2924 | 0.3032 | 0.2953 (ep 41) | 3.19e-04 | 2.9 |
| 44 | 0.0260 | 0.2916 | 0.3043 | 0.2953 (ep 41) | 3.27e-04 | 2.9 |
| 43 | 0.0262 | 0.2944 | 0.3038 | 0.2953 (ep 41) | 3.35e-04 | 2.9 |
| 42 | 0.0264 | 0.2929 | 0.3030 | 0.2953 (ep 41) | 3.43e-04 | 2.9 |
| 41 | 0.0266 | 0.2953 ⭐ | 0.3019 | 0.2953 (ep 41) | 3.50e-04 | 2.9 |
| 40 | 0.0268 | 0.2930 ⭐ | 0.3016 | 0.2930 (ep 40) | 3.58e-04 | 2.9 |
| 39 | 0.0271 | 0.2899 | 0.3027 | 0.2925 (ep 35) | 3.65e-04 | 2.9 |
| 38 | 0.0273 | 0.2876 | 0.3041 | 0.2925 (ep 35) | 3.73e-04 | 2.9 |
| 37 | 0.0276 | 0.2906 | 0.3043 | 0.2925 (ep 35) | 3.80e-04 | 2.9 |
| 36 | 0.0278 | 0.2897 | 0.3040 | 0.2925 (ep 35) | 3.87e-04 | 2.9 |
| 35 | 0.0280 | 0.2925 ⭐ | 0.3028 | 0.2925 (ep 35) | 3.94e-04 | 2.9 |
| 34 | 0.0283 | 0.2888 | 0.3019 | 0.2904 (ep 30) | 4.00e-04 | 2.9 |
| 33 | 0.0285 | 0.2879 | 0.3007 | 0.2904 (ep 30) | 4.07e-04 | 2.9 |
| 32 | 0.0288 | 0.2839 | 0.2990 | 0.2904 (ep 30) | 4.13e-04 | 2.9 |
| 31 | 0.0291 | 0.2840 | 0.2993 | 0.2904 (ep 30) | 4.19e-04 | 2.9 |
| 30 | 0.0294 | 0.2904 ⭐ | 0.2983 | 0.2904 (ep 30) | 4.25e-04 | 2.9 |
| 29 | 0.0297 | 0.2816 | 0.2970 | 0.2857 (ep 28) | 4.31e-04 | 2.9 |
| 28 | 0.0299 | 0.2857 ⭐ | 0.2964 | 0.2857 (ep 28) | 4.37e-04 | 2.9 |
| 27 | 0.0303 | 0.2781 | 0.2934 | 0.2833 (ep 25) | 4.42e-04 | 2.9 |
| 26 | 0.0306 | 0.2820 | 0.2907 | 0.2833 (ep 25) | 4.47e-04 | 2.9 |
| 25 | 0.0309 | 0.2833 ⭐ | 0.2882 | 0.2833 (ep 25) | 4.52e-04 | 3.0 |
| 24 | 0.0312 | 0.2742 | 0.2854 | 0.2742 (ep 22) | 4.57e-04 | 2.9 |
| 23 | 0.0316 | 0.2696 | 0.2833 | 0.2742 (ep 22) | 4.62e-04 | 2.9 |
| 22 | 0.0319 | 0.2742 ⭐ | 0.2808 | 0.2742 (ep 22) | 4.66e-04 | 2.9 |
| 21 | 0.0323 | 0.2708 ⭐ | 0.2773 | 0.2708 (ep 21) | 4.70e-04 | 2.9 |
| 20 | 0.0327 | 0.2686 ⭐ | 0.2735 | 0.2686 (ep 20) | 4.74e-04 | 2.9 |
| 19 | 0.0331 | 0.2675 ⭐ | 0.2705 | 0.2675 (ep 19) | 4.77e-04 | 3.0 |
| 18 | 0.0336 | 0.2582 ⭐ | 0.2667 | 0.2582 (ep 18) | 4.81e-04 | 2.9 |
| 17 | 0.0340 | 0.2567 ⭐ | 0.2629 | 0.2567 (ep 17) | 4.84e-04 | 2.9 |
| 16 | 0.0345 | 0.2490 ⭐ | 0.2589 | 0.2490 (ep 16) | 4.86e-04 | 3.0 |
| 15 | 0.0351 | 0.2444 ⭐ | 0.2543 | 0.2444 (ep 15) | 4.89e-04 | 2.9 |
| 14 | 0.0358 | 0.2402 ⭐ | 0.2495 | 0.2402 (ep 14) | 4.91e-04 | 2.9 |
| 13 | 0.0364 | 0.2310 | 0.2436 | 0.2318 (ep 12) | 4.93e-04 | 2.9 |
| 12 | 0.0370 | 0.2318 ⭐ | 0.2368 | 0.2318 (ep 12) | 4.95e-04 | 3.0 |
| 11 | 0.0377 | 0.2142 ⭐ | 0.2289 | 0.2142 (ep 11) | 4.97e-04 | 2.9 |
| 10 | 0.0384 | 0.2071 ⭐ | 0.2198 | 0.2071 (ep 10) | 4.98e-04 | 3.0 |
| 9 | 0.0393 | 0.1964 ⭐ | 0.2097 | 0.1964 (ep 9) | 4.99e-04 | 2.9 |
| 8 | 0.0402 | 0.1901 ⭐ | 0.1973 | 0.1901 (ep 8) | 4.99e-04 | 3.0 |
| 7 | 0.0414 | 0.1780 ⭐ | 0.1804 | 0.1780 (ep 7) | 5.00e-04 | 2.9 |
| 6 | 0.0431 | 0.1624 ⭐ | 0.1588 | 0.1624 (ep 6) | 5.00e-04 | 2.9 |
| 5 | 0.0451 | 0.1389 ⭐ | 0.1331 | 0.1389 (ep 5) | 4.00e-04 | 2.9 |
| 4 | 0.0492 | 0.1107 ⭐ | 0.0987 | 0.1107 (ep 4) | 3.00e-04 | 2.9 |
| 3 | 0.0671 | 0.0713 ⭐ | 0.0655 | 0.0713 (ep 3) | 2.00e-04 | 2.9 |
| 2 | 0.3270 | 0.0431 ⭐ | 0.0402 | 0.0431 (ep 2) | 1.00e-04 | 2.9 |
| 1 | 0.6969 | 0.0240 ⭐ | 0.0240 | 0.0240 (ep 1) | 5.00e-10 | 2.9 |

## Last 80 log lines

_The log counts epochs from 0; the tables above count from 1._

```
[seed 323] epoch  51/100 | lr 2.71e-04 | train BCE 0.0245 | val AP 0.2950 | best val 0.2976 @ep47 | EMA val 0.3024 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.4h
[seed 323] epoch  52/100 | lr 2.62e-04 | train BCE 0.0243 | val AP 0.2944 | best val 0.2976 @ep47 | EMA val 0.3031 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.4h
[seed 323] epoch  53/100 | lr 2.54e-04 | train BCE 0.0241 | val AP 0.2984 | best val 0.2984 @ep53 | EMA val 0.3020 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.3h
[seed 323] epoch  54/100 | lr 2.46e-04 | train BCE 0.0239 | val AP 0.2916 | best val 0.2984 @ep53 | EMA val 0.3022 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.3h
[seed 323] epoch  55/100 | lr 2.38e-04 | train BCE 0.0237 | val AP 0.2920 | best val 0.2984 @ep53 | EMA val 0.3021 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.2h
[seed 323] epoch  56/100 | lr 2.29e-04 | train BCE 0.0235 | val AP 0.2905 | best val 0.2984 @ep53 | EMA val 0.3019 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.2h
[seed 323] epoch  57/100 | lr 2.21e-04 | train BCE 0.0233 | val AP 0.2895 | best val 0.2984 @ep53 | EMA val 0.3007 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.1h
[seed 323] epoch  58/100 | lr 2.13e-04 | train BCE 0.0231 | val AP 0.2889 | best val 0.2984 @ep53 | EMA val 0.2999 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 2.1h
[seed 323] epoch  59/100 | lr 2.05e-04 | train BCE 0.0229 | val AP 0.2932 | best val 0.2984 @ep53 | EMA val 0.2986 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.0h
[seed 323] epoch  60/100 | lr 1.97e-04 | train BCE 0.0227 | val AP 0.2933 | best val 0.2984 @ep53 | EMA val 0.2982 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 2.0h
[seed 323] epoch  61/100 | lr 1.89e-04 | train BCE 0.0226 | val AP 0.2942 | best val 0.2984 @ep53 | EMA val 0.2981 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.9h
[seed 323] epoch  62/100 | lr 1.81e-04 | train BCE 0.0224 | val AP 0.2910 | best val 0.2984 @ep53 | EMA val 0.2982 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.9h
[seed 323] epoch  63/100 | lr 1.73e-04 | train BCE 0.0222 | val AP 0.2954 | best val 0.2984 @ep53 | EMA val 0.2982 | 177s (train 162s, eval 16s) | GPU max 89C | ETA<= 1.8h
[seed 323] epoch  64/100 | lr 1.65e-04 | train BCE 0.0220 | val AP 0.2919 | best val 0.2984 @ep53 | EMA val 0.2979 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.8h
[seed 323] epoch  65/100 | lr 1.57e-04 | train BCE 0.0219 | val AP 0.2897 | best val 0.2984 @ep53 | EMA val 0.2980 | 177s (train 162s, eval 16s) | GPU max 89C | ETA<= 1.7h
[seed 323] epoch  66/100 | lr 1.50e-04 | train BCE 0.0217 | val AP 0.2925 | best val 0.2984 @ep53 | EMA val 0.2982 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.7h
[seed 323] epoch  67/100 | lr 1.42e-04 | train BCE 0.0216 | val AP 0.2905 | best val 0.2984 @ep53 | EMA val 0.2977 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.6h
[seed 323] epoch  68/100 | lr 1.35e-04 | train BCE 0.0214 | val AP 0.2896 | best val 0.2984 @ep53 | EMA val 0.2976 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.6h
[seed 323] epoch  69/100 | lr 1.27e-04 | train BCE 0.0213 | val AP 0.2887 | best val 0.2984 @ep53 | EMA val 0.2969 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.5h
[seed 323] epoch  70/100 | lr 1.20e-04 | train BCE 0.0211 | val AP 0.2901 | best val 0.2984 @ep53 | EMA val 0.2960 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.5h
[seed 323] epoch  71/100 | lr 1.13e-04 | train BCE 0.0210 | val AP 0.2886 | best val 0.2984 @ep53 | EMA val 0.2945 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.4h
[seed 323] epoch  72/100 | lr 1.06e-04 | train BCE 0.0209 | val AP 0.2881 | best val 0.2984 @ep53 | EMA val 0.2942 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.4h
[seed 323] epoch  73/100 | lr 9.97e-05 | train BCE 0.0207 | val AP 0.2871 | best val 0.2984 @ep53 | EMA val 0.2935 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.3h
[seed 323] epoch  74/100 | lr 9.32e-05 | train BCE 0.0206 | val AP 0.2883 | best val 0.2984 @ep53 | EMA val 0.2929 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.3h
[seed 323] epoch  75/100 | lr 8.69e-05 | train BCE 0.0205 | val AP 0.2900 | best val 0.2984 @ep53 | EMA val 0.2926 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.2h
[seed 323] epoch  76/100 | lr 8.07e-05 | train BCE 0.0204 | val AP 0.2892 | best val 0.2984 @ep53 | EMA val 0.2919 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.2h
[seed 323] epoch  77/100 | lr 7.47e-05 | train BCE 0.0203 | val AP 0.2880 | best val 0.2984 @ep53 | EMA val 0.2916 | 177s (train 162s, eval 16s) | GPU max 89C | ETA<= 1.1h
[seed 323] epoch  78/100 | lr 6.89e-05 | train BCE 0.0202 | val AP 0.2873 | best val 0.2984 @ep53 | EMA val 0.2911 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 1.1h
[seed 323] epoch  79/100 | lr 6.33e-05 | train BCE 0.0200 | val AP 0.2886 | best val 0.2984 @ep53 | EMA val 0.2906 | 177s (train 162s, eval 16s) | GPU max 89C | ETA<= 1.0h
[seed 323] epoch  80/100 | lr 5.79e-05 | train BCE 0.0200 | val AP 0.2889 | best val 0.2984 @ep53 | EMA val 0.2905 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 1.0h
[seed 323] epoch  81/100 | lr 5.27e-05 | train BCE 0.0198 | val AP 0.2892 | best val 0.2984 @ep53 | EMA val 0.2907 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.9h
[seed 323] epoch  82/100 | lr 4.77e-05 | train BCE 0.0197 | val AP 0.2896 | best val 0.2984 @ep53 | EMA val 0.2904 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.9h
[seed 323] epoch  83/100 | lr 4.30e-05 | train BCE 0.0197 | val AP 0.2897 | best val 0.2984 @ep53 | EMA val 0.2903 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.8h
[seed 323] epoch  84/100 | lr 3.85e-05 | train BCE 0.0197 | val AP 0.2899 | best val 0.2984 @ep53 | EMA val 0.2900 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.8h
[seed 323] epoch  85/100 | lr 3.42e-05 | train BCE 0.0196 | val AP 0.2892 | best val 0.2984 @ep53 | EMA val 0.2899 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.7h
[seed 323] epoch  86/100 | lr 3.01e-05 | train BCE 0.0195 | val AP 0.2895 | best val 0.2984 @ep53 | EMA val 0.2898 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.7h
[seed 323] epoch  87/100 | lr 2.63e-05 | train BCE 0.0194 | val AP 0.2895 | best val 0.2984 @ep53 | EMA val 0.2900 | 175s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.6h
[seed 323] epoch  88/100 | lr 2.27e-05 | train BCE 0.0194 | val AP 0.2891 | best val 0.2984 @ep53 | EMA val 0.2897 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.6h
[seed 323] epoch  89/100 | lr 1.94e-05 | train BCE 0.0194 | val AP 0.2888 | best val 0.2984 @ep53 | EMA val 0.2895 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.5h
[seed 323] epoch  90/100 | lr 1.64e-05 | train BCE 0.0193 | val AP 0.2887 | best val 0.2984 @ep53 | EMA val 0.2894 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.5h
[seed 323] epoch  91/100 | lr 1.35e-05 | train BCE 0.0193 | val AP 0.2882 | best val 0.2984 @ep53 | EMA val 0.2892 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.4h
[seed 323] epoch  92/100 | lr 1.10e-05 | train BCE 0.0192 | val AP 0.2885 | best val 0.2984 @ep53 | EMA val 0.2890 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.4h
[seed 323] epoch  93/100 | lr 8.70e-06 | train BCE 0.0192 | val AP 0.2879 | best val 0.2984 @ep53 | EMA val 0.2889 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.3h
[seed 323] epoch  94/100 | lr 6.67e-06 | train BCE 0.0191 | val AP 0.2883 | best val 0.2984 @ep53 | EMA val 0.2887 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.3h
[seed 323] epoch  95/100 | lr 4.91e-06 | train BCE 0.0192 | val AP 0.2884 | best val 0.2984 @ep53 | EMA val 0.2887 | 176s (train 160s, eval 16s) | GPU max 89C | ETA<= 0.2h
[seed 323] epoch  96/100 | lr 3.41e-06 | train BCE 0.0191 | val AP 0.2889 | best val 0.2984 @ep53 | EMA val 0.2886 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.2h
[seed 323] epoch  97/100 | lr 2.18e-06 | train BCE 0.0191 | val AP 0.2879 | best val 0.2984 @ep53 | EMA val 0.2885 | 177s (train 162s, eval 16s) | GPU max 89C | ETA<= 0.1h
[seed 323] epoch  98/100 | lr 1.23e-06 | train BCE 0.0191 | val AP 0.2879 | best val 0.2984 @ep53 | EMA val 0.2884 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.1h
[seed 323] epoch  99/100 | lr 5.47e-07 | train BCE 0.0191 | val AP 0.2880 | best val 0.2984 @ep53 | EMA val 0.2884 | 177s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.0h
[seed 323] epoch 100/100 | lr 1.37e-07 | train BCE 0.0191 | val AP 0.2884 | best val 0.2984 @ep53 | EMA val 0.2883 | 176s (train 161s, eval 16s) | GPU max 89C | ETA<= 0.0h
[seed 323] FINAL TEST (evaluated once): raw epoch 53 val 0.2984 test 0.2948 | EMA epoch 37 val 0.3043 test 0.2994
--- cell 16 ---
GPS (plain) + EMA [arm GPS_ema] | gps_conf_GPS_ema_ep100_molpcba
 seed  epochs  raw_epoch  raw_val  raw_test  ema_epoch  ema_val  ema_test  hours  train_s_per_epoch  total_s_per_epoch
  101 100/100         56   0.3044    0.2900         50   0.3103    0.2995 4.9304           160.8465           177.4936
  202 100/100         51   0.3020    0.2897         46   0.3085    0.2947 4.8991           160.7075           176.3669
  323 100/100         53   0.2984    0.2948         37   0.3043    0.2994 4.9005           160.7710           176.4181
mean ± sample SD (ddof=1) over 3 seed(s): raw test 0.2915 ± 0.0029 | EMA test 0.2979 ± 0.0028
A mean ± SD over fewer than 3 seeds is only a description; do not call it a confidence interval.
/tmp/ipykernel_216633/1726116603.py:55: UserWarning: No artists with labels found to put in legend.  Note that artists whose label start with an underscore are ignored when legend() is called with no argument.
  ax.set(title=f"seed {s} (circle = selected raw, square = selected EMA)", xlabel="epoch", ylabel="validation AP"); ax.grid(alpha=0.25); ax.legend(fontsize=7)
run manifest: 5 row(s) -> /home/student/thesis/outputs/pairhgt/outputs/confirmatory/run_manifest.csv
    model              gpu  seeds  params  train_s_per_epoch  val_eval_s_per_epoch  total_s_per_epoch  hours_per_seed  time_vs_GPS+EMA
GPS + EMA NVIDIA RTX A4000      3 9744860             160.78                 15.96             176.76            4.91             1.00
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
===== 2026-11-11 23:53:53 notebook turn ended (exit 0); executed notebook: /home/student/thesis/outputs/lab_runs/notebooks/pairhgt_GPS_ema_seed323_20261111-1858.ipynb =====
```
