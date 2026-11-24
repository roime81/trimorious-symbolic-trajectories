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
    num_bytes: 920267
    num_examples: 543
  download_size: 922024
  dataset_size: 920267
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
