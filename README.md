# Effective Training Strategies for Deep Learning-based Precipitation Nowcasting and Estimation

In this software, we provided the following implementations in PyTorch:
- Model and Dataset implementation (`model.py` and `dataset.py`): U-Net based model (1x1 resolution) for precipitation nowcasting and estimation, and the dataset for each target task. 
- Codes for experiments: Codes for pre-training and fine-tuning the model, and evaluating the performance of the trained model.

## General Information
- Authors: Jihoon Ko*, Kyuhan Lee*, Hyunjin Hwang*, Seok-Woo Son, Kijung Shin
- Version: 1.0

In order to download dummy checkpoints for running demos, use the following commands:

```bash
$ wget https://www.dropbox.com/s/p3062yite6lvnq3/finetuned.pkt -O precipitation\ nowcasting/checkpoints/pretrained.pkt
$ wget https://www.dropbox.com/s/p3062yite6lvnq3/finetuned.pkt -O precipitation\ nowcasting/checkpoints/finetuned.pkt
```

For more details, see [user_guide.pdf](https://github.com/jihoonko/precipitation-nowcasting/blob/master/user_guide.pdf).
