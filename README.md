---
dataset_info:
  features:
  - name: messages
    list:
    - name: role
      dtype: string
    - name: content
      dtype: string
  splits:
  - name: train
    num_bytes: 13541943
    num_examples: 7784
  download_size: 13536993
  dataset_size: 13541943
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
