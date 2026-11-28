# GPS + EMA · ogbg-molhiv (ROC-AUC) — seed 101

[← all models](../README.md) · PairHGT notebook · ogbg-molhiv

| | |
|---|---|
| State | **finished** |
| Epochs | 100 of 100 |
| Best validation ROC-AUC | **0.8225** at epoch 30 |
| Best validation ROC-AUC, EMA weights | 0.8111 at epoch 38 |
| Test ROC-AUC | raw 0.7840 / ema 0.7927 (final) |
| Seed | 101 |
| Parameters | 558,673 |
| Minutes per epoch (last 5, incl. validation) | 0.8 |
| Training time so far | 1.3 h |
| Training time left | done |
| Sessions (start + resumes) | 1 |
| Hottest GPU reading | 61.0 °C |
| Last update | 2026-11-23 03:00 (135.1 h ago) |

![curves](pairhgt_molhiv_GPS_ema_seed101.png)

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
| raw | 30 | 0.8225 | 0.7840 |
| ema | 38 | 0.8111 | 0.7927 |

## Every epoch (newest first)

| Epoch | Train loss | Val ROC-AUC | Val ROC-AUC (EMA weights) | Best so far | LR | Minutes |
|---|---|---|---|---|---|---|
| 100 | 0.0408 | 0.7932 | 0.7934 | 0.8225 (ep 30) | 2.73e-08 | 0.8 |
| 99 | 0.0409 | 0.7972 | 0.7935 | 0.8225 (ep 30) | 1.09e-07 | 0.8 |
| 98 | 0.0406 | 0.7890 | 0.7936 | 0.8225 (ep 30) | 2.46e-07 | 0.8 |
| 97 | 0.0402 | 0.7959 | 0.7938 | 0.8225 (ep 30) | 4.37e-07 | 0.8 |
| 96 | 0.0396 | 0.7868 | 0.7940 | 0.8225 (ep 30) | 6.82e-07 | 0.8 |
| 95 | 0.0434 | 0.7925 | 0.7942 | 0.8225 (ep 30) | 9.81e-07 | 0.8 |
| 94 | 0.0420 | 0.7935 | 0.7945 | 0.8225 (ep 30) | 1.33e-06 | 0.8 |
| 93 | 0.0414 | 0.7951 | 0.7946 | 0.8225 (ep 30) | 1.74e-06 | 0.8 |
| 92 | 0.0405 | 0.7921 | 0.7948 | 0.8225 (ep 30) | 2.20e-06 | 0.8 |
| 91 | 0.0404 | 0.7931 | 0.7953 | 0.8225 (ep 30) | 2.71e-06 | 0.8 |
| 90 | 0.0413 | 0.7962 | 0.7962 | 0.8225 (ep 30) | 3.27e-06 | 0.8 |
| 89 | 0.0414 | 0.7928 | 0.7969 | 0.8225 (ep 30) | 3.89e-06 | 0.8 |
| 88 | 0.0419 | 0.7928 | 0.7972 | 0.8225 (ep 30) | 4.55e-06 | 0.8 |
| 87 | 0.0419 | 0.7980 | 0.7974 | 0.8225 (ep 30) | 5.26e-06 | 0.8 |
| 86 | 0.0421 | 0.7959 | 0.7973 | 0.8225 (ep 30) | 6.03e-06 | 0.8 |
| 85 | 0.0436 | 0.7980 | 0.7968 | 0.8225 (ep 30) | 6.84e-06 | 0.8 |
| 84 | 0.0422 | 0.7960 | 0.7967 | 0.8225 (ep 30) | 7.70e-06 | 0.8 |
| 83 | 0.0452 | 0.7973 | 0.7976 | 0.8225 (ep 30) | 8.60e-06 | 0.8 |
| 82 | 0.0432 | 0.7966 | 0.7985 | 0.8225 (ep 30) | 9.55e-06 | 0.8 |
| 81 | 0.0453 | 0.8004 | 0.7986 | 0.8225 (ep 30) | 1.05e-05 | 0.8 |
| 80 | 0.0448 | 0.8003 | 0.7983 | 0.8225 (ep 30) | 1.16e-05 | 0.8 |
| 79 | 0.0452 | 0.7987 | 0.7976 | 0.8225 (ep 30) | 1.27e-05 | 0.8 |
| 78 | 0.0451 | 0.7932 | 0.7977 | 0.8225 (ep 30) | 1.38e-05 | 0.8 |
| 77 | 0.0447 | 0.7926 | 0.7984 | 0.8225 (ep 30) | 1.49e-05 | 0.8 |
| 76 | 0.0451 | 0.7983 | 0.7989 | 0.8225 (ep 30) | 1.61e-05 | 0.8 |
| 75 | 0.0483 | 0.7897 | 0.7997 | 0.8225 (ep 30) | 1.74e-05 | 0.8 |
| 74 | 0.0465 | 0.7992 | 0.8002 | 0.8225 (ep 30) | 1.86e-05 | 0.8 |
| 73 | 0.0474 | 0.7993 | 0.8001 | 0.8225 (ep 30) | 1.99e-05 | 0.8 |
| 72 | 0.0477 | 0.8007 | 0.7996 | 0.8225 (ep 30) | 2.13e-05 | 0.8 |
| 71 | 0.0483 | 0.7973 | 0.7998 | 0.8225 (ep 30) | 2.27e-05 | 0.8 |
| 70 | 0.0508 | 0.7836 | 0.8007 | 0.8225 (ep 30) | 2.41e-05 | 0.8 |
| 69 | 0.0508 | 0.7928 | 0.8032 | 0.8225 (ep 30) | 2.55e-05 | 0.8 |
| 68 | 0.0501 | 0.8109 | 0.8021 | 0.8225 (ep 30) | 2.69e-05 | 0.8 |
| 67 | 0.0488 | 0.7925 | 0.8030 | 0.8225 (ep 30) | 2.84e-05 | 0.8 |
| 66 | 0.0495 | 0.7851 | 0.8030 | 0.8225 (ep 30) | 2.99e-05 | 0.8 |
| 65 | 0.0527 | 0.8124 | 0.8025 | 0.8225 (ep 30) | 3.14e-05 | 0.8 |
| 64 | 0.0519 | 0.7906 | 0.8019 | 0.8225 (ep 30) | 3.30e-05 | 0.8 |
| 63 | 0.0535 | 0.7983 | 0.8020 | 0.8225 (ep 30) | 3.45e-05 | 0.8 |
| 62 | 0.0519 | 0.8013 | 0.8018 | 0.8225 (ep 30) | 3.61e-05 | 0.8 |
| 61 | 0.0565 | 0.8090 | 0.8014 | 0.8225 (ep 30) | 3.77e-05 | 0.8 |
| 60 | 0.0561 | 0.7979 | 0.7996 | 0.8225 (ep 30) | 3.93e-05 | 0.8 |
| 59 | 0.0541 | 0.7908 | 0.8000 | 0.8225 (ep 30) | 4.10e-05 | 0.8 |
| 58 | 0.0561 | 0.7973 | 0.8006 | 0.8225 (ep 30) | 4.26e-05 | 0.8 |
| 57 | 0.0586 | 0.7861 | 0.8019 | 0.8225 (ep 30) | 4.42e-05 | 0.8 |
| 56 | 0.0581 | 0.7876 | 0.8028 | 0.8225 (ep 30) | 4.59e-05 | 0.8 |
| 55 | 0.0602 | 0.7961 | 0.8038 | 0.8225 (ep 30) | 4.75e-05 | 0.8 |
| 54 | 0.0621 | 0.8169 | 0.8032 | 0.8225 (ep 30) | 4.92e-05 | 0.8 |
| 53 | 0.0614 | 0.8034 | 0.8028 | 0.8225 (ep 30) | 5.08e-05 | 0.8 |
| 52 | 0.0612 | 0.7963 | 0.8018 | 0.8225 (ep 30) | 5.25e-05 | 0.8 |
| 51 | 0.0632 | 0.7860 | 0.8048 | 0.8225 (ep 30) | 5.41e-05 | 0.8 |
| 50 | 0.0633 | 0.8126 | 0.8056 | 0.8225 (ep 30) | 5.58e-05 | 0.8 |
| 49 | 0.0635 | 0.7926 | 0.8058 | 0.8225 (ep 30) | 5.74e-05 | 0.8 |
| 48 | 0.0668 | 0.7955 | 0.8069 | 0.8225 (ep 30) | 5.90e-05 | 0.8 |
| 47 | 0.0655 | 0.7977 | 0.8081 | 0.8225 (ep 30) | 6.07e-05 | 0.8 |
| 46 | 0.0657 | 0.8056 | 0.8106 | 0.8225 (ep 30) | 6.23e-05 | 0.8 |
| 45 | 0.0695 | 0.8201 | 0.8104 | 0.8225 (ep 30) | 6.39e-05 | 0.8 |
| 44 | 0.0694 | 0.7927 | 0.8105 | 0.8225 (ep 30) | 6.55e-05 | 0.8 |
| 43 | 0.0704 | 0.8039 | 0.8095 | 0.8225 (ep 30) | 6.70e-05 | 0.8 |
| 42 | 0.0702 | 0.7838 | 0.8094 | 0.8225 (ep 30) | 6.86e-05 | 0.8 |
| 41 | 0.0729 | 0.8097 | 0.8076 | 0.8225 (ep 30) | 7.01e-05 | 0.8 |
| 40 | 0.0748 | 0.7941 | 0.8067 | 0.8225 (ep 30) | 7.16e-05 | 0.8 |
| 39 | 0.0741 | 0.8029 | 0.8091 | 0.8225 (ep 30) | 7.31e-05 | 0.8 |
| 38 | 0.0758 | 0.7998 | 0.8111 | 0.8225 (ep 30) | 7.45e-05 | 0.8 |
| 37 | 0.0766 | 0.8020 | 0.8098 | 0.8225 (ep 30) | 7.59e-05 | 0.8 |
| 36 | 0.0787 | 0.8068 | 0.8091 | 0.8225 (ep 30) | 7.73e-05 | 0.8 |
| 35 | 0.0792 | 0.7955 | 0.8102 | 0.8225 (ep 30) | 7.87e-05 | 0.8 |
| 34 | 0.0793 | 0.8119 | 0.8097 | 0.8225 (ep 30) | 8.01e-05 | 0.8 |
| 33 | 0.0823 | 0.8085 | 0.8095 | 0.8225 (ep 30) | 8.14e-05 | 0.8 |
| 32 | 0.0824 | 0.7908 | 0.8092 | 0.8225 (ep 30) | 8.26e-05 | 0.8 |
| 31 | 0.0848 | 0.8155 | 0.8058 | 0.8225 (ep 30) | 8.39e-05 | 0.8 |
| 30 | 0.0844 | 0.8225 ⭐ | 0.8042 | 0.8225 (ep 30) | 8.51e-05 | 0.8 |
| 29 | 0.0860 | 0.8048 | 0.8049 | 0.8155 (ep 18) | 8.62e-05 | 0.8 |
| 28 | 0.0864 | 0.7934 | 0.8042 | 0.8155 (ep 18) | 8.73e-05 | 0.8 |
| 27 | 0.0885 | 0.8151 | 0.8016 | 0.8155 (ep 18) | 8.84e-05 | 0.8 |
| 26 | 0.0895 | 0.7966 | 0.8027 | 0.8155 (ep 18) | 8.95e-05 | 0.8 |
| 25 | 0.0910 | 0.7958 | 0.8051 | 0.8155 (ep 18) | 9.05e-05 | 0.8 |
| 24 | 0.0929 | 0.7917 | 0.8065 | 0.8155 (ep 18) | 9.14e-05 | 0.8 |
| 23 | 0.0925 | 0.8001 | 0.8055 | 0.8155 (ep 18) | 9.23e-05 | 0.8 |
| 22 | 0.0942 | 0.7961 | 0.8066 | 0.8155 (ep 18) | 9.32e-05 | 0.8 |
| 21 | 0.0963 | 0.7873 | 0.8095 | 0.8155 (ep 18) | 9.40e-05 | 0.8 |
| 20 | 0.0968 | 0.7910 | 0.8084 | 0.8155 (ep 18) | 9.47e-05 | 0.8 |
| 19 | 0.0991 | 0.7900 | 0.8093 | 0.8155 (ep 18) | 9.55e-05 | 0.8 |
| 18 | 0.1000 | 0.8155 ⭐ | 0.8081 | 0.8155 (ep 18) | 9.61e-05 | 0.8 |
| 17 | 0.1029 | 0.7784 | 0.8073 | 0.8014 (ep 12) | 9.67e-05 | 0.8 |
| 16 | 0.1025 | 0.7718 | 0.8036 | 0.8014 (ep 12) | 9.73e-05 | 0.8 |
| 15 | 0.1055 | 0.7849 | 0.8006 | 0.8014 (ep 12) | 9.78e-05 | 0.8 |
| 14 | 0.1066 | 0.7841 | 0.8021 | 0.8014 (ep 12) | 9.83e-05 | 0.8 |
| 13 | 0.1103 | 0.7911 | 0.7989 | 0.8014 (ep 12) | 9.87e-05 | 0.8 |
| 12 | 0.1120 | 0.8014 ⭐ | 0.7947 | 0.8014 (ep 12) | 9.90e-05 | 0.8 |
| 11 | 0.1138 | 0.7562 | 0.7927 | 0.7653 (ep 10) | 9.93e-05 | 0.8 |
| 10 | 0.1171 | 0.7653 ⭐ | 0.7771 | 0.7653 (ep 10) | 9.96e-05 | 0.8 |
| 9 | 0.1190 | 0.7651 ⭐ | 0.7654 | 0.7651 (ep 9) | 9.98e-05 | 0.8 |
| 8 | 0.1238 | 0.7468 | 0.7569 | 0.7624 (ep 7) | 9.99e-05 | 0.8 |
| 7 | 0.1276 | 0.7624 ⭐ | 0.7441 | 0.7624 (ep 7) | 1.00e-04 | 0.8 |
| 6 | 0.1331 | 0.7169 | 0.7366 | 0.7305 (ep 5) | 1.00e-04 | 0.8 |
| 5 | 0.1380 | 0.7305 ⭐ | 0.7275 | 0.7305 (ep 5) | 8.00e-05 | 0.8 |
| 4 | 0.1433 | 0.6966 | 0.7212 | 0.7128 (ep 3) | 6.00e-05 | 0.8 |
| 3 | 0.1544 | 0.7128 ⭐ | 0.6814 | 0.7128 (ep 3) | 4.00e-05 | 0.8 |
| 2 | 0.3119 | 0.6376 ⭐ | 0.6239 | 0.6376 (ep 2) | 2.00e-05 | 0.8 |
| 1 | 0.6077 | 0.4470 ⭐ | 0.4423 | 0.4470 (ep 1) | 1.00e-10 | 0.8 |

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
