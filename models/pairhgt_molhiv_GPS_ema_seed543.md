# GPS + EMA · ogbg-molhiv (ROC-AUC) — seed 543

[← all models](../README.md) · PairHGT notebook · ogbg-molhiv

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation ROC-AUC | **0.8255** at epoch 14 |
| Best validation ROC-AUC, EMA weights | 0.8219 at epoch 20 |
| Test ROC-AUC | raw 0.7734 / ema 0.7782 (final) |
| Seed | 543 |
| Parameters | 558,673 |
| Minutes per epoch (last 5, incl. validation) | 0.8 |
| Training time so far | 1.4 h |
| Training time left | done |
| Sessions (start + resumes) | 1 |
| Hottest GPU reading | 53.0 °C |
| Last update | 2026-11-23 08:26 (129.7 h ago) |

![curves](pairhgt_molhiv_GPS_ema_seed543.png)

<details><summary>Settings of this run</summary>

| Setting | Value |
|---|---|
| Epochs (warm-up) | 100 (5) |
| Batch size | 32 |
| Learning rate, weight decay | 0.0001, 1e-05 |
| Layers × width, heads | 10 × 64, 4 |
| Dropout, attention dropout | 0.05, 0.5 |
| Pair channel | no pair channel |
| Precision | fp32 (TF32 matrix products) |
| EMA decay | 0.9996632505026597 |
| Gradient clip | 1.0 |
| Protocol | v2_test_once |
| Notebook version, config hash | pairhgt-generalization-v1.0, 7b53e24f167e1773 |

</details>

## Final test (evaluated once)

| Weights | Epoch | Validation ROC-AUC | Test ROC-AUC |
|---|---|---|---|
| raw | 14 | 0.8255 | 0.7734 |
| ema | 20 | 0.8219 | 0.7782 |

## Every epoch (newest first)

