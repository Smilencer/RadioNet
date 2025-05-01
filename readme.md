# RadioNet

This model is intended solely for academic research and is not validated for clinical deployment.

CUDA_VISIBLE_DEVICES=0 nohup python3 -u train_radionet_Synapse.py >train_radionet_Synapse.log 2>&1 & 

CUDA_VISIBLE_DEVICES=0 nohup python3 -u train_radionet_ACDC.py >train_radionet_ACDC.log 2>&1 &
