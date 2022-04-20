<!-- Generated by ./scripts/utils/show_enh_score.sh -->
# RESULTS
## Environments
- date: `Fri May 28 20:55:14 CST 2021`
- python version: `3.8.5 (default, Sep  4 2020, 07:30:14)  [GCC 7.3.0]`
- espnet version: `espnet 0.9.9`
- pytorch version: `pytorch 1.4.0`
- Git hash: `be73d0de071e9a7fcaf98ad2e5c94dad9ca73cda`
  - Commit date: `Fri May 28 19:14:45 2021 +0800`


## enh_train_enh_blstm_tf_raw

 - config: ./conf/tuning/train_enh_blstm_tf.yaml
 - Pretrained model: https://zenodo.org/record/4923697

| dataset                           | STOI | SAR   | SDR   | SIR  |
| --------------------------------- | ---- | ----- | ----- | ---- |
| enhanced_cv_synthetic             | 0.95 | 18.63 | 18.63 | 0.00 |
| enhanced_tt_synthetic_no_reverb   | 0.92 | 10.92 | 10.92 | 0.00 |
| enhanced_tt_synthetic_with_reverb | 0.85 | 9.31  | 9.31  | 0.00 |

<!-- Generated by ./scripts/utils/show_enh_score.sh -->
# RESULTS
## Environments
- date: `Thu Feb 10 23:11:40 CST 2022`
- python version: `3.8.12 (default, Oct 12 2021, 13:49:34)  [GCC 7.5.0]`
- espnet version: `espnet 0.10.5a1`
- pytorch version: `pytorch 1.9.1`
- Git hash: `6f66283b9eed7b0d5e5643feb18d8f60118a4afc`
  - Commit date: `Mon Dec 13 15:30:29 2021 +0800`


## enh_train_enh_dccrn_raw

- config: ./conf/tuning/train_enh_dccrn.yaml
- download_model: https://huggingface.co/Johnson-Lsx/Shaoxiong_Lin_dns_ins20_enh_enh_train_enh_dccrn_raw

| dataset                           | PESQ | STOI | SAR   | SDR   | SIR  | SI_SNR |
| --------------------------------- | ---- | ---- | ----- | ----- | ---- | ------ |
| enhanced_cv_synthetic             | 3.72 | 0.98 | 24.69 | 24.69 | 0.00 | 24.22  |
| enhanced_tt_synthetic_no_reverb   | 3.29 | 0.96 | 17.69 | 17.69 | 0.00 | 17.50  |
| enhanced_tt_synthetic_with_reverb | 2.54 | 0.81 | 10.45 | 10.45 | 0.00 | 9.72   |

Note: Here, the model is only trained on data without reverberation.
Note: Here, the PESQ score is calculated based on https://github.com/vBaiCai/python-pesq.