| Epoch | Train loss | Val ROC-AUC | Val ROC-AUC (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0424 | 0.7915 | 0.7964 | 0.8255 (ep 14) | 2.73e-08 | 0.8 |
| 99 | 0.0415 | 0.7991 | 0.7965 | 0.8255 (ep 14) | 1.09e-07 | 0.8 |
| 98 | 0.0427 | 0.7940 | 0.7965 | 0.8255 (ep 14) | 2.46e-07 | 0.8 |
| 97 | 0.0420 | 0.7894 | 0.7966 | 0.8255 (ep 14) | 4.37e-07 | 0.8 |
| 96 | 0.0426 | 0.7962 | 0.7966 | 0.8255 (ep 14) | 6.82e-07 | 0.8 |
| 95 | 0.0431 | 0.7956 | 0.7968 | 0.8255 (ep 14) | 9.81e-07 | 0.8 |
| 94 | 0.0429 | 0.7989 | 0.7970 | 0.8255 (ep 14) | 1.33e-06 | 0.8 |
| 93 | 0.0433 | 0.7877 | 0.7971 | 0.8255 (ep 14) | 1.74e-06 | 0.8 |
| 92 | 0.0440 | 0.7926 | 0.7975 | 0.8255 (ep 14) | 2.20e-06 | 0.8 |
| 91 | 0.0447 | 0.7965 | 0.7977 | 0.8255 (ep 14) | 2.71e-06 | 0.8 |
| 90 | 0.0440 | 0.7935 | 0.7978 | 0.8255 (ep 14) | 3.27e-06 | 0.8 |
| 89 | 0.0422 | 0.7985 | 0.7977 | 0.8255 (ep 14) | 3.89e-06 | 0.8 |
| 88 | 0.0442 | 0.7931 | 0.7974 | 0.8255 (ep 14) | 4.55e-06 | 0.8 |
| 87 | 0.0444 | 0.7922 | 0.7966 | 0.8255 (ep 14) | 5.26e-06 | 0.8 |
| 86 | 0.0428 | 0.7977 | 0.7964 | 0.8255 (ep 14) | 6.03e-06 | 0.8 |
| 85 | 0.0438 | 0.7982 | 0.7958 | 0.8255 (ep 14) | 6.84e-06 | 0.8 |
| 84 | 0.0439 | 0.7962 | 0.7962 | 0.8255 (ep 14) | 7.70e-06 | 0.8 |
| 83 | 0.0474 | 0.7953 | 0.7959 | 0.8255 (ep 14) | 8.60e-06 | 0.8 |
| 82 | 0.0469 | 0.7921 | 0.7954 | 0.8255 (ep 14) | 9.55e-06 | 0.8 |
| 81 | 0.0439 | 0.7920 | 0.7956 | 0.8255 (ep 14) | 1.05e-05 | 0.8 |
| 80 | 0.0484 | 0.7942 | 0.7960 | 0.8255 (ep 14) | 1.16e-05 | 0.8 |
| 79 | 0.0461 | 0.7950 | 0.7953 | 0.8255 (ep 14) | 1.27e-05 | 0.8 |
| 78 | 0.0455 | 0.7907 | 0.7948 | 0.8255 (ep 14) | 1.38e-05 | 0.8 |
| 77 | 0.0481 | 0.7917 | 0.7946 | 0.8255 (ep 14) | 1.49e-05 | 0.8 |
| 76 | 0.0480 | 0.7895 | 0.7944 | 0.8255 (ep 14) | 1.61e-05 | 0.8 |
| 75 | 0.0487 | 0.7921 | 0.7954 | 0.8255 (ep 14) | 1.74e-05 | 0.8 |
| 74 | 0.0482 | 0.8026 | 0.7940 | 0.8255 (ep 14) | 1.86e-05 | 0.8 |
| 73 | 0.0478 | 0.7848 | 0.7916 | 0.8255 (ep 14) | 1.99e-05 | 0.8 |
| 72 | 0.0496 | 0.7949 | 0.7913 | 0.8255 (ep 14) | 2.13e-05 | 0.8 |
| 71 | 0.0519 | 0.7851 | 0.7911 | 0.8255 (ep 14) | 2.27e-05 | 0.8 |
| 70 | 0.0497 | 0.7761 | 0.7950 | 0.8255 (ep 14) | 2.41e-05 | 0.8 |
| 69 | 0.0511 | 0.7961 | 0.7970 | 0.8255 (ep 14) | 2.55e-05 | 0.8 |
| 68 | 0.0527 | 0.7861 | 0.8001 | 0.8255 (ep 14) | 2.69e-05 | 0.8 |
| 67 | 0.0522 | 0.8026 | 0.8011 | 0.8255 (ep 14) | 2.84e-05 | 0.8 |
| 66 | 0.0539 | 0.7842 | 0.8028 | 0.8255 (ep 14) | 2.99e-05 | 0.8 |
| 65 | 0.0527 | 0.7985 | 0.8032 | 0.8255 (ep 14) | 3.14e-05 | 0.8 |
| 64 | 0.0542 | 0.8041 | 0.8018 | 0.8255 (ep 14) | 3.30e-05 | 0.8 |
| 63 | 0.0551 | 0.8015 | 0.7996 | 0.8255 (ep 14) | 3.45e-05 | 0.8 |
| 62 | 0.0584 | 0.8034 | 0.7959 | 0.8255 (ep 14) | 3.61e-05 | 0.8 |
| 61 | 0.0546 | 0.7868 | 0.7975 | 0.8255 (ep 14) | 3.77e-05 | 0.8 |
| 60 | 0.0584 | 0.7979 | 0.7990 | 0.8255 (ep 14) | 3.93e-05 | 0.8 |
| 59 | 0.0567 | 0.7819 | 0.8027 | 0.8255 (ep 14) | 4.10e-05 | 0.8 |
| 58 | 0.0577 | 0.7892 | 0.8039 | 0.8255 (ep 14) | 4.26e-05 | 0.8 |
| 57 | 0.0599 | 0.8019 | 0.8031 | 0.8255 (ep 14) | 4.42e-05 | 0.8 |
| 56 | 0.0594 | 0.8053 | 0.8021 | 0.8255 (ep 14) | 4.59e-05 | 0.8 |
| 55 | 0.0613 | 0.8022 | 0.7997 | 0.8255 (ep 14) | 4.75e-05 | 0.8 |
| 54 | 0.0639 | 0.8055 | 0.7990 | 0.8255 (ep 14) | 4.92e-05 | 0.8 |
| 53 | 0.0619 | 0.7807 | 0.7975 | 0.8255 (ep 14) | 5.08e-05 | 0.8 |
| 52 | 0.0632 | 0.7866 | 0.7946 | 0.8255 (ep 14) | 5.25e-05 | 0.8 |
| 51 | 0.0645 | 0.7973 | 0.7937 | 0.8255 (ep 14) | 5.41e-05 | 0.8 |
| 50 | 0.0649 | 0.7967 | 0.7934 | 0.8255 (ep 14) | 5.58e-05 | 0.8 |
| 49 | 0.0658 | 0.7797 | 0.7916 | 0.8255 (ep 14) | 5.74e-05 | 0.8 |
| 48 | 0.0668 | 0.7683 | 0.7927 | 0.8255 (ep 14) | 5.90e-05 | 0.8 |
| 47 | 0.0669 | 0.7827 | 0.7916 | 0.8255 (ep 14) | 6.07e-05 | 0.8 |
| 46 | 0.0696 | 0.8026 | 0.7896 | 0.8255 (ep 14) | 6.23e-05 | 0.8 |
| 45 | 0.0693 | 0.7861 | 0.7932 | 0.8255 (ep 14) | 6.39e-05 | 0.8 |
| 44 | 0.0698 | 0.8032 | 0.7936 | 0.8255 (ep 14) | 6.55e-05 | 0.8 |
| 43 | 0.0715 | 0.7772 | 0.7959 | 0.8255 (ep 14) | 6.70e-05 | 0.8 |
| 42 | 0.0746 | 0.7834 | 0.7946 | 0.8255 (ep 14) | 6.86e-05 | 0.8 |
| 41 | 0.0741 | 0.7945 | 0.7935 | 0.8255 (ep 14) | 7.01e-05 | 0.8 |
| 40 | 0.0755 | 0.7840 | 0.7950 | 0.8255 (ep 14) | 7.16e-05 | 0.8 |
| 39 | 0.0755 | 0.7815 | 0.7962 | 0.8255 (ep 14) | 7.31e-05 | 0.8 |
| 38 | 0.0769 | 0.8049 | 0.7975 | 0.8255 (ep 14) | 7.45e-05 | 0.8 |
| 37 | 0.0792 | 0.7911 | 0.7960 | 0.8255 (ep 14) | 7.59e-05 | 0.8 |
| 36 | 0.0791 | 0.8035 | 0.7970 | 0.8255 (ep 14) | 7.73e-05 | 0.8 |
| 35 | 0.0799 | 0.7877 | 0.7987 | 0.8255 (ep 14) | 7.87e-05 | 0.8 |
| 34 | 0.0821 | 0.7887 | 0.8001 | 0.8255 (ep 14) | 8.01e-05 | 0.8 |
| 33 | 0.0831 | 0.7866 | 0.8013 | 0.8255 (ep 14) | 8.14e-05 | 0.8 |
| 32 | 0.0835 | 0.8020 | 0.8056 | 0.8255 (ep 14) | 8.26e-05 | 0.8 |
| 31 | 0.0860 | 0.7850 | 0.8049 | 0.8255 (ep 14) | 8.39e-05 | 0.8 |
| 30 | 0.0865 | 0.7866 | 0.8055 | 0.8255 (ep 14) | 8.51e-05 | 0.8 |
| 29 | 0.0869 | 0.8062 | 0.8102 | 0.8255 (ep 14) | 8.62e-05 | 0.8 |
| 28 | 0.0899 | 0.7902 | 0.8102 | 0.8255 (ep 14) | 8.73e-05 | 0.8 |
| 27 | 0.0900 | 0.7864 | 0.8120 | 0.8255 (ep 14) | 8.84e-05 | 0.8 |
| 26 | 0.0910 | 0.8052 | 0.8138 | 0.8255 (ep 14) | 8.95e-05 | 0.8 |
| 25 | 0.0938 | 0.8086 | 0.8128 | 0.8255 (ep 14) | 9.05e-05 | 0.8 |
| 24 | 0.0951 | 0.8053 | 0.8120 | 0.8255 (ep 14) | 9.14e-05 | 0.8 |
| 23 | 0.0944 | 0.7979 | 0.8147 | 0.8255 (ep 14) | 9.23e-05 | 0.8 |
| 22 | 0.0952 | 0.8226 | 0.8171 | 0.8255 (ep 14) | 9.32e-05 | 0.8 |
| 21 | 0.0980 | 0.7999 | 0.8198 | 0.8255 (ep 14) | 9.40e-05 | 0.8 |
| 20 | 0.1004 | 0.8020 | 0.8219 | 0.8255 (ep 14) | 9.47e-05 | 0.8 |
| 19 | 0.1014 | 0.8052 | 0.8208 | 0.8255 (ep 14) | 9.55e-05 | 0.8 |
| 18 | 0.1032 | 0.8091 | 0.8186 | 0.8255 (ep 14) | 9.61e-05 | 0.8 |
| 17 | 0.1047 | 0.7990 | 0.8170 | 0.8255 (ep 14) | 9.67e-05 | 0.8 |
| 16 | 0.1073 | 0.7917 | 0.8172 | 0.8255 (ep 14) | 9.73e-05 | 0.8 |
| 15 | 0.1075 | 0.8099 | 0.8133 | 0.8255 (ep 14) | 9.78e-05 | 0.8 |
| 14 | 0.1099 | 0.8255 ⭐ | 0.8123 | 0.8255 (ep 14) | 9.83e-05 | 0.8 |
| 13 | 0.1111 | 0.7968 | 0.8124 | 0.8163 (ep 12) | 9.87e-05 | 0.8 |
| 12 | 0.1133 | 0.8163 ⭐ | 0.8140 | 0.8163 (ep 12) | 9.90e-05 | 0.8 |
| 11 | 0.1163 | 0.8002 | 0.8133 | 0.8125 (ep 10) | 9.93e-05 | 0.8 |
| 10 | 0.1182 | 0.8125 ⭐ | 0.8080 | 0.8125 (ep 10) | 9.96e-05 | 0.8 |
| 9 | 0.1210 | 0.7861 | 0.7997 | 0.8015 (ep 8) | 9.98e-05 | 0.8 |
| 8 | 0.1256 | 0.8015 ⭐ | 0.7819 | 0.8015 (ep 8) | 9.99e-05 | 0.8 |
| 7 | 0.1286 | 0.7670 ⭐ | 0.7825 | 0.7670 (ep 7) | 1.00e-04 | 0.8 |
| 6 | 0.1328 | 0.7451 | 0.7740 | 0.7502 (ep 4) | 1.00e-04 | 0.8 |
| 5 | 0.1369 | 0.7374 | 0.7696 | 0.7502 (ep 4) | 8.00e-05 | 0.8 |
| 4 | 0.1437 | 0.7502 ⭐ | 0.7531 | 0.7502 (ep 4) | 6.00e-05 | 0.8 |
| 3 | 0.1733 | 0.6717 ⭐ | 0.7051 | 0.6717 (ep 3) | 4.00e-05 | 0.8 |
| 2 | 0.4890 | 0.5876 ⭐ | 0.5860 | 0.5876 (ep 2) | 2.00e-05 | 0.8 |
| 1 | 0.7842 | 0.4810 ⭐ | 0.4646 | 0.4810 (ep 1) | 1.00e-10 | 0.8 |

## Last 80 log lines

_The log counts epochs from 0; the tables above count from 1._

```
[seed 543] epoch  53/100 | lr 5.08e-05 | train loss 0.0619 | val ROC-AUC 0.7807 | best val 0.8255 @ep14 | EMA val 0.7975 | 49s (train 44s, eval 5s) | GPU max 53C | ETA<= 0.6h
[seed 543] epoch  54/100 | lr 4.92e-05 | train loss 0.0639 | val ROC-AUC 0.8055 | best val 0.8255 @ep14 | EMA val 0.7990 | 49s (train 45s, eval 5s) | GPU max 52C | ETA<= 0.6h
[seed 543] epoch  55/100 | lr 4.75e-05 | train loss 0.0613 | val ROC-AUC 0.8022 | best val 0.8255 @ep14 | EMA val 0.7997 | 49s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.6h
[seed 543] epoch  56/100 | lr 4.59e-05 | train loss 0.0594 | val ROC-AUC 0.8053 | best val 0.8255 @ep14 | EMA val 0.8021 | 48s (train 44s, eval 5s) | GPU max 53C | ETA<= 0.6h
[seed 543] epoch  57/100 | lr 4.42e-05 | train loss 0.0599 | val ROC-AUC 0.8019 | best val 0.8255 @ep14 | EMA val 0.8031 | 49s (train 44s, eval 5s) | GPU max 53C | ETA<= 0.6h
[seed 543] epoch  58/100 | lr 4.26e-05 | train loss 0.0577 | val ROC-AUC 0.7892 | best val 0.8255 @ep14 | EMA val 0.8039 | 49s (train 44s, eval 5s) | GPU max 53C | ETA<= 0.6h
[seed 543] epoch  59/100 | lr 4.10e-05 | train loss 0.0567 | val ROC-AUC 0.7819 | best val 0.8255 @ep14 | EMA val 0.8027 | 49s (train 44s, eval 5s) | GPU max 53C | ETA<= 0.6h
[seed 543] epoch  60/100 | lr 3.93e-05 | train loss 0.0584 | val ROC-AUC 0.7979 | best val 0.8255 @ep14 | EMA val 0.7990 | 49s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.5h
[seed 543] epoch  61/100 | lr 3.77e-05 | train loss 0.0546 | val ROC-AUC 0.7868 | best val 0.8255 @ep14 | EMA val 0.7975 | 49s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.5h
[seed 543] epoch  62/100 | lr 3.61e-05 | train loss 0.0584 | val ROC-AUC 0.8034 | best val 0.8255 @ep14 | EMA val 0.7959 | 48s (train 44s, eval 5s) | GPU max 53C | ETA<= 0.5h
[seed 543] epoch  63/100 | lr 3.45e-05 | train loss 0.0551 | val ROC-AUC 0.8015 | best val 0.8255 @ep14 | EMA val 0.7996 | 49s (train 45s, eval 5s) | GPU max 52C | ETA<= 0.5h
[seed 543] epoch  64/100 | lr 3.30e-05 | train loss 0.0542 | val ROC-AUC 0.8041 | best val 0.8255 @ep14 | EMA val 0.8018 | 49s (train 45s, eval 5s) | GPU max 52C | ETA<= 0.5h
[seed 543] epoch  65/100 | lr 3.14e-05 | train loss 0.0527 | val ROC-AUC 0.7985 | best val 0.8255 @ep14 | EMA val 0.8032 | 49s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.5h
[seed 543] epoch  66/100 | lr 2.99e-05 | train loss 0.0539 | val ROC-AUC 0.7842 | best val 0.8255 @ep14 | EMA val 0.8028 | 48s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.5h
[seed 543] epoch  67/100 | lr 2.84e-05 | train loss 0.0522 | val ROC-AUC 0.8026 | best val 0.8255 @ep14 | EMA val 0.8011 | 48s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.4h
[seed 543] epoch  68/100 | lr 2.69e-05 | train loss 0.0527 | val ROC-AUC 0.7861 | best val 0.8255 @ep14 | EMA val 0.8001 | 48s (train 43s, eval 5s) | GPU max 52C | ETA<= 0.4h
[seed 543] epoch  69/100 | lr 2.55e-05 | train loss 0.0511 | val ROC-AUC 0.7961 | best val 0.8255 @ep14 | EMA val 0.7970 | 49s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.4h
[seed 543] epoch  70/100 | lr 2.41e-05 | train loss 0.0497 | val ROC-AUC 0.7761 | best val 0.8255 @ep14 | EMA val 0.7950 | 49s (train 45s, eval 5s) | GPU max 52C | ETA<= 0.4h
[seed 543] epoch  71/100 | lr 2.27e-05 | train loss 0.0519 | val ROC-AUC 0.7851 | best val 0.8255 @ep14 | EMA val 0.7911 | 49s (train 45s, eval 5s) | GPU max 52C | ETA<= 0.4h
[seed 543] epoch  72/100 | lr 2.13e-05 | train loss 0.0496 | val ROC-AUC 0.7949 | best val 0.8255 @ep14 | EMA val 0.7913 | 49s (train 45s, eval 5s) | GPU max 52C | ETA<= 0.4h
[seed 543] epoch  73/100 | lr 1.99e-05 | train loss 0.0478 | val ROC-AUC 0.7848 | best val 0.8255 @ep14 | EMA val 0.7916 | 48s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.4h
[seed 543] epoch  74/100 | lr 1.86e-05 | train loss 0.0482 | val ROC-AUC 0.8026 | best val 0.8255 @ep14 | EMA val 0.7940 | 49s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.4h
[seed 543] epoch  75/100 | lr 1.74e-05 | train loss 0.0487 | val ROC-AUC 0.7921 | best val 0.8255 @ep14 | EMA val 0.7954 | 49s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.3h
[seed 543] epoch  76/100 | lr 1.61e-05 | train loss 0.0480 | val ROC-AUC 0.7895 | best val 0.8255 @ep14 | EMA val 0.7944 | 49s (train 44s, eval 5s) | GPU max 52C | ETA<= 0.3h
[seed 543] epoch  77/100 | lr 1.49e-05 | train loss 0.0481 | val ROC-AUC 0.7917 | best val 0.8255 @ep14 | EMA val 0.7946 | 50s (train 45s, eval 5s) | GPU max 51C | ETA<= 0.3h
[seed 543] epoch  78/100 | lr 1.38e-05 | train loss 0.0455 | val ROC-AUC 0.7907 | best val 0.8255 @ep14 | EMA val 0.7948 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.3h
[seed 543] epoch  79/100 | lr 1.27e-05 | train loss 0.0461 | val ROC-AUC 0.7950 | best val 0.8255 @ep14 | EMA val 0.7953 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.3h
[seed 543] epoch  80/100 | lr 1.16e-05 | train loss 0.0484 | val ROC-AUC 0.7942 | best val 0.8255 @ep14 | EMA val 0.7960 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.3h
[seed 543] epoch  81/100 | lr 1.05e-05 | train loss 0.0439 | val ROC-AUC 0.7920 | best val 0.8255 @ep14 | EMA val 0.7956 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.3h
[seed 543] epoch  82/100 | lr 9.55e-06 | train loss 0.0469 | val ROC-AUC 0.7921 | best val 0.8255 @ep14 | EMA val 0.7954 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.2h
[seed 543] epoch  83/100 | lr 8.60e-06 | train loss 0.0474 | val ROC-AUC 0.7953 | best val 0.8255 @ep14 | EMA val 0.7959 | 49s (train 45s, eval 5s) | GPU max 51C | ETA<= 0.2h
[seed 543] epoch  84/100 | lr 7.70e-06 | train loss 0.0439 | val ROC-AUC 0.7962 | best val 0.8255 @ep14 | EMA val 0.7962 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.2h
[seed 543] epoch  85/100 | lr 6.84e-06 | train loss 0.0438 | val ROC-AUC 0.7982 | best val 0.8255 @ep14 | EMA val 0.7958 | 49s (train 45s, eval 5s) | GPU max 51C | ETA<= 0.2h
[seed 543] epoch  86/100 | lr 6.03e-06 | train loss 0.0428 | val ROC-AUC 0.7977 | best val 0.8255 @ep14 | EMA val 0.7964 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.2h
[seed 543] epoch  87/100 | lr 5.26e-06 | train loss 0.0444 | val ROC-AUC 0.7922 | best val 0.8255 @ep14 | EMA val 0.7966 | 48s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.2h
[seed 543] epoch  88/100 | lr 4.55e-06 | train loss 0.0442 | val ROC-AUC 0.7931 | best val 0.8255 @ep14 | EMA val 0.7974 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.2h
[seed 543] epoch  89/100 | lr 3.89e-06 | train loss 0.0422 | val ROC-AUC 0.7985 | best val 0.8255 @ep14 | EMA val 0.7977 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.1h
[seed 543] epoch  90/100 | lr 3.27e-06 | train loss 0.0440 | val ROC-AUC 0.7935 | best val 0.8255 @ep14 | EMA val 0.7978 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.1h
[seed 543] epoch  91/100 | lr 2.71e-06 | train loss 0.0447 | val ROC-AUC 0.7965 | best val 0.8255 @ep14 | EMA val 0.7977 | 49s (train 45s, eval 5s) | GPU max 51C | ETA<= 0.1h
[seed 543] epoch  92/100 | lr 2.20e-06 | train loss 0.0440 | val ROC-AUC 0.7926 | best val 0.8255 @ep14 | EMA val 0.7975 | 49s (train 45s, eval 5s) | GPU max 51C | ETA<= 0.1h
[seed 543] epoch  93/100 | lr 1.74e-06 | train loss 0.0433 | val ROC-AUC 0.7877 | best val 0.8255 @ep14 | EMA val 0.7971 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.1h
[seed 543] epoch  94/100 | lr 1.33e-06 | train loss 0.0429 | val ROC-AUC 0.7989 | best val 0.8255 @ep14 | EMA val 0.7970 | 48s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.1h
[seed 543] epoch  95/100 | lr 9.81e-07 | train loss 0.0431 | val ROC-AUC 0.7956 | best val 0.8255 @ep14 | EMA val 0.7968 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.1h
[seed 543] epoch  96/100 | lr 6.82e-07 | train loss 0.0426 | val ROC-AUC 0.7962 | best val 0.8255 @ep14 | EMA val 0.7966 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.1h
[seed 543] epoch  97/100 | lr 4.37e-07 | train loss 0.0420 | val ROC-AUC 0.7894 | best val 0.8255 @ep14 | EMA val 0.7966 | 49s (train 45s, eval 5s) | GPU max 51C | ETA<= 0.0h
[seed 543] epoch  98/100 | lr 2.46e-07 | train loss 0.0427 | val ROC-AUC 0.7940 | best val 0.8255 @ep14 | EMA val 0.7965 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.0h
[seed 543] epoch  99/100 | lr 1.09e-07 | train loss 0.0415 | val ROC-AUC 0.7991 | best val 0.8255 @ep14 | EMA val 0.7965 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.0h
[seed 543] epoch 100/100 | lr 2.73e-08 | train loss 0.0424 | val ROC-AUC 0.7915 | best val 0.8255 @ep14 | EMA val 0.7964 | 49s (train 44s, eval 5s) | GPU max 51C | ETA<= 0.0h
[seed 543] FINAL TEST (evaluated once): raw epoch 14 val 0.8255 test 0.7734 | EMA epoch 20 val 0.8219 test 0.7782 (ROC-AUC, higher is better)
--- cell 17 ---
GPS + EMA | gps_conf_GPS_ema_ep100_molhiv | ROC-AUC (higher is better)
 seed  epochs  raw_epoch  raw_val  raw_test  ema_epoch  ema_val  ema_test  hours  train_s_per_epoch  total_s_per_epoch
  101 100/100         30   0.8225    0.7840         38   0.8111    0.7927 1.3385            43.6222            48.1855
  202 100/100         15   0.8166    0.7669         16   0.8085    0.7774 1.3481            43.9524            48.5310
  323 100/100         24   0.8175    0.7644         21   0.7994    0.7783 1.3530            44.1291            48.7094
  432 100/100         40   0.8146    0.7984         49   0.7987    0.8011 1.3573            44.2799            48.8643
  543 100/100         14   0.8255    0.7734         20   0.8219    0.7782 1.3555            44.2190            48.7997
mean ± sample SD (ddof=1) over 5 seed(s): raw test 0.7774 ± 0.0140 | EMA test 0.7855 ± 0.0108
A mean ± SD over fewer than 3 seeds is only a description; do not call it a confidence interval.
run manifest: 5 row(s) -> /home/student/thesis/outputs/pairhgt/outputs/confirmatory_molhiv/run_manifest.csv
    model              gpu  seeds  params  train_s_per_epoch  val_eval_s_per_epoch  total_s_per_epoch  hours_per_seed  time_vs_GPS+EMA
GPS + EMA NVIDIA RTX A4000      5  558673              44.04                  4.56              48.62            1.35              1.0
train = training steps incl. EMA update; val_eval = validation of raw + EMA weights; no test pass inside an epoch (protocol v2). For the thesis cost table use only seeds that had the GPU alone.
--- cell 19 ---
=== PairHGT  minus  GPS + EMA   (ogbg-molhiv, ROC-AUC, higher is better; matched seeds) ===
  no matched finished seeds with a final test result yet
GPS sanity line (ogbg-molhiv, raw weights, 5 seed(s)): ours 0.7774 ± 0.0140 vs published 0.7880 ± 0.0101 (10 seeds): gap -0.0106 = -1.05 published SDs  (within 2 published SDs)
--- cell 21 ---
        dataset  metric weights  n_seeds  gps_mean  pairhgt_mean  diff_mean  ci_lo  ci_hi  seeds_in_favour  diff_in_published_sd
   ogbg-molpcba      AP     raw        5    0.2904        0.2963     0.0059 0.0021 0.0097              5.0                2.1143
   ogbg-molpcba      AP     EMA        5    0.2980        0.3061     0.0082 0.0039 0.0124              5.0                2.9111
  Peptides-func      AP     raw        0       NaN           NaN        NaN    NaN    NaN              NaN                   NaN
  Peptides-func      AP     EMA        0       NaN           NaN        NaN    NaN    NaN              NaN                   NaN
Peptides-struct     MAE     raw        0       NaN           NaN        NaN    NaN    NaN              NaN                   NaN
Peptides-struct     MAE     EMA        0       NaN           NaN        NaN    NaN    NaN              NaN                   NaN
    ogbg-molhiv ROC-AUC     raw        0       NaN           NaN        NaN    NaN    NaN              NaN                   NaN
    ogbg-molhiv ROC-AUC     EMA        0       NaN           NaN        NaN    NaN    NaN              NaN                   NaN
-> /home/student/thesis/outputs/pairhgt/outputs/confirmatory_all_datasets/summary_all_datasets.csv and .tex (molpcba read from /home/student/thesis/outputs/pairhgt/checkpoints, read only)
--- cell 23 ---
===== 2026-11-23 08:26:47 notebook run ended (exit 0); executed notebook: /home/student/thesis/outputs/lab_runs/notebooks_gen/molhiv_GPS_ema_20261123_014004.ipynb =====
```
